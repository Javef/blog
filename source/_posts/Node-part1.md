---
title: Node第一部分-初体验
date: 2016-12-10 10:31:09
tags: 
    - Node
    - Nodejs 
categories: Node
---

## Node

- [官网](https://nodejs.org/en/)

## Node是什么?

- `Node` 中也包含 `js` 解析引擎( `Node` 现在用的就是 `V8` 引擎，速度非常快)
- `Node`
- `PHP` 、 后端使用的语言(后端写的代码是在服务器！)
  * 区分前端和后端(就是最终代码是在哪里执行的，在浏览器中执行就是前端，在服务器执行，就是后端)
- `Node` 其实【 *是一个包含的 `js` 解析引擎的软件* 】，(可以在后端使用)
  * 有了 `js` 解析引擎就会解析 `js` 代码
- 浏览器的 `js`
  * 可以通过 `js` 操作 `html`
  * 有 `DOM` (和操作 `html` 有关)，有 `BOM` (和浏览器有关)，有 `ECMA` (就是 `js` 语法规范)
+ `Node` 中的 `js`
  * 没有 `DOM`, 没有 `BOM`, 有 `ECMA`
  * `windows` (也就是说没有 `windows` 对象)

## Node安装

## Node快速开始

- 1.10 `xxx` , `Node` 就开源
  + 开源的话, 别人就可以贡献源码! 
  + 第三方社区: 觉得Node更新太慢! 
    * 第三方社区给予原来的Node继续开发加入了很多新的东西
  + 合并: 4.x 直接升到4.x
  + 4.xxx  5.xxx  6.xxx 7.xx

### Node中引入模块, 和暴露数据

- 引入模块, 使用 `Node` 中提供的 `require('./jack.js')` 方法
- 暴露数据最后使用的是 `module.exports = {xxx}`
  + 或者 `exports.xxx = yyy`

### node中不仅包含js解析引擎，还包含服务器软件的功能
- 我们电脑上只要安装了node,不需要其他的软件配置，就能够开启一个http服务

## 服务器

- 服务器就是一台电脑, 只是性能一般比我们普通电脑高!

### 注意
*file协议，默认，是不能够发ajax请求的！*

- 服务器就是一台电脑(这个电脑是有独立ip)
- 我们的笔记本也是电脑(也可以把最终的项目代码放到笔记本上! ,但是没有公司愿意这么干)
- 操作系统都可能是一样的
- 服务器能运行的软件，我们电脑也能运行

## 环境变量

- 我们在 `cmd` 窗口中敲一个命令, 本质上是执行了一个程序(软件)
- 默认按下回车时, 会到当前命令行所对应的目录寻找文件, 如果找到就立即执行
- 如果找不到就会到环境变量中的 `PATH` 中指定的目录中寻找!

例:我们把 `node` 的默认安装目录: `C:\Program Files\nodejs`, 配置 `PATH` 上，那么
我们在 `cmd` 中敲命令时，如果当前目录找不到，就会到 `C:\Program Files\nodejs` 
目录寻找相应的文件执行!

## 命令行

- 系统底层还是命令
- windows系统刚开始的时候还没有界面
- 在 `cmd` 中敲命令,或默认到当前命令行对应的目录中找文件执行

## http

## 文件读取