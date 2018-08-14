# \# 环境配置

## 安装

本地环境：

* vagrant + ubuntu 14.04  64位
* 当前 **root** 用户

下载go:

* `https://dl.google.com/go/go1.10.3.linux-amd64.tar.gz`

解压：

* `tar zxvf go1.10.3.linux-amd64.tar.gz -C /usr/lib`

设置path

* `export PATH=$PATH:/usr/lib/go/bin`

执行go

```go
go
```

显示如下信息：

```go
Go is a tool for managing Go source code.

Usage:

    go command [arguments]

The commands are:

    build       compile packages and dependencies
    clean       remove object files and cached files
    doc         show documentation for package or symbol
    env         print Go environment information
    bug         start a bug report
    fix         update packages to use new APIs
    fmt         gofmt (reformat) package sources
    generate    generate Go files by processing source
    get         download and install packages and dependencies
    install     compile and install packages and dependencies
    list        list packages
    run         compile and run Go program
    test        test packages
    tool        run specified go tool
    version     print Go version
    vet         report likely mistakes in packages

Use "go help [command]" for more information about a command.

Additional help topics:

    c           calling between Go and C
    buildmode   build modes
    cache       build and test caching
    filetype    file types
    gopath      GOPATH environment variable
    environment environment variables
    importpath  import path syntax
    packages    package lists
    testflag    testing flags
    testfunc    testing functions

Use "go help [topic]" for more information about that topic.
```

至此，安装成功。

