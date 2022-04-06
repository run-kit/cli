---
title: CLI 介绍
order: 1
toc: menu
---

# CLI 介绍

## 为什么要搞脚手架

在实际的开发过程中，我们经常用别人开发的脚手架，以节约搭建项目的时间。但是，当 npm 没有自己中意的脚手架时，我们不得不自己动手，此时学会开发前端 CLI 脚手架的技能就显得非常重要。搭建一个符合大众化的脚手架能使自己在项目经验上加个分哦！

## 什么时候需要脚手架

其实很多时候从 0 开始搭建的项目都可以做成模板，而脚手架的主要核心功能就是利用模板来快速搭建一个完整的项目结构，后续我们只需在这上面进行开发就可以了。

## 常规依赖库

- [commander](./commander.md)，实现 NodeJS 命令行。
- [chalk](./chalk.md)，控制台字符样式。
- [inquirer](./inquirer.md)，实现命令行之间的交互。
- [ora](./ora)，优雅终端 Spinner 等待动画。
- [fs-extra](./fs-extra)，增强的基础文件操作库。
- [log-symbols](./log-symbols)，为各种日志级别提供着色符号。
- [update-notifier](./update-notifier)，npm 在线检查更新。
- [handlebars](./handlebars)，实现模板字符替换。
- [download](./download)，实现文件远程下载。
- [listr](./listr)，可以在命令行中画出进度列表的工具。
- [ncp](./ncp)，可以实现跨平台递归拷贝文件。
- [pkg-install](./pkg-install)，可以使用 `yarn install` 或 `npm install` 安装依赖。
- [semver](./semver)，专门分析语义化版本的工具。
- [execa](./execa)，可以衍生一个 `shell`，传入 `command` 字符串在该 `shell` 直接处理的子进程管理工具，支持 `promise` 回调。
## 参考资料

- [npmjs](https://www.npmjs.com/search?q=keywords:cli)
