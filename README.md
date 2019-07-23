# Data-analysis-platform
A simple data analysis platform with visual and machine learning features

目录  
第一部分：构建背景  
第二部分：架构图  
第三部分：使用工具  
第四部分：实现功能  
1.可视化  
2.机器学习  
  
  
第一部分：构建背景 
发展趋势：大数据已经为目前发展的趋势，各行各业都会涌现大量的数据，如何利用和发掘这些数据的价值成为关键。  
国内发展情况：目前国内涌现出了不少数据分析平台产品，产品的目标是BI，利用可视化提供数据探索的功能，并且加入机器学习和预测的功能。  
  
  
第二部分：架构图  


第三部分：使用工具  
1.客户端  
bootstrap   前端框架，基于 HTML、CSS、JAVASCRIPT 
requirejs     JS 依赖管理
jquery         JavaScript 库
reactjs         UI框架，基于组件（component）
d3js              JavaScript的函数库，用来做数据可视化
echarts        JavaScript的函数库，用来做数据可视化

2.服务器  
flask        Python Web框架
pandas   Python数据结构和数据分析工具包，提供数据处理的功能
sklearn   Python机器学习包，依赖于numpy，scipy和matplotlib

3.开发工具
nodejs     服务端JavaScript环境
babel       javascript的编译器，支持代码转换成浏览器可执行的代码


第四部分：实现功能  

1.数据源展示
可添加简单的数据文件
可自定义每页显示数据记录行数
可搜索数据

2.可视化  
可以选择的可视化图形类型有6种：折线图、柱状图、饼状图、树状图、散点图、区域图
可快捷切换到数据视图、折线图切换、柱状图切换、堆积图、平铺图
可以动态获取数据点
可还原、储存可视化后的结果图

2.机器学习  




