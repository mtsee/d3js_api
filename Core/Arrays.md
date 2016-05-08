### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E6%95%B0%E6%8D%AE%E6%93%8D%E4%BD%9Cworking-with-arrays)[数据操作(Working with Arrays)](https://github.com/mbostock/d3/wiki/Arrays)

*   [d3.ascending](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_ascending)&nbsp;- 升序排序函数.

*   [d3.descending](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_descending)&nbsp;- 降序排序函数.

*   [d3.min](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_min)&nbsp;- 获取数组中的最小值.

*   [d3.max](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_max)&nbsp;- 获取数组中的最大值.

*   [d3.extent](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_extent)&nbsp;- 获取数组的范围(最小值和最大值).

*   [d3.sum](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_sum)&nbsp;- 获取数组中数字之和.

*   [d3.mean](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_mean)&nbsp;-获取数组中数字的算术平均值.

*   [d3.median](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_median)&nbsp;- 获取数组中数字的中位数 (相当于 0.5-quantile的值).

*   [d3.quantile](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_quantile)&nbsp;- 获取排好序的数组的一个分位数(quantile).

*   [d3.bisect](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_bisect)&nbsp;- 通过二分法获取某个数在排好序的数组中的插入位置(同d3.bisectRight).

*   [d3.bisectRight](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_bisectRight)&nbsp;- 获取某个数在排好序的数组中的插入位置(相等的值归入右边).

*   [d3.bisectLeft](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_bisectLeft)&nbsp;- 获取某个数在排好序的数组中的插入位置(相等的值归入左边).

*   [d3.bisector](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_bisector)&nbsp;- 自定义一个二分函数.

*   [d3.shuffle](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_shuffle)&nbsp;- 洗牌，随机排列数组中的元素.

*   [d3.permute](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_permute)&nbsp;- 以指定顺序排列数组中的元素.

*   [d3.zip](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_zip)&nbsp;- 将多个数组合并成一个数组的数组，新数组的的第i个元素是原来各个数组中第i个元素组成的数组.

*   [d3.transpose](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_transpose)&nbsp;- 矩阵转置，通过d3.zip实现.

*   [d3.pairs](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_pairs)&nbsp;- 返回临近元素对的数组，d3.pairs([1, 2, 3, 4]); // returns [ [1, 2], [2, 3], [3, 4] ].

*   [d3.keys](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_keys)&nbsp;- 返回关联数组(哈希表、json、object对象)的key组成的数组.

*   [d3.values](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_values)&nbsp;- 返回关联数组的value组成的数组.

*   [d3.entries](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_entries)&nbsp;- 返回关联数组的key-value实体组成的数组, d3.entries({ foo: 42 }); // returns [{key: "foo", value: 42}].

*   [d3.merge](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_merge)&nbsp;- 将多个数组连成一个，类似于原生方法concat. d3.merge([ [1], [2, 3] ]); // returns [1, 2, 3].

*   [d3.range](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_range)&nbsp;- 获得一个数列. d3.range([start, ]stop[, step])

*   [d3.nest](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_nest)&nbsp;- 获得一个nest对象，将数组组织成层级结构. 示例：[http://bl.ocks.org/phoebebright/raw/3176159/](http://bl.ocks.org/phoebebright/raw/3176159/)

*   [nest.key](https://github.com/mbostock/d3/wiki/Arrays#wiki-nest_key)&nbsp;- 为nest层级结构增加一个层级.

*   [nest.sortKeys](https://github.com/mbostock/d3/wiki/Arrays#wiki-nest_sortKeys)&nbsp;- 将当前的nest层级结构按key排序.

*   [nest.sortValues](https://github.com/mbostock/d3/wiki/Arrays#wiki-nest_sortValues)&nbsp;- 将叶nest层级按value排序.

*   [nest.rollup](https://github.com/mbostock/d3/wiki/Arrays#wiki-nest_rollup)&nbsp;- 设置修改叶节点值的函数.

*   [nest.map](https://github.com/mbostock/d3/wiki/Arrays#wiki-nest_map)&nbsp;- 执行nest操作, 返回一个关联数组(json).

*   [nest.entries](https://github.com/mbostock/d3/wiki/Arrays#wiki-nest_entries)&nbsp;- 执行nest操作, 返回一个key-value数组. 如果nest.map返回的结果类似于{ foo: 42 }, 则nest.entries返回的结果类似于[{key: "foo", value: 42}].

*   [d3.map](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_map)&nbsp;- 将javascript的object转化为hash,屏蔽了object的原型链功能导致的与hash不一致的问题。

*   [map.has](https://github.com/mbostock/d3/wiki/Arrays#wiki-map_has)&nbsp;- map有某个key就返回true.

*   [map.get](https://github.com/mbostock/d3/wiki/Arrays#wiki-map_get)&nbsp;- 返回map中某个key对应的value.

*   [map.set](https://github.com/mbostock/d3/wiki/Arrays#wiki-map_set)&nbsp;- 设置map中某个key对应的value.

*   [map.remove](https://github.com/mbostock/d3/wiki/Arrays#wiki-map_remove)&nbsp;- 删除map中的某个key.

*   [map.keys](https://github.com/mbostock/d3/wiki/Arrays#wiki-map_keys)&nbsp;- 返回map中所有key组成的数组.

*   [map.values](https://github.com/mbostock/d3/wiki/Arrays#wiki-map_values)&nbsp;- 返回map中所有value组成的数组.

*   [map.entries](https://github.com/mbostock/d3/wiki/Arrays#wiki-map_entries)&nbsp;- 返回map中所有entry（key-value键值对）组成的数组.类似于{ foo: 42 }转化成[{key: "foo", value: 42}]

*   [map.forEach](https://github.com/mbostock/d3/wiki/Arrays#wiki-map_forEach)&nbsp;- 对map中每一个entry执行某个函数.

*   [d3.set](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_set)&nbsp;- 将javascript的array转化为set,屏蔽了array的object原型链功能导致的与set不一致的问题。set中的value是array中每个值转换成字符串的结果。set中的value是去重过的。

*   [set.has](https://github.com/mbostock/d3/wiki/Arrays#wiki-set_has)&nbsp;- 返回set中是否含有某个value.

*   [set.add](https://github.com/mbostock/d3/wiki/Arrays#wiki-set_add)&nbsp;- 添加某个value.

*   [set.remove](https://github.com/mbostock/d3/wiki/Arrays#wiki-set_remove)&nbsp;- 删除某个value.

*   [set.values](https://github.com/mbostock/d3/wiki/Arrays#wiki-set_values)&nbsp;- 返回set中的值组成的数组.set中的value是去重过的.

*   [set.forEach](https://github.com/mbostock/d3/wiki/Arrays#wiki-set_forEach)&nbsp;- 对set中每一个value执行某个函数.