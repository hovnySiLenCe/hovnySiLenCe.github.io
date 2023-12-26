---
title: 「Author's Choice」
date: 2019-12-21 22:48:31
author: h^ovny
avatar: /images/avatar.jpg
authorAbout: devil.
authorDesc: devil.
comments: false
mathjax: true
authorLink: https://hovnySiLenCe.github.io/
description: Step by Step
keywords: 「Author's Choice」
photos:
 - https://cdn.jsdelivr.net/gh/hovnySiLenCe/cdn@1.4.2/images/cover/17-1.jpg
layout: post
---

## mistakes

### 2020-7-30
1. 原来 `double` 的精度 `15` 位是包括整部的！！！ [$\mathtt{Luogu\ P4166}$](https://www.luogu.com.cn/problem/P4140)

### 2020-7-29
1. 原来 `1<<k` 也要注意开 `LL` 的 [$\mathtt{Luogu\ P4140}$](https://www.luogu.com.cn/problem/P4140)
2. 又又又没开 `LL`，`F` 和 `G` 两个 $tag$ 数组没开 `LL` [$\mathtt{CF1114F}$](https://www.luogu.com.cn/problem/CF1114F)

### 2020-6-2
1. 打 $CF$ 模拟赛又又又又没看清题意/qiao

### 2020-5-28
1. 打 $CF$ 模拟赛的时候第三次没看清题意 [$\mathtt{CF1344C\ Quantifier\ Question}$](https://www.luogu.com.cn/problem/CF1344C)

### 2020-5-24
1. 状压方向弄反了 [$\mathtt{Luogu\ P1391}$](https://www.luogu.com.cn/problem/P1391)
2. 数组排序后没取最小值&爆 `int` 了 [$\mathtt{CF161B\ Discounts}$](https://www.luogu.com.cn/problem/CF161B)

## tips

### 2020-8-6
1. 对于这类求一段区间的权值 $=length\times value$ 的 max 或 min 值题目，一般采取用分治的思想解决

### 2020-8-1
1. 旋转卡壳最大外接矩形时维护左右边界可以使用点积

### 2020-4-4
1. 带权并查集 [$\mathtt{Luogu\ P4079}$](https://www.luogu.com.cn/problem/P4079)

### 2020-2-7
1. 处理数据的顺序要灵活变换 [$\mathtt{Link}$](https://hovnysilence.github.io/2020/02/07/Luogu_P3963-[TJOI2013]Scholarship-Solution/)

### 2020-2-5
1. 线段树区间合并可以使用重载运算符来简化代码复杂度
2. 对 $Treap$ 可以用中序遍历进行线性化

### 2020-2-4
1. 树上 $DP$ 可以转换为 $DFS$ 序后解决
2. $DP$ 遇到困难，要考虑改变状态，一般来说，有问题就找 $DP$ 状态，如：行先改变为列先
3. 使用 `for(i=S;i;i=S&(i-1))` 来遍历集合的所有子集

### 2020-1-30
1. 底数不变的矩阵快速幂可以用分块优化
