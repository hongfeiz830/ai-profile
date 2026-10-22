# hongfeiz830/ai-profile

个人 AI 档案仓库。**一处维护，所有大模型通用**——更新仓库后，ChatGPT / Claude / Gemini / DeepSeek 等任何工具下次读取到的都是最新版本，无需在每个工具里各改一份。

## 文件说明

| 文件 | 用途 |
|------|------|
| `profile.md` | 主档案（给 AI 读的核心内容，Markdown，人读机读都友好） |
| `profile.json` | 结构化版本（机器可读，适合程序化调用） |
| `prompts.md` | 各主流大模型的调用模板与开场白 |
| `PRIVATE-TEMPLATE.md` | 私有档案模板（敏感信息用，**不要**提交到本仓库） |

## 30 秒上手

在任意大模型的新对话中粘贴：

```text
请先阅读我的 AI 档案：https://raw.githubusercontent.com/hongfeiz830/ai-profile/main/profile.md
阅读后用一句话确认你已了解我的背景和偏好，然后我们开始。
```

> 注意：URL 中的 `hongfeiz830` 需替换为你自己的 GitHub 用户名。

## 隐私分级（重要）

- **本仓库公开**：职业背景、技术环境、AI 工具栈、交互偏好
- **不放本仓库**：健康信息、家庭住址、法律事务细节、任何账号密码

敏感信息用 `PRIVATE-TEMPLATE.md` 在本地维护，需要时手动粘贴给 AI。

## 各模型调用方式

详见 [prompts.md](prompts.md)。

## 更新档案后的动作

```bash
git add -A && git commit -m "update: profile vX.X" && git push
```

推完即生效，无需通知任何 AI 工具。
