### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E8%BD%BD%E5%85%A5%E5%A4%96%E9%83%A8%E8%B5%84%E6%BA%90loading-external-resources)[载入外部资源(Loading External Resources)](https://github.com/mbostock/d3/wiki/Requests)

*   [d3.xhr](https://github.com/mbostock/d3/wiki/Requests#wiki-d3_xhr)&nbsp;- 发起XMLHttpRequest请求获取资源。

*   [xhr.header](https://github.com/mbostock/d3/wiki/Requests#wiki-header)&nbsp;- 设置 request header。

*   [xhr.mimeType](https://github.com/mbostock/d3/wiki/Requests#wiki-mimeType)&nbsp;- 设置 Accept request header，并重写 response MIME type。

*   [xhr.response](https://github.com/mbostock/d3/wiki/Requests#wiki-response)&nbsp;- 设置response返回值转化函数。如 function(request) { return JSON.parse(request.responseText); }

*   [xhr.get](https://github.com/mbostock/d3/wiki/Requests#wiki-get)&nbsp;- 发起GET请求。

*   [xhr.post](https://github.com/mbostock/d3/wiki/Requests#wiki-post)&nbsp;- 发起POST请求。

*   [xhr.send](https://github.com/mbostock/d3/wiki/Requests#wiki-send)&nbsp;- 以指定的方法和数据发起请求。

*   [xhr.abort](https://github.com/mbostock/d3/wiki/Requests#wiki-abort)&nbsp;- 终止当前请求。

*   [xhr.on](https://github.com/mbostock/d3/wiki/Requests#wiki-on)&nbsp;- 为请求添加"beforesend", "progress", "load" 或 "error" 等事件监听器。

*   [d3.text](https://github.com/mbostock/d3/wiki/Requests#wiki-d3_text)&nbsp;- 请求一个text文件。

*   [d3.json](https://github.com/mbostock/d3/wiki/Requests#wiki-d3_json)&nbsp;- 请求一个JSON。

*   [d3.html](https://github.com/mbostock/d3/wiki/Requests#wiki-d3_html)&nbsp;- 请求一个html文本片段。

*   [d3.xml](https://github.com/mbostock/d3/wiki/Requests#wiki-d3_xml)&nbsp;- 请求一个XML文本片段。

*   [d3.csv](https://github.com/mbostock/d3/wiki/CSV)&nbsp;- 请求一个CSV(comma-separated values, 逗号分隔值)文件。

*   [d3.tsv](https://github.com/mbostock/d3/wiki/CSV#wiki-tsv)&nbsp;- 请求一个TSV(tab-separated values, tab分隔值)文件。