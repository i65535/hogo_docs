+++
title = "接口返回数据结构"
description = ""
tags = [
    "result"
]
date = "2016-04-05"
categories = [
    "parameter"
]

image = "3.png" 
toc = true
+++

<font size=2>列出全部接口返回数据的外层包装</font>
***

#### 返回值的外层封装：

{{< highlight html >}}
result = {
    "content" : {},
    "message" : "done",
    "result" : 0
}
{{< /highlight >}}

<!--more-->

其中：

* result是一个数字，对应服务端的一个错误码，0表示成功；
* result 等于 0，表示请求成功，返回的数据在content中；
* result 不等于 0， 表示请求失败，简单的错误信息在message中。


#### 分页数据的外层封装，待定：

{{< highlight html >}}
result = {
    "content" : {},
    "message" : "done",
    "result" : 0
}
{{< /highlight >}}

其中：

* result是一个数字，对应服务端的一个错误码，0表示成功；
* result 等于 0，表示请求成功，返回的数据在content中；
* result 不等于 0， 表示请求失败，简单的错误信息在message中。
