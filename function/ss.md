# 主题包功能

1. 获取分类列表
    ```ruby
    FontCenter.getInstance().getCateListFromServer(IHttpCallBack callback, String country)
    ```
2. 获取单个分类详细数据列表

    ```ruby
    FontCenter.getInstance().getCateFontListFromServer(IHttpCallBack callback,String id)
    ```

3. 根据字体id获取Font对象

    ```php
    //可通过Font.getTypeface()获取Typefaced对象，如果字体没下载，typeface为null
    FontCenter.getInstance().getFontById(String id);
    ```


