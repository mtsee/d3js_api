### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E5%8A%9B%E5%AD%A6force)[力学(Force)](https://github.com/mbostock/d3/wiki/Force-Layout)

*   [d3.layout.force](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-force)&nbsp;-节点（node）基于物理模拟的位置连接。

*   [force.on](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-on)&nbsp;- 监听布局位置的变化。(仅支持"start","step","end"三种事件)

*   [force.nodes](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-nodes)&nbsp;- 获得或设置布局中的节点（node）阵列组。

*   [force.links](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-links)&nbsp;- 获得或设置布局中节点间的连接（Link）阵列组。.

*   [force.size](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-size)&nbsp;- 获取或设置布局的&nbsp;_宽_&nbsp;和&nbsp;_高_&nbsp;的大小.

*   [force.linkDistance](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-linkDistance)&nbsp;- 获取或设置节点间的连接线距离.

*   [force.linkStrength](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-linkStrength)&nbsp;- 获取或设置节点间的连接强度.

*   [force.friction](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-friction)&nbsp;- 获取或设置摩擦系数.

*   [force.charge](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-charge)&nbsp;- 获取或设置节点的电荷数.(电荷数决定结点是互相排斥还是吸引)

*   [force.gravity](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-gravity)&nbsp;- 获取或设置节点的引力强度.

*   [force.theta](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-theta)&nbsp;- 获取或设置电荷间互相作用的强度.

*   [force.start](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-start)&nbsp;- 开启或恢复结点间的位置影响.

*   [force.resume](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-resume)&nbsp;- 设置冷却系数为0.1,并重新调用start()函数.

*   [force.stop](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-stop)&nbsp;- 立刻终止结点间的位置影响.(等同于将_冷却系数_设置为0)

*   [force.alpha](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-alpha)&nbsp;- 获取或设置布局的冷却系数.(冷却系数为0时,节点间不再互相影响)

*   [force.tick](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-tick)&nbsp;- 让布局运行到下一步.

*   [force.drag](https://github.com/mbostock/d3/wiki/Force-Layout#wiki-drag)&nbsp;- 获取当前布局的拖拽对象实例以便进一步绑定处理函数.