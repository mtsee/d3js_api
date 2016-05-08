### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E5%AE%9A%E9%87%8F%E5%8F%98%E6%8D%A2quantitative)[定量变换(Quantitative)](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantitative)

*   [d3.scale.linear](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear)&nbsp;- 创建一个线性定量变换。（建议参考源码以深入理解各种变换。）

*   [linear](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-_linear)&nbsp;- 输入一个定义域的值，返回一个值域的值。

*   [linear.invert](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_invert)&nbsp;- 反变换，输入值域值返回定义域值。

*   [linear.domain](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_domain)&nbsp;- get或set定义域。

*   [linear.range](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_range)&nbsp;- get或set值域。

*   [linear.rangeRound](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_rangeRound)&nbsp;- 设置值域，并对结果取整。

*   [linear.interpolate](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_interpolate)&nbsp;- get或set变换的插值函数，如将默认的线性插值函数替换成取整的线性插值函数d3_interpolateRound。

*   [linear.clamp](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_clamp)&nbsp;- 设置值域是否闭合，默认不闭合。当值域闭合时，如果插值结果在值域之外，会取值域的边界值。如值域为[1, 2],插值函数的计算结果为3，如果不闭合，最终结果为3；如果闭合，最终结果为2。

*   [linear.nice](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_nice)&nbsp;- 扩展定义域范围使定义域更规整。如[0.20147987687960267, 0.996679553296417] 变成 [0.2, 1]。

*   [linear.ticks](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_ticks)&nbsp;- 从定义域中取出有代表性的值。通常用于坐标轴刻度的选取。

*   [linear.tickFormat](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_tickFormat)&nbsp;- 获取格式转化函数，通常用于坐标轴刻度的格式转化。如：var x = d3.scale.linear().domain([-1, 1]); console.log(x.ticks(5).map(x.tickFormat(5, "+%"))); // ["-100%", "-50%", "+0%", "+50%", "+100%"]

*   [linear.copy](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-linear_copy)&nbsp;- 从已有的变换中复制出一个变换。

*   [d3.scale.sqrt](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-sqrt)&nbsp;- 创建一个求平方根的定量转换。

*   [d3.scale.pow](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow)&nbsp;- 创建一个指数变换。（可参考linear对应函数的注释）

*   [pow](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-_pow)&nbsp;- 输入一个定义域的值，返回一个值域的值。

*   [pow.invert](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_invert)&nbsp;- 反变换，输入值域值返回定义域值。

*   [pow.domain](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_domain)&nbsp;- get或set定义域。

*   [pow.range](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_range)&nbsp;- get或set值域。

*   [pow.rangeRound](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_rangeRound)&nbsp;- 设置值域，并对结果取整。

*   [pow.interpolate](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_interpolate)&nbsp;- get或set变换的插值函数。

*   [pow.clamp](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_clamp)&nbsp;- 设置值域是否闭合，默认不闭合。

*   [pow.nice](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_nice)&nbsp;- 扩展定义域范围使定义域更规整。

*   [pow.ticks](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_ticks)&nbsp;- 从定义域中取出有代表性的值。通常用于坐标轴刻度的选取。

*   [pow.tickFormat](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_tickFormat)&nbsp;- 获取格式转化函数，通常用于坐标轴刻度的格式转化。

*   [pow.exponent](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_exponent)&nbsp;- get或set指数的幂次。默认为1次幂。

*   [pow.copy](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-pow_copy)&nbsp;- 从已有的变换中复制出一个变换。

*   [d3.scale.log](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log)&nbsp;- 创建一个对数变换。（可参考linear对应函数的注释）

*   [log](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-_log)&nbsp;- 输入一个定义域的值，返回一个值域的值。

*   [log.invert](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_invert)&nbsp;- 反变换，输入值域值返回定义域值。

*   [log.domain](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_domain)&nbsp;- get或set定义域。

*   [log.range](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_range)&nbsp;- get或set值域。

*   [log.rangeRound](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_rangeRound)&nbsp;- 设置值域，并对结果取整。

*   [log.interpolate](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_interpolate)&nbsp;- get或set变换的插值函数。

*   [log.clamp](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_clamp)&nbsp;- 设置值域是否闭合，默认不闭合。

*   [log.nice](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_nice)&nbsp;- 扩展定义域范围使定义域更规整。

*   [log.ticks](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_ticks)&nbsp;- 从定义域中取出有代表性的值。通常用于坐标轴刻度的选取。

*   [log.tickFormat](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_tickFormat)&nbsp;- 获取格式转化函数，通常用于坐标轴刻度的格式转化。

*   [log.copy](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-log_copy)&nbsp;- 从已有的变换中复制出一个变换。

*   [d3.scale.quantize](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantize)&nbsp;- 创建一个quantize线性变换,定义域为一个数值区间，值域为几个离散值。

*   [quantize](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-_quantize)&nbsp;- 输入数值，返回离散值。如： var q = d3.scale.quantize().domain([0, 1]).range(['a', 'b', 'c']); //q(0.3) === 'a', q(0.4) === 'b', q(0.6) === 'b', q(0.7) ==='c;

*   [quantize.invertExtent](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantize_invertExtent)&nbsp;- 返回得到某个离散值的值域范围。 // q.invertExtent('a') 的结果为 [0, 0.3333333333333333]

*   [quantize.domain](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantize_domain)&nbsp;- get或set变换的定义域。

*   [quantize.range](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantize_range)&nbsp;- get或set变换的值域。

*   [quantize.copy](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantize_copy)&nbsp;- 从已有的变换中复制出一个变换。

*   [d3.scale.threshold](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-threshold)&nbsp;- 构建一个threshold(阈值)线性变换。定义域为分隔值数值序列，值域为离散值。它与quantize的区别是quantize指定的值域为一个区间，然后均分这个区间为多个小区间，以对应各离散值。threshold则指定各小区间的边界分隔值。示例: var t = d3.scale.threshold().domain([0, 1]).range(['a', 'b', 'c']); t(-1) === 'a'; t(0) === 'b'; t(0.5) === 'b'; t(1) === 'c'; t(1000) === 'c'; t.invertExtent('a'); //returns [undefined, 0] t.invertExtent('b'); //returns [0, 1] t.invertExtent('c'); //returns [1, undefined]

*   [threshold](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-_threshold)&nbsp;- 输入数值，返回离散值。

*   [threshold.invertExtent](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-threshold_invertExtent)&nbsp;- 输入离散值，返回数值。

*   [threshold.domain](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-threshold_domain)&nbsp;- get或set变换的定义域。

*   [threshold.range](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-threshold_range)&nbsp;- get或set变换的值域。

*   [threshold.copy](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-threshold_copy)&nbsp;- 从已有的变换中复制出一个变换。

*   [d3.scale.quantile](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantile)&nbsp;- 构建一个quantile线性变换。使用方法与quantize完全类似，区别是quantile根据中位数来分隔区间，quantize根据算数平均值来分隔区间。[example](http://stackoverflow.com/questions/19258996/what-is-the-difference-between-d3-scale-quantize-and-d3-scale-quantile)

*   [quantile](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-_quantile)&nbsp;- 输入数值，返回离散值。

*   [quantile.invertExtent](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantile_invertExtent)&nbsp;- 输入离散值，返回数值。

*   [quantile.domain](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantile_domain)&nbsp;- get或set变换的定义域。

*   [quantile.range](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantile_range)&nbsp;- get或set变换的值域。

*   [quantile.quantiles](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantile_quantiles)&nbsp;- 获得quantile变换的分隔值。示例： var q = d3.scale.quantile().domain([0, 1]).range(['a', 'b', 'c']); q.quantiles() returns [0.33333333333333326, 0.6666666666666665]

*   [quantile.copy](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-quantile_copy)&nbsp;- 从已有的变换中复制出一个变换。

*   [d3.scale.identity](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-identity)&nbsp;- 构建一个identity线性变换。特殊的linear线性变换，此变换定义域和值域相同，只在一些d3内部的axis或brush模块中用到。

*   [identity](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-_identity)&nbsp;- identity线性变换函数。返回输入值。

*   [identity.invert](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-_identity)&nbsp;- 和identity函数相同，返回输入值。

*   [identity.domain](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-identity_domain)&nbsp;- get或set变换的定义域。

*   [identity.range](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-identity_domain)&nbsp;- get或set变换的值域。

*   [identity.ticks](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-identity_ticks)&nbsp;- 从定义域中取出有代表性的值。通常用于坐标轴刻度的选取。

*   [identity.tickFormat](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-identity_tickFormat)&nbsp;- 获取格式转化函数，通常用于坐标轴刻度的格式转化。

*   [identity.copy](https://github.com/mbostock/d3/wiki/Quantitative-Scales#wiki-identity_copy)&nbsp;- 从已有的变换中复制出一个变换。