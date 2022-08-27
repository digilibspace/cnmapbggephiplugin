Gephi map background generator plugin
Gephi地图背景插件
使用说明：
2.1版数据

 "地理参考线"
 "世界地图背景"
 "全国省级区划(无标签)"
 "全国主要河流"
 "北京区划(无标签)"
 "北京地铁"
 "北京地铁线路标签"
 "北京环路"
 "上海区划"
 "上海地铁"
 "香港区划"
 "台湾(无标签)"

*'地理定位'功能
在数据表增加两列(Double类型)：
"mapbg_lat"
"mapbg_lng"
并输入经纬度数据，就可以利用该功能经node打印在layout图上

*关于'标签'
数据如果带有标签，会出现在mapbg_note列，这时让标签出现在图上，可以把mapbg_note列的内容拷贝到lable列，或者配置Gephi指定label使用mapbg_node列,注意：在preview模块只能使用lable列

*线条颜色
可以指定线条颜色，有的图线条是带有默认颜色，比如地铁线路。
