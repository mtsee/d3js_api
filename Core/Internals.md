### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E5%86%85%E9%83%A8%E6%96%B9%E6%B3%95internals)[内部方法（Internals）](https://github.com/mbostock/d3/wiki/Internals)

*   [d3.functor](https://github.com/mbostock/d3/wiki/Internals#wiki-functor)&nbsp;- 函数化。将非函数变量转化为只返回该变量值的函数。输入函数，则返回原函数；输入值，则返回一个函数，该函数只返回原值。

*   [d3.rebind](https://github.com/mbostock/d3/wiki/Internals#wiki-rebind)&nbsp;- 将一个对象的方法绑定到另一个对象上。

*   [d3.dispatch](https://github.com/mbostock/d3/wiki/Internals#wiki-d3_dispatch)&nbsp;- 创建一个定制的事件。

*   [dispatch.on](https://github.com/mbostock/d3/wiki/Internals#wiki-dispatch_on)&nbsp;- 添加或移除一个事件监听器。对一个事件可添加多个监听器。

*   [dispatch.type](https://github.com/mbostock/d3/wiki/Internals#wiki-_dispatch)&nbsp;- 触发事件。其中‘type’为要触发的事件的名称。