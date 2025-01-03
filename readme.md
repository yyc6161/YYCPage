# 魔改版Unity文档网站地图

用于自用检索

把XR、AR等等不太关心的部分剔除掉了

把子级的页面都剔除掉了，正则如下，数字表示剔除的子级数：
<url><loc>https://docs\.unity3d\.com/ScriptReference/[^./]+(?:[.-][^./]+){1}\.html</loc></url>\n?