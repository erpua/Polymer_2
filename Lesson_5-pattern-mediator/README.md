# \<Lesson_5-pattern-mediator\>

Error: survey-questions.html.js:39 Uncaught TypeError: Cannot read property 'options' of undefined
at callWithPressing (survey-questions.html.js:39)
Way out: ready() {
super.ready();
window.addEventListener('keypress', this.callWithPressing.bind(this));
}
