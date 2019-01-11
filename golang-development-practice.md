# Golang开发实践

Go is an open source programming language.

# Features

* 跨平台快速编译、部署
* 面向工程语言设计
* 语言级高并发支持
* 丰富内置标准库
* 单机性能高，接近C
* 语法简洁，学习曲线低
* 内置GC
* 与C无缝集成
* 商业支持：google

# 适合领域

* 网络服务开发
* 系统应用开发
* 分布式服务开发
* 微服务开发
* 云平台开发

# 示例代码

```
# REST for API

package main

import (
    "io"
    "net/http"
)

func hello(w http.ResponseWriter, r* http.Request) {
    io.WriteString(w, "How To Study GO?")
}

func main() {
    http.HandleFunc("/hello", hello)
    http.ListenAndServe(":8080", nil)
}
```

# Awesome

* Container: docker, swarm, kubernetes, rtk, runC
* Database: cockroach, 🔱, influxdb
* Monitoring: prometheus, open-falcon
* Distributed system: etcd, consul
* Message: nsq
* WebFramework: fasthttp, gin, beego
* Block chain: hyperledger, ethereum
* Other: grafana, lantern

# Function

* 无需前置声明
* 支持不定长参数
* 支持多返回值
* 支持命名返回值
* 不支持嵌套定义
* 不支持同名重载
* 不支持默认参数

