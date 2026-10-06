# 论文写作中如何规范引用文献？ (How to cite papers?)

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1672342931473137664](https://twitter.com/jbhuang0604/status/1672342931473137664)

---

论文写作中如何规范引用文献？

文献引用不仅是学术诚信的体现，更是构建学术共同体信任的桥梁。不规范的引用极易惹恼审稿人。  
分享学术引用的关键守则。🧵

---

### 1. 引用原始开创性工作 (Cite the original work)

不要仅仅引用综述论文或二传手文献。追根溯源，找到该概念/算法最早被提出的奠基性论文并给予引用。

---

### 2. 区分句内引用与括号引用 (citet vs citep)

- 句内引用（作为主语/宾语）："Huang et al. [1] proposed ..." -> 使用 `\citet{}`。
- 括号引用（作为事实支撑）："... achieves higher accuracy [1]." -> 使用 `\citep{}` 或 `\cite{}`。  
删除括号引用后，原句子的语法必须依然完整通顺。

---

### 3. 清理 BibTeX 元数据脏数据 (Clean your BibTeX)

- 统一会议/期刊名称格式（不要一篇是 CVPR，另一篇是 IEEE Conference on Computer Vision and Pattern Recognition）。
- 保护专有名词大小写（在 BibTeX 中用大括号包裹，如 `{G}aussian`、`{P}y{T}orch`）。
- 补齐正式出版年份与卷号，避免全篇都是无来源的 arXiv 占位符。
