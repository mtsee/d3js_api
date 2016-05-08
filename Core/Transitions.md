### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E8%BF%87%E6%B8%A1%E6%95%88%E6%9E%9C)[过渡效果](https://github.com/mbostock/d3/wiki/Transitions)

*   [d3.transition](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_transition)&nbsp;- 开始一个动画过渡。[简单教程](http://bost.ocks.org/mike/transition/)

*   [transition.delay](https://github.com/mbostock/d3/wiki/Transitions#wiki-delay)&nbsp;- 指定每个元素过渡的延迟时间（单位：毫秒ms）。

*   [transition.duration](https://github.com/mbostock/d3/wiki/Transitions#wiki-duration)&nbsp;- 指定每个元素过渡的持续时间（单位：毫秒ms）。

*   [transition.ease](https://github.com/mbostock/d3/wiki/Transitions#wiki-ease)&nbsp;- 指定过渡的缓冲函数。

*   [transition.attr](https://github.com/mbostock/d3/wiki/Transitions#wiki-attr)&nbsp;- 平滑过渡到新的attr属性值（起始属性值为当前属性）。

*   [transition.attrTween](https://github.com/mbostock/d3/wiki/Transitions#wiki-attrTween)&nbsp;- 在不同attr属性值之间平滑过渡（起始属性值可在过渡函数中设置,甚至整个过渡函数都可以自定义）。

*   [transition.style](https://github.com/mbostock/d3/wiki/Transitions#wiki-style)&nbsp;- 平滑过渡到新的style属性值。

*   [transition.styleTween](https://github.com/mbostock/d3/wiki/Transitions#wiki-styleTween)&nbsp;- 在不同style属性值之间平滑过渡。

*   [transition.text](https://github.com/mbostock/d3/wiki/Transitions#wiki-text)&nbsp;- 在过渡开始时设置文本内容。

*   [transition.tween](https://github.com/mbostock/d3/wiki/Transitions#wiki-tween)&nbsp;- 使某个属性过渡到一个新的属性值，该属性可以是非attr或非style属性，比如text。

*   [transition.select](https://github.com/mbostock/d3/wiki/Transitions#wiki-select)&nbsp;- 选择每个当前元素的某个子元素进行过渡。

*   [transition.selectAll](https://github.com/mbostock/d3/wiki/Transitions#wiki-selectAll)&nbsp;- 选择每个当前元素的多个子元素进行过渡。

*   [transition.filter](https://github.com/mbostock/d3/wiki/Transitions#wiki-filter)&nbsp;- 通过数据筛选出当前元素中的部分元素进行过渡。

*   [transition.transition](https://github.com/mbostock/d3/wiki/Transitions#wiki-transition)&nbsp;- 当前过渡结束后开始新的过渡。

*   [transition.remove](https://github.com/mbostock/d3/wiki/Transitions#wiki-remove)&nbsp;- 过渡结束后移除当前元素。

*   [transition.empty](https://github.com/mbostock/d3/wiki/Transitions#wiki-empty)&nbsp;- 如果过渡为空就返回true。如果当前元素中没有非null元素，则此过渡为空。

*   [transition.node](https://github.com/mbostock/d3/wiki/Transitions#wiki-node)&nbsp;- 返回过渡中的第一个元素。

*   [transition.size](https://github.com/mbostock/d3/wiki/Transitions#wiki-size)&nbsp;- 返回过渡中当前元素的数量。

*   [transition.each](https://github.com/mbostock/d3/wiki/Transitions#wiki-each)&nbsp;- 遍历每个元素执行操作。不指定触发类型时，立即执行操作。当指定触发类型为'start'或'end'时,会在过渡开始或结束时执行操作。

*   [transition.call](https://github.com/mbostock/d3/wiki/Transitions#wiki-call)&nbsp;- 以当前过渡为this执行某个函数。

*   [d3.ease](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_ease)&nbsp;- 定制过渡的缓冲函数。

*   [ease](https://github.com/mbostock/d3/wiki/Transitions#wiki-_ease)&nbsp;- 缓冲函数。缓冲函数可让动画效果更自然，比如elastic缓冲函数可用以模拟弹性物体的运动。是一种插值函数的特例。

*   [d3.timer](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_timer)&nbsp;- 开始一个定制的动画计时。功能类似于setTimeout，但内部用requestAnimationFrame实现，更高效。

*   [d3.timer.flush](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_timer_flush)&nbsp;- 立刻执行当前没有延迟的计时。可用于处理闪屏问题。

*   [d3.interpolate](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolate)&nbsp;- 生成一个插值函数，在两个参数间插值。差值函数的类型会根据输入参数的类型（数字、字符串、颜色等）而自动选择。

*   [interpolate](https://github.com/mbostock/d3/wiki/Transitions#wiki-_interpolate)&nbsp;- 插值函数。输入参数在[0, 1]之间。

*   [d3.interpolateNumber](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateNumber)&nbsp;- 在两个数字间插值。

*   [d3.interpolateRound](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateRound)&nbsp;- 在两个数字间插值，返回值会四舍五入取整。

*   [d3.interpolateString](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateString)&nbsp;- 在两个字符串间插值。解析字符串中的数字，对应的数字会插值。

*   [d3.interpolateRgb](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateRgb)&nbsp;- 在两个RGB颜色间插值。

*   [d3.interpolateHsl](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateHsl)&nbsp;- 在两个HSL颜色间插值。

*   [d3.interpolateLab](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateLab)&nbsp;- 在两个L*a*b*颜色间插值。

*   [d3.interpolateHcl](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateHcl)&nbsp;- 在两个HCL颜色间插值。

*   [d3.interpolateArray](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateArray)&nbsp;- 在两个数列间插值。d3.interpolateArray( [0, 1], [1, 10, 100] )(0.5); // returns [0.5, 5.5, 100]

*   [d3.interpolateObject](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateObject)&nbsp;- 在两个object间插值。d3.interpolateArray( {x: 0, y: 1}, {x: 1, y: 10, z: 100} )(0.5); // returns {x: 0.5, y: 5.5, z: 100}

*   [d3.interpolateTransform](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateTransform)&nbsp;- 在两个2D仿射变换间插值。

*   [d3.interpolateZoom](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolateZoom)&nbsp;- 在两个点之间平滑地缩放平移。[示例](http://bl.ocks.org/mbostock/3828981)

*   [d3.interpolators](https://github.com/mbostock/d3/wiki/Transitions#wiki-d3_interpolators)&nbsp;- 添加一个自定义的插值函数.