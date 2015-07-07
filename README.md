# ngKnob

A simple directive that simulates a real-world *volume knob*. This was built as an example at [Fullstack Academy](http://www.fullstackacademy.com/).
  
# Running the example

Use `python -m HTTPSimpleServer` or `npm install -g http-server && http-server` to run the example code.

# Using it in your application

`npm install ng-knob`.

Include `dist/ngKnob.js` in your application as a `<script>` and as well as link the `dist/ngKnob.css` stylesheet. Merge your application with ngKnob (`angular.module('YourApp', ['ngKnob'])`) and use the `<ng-knob>` directive as seen in the example.