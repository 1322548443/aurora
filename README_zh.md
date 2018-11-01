![aurora](./aurora.png "aurora")

# aurora

[![Build Status](https://travis-ci.com/xuri/aurora.svg?branch=master)](https://travis-ci.com/xuri/aurora)
[![Backers on Open Collective](https://opencollective.com/aurora/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/aurora/sponsors/badge.svg)](#sponsors) [![Code Coverage](https://codecov.io/gh/xuri/aurora/branch/master/graph/badge.svg)](https://codecov.io/gh/xuri/aurora)
[![Downloads](https://img.shields.io/github/downloads/xuri/aurora/total.svg)](https://github.com/xuri/aurora/releases)
[![Go Report Card](https://goreportcard.com/badge/github.com/xuri/aurora)](https://goreportcard.com/report/github.com/xuri/aurora)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://github.com/xuri/aurora/blob/master/LICENSE)
[![Release](https://img.shields.io/github/release/xuri/aurora.svg?label=Release)](https://github.com/xuri/aurora/releases)

## 简介

aurora 是 Go 语言编写的一个基于 Web 的 Beanstalk 消息队列服务器管理工具，单文件无需依赖其他组件，提供跨平台支持，可以运行在 macOS、Linux 和 Windows 等操作系统上。支持管理本地和远程多个队列服务器。

[界面截图](https://github.com/xuri/aurora/wiki)

## 功能

- 跨平台支持 macOS/Linux/Windows 32/64-bit
- 单文件简单易部署
- 不依赖其他组件
- 支持读取配置文件方式启动 + 登陆用户认证
- 显示全部可用 Tube 列表
- 自动刷新 Beanstalk 队列服务器状态
- 对每个 Tube 的 ready/delayed/buried 状态进行管理
- 对每个 Tube 中的 Job 进行 add/kick/delete 操作
- 支持批量清空 Tube 中的 Job
- 自定义队列服务器状态监控项
- 支持将 Job 在不同的 Tube 之间移动
- 支持对 Tube 进行暂停操作
- 支持 Job 模糊搜索
- 可定制化的 UI (Job 文本高亮显示、监控项筛选、图表自动刷新时间和 Tube 暂停时长设置)

## 安装

下载针对不同操作系统的 [安装程序](https://github.com/xuri/aurora/releases)。

## Todo

- 404 页面支持
- Tube 列表页面支持筛选功能
- 当登陆用户认证开启时添加登出功能
- 自定义 job 文本内容高亮显示的样式主题
- Cookies 控制, 支持每个用户设置独立的 Beanstalk server

## 致谢

- Beanstalk Go 语言客户端 [beanstalkd/go-beanstalk](https://github.com/beanstalkd/go-beanstalk)
- TOML 解析器使用了 [BurntSushi/toml](https://github.com/BurntSushi/toml)
- Web UI 的设计来自于 [ptrofimov/beanstalk_console](https://github.com/ptrofimov/beanstalk_console)
- Logo 的设计来自于 [Ali Irawan](http://www.solusiteknologi.co.id/using-supervisord-beanstalkd-laravel/)。

## 社区合作

欢迎您为此项目贡献代码，提出建议或问题、修复 Bug 以及参与讨论对新功能的想法。感谢所有的 [[贡献者](CONTRIBUTING.md)].

[![Contributors](https://opencollective.com/aurora/contributors.svg?width=890&button=false)](https://github.com/xuri/aurora/graphs/contributors)

## 成为支持者

项目的发展离不开你的支持，请作者喝杯咖啡吧！aurora 通过以下方式接受捐赠： 🙏 [[成为支持者](https://opencollective.com/aurora#backer)]

[![Backers](https://opencollective.com/aurora/backers.svg?width=890)](https://opencollective.com/aurora#backers)

## 提供赞助

成为支持这个项目的赞助商，您的 Logo 将显示在此处，并带有指向您网站的链接。 [[成为赞助商](https://opencollective.com/aurora#sponsor)]

## 开源许可

本项目遵循 MIT 开源许可协议，访问 [LICENSE](https://github.com/xuri/aurora/blob/master/LICENSE) 查看许可协议文件。