## 期末项目
- [代码github链接](https://github.com/Jidemn/python2.0)
- [pythonanywhere链接](http://jidemn.pythonanywhere.com/)

#### 项目简介
通过博物馆相关数据了解各地区文化底蕴，及不同地区文化吸引力。并进行可视化分析，并设置交互控件实现与用户交互效果。

#### 数据传递描述
- **定义函数** 
  - def()
  - 返回值return

- **数据导入**
  - 通过*pandas*导入all.csv文件，在列表的基础上对csv文件的省份进行读取
- **数据筛选**
  - 单条件数据筛选 <u> df[df['指标']== "BaseQuantity" ]</u>
- **HTML档**
  - result2.html为每一个展示页面的样式与布局。其中有两大部分，一个为表头部分，放置交互控件，另一个部分为背景和表格。
  - 其他html文档为对应内容交互图表的源代码。
  - 链接外部样式表 <u><link rel="stylesheet" href="static/hf.css" /></u>
  - flask渲染模版![图片](https://wx1.sinaimg.cn/mw1024/007nTmiKgy1galwa0nttoj30x807y0u9.jpg)
- **python文档描述**
  - visual_test.py将图表图表嵌入网页
  - visual_end.py描述的是根据所展示的图表与地图分析得出来的结论。
  - flask框架的运用
  
