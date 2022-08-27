Gephi map background generator plugin<br>
Gephi地图背景插件<br>
使用说明：<br>
2.1版数据<br>

 "地理参考线"<br>
 "世界地图背景"<br>
 "全国省级区划(无标签)"<br>
 "全国主要河流"<br>
 "北京区划(无标签)"<br>
 "北京地铁"<br>
 "北京地铁线路标签"<br>
 "北京环路"<br>
 "上海区划"<br>
 "上海地铁"<br>
 "香港区划"<br>
 "台湾(无标签)"<br>

*'地理定位'功能<br>
在数据表增加两列(Double类型)：<br>
"mapbg_lat"<br>
"mapbg_lng"<br>
并输入经纬度数据，就可以利用该功能经node打印在layout图上<br>

*关于'标签'<br>
数据如果带有标签，会出现在mapbg_note列，这时让标签出现在图上，可以把mapbg_note列的内容拷贝到lable列，或者配置Gephi指定label使用mapbg_node列,注意：在preview模块只能使用lable列<br>

*线条颜色<br>
可以指定线条颜色，有的图线条是带有默认颜色，比如地铁线路。<br>
