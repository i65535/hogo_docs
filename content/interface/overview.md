+++
title = "取得系统统计信息"
description = ""
tags = [
    "overview",
    "get"
]
date = "2016-04-05"
categories = [
    "admin"
]

image = "3.png"
toc = true
+++

<font size=2>取得系统统计信息，包括用户数量，仓库数量，命名空间数量</font>
***

#### API地址：

> /api/info


#### Post 数据

[Token]({{< ref "token.md" >}})

#### 返回值：

类型：[Result]({{< ref "result.md" >}})

{{< highlight html >}}
content = {
    "namespace":1.0,
    "user":1.0,
    "repository":1.0
}
{{< /highlight >}}


