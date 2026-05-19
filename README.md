# In-Parameter Learning: Why Lifelong AI Systems Need More Than Longer Context

<p align="center">
  <a href="https://github.com/MuLabPKU/In-Parameter-Learning/blob/main/Beyond_longer_context.pdf">📄 Paper</a>
</p>

## Introduction

This is the official repository for our position paper:

**In-Parameter Learning: Why Lifelong AI Systems Need More Than Longer Context**

> AI agents are increasingly expected to interact with changing users, tools, and environments over extended periods of time. However, current systems remain largely static: their parameters are fixed during deployment, while new experiences, domain knowledge, corrections, and behavioral adaptations are handled primarily through external memory management and in-context learning.
>
> In this position paper, we argue that existing in-context mechanisms are **insufficient** for lifelong AI, and advocate **In-Parameter Learning (IPL)** as a necessary complement to In-Context Learning (ICL) — referring to mechanisms that allow a deployed model to continually and safely update its parameters during use.
>
> Our central claim is that future lifelong AI systems should be built around a **hybrid paradigm**: in-context learning for immediate, provisional, and reversible information, and in-parameter learning for durable, cumulative, and generalizable growth.

## Key Arguments

- **Context windows have hard limits.** Even the most conservative estimates of lifetime experience (language, perception, structured data) exceed current 1M-token frontiers by orders of magnitude.
- **Scaling context length faces fundamental obstacles** in computation, data, and model architecture.
- **In-Parameter Learning raises the capability ceiling** by consolidating newly acquired information into model weights — enabling cumulative growth, better generalization, and reduced inference overhead.
- **ICL and IPL are complementary**, not competing: ICL handles transient, reversible context; IPL handles durable, generalizable knowledge.

## Authors

Yiding Wang\*, Haotong Yang\*, Pingzhi Tang\*, Shijia Kang\*, Cai Zhou, Chenglin Zhu, Fan Jiang, Fanxu Meng, Juntong Wang, Libin Chen, Tianyi Guan, Xiyuan Wang, Xuejie Liu, Yanbo Wang, Yansheng Mao, Yewei Liu, Yi Hu, Yufei Xu, Yuxuan Wang, Zian Li, Ziyuan He, **Xing Sun**†, **Muhan Zhang**†‡

¹Peking University &nbsp; ²Massachusetts Institute of Technology &nbsp; ³Tencent Youtu Lab

\* Equal contribution. † Senior authors. ‡ Correspondence: muhan@pku.edu.cn
