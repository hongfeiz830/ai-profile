# 张宏飞 · AI 档案（All-in-One 合并版）

> **用途**：一条链接读取本仓库全部内容文件。生成时间：2026-10-22
> **包含**：profile.md、README.md、prompts.md、PRIVATE-TEMPLATE.md、profile.json（.gitignore 为 git 配置，无需 AI 阅读，故不并入）
> **来源仓库**：https://github.com/hongfeiz830/ai-profile

---

# 张宏飞 · AI 档案（AI Profile）

> **用途**：任何大模型（ChatGPT / Claude / Gemini / DeepSeek / Codex 等）在对话开始时读取本档案，即可获得用户的背景与技术偏好，无需反复自我介绍。
> **固定地址**：https://raw.githubusercontent.com/hongfeiz830/ai-profile/main/profile.md
> **版本**：v1.0 ｜ 更新：2026-10-22
> **隐私分级**：本文件为【公开版】，只含职业、技术环境与交互偏好。健康、家庭细节、法律事务等敏感信息不放本仓库。

---

## 一、基本信息

- 姓名：张宏飞
- 出生：1970 年（56 岁），定居上海
- 家庭：三口之家；女儿张颐熙，大学硕士二年级在读
- 语言：简体中文为母语；英语 CET-4（1992 年通过），可读写英文技术资料

## 二、职业背景

- 工科背景，采购方向从业 30 年以上
- 上海锅炉厂（国资委企业）6.5 年：原材料采购品类，曾管理采购团队
- 上海贝尔 → 阿尔卡特上海贝尔 → 诺基亚上海贝尔 → 诺基亚上海：完整外企/合资企业采购履历
- 兼具国企与跨国合资/独资企业双重采购背景

## 三、技术环境

- 主力机：MacBook M3（24G + 512G），macOS 用户名 hongfeiz830；另有旧机 MacBook M1
- 网络：斐讯 N1 盒子（LAN IP 192.168.2.240）运行 iStoreOS + OpenClash 旁路由；同机 Docker 部署 Sub-Store（192.168.2.240:3001）统一管理代理订阅
- 多媒体：ffmpeg 8.1.2（启用 videotoolbox 硬件编解码 + libx265），用于短视频处理流水线
- 进行中：VPS 上部署 3x-ui 代理面板
- 工具偏好：文件下载优先 curl 命令行，不用 GUI；通过 GitHub / CSDN / B站 / YouTube / X 获取 AI 前沿资讯
- 代码能力：业余水平，能读懂非专业开发代码，不从事专业开发工作

## 四、AI 工具栈

- 常用工具：ChatGPT / Claude / Gemini / DeepSeek
- 主力链路：Codex + ccswitch 调用 DeepSeek token
- 工作区：WorkBuddy（云端工作区与连接电脑为两个独立工作空间）
- 倾向：开源免费方案
- 正在研究：DeepSeek harness

## 五、当前关注方向

- AI 大模型 × 内容生成视频（政经类、生活类短视频创作方向）
- 抖音运营：粉丝约 2000，定位宣传爱国正能量
- 习惯用短视频记录生活

## 六、交互偏好（AI 必读，优先级最高）

1. **语言**：默认简体中文回复；技术术语、命令、路径保留英文原文
2. **风格**：直接、犀利、精准克制；不说教、不居高临下、不过度客套、不输出"正确的废话"
3. **质量**：逐步推导、自我验证、零幻觉；不确定就明说"不确定"，禁止编造命令、参数或事实
4. **工作流**：输出完整可粘贴的命令序列，附参数范围说明和示例；多步任务按命令逐条执行、逐条确认，不要一次性堆砌
5. **技术输出**：面向 macOS 终端环境，优先 curl 命令行方案；Mac 已装 ffmpeg 8.1.2（videotoolbox + libx265）
6. **沉淀**：倾向于把可重复的工作流固化为可复用技能/脚本，而不是一次性用完即弃
7. **回避话题**：体育比赛、电子游戏
8. **提问习惯**：多步技术任务中会追问细节；期望得到分步、可验证的答案而非概括性结论

## 七、更新记录

| 版本 | 日期 | 变更 |
|------|------|------|
| v1.0 | 2026-10-22 | 初版：基本信息、职业、技术环境、AI 工具栈、交互偏好 |

---

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

---

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

---

# 私有档案模板（PRIVATE — 严禁提交到公开仓库）

**用法**：复制本文件为 `private.md`，保存在本地 `~/ai-profile/private.md`，并把文件名加入 `.gitignore`。
**使用方式**：需要 AI 了解敏感背景时（如涉及家庭安排、健康作息、法律事务的对话），在开场白之后追加粘贴本文件内容，或仅粘贴相关段落。

> 注意：本模板内容为示例占位，请按实际情况填写；填写前想清楚"这段信息给这个 AI 工具看是否合适"。

---

## 健康与作息

- 高血压（遗传性），需规律服药，服药时间：____
- 帕金森病（中晚期），开期不影响生活和工作；药物生效节奏：____
- 作息：早睡早起，约 __ 点睡、__ 点起；精力最好的时段：____
- 回复时长/强度偏好：____（如"晚上 9 点后不安排烧脑任务"）

## 家庭安排

- 妻子/女儿需要协调的事项：____
- 父母（浙江农村，年事已高）探望/照顾节奏：____
- 兄长在浙江县城工作，可协调事项：____

## 法律事务

- 车位转让纠纷：(2026)沪0117民初9504号，2026-06-26 结案生效
- 判决：被告松江国际医药城有限公司十日内协助将 B316 车位过户至张颐熙名下
- 车位产权：沪(2021)松字不动产权第051575号，无抵押无查封，非人防产权
- 后续跟进事项：____

## 财务与资产（按需填写）

- ____

## 其他只给本地 AI 知道的信息

- ____

---

## 附：profile.json（结构化版）

```json
{
  "schema": "ai-profile/v1",
  "name": "张宏飞",
  "name_pinyin": "Zhang Hongfei",
  "birth_year": 1970,
  "location": "上海",
  "language": ["zh-CN", "en (CET-4)"],
  "family": {
    "members": 3,
    "daughter": "张颐熙（大学硕士二年级在读）"
  },
  "career": {
    "domain": "采购（原材料品类）",
    "years": "30+",
    "history": [
      "上海锅炉厂（国资委企业）6.5 年，原材料采购，曾任采购团队管理",
      "上海贝尔",
      "阿尔卡特上海贝尔",
      "诺基亚上海贝尔",
      "诺基亚上海"
    ],
    "background": "国企 + 跨国合资/独资企业双重采购背景"
  },
  "tech_environment": {
    "primary_machine": "MacBook M3 24G+512G (macOS user: zhanghongfei)",
    "legacy_machine": "MacBook M1",
    "home_lab": {
      "device": "斐讯 N1 盒子 (LAN IP 192.168.2.240)",
      "os": "iStoreOS + OpenClash 旁路由",
      "docker_services": ["Sub-Store (192.168.2.240:3001)"]
    },
    "multimedia": "ffmpeg 8.1.2 (videotoolbox + libx265)",
    "in_progress": ["VPS 部署 3x-ui 代理面板"],
    "code_level": "业余水平，能读非专业开发代码",
    "info_sources": ["GitHub", "CSDN", "B站", "YouTube", "X"]
  },
  "ai_toolchain": {
    "tools": ["ChatGPT", "Claude", "Gemini", "DeepSeek"],
    "primary_stack": "Codex + ccswitch (DeepSeek token)",
    "workspace": "WorkBuddy（云端工作区 / 连接电脑，两个独立空间）",
    "preference": "开源免费方案",
    "researching": ["DeepSeek harness"]
  },
  "current_focus": [
    "AI 大模型 × 内容生成视频（政经类、生活类短视频）",
    "抖音运营（粉丝约 2000，爱国正能量定位）",
    "短视频记录生活"
  ],
  "interaction_preferences": {
    "language": "简体中文优先，技术术语保留英文",
    "style": ["直接", "犀利", "精准克制", "零幻觉", "逐步推导", "自我验证"],
    "avoid": ["说教", "居高临下", "过度客套", "编造命令或事实", "体育比赛话题", "电子游戏话题"],
    "workflow": "完整可粘贴命令序列 + 参数范围 + 示例；多步任务逐条执行逐条确认",
    "cli_preference": "curl 命令行优先，macOS 终端环境",
    "reuse": "倾向把重复工作流固化为可复用技能/脚本"
  },
  "updated": "2026-10-22",
  "version": "1.0.0"
}
```
