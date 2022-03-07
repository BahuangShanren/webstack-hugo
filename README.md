![](https://github.com/BahuangShanren/webstack-hugo/blob/master/static/images/Blog-on-Devices.png)

在[webstack-hugo-v2.0rc2](https://github.com/iplaycode/webstack-hugo/releases/tag/2.0rc2)的基础上进行了一些简单的改动，详见[commits](https://github.com/BahuangShanren/webstack-hugo/commits/master)，以下仅列举部分：

- [x] 使用自定义的网站和图标。
- [x] 网站图标使用矢量SVG格式，全部是我自己画的。

    > 仅部分复杂图标未使用矢量，见[not-vector-logo.txt](https://github.com/BahuangShanren/webstack-hugo/blob/master/static/images/not-vector-logo.txt)。

- [x] 替换网站各处的图片。
- [x] 修改404页面。
- [x] 删除`关于本站`页面及相关模板。
- [x] 使用HUGO内置模板[Open Graph](hhttps://gohugo.io/templates/internal#open-graph)和[Twitter Cards](https://gohugo.io/templates/internal#twitter-cards)。
- [x] 右上角GitHub链接可自定义。
- [x] 支持通过`<meta>`方式验证网站所有权。
- [x] 删除对于我来说用不到的搜索引擎。
- [x] 将搜索框移动到顶栏。
- [x] 使用按钮切换暗色模式，而不是在`config.toml`中直接指定是否启用暗色模式。