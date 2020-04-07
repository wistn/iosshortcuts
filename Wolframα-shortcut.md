# Wolframα查询LaTeX.v2 @Guang
## 功能
手写数学式子后，调用WolframAlpha对最近复制或文本选中的LaTeX式子查询计算
## 使用
在 http://webdemo.myscript.com/views/math/index.html# 手写数学式子后，对LaTeX栏识别出的LaTeX式子复制（或者选中后共享）。点击快捷指令Wolframα，即可计算手写式子（部分识别出的LaTeX式子不能计算）。

---
**项目说明**https://github.com/wistn/iosshortcuts/blob/master/Wolframα-shortcut.md

**[English无]() | 中文**

[ [功能](#功能)、[使用](#使用)、[Demo演示无](#Demo演示无)、[安装](#安装)、[依赖](#依赖)、[更新日志](#更新日志)、[注释](#注释) ]

---
## Demo演示无
---
## 安装
- 用safari等支持URL Scheme的浏览器打开https://www.icloud.com/shortcuts/46a46fae1d594ba29fd0c37c6d7213f9

---
## 依赖
* ios的快捷指令（曾叫做捷径，前身是workflow）
* WolframAlpha、Safari
---
## 更新日志
* v2 ios捷径编码URL对+/这2个符号不转义，所以手动转义+，斜杠在wolframalpha不受影响所以不用转义。
* v1发布 190608
---
## 注释
> - 代码步骤：
> 1. 获取传入文本/剪贴板；
> 2. 进行编码和转义；
> 3. 【URL】wolframalpha://m.wolframalpha.com/input/?i=变量；
> 4. 打开URL，自动跳转wolframalpha；
> 5. 退出快捷指令。
> 6. 注释；

- 设置：在小组件中显示，在共享表单中显示，接受的类型为文本。
---
