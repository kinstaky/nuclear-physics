#molecular #9B #9Be #10Be #10B #cluster

[pdf](D:/paper/cluster/Oertzen-1996.pdf)
## 作者
[[W. von Oertzen]]
## 理论
9Be 是经典的 [[Borromean]] 结构，由 3 个成分 $\alpha+\alpha+n$ 组成，是稳定的，但是任意两个成分的组合，即5He 或者 8Be 都是不稳定的，只有 3 个成分同时存在才是稳定的。  
这篇文章解释了经典的两核心的壳层（Nielson 模型）随两核心距离改变的演化。两核心靠近时，就是典型的壳模型，从低到高是 s$_{1/2}$、p$_{3/2}$、p$_{1/2}$，d$_{5/2}$。但是当两核心的距离增加时，似乎是泡利不相容作用降低，一部分 p$_{3/2}$ 演化为 s$_{1/2}$，p$_{1/2}$ 和一部分 d$_{5/2}$ 演化为 p$_{3/2}$，即这些壳层都能容纳两倍的粒子。对于 9Be 或者 9B，决定自旋的是第 5 个中子或者质子，从壳层演化的计算看来，距离较远时是 1/2+(u) 态，距离较近时是 3/2-(g) 态，所以会有 3/2- 和 1/2+ 两条分子转动带。**u 和 g 表示的是正宇称和负宇称。** 配合[[Oertzen2006]]以及[[Itagaki2000]]阅读。
**9Be 的态不一定能在 9B 中看到，比如说 $l=0$ 的态，只有很宽的峰。这里没太懂**
确定了 A=9 的核后，可以考虑 A=10 的 10Be，相比 9Be 多了 1 个中子。已知这两个核子处于 3/2- 和 1/2+，我们考虑两者耦合的情形。3/2- 和 1/2+可以耦合出 J=2 和 J=1，宇称则为两者相乘，所以是 2- 和 1-。对于两个 3/2-，耦合结果正常来说应该是 3+、2+、1+、0+，但是考虑到泡利不相容原理，两个核子不能同时是 $j_m$ = 3/2 也不能同时是 $j_m$ = 1/2，$j_m$=-1/2，$j_m$=-3/2，而且两个粒子是全同的，又减少了一半的可能，所以最终只剩下 $j_m^A\times j_m^B = \frac32^A\times\frac12^B, \frac32^A\times-\frac12^B, \frac32^A\times-\frac32^B, \frac12^A\times-\frac12^B, \frac12^A\times-\frac32^B, -\frac12^A\times-\frac32^B$，即 $J^\pi = 2^+, 0^+$。同理，两个 1/2+ 的中子只能耦合出 0+ 的结果。总的来说就是耦合出 2+、0+、2-、1-，恰好是 10Be 在 6MeV 附近的 4 个态。
对于 10B 来说，只考虑多出来的一个中子和一个质子，那么除了和 10Be 中也有的 2+、0+、2-、1-  组成 T=1（同位旋三重态）以外，还有 T=0（同位旋单态）的存在。此时两个核子同位旋不同，自旋取向可以相同而不破坏泡利不相容原理。那么 3/2- 和 1/2+ 就可以有更多的组合，$(\frac32^-)^2$ 组合出 3+ 和 1+（当然也有 2+ 和 0+，但是属于 T=1，所以此处不提），$(\frac12^-)^2$ 组合出 1+，$(\frac32^-\frac12^+)$ 组合出额外的 2- 和 1-（在考虑两个中子的 T=1 时，全同粒子去掉一半，所以只有一种 2- 和 1-，现在 T=0 就有额外的 2- 和 1-）。总的来说对应 T=0 的结构应该有 3+、1+、1+、2-、1-。 

## 引用

```bibtex
@article{Oertzen1996,
  title = {Two-center molecular states in ${}^9$B,${}^9$Be,${}^{10}$Be, and ${}^{10}$B},
  author = {W. von Oertzen},
  journal = {Zeitschrift für Physik A Hadrons and Nuclei},
  volume = {354},
  number = {1},
  pages = {37--43},
  year = {1996},
  issn = {0939-7922},
  doi = {10.1007/s002180050010},
  url = {https://doi.org/10.1007/s002180050010},
  abstract = {The molecular states in the mass 9 and 10 nuclei, which consist of two α-particles plus one or two valence nucleons (protons or neutrons) are discussed. Arguments for the existence of two-center dimers as excited states in 10Be and corresponding resonances (p+9Be) in 10B are given. The latter states are observed as anomalous (non statistical) population in the final state interactions in thep+9Be channel in various heavy ion collisions. With the establishment of two-center states (dimers) based on the αα-potential and a localized binding via two nucleons in10Be, the existence of more extended structures (multimers) by adding (α2n) structures to10Be* is postulated. Generally clustering intoα-particles and nucleons in terms of molecular states is expected to occur at excitation energies close to the threshold for these substructures in analogy to the clustering rules of Ikeda forα-particle nuclei. Consequences to clustering properties of neutron rich nuclei are discussed.}
}
```
