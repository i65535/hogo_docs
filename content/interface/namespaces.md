+++
title = "列出全部的命名空间"
description = ""
tags = [
    "get",
    "list"
]
date = "2016-04-05"
categories = [
    "registry",
    "namespace",
]

image = "3.png" 
toc = true
+++

<font size=2>列出全部的命名空间</font>
***

#### API地址：

> /api/namespaces


#### Post 数据

[Token]({{< ref "token.md" >}})


#### 返回值：

类型：[Result]({{< ref "result.md" >}})

{{< highlight html >}}
content = [{
    "update_time" : 1459152798331,
    "repo_num" : 1.0,
    "permission" : "public",
    "create_time" : 1459131768006,
    "desc" : "appsoar",
    "_id" : "appsoar",
    "owner_id" : "admin"
}]
{{< /highlight >}}

