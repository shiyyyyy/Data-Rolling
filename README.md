<h1 align="center">
动态排名数据可视化
</h1>
<h3>非本人所写,因项目用到,直接拿来用</h3> 
<p align="center">
  <center>

  [![原地址](https://github.com/Jannchie/Historical-ranking-data-visualization-based-on-d3.js/issues)


  </center>
</p>
<h3 align="center">将历史数据排名转化为动态柱状图图表</h3>


  

<p align="center">
  <a href="readme-en.md">English</a>
  
  <center>

  [![GitHub issues](https://img.shields.io/github/issues/Jannchie/Historical-ranking-data-visualization-based-on-d3.js.svg?style=flat-square)](https://github.com/Jannchie/Historical-ranking-data-visualization-based-on-d3.js/issues)
  [![GitHub stars](https://img.shields.io/github/stars/Jannchie/Historical-ranking-data-visualization-based-on-d3.js.svg?style=flat-square)](https://github.com/Jannchie/Historical-ranking-data-visualization-based-on-d3.js/stargazers)
  [![GitHub forks](https://img.shields.io/github/forks/Jannchie/Historical-ranking-data-visualization-based-on-d3.js.svg?style=flat-square)](https://github.com/Jannchie/Historical-ranking-data-visualization-based-on-d3.js/network)
  [![GitHub license](https://img.shields.io/github/license/Jannchie/Historical-ranking-data-visualization-based-on-d3.js.svg?style=flat-square)](https://github.com/Jannchie/Historical-ranking-data-visualization-based-on-d3.js/blob/master/LICENSE)

  </center>

</p>

这是一个数据可视化项目，基于D3.js。能够将历史数据排名转化为动态柱状图图表。

这个项目旨在降低此类视频的使用门槛与提高生产效率，使得没有编程经验的用户也能无痛制作排名可视化动画。



----

# 一句话用法

只需打开src目录下的bargraph.html。然后点击页面中间的选择文件按钮，接着选择csv格式的数据文件，便可以看到可视化的结果。

# 数据格式

本项目能够读取csv格式的数据。

具体的格式如下：

name|type|value|date
--|--|--|--
名称1|类型1|值1|日期1
名称2|类型2|值2|日期2

其中“名称”会出现在柱状图的左侧作为Y轴，而“类型-名称”会作为附加信息出现在柱状图上。

类型与柱状图的颜色相关，建议命名为不包含空格或者特殊符号的中英文字符。

值与柱状图的长度绑定，必须是整数或浮点数。

日期建议使用的格式为"YYYY-MM-DD"。

# 配置

本项目能够进行一些简单的定制。

使用记事本或者其他文本编辑器，打开config.js的文件即可进行一些参数的修改。
