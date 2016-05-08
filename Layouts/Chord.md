### [](https://github.com/mbostock/d3/wiki/Api%E5%8F%82%E8%80%83#%E5%BC%A6%E5%9B%BEchord)[弦图(Chord)](https://github.com/mbostock/d3/wiki/Chord-Layout)

*   [d3.layout.chord](https://github.com/mbostock/d3/wiki/Chord-Layout#wiki-chord)&nbsp;- 初始化一个弦图对象, 返回一个 Chord 实例

*   [chord.matrix](https://github.com/mbostock/d3/wiki/Chord-Layout#wiki-matrix)&nbsp;- 设置或者获取弦图实例对应的矩阵数据

*   [chord.padding](https://github.com/mbostock/d3/wiki/Chord-Layout#wiki-padding)&nbsp;- 设置或获取弦图各段圆弧之间的间隔角度

*   [chord.sortGroups](https://github.com/mbostock/d3/wiki/Chord-Layout#wiki-sortGroups)&nbsp;- 设置或获取矩阵分组的排序函数

*   [chord.sortSubgroups](https://github.com/mbostock/d3/wiki/Chord-Layout#wiki-sortSubgroups)&nbsp;- 设置或获取矩阵二级分组的排序函数

*   [chord.sortChords](https://github.com/mbostock/d3/wiki/Chord-Layout#wiki-sortChords)&nbsp;- 设置或获取弦图在z序上的排序函数(决定哪一组显示在最上层)

*   [chord.chords](https://github.com/mbostock/d3/wiki/Chord-Layout#wiki-chords)&nbsp;- 该函数会将参数处理成对 chord 更友好的格式并返回, 若没有提供参数, 会调用matrix()来获取数据

*   [chord.groups](https://github.com/mbostock/d3/wiki/Chord-Layout#wiki-groups)&nbsp;- 该函数参数处理成更易于理解的分组信息, 若没有提供参数, 会调用matrix()来获取数据