>  此功能最低要求 1.1.4.6022 版本，如低于此版本，[请升级](http://ksria.com/simpread/) 到最新版本。

位置
---

> 阅读模式 → 控制栏 → 动作 → 保存

![lzcLOe.png](https://s2.ax1x.com/2020/02/01/18otu8.md.png)

说明
---

导出到 `Notion` 的内容为 **Markdown** 格式


授权
---

> 由于  **Notion** 并未提供 API 方式，所以需要使用 下面几个步骤才能授权成功。

- 选项页 → 高级设定 → 授权管理
  ![NeHUaQ.png](https://s1.ax1x.com/2020/06/18/NeHUaQ.png)
- 用户需要手动登录到 [Notion](https://www.notion.so/) _Notion 暂不支持 API 所以需要手动登录_
- 选择授权
- 授权成功后，可选择保存的文件夹_**注意：与其它授权不同，简悦无法自动建立对应的文件夹**_
- Notion Page 支持层级文件夹 _**注意：需要 1.1.4.6016 版本才可支持**_

![lzgEwj.png](https://s1.ax1x.com/2020/06/16/NFU1k8.png)

- 导出到 Notion 支持 **database** 和 **page** 方式 _**注意：需要 1.1.4.6016 版本（以上）才可支持**_

- 导出到 **Notion  database**  **才可支持源网址**   _**注意：需要 1.1.4.6022 版本（以上）才可支持**_

[![NFwLu9.png](https://s1.ax1x.com/2020/06/22/NGcYdO.png)](https://s1.ax1x.com/2020/06/22/NGcYdO.png)

图床
---

> [1.1.4.6022](http://ksria.com/simpread/changelog.html#1.1.4.6022) 增加了 Notion.so 图床功能，导入到 Notion 的内容可自动上传为 Notion 本身，避免源页面 404 等问题

> 注意：由于使用了 Notion 私有 API 所以在上传图片时较慢 

- 选项页 → 高级设定 → 授权管理，开启图床功能 _**默认为关闭状态**_

  ![NGBOWq.png](https://s1.ax1x.com/2020/06/22/NGBOWq.png)

  ![NGcqkF.gif](https://s1.ax1x.com/2020/06/22/NGcqkF.gif)

注意
---

> A. 如何更改授权后的文件夹？

1. 选项页 → 高级设定 → 授权管理
2. 点击 **重新获取 Notion Page** 即可看到下拉列表

> B. 导出到 Notion database 的内容 **不含有链接** 的话，请参照下面的方式设定

![NNWyDJ.png](https://s1.ax1x.com/2020/06/23/NNWyDJ.png)

>  C. 导出到 Notion database 的内容也可以显示导入时间，请参照下面的方式设定

![NNWsu4.png](https://s1.ax1x.com/2020/06/23/NNWsu4.png)


授权异常
---

> 受影响的版本，包括 **1.1.4** · **1.1.4.6016** · **1.1.4.6022** _备注：选项页 → 关于 如果未显示 1.1.4.6025（不包含以上版本）的话，则视为有问题的版本_
>
> 在使用 Notion 授权时（个别情况下）会出现无法授权的错误，为避免这种问题，因此发布了 **1.1.4.6025** 版。

> 此版本唯一的用处就是：确保用户可以授权成功，**即便在发生错误的情况下，也会成功授权你的第一个 Page** 

> 如下图所示，发生这种问题后，建议请提 [Issues](https://github.com/Kenshin/simpread/issues/809)

![N0JMEF.png](https://s1.ax1x.com/2020/06/25/N0JMEF.png)

> 由于使用了私有 API 所以需要 Cookie 的开启，请确保下面的内容

![U4aM60.png](https://s1.ax1x.com/2020/07/20/U4aM60.png)

> 如果上述内容均无法成功授权或无法导出到 Notion，请看下面的方式

使用 Notion Web Cliper 并新建一个 database 的 Page 然后通过 Notion 授权并选择这个 Page 的方式