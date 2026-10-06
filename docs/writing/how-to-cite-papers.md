# 论文写作中如何规范引用文献？ (How to cite papers?)

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1672342931473137664](https://twitter.com/jbhuang0604/status/1672342931473137664)

---

论文写作中如何规范引用文献？

恰当规范地引用文献：  
👉 给予原作者应有的学术认可  
👉 为本文研究提供扎实的立论依据  
👉 帮助读者建立完整的知识脉络。  

分享一些论文引用时的核心守则。🧵

---

### 引用奠基性的原创成果 (Cite the original work)

追溯思想的源头，引用首次提出该算法或理论的开创性文献，而不是二传手的综述文章。

---

### 区分句内引用与括号内引用 (In-text vs parenthetical)

- 句内引用（作为句子主干）："Huang et al. [1] proposed..." -> 使用 `\citet{}`  
- 括号引用（作为参考补充）："...has been widely studied [1]." -> 使用 `\citep{}`  
即使拿掉所有括号内的引用标记，你的句子在语法和语义上依然必须是完整无缺的。

---

### 彻底清洗 BibTeX 数据库 (Clean BibTeX)

- 保护专有名词的大小写（在花括号内包裹，如 `{G}aussian`）  
- 统一期刊与会议名称缩写，切忌同一会议前后名称不一致。
