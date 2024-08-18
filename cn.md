## 关于

[English](README.md) | 中文

本仓库用于标记和分享 macOS 上对编程开发者有用的实用工具。

介绍规则如下：

```markdown
## 基础类型

### 主要类型

#### [工具名称]({链接})

> 一句话介绍

? 更详细的功能和特性描述，少于 200 汉字。

免费 | 有限制的免费 | 试用 | 付费

? [{笔记}]({folder}/{file}) ...
```

-----

## 依赖库或命令行软件

-----

### 包管理器

-----

#### [HomeBrew](https://brew.sh/)

> macOS上非常实用强大的包管理器

免费

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

[镜像](libs/homebrew.md#mirrors)

-----

### IOS 开发

#### [Cocoapods](https://cocoapods.org/)

> OC / Swift 的依赖包管理器，用于IOS开发

```bash
sudo gem install cocoapods
```

### 通用开发工具

#### [VirtualBox](https://www.virtualbox.org/)

> VirtualBox是一款功能强大的x86和AMD64/Intel64虚拟化产品，适用于企业和家庭使用。


免费

```bash
brew install virtualbox
```

#### [Minikube](https://minikube.sigs.k8s.io/docs/)

> minikube在macOS、Linux和Windows上快速建立本地Kubernetes集群。我们自豪地专注于帮助应用程序开发人员和新的Kubernetes用户。

免费

```bash
brew install minikube
```


#### [nginx](https://nginx.org)

> nginx [engine x] 是一个 HTTP 和反向代理服务器、一个邮件代理服务器和一个通用 TCP/UDP 代理服务器，最初由 Igor Sysoev 编写
> 
免费

```bash
brew install nginx
```

[安装配置信息](libs/nginx.md)

#### [Postgresql](https://www.postgresql.org/)

> 全球最先进的开源关系数据库

免费

```bash
brew install postgresql
```

[安装配置信息](libs/postgresql.md)

-----

## 图形应用

-----

### 终端和远程桌面

#### [Royal TSX](https://royalapps.com/ts/mac/features)

> Comprehensive Remote Management Solution

简洁的设计、简单易用。
丰富的特性和插件、能够轻松的进行远程桌面、SSH、UART等连接

有限制的免费


-----

### 大语言模型

#### [GPT4All](https://www.nomic.ai/gpt4all)

> 本地运行各种达模型

可以在mac上部署运行各种大模型

免费

----- 

### 通用开发工具

#### [Docker Desktop](https://www.docker.com/products/docker-desktop/)

> Docker 的桌面图形化软件

个人和小团队免费

#### [SequelPro](https://sequelpro.com/)

> Sequel Pro 是一款快速、易于使用的 Mac 数据库管理应用程序，用于处理 MySQL 数据库。

免费

仅支持MySQL

#### [dbeaver](https://dbeaver.io/)

> DBeaver Community 是一款免费的跨平台数据库工具，适用于开发人员、数据库管理员、分析师以及所有处理数据的人。它支持所有流行的 SQL 数据库，如 MySQL、MariaDB、PostgreSQL、SQLite、Apache Family 等。

社区版免费

```bash
brew install --cask dbeaver-community
```


-----

### Others
