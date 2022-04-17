![](https://z3.ax1x.com/2021/11/25/oAVJSA.png)

> 每期周报都会推送到以下的渠道：

- [Telegram Channel](https://t.me/simpread/377)

- [RSS](https://rss.simpread.pro/feed)

- **简悦扩展端 → 选项页 → 通知中心**

- [竹白上的简悦专栏](https://simpread.zhubai.love)

- [知乎专栏](https://zhuanlan.zhihu.com/p/500027291)

- 微信 / 订阅时的信箱（通过竹白推送）

# 本期内容

先说点其他内容，从「2021年11月22日」开始在竹白这里推送简悦周报，算本期共计写了十六期周报，除了过年期间只发布一期外，只有两期是在周一写（晚一天），其余周报都能按时在每周的周末推送。

我已经坚持了「四个月二十六天」，也就是说：简悦每周都能发布新东西，所以才能形成周报，当然真实的数据肯定要比这个高多了，从去年7月份开始，简悦每周都能更新 3  ~ 4 篇文章。

> 无论哪种「计算方式」，对我来说也算是完成了一个 **里程碑** 🎉 

当年写博客的时候，都没法坚持到每周一篇。 😂 我想能否以这个频率坚持一年？

> 在这里立个 Flag，一年后再看。😄

## 同步助手 · 命令行版

![img](https://imgs.zhubai.love/cf9e0abaa8e94f9f960b2bd13189737b.png)

### 描述

同步助手的命令行版本，可以替代部分同步助手的功能。

### 功能比较

![img](https://imgs.zhubai.love/1e42a4494bc04773a68b59ca29375731.png)

### 适用范围

1. Linux 用户
2. 因 AMD 显卡出现错误的用户

### 如何使用

支持 UNIX 式的命令行调用，如果你只是想要指定同步的文件夹，可命令行直接使用 `./simpread-sync --sync-path <syncPath>`，更多用法请使用 `./simpread-sync -h` 查看。

### 其它平台

- Linux 用户，在主分支留下了 sytemed 的 service 模板。
- Arch Linux 用户还可以在该仓库的 pkgbuild 分支找到 PKGBUILD 文件。
- scoop 用户，也欢迎添加 [scoop bucket](https://github.com/j1g5awi/scoop-jigsaw) 来安装此程序。

> 详细请看 [同步助手 · 命令行版本](https://zhuanlan.zhihu.com/p/498978023) ⤴️，感谢[ ](https://zhuanlan.zhihu.com/p/498978023)[简悦社区](https://t.me/simpread) 用户 [Jigsaw](https://github.com/j1g5awi) 开发 👏

## 导入到 Obsidian 1.1.0

![img](https://imgs.zhubai.love/c9a67dc0440d421eaad6ba1fdc0d4d89.png)

这是简悦的一个插件，可以将阅读模式的正文导入到 Obsidan，1.1.0 版新增了 Local REST API 方案，可以解决 Windows 因字符限制无法正常导入的 Bug。

因为使用了 API Post 方案，所以建议全部用户都改为此方案。

> 详细说明请看 [导入到 Obsidian 1.1.0 ](https://zhuanlan.zhihu.com/p/498508156)⤴️。

## 稍后读技巧汇总和常见问题解决方案

![img](https://imgs.zhubai.love/09d0915394134ab689e324d78b8732db.png)

> 非常适合新用户，但以下的问题并不是每个新用户都会遇到。

- [加入稍后读后，为什么无法触发自动化方案的解决方案](https://github.com/Kenshin/simpread/discussions/2362)
- [稍后读使用阅读模式时发现标注色异常的解决方案](https://github.com/Kenshin/simpread/discussions/3162)
- [阅读模式设置为暗色模式时导出 PDF 的颜色问题的解决方案](https://github.com/Kenshin/simpread/discussions/3521)
- [当系统手动调整为暗色模式后稍后读内置标注色异常的解决方案](https://github.com/Kenshin/simpread/discussions/3164)
- [稍后读打开后空白的解决方案](https://github.com/Kenshin/simpread/discussions/2727)
- [当配置了自定义标题后导出到本地的第一个稍后读无序号（附临时解决方案） ](https://github.com/Kenshin/simpread/discussions/3098)
- 稍后读内置阅读模式无法解析的解决方案，建议使用下面两种方案：
  - 使用 [知识库](https://kb.simpread.pro/#/page/建立知识库)（首选方案） 
  - 使用 [内置解析](http://ksria.com/simpread/docs/#/Sync?id=内置解析)


- 通过 API 加入的 URL 为什么无法触发自动化

  自动化功能是扩展端功能，API 导入 URL 是服务器端行为，暂时不支持自动化。

- 本地文件如何加入稍后读

  本地 HTML 是可以被识别为阅读模式的，但因为一个 Bug 导致暂时无法加入稍后读，下个版本解决。

> 详细请看 [简悦稍后读的使用技巧汇总和常见问题说明附解决方案 ](https://zhuanlan.zhihu.com/p/497108825)⤴️。

***

# 小提示

1. 竹白上的简悦周报仅负责周报，而简悦大版本更新推送，不定期推送简悦技巧，用法，工作流等，仍以 [官方 Newsletter](http://newsletter.simpread.pro/ ) 为主，且永不改变。
2. 竹白上的内容除了每周的简悦周报外，也会聊聊其它的生产力工具。

# 如何订阅

> 建议使用微信订阅，请扫码下方二维码，邮箱订阅方式 [请看这里](https://simpread.zhubai.love/)。

![](https://cdn.jsdelivr.net/gh/23784148/upload-images@main/simpered/notice/weekly@zhubai_small.png)

# 订阅中心

> 包括：RSS / Telegram Channel 等多种订阅方案，欢迎 [前往订阅](https://simpread.pro/subscribe)。

![img](https://imgs.zhubai.love/d0e806ddd44c42018b77780e3e0f1e64.png)