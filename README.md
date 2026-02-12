# 🏟️ AI Coding Arena

> 用日常真实编程需求，测试不同 AI 模型的 Agentic Coding 能力

## 为什么做这个？

大模型评测总是用学术 benchmark，离普通开发者太远。这个项目用**真实、接地气的编程任务**来测试 AI 模型，看看它们到底能不能帮你干活。

灵感来自[阮一峰的测评文章](https://mp.weixin.qq.com/s/kvhc3xjpBl8Uk4-Yv0-CAw)和 [Alejandro AO 的视频](https://www.youtube.com/watch?v=c31Ow23mErE)。

## 挑战列表

| # | 挑战 | 描述 | 难度 |
|---|------|------|------|
| 01 | [网页重构设计](challenges/01-web-redesign/) | 把简陋页面重构为专业 Landing Page | 🟢 |
| 02 | [3D 太阳系沙盒](challenges/02-3d-solar-system/) | 可交互的 3D 天体运动模拟器 | 🔴 |
| 03 | [愤怒的小鸟](challenges/03-angry-birds/) | 可玩的网页版弹射游戏 | 🟡 |
| 04 | [Laravel → Next.js](challenges/04-laravel-to-nextjs/) | PHP 项目迁移到 JS 框架 | 🔴 |

## 每个挑战包含

```
challenges/XX-name/
├── PROMPT.md              # 给 AI 的提示词
├── starter/               # 起始文件（如有）
├── results/
│   ├── claude-opus-4.6/   # 各模型生成结果
│   ├── glm-5/
│   └── gpt-5.3-codex/
└── VERDICT.md             # 评测对比结论
```

## 评测维度

- ✅ **正确性** — 代码能跑吗？结果对吗？
- 🎨 **质量** — 视觉设计、代码风格、架构
- ⚡ **效率** — 生成速度、token 消耗
- 🔄 **自主性** — 遇到错误能自己修吗？需要人工干预几次？
- 💡 **创意** — 有没有超出预期的惊喜？

## 参赛模型

| 模型 | 厂商 | 类型 |
|------|------|------|
| Claude Opus 4.6 | Anthropic | 闭源 |
| GPT-5.3-Codex | OpenAI | 闭源 |
| GLM-5 | 智谱 | 开源 |
| *更多待加...* | | |

## 如何复现

1. 复制对应挑战的 `PROMPT.md` 内容
2. 在你喜欢的 AI 编程工具里跑一遍
3. 对比结果，欢迎提 PR 补充

## 贡献

欢迎提交新的挑战题目或补充模型测试结果！详见 [CONTRIBUTING.md](CONTRIBUTING.md)

## 致谢

- [阮一峰](https://www.ruanyifeng.com/) — 原始测评文章
- [Alejandro AO](https://www.youtube.com/@alejandro_ao) — 原始测试题目
- [ruanyf/ai-test-case](https://github.com/ruanyf/ai-test-case) — 提示词和起始文件

## License

MIT
