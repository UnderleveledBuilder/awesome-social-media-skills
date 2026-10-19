### 做小红书有哪些好用的 skill？

收录的项目里，明确针对小红书的有 {{facet:platforms:xiaohongshu}} 个，星数最高的是 {{top:facet:platforms:xiaohongshu}}。写笔记看[文案和内容创作](#group-writing)，排版和做封面看[排版、封面配图和短视频](#group-visual)，想自动发布看[发布和自动化](#group-publish)。完整对照见[按平台查找](#by-platforms)。

### 有写公众号文章、排版和发布的 skill 吗？

有。针对微信公众号的有 {{facet:platforms:wechat}} 个，星数最高的是 {{top:facet:platforms:wechat}}。多数能把 Markdown 排成公众号样式，不少能直接推到草稿箱，最后发出去一般还要你在后台自己点。

### 自媒体 skill 是什么？和 MCP 有什么区别？

skill 是给 AI 智能体（agent）装的能力包。一个 skill 就是一个文件夹，核心是一份 `SKILL.md` 说明，有的还带脚本和模板。装上之后，agent 按里面的方法完成某件事，比如按小红书的口吻写笔记、给公众号文章排版。MCP 是让 agent 能直接读写平台的工具，比如读小红书的搜索结果、把笔记发出去。两者常一起用：skill 管怎么写，MCP 管怎么发。MCP 工具单列在[MCP 和命令行工具](#group-mcp)，不计入 skill 数。

### 能装进千问、豆包、龙虾（OpenClaw）、WorkBuddy 这些国产智能体吗？

能。标准 `SKILL.md` 格式的 skill，支持技能的智能体都能装：

- **千问办公**（阿里）：把 skill 文件夹放进 `~/.qwenworkcn/skills/`
- **豆包电脑版**（字节）：在「技能」页面点「+ 添加」，上传 skill 文件夹
- **龙虾 OpenClaw**：`npx skills add 作者/仓库名 -a openclaw`
- **WorkBuddy**（腾讯）：把 skill 文件夹放进 `~/.workbuddy/skills/`
- **Kimi Code、Qwen Code、CodeBuddy、Trae、Qoder**：`npx skills add 作者/仓库名 -a 名字`，名字依次是 `kimi-code-cli`、`qwen-code`、`codebuddy`、`trae`（国内版 `trae-cn`）、`qoder`（国内版 `qoder-cn`）

Claude Code、Codex 用 `npx skills add 作者/仓库名`，每个分组末尾的「安装命令」里有现成命令。

### X、YouTube、TikTok、LinkedIn 有哪些 skill？

针对 X 的有 {{facet:platforms:x}} 个，YouTube {{facet:platforms:youtube}} 个，TikTok {{facet:platforms:tiktok}} 个，LinkedIn {{facet:platforms:linkedin}} 个。不挑平台的通用项目有 {{facet:platforms:general}} 个，星数最高的是 {{top:facet:platforms:general}}。

### 让 agent 自动发帖安全吗？会不会封号？

有两层风险。一是账号：自动发布多半要用你的账号登录，有的把 cookie 存在本地，装之前要看清楚登录态存在哪、有没有发到别的服务器。二是平台规则：各平台都限制自动化操作，批量发布、频繁互动可能被限流或封号。稳妥的用法是让 agent 写好、排好，最后一步自己点发布。

### 这些项目安全吗？

收录前逐个核对过仓库说明、目录和文件，并用脚本查过二进制和压缩包、安装钩子、远程执行和读敏感文件。收录了 {{count}} 个 skill 项目和 {{platforms}} 个工具与平台。看过但没收的，原因逐条记在 [data/ignore.toml](data/ignore.toml)（目前 {{ignored}} 个）。正常的 skill 只是几份文本文件，用不着 exe 或 dmg。脚本查不到不等于安全，安装前先读一遍它的 `SKILL.md` 和脚本。

### 多久更新一次？

每周一自动刷新星数、最近更新时间和许可证，并搜索新仓库；新仓库人工核对后才收录，见[本周新增](#new)。
