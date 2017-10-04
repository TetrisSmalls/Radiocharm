# Radiocharm
Lightweight jQuery plugin that gives charm to radio boxes and allows custom labels, icons, and ability to un-check selection by clicking again on the selected radio box.

## Usage

### Default Implementation
Default implementation using data-radiocharm-label as the label for each option.

~~~ html
<input data-radiocharm-label="Label Here" type="radio" />
~~~

~~~ js
$(document).ready(function(){
  $('input:radio').radiocharm();
});
~~~

### Background Color Implementation
Background color implementation using **data-radiocharm-background-color** to change the background colors for each option. Additionally, you can use **data-radiocharm-text-color** if you need to change the color of the text.

~~~ html
<input data-radiocharm-label="Label Here" data-radiocharm-background-color="c9302c" type="radio" />
~~~

~~~ js
$(document).ready(function(){
  $('input:radio').radiocharm();
});
~~~

### Icon Implementation
Icon implementation using **data-radiocharm-icon** to change the icon for each option.

~~~ html
<input data-radiocharm-label="Label Here" data-radiocharm-icon="thumbs-up" type="radio" />
~~~

~~~ js
$(document).ready(function(){
  $('input:radio').radiocharm();
});
~~~

### Uncheckable Implementation
Uncheckable implementation using **uncheckable** setting to be passed over on initialization. **Default** is false.

~~~ html
<input data-radiocharm-label="Label Here" type="radio" />
~~~

~~~ js
$(document).ready(function(){
  $('input:radio').radiocharm({
    uncheckable: true
  });
});
~~~











## Dependencies

[Font Awesome](http://fontawesome.io)
~~~ html
<link href=https://opensource.keycdn.com/fontawesome/4.7.0/font-awesome.min.css" rel="stylesheet" />
~~~
