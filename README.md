# Bootstrap.GravityForms
This is a Bootstrap3 SASS for Gravity Forms that goes in place of the default Gravity 
Forms CSS to make it look more like Bootstrap.

## How to use
Add the `gravity-forms.scss` to you project after all the Bootstrap includes. You 
must compile it at the same time as bootstrap.

```css
@import "bootstrap-theme/variables";
@import "bootstrap-theme/bootstrap";
@import "bootstrap-theme/gravity-forms";
```

## jQuery UI
Because Gravity Forms requires jQuery UI, you must also include the CSS for it as 
things like date pickers will not render properly.

You can either use the standard CSS from the jQuery site, or if you prefer a SASS 
option I have written a theme file (`_jqueryui-variables.scss`) for 
[Jakob Hilden](https://github.com/jhilden)'s port of 
[jQUI to SASS](https://github.com/jhilden/jquery-ui-sass-rails). 

## Issues
It is very possible that not every feature of Gravity Forms is supported. Please file 
[issues](https://github.com/michaelcoxon/Bootstrap.GravityForms/issues) or branch off
and collaborate with me on this. It was initially created to fix one small issue 
I was having.