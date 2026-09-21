# rrs-feeds-feishu

个人研究文献 RSS 订阅源。内容来自两个自动化检索源（互联网公开信息：官方博客 / arXiv / 技术社区），
按原始清单口径**全量收录**每轮检索到的所有条目（含未入选内容）。

## 订阅地址

按内容类型拆分（阅读器按订阅源归类，建议全部订阅后分入「论文」「资讯」两组）：

| Feed | 内容 | 订阅 URL |
|---|---|---|
| AI 检索 · 论文PDF | AI 机构最新论文与 PDF 技术报告，正文含中文省流版 | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/ai-papers.xml` |
| AI 检索 · 网页资讯 | AI 机构最新博客文章与官方公告 | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/ai-news.xml` |
| 高效计算 · 论文PDF | 模型压缩 / ML 编译 / HPC / 边缘计算论文，正文含中文省流版 | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/ec-papers.xml` |
| 高效计算 · 网页资讯 | 上述方向技术博客与官方公告 | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/ec-news.xml` |
| 每日精选 Summary | 每天一条，当日两个检索源的重点汇总 | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/daily-summary.xml` |

全量合并版（两库全量条目，含上述全部内容，按 category 打标）：

| Feed | 订阅 URL |
|---|---|
| AI 技术报告检索 · 全量 | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/ai-tech-reports.xml` |
| 高效计算文献检索 · 全量 | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/efficient-computing.xml` |

## 说明

- 软分类（RSS category）：`论文PDF` / `技术博客` / `官方公告` / `每日精选`（检索轮入选的重点内容）。
- 论文 PDF 型条目的正文为基于摘要提炼的中文省流版（研究问题 / 方法 / 关键数字 / 为什么值得看），并附原文链接；省流版会随轮次逐步补齐。
- 前两个 feed 每 12 小时更新；每日 Summary 每天一条。

> 最后更新：2026-09-21 23:29（北京时间）｜AI feed 108 条 / 高效计算 feed 300 条 / 已含省流版 113 条
