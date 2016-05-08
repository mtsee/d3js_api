### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E7%9F%A9%E9%98%B5%E6%A0%91treemap)[矩阵树(Treemap)](https://github.com/mbostock/d3/wiki/Treemap-Layout)

*   [d3.layout.treemap](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-treemap)&nbsp;- 返回一个矩阵树对象(用矩阵来展示一颗树).

*   [treemap.sort](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-sort)&nbsp;- 设置或获取一个函数, 用来给兄弟节点(同一父结点的子结点)排序.

*   [treemap.children](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-children)&nbsp;- 设置或获取子结点的访问器.

*   [treemap.nodes](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-nodes)&nbsp;- 计算并返回指定结点的子结点信息.

*   [treemap.links](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-links)&nbsp;- 指定一个子结点数组(通常是**nodes**函数返回值), 计算它们与父结点的连接信息.

*   [treemap.value](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-value)&nbsp;- 设置或获取一个用来计算单元格大小的值访问器.

*   [treemap.size](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-size)&nbsp;- 指定整个布局的宽和高.

*   [treemap.padding](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-padding)&nbsp;- 指定父结点和子结点的间距.

*   [treemap.round](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-round)&nbsp;- 禁用或启用边界补偿.

*   [treemap.sticky](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-sticky)&nbsp;- 让布局更"粘"以保证在更新数据时有平滑的动画效果.

*   [treemap.mode](https://github.com/mbostock/d3/wiki/Treemap-Layout#wiki-mode)&nbsp;- 更改矩阵树的布局算法.