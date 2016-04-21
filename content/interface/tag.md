+++
title = "列出指定标签的详细信息"
description = ""
tags = [
    "detail",
    "get"
]
date = "2016-04-06"
categories = [
    "tag",
    "registry"
]

image = "3.png"
toc = true
+++

<font size=2>查询仓库中某个标签的详细信息，包括下载次数，文件大小等</font>
***

#### API地址：

> /api/tag/{namespace}/{reponame}/{tag_name}

> /api/tag/{user_name}/{reponame}/{tag_name}

> /api/tag/{reponame}/{tag_name}

#### 分别实现：

* 查询**命名空间**下仓库的指定标签的详细信息
* 查询**用户**仓库的指定标签的详细信息
* 查询**公共**仓库的指定标签的详细信息


#### Post 数据

[Token]({{< ref "token.md" >}})

#### 返回值：

类型：[Result]({{< ref "result.md" >}})

<!--more-->

{{< highlight html >}}
content = {
    "size" : 633,
    "user_id" : "admin",
    "repository" : "appsoar/hello-world",
    "pull_num" : 4,
    "tag_name" : "latest",
    "create_time" : 1459131768589,
    "_id" : 1000,
    "digest" : "sha256:fea8895f450959fa676bcc1df0611ea93823a735a01205fd8622846041d0c7cf",
    "delete" : 0
}
{{< /highlight >}}


