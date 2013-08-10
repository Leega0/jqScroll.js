jqScroll.js
===========

平滑滚动插件

使用方法和jQuery本身函数一样简单：

$.scrollTo ( selector, speed, callbackfunction );

其中，要实现平滑滚动的话selector和speed是不可少的，selector是jQuery标准的元素选择器，speed是毫秒，即滑动时间。最后是回调函数。比如：

$.scrollTo ( '#header' , 1000, function(){ window.alert('OK'); } );
