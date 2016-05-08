### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E6%97%B6%E9%97%B4%E5%8F%98%E6%8D%A2time-scales)[时间变换(Time Scales)](https://github.com/mbostock/d3/wiki/Time%20Scales)

*   [d3.time.scale](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-scale)&nbsp;- 创建一个线性时间变换，定义域为数值区间，值域为时间区间。常用于时间坐标轴的创建。详情可参考d3.scale.linear。

*   [scale](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-_scale)&nbsp;- 输入为一个数值，返回为一个时间。

*   [scale.invert](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-invert)&nbsp;- 反变换，输入时间返回数值。

*   [scale.domain](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-domain)&nbsp;- get或set变换的定义域。

*   [scale.nice](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-nice)&nbsp;- 扩展定义域范围使定义域更规整。

*   [scale.range](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-range)&nbsp;- get或set变换的值域。

*   [scale.rangeRound](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-rangeRound)&nbsp;- 设置值域，并对结果取整。

*   [scale.interpolate](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-interpolate)&nbsp;- get或set变换的插值函数，如将默认的线性插值函数替换成指数插值函数。

*   [scale.clamp](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-clamp)&nbsp;- 设置值域是否闭合，默认不闭合。当值域闭合时，如果插值结果在值域之外，会取值域的边界值。详情参考linear.clamp。

*   [scale.ticks](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-ticks)&nbsp;- 从定义域中取出有代表性的值。通常用于坐标轴刻度的选取。

*   [scale.tickFormat](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-tickFormat)&nbsp;- 获取格式转化函数，通常用于坐标轴刻度的格式转化。

*   [scale.copy](https://github.com/mbostock/d3/wiki/Time-Scales#wiki-copy)&nbsp;- 从已有的时间变换中复制出一个变换。