# 各主流大模型调用档案的方法

档案地址（固定不变，替换为你的 GitHub 用户名）：

```text
https://raw.githubusercontent.com/hongfeiz830/ai-profile/main/profile.md
```

---

## 1. 通用开场白（所有模型适用）

新对话第一句粘贴：

```text
请先阅读我的 AI 档案：https://raw.githubusercontent.com/hongfeiz830/ai-profile/main/profile.md
阅读后用一句话确认你已了解我的背景和交互偏好，然后等我布置任务。
```

---

## 2. ChatGPT

- **有联网（GPT-4o / GPT-5 系列，联网开关打开）**：直接贴上面的开场白，模型会自行抓取 URL。
- **无联网**：把 `profile.md` 内容粘贴到「自定义指令（Custom Instructions）」；或用 Projects 功能上传 `profile.md` 作为项目知识。
- **长期免粘贴**：Settings → Personalization → Custom instructions，把档案正文粘进去（注意有长度上限，超长就只贴「六、交互偏好」部分）。

## 3. Claude

- **有联网时**：直接贴 URL。
- **无联网时**：Projects → 新建项目 → 上传 `profile.md` 到项目知识库，项目内所有对话自动生效。
- **Claude Code**：把档案放到项目的 `CLAUDE.md` 或 `AGENTS.md`，进入项目自动读取。

## 4. Gemini

- 直接贴 URL（Gemini 默认具备网页抓取能力）。
- 长期方案：Gems → 新建 Gem → 指令栏粘贴档案正文，之后在 Gem 内对话自动生效。

## 5. DeepSeek

- DeepSeek 暂无稳定的联网读取能力：新对话开头**粘贴 `profile.md` 全文**（或精简版）。
- 建议在本地存一份 `profile-short.md`（只保留基本信息 + 交互偏好，约 40 行），方便快速粘贴。
- 快捷操作：Mac 上用 `pbcopy < ~/ai-profile/profile.md` 复制到剪贴板，到对话框直接 Cmd+V。

## 6. Codex / Cursor / Claude Code 等编程 Agent

- 在你的代码仓库根目录放 `AGENTS.md`，内容写「请先读取 https://raw.githubusercontent.com/<你的用户名>/ai-profile/main/profile.md 并遵循其中的交互偏好」，即可让 Agent 类工具自动遵循你的偏好（AGENTS.md 已是跨工具通用标准，Codex / Cursor / Copilot / Gemini CLI 均支持）。

## 7. 进阶：让 AI 主动拉取（MCP 方案）

如果你使用支持 MCP 的客户端（如 Claude Desktop），可添加 GitHub 官方 MCP Server，让 AI 能主动读取你仓库里的档案，连 URL 都不用贴。适合愿意折腾配置的用户；日常使用前述第 1 条方案已足够。

---

## 方案对比

| 方式 | 生效范围 | 更新成本 | 适合场景 |
|------|----------|----------|----------|
| 每工具各存一份（自定义指令/Projects） | 单个工具 | 改一次要同步多处 | 只用一两个工具 |
| **GitHub 档案 + 贴 URL（本方案）** | 所有工具 | 改仓库即全部生效 | 多工具混用（你的情况） |
| MCP 主动拉取 | 支持 MCP 的客户端 | 改仓库即生效 | 重度 Agent 用户 |
