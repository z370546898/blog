---
layout: post
title: 流程图测试
categories: [流程图, markdown]
description: 流程图测试
keywords: 流程图, markdown
flow: true
---


```flow
st=>start: 用户登陆
op=>operation: 登陆操作
cond=>condition: 登陆成功 Yes or No?
e=>end: 进入后台

st->op->cond
cond(yes)->e
cond(no)->op
```