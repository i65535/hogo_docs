+++
title = "列出全部的Image仓库"
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

<font size=2>查询全部的仓库信息，包括每个仓库提交的版本</font>
***

#### API地址：

> /api/repositories  【停用】

> /api/repositories/{namespace}   【停用】

> /api/repositories/usr/{user_name}

#### 分别实现：

* 查询全部的仓库信息
* 按命名空间查询仓库信息
* 按用户名查询仓库信息
<!--more-->

{{< highlight html >}}
filter = [{
    "repo":'appsoar/ubuntu',
    "permission":"public",
    "namespace":"appsoar"
}]

#### 返回值：

类型：[Result]({{< ref "result.md" >}})



{{< highlight html >}}
content = [{
    "push_time" : 1459131768008,
    "user_id" : "admin",
    "permission" : "public",
    "tags" : [{
            "size" : 633.0,
            "user_id" : "admin",
            "repository" : "appsoar/hello-world",
            "pull_num" : 4,
            "tag_name" : "latest",
            "create_time" : 1459131768589,
            "_id" : 1000,
            "digest" : "sha256:fea8895f450959fa676bcc1df0611ea93823a735a01205fd8622846041d0c7cf",
            "delete" : 0
        }, {
            "size" : 633.0,
            "user_id" : "admin",
            "repository" : "appsoar/hello-world",
            "pull_num" : 4,
            "tag_name" : "dev1.0",
            "create_time" : 1459131768589,
            "_id" : 1001,
            "digest" : "sha256:fea8895f450959fa676bcc1df0611ea93823a735a01205fd8622846041d0c7cf",
            "delete" : 0
        }
    ],
    "namespace" : "appsoar",
    "desc" : "",
    "_id" : "appsoar/hello-world",
    "delete" : 0
    }]
{{< /highlight >}}


