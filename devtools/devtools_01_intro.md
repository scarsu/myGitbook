# Devtools 老司机养成-第一篇-介绍

## 相关

-   本文作者：[ScarSu](www.scarsu.com)
-   非新手可以直接跳过本文看进阶系列文👉🏻[进阶系列文链接](https://doc.scarsu.com/devtools/devtools_01_intro.html)
-   本文基于 chrome 浏览器版本 73.0.3683.103（正式版本）总结
-   本文目的：关于【devtools 能做什么】建立完善的知识结构，至于怎么做，请查阅官方文档；另工具类知识需要实践，建议阅读本文时打开 [sample](https://masteringdevtools.com/)和 devtools 操作一遍
-   参考 1：[google developers 官方文档](https://developers.google.com/web/tools/chrome-devtools/)
-   参考 2：来自作者 Jon Kuoerman 在 FrontEndMaster 的 [Mastering Chrome Developer Tools v2 课程](https://frontendmasters.com/courses/chrome-dev-tools-v2)
-   参考 3：来自 作者 Tomek Sułkowski 在 medium 的[系列文章](https://medium.com/@tomsu)
-   ![Devtools脑图.png](https://i.loli.net/2019/04/19/5cb95639a9f73.png)

## web devtool 历史

-   view-source + alert 调试法
-   [Live DOM Viewer](https://software.hixie.ch/utilities/js/live-dom-viewer/)
-   [Firebug](https://getfirebug.com/)

## Chrome Devtools 界面概览

![000devtoolsAll.png](https://i.loli.net/2019/04/19/5cb955bed88ce.png)

## Tips and Tricks

-   快捷键：ctrl shift p：执行命令
-   快捷键：ctrl p：打开文件
-   快捷键：esc：显示/隐藏 drawer(第二行面板
-   快捷键：ctrl shift c：选择元素
-   more -> focus debugee：切换至正在被调试的页面
-   more -> more tools：全部面板
-   无痕模式打开网页 —> 更纯净的调试环境，无扩展代码干扰
-   实验性功能：

```
    打开url     chrome://flags/
    搜索dev
    打开Experimental Extension APIs开关
    在settings中找到experiments可以找到相关实验性功能
    shift按七次，显示隐藏的实验性功能（比如terminal
```

-   金丝雀版 chrome - [Canary - 开发者专用的每日更新版](https://www.google.cn/chrome/canary/)
-   开发者版 chrome - [Canary - 开发者专用的每周更新版](https://www.google.cn/chrome/dev/)
