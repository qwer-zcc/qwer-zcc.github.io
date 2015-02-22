---
layout : post
category : Codechef
title : "Codechef December Challenge"
tags : [Codechef]
---
感觉codechef改成IOI模式后已经无法阻止人类ak的步伐了。


粗略地写一下题解：

Chef and Apple Trees ：签到题，求不同颜色个数。

XOR with Subset ：签到题，搞出所有可能的异或和。

Alok-nath and His Sanskars ：状压dp，贪心直接过去了。。。

Chef and Bracket-Pairs ：区间dp。

Chef Under Pressure ：发现英文题面N竟然只有10000，就直接O(NQ)过了。。。

Kali and Devtas ：Challenge，写了个搞笑的prim就放弃治疗了。

Sereja and GCD ：听说要分块，加了些常数优化就过了。

Course Selection ：网络流。

Divide or die ：用尺规把N度角N等分。其实就是构造出1°角，貌似有个结论说用尺规在白纸上能构出的最小的整数角是3°，那么除了三的倍数的角都是可以N等分的。至于3°角用勾股定理就可以了。

Good Galaxy ：判断两个图是否同构，发现只有5组数据，就开始爆oj，爆完subtask1感觉人生无望就开始想正常做法。然后就搞了一些奇怪的hash，再配上之前爆oj的成果A掉了。以下是自认为正确的做法：由于这是一个分层图，拓扑排序后从后往前hash。
