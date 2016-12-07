# DOM-Text-Binder
Dom-Text-Binder is a javascript library that allows to bind special tags in html Dom.
# Usage
Include the parser.js
```html
 <script src="js/parser.js"></script>
```
Just bind any text using simple syntax:-
 ```
 {{variable}}
 ```
 Use the below javascript to set the value for this variable
 ```javascript
window.onload = function(){
  parser.init({
    parse: function(){
    var reference = this;
setValues(this);
    }
  });
}
function setValues(reference){
  reference.variable= "value";
}
```
