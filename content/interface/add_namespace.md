+++
title = "创建命名空间"
description = ""
tags = [
    "add",
    "post"
]
date = "2016-04-05"
categories = [
    "registry",
    "namespace",
]

image = "3.png" 
toc = true
+++

<font size=2>创建新的命名空间</font>
***

#### API地址：

> /api/namespace/add


#### Post 数据

[Token]({{< ref "token.md" >}})

{{< highlight html >}}
namespace = {
    "_id": "appsoar",  // 全局唯一
    "owner_id":"admin",
    "desc":"",
    "permission":"public"
}
{{< /highlight >}}



#### 返回值：

类型：[Result]({{< ref "result.md" >}})
