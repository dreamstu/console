# qs-console

---

[![Build Status](https://travis-ci.org/dreamstu/console.svg?branch=master)](https://travis-ci.org/dreamstu/console)
[![spm version](http://spmjs.io/badge/qs-console)](http://spmjs.io/package/qs-console)


一套方便灵活的高可用的前端组合框架 An qs-console lib on quickjs package!

---

## Install

```
$ spm install qs-console --save
```

## Usage

```js
var qsConsole = require('qs-console');
// use qsConsole
```


---
## 配置说明

### toggle()

`释义`
显示/隐藏调试信息面板。

`参数及返回`
无


---
### resize()

`释义`
改变面板大小。

`参数及返回`
无



---
### debug(msg) *String*

`释义`
输出调试信息。

`参数及返回`
>@param msg 消息或调试代码




---
### info(msg) *String*

`释义`
输出消息。

`参数及返回`
>@param msg 消息





---
### warn(msg) *String*

`释义`
输出警告。

`参数及返回`
>@param msg 消息




---
### error(msg) *String*

`释义`
输出错误信息。

`参数及返回`
>@param msg 消息




---
### profile(profile) *String*

`释义`
开始/结束计时。

`参数及返回`
>@param msg 消息



---
### profile() *String*

`释义`
清空调试消息。

`参数及返回`
无


---
##快捷键

F2	显示/隐藏

Shift＋F2	移 动（move）

Alt ＋ Shift ＋ F2	清 空

单击左上图标可以进行类型过滤；或者Alt ＋ 单击