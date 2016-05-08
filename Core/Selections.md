### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E9%80%89%E6%8B%A9%E9%9B%86)[选择集](https://github.com/mbostock/d3/wiki/%E9%80%89%E6%8B%A9%E9%9B%86)

*   [d3.select](https://github.com/mbostock/d3/wiki/Selections#wiki-d3_select)&nbsp;- 从当前文档中选择一系列元素。

*   [d3.selectAll](https://github.com/mbostock/d3/wiki/Selections#wiki-d3_selectAll)&nbsp;- 从当前文档中选择多项元素。

*   [selection.attr](https://github.com/mbostock/d3/wiki/Selections#wiki-attr)&nbsp;- 设置或获取指定属性。

*   [selection.classed](https://github.com/mbostock/d3/wiki/Selections#wiki-classed)&nbsp;- 添加或删除选定元素的 CSS 类（CSS class）。

*   [selection.style](https://github.com/mbostock/d3/wiki/Selections#wiki-style)&nbsp;- 设置或删除 CSS 属性。style优先级高于attr。

*   [selection.property](https://github.com/mbostock/d3/wiki/Selections#wiki-property)&nbsp;- 设置或获原生的属性值（raw property）。

*   [selection.text](https://github.com/mbostock/d3/wiki/Selections#wiki-text)&nbsp;- 设置或获取选定元素的标签体文本内容。

*   [selection.html](https://github.com/mbostock/d3/wiki/Selections#wiki-html)&nbsp;- 设置或获取选定元素的 HTML 内容（类似 innerHTML ）

*   [selection.append](https://github.com/mbostock/d3/wiki/Selections#wiki-append)&nbsp;- 创建并添加新元素到选定元素后。

*   [selection.insert](https://github.com/mbostock/d3/wiki/Selections#wiki-insert)&nbsp;- 创建并添加新元素到选定元素前。

*   [selection.remove](https://github.com/mbostock/d3/wiki/Selections#wiki-remove)&nbsp;- 从当前文档对象中删除选定的元素。

*   [selection.data](https://github.com/mbostock/d3/wiki/Selections#wiki-data)&nbsp;- 设置或获取一组元素的绑定数据（get or set data for a group of elements, while computing a relational join.）

*   [selection.enter](https://github.com/mbostock/d3/wiki/Selections#wiki-enter)&nbsp;- 返回缺失元素的占位对象（placeholder），指向绑定的数据中比选定元素集多出的一部分元素。

*   [selection.exit](https://github.com/mbostock/d3/wiki/Selections#wiki-exit)&nbsp;- 返回多余元素的元素集，即选择元素中比绑定数据多出的一部分。(关于data, enter, exit原理的[示例1](http://bost.ocks.org/mike/join/),&nbsp;[示例2](http://bl.ocks.org/mbostock/3808218),&nbsp;[示例3](http://bl.ocks.org/mbostock/5779690))

*   [selection.datum](https://github.com/mbostock/d3/wiki/Selections#wiki-datum)&nbsp;- 设置或获取单独元素的数据，不进行关联。（get or set data for individual elements, without computing a join.）

*   [selection.filter](https://github.com/mbostock/d3/wiki/Selections#wiki-filter)&nbsp;- 根据绑定的数据过滤选择集。

*   [selection.sort](https://github.com/mbostock/d3/wiki/Selections#wiki-sort)&nbsp;- 根据绑定的数据对选择的元素进行排序。

*   [selection.order](https://github.com/mbostock/d3/wiki/Selections#wiki-order)&nbsp;- 对文档中的元素重排序以匹配选择集。

*   [selection.on](https://github.com/mbostock/d3/wiki/Selections#wiki-on)&nbsp;- 添加或删除事件监听器。

*   [selection.transition](https://github.com/mbostock/d3/wiki/Selections#wiki-transition)&nbsp;- 启动一个过渡效果（返回 Transition 对象），可以理解为动画。

*   [selection.interrupt](https://github.com/mbostock/d3/wiki/Selections#wiki-interrupt)&nbsp;- 立即停止所有正在进行的动画动作。

*   [selection.each](https://github.com/mbostock/d3/wiki/Selections#wiki-each)&nbsp;- 为每个选择的元素集调用指定的函数。

*   [selection.call](https://github.com/mbostock/d3/wiki/Selections#wiki-call)&nbsp;- 为当前选择的元素集调用指定的函数。

*   [selection.empty](https://github.com/mbostock/d3/wiki/Selections#wiki-empty)&nbsp;- 测试选择集是否为空。

*   [selection.node](https://github.com/mbostock/d3/wiki/Selections#wiki-node)&nbsp;- 返回选择集中的第一个元素。

*   [selection.size](https://github.com/mbostock/d3/wiki/Selections#wiki-size)&nbsp;- 返回选择集中的元素个数。

*   [selection.select](https://github.com/mbostock/d3/wiki/Selections#wiki-select)&nbsp;- 选择所选的元素中的第一个子元素组成新的选择集。

*   [selection.selectAll](https://github.com/mbostock/d3/wiki/Selections#wiki-selectAll)&nbsp;- 选择所选的元素中的多个子元素组成新的选择集。

*   [d3.selection](https://github.com/mbostock/d3/wiki/Selections#wiki-d3_selection)&nbsp;- 选择集对象原型（可通过&nbsp;`d3.selection.prototype`&nbsp;为选择集增强功能）。

*   [d3.event](https://github.com/mbostock/d3/wiki/Selections#wiki-d3_event)&nbsp;- 获取当前交互的用户事件。

*   [d3.mouse](https://github.com/mbostock/d3/wiki/Selections#wiki-d3_mouse)&nbsp;- 获取鼠标的相对某元素的坐标。

*   [d3.touches](https://github.com/mbostock/d3/wiki/Selections#wiki-d3_touches)&nbsp;- 获取相对某元素的触控点坐标。