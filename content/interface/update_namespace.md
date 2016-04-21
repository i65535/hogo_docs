+++
title = "更新命名空间"
description = ""
tags = [
    "update",
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

<font size=2>更新的命名空间部分信息，如描述，权限</font>
***

#### API地址：

> /api/namespace/update/{namespace}


#### Post 数据

[Token]({{< ref "token.md" >}})

{{< highlight html >}}
namespace = {
    "desc":"",
    "permission":"public"
}
{{< /highlight >}}



#### 返回值：

类型：[Result]({{< ref "result.md" >}})
