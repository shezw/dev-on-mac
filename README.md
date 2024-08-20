## About 

English | [中文](cn.md) 

This repo is used to mark and share awesome utils on macOS that useful for programming developer.

The introduction rule is below:

```markdown
## Base Category

### Main Category

#### [Utils Name]({url})

> One Sentence Introduction

? More detailed description of functions and features, less than 500 words.

free | free for part | trial | purchase

? [{notes}]({folder}/{file}) ...
```

-----

## Libraries or commandline-tools

-----

### Packages management

#### [HomeBrew](https://brew.sh/)

> The Missing Package Manager for macOS (or Linux)

free

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

[mirror](libs/homebrew.md#mirrors)

-----

### IOS Development

#### [Cocoapods](https://cocoapods.org/)

> CocoaPods is a dependency manager for Swift and Objective-C Cocoa projects.

```shell
sudo gem install cocoapods
```

### General Development Tools

#### [VirtualBox](https://www.virtualbox.org/)

> VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use.

free

```shell
brew install virtualbox
```

#### [Minikube](https://minikube.sigs.k8s.io/docs/)

> minikube quickly sets up a local Kubernetes cluster on macOS, Linux, and Windows. We proudly focus on helping application developers and new Kubernetes users.

free 

```shell
brew install minikube
```

-----

#### [nginx](https://nginx.org)

> nginx [engine x] is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev

free

```shell
brew install nginx
```

[install notice](libs/nginx.md)

#### [Postgresql](https://www.postgresql.org/)

> The World's Most Advanced Open Source Relational Database

free

```shell
brew install postgresql
```

[notice](libs/postgresql.md)

#### [MySQL](https://www.mysql.com/)

```shell
brew install mysql
```

[notice](libs/mysql.md)


#### [Redis](https://redis.io/)

> the world’s fastest in-memory database from the ones who built it.

```shell
brew install redis
```

[notice](libs/redis.md)

#### [openJDK](https://openjdk.java.net/)

> Development kit for the Java programming language

free (GPL)

```shell
brew install openjdk  # 22
brew install openjdk@21
brew install openjdk@17
brew install openjdk@11
brew install openjdk@8
```

#### [scala](https://docs.scala-lang.org/getting-started/index.html)

> A programming language that scales with you: from small scripts to large multiplatform applications.

```shell
brew install coursier/formulas/coursier && cs setup
```

Or
on Apple Silicon arch:
```shell
curl -fL https://github.com/VirtusLab/coursier-m1/releases/latest/download/cs-aarch64-apple-darwin.gz | gzip -d > cs && chmod +x cs && (xattr -d com.apple.quarantine cs || true) && ./cs setup
```
on x86_64 arch:
```shell
curl -fL https://github.com/coursier/coursier/releases/latest/download/cs-x86_64-apple-darwin.gz | gzip -d > cs && chmod +x cs && (xattr -d com.apple.quarantine cs || true) && ./cs setup
```

## Graphic UI applications

-----

### Terminal & Remote Desktop

#### [Royal TSX](https://royalapps.com/ts/mac/features)

> Comprehensive Remote Management Solution

clean design and easy to use, lots of features and plugins.
support remote desktop, VNC, SSH, UART ...

free for part

-----

### Large Language Model

#### [GPT4All](https://www.nomic.ai/gpt4all)

> Run Large Language Models Locally

free

----- 

### General Development Tools

#### [Docker Desktop](https://www.docker.com/products/docker-desktop/)

> The #1 containerization software for developers and teams

free for personal and small team

#### [SequelPro](https://sequelpro.com/)

> Sequel Pro is a fast, easy-to-use Mac database management application for working with MySQL databases.

free

MySQL support only 

### [PGAdmin](https://www.pgadmin.org/)

> pgAdmin is the most popular and feature rich Open Source administration and development platform for PostgreSQL, the most advanced Open Source database in the world.

free

[download dmg](https://www.pgadmin.org/download/pgadmin-4-macos/)

#### [dbeaver](https://dbeaver.io/)

> Universal Database Tool
DBeaver Community is a free cross-platform database tool for developers, database administrators, analysts, and everyone working with data. It supports all popular SQL databases like MySQL, MariaDB, PostgreSQL, SQLite, Apache Family, and more.

free of community version

```shell
brew install --cask dbeaver-community
```

#### [~~Redis Desktop Manager~~ RedisInsight](https://github.com/RedisInsight/RedisDesktopManager)

> GUI for Redis ® (Formerly RedisDesktopManager) <br/>RESP.app is joining forces with Redis to offer the Redis community the best possible developer experience and to increase productivity when developing with Redis. 

free

```shell
brew install redisinsight
```

-----

### Others
