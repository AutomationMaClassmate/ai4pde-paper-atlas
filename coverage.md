# PAL_王师AI_Lab · AI4PDE 2026 文献数据与覆盖说明

截至2026-10-15。首版公开数据。

正式索引 260 条；其中全文核读 28 条，其余摘要级。正式索引指存在发表/录用依据及全文入口，不等于全部全文访问已独立验证。

## 当前记录数量

- AAAI 2026: 17
- Computer Methods in Applied Mechanics and Engineering: 9
- ICLR: 37
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

## 范围和方法

- 会议：ICML、ICLR、NeurIPS、AAAI、KDD、IJCAI、UAI 2026。不同track独立标注，不把workshop当主会。
- 期刊：NMI、NC、JMLR、TMLR、JCP、CMAME、Neural Networks。2026卷期/已在线发表条目按官方日期记录，不覆盖尚未发表的未来文章。
- 分类采用八个主类与交叉标签，架构和泛化实证优先，纯理论作为补充。
- 会议以官方目录及摘要关键词筛选；期刊结合官方年度目录、Crossref出版元数据与候选官方页面检索。未命中关键词的相关论文可能遗漏。
- NeurIPS来自2026官方展示数据，按OpenReview标识去重、核对accept决定及track。正式论文集未出版不妨碍已核录用论文入库。
- ICML结合PMLR与活动目录；ICLR结合官方活动目录和OpenReview。已发现ICLR独立正式论文集入口，后续继续对照作者及版本，避免将报告人误当完整作者名单。
- 同名早期预印本/撤回投稿不单独计数；跨会投稿历史不等于多次正式发表。

## 尚待完成

- 首轮不是穷尽式综述，大部分记录是摘要级，不据此推断完整超参数、最强对照或OOD设置。
- 部分官方PDF入口已列出，但本次网络访问未完成；可用性在逐篇fulltext_access字段说明。
- 代码链接可访问不代表代码可运行、数据开放或复现成功。404/受限链接不宣称开源可复现。
- 少数作者信息及出版引用仍待核对，不生成缺作者的引用条目。BibTeX入口保留原来源版本，不将arXiv条目伪造成正式卷页。
- 官方目录规模只是筛选范围，不是精读数量。各来源目录存在跨track、重复展示和论文数差异，不能简单加总为领域论文数。
- 不上传/转载付费PDF。分享原文和作者合法公开版本链接。

## 审阅建议

先看五篇HTML卡片确认文字深度，再用Excel筛选主类和阅读深度。数据、示例和页面均为审阅版，获得确认后再上传公开仓库。
