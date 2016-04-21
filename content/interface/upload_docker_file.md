+++
title = "上传Dockerfile"
description = ""
tags = [
    "upload",
    "post"
]
date = "2016-04-05"
categories = [
    "tag"
]

image = "3.png"
toc = true
+++
<font size=2>提交Tag 的Dockerfile</font>
***

<!--more-->

#### API地址：

> /api/upload_docker_file

#### URL传参：

{{< highlight html >}}
filter = [{
    "repository":'appsoar/hello-world',
    "tag_name":'1.0'
}]
{{< /highlight >}}


#### Post 数据

Dockfile

#### 返回值：

类型：[Result]({{< ref "result.md" >}})

