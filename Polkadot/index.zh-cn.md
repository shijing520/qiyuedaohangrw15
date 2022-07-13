﻿---
weight: 
title: "Polkadot"
description: "Polkadot empowers blockchain networks to work together under the protection of shared security."
date: 2022-07-13T21:57:40+08:00
lastmod: 2022-07-13T16:45:40+08:00
draft: false
authors: ["qianxun"]
featuredImage: "173.png"
link: "https://www.zhihu.com/question/419221078/answer/1461218928"
tags: ["Polkadot","去中心化"]
categories: ["navigation"]
navigation: ["去中心化"]
lightgallery: true
toc: true
pinned: false
recommend: false
recommend1: false
---
Polkadot授权区块链网络在共享安全的保护下协同工作。

跨链底层项目Polkadot（波卡）和Cosmos的定位比较接近，同样是尝试建立一套多链的架构，将让所有接入此架构的区块链能更好的完成互相之间的信息交互。Polkadot定义了一套平行链（Parachain）和中继链（Relaychain），来分别解决扩展性和伸缩性问题。有人形象地比喻Cosmos更像安卓系统，Polkadot更像iOS。



“Polkadot 是一种异构的多链架构，旨在解决区块链架构中的伸缩性与隔离性的问题”。通俗来说，Polkadot是一个由多条区块链，异构组成的区块链集合。

作为以太坊的前核心开发者，Polkadot创始人Gavin Wood在深度参与过以太坊项目之后，深知以太坊的优势与劣势，也更加深了对区块链的认知。

Gavin Wood 很早就想解决区块链的扩容问题，2016年，基于此前的开发经验，他创建了Polkadot，通过平行链宇宙解决扩容的问题，通过中继链和转接桥解决跨链问题。

Polkadot网络由一个协作的去中心化区块链网络组成，这个网络叫做中继链，也是整个波卡网络的核心，它与并行运行的平行链交互，这些平行链可以看作是中继链的客户端，中继链的目的是保护和协调平行链。而转接桥连接的则是以太坊。

当以太坊上的节点向其他区块链发送信息时，数据将通过转接桥传递到中继链，中继链再经过几次路由后，最后找到正确的平行链，再由验证者验证，计算处理信息。

在Polkadot网络中，有四个比较重要的角色，分别是收集人、钓鱼人、提名人、验证人。收集人负责收集平行链各种信息，并把信息打包给验证人；钓鱼人专门检查恶意行为，检查出后获取奖励；提名人是一个权益群体，验证人作为其代表，他们将押金委托给验证人；验证人则帮助在Polkadot网络中打包新区块。

整个波卡网络上不同的链可以随时进行数据交换，同时波卡把大部分复杂的功能让中继链来处理，提高效率，减少资源浪费。从而，Polkadot既具备了可伸缩性又具备了可扩展性。



