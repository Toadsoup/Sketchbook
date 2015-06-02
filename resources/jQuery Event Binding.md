**[Effective Event Binding with jQuery](http://www.sitepoint.com/effective-event-binding-jquery/)**

From Will Boyd [@lonekorean](https://github.com/lonekorean)


Thanks Will

The article is basically about being smarter with jQuery binds so they don't have to rely on the same class/id selectors as your css.


The meat of the article is within this extend to create hooks from the data attribute.
```
$.extend({
    hook: function(hookName) {
        var selector;
        if(!hookName || hookName === '*') {
            // select all data-hooks
            selector = '[data-hook]';
        } else {
            // select specific data-hook
            selector = '[data-hook~="' + hookName + '"]';
        }
        return $(selector);
    }
});
```



Then you can snag it much like any other jQuery thing...
```
$.hook('nav-menu-toggle').on('click', function() {
    $.hook('nav-menu').toggle();
});
```

Works on
```
<button data-hook="nav-menu-toggle">Toggle Nav Menu</button>
```



Which used to be driven off of class="nav-menu-toggle" ...

```
$('.nav-menu-toggle').on('click', function() {
    $('nav').toggle();
});

```
Which required the element to contain said class
```
<button class="nav-menu-toggle">Toggle Nav Menu</button>
```


Now you can change things up (css) without ruining your life (and javascript) in the process.


