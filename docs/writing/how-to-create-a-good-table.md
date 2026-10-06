# How to create a good table? / 如何在学术论文中制作出色的表格？

> 原文作者：Jia-Bin Huang ([@jbhuang0604](https://x.com/jbhuang0604))  
> 原始推文：[https://twitter.com/jbhuang0604/status/1626372600824844289](https://twitter.com/jbhuang0604/status/1626372600824844289)

---

How to create a good table?
While in grad school, I thought my job writing the paper was done after dumping all the numerical numbers from my experiments in a table. 🤦‍♂️
Check out some tips that will help you improve the quality of your tables! 🧵

如何制作出色的表格？
读研的时候，我曾经天真地以为只要把实验得出的所有数字往表格里一倒，我的论文写作任务就大功告成了。🤦‍♂️
分享一些能立刻提升你论文表格质感与可读性的小技巧！🧵

---

*1⃣ Avoid vertical lines*
Having vertical lines in a table almost always makes the table less readable. Avoid them at all costs.

*1⃣ 坚决避免使用竖线 (Avoid vertical lines)*
表格中出现竖线几乎无一例外会严重破坏表格的可读性与美感。不惜一切代价彻底摒弃竖线。

---

*2⃣ Never, ever use double rules*
Feel the urge to use double rules (\hline)?
Try the \toprule, \midrule, \bottomrule using the booktabs package instead! It levels up your table in no time!

*2⃣ 永远不要使用双横线 (Never, ever use double rules)*
老想用双横线（连续两个 \hline）？
赶快使用 booktabs 宏包中的 \toprule、\midrule、\bottomrule！它能瞬间让你的表格呈现出出版社级别的专业排版质感！

---

*3⃣ Label the columns*
Add up/down arrows to let readers know how to interpret the numbers.
Add units to let your readers understand what the numbers mean.

*3⃣ 为列标题添加明确标记 (Label the columns)*
添加向上或向下箭头（↑ / ↓），让读者秒懂指标是越大越好还是越小越好。
标注清晰的物理单位，让读者准确明白数值的真实量级含义。

---

*4⃣ Align everything*
• Align texts to the left
• Align numbers to the center
• Align numbers at consistent decimal point

*4⃣ 严格对齐所有元素 (Align everything)*
• 文本描述一律左对齐
• 数值结果一律居中对齐
• 浮点数值严格按小数点位置纵向对齐

---

*5⃣ Grouping results*
Have two or more groups of results and feel the urge again to separate them using vertical lines?
\multicolumn comes to the rescue!
Remember to use \cmidrule to group the right columns!

*5⃣ 结果合理分块编组 (Grouping results)*
包含两组或多组对比结果，又忍不住想用竖线来隔开？
\multicolumn 宏包拯救你！
记得使用 \cmidrule 优雅地为对应的子列添加横向分割线！

---

*6⃣ Encode rows with attributes*
One table, one message. Don't mix all the results together.
If possible, encode different rows using *attributes* so that it's easy for readers to understand/compare results from different rows.

*6⃣ 用属性特征标记行 (Encode rows with attributes)*
一图胜千言，一表一核心。切忌把毫无关联的实验结果胡乱混在一个表里。
如果可能，使用特定的“特征属性”来标记不同的行，使读者能够极度轻松地跨行对比各组件带来的性能差异。

---

*7⃣ Hope this helps!*
Having a clean and clear table definitely gets your message across more effectively!
What's your favorite tip on creating tables?

希望这些技巧对大家有所启发！
拥有一张整洁典雅的表格，绝对能让你的核心结论更具穿透力！
你制作学术表格最喜欢的小技巧是什么？
