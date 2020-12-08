# \<test-element\>

command: polymer test -l chrome

possible error:

- java is not present on your PATH.
  Please install it: https://java.com/download/
  error: cli runtime exception: java is not present on your PATH.
  Please install it: https://java.com/download/

- to run element => polymer serve
- to test element in terminal => polymer test -l chrome
  if not working try in browser root
- to test element in browser => http://127.0.0.1:8081/components/test-element/test/index.html

Polymer news:

- https://github.com/Polymer/news

TIPS for similar project if error:

"Could not find WCT plugin istanbul" => ./node_modules/web-component-tester/bin/wct/ -l chrome
