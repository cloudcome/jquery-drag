# jquery-drag [![spm version](http://spmjs.io/badge/jquery-drag)](http://spmjs.io/package/jquery-drag)
AUTHOR WEBSITE: [http://ydr.me/](http://ydr.me/)

A simple drag for jquery OR yquery

__IT IS [A spm package](http://spmjs.io/package/jquery-drag).__




#usage
```
var $ = require('jquery');
require('jquery-drag')($);

$('#demo').drag();
```



#options
````
defaults = {
    // 鼠标操作区域选择器，默认为this
    // 参数为选择器字符串
    handle: null,

    // 鼠标拖拽时，移动的目标，即从handle开始查找最近匹配的祖先元素
    // 默认为this
    // 参数为选择器字符串
    drag: null,

    // 拖拽轴向，x：水平，y：垂直，xy：所有
    axis: 'xy',

    // 鼠标形状，为空时将不会自动设置
    cursor: 'move',

    // 拖拽对象的最小位置，格式为{left: 10, top: 10}
    min: null,

    // 拖拽对象的最大位置，格式为{left: 1000, top: 1000}
    max: null,

    // 拖拽时的层级值
    zIndex: 9999,

    // 拖拽开始前回调
    // this: drag element
    // arg0: event
    // arg1: instance
    ondragbefore: $.noop,


    // 拖拽开始后回调
    // this: drag element
    // arg0: event
    // arg1: instance
    ondragstart: $.noop,

    // 拖拽中回调
    // this: drag element
    // arg0: event
    // arg1: instance
    ondrag: $.noop,

    // 拖拽结束后回调
    // this: drag element
    // arg0: event
    // arg1: instance
    ondragend: $.noop
};
````

