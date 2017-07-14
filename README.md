# fsm.js
### A javascript library for creating divs that expand to fill the screen when they are clicked on


## How to use
When I was making this I tried to make it as simple to use as possible. Simply include the js file and in your HTML put the class of fsm on any div that you want to have this functionality. 

```html
<div class="fsm">
  <i class="fa fa-apple"></i>
</div>
```

When the div is growing there is a class of "growing" added to the div. Once the div reaches 100vh and 100vw a class of "full-screen" is added to the div and the class "growing" is removed.

When the div is shrinking the class of "full-screen" is removed and a class of "shrinking" is added. Once the div reaches the original size, it only has the "fsm" class and any other classes you may have added to the div.
