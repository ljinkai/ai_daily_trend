# AI Daily Trend 🤖

每日自动抓取 Twitter/X、YouTube、Hacker News、36氪、TechCrunch、InfoQ 的 AI 最新资讯，经 AI 翻译、质量筛选后归档存储，同步推送钉钉。

## 目录结构

```
ai_daily_trend/
├── README.md
├── 2026/
│   ├── README.md          # 年度汇总索引
│   ├── 02/
│   │   ├── 2026-02-28.md  # 每日资讯（上午版 + 下午版合并）
│   │   └── ...
│   └── ...
└── 2027/
    └── ...
```

## 数据来源

| 平台 | 说明 | 优先级 |
|------|------|--------|
| 🐦 Twitter / X | 16 位 AI 核心 KOL 推文（优先抓取） + 关键词搜索 | ⭐⭐⭐ |
| 🔥 Hacker News | AI 相关热门讨论，score ≥ 80 | ⭐⭐⭐ |
| 📰 36氪 | 国内 AI 商业资讯 | ⭐⭐ |
| 🌐 TechCrunch | 英文 AI 科技媒体 | ⭐⭐ |
| 🛠 InfoQ | 技术实践与架构 | ⭐⭐ |
| 📺 YouTube | AI 视频资讯与教程 | ⭐ |

## 重点追踪的 Twitter KOL

| 账号 | 姓名 | 标签 |
|------|------|------|
| @sama | Sam Altman | OpenAI CEO |
| @karpathy | Andrej Karpathy | AI 研究 |
| @AndrewYNg | Andrew Ng | AI 教育 |
| @demishassabis | Demis Hassabis | DeepMind CEO |
| @ylecun | Yann LeCun | Meta AI |
| @drfeifei | Fei-Fei Li | 斯坦福 AI |
| @fchollet | François Chollet | Keras |
| @yoshua_bengio | Yoshua Bengio | 深度学习 |
| @katecrawford | Kate Crawford | AI 伦理 |
| @RichardSSutton | Richard Sutton | 强化学习 |
| @alliekmiller | Allie K. Miller | AI 商业 |
| @KirkDBorne | Kirk Borne | 数据科学 |
| @BernardMarr | Bernard Marr | AI 趋势 |
| @rowancheung | Rowan Cheung | AI 工具 |
| @mattshumer_ | Matt Shumer | 生成 AI |
| @yoheinakajima | Yohei Nakajima | AI 应用 |

## 关键词

`OpenAI` · `Claude` · `Gemini` · `GPT` · `LLM` · `Anthropic` · `openclaw` · `DeepSeek` · `Grok` · `Mistral` · `大模型` · `人工智能`

## 质量标准

每次推送精选 **15-25 条优质内容**，过滤掉：
- 标题模糊泛泛（"AI 改变世界"类）
- 纯广告 / 课程推广
- 超过 7 天的非重大旧闻

## 更新频率

每天 **09:00** 和 **15:00**（北京时间）自动推送，同步归档至本仓库。

---

> 由 [OpenClaw](https://openclaw.ai) 自动驱动 · 质量优先
