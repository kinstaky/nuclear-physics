#10B #branch-ratio

[pdf](D:/paper/B/Kuvin-2017-PRC-10B.pdf)

通过 10B 打  [[CH2]] 靶，测量 5.164 MeV 共振态的 $\alpha$ 和 $\gamma$ 的分支比，据说这个分支比对于 ab initio 计算很有用。这篇论文的测量很有目的性，就是瞄着测量 5.164 MeV 的 $\Gamma_\alpha$ 去的，而对于 10B 的结构基本没有讨论。 
## 作者
[[S. A. Kuvin]]
## 实验
实验是在 [[Argonne]] 做的，用的是磁铁+硅的 [[HELIOS]]。关注的反应道包括：
1. 只有反冲质子
2. 反冲质子 + 4He 或 6Li
3. 反冲质子 + 4He + 6Li
没有测量光子，但是通过测量反冲质子，即缺失质量法，可以得到总宽度；而测量的带电离子 4He 和 6Li 可以得到 $\Gamma_\alpha$，所以 $\Gamma_\gamma$ 基本是通过排除法得到的。
## 分析
文章中大部分内容都是对计算分支比方法的讨论，通过对比不同的激发态的、不同粒子组合的截面，仔细推敲了 $\Gamma$ 的计算，说明其中的误差是有限的，对于效率的计算也是准确的。
## 引用

```bibtex
@article{Kuvin2017,
  title = {$\ensuremath{\alpha}$ decay of the $T=1, {2}^{+}$ state in $^{10}\mathrm{B}$ and isospin symmetry breaking in the $A=10$ triplet},
  author = {Kuvin, S. A. and Wuosmaa, A. H. and Lister, C. J. and Avila, M. L. and Hoffman, C. R. and Kay, B. P. and McNeel, D. G. and Morse, C. and McCutchan, E. A. and Santiago-Gonzalez, D. and Winkelbauer, J. R.},
  journal = {Phys. Rev. C},
  volume = {96},
  issue = {4},
  pages = {041301},
  numpages = {5},
  year = {2017},
  month = {Oct},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevC.96.041301},
  url = {https://link.aps.org/doi/10.1103/PhysRevC.96.041301}
}
```
