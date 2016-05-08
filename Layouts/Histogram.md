### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E7%9B%B4%E6%96%B9%E5%9B%BEhistogram)[直方图(Histogram)](https://github.com/mbostock/d3/wiki/Histogram-Layout)

*   [d3.layout.histogram](https://github.com/mbostock/d3/wiki/Histogram-Layout#wiki-histogram)&nbsp;- 构建一个默认直方图(用来表示一组离散数字的分布,横轴表示区间,纵轴表示区间内样本数量或样本百分比).

*   [histogram.value](https://github.com/mbostock/d3/wiki/Histogram-Layout#wiki-value)&nbsp;- 获取或设置值访问器.

*   [histogram.range](https://github.com/mbostock/d3/wiki/Histogram-Layout#wiki-range)&nbsp;- 获取或设置合法值范围.

*   [histogram.bins](https://github.com/mbostock/d3/wiki/Histogram-Layout#wiki-bins)&nbsp;- 指定如何将数据分组到不同的区间(bin)里, 返回一个[构造函数](https://github.com/mbostock/d3/wiki/Histogram-Layout#wiki-_histogram).

*   [histogram](https://github.com/mbostock/d3/wiki/Histogram-Layout#wiki-_histogram)&nbsp;- 根据已设置的区间将数据分组,返回已分组的二维数组(compute the distribution of data using quantized bins).

*   [histogram.frequency](https://github.com/mbostock/d3/wiki/Histogram-Layout#wiki-frequency)&nbsp;- 设置直方图Y轴值是区间内数据的总量还是百分比(compute the distribution as counts or probabilities).