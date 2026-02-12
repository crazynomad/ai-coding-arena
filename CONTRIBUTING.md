# 贡献指南

## 提交新挑战

1. 在 `challenges/` 下创建新目录，如 `challenges/13-your-challenge/`
2. 包含以下文件：
   - `PROMPT.md` — 完整的提示词
   - `starter/` — 起始文件（可选）
   - `README.md` — 挑战说明

## 补充模型结果

1. 在对应挑战的 `results/<model-name>/` 下放入生成的代码
2. 更新 `VERDICT.md` 加入你的测试结论
3. 附上截图（放在 `results/<model-name>/screenshots/`）

## 命名规范

- 挑战目录：`XX-短横线命名`
- 模型目录：`模型名-版本`，如 `claude-opus-4.6`、`glm-5`、`gpt-5.3-codex`

## 评测要求

- 记录使用的具体模型版本和工具（如 Cursor、Claude Code、Codex CLI 等）
- 记录生成时间和 token 消耗（如果能获取的话）
- 尽量不要人工干预，记录 AI 的原始输出
