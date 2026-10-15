# PAL_王师AI_Lab · AI4PDE Atlas 2026

在线访问：https://automationmaclassmate.github.io/ai4pde-paper-atlas/

用于课题组共享的静态论文导航。无需账号、数据库、构建服务或跟踪脚本。

## 本地查看
双击 `index.html` 即可打开。推荐使用桌面浏览器；手机可访问部署后的网页。
发布版为自包含 HTML，数据与样式内嵌，不使用 fetch，本地也可检索筛选。

## GitHub Pages 部署
1. 选择要公开的仓库，将本文件夹内容放到仓库根目录，保留相对目录结构。
2. 仓库 Settings → Pages，选择从分支发布，选择对应分支和根目录。
3. 等待 GitHub 发布完成，用其实际返回的网址访问。仓库名无需固定。
4. 若仓库不公开，先核对你的账户是否支持对应的 Pages 访问策略。GitHub Pages 网页的可访问范围不能仅由仓库是否私有来推定。

论文版权归原作者及出版方所有；本仓库提供索引、中文整理与合法原文入口。

## 维护
- 正式库 `papers.json` 与 `index.html` 内嵌数据对应；更新数据时需同步更新网页。
- `pending.json` 单列尚未核实录用/全文的候选，不计入主库。
- `coverage.md` 记录筛选覆盖与限制；不能将当前数量理解为整个领域论文总数。
- `catalog.xlsx` 用于表格筛选与后续维护；`references.bib` 只含已核实的引用元数据。
- 收藏仅保存在浏览器 localStorage 中，不跨设备同步。
- 使用安全HTTP(S)链接，没有外部跟踪和远程脚本。不托管付费论文全文。
- 主库解释、图表和引用均需结合原文复核；不等于代码复现，也不保证论文结论正确。

## 文献范围
ICML、ICLR、NeurIPS、AAAI、KDD、IJCAI、UAI 2026。
Nature Machine Intelligence、Nature Communications、JMLR、TMLR、Journal of Computational Physics、Computer Methods in Applied Mechanics and Engineering、Neural Networks。
2026年截至2026-10-15已录用或正式发表，阅读全文状态逐条标注。

## 全文解读更新

本轮逐条补充方法、输入输出、训练/测试设置、实际泛化变化、对照、结果和局限，并记录原文章节或表格定位。具体阅读范围见每条的全文访问状态和解读版本。部分全文解读可在阅读深度筛选中单独查看。

ICLR Journal Track条目保留2026会议展示信息，并明确其TMLR原始发表年份；引用文件按原始期刊论文著录。论文主文无法访问的条目不以代码默认配置冒充论文实验证据。

当前数量、版本限定和仍待补充全文的清单见 [coverage.md](coverage.md)。
