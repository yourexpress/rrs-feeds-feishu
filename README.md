# rrs-feeds-feishu

个人研究文献 RSS 订阅源。内容来自两个自动化检索源（互联网公开信息：官方博客 / arXiv / 技术社区），
按原始清单口径**全量收录**每轮检索到的所有条目（含未入选内容）。

## 订阅地址

| Feed | 内容 | 订阅 URL |
|---|---|---|
| AI 技术报告检索 | DeepMind / OpenAI / Anthropic / Microsoft / Meta / xAI / Mistral / Qwen / Seed 等机构最新发布 | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/ai-tech-reports.xml` |
| 高效计算文献检索 | 模型压缩 / ML 编译 / HPC / 边缘计算 / 低功耗计算（arXiv / 顶会 / 技术博客） | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/efficient-computing.xml` |
| 每日精选 Summary | 每天一条，当日两个检索源的重点汇总 | `https://raw.githubusercontent.com/yourexpress/rrs-feeds-feishu/main/feeds/daily-summary.xml` |

## 说明

- 软分类（RSS category）：`论文PDF` / `技术博客` / `官方公告` / `每日精选`（检索轮入选的重点内容）。
- 论文 PDF 型条目的正文为基于摘要提炼的中文省流版（研究问题 / 方法 / 关键数字 / 为什么值得看），并附原文链接；省流版会随轮次逐步补齐。
- 前两个 feed 每 12 小时更新；每日 Summary 每天一条。

> 最后更新：2026-09-20 11:58（北京时间）｜AI feed 108 条 / 高效计算 feed 655 条 / 已含省流版 25 条
