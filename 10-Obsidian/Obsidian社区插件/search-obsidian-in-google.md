---
uid: 20230513222808
title: Obsidian 插件：Search Obsidian In Google 让你在谷歌搜索中搜索 Obsidian 中的笔记
tags: [Obsidian, 插件, 搜索, google, 谷歌]
description: Obsidian 插件：Search Obsidian In Google 让你在谷歌搜索中搜索 Obsidian 中的笔记
author: Bon
type: other
draft: false
editable: false
modified: 20240108111043
---

# Obsidian 插件：Search Obsidian In Google 让你在谷歌搜索中搜索 Obsidian 中的笔记

## 概述

如果你之前有使用过 Cubox 或者印象笔记，你可能对其能在搜索引擎中插入来自你裁剪库的搜索印象深刻，现在这个插件就是让你也拥有了和他们一样的能力，甚至，你的数据都是存在自己本地的。

> [!Note] 插件名片
> - 插件名称：Search Obsidian In Google--由于Omnisearch 也已经实现了相同的功能，更建议使用Omnisearch
> - 插件作者：YuNing Chen
> - 插件说明：让你在谷歌搜索中搜索 Obsidian 中的笔记。
> - 插件项目地址：[点我跳转](https://github.com/qazxcdswe123/search-obsidian-in-google)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?search-obsidian-in-google)

## 效果&特性

- 支持在搜索结果中展示 Obsidian 中的笔记内容；
- 模糊匹配；
- 自动排序；
- 点击后在 Obsidian 中打开；

![Search Obsidian in Google](https://cdn.pkmer.cn/covers/search-obsidian-in-google.jpeg!pkmer)

## 使用

- 在你启用该插件后，你需要走一次以下的安装流程：
	1. 安装用于检索本地内容的 Omnisearch 插件，你可以点击这里直接跳转 [Omnisearch](obsidian://show-plugin?id=omnisearch)；
	2. 在Omnisearch 插件的设置中，打开`Enable the Http server`
	3. 安装Tampermonkey 插件，用来管理脚本。你可以点击这里直接跳转[Tampermonkey](https://www.tampermonkey.net/)
	4. 安装 Search Obsidian In Google 脚本，你可以点击这里直接跳转 [Search Obsidian In Google的chrome浏览器js脚本](https://github.com/scambier/userscripts/raw/master/dist/obsidian-omnisearch-google.user.js)
	5. 搞定！
- 然后，你只需要在谷歌搜索内容就可以在右侧看到你的笔记了；

> [!tip]
> - 点击任意标题后会请求你允许以后默认都打开，记得允许~
> - 这个插件不需要 `Local REST API` 插件配合；
> - 这是上述操作的原链接：https://publish.obsidian.md/omnisearch/Inject+Omnisearch+results+into+your+search+engine

> [!Tip] 推荐
> - 如果你对这个插件感兴趣，不妨看看如下内容
> - [[search-on-internet]] ，可以搜索并自定义搜索引擎
> - [[obsidian-custom-frames]]，将第三方 web 引用直接集成到 Obsidian
