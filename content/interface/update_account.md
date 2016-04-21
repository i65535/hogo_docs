+++
title = "更新用户信息"
description = ""
tags = [
    "update",
    "post"
]
date = "2016-04-05"
categories = [
    "user",
    "account",
]

image = "3.png"
toc = true
+++

<font size=2>更新用户信息，包括密码，昵称等</font>
***

#### API地址：

> /api/account/update/{user_id}


#### Post 数据

[Token]({{< ref "token.md" >}})

{{< highlight html >}}
User = {
    "password":"admin",
    "nick_name":"admin",
    "desc":"",
    "source":"local",
    "avatar":""
}
{{< /highlight >}}


#### 返回值：

类型：[Result]({{< ref "result.md" >}})

