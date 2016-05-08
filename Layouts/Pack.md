### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E5%B1%82%E5%8C%85pack)[层包(Pack)](https://github.com/mbostock/d3/wiki/Pack-Layout)

*   [d3.layout.pack](https://github.com/mbostock/d3/wiki/Pack-Layout#wiki-pack)&nbsp;- 用递归的圆环表现一个多层级布局.

*   [pack.sort](https://github.com/mbostock/d3/wiki/Pack-Layout#wiki-sort)&nbsp;- 获取或设置一个函数, 用来给兄弟节点(同一父结点的子结点)排序.

*   [pack.children](https://github.com/mbostock/d3/wiki/Pack-Layout#wiki-children)&nbsp;- 获取或设置子结点的访问器.

*   [pack.nodes](https://github.com/mbostock/d3/wiki/Pack-Layout#wiki-nodes)&nbsp;- 计算并返回指定结点的子结点信息.

*   [pack.links](https://github.com/mbostock/d3/wiki/Pack-Layout#wiki-links)&nbsp;- 指定一个子结点数组(通常是**nodes**函数返回值), 计算它们与父结点的连接信息.

*   [pack.value](https://github.com/mbostock/d3/wiki/Pack-Layout#wiki-value)&nbsp;- 获取或设置一个函数, 用来计算圆环的大小(近似值).

*   [pack.size](https://github.com/mbostock/d3/wiki/Pack-Layout#wiki-size)&nbsp;- 设置整个布局画布的&nbsp;_宽_&nbsp;and&nbsp;_高_.

*   [pack.radius](https://github.com/mbostock/d3/wiki/Pack-Layout#wiki-radius)&nbsp;- 如果不想结点半径与结点的值相同, 可以传入一个函数用来计算结点半径.

*   [pack.padding](https://github.com/mbostock/d3/wiki/Pack-Layout#wiki-padding)&nbsp;- 指定相邻结点之点的间距(近似值).