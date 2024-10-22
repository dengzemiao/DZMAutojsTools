## 一、简介

- `autojx` 全家桶，包含图色工具、配对模拟器、开发文档、开发案例、获取签名工具 .... 转载请注明出处，收集不易，后续还会进行版本更新收集。

- [自用案例](https://github.com/dengzemiao/DZMAutoxjsScripts)

- 有 `autojs pro 9.3.11` 版本，不方便公开！

## 二、安装与文档

- auto.js 开发文档

  - http://doc.autoxjs.com/#/documentation : `autoxjs` 该文档主要包含 `auto.js 4.1.1` 的 `api`，部分组件相关介绍缺失。

  - http://www.autojs.cc/docs/zh/v8/index.htm ：`autojs` 该文档还包含了最新版本的 `api`，文档更全，看第一代文档即可。

- 下载 [auto.js 4.1.1 免费版](http://www.autojs.cc/)

  - `auto.js 打包插件` 安装到手机后是看不到的，默认 `auto.js 4.1.1 免费版` 不支持打包，安装后则可以进行打包，相当于激活了打包功能，而不是多一个 `打包 app`。

  - 如果 `auto.js` 打不开，可以使用 [autoxjs](http://doc.autoxjs.com/#/) ，它是基于 `auto.js 4.1.1` 进行维护的。

  - 其次 [autoxjs](https://github.com/kkevsekk1/AutoX/releases) 这个，大部分代码写法是一致的，能一个包搞定编写跟打包，`autojs` 则拆分成了两个包，如果工程内的 `Autox.apk` 安卓失败，可以到官网进行下载，可以通过下面的方式获得当前设备的 `cpu 类型` 后进行下载。

  - `autojs` 与 `autoxjs` 使用上的差异：

    - `autojs`：在 `js` 语法上只支持老的写法，一些新的写法与函数可能不支持，但是它的 `apk` 调试应用体验更好，遇到代码 `bug` 不会直接闪退，因为 `无障碍模式` 每次重启 `app` 都需要重新打开。

    - `autoxjs`：在 `js` 语法上只支持新的写法，一些新的写法与函数都支持，而且在 `autojs` 的基础上加了不少个性化系统的函数，或调整了函数的命名。但是它的调试体验不太好，编写代码时遇到问题直接闪退，导致每次都要在打开一次 `无障碍模式`。

    - 兼容性：两者各自写的代码在对方调试器上均都会有些兼容问题， `autojs` 的写法更好被兼容。

  - 下载 `apk` 后，丢入模拟器或真机中，包内已经下载好了，根据需要安装即可。附：[查看安卓手机 CPU 类型](https://blog.csdn.net/zz00008888/article/details/133696691)，不清楚就直接下通用版本。

  - 如果工程内现有的安装包坏了，可以到官方网址进行下载，上面地址都有。

## 三、开发工具

- 下载 [VSCode](https://code.visualstudio.com/)

  - 安装插件 [Auto.js-Autox.js-VSCodeExt]：`auto.js` 或 `autox.js` 需要使用的，如果搜不到了，可以使用包内的 `aaroncheng.auto-js-vsce-fixed-1.110.0.vsix` 从本地导入添加插件，只是留个备份。

  - 如何结合以上工具进行使用，请看文章 [Autox.js 脚本开发环境搭建，从案例到打包 apk（详细流程）](https://blog.csdn.net/zz00008888/article/details/133711217)，文章内使用的是真机，但操作是一样。

- 没真机可以下载 [雷电模拟器](https://www.ldmnq.com/)。

## 四、图色工具，使用细节备注

- 图色工具必现基于 [雷电 4.x](https://www.ldmnq.com/faq/6137.html) 模拟器进行使用，真机或模拟器其他版本无效。

- 打开图色工具，左上角点击连接 `雷电模拟器 4.x`，选择后，还得再次点击选择一下雷电模拟器，这样才算连接成功。

- 尺子图标：`80%` ；找色类型：`AJ 找色` ；其他配置可以不动。

## 五、真机投屏神器 `Scrcpy`

- [Scrcpy 安装与使用](https://blog.csdn.net/zz00008888/article/details/133700678)

## 六、文件传输助手

- `Android File Transfer` 支持 `Mac、Windows` 双系统，不支持 `MacOS 13.0`。

- `Mac` 新系统可以使用 [MacDroid](https://www.macdroid.app/android-file-transfer/)，但收费，所以可以到 [这里搜索下载，你懂得](https://www.macat.vip/)。
