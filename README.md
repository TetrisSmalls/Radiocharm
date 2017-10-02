# Radiocharm
Lightweight jQuery plugin that gives charm to radio boxes and allows custom labels, icons, and ability to un-check selection by clicking again on the selected radio box.

Usage
-----------

~~~ html
<input data-radiocharm-label="Label Here" name="option" type="radio" value="Value Here" />
~~~

~~~ js
$(document).ready(function(){
  $('input:radio').radiocharm();
});
~~~

Dependencies
-----------

[Font Awesome]: http://fontawesome.io
