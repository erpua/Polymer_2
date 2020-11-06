# \<Lesson_5-pattern-mediator\>

Error: survey-questions.html.js:39 Uncaught TypeError: Cannot read property 'options' of undefined
at callWithPressing (survey-questions.html.js:39)
Way out: ready() {
super.ready();
window.addEventListener('keypress', this.callWithPressing.bind(this));
}

- <template is="dom-if" if="[[!cancelled]]"> =>meaning: if not true cancelled propoerty

- add dom-if in survey-element.html: <link
    rel="import"
    href="../../bower_components/polymer/lib/elements/dom-if.html"
  />

  - on-track event = while key is down

- FOR GESTOR EVENTS MUST BU CHANGED => class SurveyElement extends Polymer.Element
  => class SurveyElement extends Polymer.GestureEventListeners(Polymer.Element)
- IN survey-element.html add <link rel="import" href="../../bower_components/polymer/lib/mixins/gesture-event-listeners.html">
