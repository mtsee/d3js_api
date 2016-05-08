### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E5%AD%97%E7%AC%A6%E4%B8%B2%E6%A0%BC%E5%BC%8F%E5%8C%96string-formatting)[字符串格式化(String Formatting)](https://github.com/mbostock/d3/wiki/Formatting)

*   [d3.format](https://github.com/mbostock/d3/wiki/Formatting#wiki-d3_format)&nbsp;- 将数字转化成指定格式的字符串。转化的格式非常丰富，且非常智能。

*   [d3.formatPrefix](https://github.com/mbostock/d3/wiki/Formatting#wiki-d3_formatPrefix)&nbsp;- 以指定的值和精度获得一个[SI prefix]对象。这个函数可用来自动判断数据的量级， 如K(千)，M(百万)等等。示例: var prefix = d3.formatPrefix(1.21e9); console.log(prefix.symbol); // "G"; console.log(prefix.scale(1.21e9)); // 1.21

*   [d3.requote](https://github.com/mbostock/d3/wiki/Formatting#wiki-d3_requote)&nbsp;- 将字符串转义成可在正则表达式中使用的格式。如 d3.requote('$'); // return "\$"

*   [d3.round](https://github.com/mbostock/d3/wiki/Formatting#wiki-d3_round)&nbsp;- 设置某个数按小数点后多少位取整。与toFixed()类似，但返回格式为number。 如 d3.round(1.23); // return 1; d3.round(1.23, 1); // return 1.2; d3.round(1.25, 1); // return 1.3