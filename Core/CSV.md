### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#csv-%E6%A0%BC%E5%BC%8F%E5%8C%96-d3csv)[CSV 格式化 (d3.csv)](https://github.com/mbostock/d3/wiki/CSV)

*   [d3.csv](https://github.com/mbostock/d3/wiki/CSV#wiki-csv)&nbsp;- 获取一个CSV (comma-separated values, 冒号分隔值)文件。

*   [d3.csv.parse](https://github.com/mbostock/d3/wiki/CSV#wiki-parse)&nbsp;- 将CSV文件字符串转化成object的数组，object的key由第一行决定。如： [{"Year": "1997", "Length": "2.34"}, {"Year": "2000", "Length": "2.38"}]

*   [d3.csv.parseRows](https://github.com/mbostock/d3/wiki/CSV#wiki-parseRows)&nbsp;- 将CSV文件字符串转化成数组的数组。如： [ ["Year", "Length"],["1997", "2.34"],["2000", "2.38"] ]

*   [d3.csv.format](https://github.com/mbostock/d3/wiki/CSV#wiki-format)&nbsp;- 将object的数组转化成CSV文件字符串，是d3.csv.parse的逆操作。

*   [d3.csv.formatRows](https://github.com/mbostock/d3/wiki/CSV#wiki-formatRows)&nbsp;- 将数组的数组转化成CSV文件字符串，是d3.csv.parseRows的逆操作。

*   [d3.tsv](https://github.com/mbostock/d3/wiki/CSV#wiki-tsv)&nbsp;- 获取一个TSV (tab-separated values, tab分隔值)文件。

*   [d3.tsv.parse](https://github.com/mbostock/d3/wiki/CSV#wiki-tsv_parse)&nbsp;- 类似于d3.csv.parse。

*   [d3.tsv.parseRows](https://github.com/mbostock/d3/wiki/CSV#wiki-tsv_parseRows)&nbsp;- 类似于d3.csv.parseRows。

*   [d3.tsv.format](https://github.com/mbostock/d3/wiki/CSV#wiki-tsv_format)&nbsp;- 类似于d3.csv.format。

*   [d3.tsv.formatRows](https://github.com/mbostock/d3/wiki/CSV#wiki-tsv_formatRows)&nbsp;- 类似于d3.csv.formatRows。

*   [d3.dsv](https://github.com/mbostock/d3/wiki/CSV#wiki-dsv)&nbsp;- 创建一个类似于d3.csv的文件处理对象，可以自定义分隔符和mime type。如：var dsv = d3.dsv("|", "text/plain");