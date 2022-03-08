![](/static/images/Blog-on-Devices.png)

<a href="https://gohugo.io" target="_blank" rel="noopener noreffer"><img src="https://img.shields.io/badge/Frame-Hugo-blue?style=flat&logo=Hugo&color=FF4088"></a> <a href="https://github.com/iplaycode/webstack-hugo" target="_blank" rel="noopener noreffer"><img src="https://img.shields.io/badge/Theme-webstack--hugo-blue?style=flat&logo=CSS3&logoColor=0594CB&color=0594CB"></a> <a href="https://github.com/BahuangShanren/webstack-hugo/blob/master/.github/workflows/GitHubPages.yml" target="_blank" rel="noopener noreffer"><img src="https://img.shields.io/github/workflow/status/BahuangShanren/webstack-hugo/GitHub%20Pages?color=33BA91&label=Deploy&logo=GitHub%20Actions&logoColor=FFFFFF"></a> <a href="https://www.cloudflare.com/" target="_blank" rel="noopener noreffer"><img src="https://img.shields.io/badge/CDN-Cloudflare-blue?style=flat&logo=Cloudflare&color=F38020"></a> <a href="https://gitee.com/BahuangShanren/webstack-hugo" target="_blank" rel="noopener noreffer"><img src="https://img.shields.io/badge/Mirror-Gitee-blue?style=flat&logo=Gitee&logoColor=C71D23&color=C71D23"></a>

## 介绍

在[webstack-hugo-v2.0rc2](https://github.com/iplaycode/webstack-hugo/releases/tag/2.0rc2)的基础上进行了一些简单的改动，详见[commits](https://github.com/BahuangShanren/webstack-hugo/commits/master)，以下仅列举部分：

- [x] 使用自定义的网站和图标。
- [x] 网站图标使用矢量SVG格式，全部是我自己画的。

    > 仅部分复杂图标未使用矢量，见[not-vector-logo.txt](/static/images/not-vector-logo.txt)。

- [x] 修改404页面。
- [x] 删除`关于本站`页面及相关模板。
- [x] 使用HUGO内置模板[Open Graph](https://gohugo.io/templates/internal#open-graph)和[Twitter Cards](https://gohugo.io/templates/internal#twitter-cards)。
- [x] 右上角GitHub链接可自定义。
- [x] 支持通过`<meta>`方式验证网站所有权。
- [x] 精简搜索引擎。
- [x] 搜索框移动到顶栏。
- [x] 使用按钮切换暗色模式，而不是在`config.toml`中直接指定是否启用暗色模式。
- [x] 删除失效站点，截至2022/03/08。
- [x] 次级菜单支持自定义图标。

## 提示

- 修改[/data/webstack.yml](/data/webstack.yml)来自定义网站。
- [/data/webstack.yml](/data/webstack.yml)中的图片位于[/static/images/logos](/static/images/logos)目录下。
- 使用[Font Awesome_v4.7.0](https://fontawesome.dashgame.com/)，使用时注意图标引用格式。

## 致谢

- [https://github.com/iplaycode/webstack-hugo](https://github.com/iplaycode/webstack-hugo)
- [https://github.com/WebStackPage/WebStackPage.github.io](https://github.com/WebStackPage/WebStackPage.github.io)