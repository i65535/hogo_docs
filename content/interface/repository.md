+++
title = "列出指定仓库的所有标签"
description = ""
tags = [
    "list",
    "get"
]
date = "2016-04-06"
categories = [
    "repository",
    "registry"
]

image = "3.png"
toc = true
+++

<font size=2>查询指定仓库的标签列表</font>
***

#### API地址：

> /api/repository/{namespace}/{reponame}

> /api/repository/{user_name}/{reponame}

> /api/repository/{reponame}

#### 分别实现：

* 查询**命名空间**下指定仓库的标签列表
* 查询**用户**仓库的标签列表
* 查询**公共**仓库的标签列表

<!--more-->


#### Post 数据

[Token]({{< ref "token.md" >}})

#### 返回值：

类型：[Result]({{< ref "result.md" >}})

<!--more-->

{{< highlight html >}}
content = [{
    "size" : 633.0,
    "user_id" : "admin",
    "repository" : "appsoar/hello-world",
    "permission" : "public",
    "pull_num" : 4,
    "alias" : "",
    "tag_name" : "latest",
    "create_time" : 1459131768589,
    "_id" : 1000,
    "digest" : "sha256:fea8895f450959fa676bcc1df0611ea93823a735a01205fd8622846041d0c7cf",
    "delete" : 0
}, {
    "size" : 633.0,
    "user_id" : "admin",
    "repository" : "appsoar/hello-world",
    "permission" : "public",
    "pull_num" : 4,
    "alias" : "",
    "tag_name" : "dev1.0",
    "create_time" : 1459131768589,
    "_id" : 1001,
    "digest" : "sha256:fea8895f450959fa676bcc1df0611ea93823a735a01205fd8622846041d0c7cf",
    "delete" : 0
}]
{{< /highlight >}}


