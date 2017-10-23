---
layout: post
title: 安装组策略编辑器 gpedit.msc
date: 2017-10-22-22:09
categories: blog
tags: [SecurityEnhance] [gpedit.msc]
---

由于微软的限制，win7以上的Windows家庭版默认是没有组策略编辑器的，而又有一些特殊操作需要使用组策略编辑器。搜索引擎中中文资源有部分并不具有普适性，本文给出一种较为简单快捷的办法。

### 注意
本文仅在win10家庭版上进行过测试

本工具原作者：jwils876-d3kh6vm

本文翻译自https://www.itechtics.com/easily-enable-group-policy-editor-gpedit-msc-in-windows-10-home-edition/

### 1. 下载gpedit.msc 安装包
https://github.com/dRl-l/resource-backup/raw/master/add_gpedit_msc/add_gpedit_msc_by_jwils876-d3kh6vm.exe
（为防止外链失效，这里的链接是笔者github上自己备份的）

### 2. 安装
安装完成后，如果是32位系统用户，此时应该已经可以使用gpedit.msc了


### 3. 64位系统后续操作
前往C:\Windows\SysWOW64
拷贝下列文件夹及文件至C:\Windows\System32
“GroupPolicy“， ”GroupPolicyUsers”， “gpedit.msc”


转载请注明原地址https://drl-l.github.io/2017/10/23/2017-10-22-Install-gpedit-msc/