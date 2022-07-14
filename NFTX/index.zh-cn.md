﻿---
weight: 
title: "NFTX"
description: "With NFTX it is possible to create, mint and trade NFT-backed tokens."
date: 2022-07-13T21:57:40+08:00
lastmod: 2022-07-13T16:45:40+08:00
draft: false
authors: ["qianxun"]
featuredImage: "137.jpg"
link: "https://zhuanlan.zhihu.com/p/364053672"
tags: ["NFTX","交易所"]
categories: ["navigation"]
navigation: ["交易所"]
lightgallery: true
toc: true
pinned: false
recommend: false
recommend1: false
---
有了NFTX，你就可以创建、铸造和交易NFT支持的代币。



**NFTX是一个为流动性差的非同质化代币（NFT）创建流动性市场的平台**。

一个社区拥有(DAO)的NFT指数基金发行协议。

NFTX是一个能够发行以NFT作为标的物的指数基金的平台协议。可以理解是将NFT转换为ERC20，这样就可以在交易所中以ERC20金的形式交易NFT。

- 核心优势：以太坊中第一个NFT作为标的物的指数基金的发行平台。



1. 一直以来，NFT 的流动性难以让人满意不满，有时需要数天甚至数月才能达成一笔交易，这让很多本想加入 NFT 领域的投资者望而却步。绝大多数NFT 只能被挂在 OpenSea 等NFT交易市场等待挑选，而不能像 ERC20 代币那样在各个交易平台无阻碍流通。
2. 对于不熟悉各种NFT的市场行情的人而言，交易新种类的NFT需要化时间和精力去学习了解NFT相关的知识，面对市场上这么多的NFT项目，怎么能高效地去交易自己不熟悉的NFT？这就是NFTX发现的市场空间，这类投资者可以在 Uniswap 上交易通过NFTX发行的基金代币，而不会在 NFTX 网站上铸造或是将基金代币兑换成NFT。这让NFT交易市场中有了更便捷的套利方法，大多数时候，只有套利者才会铸造或赎回基金代币（NFT 收藏家都喜欢浏览和交易真正的NFT，他们几乎不会想将自己的NFT收藏品转换成ERC20。这可以类比WBTC：大多数交易 WBTC 的人不会自己铸造或销毁它。）
3. 不同种类的NFT的定价成谜，没有统一的价格预言机去衡量NFT市场中合理的交易定价。



- 目前有2类指数基金

- - D1 基金支持1:1的比例将NFT兑换ERC20，用户可以去Uniswap、Sushiswap等DEX去交易ERC20，也可以用ERC20来赎回NFT（目前仅支持随机赎回，未来将可以自由选择想赎回的NFT）。
    例如用户拥有 2 个 PUNK-ZOMBIE 基金，就意味着用户可以在任意时刻兑换两个 Zombie Cryptopunk。
  - D2 基金是整合 D1 基金的 Balancer 池（意味着池子内各个不同D1 ERC20的数量的相对比例恒定）。
    用户持有一个代币，相当于持有了池子内所有不同类型的D1 Fund。例如 PUNK 就是一个 D2 基金，它结合了 5 个不同的 D1 基金，如 PUNK-BASIC、PUNK-FEMALE 等。这样做的目的是提供更多样化的风险敞口，而不需要用户持有多个代币 v2基于多个v1的ERC20按照比例做成混合池，用户可以用1个v2 token代表多个不同类型的v1 token



- 基金发行步骤（D1 Fund）

1. 小卡在NFTX的智能合约进行 创建Fund的合约写入，填写想要标的物的NFT的合约地址、Fund的基金名称、ERC20名称等，交易完成之后新基金的智能合约将被自动创建。
2. 创建好之后需要将小卡把自己的钱包内此类标的物的NFT的使用权限给NFTX的智能合约，然后使用这个合约往新基金的合约内铸币，这个过程中需要小卡自己选择哪些NFT被转到基金合约内完成铸币。假设小卡选择了3个NFT，那么交易完成后，小卡将获得3个新基金的ERC0。
3. 小卡现在还需要最后一步，就是敲定（Finalize）新基金的智能合约，完成敲定的交易后，新基金的控制权将转移给NFTX DAO官方。
4. 如果想要新基金的ERC20能够在DEX被交易，需要有人去添加流动性，这个过程谁都可以去做。



NFTX 想要将网站做成类似 NFT 领域的 CoinMarketCap 或 DefiPulse。用户到达NFTX网站后会看到 PUNK、KITTY、AXIE、AVASTR、GLYPH 和 JOY 等顶级基金的指标。最终，NFTX 将成为所有 NFT 基金的行情和发行网站，每只基金都将提供实时价格、交易量和 TVL 数据等等。



1. 用户可以用NFT贷款ERC20

2. 通过对NFT基金的链上流动性，NFTX可以作为NFT的价格预言机，

3. 用户用基金代币来抽盲盒或者送出礼品卡

   

   在我实际创建基金的过程中，最大的问题就是交易费 贵的离谱，铸造5个基金代币，需要花掉差不多200美金的gas fee，这几乎就玩不了了，通过基金代币套利想要赚回这些gas fee费也太费力了。NFTX的可能性被目前的巨高gas fee压制了，现在的套利空间太小了，所以铸币人数和交易人数都不多，到了Layer2，应该会好很多的。

   

   长期而言，NFTX将作为所有NFT基金的发行机构，这个饼是很大的。所有数字土地、游戏内物品、租赁协议、数字艺术品、数字收藏品、数字彩票等都可以作为NFT的代表。随着NFT生态系统的发展，单个的NFT将越来越难以检索，所以代币化资金ERC20将成为许多投资者和交易平台的必需品。（而且NFTX还考虑未来对所有NFTX的铸币和烧币业务收取2.5%的费用）

   

   除了目前的gas fee太贵，成本太高之外，NFTX都很不错，想象空间大，业务赛道不错，也有先发优势。项目团队是DAO，接触过的几个成员感觉都还不错。