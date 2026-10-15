# PAL_王师AI_Lab · AI4PDE 文献数据与覆盖说明

内容更新：2026-10-15。正式记录 260 条，其中已依据全文的方法、实验及相关附录补充解读 256 条。其余条目的具体访问限制在详情页说明。

“全文解读”表示核对了所标明版本中的相关章节，不表示代码复现、重新证明所有定理或独立重复实验。各条目的输入输出、训练设置、泛化变化、对照、结果和局限均对应其具体任务；不适用的字段说明原因。

## 当前记录数量

- AAAI 2026: 17
- Computer Methods in Applied Mechanics and Engineering: 9
- ICLR: 34
- ICLR Journal Track: 3
- ICML: 89
- IJCAI 2026: 6
- JMLR: 9
- Journal of Computational Physics: 13
- KDD 2026: 13
- Nature Communications: 9
- Nature Machine Intelligence: 4
- NeurIPS 2026: 25
- Neural Networks: 2
- TMLR: 23
- UAI 2026: 4

## 文献范围和版本

- 会议覆盖ICML、ICLR、NeurIPS、AAAI、KDD、IJCAI、UAI 2026的相关正式录用或展示记录。
- 期刊覆盖Nature Machine Intelligence、Nature Communications、JMLR、TMLR、Journal of Computational Physics、Computer Methods in Applied Mechanics and Engineering、Neural Networks的2026相关条目。
- ICLR Journal Track为期刊论文的会议展示。原始发表年份单独标明，不计作2026主会新论文；不把workshop当主会。
- NeurIPS依据官方2026展示数据与录用决定；正式论文集尚未出版不妨碍有录用依据的条目入库。
- 优先阅读神经算子架构、泛化迁移、预训练与PDE基础模型，兼顾物理约束、时间演化、逆问题、理论及数据评测。邻近领域条目说明与PDE的实际关系。
- 若读到的是作者预印本而非最终出版版，解读版本和差异在记录中标明，不把旧版数值无条件归于最终版。
- 本库不是穷尽式综述。官方目录规模、关键词筛选数量与精读数量不能混用。

## 结果解读与使用

- 数值为原论文在具体任务、划分、预算与指标下报告的结果；单项最好、平均最好和所有任务最好明确区分。
- 明确区分同轨迹时间帧划分、新轨迹/新几何测试、分辨率变化、参数插值/外推，以及微调与零样本迁移。
- 对正文叙述与表格存在差异的地方保留具体来源与限定，不擅自补造数据。
- 代码入口被发现或可访问，不代表已运行复现、数据完整开放或结果已独立验证。
- 不托管论文PDF，只提供官方页面与合法公开版本入口。论文版权归作者和出版方所有。
- 网页与papers.json同步；catalog.xlsx用于筛选和个人笔记，references.bib用于引用导出。个人收藏只保存在本机浏览器。

## 尚未完成全文解读的条目

- Information-Coupled neural operator for computational mechanics and parametric PDEs：论文全文未取到；已实际读作者公开架构与三个实验脚本、README结果图。
- Quantum neural operators with implicit quadratic frame and expressivity advantages：已读出版社完整补充材料和作者官方实现README；主文订阅限制。官方PDF为订阅HTML，作者主页/arxiv/仓库无同版本主文；缺口明确限定为主文实验表及实施协议。
- DIMENSION DOMAIN CO-DECOMPOSITION: SOLVING PDES WITH INTERPRETABILITY：直接PDF及web open仍被OpenReview browser verification阻挡；公开搜索索引实际读取TMLR旧稿p4 §3–3.1，实验/附录未能获取。
- Wavenumber-Resolved Spectral Gating for Diffusion Models of Two-Dimensional Turbulence：论文PDF受OpenReview验证/403阻挡；实际阅读作者WRSG.py的方法、配置、拆分和OOD实现；TMLR仅摘要。
