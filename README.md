# tabs_module
Tabs module for website

This module is intended to implement a tabs on a website page. The module is implemented in a native JavaScript, using the ES6 standard.

Usage:

1.  Set up your HTML markup:
```
<div class="your class container">
    <div class="your class content">your content</div>
    <div class="your class content">your content</div>
    <div class="your class content">your content</div>
    <div class="your class content">your content</div>
    <div class="your wrapper">
        <div class="your perent class tabs">
            <div class="your class tab and your class active">your tab</div>
            <div class="your class tab">your tab</div>
            <div class="your class tab">your tab</div>
            <div class="your class tab">your tab</div>
        </div>
    </div>
</div>
```

2.  Set up your CSS style:
   -  create "active class" and add style for active class;
   -  create "show class" in which you specify:
```
.show {
  display: block;
}
```
   -  create "hide class" in which you specify:
```
.hide {
  display: none;
}
```
   -  create animation css

3.  Сopy the code from the tabs.js file to your separate tabs file
   
4.  Import using command 'import tabs from ...' in your main file 'main.js'

5.  In the main file call the function tabs({}) inside which, as a parameter, pass an object with the following properties:
```
tabs({
  perentSelectorTabs: 'your perent selector tabs',
  tabsSelector: 'your selector tab',
  contentSelector: 'your selector content',
  classActive: 'your selector active',
  classShow: 'your class show',
  classHide: 'your class hide',
  classAnimation: 'your class animation'
});
```
