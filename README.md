# 易字云SDK v2.0.1 开发手册

本手册只适用于易字云SDK v2.0 -- 2.0.1版本

易字云SDK主要用于为开发者提供字体资源，通过SDK的形式，实现开发者对字体的下载管理和使用等功能

## 下载SDK

[易字云SDK v2.0.1(Demo+jar)][demojar_download]

[易字云SDK v2.0.1(jar)][jar_download]


## 更新日志
###SDK V2.0.1：
1. 优化统计功能，提供精确数据分析报表
2. 优化下载

###SDK V2.0：
1. 获取字体列表信息接口
`getCateListFromServer(IHttpCallBack callback, String country) ` SDK现在加入对国家的支撑,提供了国家代码来支撑不同国家的字体,用于国际化.
Country：国家代号，比如说中文字体：cn，英文字体cn，日文字体 ja
Callback：获取数据回调接口
2. 新增字体包用于跳转谷歌市场下载字体 `downloadFont(Font font, Context context)`
和跳转方式，如果有需要在海外市场下载字体的话，请联系管理员。
3. 根据字体信息删除字体文件 deleteFont(Font font)



[demojar_download]:http://doc.zitiguanjia.com/public/file/sdkfile/v2.0-1/fontsdk-v2.0.1-1(jar-demo).zip
[jar_download]:http://doc.zitiguanjia.com/public/file/sdkfile/v2.0-1/fontsdk_v2.0.1-1.jar
