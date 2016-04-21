+++
title = "删除Tag"
description = "通过标签删除对应的镜像文件"
tags = [
    "delete",
    "post"
]
date = "2016-04-05"
categories = [
    "registry",
    "tag"
]

image = "3.png"
toc = true
+++

<font size=2>通过标签删除对应的镜像文件</font>
***

#### API地址：

> /api/tag/delete 


#### Post 数据

[Token]({{< ref "token.md" >}})

{{< highlight html >}}
filter = [{
    "repository":'appsoar/ubuntu',
    "tag_name":"dev"
}]
{{< /highlight >}}

#### 返回值：

类型：[Result]({{< ref "result.md" >}})
