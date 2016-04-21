+++
title = "取得命名空间详细信息"
description = ""
tags = [
    "get",
    "detail"
]
date = "2016-04-05"
categories = [
    "namespace",
    "registry",
]

image = "3.png" 
toc = true
+++

<font size=2>取得命名空间详细信息</font>
***

#### API地址：

> /api/namespace/{namespace}


#### Post 数据

[Token]({{< ref "token.md" >}})


#### 返回值：

类型：[Result]({{< ref "result.md" >}})

{{< highlight html >}}
content = {
    "update_time" : 1459152798331,
    "repo_num" : 1,
    "permission" : "public",
    "create_time" : 1459131768006,
    "desc" : "appsoar",
    "_id" : "appsoar",
    "owner_id" : "admin"
}
{{< /highlight >}}

