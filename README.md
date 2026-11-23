<!-- 本文件由 scripts/build.py 生成，请勿手改。要改内容请编辑 data/ 或 templates/ 后重新生成。 -->

# Awesome Social Media Skills

**中文** · [English](README.en.md)

> 自媒体运营 Skill（技能包）精选：小红书、抖音、公众号、视频号、B 站，以及 X、YouTube、TikTok、LinkedIn。从选题、写稿、配图到发布和看数据，装进千问、豆包、龙虾（OpenClaw）、WorkBuddy、Claude Code、Codex 等智能体就能用。
>
> A curated list of agent skills for social media: Xiaohongshu (RedNote), Douyin, WeChat, Bilibili, X, YouTube, TikTok and LinkedIn.

这里收录给 AI 智能体（agent）用的自媒体 skill：写小红书笔记和公众号文章、做封面和短视频、定时发布、追热点、回评论、看数据。大多是标准 SKILL.md 格式，支持技能的智能体都能装，装法见[常见问题](#faq)。每个项目都经过人工核对，收录前用脚本做过安全检查，按要干的活和平台整理。

收录 354 个 skill 项目 + 51 个 MCP 工具和开源平台 · 元数据更新于 2026-11-23

**图例**：🌟 精选 · 📝 提示词文件（非标准 skill）· 🔌 MCP 或命令行工具 · 🧩 完整应用 · 💤 超过 180 天未更新 · 📦 已归档 · ⚠️ 仓库失效

**让 agent 帮你挑**：这份清单也是一个 skill。运行 `npx skills add UnderleveledBuilder/awesome-social-media-skills` 装上 social-media-skill-finder，再问你的 agent「我做小红书美妆号，装哪个 skill 写笔记？」。

> [!WARNING]
> 能替你发帖、回私信的工具，多半要用你的账号登录，有的会把 cookie 存在本地。装之前先读它的 SKILL.md 和脚本，看登录态存在哪、发给了谁。平台限制自动化操作，批量发布可能被限流或封号。

> [!NOTE]
> 「人工核对」指核对过仓库说明、目录结构和分类，不等于实测过效果。「安全检查」是用脚本查二进制和压缩包、安装钩子、远程执行和读敏感文件，并列出脚本里的联网地址；查不到不等于安全。

## 目录

- [本周新增](#new)（1）
- [按类型](#by-group)
  - [全流程运营：选题 → 创作 → 发布 → 复盘](#group-pipeline)（57）
  - [文案和内容创作](#group-writing)（34）
  - [排版、封面配图和短视频](#group-visual)（137）
  - [发布和自动化](#group-publish)（39）
  - [选题、热点和数据分析](#group-research)（72）
  - [账号定位和增长](#group-strategy)（15）
  - [MCP 和命令行工具（不是 skill）](#group-mcp)（33）
  - [相关开源平台（完整应用，不是 skill）](#group-apps)（18）
- [按平台查找](#by-platforms)
- [常见问题](#faq)
- [相关资源](#resources)
- [收录徽章](#badge)

<a id="new"></a>
## 本周新增

近 7 天新收录 1 个：

- [okdata skills](https://github.com/okdataapi/skills) ★0：社媒和电商调研：竞品动态、评论口碑、品牌提及、热点、达人、字幕、广告和商品评价，抖音、小红书、公众号、B 站、微博、TikTok、YouTube、X 等都能查

<a id="by-group"></a>
## 按类型

<a id="group-pipeline"></a>
### 全流程运营：选题 → 创作 → 发布 → 复盘

一套 skill 管到底：找选题、写稿配图、发出去、看数据，适合一个人运营一个或几个账号。

- 🌟 **[baoyu-skills](https://github.com/JimLiu/baoyu-skills)** · ★ 27.8k<br>宝玉的 skill 合集：小红书图文、文章配图、封面、信息图，发布到公众号、X 和微博，另有翻译和网页转 Markdown<br><sub>平台：小红书 · 公众号 · 微博 · X</sub><br><sub>更新于 2026-11-20 · 多语言 · 23 个 skill · MIT</sub>

- 🌟 **[wewrite](https://github.com/imraywang/wewrite)** · ★ 3.7k<br>公众号全流程：抓热点、评选题、搜素材、按你的风格写稿并审稿，可选配图、18 套排版和推送草稿箱，改稿后能学你的改法<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-11-16 · 中文 · 10 个 skill · MIT</sub>

- **[instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill)** · ★ 8.3k<br>Instagram 13 个 skill：26 种钩子公式写 Reels、找本领域爆款、查文案、去 AI 腔，免费、不用注册和 API Key<br><sub>平台：Instagram</sub><br><sub>更新于 2026-09-13 · 英文 · 13 个 skill · MIT</sub>

- **[youtube-agent-skill](https://github.com/Jakeschincariol/youtube-agent-skill)** · ★ 7k<br>YouTube 11 个 skill：钩子打分的脚本、标题和缩略图配对检查、按字幕出剪辑单、找观众流失点、切 Shorts<br><sub>平台：YouTube</sub><br><sub>更新于 2026-09-16 · 英文 · 11 个 skill · MIT</sub><br><sub>💡 另有 ChatGPT 版：Jakeschincariol/chatgpt-youtube-agent-skill</sub>

- **[sergebulaev/linkedin-skills](https://github.com/sergebulaev/linkedin-skills)** · ★ 6.1k<br>LinkedIn 12 个 skill：按你的口吻写帖子和评论、分析信息流、排发帖节奏，去 AI 腔，发布前等你批准<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-11-18 · 英文 · 14 个 skill · MIT</sub>

- **[yichen-skills](https://github.com/mcncarl/yichen-skills)** · ★ 5.4k<br>逸尘的创作者 skill：写作、把内容切成 X 推文、推送 X Articles 草稿、存公众号文章，导出自己的小红书、抖音收藏和 X 书签<br><sub>平台：小红书 · 抖音 · 公众号 · X</sub><br><sub>更新于 2026-11-01 · 多语言 · 16 个 skill</sub>

- **[charlie947/social-media-skills](https://github.com/charlie947/social-media-skills)** · ★ 4.8k<br>17 个社媒 skill：学你的口吻、写 LinkedIn 帖子、调研、看数据、写 Reels 脚本、生成 Gemini 配图提示词<br><sub>平台：Instagram · LinkedIn · Newsletter</sub><br><sub>更新于 2026-10-18 · 英文 · 17 个 skill · MIT</sub>

- **[linkedin-agent-skill](https://github.com/Jakeschincariol/linkedin-agent-skill)** · ★ 3.8k<br>LinkedIn 11 个 skill：21 种钩子写帖子、评论、回复、主页打分、周计划，去 AI 腔并在发出前打分<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-09-17 · 英文 · 11 个 skill · MIT</sub>

- **[xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill)** · ★ 2.6k<br>OpenClaw 小红书运营：推荐流和账号分析、选题、创作、发布、复盘，能输入爆款链接复刻同类笔记；用浏览器自动化，首次扫码登录<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-19 💤 · 中文</sub>

- **[growth-lab](https://github.com/tsingyuai/growth-lab)** · ★ 2k<br>产品增长闭环：读懂产品、用 MediaCrawler 采小红书/抖音/B站/快手等数据做调研，执行增长动作再按结果改进<br><sub>平台：小红书 · 抖音 · B 站 · 微博 · 知乎 · 快手</sub><br><sub>更新于 2026-11-13 · 中文 · 22 个 skill · Apache-2.0</sub>

- **[creator-buddy](https://github.com/SpaceZephyr/creator-buddy)** · ★ 1.9k<br>创作者工具箱：搜小红书/B站/抖音热门、挖公众号爆款、拆竞品和评论，再起标题、写正文、配图、剪视频、出封面<br><sub>平台：小红书 · 抖音 · 公众号 · B 站</sub><br><sub>更新于 2026-08-26 · 中文 · 33 个 skill</sub>

- **[instagram-skills](https://github.com/sergebulaev/instagram-skills)** · ★ 905<br>Instagram 9 个 skill：前 125 字钩子的文案、轮播逐页规划、话题标签和周计划，读数据要 Apify，发布走 Publora<br><sub>平台：Instagram</sub><br><sub>更新于 2026-11-18 · 英文 · 11 个 skill · MIT</sub>

- **[claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post)** · ★ 899<br>学你在 Facebook 的口吻写贴文，排 14 天日历，确认后发到 FB、IG、Threads、X，用已登录的 Chrome 管理留言<br><sub>平台：X · Instagram · Threads · Facebook</sub><br><sub>更新于 2026-11-13 · 中文 · 2 个 skill · MIT</sub>

- **[claude-youtube](https://github.com/AgriciDaniel/claude-youtube)** · ★ 848<br>YouTube 创作者 skill：频道审计、视频 SEO、留存脚本和钩子、缩略图、内容策略、Shorts、数据和变现<br><sub>平台：YouTube</sub><br><sub>更新于 2026-04-10 💤 · 英文 · MIT</sub>

- **[wechat-article-skills](https://github.com/aiworkskills/wechat-article-skills)** · ★ 759<br>公众号运营助手：选题、写稿、审稿（敏感词、错别字、AI 味）、排版、配图、发布 8 个 skill 串成一条线，每步停下等你确认<br><sub>平台：公众号</sub><br><sub>更新于 2026-09-23 · 中文 · 9 个 skill · Apache-2.0</sub>

- **[self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow)** · ★ 729<br>模块化自媒体工作流：创作简报、账号策略、热点与竞品研究、平台原生文案、短视频方案、多平台发布、数据复盘和归档，不绑定工具<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · YouTube</sub><br><sub>更新于 2026-11-09 · 多语言 · 10 个 skill · MIT</sub>

- **[blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills)** · ★ 675<br>14 个社媒 skill：内容策略、日历、配图文案、轮播文案、涨粉分析，覆盖文字型和图片型平台<br><sub>平台：X · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-05 · 英文 · 14 个 skill · MIT</sub>

- **[claude-content-skills](https://github.com/Ootto-AI/claude-content-skills)** · ★ 548<br>Instagram Reels 内容工厂：找爆款格式、拆钩子、按你的口吻写脚本和配文、排两周日历，把评论变成销售线索<br><sub>平台：Instagram</sub><br><sub>更新于 2026-11-07 · 英文 · 55 个 skill · MIT</sub>

- **[rayskills](https://github.com/imraywang/rayskills)** · ★ 403<br>WeWrite 作者的工具箱：本地知识库、长文、口播稿、封面、解说视频，内容直达公众号和 X Articles 草稿箱<br><sub>平台：公众号 · X</sub><br><sub>更新于 2026-11-05 · 中文 · 9 个 skill</sub>

- **[social-media-skills/skills](https://github.com/social-media-skills/skills)** · ★ 372<br>106 个社媒 skill：品牌和口吻、内容日历、LinkedIn 帖子、短视频、设计、各平台增长、发布和数据分析<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-10-15 · 英文 · 106 个 skill · MIT</sub>

- **[wechat_article_skills](https://github.com/BND-1/wechat_article_skills)** · ★ 318<br>公众号四件套：科技科普写作、AI 产品经理视角写作、Markdown 转公众号排版、推送草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-01-16 💤 · 中文 · 4 个 skill</sub>

- **[jiji262/wechat-publisher](https://github.com/jiji262/wechat-publisher)** · ★ 300<br>公众号文章一条命令：多轮搜素材、写 3000-5000 字长文、每章配手绘信息图、排版、推送草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-22 · 中文</sub>

- **[social-ai-team](https://github.com/stevenflanagan1/social-ai-team)** · ★ 284<br>给小企业的社媒团队：品牌建档、月度内容日历、配图文案、LinkedIn 文章、创意和月度复盘<br><sub>平台：X · TikTok · Instagram · LinkedIn · Threads · Facebook</sub><br><sub>更新于 2026-11-09 · 英文 · 10 个 skill</sub>

- **[content-pipeline](https://github.com/OrangeViolin/content-pipeline)** · ★ 222<br>一个 skill 管内容生产和分发：收素材、出稿、排版、封面、朋友圈文案、多平台改写，用 Chrome 自动发布<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-11-20 · 中文 · MIT</sub>

- **[wenzi-xiaohongshu-workflow](https://github.com/wenziai/wenzi-xiaohongshu-workflow)** · ★ 213<br>文子的小红书冷启动工作流：账号定位、选题标题、真人化改稿和合规检查、图文规划、排期和数据复盘<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-20 · 中文 · 6 个 skill</sub>

- **[x-skills](https://github.com/sergebulaev/x-skills)** · ★ 194<br>X 的 9 个 skill：按你的口吻写推文和长串、拆爆款推文的钩子、写回复和引用、排一周内容，发布前等你批准<br><sub>平台：X</sub><br><sub>更新于 2026-11-18 · 英文 · 11 个 skill · MIT</sub><br><sub>💡 发布走 Publora，它的免费档不含 X</sub>

- **[facebook-skills](https://github.com/sergebulaev/facebook-skills)** · ★ 160<br>Facebook 公共主页 8 个 skill：按你的口吻写帖子并审稿、控制在 80 字符内提高互动、读评论、排一周内容<br><sub>平台：Facebook</sub><br><sub>更新于 2026-11-18 · 英文 · 10 个 skill · MIT</sub>

- **[843645440/wechat-skill](https://github.com/843645440/wechat-skill)** · ★ 142<br>公众号内容工具包：追热点、科技写作、去 AI 味、配图和封面、12 套排版主题，写入多个账号的草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-25 · 中文 · 10 个 skill</sub>

- **[tiktok-skills](https://github.com/sergebulaev/tiktok-skills)** · ★ 137<br>TikTok 8 个 skill：前 3 秒钩子脚本、配文和话题标签、蹭趋势、一周计划，按真实数据读赛道，发布走 Publora<br><sub>平台：TikTok</sub><br><sub>更新于 2026-11-18 · 英文 · 10 个 skill · MIT</sub>

- **[WorkBuddy](https://github.com/adsorgcn/WorkBuddy)** · ★ 134<br>iLang 两个运营专家：公众号爆文专家找题、写稿、出封面提示词、推草稿箱；X 运营专家找题、发帖、回自己帖下评论<br><sub>平台：公众号 · X</sub><br><sub>更新于 2026-11-22 · 中文 · 7 个 skill · MIT</sub><br><sub>💡 公众号数据走 wxrank，看一次榜扣 1 积分；X 走接口发帖要充值</sub>

- **[wemp-operator](https://github.com/IanShaw027/wemp-operator)** · ★ 114<br>OpenClaw 公众号运营：从 20 多个来源采集热点，生成日报周报和数据分析，检查并回复评论，写文章<br><sub>平台：公众号</sub><br><sub>更新于 2026-02-02 💤 · 中文 · MIT</sub><br><sub>💡 要先装 wemp skill</sub>

- **[sergebulaev/youtube-skills](https://github.com/sergebulaev/youtube-skills)** · ★ 106<br>YouTube 和 Shorts 的包装 skill：高点击标题、带章节的 SEO 描述、留存钩子、缩略图简报、社区帖和频道主页审计<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-18 · 英文 · 11 个 skill · MIT</sub>

- **[threads-skills](https://github.com/sergebulaev/threads-skills)** · ★ 75<br>Threads 8 个 skill：按你的口吻写单帖和串帖、写回复、按真实数据读赛道、排一周内容，发布前等你批准<br><sub>平台：Threads</sub><br><sub>更新于 2026-11-18 · 英文 · 10 个 skill · MIT</sub>

- **[Fully-automatic-article-generation-skill](https://github.com/solar-luna/Fully-automatic-article-generation-skill)** · ★ 73<br>AI 资讯号自动发文：抓 AI 热点，按早中晚写工具介绍、教程或行业动态，发到公众号草稿箱和小红书<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-01-21 💤 · 中文 · 5 个 skill · MIT</sub>

- **[workbuddy-xhs-skills](https://github.com/jackbauerxu/workbuddy-xhs-skills)** · ★ 55<br>小红书从 0 起号的 10 个 skill：倒推变现定位、拆低粉爆款、选题库、去 AI 味和合规、封面和配图、排期复盘<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-01 · 中文 · 10 个 skill</sub>

- **[libra-skill](https://github.com/hekaixin66-sketch/libra-skill)** · ★ 43<br>Libra 小红书运营：逆向拆用户需求、同屏竞争下的封面和标题、生成笔记，发布前内容自检、发布后复盘<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-06 · 中文</sub>

- **[xhs-ai-workflow](https://github.com/554022647henry-boop/xhs-ai-workflow)** · ★ 38<br>小红书运营的提示词文件：主控提示词加 7 个分工 Agent（调研、选题、起草、审稿、发布准备等），你只定题和改稿<br><sub>平台：小红书</sub><br><sub>更新于 2026-05-13 💤 · 📝 提示词 · 中文</sub><br><sub>💡 自动发布要另装小红书 MCP、登录账号；只写稿可以不装</sub>

- **[MediaManager](https://github.com/LDJ-creat/MediaManager)** · ★ 33<br>自媒体全流程：抓 RSS 热点选题，写长文和小红书笔记、配图，一稿发到公众号、CSDN、掘金和小红书，再拉各平台数据复盘，复盘结论写回你的创作规范<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-06-25 · 中文 · 11 个 skill</sub><br><sub>💡 公众号、CSDN、掘金只存草稿；小红书是直接发出</sub>

- **[wechat-article-pipeline-skill](https://github.com/jhwreal/wechat-article-pipeline-skill)** · ★ 25<br>公众号长文流水线：写稿或整理口述、配图计划和生成、HTML 工作台排版，一篇终稿同步到公众号、头条和小红书草稿<br><sub>平台：小红书 · 公众号 · 头条</sub><br><sub>更新于 2026-11-07 · 中文 · MIT</sub><br><sub>💡 公众号草稿走官方 API；头条和小红书草稿要 macOS 上已登录的 Chrome</sub>

- **[doubaoya-community](https://github.com/zizhanovo/doubaoya-community)** · ★ 14<br>都爆鸭的 13 个新媒体 skill：挖选题、追热点、写抖音小红书公众号脚本、三平台违禁词检测、写进公众号草稿箱<br><sub>平台：小红书 · 抖音 · 公众号</sub><br><sub>更新于 2026-10-14 · 中文 · 13 个 skill</sub><br><sub>💡 大部分 skill 要在 doubaoya.com 生成 API Key</sub>

- **[wechat-editroom](https://github.com/shiker1996/wechat-editroom)** · ★ 13<br>见字公众号编辑工作台：接信息源找热点、核事实、定选题、写稿审稿、排版、出封面和小红书图文，本地运行<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-11-22 · 中文 · 47 个 skill · MIT</sub><br><sub>💡 有 Windows 桌面版，其他系统从源码运行</sub>

- **[Content-Agent-Kit](https://github.com/XuHo-IT/Content-Agent-Kit)** · ★ 10<br>越南语的内容运营套件：找选题、写稿、做 9:16 视频、审稿、发布，还能跑 Facebook 广告，32 个 skill<br><sub>平台：YouTube · TikTok · Instagram · Facebook</sub><br><sub>更新于 2026-11-20 · 越南文 · 32 个 skill · MIT</sub>

- **[ai-video-marketing](https://github.com/matt-j-penny/ai-video-marketing)** · ★ 9<br>视频营销 skill 合集：查什么在火、按你的口吻写钩子和脚本、UGC 广告、剪原始素材、YouTube SEO、改编和发布<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-22 · 英文 · 7 个 skill · MIT</sub>

- **[self-media-content-base](https://github.com/caodoris471/self-media-content-base)** · ★ 9<br>自媒体素材库：收链接、采集对标博主视频、整理资讯，按人设改写成稿件，写进飞书并记录进度<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手</sub><br><sub>更新于 2026-11-04 · 中文 · 2 个 skill</sub><br><sub>💡 部署文档按 WorkBuddy + Windows + 飞书写</sub>

- **[my-claude-skills](https://github.com/vincentventalon/my-claude-skills)** · ★ 7<br>法语技能包：TikTok、Reels 真人口播短视频，审账号、找爆款、写稿、剪片、长视频切片和发布；另有一套 SEO<br><sub>平台：TikTok · Instagram</sub><br><sub>更新于 2026-11-18 · 法文 · 2 个 skill · MIT</sub>

- **[videopowers](https://github.com/vinit-agr/videopowers)** · ★ 6<br>一人 YouTube 工作室的流水线：选题、调研、写稿、粗剪、Remotion 动效和标题封面包装，每步一个 skill<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-18 · 英文 · 14 个 skill · MIT</sub>

- **[Marky](https://github.com/Marky-Team/marky-skills)** · ★ 5<br>Marky 社媒 skill：按品牌风格做帖子、图片、轮播和视频，注册 Marky 后可直接发布并按效果优化<br><sub>平台：YouTube · Instagram · LinkedIn · Facebook</sub><br><sub>更新于 2026-11-11 · 英文 · 16 个 skill · Apache-2.0</sub><br><sub>💡 做内容不用注册；直接发布和优化要 Marky 账号</sub>

- **[estudio-de-conteudo-ia](https://github.com/fermaziero/estudio-de-conteudo-ia)** · ★ 4<br>葡萄牙语的 Instagram 运营套件：访谈定品牌，策划、写稿、做图、发布和看数据，每步等你确认<br><sub>平台：Instagram</sub><br><sub>更新于 2026-11-01 · 葡萄牙文 · 8 个 skill · MIT</sub>

- **[everyone-content](https://github.com/gallagherjas/everyone-content)** · ★ 4<br>多账号内容工作台：从抖音指数采集话题和达人数据，按七部分账号画像评估选题，学你的稿子按你的文风写<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-17 · 中文 · 5 个 skill · AGPL-3.0</sub>

- **[linkedin-agent-italia](https://github.com/JacopoMarini/linkedin-agent-italia)** · ★ 4<br>意大利语的 LinkedIn 运营：13 个 skill，写帖、写评论和回复、给主页打分重写、排周计划，带意大利语去 AI 味<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-11-19 · 意大利文 · 13 个 skill · MIT</sub>

- **[Reelfold 千剪](https://github.com/zyziyun/reelfold)** · ★ 4<br>千剪 Reelfold：从笔记或选题出稿，把素材批量剪成多平台、中英双语成片再发布，Mac 应用加 skill<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · X · YouTube · TikTok · Instagram · LinkedIn</sub><br><sub>更新于 2026-11-08 · 多语言 · MIT</sub>

- **[theme-page](https://github.com/sanskarprajapati/theme-page)** · ★ 4<br>运营 Instagram、TikTok 新闻主题号：搜本领域热门新闻按热度排好，你挑完做成带来源的品牌轮播图<br><sub>平台：TikTok · Instagram</sub><br><sub>更新于 2026-10-30 · 英文 · MIT</sub>

- **[workbuddy-media-desk](https://github.com/phs-bitqun/workbuddy-media-desk)** · ★ 4<br>自媒体工作台的 WorkBuddy 版：一句话出口播脚本、封面大字和分镜，排发布时间，把平台数据读成写作规则<br><sub>平台：通用</sub><br><sub>更新于 2026-11-15 · 中文 · MIT</sub><br><sub>💡 移植自 woniuniuniu/dsh-media-desk</sub>

- **[boqount](https://github.com/boqo-ai/boqount)** · ★ 3<br>让 agent 运营品牌的 Instagram、TikTok 和 YouTube：读项目、按你的风格从零做片，发前问你，发后复盘<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-18 · 英文 · 2 个 skill · MIT</sub>

- **[instagram-skill](https://github.com/social-media-skills/instagram-skill)** · ★ 3<br>Instagram 一条龙：给想法、链接或素材，定形式、写文案、做轮播图和 Reels，检查预览后排期，可管多账号<br><sub>平台：Instagram</sub><br><sub>更新于 2026-11-11 · 英文 · MIT</sub>

- **[taplio-linkedin-plugin](https://github.com/TaplioOfficial/taplio-linkedin-plugin)** · ★ 3<br>Taplio 官方的 LinkedIn 插件：26 个 skill，写帖、轮播图、排期、找评论机会和读数据<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-11-20 · 英文 · 26 个 skill · MIT</sub><br><sub>💡 要 Taplio 账号</sub>

- **[xhs-workflow-skill](https://github.com/anthonyhann/xhs-workflow-skill)** · ★ 3<br>小红书全链路调度：10 个子 skill 走完调研、写作、配图、发布和互动，上线前每步等你确认<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-04 · 中文 · MIT</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# baoyu-skills
npx skills add JimLiu/baoyu-skills
# wewrite
npx skills add imraywang/wewrite
# instagram-agent-skill
npx skills add Jakeschincariol/instagram-agent-skill
# youtube-agent-skill
npx skills add Jakeschincariol/youtube-agent-skill
# sergebulaev/linkedin-skills
npx skills add sergebulaev/linkedin-skills
# yichen-skills
npx skills add mcncarl/yichen-skills
# charlie947/social-media-skills
npx skills add charlie947/social-media-skills
# linkedin-agent-skill
npx skills add Jakeschincariol/linkedin-agent-skill
# xiaohongshu-ops-skill
npx skills add Xiangyu-CAS/xiaohongshu-ops-skill
# growth-lab
npx skills add tsingyuai/growth-lab
# creator-buddy
npx skills add SpaceZephyr/creator-buddy
# instagram-skills
npx skills add sergebulaev/instagram-skills
# claude-skill-social-post
npx skills add Hao0321/claude-skill-social-post
# claude-youtube
npx skills add AgriciDaniel/claude-youtube
# wechat-article-skills
npx skills add aiworkskills/wechat-article-skills
# self-media-content-workflow
npx skills add yanhua1010/self-media-content-workflow
# blacktwist/social-media-skills
npx skills add blacktwist/social-media-skills
# claude-content-skills
npx skills add Ootto-AI/claude-content-skills
# rayskills
npx skills add imraywang/rayskills
# social-media-skills/skills
npx skills add social-media-skills/skills
# wechat_article_skills
npx skills add BND-1/wechat_article_skills
# jiji262/wechat-publisher
npx skills add jiji262/wechat-publisher
# social-ai-team
npx skills add stevenflanagan1/social-ai-team
# content-pipeline
npx skills add OrangeViolin/content-pipeline
# wenzi-xiaohongshu-workflow
npx skills add wenziai/wenzi-xiaohongshu-workflow
# x-skills
npx skills add sergebulaev/x-skills
# facebook-skills
npx skills add sergebulaev/facebook-skills
# 843645440/wechat-skill
npx skills add 843645440/wechat-skill
# tiktok-skills
npx skills add sergebulaev/tiktok-skills
# WorkBuddy
npx skills add adsorgcn/WorkBuddy
# wemp-operator
npx skills add IanShaw027/wemp-operator
# sergebulaev/youtube-skills
npx skills add sergebulaev/youtube-skills
# threads-skills
npx skills add sergebulaev/threads-skills
# Fully-automatic-article-generation-skill
npx skills add solar-luna/Fully-automatic-article-generation-skill
# workbuddy-xhs-skills
npx skills add jackbauerxu/workbuddy-xhs-skills
# libra-skill
npx skills add hekaixin66-sketch/libra-skill
# MediaManager
npx skills add LDJ-creat/MediaManager
# wechat-article-pipeline-skill
npx skills add jhwreal/wechat-article-pipeline-skill
# doubaoya-community
npx skills add zizhanovo/doubaoya-community
# wechat-editroom
npx skills add shiker1996/wechat-editroom
# Content-Agent-Kit
npx skills add XuHo-IT/Content-Agent-Kit
# ai-video-marketing
npx skills add matt-j-penny/ai-video-marketing
# self-media-content-base
npx skills add caodoris471/self-media-content-base
# my-claude-skills
npx skills add vincentventalon/my-claude-skills
# videopowers
npx skills add vinit-agr/videopowers
# Marky
npx skills add Marky-Team/marky-skills
# estudio-de-conteudo-ia
npx skills add fermaziero/estudio-de-conteudo-ia
# everyone-content
npx skills add gallagherjas/everyone-content
# linkedin-agent-italia
npx skills add JacopoMarini/linkedin-agent-italia
# Reelfold 千剪
npx skills add zyziyun/reelfold
# theme-page
npx skills add sanskarprajapati/theme-page
# workbuddy-media-desk
npx skills add phs-bitqun/workbuddy-media-desk
# boqount
npx skills add boqo-ai/boqount
# instagram-skill
npx skills add social-media-skills/instagram-skill
# taplio-linkedin-plugin
npx skills add TaplioOfficial/taplio-linkedin-plugin
# xhs-workflow-skill
npx skills add anthonyhann/xhs-workflow-skill
```

</details>

<a id="group-writing"></a>
### 文案和内容创作

写笔记、推文、标题、口播稿和长文，改写成各平台的口吻，去 AI 味，发布前查违禁词和限流风险。

- 🌟 **[humanizer](https://github.com/blader/humanizer)** · ★ 72.3k<br>英文去 AI 腔：按维基百科编辑识别 AI 文本的那份特征清单逐条改写，不改原意<br><sub>平台：通用</sub><br><sub>更新于 2026-11-19 · 英文 · MIT</sub>

- 🌟 **[Humanizer-zh](https://github.com/op7418/Humanizer-zh)** · ★ 23.6k<br>中文去 AI 味：删改空话、重复和模板化表达，保留事实、确定程度和作者声音，没问题的句子不改<br><sub>平台：通用</sub><br><sub>更新于 2026-09-23 · 中文 · MIT</sub>

- **[khazix-skills](https://github.com/KKKKhazix/khazix-skills)** · ★ 22.5k<br>卡兹克的 skill 合集，写作用 khazix-writer：照他的口吻写公众号长文，默认 4000–8000 字，写完自检；另有 aihot 查 AI 热点<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-18 · 中文 · 6 个 skill · MIT</sub>

- **[lieflat-less-ai-tone](https://github.com/larashero3-dotcom/lieflat-less-ai-tone)** · ★ 8.6k<br>去 AI 味：先按 520 万字人机对照实测出的指标出检测报告，附原文例句和改法，你同意后才做最小改写并复测<br><sub>平台：通用</sub><br><sub>更新于 2026-11-11 · 中文</sub><br><sub>💡 CC BY-NC 4.0：不能商用</sub>

- **[human-writing](https://github.com/KKKKhazix/human-writing)** · ★ 4.7k<br>活人感写作：知乎回答、公众号文章、评测、口播稿等中文写作，先查够材料再写，读起来像一个具体的人在说话<br><sub>平台：公众号 · 知乎</sub><br><sub>更新于 2026-11-15 · 中文 · MIT</sub>

- **[writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill)** · ★ 3.3k<br>写作蒸馏器：从至少 20 篇文章里蒸馏一个账号或作者的写作 DNA（语言、结构、选题、素材），之后按这套 DNA 写<br><sub>平台：小红书 · 公众号 · 微博 · Newsletter</sub><br><sub>更新于 2026-11-11 · 中文 · 2 个 skill</sub>

- **[shuorenhua](https://github.com/MrGeDiao/shuorenhua)** · ★ 2.7k<br>说人话：中文去 AI 味改写，删套话和重复铺垫，数字、条件、承诺和作者口气原样保留，改完能直接发<br><sub>平台：通用</sub><br><sub>更新于 2026-11-22 · 中文 · MIT</sub>

- **[ai-copywriter](https://github.com/mikiarlo3/ai-copywriter)** · ★ 1.2k<br>文案和去 AI 腔一起做：标题、短描述、微文案、邮件主题，按 LinkedIn 的短段落节奏写帖子<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-08-01 · 英文 · MIT</sub>

- **[Viral_Writer_Skill](https://github.com/nashsu/Viral_Writer_Skill)** · ★ 845<br>给一个主题，按 11 个内容洞见维度写成整篇文章，附 5 个备选标题和每张配图的提示词，公众号、小红书、抖音三种写法<br><sub>平台：小红书 · 抖音 · 公众号</sub><br><sub>更新于 2026-03-24 💤 · 中文</sub>

- **[yuwen-publish-precheck](https://github.com/yuwen-cool/yuwen-publish-precheck)** · ★ 820<br>发布前审：口播稿、图文、字幕、封面字能不能发抖音/小红书/视频号，指出哪句踩线、依据哪条官方规则，给改法<br><sub>平台：小红书 · 抖音 · 视频号</sub><br><sub>更新于 2026-10-08 · 中文 · MIT</sub>

- **[qu-ai-wei](https://github.com/LifelongLazyLearner/qu-ai-wei)** · ★ 771<br>简体中文去 AI 味：清理套话、翻译腔和机械排比，保留事实、正式程度和原文声口<br><sub>平台：通用</sub><br><sub>更新于 2026-11-21 · 中文 · MIT</sub>

- **[anti-ai-slop-writing](https://github.com/jalaalrd/anti-ai-slop-writing)** · ★ 622<br>英文去 AI 腔：推文、邮件、文章、简介、配图文案都按可检测的 AI 写作特征逐条避开<br><sub>平台：通用</sub><br><sub>更新于 2026-04-18 💤 · 英文</sub>

- **[taishang-laojun](https://github.com/liuhaisi2026212-maker/taishang-laojun)** · ★ 606<br>抖音/小红书口播短视频创作：先问清你是谁、想吸引谁，再拆对标爆款、选题、系列策划，写成能直接念的口播稿，还管标题、复盘和去 AI 味<br><sub>平台：小红书 · 抖音</sub><br><sub>更新于 2026-11-08 · 中文 · 8 个 skill</sub><br><sub>💡 CC BY-NC 4.0：不能商用</sub>

- **[writing-agent](https://github.com/dongbeixiaohuo/writing-agent)** · ★ 463<br>多 agent 写稿：写作导演、主笔、读者审校、去 AI 味专家一起从选题写到成稿，能从公众号样文建风格档案；另有 Windows 客户端<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-22 · 中文 · 3 个 skill · MIT</sub>

- **[xiaoma-durex-copywriter](https://github.com/crawfordxx/xiaoma-durex-copywriter)** · ★ 347<br>杜蕾斯式借势文案和海报：双层语义和 8 个文案公式，拆自 260 张原始海报，适合热点、节日、产品卖点<br><sub>平台：通用</sub><br><sub>更新于 2026-08-08 · 中文</sub>

- **[humanizer-skill](https://github.com/Aboudjem/humanizer-skill)** · ★ 326<br>英文去 AI 腔并打分：识别 55 种 AI 写作特征，按 5 种口吻改写，给 0-100 的 AI 痕迹分，本地运行<br><sub>平台：通用</sub><br><sub>更新于 2026-11-17 · 英文 · MIT</sub>

- **[content-skills](https://github.com/vyralcontent/content-skills)** · ★ 278<br>短视频钩子、脚本和轮播：从 20 万条爆款视频总结写法，覆盖 TikTok、Reels 和 Shorts，也写配文和行动号召<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-06-22 · 英文 · 7 个 skill · MIT</sub>

- **[gainubi/wechat-skills](https://github.com/gainubi/wechat-skills)** · ★ 174<br>小盖的公众号写作 skill：从 3–10 篇文章梳理文风 DNA，按 DNA 写初稿，给文章做扁平风解释配图<br><sub>平台：公众号</sub><br><sub>更新于 2026-05-21 💤 · 中文 · 7 个 skill</sub>

- **[traffic-compass](https://github.com/code-wahaha/traffic-compass)** · ★ 102<br>抖音发布前自查：查广告法违禁词、引流词、AI 标注和资质红线，给最小改法，再按粉丝量和赛道估播放区间<br><sub>平台：抖音</sub><br><sub>更新于 2026-07-07 · 中文 · MIT</sub>

- **[create-viral-content](https://github.com/aaaronmiller/create-viral-content)** · ★ 91<br>爆款社媒内容：钩子、标题、缩略图、各平台规则和去 AI 痕迹，带对抗式改稿，按 2026 年平台变化更新<br><sub>平台：X · YouTube · TikTok · LinkedIn · Reddit</sub><br><sub>更新于 2026-11-22 · 英文</sub>

- **[media-publish-check](https://github.com/XshuiAi/media-publish-check)** · ★ 73<br>发布前审核：抖音、小红书、视频号、快手的视频和图文能不能直接发、问题在哪、怎么改，并按平台改写<br><sub>平台：小红书 · 抖音 · 视频号 · 快手</sub><br><sub>更新于 2026-07-22 · 中文 · MIT</sub>

- **[content-risk-detector](https://github.com/liuxingqitd/content-risk-detector)** · ★ 58<br>短视频逐字稿合规检测：按抖音、小红书、视频号社区规范找风险点，出分级报告和修改建议<br><sub>平台：小红书 · 抖音 · 视频号</sub><br><sub>更新于 2026-09-14 · 中文 · MIT</sub>

- **[jianghushuo-oral-skill](https://github.com/read2017/jianghushuo-oral-skill)** · ★ 33<br>姜胡说口播 skill：从 433 条口播逐字稿和《价值心法》蒸馏，按他的方法找选题、写口播稿、改稿、诊断账号<br><sub>平台：小红书 · 抖音</sub><br><sub>更新于 2026-11-15 · 中文 · MIT</sub>

- **[guage-write-flow](https://github.com/guage1029/guage-write-flow)** · ★ 26<br>中文技术文章和公众号长文写作：调研核验、选题、两阶段创作、多轮审校，也能审校已有文章、降 AI 味<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-17 · 中文 · MIT</sub>

- **[Master-humanizer-skill](https://github.com/masterball-w/Master-humanizer-skill)** · ★ 17<br>降 AI 味·反向法则：主要写公众号文章，18 条带检测问题的规则，先写后逐句检查，按 7 种文体加规则<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-13 · 中文</sub>

- **[Andy-Writing-Skill](https://github.com/AIPMAndy/Andy-Writing-Skill)** · ★ 15<br>Andy 写作 skill：一个入口按任务和平台路由到 19 个写作场景，Threads、X 长文、公众号、小红书、口播和商业文案<br><sub>平台：小红书 · 公众号 · X · Threads</sub><br><sub>更新于 2026-11-14 · 中文 · 4 个 skill · MIT</sub>

- **[chinese-de-ai-writing](https://github.com/tangwenwen-md/chinese-de-ai-writing)** · ★ 8<br>中文去 AI 味：只执行在人写和 AI 语料对比里站得住的特征，被数据否定的规则列为不要做，不改事实和论断强度<br><sub>平台：通用</sub><br><sub>更新于 2026-11-04 · 中文 · MIT</sub>

- **[wechat-explosive-article-skill](https://github.com/AIPMAndy/wechat-explosive-article-skill)** · ★ 8<br>公众号爆款文章方法论：多篇观点融合、注入个人经历、七成讲怎么办，再用五个维度对抗式审稿，七步写完<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-12 · 中文 · MIT</sub>

- **[social-content-engine](https://github.com/caelynmoss/social-content-engine)** · ★ 6<br>个人写作搭档：账号定位、提炼你的口吻、扩展想法、核查证据，写文章和 X 帖子，另有加密推特热点雷达<br><sub>平台：X</sub><br><sub>更新于 2026-11-10 · 多语言 · MIT</sub>

- **[sph-work-skills](https://github.com/skystmm/sph-work-skills)** · ★ 6<br>图书带货短视频文案：深度二创口播稿、合规判定和改写、注音标注、字幕排版，给 WorkBuddy 用<br><sub>平台：通用</sub><br><sub>更新于 2026-11-18 · 中文 · 5 个 skill</sub>

- **[Content-Critic](https://github.com/Anghelo12344567/Content-Critic)** · ★ 5<br>发之前给脚本、开头、帖子和 Reels 打分：按平台看钩子、留存、价值和行动号召，直接给改好的版本<br><sub>平台：X · TikTok · Instagram · LinkedIn</sub><br><sub>更新于 2026-11-10 · 西班牙文 · MIT</sub>

- **[xiaohongshu-copywriter-skill](https://github.com/beatra-ai/xiaohongshu-copywriter-skill)** · ★ 4<br>小红书文案：把商品、体验、选题或受众信息写成标题、正文、首图文案、话题标签和评论区互动引导<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-20 · 中文 · MIT-0</sub><br><sub>💡 要 Beatra 账号，生成扣积分</sub>

- **[copyflow](https://github.com/AIPMAndy/copyflow)** · ★ 3<br>CopyFlow：一个主题写出 10 种风格的文案，配 AI 图，整理成可发布的素材包，给内容运营团队用<br><sub>平台：小红书 · 公众号 · X</sub><br><sub>更新于 2026-11-22 · 中文</sub>

- **[xiaohongshu-doctor](https://github.com/softbread/xiaohongshu-doctor)** · ★ 3<br>小红书笔记发布前体检：内容质量、关键词、标题吸引力、敏感内容风险、商业化程度和互动潜力<br><sub>平台：小红书</sub><br><sub>更新于 2026-01-15 💤 · 中文</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# humanizer
npx skills add blader/humanizer
# Humanizer-zh
npx skills add op7418/Humanizer-zh
# khazix-skills
npx skills add KKKKhazix/khazix-skills
# lieflat-less-ai-tone
npx skills add larashero3-dotcom/lieflat-less-ai-tone
# human-writing
npx skills add KKKKhazix/human-writing
# writing-dna-skill
npx skills add larashero3-dotcom/writing-dna-skill
# shuorenhua
npx skills add MrGeDiao/shuorenhua
# ai-copywriter
npx skills add mikiarlo3/ai-copywriter
# Viral_Writer_Skill
npx skills add nashsu/Viral_Writer_Skill
# yuwen-publish-precheck
npx skills add yuwen-cool/yuwen-publish-precheck
# qu-ai-wei
npx skills add LifelongLazyLearner/qu-ai-wei
# anti-ai-slop-writing
npx skills add jalaalrd/anti-ai-slop-writing
# taishang-laojun
npx skills add liuhaisi2026212-maker/taishang-laojun
# writing-agent
npx skills add dongbeixiaohuo/writing-agent
# xiaoma-durex-copywriter
npx skills add crawfordxx/xiaoma-durex-copywriter
# humanizer-skill
npx skills add Aboudjem/humanizer-skill
# content-skills
npx skills add vyralcontent/content-skills
# gainubi/wechat-skills
npx skills add gainubi/wechat-skills
# traffic-compass
npx skills add code-wahaha/traffic-compass
# create-viral-content
npx skills add aaaronmiller/create-viral-content
# media-publish-check
npx skills add XshuiAi/media-publish-check
# content-risk-detector
npx skills add liuxingqitd/content-risk-detector
# jianghushuo-oral-skill
npx skills add read2017/jianghushuo-oral-skill
# guage-write-flow
npx skills add guage1029/guage-write-flow
# Master-humanizer-skill
npx skills add masterball-w/Master-humanizer-skill
# Andy-Writing-Skill
npx skills add AIPMAndy/Andy-Writing-Skill
# chinese-de-ai-writing
npx skills add tangwenwen-md/chinese-de-ai-writing
# wechat-explosive-article-skill
npx skills add AIPMAndy/wechat-explosive-article-skill
# social-content-engine
npx skills add caelynmoss/social-content-engine
# sph-work-skills
npx skills add skystmm/sph-work-skills
# Content-Critic
npx skills add Anghelo12344567/Content-Critic
# xiaohongshu-copywriter-skill
npx skills add beatra-ai/xiaohongshu-copywriter-skill
# copyflow
npx skills add AIPMAndy/copyflow
# xiaohongshu-doctor
npx skills add softbread/xiaohongshu-doctor
```

</details>

<a id="group-visual"></a>
### 排版、封面配图和短视频

公众号排版、做封面和信息卡片、配图，剪短视频、加字幕、写分镜。

- 🌟 **[guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill)** · ★ 8.2k<br>歸藏的图文卡片：小红书组图、Live Photo 动态卡、公众号 21:9+1:1 封面对，杂志风和瑞士风两套视觉、28 种版式<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-10-30 · 中文 · AGPL-3.0</sub>

- 🌟 **[gzh-design-skill](https://github.com/isjiamu/gzh-design-skill)** · ★ 4.4k<br>公众号排版：Markdown 排成能直接粘进公众号编辑器的 HTML，6 套主题加主题生成器，样式全内联不掉格式<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-21 · 中文</sub>

- **[guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill)** · ★ 30.3k<br>歸藏的网页 PPT：把文章做成单文件 HTML 翻页演示，杂志风和瑞士风两套，带演讲者模式，同一套视觉还能出公众号、小红书、视频号封面<br><sub>平台：小红书 · 公众号 · 视频号</sub><br><sub>更新于 2026-10-30 · 中文 · AGPL-3.0</sub><br><sub>💡 配图要在 Codex 里用 GPT-Image 生成，不用也能出纯排版的 PPT</sub>

- **[openmotion](https://github.com/nexu-io/openmotion)** · ★ 15.3k<br>OpenMotion（原 HTML Anything）：给一条参考视频或社媒视频链接，agent 拆镜头、用 HTML 复刻成你自己品牌的片子，也能剪口播<br><sub>平台：小红书 · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-23 · 🧩 应用 · 多语言 · 415 个 skill · Apache-2.0</sub><br><sub>💡 11 月起仓库换成了 OpenMotion，原来的 HTML 编辑器只留在 legacy 分支；补镜头、配乐、配音要接自己的模型 API key</sub>

- **[ian-xiaohei-illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations)** · ★ 13.3k<br>Ian 的「小黑」手绘正文配图：读文章挑出判断、流程或隐喻，画成 4–8 张 16:9 白底怪诞配图<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-27 · 中文 · MIT</sub><br><sub>💡 按 Codex 写的，出图调 Codex 自带的 image_gen；在别的 agent 里用要自己接生图工具</sub>

- **[handraw-style](https://github.com/yang0/handraw-style)** · ★ 8k<br>选编号出图提示词：367 种手绘和写实画风、170 种排版图型、36 套配色，输入主题就出中英双语提示词，做小红书封面、公众号题图和配图、知识长图、条漫<br><sub>平台：小红书 · 公众号 · B 站 · X · YouTube</sub><br><sub>更新于 2026-11-22 · 中文 · 23 个 skill</sub><br><sub>💡 出图后会提示把作品分享到作者的网站，点了发布按钮才会公开</sub>

- **[md2wechat-skill](https://github.com/geekjourneyx/md2wechat-skill)** · ★ 3.8k<br>公众号创作与发布 CLI：Markdown 排版、AI 配图和封面、预览校验、推送草稿箱，也能让浏览器 agent 存知乎、头条草稿<br><sub>平台：公众号 · 知乎 · 头条</sub><br><sub>更新于 2026-10-14 · 中文</sub><br><sub>💡 部分功能要向作者申请 API Key</sub>

- **[herk-edit-kit](https://github.com/nateherkai/herk-edit-kit)** · ★ 3.1k<br>Nate Herk 的口播剪辑包：按字幕剪掉停顿和口误、规划叙事、406 张动效卡片和 HyperFrames 模板，做 Reels 和 Shorts<br><sub>平台：YouTube · Instagram</sub><br><sub>更新于 2026-10-14 · 英文 · 15 个 skill</sub>

- **[native-subtitle-quote-image](https://github.com/chengyi-ai/native-subtitle-quote-image)** · ★ 2.9k<br>把视频做成带字幕的社交长图：本地视频或 YouTube 链接进来，找句子、精确取帧、拼图、逐张质检；保留画面里原有的字幕，或画上你审过的台词并标明是后期加的<br><sub>平台：通用</sub><br><sub>更新于 2026-11-06 · 多语言 · MIT</sub>

- **[youtube-shorts-pipeline](https://github.com/rushindrasinha/youtube-shorts-pipeline)** · ★ 2.4k<br>竖屏短视频流水线：一个选题自动调研、写脚本、出画面、配音、加字幕并上传，每条约 0.11 美元<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-06-09 · 英文 · MIT</sub>

- **[Youtube-clipper-skill](https://github.com/op7418/Youtube-clipper-skill)** · ★ 2.4k<br>YouTube 剪辑：下载视频、按语义分章节、剪片段、字幕翻译成双语并烧进视频<br><sub>平台：YouTube</sub><br><sub>更新于 2026-01-22 💤 · 中文 · MIT</sub>

- **[gif-factory](https://github.com/WoYun520/gif-factory)** · ★ 2.1k<br>GIF 工厂：给一张图或一段文字，做表情包、光栅变画卡、动态海报、动态签名、40 种字形的电影片头、品牌短片和动态绘本<br><sub>平台：通用</sub><br><sub>更新于 2026-11-20 · 中文 · 6 个 skill · MIT</sub><br><sub>💡 要在能生成图片的 Codex 里用；导出要 Python 3 和 Pillow，预览视频要 FFmpeg</sub>

- **[digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo)** · ★ 2.1k<br>AI 数字人口播：一张照片加一句话出成片，写稿、分段对口型生成、统一音色、加字幕，5 种剪辑风格和 48 个包装组件，生成前先报价等你确认<br><sub>平台：通用</sub><br><sub>更新于 2026-10-31 · 多语言 · 2 个 skill · MIT</sub><br><sub>💡 视频经 Renoise MCP 生成，按积分付费</sub>

- **[rnskill](https://github.com/Pluviobyte/rnskill)** · ★ 1.8k<br>雪踏乌云的 skill 合集：选题、脚本改写、AI 配音、数字人、剪口播、字幕、封面和图文，另有编码类 skill<br><sub>平台：小红书 · 抖音 · 公众号</sub><br><sub>更新于 2026-09-21 · 中文 · 62 个 skill</sub>

- **[video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker)** · ★ 1.7k<br>选题变成 4K 解说视频：调研、写稿、本地免费 TTS、Remotion 合成，适配 B 站、YouTube、小红书、抖音、视频号<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · YouTube</sub><br><sub>更新于 2026-10-01 · 多语言 · 3 个 skill · MIT</sub>

- **[xhs-visual-director-skill](https://github.com/ziguishian/xhs-visual-director-skill)** · ★ 1.6k<br>小红书视觉导演：先问 10 个问题，规划多页图文和每页视觉，出 1 张样图确认后生成整套，附发布文案和自检清单<br><sub>平台：小红书</sub><br><sub>更新于 2026-07-03 · 中文 · MIT</sub>

- **[vibe-knowledge-film](https://github.com/HeyChengC/vibe-knowledge-film)** · ★ 1.5k<br>抖音「知识大赏」类知识短片：两种热门画风，写字幕稿、排分镜表、配音效，先出 30 秒样片再出成片<br><sub>平台：抖音</sub><br><sub>更新于 2026-10-13 · 中文</sub>

- **[Punk-Posters](https://github.com/adrianpunk/Punk-Posters)** · ★ 1.5k<br>Punk 风格视觉：文章封面（小红书、公众号）、头像、人物 IP 视频封面，共用一个风格库<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-11-04 · 中文 · 3 个 skill</sub><br><sub>💡 个人非商用免费；企业、团队或商业用途要先买授权</sub>

- **[qiaomu-mondo-poster-design](https://github.com/joeseesun/qiaomu-mondo-poster-design)** · ★ 1.4k<br>乔木的 Mondo 风海报：一句话按 33 位设计师风格生成海报、书封、专辑封面，支持公众号封面 21:9、小红书配图 3:4<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-03-19 💤 · 中文 · MIT</sub>

- **[clipforge](https://github.com/xixihhhh/clipforge)** · ★ 1.4k<br>带货短视频：上传一张商品图，提炼卖点、写种草脚本、配画面配音字幕，出抖音小店、快手、小红书、TikTok Shop 视频<br><sub>平台：小红书 · 抖音 · 快手 · TikTok</sub><br><sub>更新于 2026-11-20 · 中文 · 2 个 skill · AGPL-3.0</sub><br><sub>💡 skill 调用本地部署的 ClipForge 应用</sub>

- **[story-studio](https://github.com/konlu/story-studio)** · ★ 1.2k<br>历史和人物故事短视频一条龙：选题、开头钩子、口播稿、豆包配音、本地字幕对齐、三种画风分镜配图，导出能再改的剪映草稿；内置 370 多篇高赞文案对标<br><sub>平台：抖音 · 视频号</sub><br><sub>更新于 2026-11-13 · 中文</sub>

- **[video-spec-builder](https://github.com/feicaiclub/video-spec-builder)** · ★ 1.1k<br>视频导演式追问：把「想做个视频」问成精确到秒的分镜脚本 video-spec.md，交给 HyperFrames 渲染<br><sub>平台：通用</sub><br><sub>更新于 2026-05-18 💤 · 多语言 · MIT</sub>

- **[gbro-cover-design](https://github.com/pyang5166/gbro-cover-design)** · ★ 1k<br>公众号/小红书封面提示词：读完文章问三轮，按 10 种构图出 3:4 真人出镜封面提示词，基于 oh-my-cover-design 改进<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-07-15 · 中文</sub>

- **[wallstreet-explainer](https://github.com/HeyChengC/wallstreet-explainer)** · ★ 837<br>华尔街风格财经和科技解读短片：给选题，自己写文案、找片、截新闻、配音、渲染，有口播就围着人做<br><sub>平台：通用</sub><br><sub>更新于 2026-11-20 · 中文</sub>

- **[motion-graphics-skills](https://github.com/charlie947/motion-graphics-skills)** · ★ 775<br>用代码做动效：发布会视频、动态图表、数字滚动，适合发 LinkedIn 和 Newsletter，不用 After Effects<br><sub>平台：LinkedIn · Newsletter</sub><br><sub>更新于 2026-10-11 · 英文 · 15 个 skill · MIT</sub>

- **[gimi-illustration-skill](https://github.com/GiMi-Xiaomi/gimi-illustration-skill)** · ★ 737<br>中文文章和口播配图：把判断、流程、对比画成一眼能懂的图，三种画风，可换成自己的 IP 形象<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-03 · 中文 · MIT</sub>

- **[xiaohu-wechat-format](https://github.com/xiaohuailabs/xiaohu-wechat-format)** · ★ 711<br>公众号一键排版加发布：Markdown 转微信兼容 HTML，85 套主题和可视化画廊挑选，可选生成封面，推送草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-06-12 · 中文 · 2 个 skill</sub>

- **[clipify](https://github.com/louisedesadeleer/clipify)** · ★ 695<br>长视频切短片：转写后找笑点、反转和高能片段，剪成 9:16 并跟踪人脸，烧录 Opus 风格字幕<br><sub>平台：通用</sub><br><sub>更新于 2026-08-24 · 英文 · MIT</sub>

- **[chatgpt-video-editing-skills](https://github.com/Jaycheng1103/chatgpt-video-editing-skills)** · ★ 635<br>用 ChatGPT/Codex 剪竖屏短视频：一个 skill 装好剪辑环境，一个按 8 步把你的素材剪成 Reels、Shorts、TikTok<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-07-26 · 多语言 · 2 个 skill · MIT</sub>

- **[Document-illustrator-skill](https://github.com/op7418/Document-illustrator-skill)** · ★ 615<br>从文档归纳要点生成多张配图，歸藏调过的三种风格，16:9 和 3:4 两种比例，适合发小红书和推特<br><sub>平台：小红书 · X</sub><br><sub>更新于 2026-01-21 💤 · 中文 · MIT</sub>

- **[Clips Kitty](https://github.com/ColinGPT9/clips-studio)** · ★ 612<br>长视频和直播切短视频：从 YouTube、Twitch、Kick 链接或本地视频里找值得发的片段，裁成 9:16 跟住说话人，烧字幕、写标题<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-22 · 英文 · AGPL-3.0</sub><br><sub>💡 skill 通过 MCP 调用同一台电脑上的开源 Clips Kitty 应用，用前要先打开应用；全程本机运行</sub>

- **[whiteboard-teacher-video](https://github.com/liangdabiao/whiteboard-teacher-video)** · ★ 576<br>图文讲解视频：把讲解稿做成手绘会动的知识短片，图形逐笔画、文字逐字写，五套风格，本地渲染不调生图接口<br><sub>平台：抖音 · B 站</sub><br><sub>更新于 2026-11-08 · 中文</sub>

- **[smart-illustrator](https://github.com/axtonliu/smart-illustrator)** · ★ 574<br>文章配图：自动找该配图的位置生成插图，也能批量出 PPT 信息图和 YouTube 缩略图，Gemini、Excalidraw、Mermaid 三种引擎<br><sub>平台：YouTube</sub><br><sub>更新于 2026-06-26 · 多语言 · MIT</sub>

- **[clipcat-skill](https://github.com/Clipcat-ai/clipcat-skill)** · ★ 545<br>TikTok Shop 带货视频：找爆款视频、研究商品店铺达人和直播间、拆为什么能卖，生成可拍的提示词<br><sub>平台：TikTok</sub><br><sub>更新于 2026-10-24 · 英文</sub><br><sub>💡 要 Clipcat 账号</sub>

- **[article2media](https://github.com/threerocks/article2media)** · ★ 535<br>一篇文章或一条视频做成小红书图文、长图、公众号排版和配音口播短视频，21 套主题，自动验收<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · X · YouTube</sub><br><sub>更新于 2026-11-11 · 中文 · 11 个 skill · MIT</sub>

- **[DaVinci-AutoEdit-Agent](https://github.com/liuluhaixiu/DaVinci-AutoEdit-Agent)** · ★ 526<br>达芬奇自动剪辑：分析素材、写文案、配音、搭剪辑蓝图并在 DaVinci Resolve 时间线成片，每步等你确认<br><sub>平台：通用</sub><br><sub>更新于 2026-06-12 · 多语言 · 3 个 skill · MIT</sub><br><sub>💡 要 DaVinci Resolve Studio</sub>

- **[hotclip](https://github.com/xixihhhh/hotclip)** · ★ 505<br>长视频和直播回放切成竖屏爆款片段：AI 找高光并说明理由、横转竖、自动字幕、去气口，本地运行不上传<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手</sub><br><sub>更新于 2026-11-20 · 中文 · AGPL-3.0</sub>

- **[claude-design-card](https://github.com/geekjourneyx/claude-design-card)** · ★ 477<br>把文本或网页做成可发布卡片：平台封面、社交分享卡、长文排版 14 种格式，统一 Claude 设计风格<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · YouTube</sub><br><sub>更新于 2026-05-27 · 中文</sub>

- **[cy-carousel-skill](https://github.com/chengyi-ai/cy-carousel-skill)** · ★ 445<br>AI 科技类小红书图文轮播：给一个选题，查证一手出处、只用开放授权素材，排成封面加 10 页，附标题、正文、置顶评论和来源清单，出图前自动检查<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-13 · 中文</sub>

- **[atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover)** · ★ 441<br>阿囤囤风小红书封面提示词：真人出镜、超大浅黄白描边标题、勾选清单和贴纸，适合 AI 工具、测评和教程类内容<br><sub>平台：小红书</sub><br><sub>更新于 2026-05-30 · 中文</sub>

- **[ttfake92-lab/skills](https://github.com/ttfake92-lab/skills)** · ★ 339<br>鱼亦乐的技能合集：拆解对标账号、竖屏分屏口播、Remotion 视频、视频提示词和封面，另有几个个人用的技能<br><sub>平台：小红书 · 抖音 · B 站 · YouTube</sub><br><sub>更新于 2026-10-30 · 中文 · 11 个 skill</sub>

- **[ian-xhs-carousel](https://github.com/helloianneo/ian-xhs-carousel)** · ★ 316<br>把文章、案例或笔记排成 3:4 小红书图文：先出分镜表等你确认，再按 20 个母版出图，浅色深色两套，附总览图和可改的 HTML<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-21 · 中文 · MIT</sub>

- **[xiaohu-ip-studio](https://github.com/xiaohuailabs/xiaohu-ip-studio)** · ★ 309<br>小互的中文深度文配图：挑认知锚点、现编隐喻、反 PPT 自检，自带 31 个原创 IP 角色出演<br><sub>平台：通用</sub><br><sub>更新于 2026-06-26 · 中文 · MIT</sub>

- **[oil-cover](https://github.com/oil-oil/oil-cover)** · ★ 308<br>从视频画面做小红书和 B 站封面：本地选帧打分，按真实屏幕画面加标题出三种画幅，适合 AI 工具实操视频<br><sub>平台：小红书 · B 站</sub><br><sub>更新于 2026-11-16 · 中文</sub>

- **[oh-my-cover-design](https://github.com/hongfamonvAI/oh-my-cover-design)** · ★ 293<br>小红书/公众号封面提示词：问完构图、人脸、表情、产品图、配色和字体，输出能直接跑图的提示词，10 种构图<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-05-16 💤 · 中文</sub>

- **[panda-video-generator](https://github.com/szhshp/panda-video-generator)** · ★ 292<br>程序员式视频自动化：抓素材、生成字幕脚本、Remotion 渲染、Playwright 多平台发布，每个环节可单独用<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手 · YouTube</sub><br><sub>更新于 2026-10-18 · 中文 · 6 个 skill</sub>

- **[douyin-live-recorder](https://github.com/WeiZhuochun/douyin-live-recorder)** · ★ 259<br>抖音直播切片号：多直播间监控、开播自动录制、边录边传百度网盘、高光识别剪辑、生成标题、多授权账号发布<br><sub>平台：抖音</sub><br><sub>更新于 2026-08-26 · 中文</sub>

- **[blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video)** · ★ 256<br>一句话出中文竖屏短视频：脚本、配音、画面、配乐、字幕、音效全自动，脚本、配音、画面三道关都可审<br><sub>平台：小红书 · 抖音 · B 站 · YouTube</sub><br><sub>更新于 2026-07-20 · 中文 · 2 个 skill</sub>

- **[xhs-cover-skill](https://github.com/Vivixiao980/xhs-cover-skill)** · ★ 226<br>小红书封面生成：18 种预设风格，命令行出图或改图，优先用 Codex 自带的生图，Gemini 作备用<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-24 · 中文</sub>

- **[leaderai-media-toolkit](https://github.com/AzenYes/leaderai-media-toolkit)** · ★ 219<br>LeaderAI 自媒体工具包：口播文案、口播剪辑（粗剪、字幕、画中画、音效）和无需素材的知识讲解动画<br><sub>平台：小红书 · 抖音 · 视频号 · B 站</sub><br><sub>更新于 2026-11-06 · 中文 · 4 个 skill · MIT</sub>

- **[xhs-writer-skill](https://github.com/JuneYaooo/xhs-writer-skill)** · ★ 214<br>小红书笔记一条龙：一句话生成竖版卡片组或短视频脚本，配文案和话题标签，有真实素材时用 gpt-image-2 图生图<br><sub>平台：小红书</sub><br><sub>更新于 2026-04-25 💤 · 中文 · Apache-2.0</sub>

- **[shorts-kit](https://github.com/howznguyen/shorts-kit)** · ★ 208<br>用 agent 和 Remotion 做带旁白的竖屏短视频：先核事实，再写叙事、配音、做画面、渲染、出封面和配文<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-09 · 英文 · 10 个 skill · MIT</sub>

- **[vibe-knowledge-video](https://github.com/xiazhuo123456789/vibe-knowledge-video)** · ★ 207<br>把数学、哲学等硬知识做成电影感的抖音知识视频：画面和配乐全用代码生成、双语字幕，一句话出成片和文案<br><sub>平台：抖音</sub><br><sub>更新于 2026-10-31 · 中文</sub>

- **[blcaptain-style-skill](https://github.com/dososo/blcaptain-style-skill)** · ★ 187<br>中文图文卡片：一段内容做成小红书 3:4 组图或公众号封面，三套视觉语言（静纸、实证、图桥）<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-07-08 · 中文</sub>

- **[ai-video-editing-skill](https://github.com/znyupup/ai-video-editing-skill)** · ★ 186<br>旅行 Vlog 自动剪辑：给一个素材文件夹，agent 挑镜头、排叙事、加字幕出成片，用 ffmpeg、Whisper 和视觉模型<br><sub>平台：通用</sub><br><sub>更新于 2026-04-27 💤 · 中文 · MIT</sub>

- **[easyedit](https://github.com/blixvip/easyedit)** · ★ 172<br>输入电影名，出一条粉丝混剪：先是带逐字字幕的经典台词，再接卡点蒙太奇，本地运行不要 API key<br><sub>平台：通用</sub><br><sub>更新于 2026-11-16 ⚠️ · 英文 · MIT</sub>

- **[wechat-article-pipeline](https://github.com/davinci-seven/wechat-article-pipeline)** · ★ 164<br>公众号排版流水线：Markdown 加本地配图生成公众号兼容 HTML、手机预览、长截图和完整性报告，不改原稿不自动发<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-10 · 中文 · MIT</sub>

- **[reelclaw](https://github.com/dansugc/reelclaw)** · ★ 157<br>给你在做的产品做 UGC 短视频广告：真人创作者反应镜头加产品画面，本地剪辑渲染，出 TikTok、Reels、Shorts<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-10-23 · 英文</sub><br><sub>💡 反应镜头来自 DansUGC，按条用积分付费</sub>

- **[xiaowan-wechat-layout-skill](https://github.com/cyberxiaowan/xiaowan-wechat-layout-skill)** · ★ 143<br>@小晚不在的公众号排版：在 gzh-design 上加阅读诊断、同款版式、封面和发布前检查，按手机宽度查断行和丢图<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-21 · 中文</sub><br><sub>💡 要先装 gzh-design，安装脚本缺它时会从 gzh-design 官方仓库下载；AGPL-3.0</sub>

- **[jianshuo/claude-skills](https://github.com/jianshuo/claude-skills)** · ★ 142<br>王建硕日常用的 skill：转写、翻译、配音、多机位剪辑、字幕烧录、横转竖，另有公众号发布<br><sub>平台：公众号 · X · YouTube</sub><br><sub>更新于 2026-11-21 · 多语言 · 44 个 skill · MIT</sub>

- **[threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill)** · ★ 128<br>把文字帖做成轮播图：适配 Threads、Instagram、LinkedIn、TikTok 和快拍尺寸<br><sub>平台：TikTok · Instagram · LinkedIn · Threads</sub><br><sub>更新于 2026-04-19 💤 · 英文 · MIT</sub>

- **[Vibepost](https://github.com/wuyoscar/Vibepost)** · ★ 125<br>Vibepost：把 Markdown 排成小红书图文卡片的桌面应用，agent 排版配图，每处改动你点头才算<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-21 · 中文</sub>

- **[daihuo-fanpai](https://github.com/wangcanyu/daihuo-fanpai)** · ★ 114<br>带货短视频复刻：反推爆款结构，换成你的产品，即梦/Seedance 重新生成镜头，配音拼接评分，交付剪映草稿<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-08 · 中文 · MIT</sub><br><sub>💡 生成镜头要即梦/Seedance，按量付费</sub>

- **[luobo-design](https://github.com/zhouwei713/luobo-design)** · ★ 113<br>一句话出设计物料：海报、通知、菜单、请柬、名片、logo 和七种结构的小红书封面；先问清需求、出三个方向让你挑，出图后自查溢字、对比度和广告法用语<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-04 · 中文 · MIT</sub>

- **[favstash-ai-video-editing-skills](https://github.com/alisadiq-ai/favstash-ai-video-editing-skills)** · ★ 102<br>FavStash 创作者 skill：找选题、写脚本，用代码剪 Reels、TikTok 和 Shorts，99 种画面风格和卡通角色<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-21 · 英文 · 7 个 skill · Apache-2.0</sub><br><sub>💡 剪辑在本机免费；排期、发布和数据要连 FavStash</sub>

- **[chaojifeng-video-content-creator](https://github.com/mileson/chaojifeng-video-content-creator)** · ★ 100<br>中文视频创作流水线：选题、口播稿、分镜、口播清洗、148 个 HTML 特效、字幕和发布包，每步有验收产物<br><sub>平台：通用</sub><br><sub>更新于 2026-11-12 · 中文 · MIT</sub>

- **[freestylefly/xiaohongshu-skills](https://github.com/freestylefly/xiaohongshu-skills)** · ★ 98<br>按主题生成小红书风格封面，生图用 Nano Banana Pro<br><sub>平台：小红书</sub><br><sub>更新于 2026-01-26 💤 · 中文</sub><br><sub>💡 要在 api.canghe.ai 申请 API Key</sub>

- **[lieflat-html-design](https://github.com/larashero3-dotcom/lieflat-html-design)** · ★ 96<br>HTML 设计 skill：小红书封面首图和长文竖图各 11 套模板，另有 12 套 PPT 风格<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-06 · 中文 · 4 个 skill · MIT</sub>

- **[space-image](https://github.com/SpaceZephyr/space-image)** · ★ 87<br>把文章或产品概念提炼成一个中心隐喻，出 2.35:1 公众号头图和概念海报，九套构图语法，只留标题和几个短标签<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-22 · 中文 · 2 个 skill</sub>

- **[editing-gameplay-montages](https://github.com/gustavomenani/editing-gameplay-montages)** · ★ 78<br>把 FPS 游戏片段和一首歌剪成踩点的竖屏短视频：击杀卡点、AI 补帧慢放、转场、缩放和歌词字，附封面<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-04 · 葡萄牙文</sub><br><sub>💡 补帧要支持 Vulkan 的显卡</sub>

- **[wechat-article-formatter-skill](https://github.com/iamzifei/wechat-article-formatter-skill)** · ★ 78<br>公众号排版：Markdown 经 bm.md 渲染成带样式的 HTML，可自定义样式，再用官方 API 发布<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-08 · 英文</sub>

- **[make-short](https://github.com/nocodehack/make-short)** · ★ 76<br>做动画 YouTube Shorts：在 Blender 里用代码搭 3D 场景和 2D 角色，配音字幕，再让评审 agent 打分改<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-05 ⚠️ · 英文 · MIT</sub>

- **[openshorts](https://github.com/jnMetaCode/openshorts)** · ★ 76<br>开片 OpenShorts：本地优先的短视频生产线，话题进成片出，写脚本、找画面、配音、字幕，免费路径 0 元<br><sub>平台：抖音 · YouTube</sub><br><sub>更新于 2026-11-01 · 中文 · MIT</sub>

- **[Clip-Forge](https://github.com/lowdevco/Clip-Forge)** · ★ 75<br>ClipForge：给 YouTube 链接或视频文件，找出高光片段打分，选中的做成调色、推镜、动态字幕的竖屏短视频<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-19 · 英文 · MIT</sub>

- **[wechat-typesetting-cy](https://github.com/CY-CHENYUE/wechat-typesetting-cy)** · ★ 75<br>公众号智能排版：不套模板，读懂文章后现场设计版式和配色，生成全内联 HTML，预览页一键复制<br><sub>平台：公众号</sub><br><sub>更新于 2026-09-19 · 中文 · Apache-2.0</sub>

- **[auto-edit-workspace](https://github.com/dean9703111/auto-edit-workspace)** · ★ 67<br>AI 自动剪辑工作区：口播视频剪掉 NG、照讲稿上字幕、加字卡和动画、配音效，浏览器剪辑台微调，本机渲染<br><sub>平台：YouTube · Instagram · Facebook</sub><br><sub>更新于 2026-11-22 · 中文 · 9 个 skill · MIT</sub><br><sub>💡 正文是繁体中文</sub>

- **[ah-skills](https://github.com/ahang008/ah-skills)** · ★ 62<br>阿杭的自媒体 skill：口播剪辑、AI 博主和减肥系列视频流程、用 Gemini 润色口播稿，另有需求澄清<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-14 · 中文 · 5 个 skill</sub>

- **[skills-videos-cortos](https://github.com/JustCarlos30/skills-videos-cortos)** · ★ 47<br>西班牙语的短视频技能包：挑剔脚本、本地 Whisper 处理配音和剪静音、Remotion 动画、音效和参考<br><sub>平台：通用</sub><br><sub>更新于 2026-11-06 · 西班牙文 · 5 个 skill · MIT</sub>

- **[youtube-translate-skill](https://github.com/0xSero/youtube-translate-skill)** · ★ 47<br>YouTube 字幕翻译：给视频、频道或播放列表链接，一次出几种语言的 .srt 字幕，可直接传回 YouTube<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-05 · 英文 · MIT</sub>

- **[claude-reel-editor](https://github.com/nicolapocock/claude-reel-editor)** · ★ 42<br>口播原片剪成品牌化短视频：清理音频、剪掉口头禅、加图形和字幕，渲染前先让你审，用 HyperFrames<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-01 · 英文 · MIT</sub>

- **[edit-reel](https://github.com/artemisln/edit-reel)** · ★ 42<br>Reels 自动剪辑：任何语言的逐字卡拉 OK 字幕，剪掉重拍和停顿，轻推镜、音效和插图，另有拍摄清单和录屏<br><sub>平台：Instagram</sub><br><sub>更新于 2026-11-04 · 英文 · 6 个 skill</sub>

- **[cut-as-code](https://github.com/WhiteTowerAI/cut-as-code)** · ★ 35<br>Cut-as-code：用 agent 剪视频，剪辑决定写成可读文件，加字幕、B-roll、动态图形和调色，浏览器里审再渲染<br><sub>平台：YouTube · TikTok</sub><br><sub>更新于 2026-11-05 · 英文 · 10 个 skill · MIT</sub>

- **[tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills)** · ★ 30<br>短视频模板：Reels、TikTok、Shorts 的钩子和结构、逐字动态字幕、倒计时、人名条<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-11 · 英文 · 4 个 skill · MIT</sub>

- **[huatu-skill](https://github.com/ythx-101/huatu-skill)** · ★ 29<br>画图 Skill：把长文和研究做成 6–10 页小红书图文轮播 PNG，或一页式 ELI5 视觉解释 HTML，本地渲染带质检<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-12 · 中文 · MIT</sub>

- **[super-video-agent](https://github.com/ww-w-ai/super-video-agent)** · ★ 27<br>用代码画出带旁白的视频：从 PDF、文章或选题做 YouTube Shorts、讲解片和 3D 飞行片，不用视频模型<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-06 · 英文</sub><br><sub>💡 源码公开但不是开源许可</sub>

- **[remotion-shorts-skill](https://github.com/social-media-skills/remotion-shorts-skill)** · ★ 26<br>Remotion 竖屏短视频：把选题、数据或更新日志做成大字动效短片，避开各 App 的按钮区，本地渲染<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-11 · 英文 · MIT</sub>

- **[hojas-studio](https://github.com/rakaga66/hojas-studio)** · ★ 24<br>阿拉伯语口播剪辑：剪停顿、逐词阿拉伯语字幕、讲解卡片和 B-roll，再在浏览器时间线上微调导出，本机运行<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-08 · 英文 · 2 个 skill</sub>

- **[wechat-visual-director](https://github.com/zhouke0929/wechat-visual-director)** · ★ 21<br>公众号视觉主编：把主题、资料或 Markdown 排成 26 套主题可换的公众号图文，AI 配图、手机预览、推草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-22 · 中文 · Apache-2.0</sub>

- **[十五画境](https://github.com/liuhaisi2026212-maker/motion-palette-15)** · ★ 21<br>十五画境：教 AI 用代码做片头和知识讲解 MG 动画，16 张风格卡，导出带声音的 MP4<br><sub>平台：通用</sub><br><sub>更新于 2026-10-31 · 中文</sub>

- **[红鸦 AI](https://github.com/rnthking/redya-skills)** · ★ 20<br>红鸦小红书图文：输入主题或链接生成标题、正文和整套图片，图片转 Live 实况，查敏感词<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-20 · 中文</sub><br><sub>💡 要红鸦账号，按积分计费</sub>

- **[social-skills](https://github.com/scrollmark/social-skills)** · ★ 19<br>社媒和短视频 skill 合集：语气、钩子、趋势和平台惯例，加短视频的场景语法、品牌一致性、字幕和卡点剪辑<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn</sub><br><sub>更新于 2026-11-21 · 英文 · 27 个 skill · MIT</sub>

- **[wechat-crayon-interactions](https://github.com/MFAI-LAB/wechat-crayon-interactions)** · ★ 19<br>公众号互动排版：蜡笔社论风，60 种可点可翻的互动样式，给出无脚本试贴稿和静态降级稿<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-06 · 中文 · MIT</sub>

- **[cartoon-shorts-skill](https://github.com/Matteoikarieth96/cartoon-shorts-skill)** · ★ 18<br>卡通动画短视频：先问清需求，再核事实、写故事，用 SVG 画面、配音、音乐和大字幕在本地渲染 9:16 成片<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-21 · 英文 · MIT</sub>

- **[claude-editing-skills](https://github.com/pihu26112005/claude-editing-skills)** · ★ 18<br>76 个动态图形 skill：给 Reels、TikTok、Shorts 加动态字幕、标题、画框、推镜和讲解动画，原片不动<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-19 · 英文 · 80 个 skill · MIT</sub>

- **[zero-dollar-studio](https://github.com/TheNoumanDev/zero-dollar-studio)** · ★ 18<br>零成本做 YouTube 视频：写稿、配音、字幕、音乐、动画和质检都用本地免费工具，另有长视频切 Shorts 和卡通角色<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-22 · 英文 · 5 个 skill · MIT</sub>

- **[claude-stickman-shorts](https://github.com/SyedBahjat/claude-stickman-shorts)** · ★ 17<br>火柴人互动故事短视频：写分支剧本、做动画、配音、逐词字幕和音效，观众投票选下一集走向，也能仿任何视频格式<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-09 · 英文 · MIT</sub>

- **[lsf-wechat-editorial-layout](https://github.com/leishifu666/lsf-wechat-editorial-layout)** · ★ 15<br>公众号长文排版：先选开篇动效、章节标记、截图背景和文末贴纸，再排成可编辑的公众号富文本<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-23 · 中文 · 30 个 skill · MIT</sub>

- **[wechat-article-skills](https://github.com/lqshow/wechat-article-skills)** · ★ 15<br>Markdown 一键排成公众号版式：6 种风格 × 9 种配色，开头动画横幅，表格和步骤变成会动的 SVG 卡片<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-10 · 中文 · 3 个 skill · MIT</sub>

- **[fragua](https://github.com/pedrovelasquez9/fragua)** · ★ 14<br>把原始录像剪成能发的短视频：剪静音、卡拉 OK 字幕、换镜、图卡、调色、音量标准化，再写各平台标题<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-10-30 · 西班牙文 · 3 个 skill · MIT</sub>

- **[claude-skills-shorts-animados](https://github.com/miguelcotrinaia/claude-skills-shorts-animados)** · ★ 13<br>用自己的角色做 TikTok 和 YouTube 动画短视频：每个角色一种声音，给一个主题出成片和发布文案<br><sub>平台：YouTube · TikTok</sub><br><sub>更新于 2026-11-01 · 西班牙文 · 2 个 skill · MIT</sub>

- **[Revid](https://github.com/tmakersas/revid-skills)** · ★ 12<br>Revid 官方 skill 和 MCP：把链接、文章、商品、PDF 或一句话做成短视频，查爆款，发到 TikTok、YouTube 等<br><sub>平台：X · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-08 · 英文 · 13 个 skill · MIT</sub><br><sub>💡 要 Revid 账号，OAuth 登录</sub>

- **[claude-edits-skill](https://github.com/iamjeeth/claude-edits-skill)** · ★ 10<br>让 Claude Code 通过 Instagram Edits 自带的 MCP 剪 Reels：加贴片、音效、标题字幕，逐词转写和导出<br><sub>平台：Instagram</sub><br><sub>更新于 2026-11-06 · 英文 · MIT</sub>

- **[video-editing-skill](https://github.com/social-media-skills/video-editing-skill)** · ★ 10<br>口播视频粗剪：剪停顿、嗯啊和重拍，推镜遮跳剪，音频响度统一，出 SRT 字幕和 YouTube 章节，本地运行<br><sub>平台：YouTube · TikTok · Instagram · LinkedIn · Facebook</sub><br><sub>更新于 2026-11-11 · 英文 · MIT</sub>

- **[b-roll-skills](https://github.com/iart-ai/b-roll-skills)** · ★ 9<br>给口播视频加 B-roll：转写后逐句决定露人、叠图还是全屏图形，图形按说的内容画，保留原声出 MP4<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-11 · 英文 · MIT</sub>

- **[instagram-carousel-skill](https://github.com/social-media-skills/instagram-carousel-skill)** · ★ 9<br>Instagram 轮播图：选格式、写封面和每页文案，本地渲染 1080x1350 图片，写替代文字和配文，确认后发布<br><sub>平台：Instagram</sub><br><sub>更新于 2026-11-11 · 英文 · MIT</sub><br><sub>💡 渲染免费；发布走同团队的 WoopSocial（有免费档）</sub>

- **[livestream-clip-editor](https://github.com/avisii1680769-cell/livestream-clip-editor)** · ★ 9<br>电商直播切片剪辑：按句级时间戳跳剪拼接、1.25 倍不变调提速、人工选段、可选画面微调去重，本地运行<br><sub>平台：抖音 · 视频号 · 快手</sub><br><sub>更新于 2026-11-14 · 中文 · MIT</sub>

- **[luobo-article-visual](https://github.com/zhouwei713/luobo-article-visual)** · ★ 9<br>萝卜文章视觉：读懂文章再出公众号封面、正文配图、X 文章横幅和小红书多页教程图，数字用 HTML 排字不出错<br><sub>平台：小红书 · 公众号 · X</sub><br><sub>更新于 2026-11-06 · 中文 · MIT</sub>

- **[墨排 Mopai](https://github.com/woodti/mopai)** · ★ 9<br>墨排：写一次 Markdown，排成公众号样式、小红书卡片和 X 推文串，带 skill、MCP 和命令行<br><sub>平台：小红书 · 公众号 · X</sub><br><sub>更新于 2026-10-31 · 中文 · MIT</sub>

- **[Riffkit](https://github.com/riffkit/skill)** · ★ 8<br>Riffkit 官方 skill：换掉视频里的衣服、场景、商品或人，镜头和节奏不变，或照爆款的结构拍成你的版本<br><sub>平台：TikTok</sub><br><sub>更新于 2026-11-14 · 英文 · 2 个 skill · MIT</sub><br><sub>💡 要 Riffkit 账号，生成按量付费</sub>

- **[youtube-video-skills](https://github.com/iart-ai/youtube-video-skills)** · ★ 8<br>YouTube 片头片尾和播客声波视频：3–5 秒品牌片头、避开可点区域的 20 秒片尾，把播客片段做成带字幕的声波视频<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-11 · 英文 · 2 个 skill · MIT</sub>

- **[social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes)** · ★ 7<br>检查并裁切社媒图片尺寸：按 Instagram、Facebook、X、LinkedIn、YouTube、TikTok、Pinterest 等平台规格校验<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-04-30 💤 · 英文 · 2 个 skill · MIT</sub>

- **[xiaohongshu-images-skill](https://github.com/iamzifei/xiaohongshu-images-skill)** · ★ 7<br>把 Markdown、HTML 或文字排成 3:4 的小红书图片，配 AI 生成的封面<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-08 · 英文</sub>

- **[dsh-fishpai](https://github.com/OMSociety/dsh-fishpai)** · ★ 6<br>鱼排编辑器：DeepSeek Harness 侧栏里的公众号排版台，人改字加批注，模型按块读改动，成品粘进公众号<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-22 · 中文 · MIT</sub><br><sub>💡 DeepSeek Harness 插件；排版内核来自 MoPai 墨排</sub>

- **[not-a-blogger](https://github.com/ilyautov/not-a-blogger)** · ★ 6<br>做短视频的 agent 工具包：143 个配方、18 个 skill、模板和质检工具，附 12 条真实视频拆解和给人看的小课<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-09 · 英文 · 21 个 skill · MIT</sub>

- **[screenshot-infographic-skill](https://github.com/Wanqiu12345/screenshot-infographic-skill)** · ★ 6<br>发一张截图或一段文字，生成一整套小红书、公众号能直接用的功能教程图和信息图<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-11-05 · 中文 · MIT</sub>

- **[video-recreation-skill](https://github.com/Yf040528/video-recreation-skill)** · ★ 6<br>爆款视频二创：拆解、重写、生成和五级质检，人物和商品一致性锚点，换品牌片尾，附 285 个电商视频提示词<br><sub>平台：抖音 · TikTok</sub><br><sub>更新于 2026-11-09 · 中文 · MIT</sub><br><sub>💡 FrameFlow（yimiagent.cn）出品，生成镜头要视频模型，按量付费</sub>

- **[xiaohongshu-cover-maker-skill](https://github.com/beatra-ai/xiaohongshu-cover-maker-skill)** · ★ 6<br>小红书封面：把一张照片或一个选题做成 3:4 竖版封面，背景干净、焦点突出、留好文字区<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-20 · 中文 · MIT-0</sub><br><sub>💡 要 Beatra 账号，生成扣积分</sub>

- **[muse-Tiktok-Skill](https://github.com/Ayanlin1688/muse-Tiktok-Skill)** · ★ 5<br>给 Muse Video 写电商带货视频提示词：TikTok Shop 和抖音电商，防货不对板、换脸和塑料感<br><sub>平台：抖音 · TikTok</sub><br><sub>更新于 2026-11-14 · 中文</sub>

- **[say-then-publish](https://github.com/Jo6666887/say-then-publish)** · ★ 5<br>说了就发：在 agent 里聊想法，聊完自动整理成正文并排成小红书图文卡片，15 套主题，本地保存<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-14 · 中文 · MIT</sub>

- **[Skill-Editor-IA](https://github.com/brianacevedo2001-lab/Skill-Editor-IA)** · ★ 5<br>白标视频剪辑工程：Claude Code 照 CLAUDE.md 剪静音、同步、做动画、混音渲染，一次录制出 YouTube、短视频和 LinkedIn 成品<br><sub>平台：YouTube · TikTok · Instagram · LinkedIn</sub><br><sub>更新于 2026-11-11 · 📝 提示词 · 西班牙文 · MIT</sub><br><sub>💡 没有 SKILL.md：克隆仓库后在目录里开 Claude Code 用，品牌信息改 marca/</sub>

- **[芦苇 Reed](https://github.com/yoruuuchan/wechat-md-studio)** · ★ 5<br>芦苇 Reed：一份 Markdown 排出公众号文章、小红书卡片和长图，227 套主题，AI 可经 MCP 直接改稿<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-11-19 · 中文 · AGPL-3.0</sub>

- **[3d-map-video-skill](https://github.com/sixwei2025/3d-map-video-skill)** · ★ 4<br>3D 地图短视频：用真实地形做城市地理科普和古代战役推演竖屏片，镜头、行军路线和口播写在一个 JSON 里<br><sub>平台：公众号 · 视频号</sub><br><sub>更新于 2026-11-18 · 中文 · MIT</sub>

- **[AITuber](https://github.com/aituberapp/ai-video-skill)** · ★ 4<br>AITuber 视频 skill：从脚本或想法生成带 AI 配音、画面和字幕的短视频和长视频，1300 多种声音，可直接发布<br><sub>平台：X · YouTube · TikTok · Instagram · Threads · Facebook</sub><br><sub>更新于 2026-11-09 · 英文 · MIT</sub><br><sub>💡 要 AITuber 账号和 API key</sub>

- **[claude-video-editor](https://github.com/vitormenoli/claude-video-editor)** · ★ 4<br>YouTube 长视频从素材剪到成片：两遍转写，剪掉静音、口吃和等待，代码做动效，再查一遍剪口<br><sub>平台：YouTube</sub><br><sub>更新于 2026-10-30 · 葡萄牙文</sub>

- **[edit-reel](https://github.com/MMhaidra/edit-reel)** · ★ 4<br>短视频自动剪辑和字幕：Whisper 转写、多语言字幕、纸片和实物风格的动态图形，给 Reels、TikTok、Shorts<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-17 · 英文 · 2 个 skill · MIT</sub>

- **[reel-scribe](https://github.com/dengxianghua888-ops/reel-scribe)** · ★ 4<br>影述剪辑技能库：口播、影视解说、教程、访谈、Vlog 的剪辑方法，素材分析、选段编排和局部修改<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-22 · 中文 · 71 个 skill</sub><br><sub>💡 作者标为实验性源码预览，不是稳定版</sub>

- **[treemation](https://github.com/Adytm404/treemation)** · ★ 4<br>全用代码做竖屏 3D 科普短视频：像素风主持人和吉祥物、运镜、逐词字幕和口型，一句话出 MP4 和封面<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-16 · 英文 · MIT</sub><br><sub>💡 配音用 ElevenLabs；示例是印尼语</sub>

- **[wechat-article-cover-skill](https://github.com/beatra-ai/wechat-article-cover-skill)** · ★ 4<br>公众号封面：输入标题、主题或参考图，生成封面、首图和主题配图，可把标题画进图或留标题位<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-20 · 中文 · MIT-0</sub><br><sub>💡 要 Beatra 账号，生成扣积分</sub>

- **[weekly-production](https://github.com/lmy414/weekly-production)** · ★ 4<br>像素风周刊视频制作：放进榜单、文案、原片和配乐，出整期视频，另出网页、长图、分享卡和公众号封面<br><sub>平台：公众号 · B 站</sub><br><sub>更新于 2026-11-07 · 中文 · GPL-3.0</sub><br><sub>💡 模板沿用「AI 娘周刊」的节目顺序</sub>

- **[ai-short-video-skill](https://github.com/6667084/ai-short-video-skill)** · ★ 3<br>AI 短视频工作流：带货短片、口播精剪、活动混剪、字幕花字、配乐、封面、质检和剪映草稿，带 MCP<br><sub>平台：抖音 · 视频号 · TikTok</sub><br><sub>更新于 2026-11-06 · 中文 · 11 个 skill</sub><br><sub>💡 视频、音乐和云端超分走 reAPI 付费，先报价再提交</sub>

- **[claude-reelsmith](https://github.com/lalimi/claude-reelsmith)** · ★ 3<br>用自己的素材做 Reels 和 TikTok：写稿、配音、从相册挑镜头按词剪、加动效和字幕、混音，出封面和配文<br><sub>平台：TikTok · Instagram</sub><br><sub>更新于 2026-11-13 · 英文 · 7 个 skill · MIT</sub>

- **[faceless-shorts](https://github.com/kinnuworks/faceless-shorts)** · ★ 3<br>一句话做出不露脸的 YouTube Shorts：查证选题、写稿、配音，画面按每个词的时间做，加字幕音效<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-03 · 英文</sub>

- **[gzh-skill-kit](https://github.com/88lin/gzh-skill-kit)** · ★ 3<br>公众号排版：把 Markdown、Word 或 PDF 稿子排成能直接粘进公众号的 HTML，18 套主题，可按参考图生成新主题<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-13 · 中文</sub><br><sub>💡 仅限个人非商业使用</sub>

- **[Minimax-H3-Tiktok-skill](https://github.com/Ayanlin1688/Minimax-H3-Tiktok-skill)** · ★ 3<br>给 MiniMax H3（海螺）写 TikTok Shop 实拍感带货视频提示词，防多手、悬空、穿模和蜡像脸<br><sub>平台：TikTok</sub><br><sub>更新于 2026-11-16 · 中文 · MIT</sub>

- **[thumbnail-studio](https://github.com/blixvip/thumbnail-studio)** · ★ 3<br>YouTube 缩略图工作台：ChatGPT 网页和参考图并排，12 个缩略图设计 skill，找钩子、构图、配色和表情<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-14 ⚠️ · 英文 · 12 个 skill · MIT</sub><br><sub>💡 只支持 Windows，出图用你自己的 ChatGPT 账号</sub>

- **[EasySociable](https://github.com/murphywuwu/easysociable-mcp)** · ★ 0<br>品牌轮播图：agent 写每页文案，EasySociable 套版式和品牌色，出 TikTok、Instagram、LinkedIn、小红书尺寸的多页图<br><sub>平台：小红书 · TikTok · Instagram · LinkedIn · Threads</sub><br><sub>更新于 2026-11-13 · 英文 · 3 个 skill · MIT</sub><br><sub>💡 要 EasySociable 账号（CLI 里 easysociable auth login），成图在它的网页 Studio 里改和下载</sub>

- **[skills](https://github.com/HoneyVid/skills)** · ★ 0<br>爆款 AI 短视频：用一张照片把人物、宠物或角色放进热门视频模板，或用 Kling、Veo、Seedance 生成视频和图片，先报价再生成<br><sub>平台：通用</sub><br><sub>更新于 2026-11-20 · 英文 · 6 个 skill · MIT</sub><br><sub>💡 要 HoneyVid 账号，按积分付费；通过 HoneyVid 远程 MCP 或 npx honeyvid CLI 调用</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# guizang-social-card-skill
npx skills add op7418/guizang-social-card-skill
# gzh-design-skill
npx skills add isjiamu/gzh-design-skill
# guizang-ppt-skill
npx skills add op7418/guizang-ppt-skill
# ian-xiaohei-illustrations
npx skills add helloianneo/ian-xiaohei-illustrations
# handraw-style
npx skills add yang0/handraw-style
# md2wechat-skill
npx skills add geekjourneyx/md2wechat-skill
# herk-edit-kit
npx skills add nateherkai/herk-edit-kit
# native-subtitle-quote-image
npx skills add chengyi-ai/native-subtitle-quote-image
# youtube-shorts-pipeline
npx skills add rushindrasinha/youtube-shorts-pipeline
# Youtube-clipper-skill
npx skills add op7418/Youtube-clipper-skill
# gif-factory
npx skills add WoYun520/gif-factory
# digital-human-koubo
npx skills add andyhuo520/digital-human-koubo
# rnskill
npx skills add Pluviobyte/rnskill
# video-podcast-maker
npx skills add Agents365-ai/video-podcast-maker
# xhs-visual-director-skill
npx skills add ziguishian/xhs-visual-director-skill
# vibe-knowledge-film
npx skills add HeyChengC/vibe-knowledge-film
# Punk-Posters
npx skills add adrianpunk/Punk-Posters
# qiaomu-mondo-poster-design
npx skills add joeseesun/qiaomu-mondo-poster-design
# clipforge
npx skills add xixihhhh/clipforge
# story-studio
npx skills add konlu/story-studio
# video-spec-builder
npx skills add feicaiclub/video-spec-builder
# gbro-cover-design
npx skills add pyang5166/gbro-cover-design
# wallstreet-explainer
npx skills add HeyChengC/wallstreet-explainer
# motion-graphics-skills
npx skills add charlie947/motion-graphics-skills
# gimi-illustration-skill
npx skills add GiMi-Xiaomi/gimi-illustration-skill
# xiaohu-wechat-format
npx skills add xiaohuailabs/xiaohu-wechat-format
# clipify
npx skills add louisedesadeleer/clipify
# chatgpt-video-editing-skills
npx skills add Jaycheng1103/chatgpt-video-editing-skills
# Document-illustrator-skill
npx skills add op7418/Document-illustrator-skill
# Clips Kitty
npx skills add ColinGPT9/clips-studio
# whiteboard-teacher-video
npx skills add liangdabiao/whiteboard-teacher-video
# smart-illustrator
npx skills add axtonliu/smart-illustrator
# clipcat-skill
npx skills add Clipcat-ai/clipcat-skill
# article2media
npx skills add threerocks/article2media
# DaVinci-AutoEdit-Agent
npx skills add liuluhaixiu/DaVinci-AutoEdit-Agent
# hotclip
npx skills add xixihhhh/hotclip
# claude-design-card
npx skills add geekjourneyx/claude-design-card
# cy-carousel-skill
npx skills add chengyi-ai/cy-carousel-skill
# atutun-xhs-cover
npx skills add panggungunvibe/atutun-xhs-cover
# ttfake92-lab/skills
npx skills add ttfake92-lab/skills
# ian-xhs-carousel
npx skills add helloianneo/ian-xhs-carousel
# xiaohu-ip-studio
npx skills add xiaohuailabs/xiaohu-ip-studio
# oil-cover
npx skills add oil-oil/oil-cover
# oh-my-cover-design
npx skills add hongfamonvAI/oh-my-cover-design
# panda-video-generator
npx skills add szhshp/panda-video-generator
# douyin-live-recorder
npx skills add WeiZhuochun/douyin-live-recorder
# blcaptain-lingjian-video
npx skills add dososo/blcaptain-lingjian-video
# xhs-cover-skill
npx skills add Vivixiao980/xhs-cover-skill
# leaderai-media-toolkit
npx skills add AzenYes/leaderai-media-toolkit
# xhs-writer-skill
npx skills add JuneYaooo/xhs-writer-skill
# shorts-kit
npx skills add howznguyen/shorts-kit
# vibe-knowledge-video
npx skills add xiazhuo123456789/vibe-knowledge-video
# blcaptain-style-skill
npx skills add dososo/blcaptain-style-skill
# ai-video-editing-skill
npx skills add znyupup/ai-video-editing-skill
# easyedit
npx skills add blixvip/easyedit
# wechat-article-pipeline
npx skills add davinci-seven/wechat-article-pipeline
# reelclaw
npx skills add dansugc/reelclaw
# xiaowan-wechat-layout-skill
npx skills add cyberxiaowan/xiaowan-wechat-layout-skill
# jianshuo/claude-skills
npx skills add jianshuo/claude-skills
# threads-carousel-claude-skill
npx skills add itchernetski/threads-carousel-claude-skill
# Vibepost
npx skills add wuyoscar/Vibepost
# daihuo-fanpai
npx skills add wangcanyu/daihuo-fanpai
# luobo-design
npx skills add zhouwei713/luobo-design
# favstash-ai-video-editing-skills
npx skills add alisadiq-ai/favstash-ai-video-editing-skills
# chaojifeng-video-content-creator
npx skills add mileson/chaojifeng-video-content-creator
# freestylefly/xiaohongshu-skills
npx skills add freestylefly/xiaohongshu-skills
# lieflat-html-design
npx skills add larashero3-dotcom/lieflat-html-design
# space-image
npx skills add SpaceZephyr/space-image
# editing-gameplay-montages
npx skills add gustavomenani/editing-gameplay-montages
# wechat-article-formatter-skill
npx skills add iamzifei/wechat-article-formatter-skill
# make-short
npx skills add nocodehack/make-short
# openshorts
npx skills add jnMetaCode/openshorts
# Clip-Forge
npx skills add lowdevco/Clip-Forge
# wechat-typesetting-cy
npx skills add CY-CHENYUE/wechat-typesetting-cy
# auto-edit-workspace
npx skills add dean9703111/auto-edit-workspace
# ah-skills
npx skills add ahang008/ah-skills
# skills-videos-cortos
npx skills add JustCarlos30/skills-videos-cortos
# youtube-translate-skill
npx skills add 0xSero/youtube-translate-skill
# claude-reel-editor
npx skills add nicolapocock/claude-reel-editor
# edit-reel
npx skills add artemisln/edit-reel
# cut-as-code
npx skills add WhiteTowerAI/cut-as-code
# tiktok-video-skills
npx skills add iart-ai/tiktok-video-skills
# huatu-skill
npx skills add ythx-101/huatu-skill
# super-video-agent
npx skills add ww-w-ai/super-video-agent
# remotion-shorts-skill
npx skills add social-media-skills/remotion-shorts-skill
# hojas-studio
npx skills add rakaga66/hojas-studio
# wechat-visual-director
npx skills add zhouke0929/wechat-visual-director
# 十五画境
npx skills add liuhaisi2026212-maker/motion-palette-15
# 红鸦 AI
npx skills add rnthking/redya-skills
# social-skills
npx skills add scrollmark/social-skills
# wechat-crayon-interactions
npx skills add MFAI-LAB/wechat-crayon-interactions
# cartoon-shorts-skill
npx skills add Matteoikarieth96/cartoon-shorts-skill
# claude-editing-skills
npx skills add pihu26112005/claude-editing-skills
# zero-dollar-studio
npx skills add TheNoumanDev/zero-dollar-studio
# claude-stickman-shorts
npx skills add SyedBahjat/claude-stickman-shorts
# lsf-wechat-editorial-layout
npx skills add leishifu666/lsf-wechat-editorial-layout
# wechat-article-skills
npx skills add lqshow/wechat-article-skills
# fragua
npx skills add pedrovelasquez9/fragua
# claude-skills-shorts-animados
npx skills add miguelcotrinaia/claude-skills-shorts-animados
# Revid
npx skills add tmakersas/revid-skills
# claude-edits-skill
npx skills add iamjeeth/claude-edits-skill
# video-editing-skill
npx skills add social-media-skills/video-editing-skill
# b-roll-skills
npx skills add iart-ai/b-roll-skills
# instagram-carousel-skill
npx skills add social-media-skills/instagram-carousel-skill
# livestream-clip-editor
npx skills add avisii1680769-cell/livestream-clip-editor
# luobo-article-visual
npx skills add zhouwei713/luobo-article-visual
# 墨排 Mopai
npx skills add woodti/mopai
# Riffkit
npx skills add riffkit/skill
# youtube-video-skills
npx skills add iart-ai/youtube-video-skills
# social-media-image-sizes
npx skills add Branding5/social-media-image-sizes
# xiaohongshu-images-skill
npx skills add iamzifei/xiaohongshu-images-skill
# dsh-fishpai
npx skills add OMSociety/dsh-fishpai
# not-a-blogger
npx skills add ilyautov/not-a-blogger
# screenshot-infographic-skill
npx skills add Wanqiu12345/screenshot-infographic-skill
# video-recreation-skill
npx skills add Yf040528/video-recreation-skill
# xiaohongshu-cover-maker-skill
npx skills add beatra-ai/xiaohongshu-cover-maker-skill
# muse-Tiktok-Skill
npx skills add Ayanlin1688/muse-Tiktok-Skill
# say-then-publish
npx skills add Jo6666887/say-then-publish
# 芦苇 Reed
npx skills add yoruuuchan/wechat-md-studio
# 3d-map-video-skill
npx skills add sixwei2025/3d-map-video-skill
# AITuber
npx skills add aituberapp/ai-video-skill
# claude-video-editor
npx skills add vitormenoli/claude-video-editor
# edit-reel
npx skills add MMhaidra/edit-reel
# reel-scribe
npx skills add dengxianghua888-ops/reel-scribe
# treemation
npx skills add Adytm404/treemation
# wechat-article-cover-skill
npx skills add beatra-ai/wechat-article-cover-skill
# weekly-production
npx skills add lmy414/weekly-production
# ai-short-video-skill
npx skills add 6667084/ai-short-video-skill
# claude-reelsmith
npx skills add lalimi/claude-reelsmith
# faceless-shorts
npx skills add kinnuworks/faceless-shorts
# gzh-skill-kit
npx skills add 88lin/gzh-skill-kit
# Minimax-H3-Tiktok-skill
npx skills add Ayanlin1688/Minimax-H3-Tiktok-skill
# thumbnail-studio
npx skills add blixvip/thumbnail-studio
# EasySociable
npx skills add murphywuwu/easysociable-mcp
# skills
npx skills add HoneyVid/skills
```

</details>

<a id="group-publish"></a>
### 发布和自动化

把内容发到平台上：定时发布、一稿多发、浏览器自动化。多数要登录你的账号，装之前先看它怎么保存登录态。

- 🌟 **[social-auto-upload](https://github.com/dreammis/social-auto-upload)** · ★ 16.8k<br>一键上传视频到抖音、小红书、视频号、B站、快手、微博、TikTok、YouTube 等，支持定时发布，带 sau 命令和 4 个 skill<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 微博 · 快手 · YouTube · TikTok</sub><br><sub>更新于 2026-10-22 · 中文 · 18 个 skill · MIT</sub>

- **[Wechatsync](https://github.com/wechatsync/Wechatsync)** · ★ 6.7k<br>文章同步助手：公众号文章一键同步到知乎、头条、小红书、掘金、CSDN 等 29+ 平台，Chrome 扩展用你自己的登录态，带 MCP<br><sub>平台：小红书 · 公众号 · 知乎 · 头条</sub><br><sub>更新于 2026-11-15 · 中文 · GPL-3.0</sub>

- **[XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills)** · ★ 3.6k<br>小红书自动发布、评论和检索：通过 Chrome 开发者协议发图文和视频，支持多账号和无头模式<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-22 · 中文 · MIT</sub>

- **[autoclaw-cc/xiaohongshu-skills](https://github.com/autoclaw-cc/xiaohongshu-skills)** · ★ 2.1k<br>小红书自动化：用你已登录的浏览器和真实账号登录、发图文和视频、搜索、评论点赞，开箱即用<br><sub>平台：小红书</sub><br><sub>更新于 2026-05-23 💤 · 中文 · 6 个 skill · MIT</sub>

- **[MatrixMedia](https://github.com/hanliang97/MatrixMedia)** · ★ 1.6k<br>矩媒：视频矩阵批量发布到抖音、快手、视频号、小红书、B站、百家号、头条、番茄视频，查登录状态和发布记录<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手 · 头条</sub><br><sub>更新于 2026-11-21 · 中文 · 4 个 skill · GPL-2.0</sub><br><sub>💡 skill 驱动矩媒桌面端，要先装应用</sub>

- **[x-article-publisher-skill](https://github.com/wshuyi/x-article-publisher-skill)** · ★ 874<br>Markdown 长文一条命令发到 X Articles（推特长文），支持分割线、表格转图片和 Mermaid<br><sub>平台：X</sub><br><sub>更新于 2026-01-25 💤 · 中文 · MIT</sub>

- **[social-push](https://github.com/jihe520/social-push)** · ★ 553<br>用 agent-browser 把内容发到小红书、微博、知乎、公众号、X 等平台，流程能自我改进<br><sub>平台：小红书 · 公众号 · 微博 · 知乎 · X</sub><br><sub>更新于 2026-06-28 · 中文 · 2 个 skill</sub>

- **[SyncCaster](https://github.com/RyanYipeng/SyncCaster)** · ★ 512<br>多平台文章同步 Chrome 扩展：Markdown 编辑，一键发到掘金、CSDN、知乎、公众号等 17+ 平台，带 MCP 桥给 agent 用<br><sub>平台：公众号 · 知乎</sub><br><sub>更新于 2026-08-25 · 中文 · MIT</sub>

- **[video-publisher-skill](https://github.com/oil-oil/video-publisher-skill)** · ★ 288<br>把视频、标题、封面准备成小红书、抖音、B站、视频号、YouTube 的已核验草稿，可续传，默认停在最终发布前<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · YouTube</sub><br><sub>更新于 2026-11-16 · 中文 · MIT</sub>

- **[xiaohongshu-mcp-skills](https://github.com/autoclaw-cc/xiaohongshu-mcp-skills)** · ★ 281<br>配合 xiaohongshu-mcp 用的 skill：部署服务、扫码登录、发笔记、搜索、内容规划<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-05 💤 · 中文 · 9 个 skill · MIT</sub>

- **[Taisly Agent Kit](https://github.com/taisly/agent)** · ★ 211<br>Taisly 短视频发布套件：skill、MCP、CLI 和 SDK，从 agent 发视频到 TikTok、Reels、Shorts、X 和 Facebook<br><sub>平台：X · YouTube · TikTok · Instagram · Facebook</sub><br><sub>更新于 2026-10-22 · 英文 · MIT</sub><br><sub>💡 要 Taisly 账号，可以免费开始</sub>

- **[wechat-article-publisher-skill](https://github.com/iamzifei/wechat-article-publisher-skill)** · ★ 159<br>通过 API 把 Markdown 或 HTML 文章推送到公众号草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-08-12 · 多语言 · MIT</sub>

- **[Spreado](https://github.com/BadKid90s/Spreado)** · ★ 154<br>开源视频发布工具：一键同步到抖音、小红书、快手、视频号，扫码登录、管理 Cookie，带 skill<br><sub>平台：小红书 · 抖音 · 视频号 · 快手</sub><br><sub>更新于 2026-11-07 · 中文 · 2 个 skill · Apache-2.0</sub>

- **[Linked-API/linkedin-skills](https://github.com/Linked-API/linkedin-skills)** · ★ 114<br>LinkedIn 自动化：查人和公司、发私信、加好友、发帖，另有按目标客户筛选并跟进的获客流程<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-11-19 · 英文 · 2 个 skill · MIT</sub><br><sub>💡 通过 Linked API 云服务操作你的账号，要先注册</sub>

- **[socialclaw](https://github.com/ndesv21/socialclaw)** · ★ 112<br>社媒排期 CLI 和 OpenClaw skill：发到 X、LinkedIn、Instagram、Facebook 主页、TikTok、YouTube 等<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-10-12 · 英文 · 3 个 skill · MIT</sub><br><sub>💡 要 SocialClaw 账号，CLI 和 API 要试用或付费方案</sub>

- **[douyin-image-post-scheduler](https://github.com/chengyi-ai/douyin-image-post-scheduler)** · ★ 108<br>抖音图文批量定时发布：从本地素材文件夹排队，在已登录的 Chrome 里上传、选话题和音乐、定时并回后台核验<br><sub>平台：抖音</sub><br><sub>更新于 2026-10-14 · 中文 · MIT</sub>

- **[douyin-upload-mcp-skill](https://github.com/WJZ-P/douyin-upload-mcp-skill)** · ★ 93<br>抖音视频和图文全自动发布：通过 CDP 操作创作者平台，MCP 优先、脚本兜底，适合 OpenClaw<br><sub>平台：抖音</sub><br><sub>更新于 2026-04-01 💤 · 中文 · AGPL-3.0</sub>

- **[publora/skills](https://github.com/publora/skills)** · ★ 71<br>Publora 官方 skill：从 agent 发帖或排期到 LinkedIn、X、Instagram、Threads、TikTok 等 10 个平台<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook</sub><br><sub>更新于 2026-11-18 · 英文 · 9 个 skill · MIT</sub><br><sub>💡 要 Publora 账号，免费档覆盖除 X 以外的平台</sub>

- **[douyin-skills](https://github.com/zJay26/douyin-skills)** · ★ 62<br>抖音本地 skill：扫码登录、浏览搜索、点赞评论和发布作品，浏览器操作走结构化命令行，登录态存本地，不做批量互动<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-05 · 英文 · 6 个 skill · MIT</sub>

- **[0731coderlee-sudo/wechat-publisher](https://github.com/0731coderlee-sudo/wechat-publisher)** · ★ 49<br>一键把 Markdown 发到公众号草稿箱：基于 wenyan-cli，多主题、代码高亮、图片自动上传<br><sub>平台：公众号</sub><br><sub>更新于 2026-02-05 💤 · 中文 · MIT</sub>

- **[upload-post-skill](https://github.com/Upload-Post/upload-post-skill)** · ★ 41<br>通过 Upload-Post API 把视频、图片、文字和文档发到 TikTok、Instagram、YouTube、LinkedIn、X 等平台<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-11-20 · 英文</sub><br><sub>💡 要 Upload-Post 账号和 API Key</sub>

- **[douyin-mcp-server](https://github.com/lancelin111/douyin-mcp-server)** · ★ 35<br>抖音视频上传 skill 和 MCP：管理登录、上传视频、自动发到创作者平台，支持 OpenClaw、Claude Code<br><sub>平台：抖音</sub><br><sub>更新于 2026-06-12 · 中文 · MIT</sub>

- **[Post Bridge](https://github.com/post-bridge-hq/agent-mode)** · ★ 17<br>Post Bridge 的 skill 和 MCP：一条命令发到 Instagram、TikTok、YouTube、X 等 10 个平台，另有营销和多账号运营<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-17 · 英文 · 3 个 skill · MIT</sub><br><sub>💡 要 Post Bridge 账号和 API key</sub>

- **[social-publish-skills](https://github.com/puppyfront-web/social-publish-skills)** · ★ 14<br>社媒发布 skill 加 Playwright 命令行：扫码或 Cookie 登录，把视频和图文发到视频号、抖音、快手、B 站、公众号、知乎等<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · 知乎 · 快手</sub><br><sub>更新于 2026-11-07 · 中文 · 15 个 skill · MIT</sub><br><sub>💡 登录态存在本机</sub>

- **[postkitty](https://github.com/mertkayacs/postkitty)** · ★ 12<br>PostKitty：一条帖子进，各平台版本出，按平台改写文案、裁图和视频时保住人脸、检查每个文件，本地运行<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook</sub><br><sub>更新于 2026-11-12 · 英文 · MIT</sub><br><sub>💡 Hermes Agent 插件</sub>

- **[x-post-skill](https://github.com/win4r/x-post-skill)** · ★ 12<br>在 Claude Code 里直接发 X：发帖、按名字续推文串、带图片视频、截终端图发出去<br><sub>平台：X</sub><br><sub>更新于 2026-11-16 · 英文</sub><br><sub>💡 要自己申请 X API key</sub>

- **[red-publisher-skill](https://github.com/iamzifei/red-publisher-skill)** · ★ 11<br>一条命令把图片和笔记发到小红书：通过 CDP 连浏览器，始终存为草稿<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-12 · 多语言 · MIT</sub>

- **[easypost](https://github.com/gybin02/easypost)** · ★ 8<br>快推 EasyPost：复用你日常的 Chrome 和登录状态，一次把短视频和图文同步发到抖音、快手、视频号、B 站、微博、X 等<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 微博 · 快手 · X · Instagram</sub><br><sub>更新于 2026-11-20 · 中文 · 9 个 skill · MIT</sub>

- **[twitterapi-io-skill](https://github.com/dorukardahan/twitterapi-io-skill)** · ★ 7<br>TwitterAPI.io skill：让 agent 用 X，搜索、发帖、点赞、转推、关注、私信、社群和 webhook，76 个接口带 curl 示例<br><sub>平台：X</sub><br><sub>更新于 2026-11-13 · 英文 · 2 个 skill · MIT</sub><br><sub>💡 要 TwitterAPI.io 的 API key，按调用付费</sub>

- **[content-repurposer](https://github.com/Mahanaicoach/content-repurposer)** · ★ 6<br>把一条 Reel 或 TikTok 改成 Instagram、TikTok、YouTube 各自合适的版本，重点改行动号召，再排期发出<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-10-30 · 英文</sub>

- **[Postey](https://github.com/posteyai/skills)** · ★ 6<br>Postey 的 MCP 和 skill：agent 起草、排期、发布到 X、LinkedIn、Instagram、TikTok 等 9 个平台，带数据和互动<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-21 · 英文 · 16 个 skill · MIT</sub><br><sub>💡 要 Postey 账号，连接免费</sub>

- **[claude-social-media-skills](https://github.com/michaellady/claude-social-media-skills)** · ★ 5<br>经 Buffer 推广自己作品的闭环：写帖时打格式标签、对抗式审稿、Buffer 分发，再按格式归因互动数据、给下周建议<br><sub>平台：YouTube · TikTok · LinkedIn · Threads · Newsletter</sub><br><sub>更新于 2026-11-09 · 英文 · 19 个 skill</sub><br><sub>💡 发帖走 Buffer，要 Buffer 账号</sub>

- **[Eason-Agent-Skills](https://github.com/EasonZhu1997/Eason-Agent-Skills)** · ★ 5<br>个人技能库：把 Word、TXT、Markdown 图文发到知乎、掘金、CSDN，另有手绘图解和架构图技能<br><sub>平台：知乎 · 通用</sub><br><sub>更新于 2026-11-05 · 中文 · 11 个 skill · MIT</sub>

- **[x-social-skill](https://github.com/baijunjie/x-social-skill)** · ★ 5<br>X 浏览器自动化：用你自己的 Chrome 发推、点赞、回复、转推、引用、搜索和删自己的推，每个项目可挂多个账号<br><sub>平台：X</sub><br><sub>更新于 2026-11-12 · 英文 · MIT</sub><br><sub>💡 每个账号手动登录一次，登录态存在 Chrome 配置里</sub>

- **[PostLake](https://github.com/PostLake/postlake-mcp)** · ★ 4<br>PostLake 的 MCP 和 skill：一个接口让 agent 在 9 个平台发布、排期、看数据、读评论和回复<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-14 · 英文 · 8 个 skill · MIT</sub><br><sub>💡 要 PostLake 账号，按积分计费</sub>

- **[brightbean-platform-agent](https://github.com/brightbeanxyz/brightbean-platform-agent)** · ★ 3<br>BrightBean 的 agent 接入：起草、排期、排队、发布和统计社媒帖子，附 MCP 和示例代码<br><sub>平台：YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-22 · 英文 · MIT</sub><br><sub>💡 要 BrightBean 账号</sub>

- **[wechat-publisher-pro](https://github.com/Readarkclub/wechat-publisher-pro)** · ★ 3<br>公众号文章生成、排版和发布：AI 生成封面，小红书风格排版，一键上传进草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-06 · 中文 · MIT</sub><br><sub>💡 要在公众号后台配 IP 白名单</sub>

- **[BulkPublish AI Toolkit](https://github.com/bulkpublish/bulkpublish-ai-toolkit)** · ★ 2<br>BulkPublish 的 skill 和 MCP：agent 排期发帖到 X、TikTok、Instagram、YouTube 等平台，管账号、回评论、看数据<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-20 · 英文 · 33 个 skill · MIT</sub><br><sub>💡 要 BulkPublish 账号和 API key（云服务，有免费档）；收件箱和回评论要付费档</sub>

- **[PostOnce](https://github.com/postoncehq/postonce-skills)** · ★ 1<br>PostOnce 官方 skill 和 MCP：经官方 API 把一条帖子或视频发到 TikTok、Instagram、YouTube 等 9 个平台，可定时<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-18 · 英文 · 6 个 skill · MIT</sub><br><sub>💡 要 PostOnce 账号（7 天免费试用），用 OAuth 连接，不需要 API key</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# social-auto-upload
npx skills add dreammis/social-auto-upload
# Wechatsync
npx skills add wechatsync/Wechatsync
# XiaohongshuSkills
npx skills add white0dew/XiaohongshuSkills
# autoclaw-cc/xiaohongshu-skills
npx skills add autoclaw-cc/xiaohongshu-skills
# MatrixMedia
npx skills add hanliang97/MatrixMedia
# x-article-publisher-skill
npx skills add wshuyi/x-article-publisher-skill
# social-push
npx skills add jihe520/social-push
# SyncCaster
npx skills add RyanYipeng/SyncCaster
# video-publisher-skill
npx skills add oil-oil/video-publisher-skill
# xiaohongshu-mcp-skills
npx skills add autoclaw-cc/xiaohongshu-mcp-skills
# Taisly Agent Kit
npx skills add taisly/agent
# wechat-article-publisher-skill
npx skills add iamzifei/wechat-article-publisher-skill
# Spreado
npx skills add BadKid90s/Spreado
# Linked-API/linkedin-skills
npx skills add Linked-API/linkedin-skills
# socialclaw
npx skills add ndesv21/socialclaw
# douyin-image-post-scheduler
npx skills add chengyi-ai/douyin-image-post-scheduler
# douyin-upload-mcp-skill
npx skills add WJZ-P/douyin-upload-mcp-skill
# publora/skills
npx skills add publora/skills
# douyin-skills
npx skills add zJay26/douyin-skills
# 0731coderlee-sudo/wechat-publisher
npx skills add 0731coderlee-sudo/wechat-publisher
# upload-post-skill
npx skills add Upload-Post/upload-post-skill
# douyin-mcp-server
npx skills add lancelin111/douyin-mcp-server
# Post Bridge
npx skills add post-bridge-hq/agent-mode
# social-publish-skills
npx skills add puppyfront-web/social-publish-skills
# postkitty
npx skills add mertkayacs/postkitty
# x-post-skill
npx skills add win4r/x-post-skill
# red-publisher-skill
npx skills add iamzifei/red-publisher-skill
# easypost
npx skills add gybin02/easypost
# twitterapi-io-skill
npx skills add dorukardahan/twitterapi-io-skill
# content-repurposer
npx skills add Mahanaicoach/content-repurposer
# Postey
npx skills add posteyai/skills
# claude-social-media-skills
npx skills add michaellady/claude-social-media-skills
# Eason-Agent-Skills
npx skills add EasonZhu1997/Eason-Agent-Skills
# x-social-skill
npx skills add baijunjie/x-social-skill
# PostLake
npx skills add PostLake/postlake-mcp
# brightbean-platform-agent
npx skills add brightbeanxyz/brightbean-platform-agent
# wechat-publisher-pro
npx skills add Readarkclub/wechat-publisher-pro
# BulkPublish AI Toolkit
npx skills add bulkpublish/bulkpublish-ai-toolkit
# PostOnce
npx skills add postoncehq/postonce-skills
```

</details>

<a id="group-research"></a>
### 选题、热点和数据分析

追热点、拆爆款、看竞品和评论，读账号数据。

- 🌟 **[last30days-skill](https://github.com/mvanhorn/last30days-skill)** · ★ 72.7k<br>查任意话题最近 30 天大家在说什么：Reddit、X、YouTube、TikTok、HN、Polymarket 等按点赞和真金白银排序，写成有出处的摘要<br><sub>平台：X · YouTube · TikTok · Reddit</sub><br><sub>更新于 2026-11-23 · 多语言 · MIT</sub>

- **[wechatDownload](https://github.com/qiye45/wechatDownload)** · ★ 10.1k<br>公众号文章批量下载：历史文章、评论、合集，存成 html/md/pdf/docx/csv，保存图片视频音频，支持 MCP 和 Skill 调用<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-01 · 中文</sub><br><sub>💡 skill 调用作者的桌面软件</sub>

- **[cheat-on-content](https://github.com/XBuilderLAB/cheat-on-content)** · ★ 7.6k<br>网红作弊器：发之前给稿子打分、盲猜数据，发后 3 天拿真实数据复盘，连错几次就提示改评分标准；内置观点类视频评分表，能读抖音、小红书、视频号、B 站后台数据<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · LinkedIn</sub><br><sub>更新于 2026-11-16 · 中文 · 16 个 skill · MIT</sub><br><sub>💡 读平台数据要在本地浏览器登录各创作者后台，登录态存在本地</sub>

- **[follow-builders](https://github.com/zarazhangrui/follow-builders)** · ★ 7.2k<br>AI 圈一线建设者摘要：追踪 X 上的研究员、创始人和 YouTube 播客，按天或周推送整理好的要点<br><sub>平台：X · YouTube</sub><br><sub>更新于 2026-11-22 · 英文</sub>

- **[social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills)** · ★ 7k<br>社媒调研：找超常爆款、挖评论、拆竞品、看广告库和趋势，覆盖 TikTok、Instagram、YouTube、Reddit、X、LinkedIn<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Reddit</sub><br><sub>更新于 2026-08-26 · 英文 · 13 个 skill · MIT</sub><br><sub>💡 数据来自 ScrapeCreators，要它的 API Key（付费）</sub>

- **[claude-real-video](https://github.com/HUANGCHIHHUNGLeo/claude-real-video)** · ★ 2.3k<br>让 AI 看视频：从链接或本地文件抽场景关键帧并去重、配时间戳字幕，用来总结和拆解对标视频，本地运行<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-20 · 英文 · 3 个 skill · MIT</sub>

- **[last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn)** · ★ 2.2k<br>中文版近 30 天研究：微博、小红书、B站、知乎、抖音、公众号、百度、头条 8 个平台并行检索，按互动和时效排序，结论都有出处<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · 微博 · 知乎 · 头条</sub><br><sub>更新于 2026-11-20 · 中文 · 2 个 skill</sub>

- **[chubbyskills](https://github.com/chubbyguan/chubbyskills)** · ★ 1.3k<br>把抖音、B站、小红书、公众号、X、播客内容存进个人知识库：图文存图、视频转文字稿、订阅和每日简报，附知识库 MCP<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · X</sub><br><sub>更新于 2026-10-14 · 中文 · 14 个 skill · MIT</sub>

- **[x-research-skill](https://github.com/rohunvora/x-research-skill)** · ★ 1.2k<br>X 调研：搜索按互动排序、跟帖、监控账号，输出带出处的简报<br><sub>平台：X</sub><br><sub>更新于 2026-02-19 💤 · 英文</sub><br><sub>💡 要自己的 X API 凭证（按量付费）</sub>

- **[ZeroPointRepo/youtube-skills](https://github.com/ZeroPointRepo/youtube-skills)** · ★ 1.2k<br>YouTube 字幕、搜索视频、浏览频道和播放列表，走 TranscriptAPI<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-03 · 英文 · 12 个 skill · MIT</sub><br><sub>💡 要 TranscriptAPI 的 API Key</sub>

- **[wechat-article-to-markdown](https://github.com/jackwener/wechat-article-to-markdown)** · ★ 1.1k<br>公众号文章抓取转 Markdown：防检测抓取，提取标题、作者、时间，图片存本地<br><sub>平台：公众号</sub><br><sub>更新于 2026-03-22 💤 · 多语言</sub>

- **[x-tweet-fetcher](https://github.com/ythx-101/x-tweet-fetcher)** · ★ 1k<br>不登录、不用 API Key 抓 X 推文、回复、时间线、列表和长文，三种后端自动切换<br><sub>平台：X</sub><br><sub>更新于 2026-11-12 · 英文 · MIT</sub>

- **[autocli-skill](https://github.com/nashsu/autocli-skill)** · ★ 938<br>让 agent 用 autocli 读 55+ 个网站：B站、知乎、X、YouTube、微博、Reddit、小红书等，复用你 Chrome 的登录态<br><sub>平台：小红书 · B 站 · 微博 · 知乎 · X · YouTube · Reddit</sub><br><sub>更新于 2026-04-20 💤 · 多语言</sub>

- **[blogger-distiller](https://github.com/otter1101/blogger-distiller)** · ★ 802<br>博主蒸馏器：输入博主账号，从真实笔记里蒸馏 TA 的爆款打法和认知，装进你的 AI 当内容教练<br><sub>平台：小红书 · 抖音</sub><br><sub>更新于 2026-09-23 · 中文 · MIT</sub>

- **[union-search-skill](https://github.com/runningZ1/union-search-skill)** · ★ 777<br>统一搜索：一条命令搜小红书、抖音、B站、YouTube、X、公众号、Reddit 等 20+ 平台，输出统一格式<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · 微博 · 知乎 · 头条 · X · YouTube · Reddit</sub><br><sub>更新于 2026-11-10 · 中文 · MIT</sub>

- **[NewsCrawler](https://github.com/NanmiCoder/NewsCrawler)** · ★ 644<br>新闻和内容提取 skill：给一条链接拿到正文、图片和元数据，支持公众号、头条、X、网易、腾讯新闻等 12 个平台<br><sub>平台：公众号 · 头条 · X</sub><br><sub>更新于 2026-08-08 · 中文 · GPL-3.0</sub>

- **[feedgrab](https://github.com/iBigQiang/feedgrab)** · ★ 623<br>18+ 平台内容抓取：输入链接或关键词批量抓 X、小红书、公众号、YouTube、B站等，输出带元数据的 Obsidian Markdown<br><sub>平台：小红书 · 公众号 · B 站 · X · YouTube</sub><br><sub>更新于 2026-10-24 · 中文 · 5 个 skill · MIT</sub>

- **[redfox-community](https://github.com/redfox-data/redfox-community)** · ★ 470<br>红狐数据的 132 个 skill：多平台主页视频提取、B站评论分析、AI 信息日报、选题、文案和数据复盘<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · 快手 · 头条 · X · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-06 · 中文 · 133 个 skill</sub>

- **[xhs-claude-skills](https://github.com/chenxiachan/xhs-claude-skills)** · ★ 435<br>小红书转 Obsidian：提取帖子文字、图片 OCR、视频字幕或转录，批量入库后做总结对比，也能做封面<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-14 · 中文 · 4 个 skill · MIT</sub>

- **[social-account-doctor](https://github.com/JuneYaooo/social-account-doctor)** · ★ 388<br>自媒体账号体检和爆款拆解：扫同赛道找对标、拆爆款为什么爆、诊断没人看的原因，顺手出仿写初稿，支持带货模式<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手</sub><br><sub>更新于 2026-09-19 · 中文 · MIT</sub>

- **[twitterapi-io](https://github.com/kaitoInfra/twitterapi-io)** · ★ 336<br>twitterapi.io 官方 skill：查推文、主页、粉丝、高级搜索、趋势，也能发帖等操作<br><sub>平台：X</sub><br><sub>更新于 2026-10-14 ⚠️ · 英文 · 2 个 skill · MIT</sub><br><sub>💡 twitterapi.io 按量付费</sub>

- **[head-of-content](https://github.com/bradautomates/head-of-content)** · ★ 332<br>内容调研同事：在 X、Instagram、YouTube、TikTok 上找表现好的内容，拆共性，做内容计划<br><sub>平台：X · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-01-23 💤 · 英文 · 6 个 skill · MIT</sub><br><sub>💡 抓数据用 Apify，按用量付费</sub>

- **[ai-influence-digest](https://github.com/koffuxu/ai-influence-digest)** · ★ 321<br>AI 影响力周报：用浏览器扫 65+ 个 AI 建设者过去 7 天的推文，筛出创作者能立刻用的工具和方法，导出海报<br><sub>平台：X</sub><br><sub>更新于 2026-04-18 💤 · 中文 · MIT</sub>

- **[TubeLab](https://github.com/TubeLabHQ/youtube-research-skills)** · ★ 311<br>TubeLab 的 YouTube 研究 skill：找爆款视频和赛道、验证赛道、拆竞品、挖评论、标题和缩略图、变现缺口和找赞助<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-21 · 英文 · 17 个 skill · MIT</sub><br><sub>💡 要 TubeLab 账号</sub>

- **[lingzao-skill](https://github.com/atian-create/lingzao-skill)** · ★ 308<br>灵造：小红书为主的公开内容研究，账号诊断、找对标、拆爆款、标题封面优化、仿写模板，也覆盖抖音和公众号<br><sub>平台：小红书 · 抖音 · 公众号</sub><br><sub>更新于 2026-07-02 · 中文 · 12 个 skill · MIT-0</sub>

- **[bigpeng-hot-gzh](https://github.com/BigPengSays/bigpeng-hot-gzh)** · ★ 290<br>公众号选题和标题：从约 100 篇 AI 爆款文章拆出 7 种标题公式和 8 个选题模板，只做选题和标题<br><sub>平台：公众号</sub><br><sub>更新于 2026-08-19 · 中文 · MIT</sub>

- **[video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill)** · ★ 264<br>短视频转字幕加 AI 总结：抖音、小红书、B 站、YouTube 链接或本地音视频，faster-whisper 本地转写<br><sub>平台：小红书 · 抖音 · B 站 · YouTube</sub><br><sub>更新于 2026-11-15 · 中文 · MIT</sub><br><sub>💡 抖音、小红书、B 站要配视频解析接口：作者推荐的 top9.cc（新用户有免费额度）或 TikHub</sub>

- **[social-media-data-tools](https://github.com/jinchenma94/social-media-data-tools)** · ★ 259<br>抖音博主和视频导出：标题、文案、完整逐字稿和互动数据，可写入飞书多维表格；要在豆包里运行<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-14 · 中文</sub>

- **[ah-douyin-clean-downloader](https://github.com/ahang008/ah-douyin-clean-downloader)** · ★ 257<br>抖音原视频下载和逐字稿：归档博主公开作品和指标，可按点赞批量改写口播稿，只用于自有或已授权内容<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-14 · 中文</sub>

- **[x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper)** · ★ 229<br>Xquik 的 X 数据：搜索、主页、粉丝、回复、时间线、媒体下载，带远程 MCP<br><sub>平台：X</sub><br><sub>更新于 2026-11-18 · 英文 · 3 个 skill · MIT</sub><br><sub>💡 Xquik 是付费服务</sub>

- **[jev-social](https://github.com/socai-io/jev-social)** · ★ 220<br>社媒调研 agent：在你已登录的 Chrome 里搜 Instagram、TikTok、LinkedIn 的帖子、主页和评论，出带出处的报告，只读不发<br><sub>平台：TikTok · Instagram · LinkedIn</sub><br><sub>更新于 2026-11-08 · 英文 · MIT</sub><br><sub>💡 要装 socai CLI；默认模型走 OpenRouter，要它的 API Key</sub>

- **[tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill)** · ★ 145<br>TikHub API 助手：帮 agent 查找和调用抖音、TikTok、小红书、Instagram、YouTube、X、Reddit 等平台的数据接口<br><sub>平台：小红书 · 抖音 · X · YouTube · TikTok · Instagram · Reddit</sub><br><sub>更新于 2026-11-15 · 中文</sub><br><sub>💡 TikHub 是付费数据接口</sub>

- **[wechat-article-extractor-skill](https://github.com/freestylefly/wechat-article-extractor-skill)** · ★ 144<br>从公众号文章链接提取标题、作者、正文、封面和公众号信息，支持图文、视频、图片集、语音和转载<br><sub>平台：公众号</sub><br><sub>更新于 2026-02-19 💤 · 中文</sub>

- **[openclaw-xhs](https://github.com/zhjiang22/openclaw-xhs)** · ★ 127<br>让 OpenClaw 读懂你的小红书：MCP 搜索浏览评论、热点报告、把收藏导出成个人记忆库<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-08 📦 · 中文</sub>

- **[hook-lab](https://github.com/hongfamonvAI/hook-lab)** · ★ 116<br>拆解 TikTok、Reels、Shorts 爆款：数据面板、钩子和脚本结构、为什么能火，给出改编到小红书和视频号的方向<br><sub>平台：小红书 · 视频号 · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-06-11 · 中文 · MIT</sub>

- **[Autody](https://github.com/kizzhang/autody)** · ★ 104<br>给一个主题，自动搜小红书和抖音、读作品和评论，整理受众问题和选题，也能复盘自己的抖音号<br><sub>平台：小红书 · 抖音</sub><br><sub>更新于 2026-10-30 · 中文 · 10 个 skill · MIT</sub><br><sub>💡 用 Codex 的 Chrome 扩展，要在 Chrome 登录两个平台</sub>

- **[wechat-search-weread](https://github.com/KANIKIG/wechat-search-weread)** · ★ 89<br>搜公众号文章：通过微信读书搜一搜拿最新文章的标题、公众号、时间、简介和直链，不抓正文<br><sub>平台：公众号</sub><br><sub>更新于 2026-06-09 · 中文</sub><br><sub>💡 要登录微信读书</sub>

- **[youtube-scout](https://github.com/AgriciDaniel/youtube-scout)** · ★ 83<br>YouTube 选题调研：输入一个话题，按播放、互动或爆发度排出视频和频道，导出含评论、字幕和钩子的 Excel 表<br><sub>平台：YouTube</sub><br><sub>更新于 2026-10-30 · 英文 · MIT</sub><br><sub>💡 要 YouTube Data API Key</sub>

- **[Mira](https://github.com/Mira-AI-Tools/mira-skill)** · ★ 73<br>Mira：让 Claude 和 ChatGPT 看懂 TikTok、Reels 和 Shorts 链接，拿回口播转写、画面文字、配文和结构化摘要<br><sub>平台：X · YouTube · TikTok · Instagram · Facebook · Pinterest</sub><br><sub>更新于 2026-11-22 · 英文 · MIT</sub><br><sub>💡 要 Mira 账号</sub>

- **[ScrapeIO](https://github.com/xhoantran/scrapeio-agent)** · ★ 68<br>ScrapeIO 社媒研究 skill：找达人和查假粉、竞品审计、视频转写、评论洞察、趋势和广告库，附 33 个平台的 MCP<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Facebook · Reddit</sub><br><sub>更新于 2026-11-07 · 英文 · 8 个 skill · MIT</sub><br><sub>💡 要 ScrapeIO 的 API key，有免费额度</sub>

- **[x-ai-topic-selector](https://github.com/vigorX777/x-ai-topic-selector)** · ★ 59<br>从 X 列表、首页或书签抓推文，按互动数据和 AI 多维打分，出选题推荐报告<br><sub>平台：X</sub><br><sub>更新于 2026-02-20 💤 · 中文</sub><br><sub>💡 AI 评分和书签模式要 Gemini API Key</sub>

- **[dissect](https://github.com/0xpratzyy/dissect)** · ★ 56<br>dissect：把任何视频逐帧拆成可照做的蓝图，镜头、转场、运镜和节奏都量化，再给你的翻拍版打分<br><sub>平台：X · YouTube · TikTok · Instagram · Facebook · Reddit</sub><br><sub>更新于 2026-11-11 · 英文 · MIT</sub>

- **[self-media-guide](https://github.com/lonely-dance-lab/self-media-guide)** · ★ 53<br>爆款对标分析：给一条或几条视频，看懂它为什么火、值不值得对标、怎么换成自己的内容，出完整报告<br><sub>平台：小红书 · 抖音 · B 站 · YouTube</sub><br><sub>更新于 2026-11-20 · 中文 · MIT</sub>

- **[xiaohongshu-summarizer-skill](https://github.com/piekill/xiaohongshu-summarizer-skill)** · ★ 45<br>小红书搜索和总结：按关键词抓前 N 篇笔记的文字、图片和评论，合成一份调研报告<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-10 💤 · 中文</sub>

- **[youtube-transcript-skills](https://github.com/tubeagentkit/youtube-transcript-skills)** · ★ 41<br>YouTube 字幕 skill：取字幕、搜视频和频道、翻频道的上传和播放列表、按时间点找原话<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-20 · 英文 · MIT</sub><br><sub>💡 要它家的 API key：注册送 100 次免费额度、不用绑卡，之后每月 5 美元起 1,000 次</sub>

- **[redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill)** · ★ 36<br>红狐数据接口 skill：让 agent 查到并调用 201 个接口，覆盖抖音、小红书、公众号、B 站、视频号、TikTok、YouTube 等<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · 微博 · 知乎 · 快手 · 头条 · X · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-15 · 中文</sub><br><sub>💡 要红狐数据的 API key，按积分计费</sub>

- **[ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills)** · ★ 28<br>ScrapeAtlas 社媒研究 skill：找爆款帖、挖评论、转写分析、钩子库、拆竞品广告、找达人和舆情监听<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-11-19 · 英文 · 17 个 skill · MIT</sub><br><sub>💡 数据来自 ScrapeAtlas 接口，要 API key</sub>

- **[xhs-creator-distill](https://github.com/aiiqc/xhs-creator-distill)** · ★ 20<br>从 3 到 8 篇代表笔记或整号资料里，提炼有证据、可迁移的小红书创作者内容方法<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-31 · 中文 · MIT</sub>

- **[xiaohongshu-openclaw-skill](https://github.com/um-why/xiaohongshu-openclaw-skill)** · ★ 18<br>小红书洞察：按关键词搜笔记、看详情、拉评论和博主作品，输出 JSON，用来选题、盯竞品、筛 KOL，不登录账号<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-18 · 中文 · MIT</sub><br><sub>💡 要第三方数据 token，按量或包月付费</sub>

- **[openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news)** · ★ 14<br>每日热榜：查微博、知乎、B 站、抖音等 54 个平台的热榜，跨平台聚合，支持定时推送<br><sub>平台：抖音 · B 站 · 微博 · 知乎 · 快手 · 头条</sub><br><sub>更新于 2026-02-06 💤 · 中文 · MIT</sub>

- **[红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh)** · ★ 13<br>红狐数据给 DeepSeek Harness 的官方插件包：100 多个自媒体数据 skill，搜内容、追热点、分析评论、诊断账号<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · 微博 · 知乎 · 快手 · 头条 · X · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-06 · 中文 · 133 个 skill · MIT</sub><br><sub>💡 要红狐数据的 API key，按积分计费</sub>

- **[sourceboard](https://github.com/aaronyi97/sourceboard)** · ★ 8<br>信源看板：让 agent 按关键词搜、按链接抓抖音、小红书、B 站、公众号等平台的内容和评论，每次自动摆成网页看板<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · 微博 · 知乎 · X · YouTube · TikTok · Reddit</sub><br><sub>更新于 2026-11-11 ⚠️ · 中文 · Apache-2.0</sub><br><sub>💡 多数平台数据走 TikHub，要自己注册充值，按次付费</sub>

- **[instagram-ai-agent-skills](https://github.com/apismith-labs/instagram-ai-agent-skills)** · ★ 7<br>Instagram 公开视频的几个 skill：提取逐字稿、读帖子数据、按天或周盘点指定创作者的 Reels<br><sub>平台：Instagram</sub><br><sub>更新于 2026-11-13 · 英文 · 3 个 skill · MIT</sub><br><sub>💡 通过 Apify 抓数据</sub>

- **[apidojo-io/social-media-skills](https://github.com/apidojo-io/social-media-skills)** · ★ 6<br>批量抓 X、TikTok、Instagram 公开数据：推文、主页、话题、评论，不用登录<br><sub>平台：X · TikTok · Instagram</sub><br><sub>更新于 2026-09-02 · 英文 · 3 个 skill</sub><br><sub>💡 跑在 Apify 上，按用量付费</sub>

- **[SocialDataX](https://github.com/DevinChen2014/socialdatax-skills)** · ★ 6<br>社媒数据助手 SocialDataX：小红书、抖音、快手、B 站、公众号等平台的内容研究、评论洞察、账号分析和竞品调研<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · 微博 · 知乎 · 快手 · 头条 · X · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-20 · 多语言 · 73 个 skill · MIT</sub><br><sub>💡 要 SocialDataX 账号，按余额计费</sub>

- **[Virlo-Agent-Plugin](https://github.com/Virlo-AI/Virlo-Agent-Plugin)** · ★ 6<br>Virlo 官方插件：查 TikTok、Shorts、Reels 上的热门内容，拆爆款原因，查创作者和热门音乐话题<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-07 · 英文 · 2 个 skill · MIT</sub><br><sub>💡 要 Virlo 账号</sub>

- **[x-monitor](https://github.com/ythx-101/x-monitor)** · ★ 5<br>X 评论监控：免登录抓某条推文的回复，标出提问，watch 模式只报新评论，输出 JSON 给 agent 起草回答<br><sub>平台：X</sub><br><sub>更新于 2026-11-12 · 英文 · MIT</sub>

- **[blogger-video-pipeline](https://github.com/caodoris471/blogger-video-pipeline)** · ★ 4<br>对标博主视频批量采集：定位账号、筛选下载、本地转写、提炼观点、改写脚本，统一归档<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手 · YouTube · TikTok</sub><br><sub>更新于 2026-11-05 · 中文</sub><br><sub>💡 按 WorkBuddy 和 Windows 写的，用别的 agent 要自己适配</sub>

- **[douyin-search-openclaw](https://github.com/um-why/douyin-search-openclaw)** · ★ 4<br>抖音公开数据搜索：搜视频、图文和用户，看博主作品、作品详情、评论和实时热榜，输出 JSON，不登录账号<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-18 · 中文</sub><br><sub>💡 要第三方数据 token，按量或包月付费</sub>

- **[HookLab](https://github.com/CoolerGit/HookLab)** · ★ 4<br>HookLab：拆 TikTok、Reels、Shorts 的开头钩子，按清单打分，判断人群和赛道，抽留存手法，存进可搜的素材库<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-13 · 英文 · 5 个 skill · Apache-2.0</sub>

- **[instagram-list-inspector](https://github.com/GreedyC/instagram-list-inspector)** · ★ 4<br>在已登录的浏览器里对比 Instagram 名单：粉丝和关注、互关、没回关、点赞的人和重复点赞者，只读<br><sub>平台：Instagram</sub><br><sub>更新于 2026-10-31 · 英文 · MIT</sub>

- **[youtube-skillbox](https://github.com/hackers-reality/youtube-skillbox)** · ★ 4<br>YouTube 免费工具箱：搜索、字幕、社区帖和首页分区，加脚本、钩子、SEO、章节和频道审计等 10 个创作工具，不要 API key<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-16 · 英文 · 15 个 skill · MIT</sub>

- **[darkniche](https://github.com/darksemfiltro/darkniche)** · ★ 3<br>YouTube 细分赛道分析：给一个赛道、点子、频道或视频，用真实数据和当天的网页调研给出做、试或避开<br><sub>平台：YouTube</sub><br><sub>更新于 2026-10-30 · 葡萄牙文 · MIT</sub><br><sub>💡 要 YouTube Data API key</sub>

- **[douyin-social](https://github.com/why20261/douyin-social)** · ★ 3<br>抖音社媒运营：串起热搜、关键词搜视频和达人主页数据，做热点选题、拆爆款卖点、匹配粉丝画像、排内容日历<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-12 · 中文 · MIT</sub><br><sub>💡 要第三方数据 token，按量或包月付费</sub>

- **[qianjin-wechat-analyzer](https://github.com/ZOORO-NEW/qianjin-wechat-analyzer)** · ★ 3<br>公众号运营诊断：用后台真实数据和全部文章量化 20 个内容特征，对比爆文和普通文，分层对标，每条建议带证据<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-12 · 中文</sub>

- **[ScraperSocial](https://github.com/nikhonit/social-media-api-skills)** · ★ 3<br>ScraperSocial 接口 skill：一个 key 读 32 个平台的公开数据，如 TikTok 转写、LinkedIn 资料、YouTube 评论<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Facebook · Reddit</sub><br><sub>更新于 2026-11-11 · 英文 · 34 个 skill · MIT-0</sub><br><sub>💡 要 ScraperSocial 的 key，注册送 25 积分</sub>

- **[viral-structure-teardown](https://github.com/JuneYaooo/viral-structure-teardown)** · ★ 3<br>爆款结构拆解：把对标视频字幕拆成钩子、留人、转折、转化的时间轴，攒成模板，给新脚本定落点<br><sub>平台：通用</sub><br><sub>更新于 2026-11-03 · 中文 · Apache-2.0</sub>

- **[viral-tiktok-skills](https://github.com/maxxyart/viral-tiktok-skills)** · ★ 3<br>Viral Camp：研究 Instagram 和 TikTok 账号数据、封面钩子和评论，拆竞品 Facebook 广告，改编成你的轮播和视频<br><sub>平台：TikTok · Instagram · Facebook</sub><br><sub>更新于 2026-11-19 · 英文 · 11 个 skill · MIT</sub><br><sub>💡 数据走 ScrapeCreators，要 API key</sub>

- **[youtube-outliers-claude-code](https://github.com/BrandonChin827/youtube-outliers-claude-code)** · ★ 3<br>找你关注的 YouTube 创作者里表现异常好的视频，按话题归类，拆最适合你的五条变成选题<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-03 · 英文 · MIT</sub><br><sub>💡 要 ScrapeCreators 的 API key</sub>

- **[douyin-video-summary](https://github.com/liu-wei-ai/douyin-video-summary)** · ★ 2<br>OpenClaw 抖音视频总结：提取音频、whisper.cpp 转写、生成结构化摘要，可同步到飞书文档<br><sub>平台：抖音</sub><br><sub>更新于 2026-02-10 💤 · 英文</sub>

- **[okdata skills](https://github.com/okdataapi/skills)** · ★ 0<br>社媒和电商调研：竞品动态、评论口碑、品牌提及、热点、达人、字幕、广告和商品评价，抖音、小红书、公众号、B 站、微博、TikTok、YouTube、X 等都能查<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · 微博 · 知乎 · 快手 · X · YouTube · TikTok · Instagram · Reddit</sub><br><sub>更新于 2026-11-22 · 多语言 · 35 个 skill · MIT</sub><br><sub>💡 要 okdata API key，按次计费</sub>

- **[skillify-sh/skills](https://github.com/skillify-sh/skills)** · ★ 0<br>抓 Instagram 公开数据，不要登录，花钱前先告诉你费用<br><sub>平台：Instagram</sub><br><sub>更新于 2026-08-23 · 英文 · MIT</sub><br><sub>💡 按次付费的数据服务</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# last30days-skill
npx skills add mvanhorn/last30days-skill
# wechatDownload
npx skills add qiye45/wechatDownload
# cheat-on-content
npx skills add XBuilderLAB/cheat-on-content
# follow-builders
npx skills add zarazhangrui/follow-builders
# social-media-research-skills
npx skills add ScrapeCreators/social-media-research-skills
# claude-real-video
npx skills add HUANGCHIHHUNGLeo/claude-real-video
# last30days-skill-cn
npx skills add Jesseovo/last30days-skill-cn
# chubbyskills
npx skills add chubbyguan/chubbyskills
# x-research-skill
npx skills add rohunvora/x-research-skill
# ZeroPointRepo/youtube-skills
npx skills add ZeroPointRepo/youtube-skills
# wechat-article-to-markdown
npx skills add jackwener/wechat-article-to-markdown
# x-tweet-fetcher
npx skills add ythx-101/x-tweet-fetcher
# autocli-skill
npx skills add nashsu/autocli-skill
# blogger-distiller
npx skills add otter1101/blogger-distiller
# union-search-skill
npx skills add runningZ1/union-search-skill
# NewsCrawler
npx skills add NanmiCoder/NewsCrawler
# feedgrab
npx skills add iBigQiang/feedgrab
# redfox-community
npx skills add redfox-data/redfox-community
# xhs-claude-skills
npx skills add chenxiachan/xhs-claude-skills
# social-account-doctor
npx skills add JuneYaooo/social-account-doctor
# twitterapi-io
npx skills add kaitoInfra/twitterapi-io
# head-of-content
npx skills add bradautomates/head-of-content
# ai-influence-digest
npx skills add koffuxu/ai-influence-digest
# TubeLab
npx skills add TubeLabHQ/youtube-research-skills
# lingzao-skill
npx skills add atian-create/lingzao-skill
# bigpeng-hot-gzh
npx skills add BigPengSays/bigpeng-hot-gzh
# video-to-subtitle-summary-skill
npx skills add imlewc/video-to-subtitle-summary-skill
# social-media-data-tools
npx skills add jinchenma94/social-media-data-tools
# ah-douyin-clean-downloader
npx skills add ahang008/ah-douyin-clean-downloader
# x-twitter-scraper
npx skills add Xquik-dev/x-twitter-scraper
# jev-social
npx skills add socai-io/jev-social
# tikhub_api_skill
npx skills add liangdabiao/tikhub_api_skill
# wechat-article-extractor-skill
npx skills add freestylefly/wechat-article-extractor-skill
# openclaw-xhs
npx skills add zhjiang22/openclaw-xhs
# hook-lab
npx skills add hongfamonvAI/hook-lab
# Autody
npx skills add kizzhang/autody
# wechat-search-weread
npx skills add KANIKIG/wechat-search-weread
# youtube-scout
npx skills add AgriciDaniel/youtube-scout
# Mira
npx skills add Mira-AI-Tools/mira-skill
# ScrapeIO
npx skills add xhoantran/scrapeio-agent
# x-ai-topic-selector
npx skills add vigorX777/x-ai-topic-selector
# dissect
npx skills add 0xpratzyy/dissect
# self-media-guide
npx skills add lonely-dance-lab/self-media-guide
# xiaohongshu-summarizer-skill
npx skills add piekill/xiaohongshu-summarizer-skill
# youtube-transcript-skills
npx skills add tubeagentkit/youtube-transcript-skills
# redfox_api_skill
npx skills add liangdabiao/redfox_api_skill
# ScrapeAtlas
npx skills add ScrapeAtlas/social-media-agent-skills
# xhs-creator-distill
npx skills add aiiqc/xhs-creator-distill
# xiaohongshu-openclaw-skill
npx skills add um-why/xiaohongshu-openclaw-skill
# openclaw-daily-hot-news
npx skills add one-box-u/openclaw-daily-hot-news
# 红狐数据 DSH 插件包
npx skills add redfox-data/redfox-community-dsh
# sourceboard
npx skills add aaronyi97/sourceboard
# instagram-ai-agent-skills
npx skills add apismith-labs/instagram-ai-agent-skills
# apidojo-io/social-media-skills
npx skills add apidojo-io/social-media-skills
# SocialDataX
npx skills add DevinChen2014/socialdatax-skills
# Virlo-Agent-Plugin
npx skills add Virlo-AI/Virlo-Agent-Plugin
# x-monitor
npx skills add ythx-101/x-monitor
# blogger-video-pipeline
npx skills add caodoris471/blogger-video-pipeline
# douyin-search-openclaw
npx skills add um-why/douyin-search-openclaw
# HookLab
npx skills add CoolerGit/HookLab
# instagram-list-inspector
npx skills add GreedyC/instagram-list-inspector
# youtube-skillbox
npx skills add hackers-reality/youtube-skillbox
# darkniche
npx skills add darksemfiltro/darkniche
# douyin-social
npx skills add why20261/douyin-social
# qianjin-wechat-analyzer
npx skills add ZOORO-NEW/qianjin-wechat-analyzer
# ScraperSocial
npx skills add nikhonit/social-media-api-skills
# viral-structure-teardown
npx skills add JuneYaooo/viral-structure-teardown
# viral-tiktok-skills
npx skills add maxxyart/viral-tiktok-skills
# youtube-outliers-claude-code
npx skills add BrandonChin827/youtube-outliers-claude-code
# douyin-video-summary
npx skills add liu-wei-ai/douyin-video-summary
# okdata skills
npx skills add okdataapi/skills
# skillify-sh/skills
npx skills add skillify-sh/skills
```

</details>

<a id="group-strategy"></a>
### 账号定位和增长

定人设和赛道、做内容规划、涨粉和变现的方法。

- 🌟 **[dbskill](https://github.com/dontbesilent2025/dbskill)** · ★ 11.5k<br>dontbesilent 的 skill 工具箱：商业诊断、选对标、把选题做成内容方案、写标题封面和开头、发布前查违规，另有查 AI 味的三件套<br><sub>平台：通用</sub><br><sub>更新于 2026-11-17 · 中文 · 38 个 skill</sub>

- **[x-mentor-skill](https://github.com/alchaincyf/x-mentor-skill)** · ★ 1.3k<br>X 运营导师：蒸馏 Dan Koe、Justin Welsh 等 6 位创作者的方法和开源算法资料，管选题、写推文和长文、账号诊断和增长<br><sub>平台：X</sub><br><sub>更新于 2026-10-13 · 中文 · MIT</sub>

- **[xhs-virtual-product](https://github.com/chenjin-cmd/xhs-virtual-product)** · ★ 902<br>小红书虚拟资料生意：选品、对标、制作、上架、发内容、复盘 7 步，附模板和版权合规红线<br><sub>平台：小红书</sub><br><sub>更新于 2026-09-30 · 中文 · MIT</sub>

- **[xiaohongshu-ai-workbench](https://github.com/mengke-wang/xiaohongshu-ai-workbench)** · ★ 639<br>《小红书运营手册》配套的 Codex skill：标题、主页、选题、评论区回复和成交路径，作者是《爆款》作者王梦珂<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-07 · 中文 · 7 个 skill · MIT</sub>

- **[agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_)** · ★ 610<br>起号专家：视频号、抖音、公众号、小红书和中文 X 账号从 0 到 1，定位、选题、脚本、小样本实验、复盘和 30 天计划<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · X</sub><br><sub>更新于 2026-07-08 · 中文 · 5 个 skill · MIT</sub>

- **[vivy-yi/xiaohongshu-skills](https://github.com/vivy-yi/xiaohongshu-skills)** · ★ 566<br>小红书运营知识库 139 个 skill：内容创作、账号运营、互动、数据分析、电商转化、平台规则和增长策略<br><sub>平台：小红书</sub><br><sub>更新于 2026-01-23 💤 · 中文 · 9 个 skill</sub>

- **[nova-youtube-agent](https://github.com/sharbelxyz/nova-youtube-agent)** · ★ 394<br>YouTube 增长 agent：扫竞品、分析频道、想选题、写脚本、追踪表现并按反馈改进，给 Hermes 和 OpenClaw 用<br><sub>平台：YouTube</sub><br><sub>更新于 2026-07-06 · 英文</sub>

- **[hattip-linkedin-os](https://github.com/ChristianDiBratto25/hattip-linkedin-os)** · ★ 139<br>在 Claude 应用里跑的 LinkedIn 运营系统：访谈你的业务，定漏斗策略，排一个月选题，按你的口吻写帖<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-10-30 · 英文 · MIT</sub>

- **[Eva-skill](https://github.com/Lulu-Eva/Eva-skill)** · ★ 64<br>创作者思考陪练：把模糊想法理成有依据的判断，做账号阶段定位、挑题，再写成短视频或非虚构文章，带新手教程和稿件批改<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号</sub><br><sub>更新于 2026-09-19 · 中文 · 13 个 skill</sub><br><sub>💡 个人非商业使用免费；用于获客或商业推广可能要授权</sub>

- **[LinkedInOptimizer](https://github.com/GodModeAI2025/LinkedInOptimizer)** · ★ 17<br>德语的 LinkedIn 主页诊断和优化：分八步，给顾问和代理商把客户定位成行业意见领袖<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-11-01 · 德文 · MIT</sub>

- **[factum-skills](https://github.com/enricpedro/factum-skills)** · ★ 15<br>YouTube 变现申诉：频道因重复使用内容或内容重复被拒、停用时，帮你选申诉路线，写申诉视频脚本，备齐审核材料<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-20 · 英文</sub>

- **[linkedin-positioning-panel](https://github.com/jeterchou/linkedin-positioning-panel)** · ★ 7<br>LinkedIn 个人资料评审：七个视角看职业定位，追踪证据，改写时不编事实，分清个人、团队和合作成果<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-11-16 · 英文 · MIT</sub>

- **[for-you-skills](https://github.com/alexliyu7352/for-you-skills)** · ★ 3<br>X 推荐算法 skill：从开源推荐代码整理 578 条知识，审帖、选帖子还是长文、核查涨粉说法、诊断流量变化<br><sub>平台：X</sub><br><sub>更新于 2026-11-09 · 多语言 · 8 个 skill · MIT</sub>

- **[jianghushuo-skill](https://github.com/zhoutian1995/jianghushuo-skill)** · ★ 3<br>非官方自媒体行动系统：参考姜胡说的公开方法，做个人 IP 诊断、从真实经历提炼选题、写内容、复盘和沉淀方法卡<br><sub>平台：小红书 · 抖音 · 视频号</sub><br><sub>更新于 2026-11-15 · 中文 · MIT</sub>

- **[account-diagnosis-skill](https://github.com/Jian21311/account-diagnosis-skill)** · ★ 0<br>账号诊断规则：先看手上有哪些数据再定怎么判，六个维度分三档，不给总分，只指出最该改的一件；没有播放量就不算完播率<br><sub>平台：小红书 · 抖音 · B 站</sub><br><sub>更新于 2026-11-16 · 中文</sub><br><sub>💡 规范文档，不是自动化工具：只给判断规则，不抓数据；附 80 条抖音公开作品样本可以逐条复算</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# dbskill
npx skills add dontbesilent2025/dbskill
# x-mentor-skill
npx skills add alchaincyf/x-mentor-skill
# xhs-virtual-product
npx skills add chenjin-cmd/xhs-virtual-product
# xiaohongshu-ai-workbench
npx skills add mengke-wang/xiaohongshu-ai-workbench
# agent-skills-launch-pack_
npx skills add chenjin-cmd/agent-skills-launch-pack_
# vivy-yi/xiaohongshu-skills
npx skills add vivy-yi/xiaohongshu-skills
# nova-youtube-agent
npx skills add sharbelxyz/nova-youtube-agent
# hattip-linkedin-os
npx skills add ChristianDiBratto25/hattip-linkedin-os
# Eva-skill
npx skills add Lulu-Eva/Eva-skill
# LinkedInOptimizer
npx skills add GodModeAI2025/LinkedInOptimizer
# factum-skills
npx skills add enricpedro/factum-skills
# linkedin-positioning-panel
npx skills add jeterchou/linkedin-positioning-panel
# for-you-skills
npx skills add alexliyu7352/for-you-skills
# jianghushuo-skill
npx skills add zhoutian1995/jianghushuo-skill
# account-diagnosis-skill
npx skills add Jian21311/account-diagnosis-skill
```

</details>

<a id="group-mcp"></a>
### MCP 和命令行工具（不是 skill）

让 agent 能读写平台的工具，常和上面的 skill 搭配用。不计入 skill 数。

- 🌟 **[xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp)** · ★ 17.3k<br>小红书 MCP：登录、发图文和视频、搜索、看笔记和评论、点赞收藏，Docker 或本地运行<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-22 · 🔌 MCP · 中文 · Apache-2.0</sub>

- **[Agent-Reach](https://github.com/Panniantong/Agent-Reach)** · ★ 114k<br>Agent-Reach：让 agent 搜索和读取小红书、X、B 站、YouTube、Reddit 上的帖子、评论和字幕，一条命令调用，只读不发<br><sub>平台：小红书 · B 站 · X · YouTube · Reddit</sub><br><sub>更新于 2026-11-22 · 🔌 MCP · 中文 · MIT</sub><br><sub>💡 要登录的平台会把你 Chrome 里该网站的登录复制到它自己的浏览器，作者建议换小号；视频转文字要配 Groq 或 OpenAI 的 Key；PyPI 上同名的包不是它</sub>

- **[Douyin_TikTok_Download_API](https://github.com/Evil0ctal/Douyin_TikTok_Download_API)** · ★ 21.5k<br>自托管的抖音、TikTok、B 站数据 API：作品、作者、评论、热榜和搜索，无水印下载、离线转文字，agent 经 MCP 调用<br><sub>平台：抖音 · B 站 · TikTok</sub><br><sub>更新于 2026-11-20 · 🔌 MCP · 多语言 · Apache-2.0</sub><br><sub>💡 docker compose 一键部署，数据存在你自己的 PostgreSQL</sub>

- **[bb-browser](https://github.com/epiral/bb-browser)** · ★ 6.3k<br>你的浏览器就是 API：CLI + MCP 让 agent 用你的登录态操作 Chrome，36 个平台 103 条现成命令<br><sub>平台：小红书 · B 站 · 微博 · 知乎 · X · YouTube · LinkedIn · Reddit</sub><br><sub>更新于 2026-05-29 · 🔌 MCP · 多语言 · 2 个 skill · MIT</sub>

- **[xiaohongshu-cli](https://github.com/jackwener/xiaohongshu-cli)** · ★ 2.7k<br>小红书命令行：搜索、阅读、点赞、收藏、评论、发布，走逆向接口，附 skill<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-21 💤 · 🔌 MCP · 多语言</sub>

- **[trypost](https://github.com/trypostit/trypost)** · ★ 1.5k<br>开源社媒排程工具，给 agent 提供 MCP 和 REST API 来写、排期、发布各平台帖子，可自己部署<br><sub>平台：YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-23 · 🔌 MCP · 英文 · 18 个 skill · AGPL-3.0</sub>

- **[wechat-download-api](https://github.com/tmwgsicp/wechat-download-api)** · ★ 1.3k<br>公众号文章获取和 RSS API：整号导出 7 种格式、定时订阅，内置 MCP，可自己部署<br><sub>平台：公众号</sub><br><sub>更新于 2026-07-27 · 🔌 MCP · 中文 · AGPL-3.0</sub>

- **[xhs-cli](https://github.com/jackwener/xhs-cli)** · ★ 704<br>小红书命令行的无头浏览器版：搜索、看主页、点赞、收藏、评论，比逆向接口版更像真人操作<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-09 · 🔌 MCP · 多语言 · Apache-2.0</sub>

- **[catbus](https://github.com/cv-cat/catbus)** · ★ 642<br>一个命令操作小红书、抖音、TikTok、B站、快手、微博、X 等：搜索、评论、下载、发布、私信、直播弹幕，统一 JSON 输出<br><sub>平台：小红书 · 抖音 · B 站 · 微博 · 快手 · X · TikTok</sub><br><sub>更新于 2026-11-20 · 🔌 MCP · 中文 · MIT</sub>

- **[postiz-agent](https://github.com/gitroomhq/postiz-agent)** · ★ 588<br>Postiz 的 agent CLI：让 Claude、OpenClaw 等 agent 把帖子排进 X、LinkedIn、Instagram 等 28+ 渠道<br><sub>平台：X · YouTube · Instagram · LinkedIn</sub><br><sub>更新于 2026-11-18 · 🔌 MCP · 英文 · 2 个 skill</sub><br><sub>💡 要 Postiz 云服务或自己部署的 Postiz</sub>

- **[redbook](https://github.com/lucasygu/redbook)** · ★ 547<br>小红书 CLI：搜笔记、读内容、分析博主、发图文，用浏览器 Cookie 认证，不要 API Key<br><sub>平台：小红书</sub><br><sub>更新于 2026-09-12 · 🔌 MCP · 多语言 · MIT</sub>

- **[rdt-cli](https://github.com/public-clis/rdt-cli)** · ★ 546<br>Reddit 命令行：浏览、读帖、搜索、点赞、收藏、订阅，附 skill<br><sub>平台：Reddit</sub><br><sub>更新于 2026-03-21 💤 · 🔌 MCP · 英文</sub>

- **[x-mcp](https://github.com/xpzouying/x-mcp)** · ★ 503<br>xiaohongshu-mcp 的浏览器插件版：装插件即用，不用部署 Docker 或 Python，在你常用的浏览器里发小红书<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-14 · 🔌 MCP · 中文</sub>

- **[xint](https://github.com/0xNyk/xint)** · ★ 262<br>本地优先的 X 数据命令行：搜索、监控、分析、导出、OAuth 操作，用你的 X API<br><sub>平台：X</sub><br><sub>更新于 2026-11-13 · 🔌 MCP · 英文 · MIT</sub>

- **[bilibili-mcp](https://github.com/adoresever/bilibili-mcp)** · ★ 200<br>B 站 MCP：扫码登录，搜视频、读评论字幕弹幕、回复评论，发动态、专栏和视频（支持多 P），看热门、排行和 UP 主数据，发私信；登录凭证存在本地 JSON<br><sub>平台：B 站</sub><br><sub>更新于 2026-03-11 💤 · 🔌 MCP · 中文 · MIT</sub>

- **[zhihu-cli](https://github.com/BAIGUANGMEI/zhihu-cli)** · ★ 116<br>知乎命令行：搜索、热榜、看问题和回答、发想法、提问和文章，扫码或 Cookie 登录，附 skill<br><sub>平台：知乎</sub><br><sub>更新于 2026-05-04 💤 · 🔌 MCP · 中文 · Apache-2.0</sub>

- **[weibo-cli](https://github.com/jackwener/weibo-cli)** · ★ 89<br>微博命令行：热搜、关键词搜索、时间线、评论转发、用户主页，附 skill<br><sub>平台：微博</sub><br><sub>更新于 2026-03-14 💤 · 🔌 MCP · 多语言</sub>

- **[dy-cli](https://github.com/Youhai020616/douyin)** · ★ 74<br>抖音命令行 dy-cli：搜索、下载、发布、互动、热榜、直播和数据分析，输出适合 agent 读<br><sub>平台：抖音</sub><br><sub>更新于 2026-11-09 · 🔌 MCP · 中文 · MIT</sub>

- **[youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp)** · ★ 72<br>从 Claude、Cursor 等 MCP 客户端直接传视频到 YouTube，本地 OAuth 登录，多频道，AI 写标题描述标签<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-22 · 🔌 MCP · 英文 · MIT</sub>

- **[social-poster](https://github.com/profullstack/social-poster)** · ★ 61<br>多平台发帖命令行：用 Puppeteer 浏览器登录，发文字、链接、图片和视频到 X、TikTok、LinkedIn、Reddit 等<br><sub>平台：X · TikTok · LinkedIn · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-11-13 · 🔌 MCP · 英文</sub><br><sub>💡 浏览器自动化登录你的账号，登录态存在本地</sub>

- **[Posthive](https://github.com/AstaBlackClove/posthive)** · ★ 28<br>Posthive：可自己部署的社媒排程平台，一稿发 14 个以上平台，内置 MCP，附 CLI 和 skill<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-20 · 🔌 MCP · 英文 · 2 个 skill · AGPL-3.0</sub>

- **[omnireach](https://github.com/Daily-AC/omnireach)** · ★ 24<br>omnireach：让 agent 搜和读要登录的中文网站，公众号、小红书、抖音、B 站，加 X、Reddit、YouTube，一个命令行<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · X · YouTube · TikTok · Reddit</sub><br><sub>更新于 2026-11-03 · 🔌 MCP · 英文 · MIT</sub><br><sub>💡 公众号搜索免配置；其他来源复用你自己浏览器的登录态</sub>

- **[Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp)** · ★ 21<br>Upload-Post 官方 MCP：agent 发布、排期、看数据，覆盖 TikTok、Instagram、YouTube、LinkedIn、X 等<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-11-20 · 🔌 MCP · 英文 · MIT</sub><br><sub>💡 要 Upload-Post 账号和 API key</sub>

- **[叮卡 DingCard](https://github.com/lottshin/DingCard)** · ★ 16<br>叮卡：浏览器里的图文卡片编辑器，长文自动排成卡片，AI 经 22 个 MCP 工具出图，生成后能接着改<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-10-31 · 🔌 MCP · 中文 · MIT</sub>

- **[Social0](https://github.com/Abhishek-B-R/social0-oss)** · ★ 8<br>Social0：多平台排期发帖，带实时数据和统一收件箱，后台能做的都开放成 REST、命令行和 MCP<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-03 · 🔌 MCP · 英文 · 4 个 skill · AGPL-3.0</sub>

- **[OpenMediaCrawl](https://github.com/Tommyapi/OpenMediaCrawl)** · ★ 6<br>MIT 可商用的自媒体采集工具：小红书、抖音、快手、B站、微博等搜索、详情、评论和下载，附 catbus 命令行 skill<br><sub>平台：小红书 · 抖音 · B 站 · 微博 · 快手 · X · TikTok</sub><br><sub>更新于 2026-11-01 · 🔌 MCP · 中文 · MIT</sub>

- **[claude-social-skills](https://github.com/isaacrowntree/claude-social-skills)** · ★ 4<br>一个命令行管 X、Reddit、Facebook、Instagram、Threads、YouTube、Pinterest 等平台，每个平台配一个 skill<br><sub>平台：X · YouTube · Instagram · Threads · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-11-03 · 🔌 MCP · 英文 · 13 个 skill · MIT</sub>

- **[MCP-rednote-assistant](https://github.com/cloudy-sfu/MCP-rednote-assistant)** · ★ 4<br>从小红书网页采集数据的 MCP，用你导出的 cookie 登录<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-20 · 🔌 MCP · 英文 · GPL-3.0</sub>

- **[Staqly](https://github.com/staqly/staqly)** · ★ 4<br>Staqly：本地优先的社媒排程工具，agent 经 MCP 或 REST 写帖，日历上看，按时发布、失败重试，可自己部署<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn</sub><br><sub>更新于 2026-11-19 · 🔌 MCP · 英文 · AGPL-3.0</sub>

- **[采诗](https://github.com/ZhongQuinnKing/caishi)** · ★ 4<br>采诗：给 agent 用的中文互联网能力包，一条命令读抖音、B 站、小红书、公众号、知乎、头条等 33 个站，只读<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · 微博 · 知乎 · 头条</sub><br><sub>更新于 2026-11-11 · 🔌 MCP · 中文</sub><br><sub>💡 复用你浏览器的登录态；内容和文档是 CC BY-NC-ND，商用要先找作者授权</sub>

- **[nitter](https://github.com/xiaoY233/nitter)** · ★ 3<br>自托管的只读网关，让 agent 读 X 的公开数据：用户、帖子、搜索，同一套工具走 REST、MCP 和 skill<br><sub>平台：X</sub><br><sub>更新于 2026-11-07 · 🔌 MCP · 英文 · AGPL-3.0</sub>

- **[wavegrain-mcp](https://github.com/wavegrain/wavegrain-mcp)** · ★ 1<br>Wavegrain 的 MCP：让 agent 按你的品牌规划帖子，做 TikTok 图文和 Instagram 轮播，改每页文字，排进日历或导出<br><sub>平台：TikTok · Instagram</sub><br><sub>更新于 2026-11-20 · 🔌 MCP · 英文 · MIT</sub><br><sub>💡 服务在 Wavegrain 云端，要 Wavegrain 账号，连接时设每天的积分上限</sub>

- **[FlashData MCP](https://github.com/rocosen/flashdata-mcp)** · ★ 0<br>FlashData 的 MCP 和命令行：搜 YouTube 视频和频道，读元数据和带时间戳的字幕，也能查 Google 搜索、新闻和图片<br><sub>平台：YouTube</sub><br><sub>更新于 2026-11-18 · 🔌 MCP · 英文 · 34 个 skill · MIT</sub><br><sub>💡 数据调用要 FlashData 的 API key 和付费积分，没有免费档</sub>


<a id="group-apps"></a>
### 相关开源平台（完整应用，不是 skill）

能自己部署的运营平台和桌面应用。不计入 skill 数。

- 🌟 **[postiz-app](https://github.com/gitroomhq/postiz-app)** · ★ 42.2k<br>开源社媒排程平台：排期、自动化和数据分析，可用云版或自己部署，支持 agent 接入<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-11-22 · 🧩 应用 · 英文 · AGPL-3.0</sub>

- **[TrendRadar](https://github.com/sansan0/TrendRadar)** · ★ 63.8k<br>TrendRadar：热点舆情监控，聚合多平台热榜和 RSS，按关键词筛，AI 简报推到飞书、Telegram 等；带 MCP，agent 能直接查热点找选题<br><sub>平台：通用</sub><br><sub>更新于 2026-11-21 · 🧩 应用 · 中文 · GPL-3.0</sub><br><sub>💡 自己部署（Docker 或本地）；热榜数据来自 newsnow 的接口，AI 分析要配自己的模型 Key</sub>

- **[AiToEarn](https://github.com/yikart/AiToEarn)** · ★ 28.6k<br>AiToEarn：AI 内容营销平台，创作、剪辑、多平台发布和变现，附 MCP 和给 Claude Code、Codex 等用的技能包<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · 快手 · X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-11-16 · 🧩 应用 · 中文 · 50 个 skill · MIT</sub><br><sub>💡 技能包要 AiToEarn 的 API key</sub>

- **[OpenCreator](https://github.com/krillinai/OpenCreator)** · ★ 14.5k<br>原 KrillinAI：创作者 AI 工作台，视频下载、翻译配音、做视频图片和语音、剪辑，内置 Codex agent<br><sub>平台：小红书 · 抖音 · B 站 · X · YouTube · TikTok · Instagram · Facebook</sub><br><sub>更新于 2026-11-20 · 🧩 应用 · 英文 · 9 个 skill · Apache-2.0</sub>

- **[AutoClip](https://github.com/zhouxiaoka/autoclip)** · ★ 13.5k<br>AutoClip：贴一个长视频链接，自动剪成短视频，配字幕、封面和发布文案，桌面应用，带 CLI、MCP 和 skill<br><sub>平台：小红书 · 抖音 · B 站 · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-23 · 🧩 应用 · 中文 · 2 个 skill · MIT</sub><br><sub>💡 软件免费，云端模型按量计费</sub>

- **[xiaobei](https://github.com/TeamWiseFlow/xiaobei)** · ★ 8.7k<br>小贝：给小微企业的自媒体获客智能体（基于 OpenClaw），公众号写作推送、小红书图文、视频分发、评论区获客、数据复盘<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-11-20 · 🧩 应用 · 中文 · 59 个 skill</sub>

- **[biliup](https://github.com/biliup/biliup)** · ★ 5.7k<br>biliup：直播 24 小时录制、剪辑台、压制和 B 站投稿，大模型推荐高光片段，附 agent skill<br><sub>平台：B 站</sub><br><sub>更新于 2026-11-09 · 🧩 应用 · 中文 · MIT</sub>

- **[we-mp-rss](https://github.com/rachelos/we-mp-rss)** · ★ 5.2k<br>WeRSS：公众号订阅助手，定时抓新文章生成 RSS，转 Markdown/PDF，支持 Webhook 和 API 给 agent 用<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-22 · 🧩 应用 · 多语言</sub>

- **[Easel](https://github.com/ZJU-REAL/Easel)** · ★ 4.8k<br>Easel：ZJU-REAL 开源的社媒 agent，在小红书、抖音、知乎、B 站等平台找趋势、策划、创作、发布和复盘，记住你的账号画像<br><sub>平台：小红书 · 抖音 · B 站 · 知乎</sub><br><sub>更新于 2026-11-17 · 🧩 应用 · 多语言 · Apache-2.0</sub>

- **[CreatorHub](https://github.com/3441293738/creatorhub)** · ★ 3.8k<br>CreatorHub：本地运行的多平台工作台，管账号，监控作品和评论，采集、下载素材，发布和管私信<br><sub>平台：小红书 · 抖音 · 视频号 · 快手 · TikTok</sub><br><sub>更新于 2026-11-23 · 🧩 应用 · 中文</sub><br><sub>💡 登录态、数据库和素材都存在本地；Windows 有安装版，也能从源码运行</sub>

- **[social-media-agent](https://github.com/langchain-ai/social-media-agent)** · ★ 3.1k<br>LangChain 的社媒 agent：读一个链接生成 X 和 LinkedIn 帖子，人工确认后排期发布<br><sub>平台：X · LinkedIn</sub><br><sub>更新于 2026-11-18 · 🧩 应用 · 英文 · MIT</sub>

- **[万稿汇 AIMedia](https://github.com/Anning01/AIMedia)** · ★ 2.6k<br>万稿汇：桌面写作工具，找热点和素材、AI 写稿改稿、去 AI 味、排版，管多平台账号，公众号只推草稿箱<br><sub>平台：小红书 · 公众号 · 头条</sub><br><sub>更新于 2026-11-04 · 🧩 应用 · 中文 · Apache-2.0</sub><br><sub>💡 去 AI 味用的是器灵的改文服务</sub>

- **[Beav](https://github.com/Jamailar/Beav)** · ★ 2.5k<br>Beav（原 RedBox）：小红书 AI 运营桌面应用，采集笔记和评论、本地素材库，一键出标题正文封面配图，能做数字人口播视频<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-22 · 🧩 应用 · 中文 · 16 个 skill</sub><br><sub>💡 仓库里公开的源码停在 2.6.0；数字人口播等新功能在官网免费下载的正式版里</sub>

- **[AIWriteX](https://github.com/iniwap/AIWriteX)** · ★ 2.3k<br>AIWriteX：公众号 AI 写作平台，热点雷达、选题、多智能体写稿、去 AI 味、配图排版和自动发布<br><sub>平台：小红书 · 公众号 · 头条</sub><br><sub>更新于 2026-11-18 · 🧩 应用 · 中文 · Apache-2.0</sub><br><sub>💡 官网另有商业版</sub>

- **[chatwiki](https://github.com/zhimaAi/chatwiki)** · ★ 2.1k<br>ChatWiki：公众号 AI 知识库和客服工作流平台，拖拽搭建自动回复等应用<br><sub>平台：公众号</sub><br><sub>更新于 2026-11-20 · 🧩 应用 · 多语言 · 2 个 skill</sub>

- **[xhs_ai_publisher](https://github.com/BetaStreetOmnis/xhs_ai_publisher)** · ★ 2.1k<br>小红书 AI 发布助手：本地编辑笔记、套模板排多页图、预览后发布，桌面界面加本机 Web 服务<br><sub>平台：小红书</sub><br><sub>更新于 2026-11-03 · 🧩 应用 · 中文 · Apache-2.0</sub>

- **[自媒体工作台](https://github.com/woniuniuniu/dsh-media-desk)** · ★ 1.7k<br>DeepSeek Harness 自媒体工作台插件：一句话记灵感，一键出口播脚本、标题、封面、配图和分镜，排期和复盘<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · X · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-11-18 · 🧩 应用 · 中文 · MIT</sub><br><sub>💡 DeepSeek Harness 的插件，作者标为实验项目</sub>

- **[locoagent](https://github.com/LocoreMind/locoagent)** · ★ 1.1k<br>用真实浏览器自动运营社媒的 agent：X、LinkedIn、Reddit 的浏览、互动和发帖<br><sub>平台：X · LinkedIn · Reddit</sub><br><sub>更新于 2026-06-27 · 🧩 应用 · 英文 · 2 个 skill · MIT</sub>


<a id="by-platforms"></a>
## 按平台查找

仓库说明里明确写了针对哪个平台（按星数排序）。「通用」是不挑平台的。

**小红书**（142）：[Agent-Reach](https://github.com/Panniantong/Agent-Reach) · [guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) · [AiToEarn](https://github.com/yikart/AiToEarn) · [baoyu-skills](https://github.com/JimLiu/baoyu-skills) · [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [openmotion](https://github.com/nexu-io/openmotion) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [AutoClip](https://github.com/zhouxiaoka/autoclip) · [xiaobei](https://github.com/TeamWiseFlow/xiaobei) · [guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill) · [handraw-style](https://github.com/yang0/handraw-style) · [cheat-on-content](https://github.com/XBuilderLAB/cheat-on-content) · [Wechatsync](https://github.com/wechatsync/Wechatsync) · [bb-browser](https://github.com/epiral/bb-browser) · [yichen-skills](https://github.com/mcncarl/yichen-skills) · [Easel](https://github.com/ZJU-REAL/Easel) · [CreatorHub](https://github.com/3441293738/creatorhub) · [wewrite](https://github.com/imraywang/wewrite) · [XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills) · [writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) · [xiaohongshu-cli](https://github.com/jackwener/xiaohongshu-cli) · [xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill) · [万稿汇 AIMedia](https://github.com/Anning01/AIMedia) · [Beav](https://github.com/Jamailar/Beav) · [AIWriteX](https://github.com/iniwap/AIWriteX) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [xhs_ai_publisher](https://github.com/BetaStreetOmnis/xhs_ai_publisher) · [autoclaw-cc/xiaohongshu-skills](https://github.com/autoclaw-cc/xiaohongshu-skills) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [creator-buddy](https://github.com/SpaceZephyr/creator-buddy) · [rnskill](https://github.com/Pluviobyte/rnskill) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [自媒体工作台](https://github.com/woniuniuniu/dsh-media-desk) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [xhs-visual-director-skill](https://github.com/ziguishian/xhs-visual-director-skill) · [Punk-Posters](https://github.com/adrianpunk/Punk-Posters) · [qiaomu-mondo-poster-design](https://github.com/joeseesun/qiaomu-mondo-poster-design) · [clipforge](https://github.com/xixihhhh/clipforge) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [xhs-virtual-product](https://github.com/chenjin-cmd/xhs-virtual-product) · [Viral_Writer_Skill](https://github.com/nashsu/Viral_Writer_Skill) · [yuwen-publish-precheck](https://github.com/yuwen-cool/yuwen-publish-precheck) · [blogger-distiller](https://github.com/otter1101/blogger-distiller) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [gimi-illustration-skill](https://github.com/GiMi-Xiaomi/gimi-illustration-skill) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [xhs-cli](https://github.com/jackwener/xhs-cli) · [catbus](https://github.com/cv-cat/catbus) · [xiaohongshu-ai-workbench](https://github.com/mengke-wang/xiaohongshu-ai-workbench) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [Document-illustrator-skill](https://github.com/op7418/Document-illustrator-skill) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [taishang-laojun](https://github.com/liuhaisi2026212-maker/taishang-laojun) · [vivy-yi/xiaohongshu-skills](https://github.com/vivy-yi/xiaohongshu-skills) · [social-push](https://github.com/jihe520/social-push) · [redbook](https://github.com/lucasygu/redbook) · [article2media](https://github.com/threerocks/article2media) · [hotclip](https://github.com/xixihhhh/hotclip) · [x-mcp](https://github.com/xpzouying/x-mcp) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [cy-carousel-skill](https://github.com/chengyi-ai/cy-carousel-skill) · [atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover) · [xhs-claude-skills](https://github.com/chenxiachan/xhs-claude-skills) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [ttfake92-lab/skills](https://github.com/ttfake92-lab/skills) · [ian-xhs-carousel](https://github.com/helloianneo/ian-xhs-carousel) · [oil-cover](https://github.com/oil-oil/oil-cover) · [lingzao-skill](https://github.com/atian-create/lingzao-skill) · [oh-my-cover-design](https://github.com/hongfamonvAI/oh-my-cover-design) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [xiaohongshu-mcp-skills](https://github.com/autoclaw-cc/xiaohongshu-mcp-skills) · [video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill) · [blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video) · [xhs-cover-skill](https://github.com/Vivixiao980/xhs-cover-skill) · [content-pipeline](https://github.com/OrangeViolin/content-pipeline) · [leaderai-media-toolkit](https://github.com/AzenYes/leaderai-media-toolkit) · [xhs-writer-skill](https://github.com/JuneYaooo/xhs-writer-skill) · [wenzi-xiaohongshu-workflow](https://github.com/wenziai/wenzi-xiaohongshu-workflow) · [blcaptain-style-skill](https://github.com/dososo/blcaptain-style-skill) · [Spreado](https://github.com/BadKid90s/Spreado) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [openclaw-xhs](https://github.com/zhjiang22/openclaw-xhs) · [Vibepost](https://github.com/wuyoscar/Vibepost) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [luobo-design](https://github.com/zhouwei713/luobo-design) · [Autody](https://github.com/kizzhang/autody) · [freestylefly/xiaohongshu-skills](https://github.com/freestylefly/xiaohongshu-skills) · [lieflat-html-design](https://github.com/larashero3-dotcom/lieflat-html-design) · [Fully-automatic-article-generation-skill](https://github.com/solar-luna/Fully-automatic-article-generation-skill) · [media-publish-check](https://github.com/XshuiAi/media-publish-check) · [Eva-skill](https://github.com/Lulu-Eva/Eva-skill) · [content-risk-detector](https://github.com/liuxingqitd/content-risk-detector) · [workbuddy-xhs-skills](https://github.com/jackbauerxu/workbuddy-xhs-skills) · [self-media-guide](https://github.com/lonely-dance-lab/self-media-guide) · [xiaohongshu-summarizer-skill](https://github.com/piekill/xiaohongshu-summarizer-skill) · [libra-skill](https://github.com/hekaixin66-sketch/libra-skill) · [xhs-ai-workflow](https://github.com/554022647henry-boop/xhs-ai-workflow) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [MediaManager](https://github.com/LDJ-creat/MediaManager) · [jianghushuo-oral-skill](https://github.com/read2017/jianghushuo-oral-skill) · [huatu-skill](https://github.com/ythx-101/huatu-skill) · [wechat-article-pipeline-skill](https://github.com/jhwreal/wechat-article-pipeline-skill) · [omnireach](https://github.com/Daily-AC/omnireach) · [红鸦 AI](https://github.com/rnthking/redya-skills) · [xhs-creator-distill](https://github.com/aiiqc/xhs-creator-distill) · [xiaohongshu-openclaw-skill](https://github.com/um-why/xiaohongshu-openclaw-skill) · [叮卡 DingCard](https://github.com/lottshin/DingCard) · [Andy-Writing-Skill](https://github.com/AIPMAndy/Andy-Writing-Skill) · [doubaoya-community](https://github.com/zizhanovo/doubaoya-community) · [social-publish-skills](https://github.com/puppyfront-web/social-publish-skills) · [wechat-editroom](https://github.com/shiker1996/wechat-editroom) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [red-publisher-skill](https://github.com/iamzifei/red-publisher-skill) · [self-media-content-base](https://github.com/caodoris471/self-media-content-base) · [luobo-article-visual](https://github.com/zhouwei713/luobo-article-visual) · [墨排 Mopai](https://github.com/woodti/mopai) · [easypost](https://github.com/gybin02/easypost) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [xiaohongshu-images-skill](https://github.com/iamzifei/xiaohongshu-images-skill) · [xiaohongshu-cover-maker-skill](https://github.com/beatra-ai/xiaohongshu-cover-maker-skill) · [screenshot-infographic-skill](https://github.com/Wanqiu12345/screenshot-infographic-skill) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [OpenMediaCrawl](https://github.com/Tommyapi/OpenMediaCrawl) · [芦苇 Reed](https://github.com/yoruuuchan/wechat-md-studio) · [say-then-publish](https://github.com/Jo6666887/say-then-publish) · [Reelfold 千剪](https://github.com/zyziyun/reelfold) · [xiaohongshu-copywriter-skill](https://github.com/beatra-ai/xiaohongshu-copywriter-skill) · [blogger-video-pipeline](https://github.com/caodoris471/blogger-video-pipeline) · [采诗](https://github.com/ZhongQuinnKing/caishi) · [MCP-rednote-assistant](https://github.com/cloudy-sfu/MCP-rednote-assistant) · [xhs-workflow-skill](https://github.com/anthonyhann/xhs-workflow-skill) · [xiaohongshu-doctor](https://github.com/softbread/xiaohongshu-doctor) · [copyflow](https://github.com/AIPMAndy/copyflow) · [jianghushuo-skill](https://github.com/zhoutian1995/jianghushuo-skill) · [okdata skills](https://github.com/okdataapi/skills) · [account-diagnosis-skill](https://github.com/Jian21311/account-diagnosis-skill) · [EasySociable](https://github.com/murphywuwu/easysociable-mcp)

**抖音**（88）：[AiToEarn](https://github.com/yikart/AiToEarn) · [Douyin_TikTok_Download_API](https://github.com/Evil0ctal/Douyin_TikTok_Download_API) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [AutoClip](https://github.com/zhouxiaoka/autoclip) · [cheat-on-content](https://github.com/XBuilderLAB/cheat-on-content) · [yichen-skills](https://github.com/mcncarl/yichen-skills) · [Easel](https://github.com/ZJU-REAL/Easel) · [CreatorHub](https://github.com/3441293738/creatorhub) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [creator-buddy](https://github.com/SpaceZephyr/creator-buddy) · [rnskill](https://github.com/Pluviobyte/rnskill) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [自媒体工作台](https://github.com/woniuniuniu/dsh-media-desk) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [vibe-knowledge-film](https://github.com/HeyChengC/vibe-knowledge-film) · [clipforge](https://github.com/xixihhhh/clipforge) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [story-studio](https://github.com/konlu/story-studio) · [Viral_Writer_Skill](https://github.com/nashsu/Viral_Writer_Skill) · [yuwen-publish-precheck](https://github.com/yuwen-cool/yuwen-publish-precheck) · [blogger-distiller](https://github.com/otter1101/blogger-distiller) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [catbus](https://github.com/cv-cat/catbus) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [taishang-laojun](https://github.com/liuhaisi2026212-maker/taishang-laojun) · [whiteboard-teacher-video](https://github.com/liangdabiao/whiteboard-teacher-video) · [article2media](https://github.com/threerocks/article2media) · [hotclip](https://github.com/xixihhhh/hotclip) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [ttfake92-lab/skills](https://github.com/ttfake92-lab/skills) · [lingzao-skill](https://github.com/atian-create/lingzao-skill) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill) · [douyin-live-recorder](https://github.com/WeiZhuochun/douyin-live-recorder) · [social-media-data-tools](https://github.com/jinchenma94/social-media-data-tools) · [ah-douyin-clean-downloader](https://github.com/ahang008/ah-douyin-clean-downloader) · [blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video) · [leaderai-media-toolkit](https://github.com/AzenYes/leaderai-media-toolkit) · [vibe-knowledge-video](https://github.com/xiazhuo123456789/vibe-knowledge-video) · [Spreado](https://github.com/BadKid90s/Spreado) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [daihuo-fanpai](https://github.com/wangcanyu/daihuo-fanpai) · [douyin-image-post-scheduler](https://github.com/chengyi-ai/douyin-image-post-scheduler) · [Autody](https://github.com/kizzhang/autody) · [traffic-compass](https://github.com/code-wahaha/traffic-compass) · [douyin-upload-mcp-skill](https://github.com/WJZ-P/douyin-upload-mcp-skill) · [openshorts](https://github.com/jnMetaCode/openshorts) · [dy-cli](https://github.com/Youhai020616/douyin) · [media-publish-check](https://github.com/XshuiAi/media-publish-check) · [Eva-skill](https://github.com/Lulu-Eva/Eva-skill) · [ah-skills](https://github.com/ahang008/ah-skills) · [douyin-skills](https://github.com/zJay26/douyin-skills) · [content-risk-detector](https://github.com/liuxingqitd/content-risk-detector) · [self-media-guide](https://github.com/lonely-dance-lab/self-media-guide) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [douyin-mcp-server](https://github.com/lancelin111/douyin-mcp-server) · [jianghushuo-oral-skill](https://github.com/read2017/jianghushuo-oral-skill) · [omnireach](https://github.com/Daily-AC/omnireach) · [doubaoya-community](https://github.com/zizhanovo/doubaoya-community) · [social-publish-skills](https://github.com/puppyfront-web/social-publish-skills) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [self-media-content-base](https://github.com/caodoris471/self-media-content-base) · [livestream-clip-editor](https://github.com/avisii1680769-cell/livestream-clip-editor) · [easypost](https://github.com/gybin02/easypost) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [video-recreation-skill](https://github.com/Yf040528/video-recreation-skill) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [OpenMediaCrawl](https://github.com/Tommyapi/OpenMediaCrawl) · [muse-Tiktok-Skill](https://github.com/Ayanlin1688/muse-Tiktok-Skill) · [everyone-content](https://github.com/gallagherjas/everyone-content) · [Reelfold 千剪](https://github.com/zyziyun/reelfold) · [reel-scribe](https://github.com/dengxianghua888-ops/reel-scribe) · [douyin-search-openclaw](https://github.com/um-why/douyin-search-openclaw) · [blogger-video-pipeline](https://github.com/caodoris471/blogger-video-pipeline) · [采诗](https://github.com/ZhongQuinnKing/caishi) · [ai-short-video-skill](https://github.com/6667084/ai-short-video-skill) · [douyin-social](https://github.com/why20261/douyin-social) · [jianghushuo-skill](https://github.com/zhoutian1995/jianghushuo-skill) · [douyin-video-summary](https://github.com/liu-wei-ai/douyin-video-summary) · [okdata skills](https://github.com/okdataapi/skills) · [account-diagnosis-skill](https://github.com/Jian21311/account-diagnosis-skill)

**微信公众号**（101）：[guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) · [AiToEarn](https://github.com/yikart/AiToEarn) · [baoyu-skills](https://github.com/JimLiu/baoyu-skills) · [khazix-skills](https://github.com/KKKKhazix/khazix-skills) · [ian-xiaohei-illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations) · [wechatDownload](https://github.com/qiye45/wechatDownload) · [xiaobei](https://github.com/TeamWiseFlow/xiaobei) · [guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill) · [handraw-style](https://github.com/yang0/handraw-style) · [Wechatsync](https://github.com/wechatsync/Wechatsync) · [yichen-skills](https://github.com/mcncarl/yichen-skills) · [we-mp-rss](https://github.com/rachelos/we-mp-rss) · [human-writing](https://github.com/KKKKhazix/human-writing) · [gzh-design-skill](https://github.com/isjiamu/gzh-design-skill) · [md2wechat-skill](https://github.com/geekjourneyx/md2wechat-skill) · [wewrite](https://github.com/imraywang/wewrite) · [writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) · [万稿汇 AIMedia](https://github.com/Anning01/AIMedia) · [AIWriteX](https://github.com/iniwap/AIWriteX) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [chatwiki](https://github.com/zhimaAi/chatwiki) · [creator-buddy](https://github.com/SpaceZephyr/creator-buddy) · [rnskill](https://github.com/Pluviobyte/rnskill) · [自媒体工作台](https://github.com/woniuniuniu/dsh-media-desk) · [Punk-Posters](https://github.com/adrianpunk/Punk-Posters) · [qiaomu-mondo-poster-design](https://github.com/joeseesun/qiaomu-mondo-poster-design) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [wechat-download-api](https://github.com/tmwgsicp/wechat-download-api) · [wechat-article-to-markdown](https://github.com/jackwener/wechat-article-to-markdown) · [gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) · [Viral_Writer_Skill](https://github.com/nashsu/Viral_Writer_Skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [wechat-article-skills](https://github.com/aiworkskills/wechat-article-skills) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [xiaohu-wechat-format](https://github.com/xiaohuailabs/xiaohu-wechat-format) · [NewsCrawler](https://github.com/NanmiCoder/NewsCrawler) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [social-push](https://github.com/jihe520/social-push) · [article2media](https://github.com/threerocks/article2media) · [SyncCaster](https://github.com/RyanYipeng/SyncCaster) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [writing-agent](https://github.com/dongbeixiaohuo/writing-agent) · [rayskills](https://github.com/imraywang/rayskills) · [wechat_article_skills](https://github.com/BND-1/wechat_article_skills) · [lingzao-skill](https://github.com/atian-create/lingzao-skill) · [jiji262/wechat-publisher](https://github.com/jiji262/wechat-publisher) · [oh-my-cover-design](https://github.com/hongfamonvAI/oh-my-cover-design) · [bigpeng-hot-gzh](https://github.com/BigPengSays/bigpeng-hot-gzh) · [content-pipeline](https://github.com/OrangeViolin/content-pipeline) · [blcaptain-style-skill](https://github.com/dososo/blcaptain-style-skill) · [gainubi/wechat-skills](https://github.com/gainubi/wechat-skills) · [wechat-article-pipeline](https://github.com/davinci-seven/wechat-article-pipeline) · [wechat-article-publisher-skill](https://github.com/iamzifei/wechat-article-publisher-skill) · [wechat-article-extractor-skill](https://github.com/freestylefly/wechat-article-extractor-skill) · [xiaowan-wechat-layout-skill](https://github.com/cyberxiaowan/xiaowan-wechat-layout-skill) · [843645440/wechat-skill](https://github.com/843645440/wechat-skill) · [jianshuo/claude-skills](https://github.com/jianshuo/claude-skills) · [WorkBuddy](https://github.com/adsorgcn/WorkBuddy) · [wemp-operator](https://github.com/IanShaw027/wemp-operator) · [wechat-search-weread](https://github.com/KANIKIG/wechat-search-weread) · [space-image](https://github.com/SpaceZephyr/space-image) · [wechat-article-formatter-skill](https://github.com/iamzifei/wechat-article-formatter-skill) · [wechat-typesetting-cy](https://github.com/CY-CHENYUE/wechat-typesetting-cy) · [Fully-automatic-article-generation-skill](https://github.com/solar-luna/Fully-automatic-article-generation-skill) · [Eva-skill](https://github.com/Lulu-Eva/Eva-skill) · [0731coderlee-sudo/wechat-publisher](https://github.com/0731coderlee-sudo/wechat-publisher) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [MediaManager](https://github.com/LDJ-creat/MediaManager) · [guage-write-flow](https://github.com/guage1029/guage-write-flow) · [wechat-article-pipeline-skill](https://github.com/jhwreal/wechat-article-pipeline-skill) · [omnireach](https://github.com/Daily-AC/omnireach) · [wechat-visual-director](https://github.com/zhouke0929/wechat-visual-director) · [wechat-crayon-interactions](https://github.com/MFAI-LAB/wechat-crayon-interactions) · [Master-humanizer-skill](https://github.com/masterball-w/Master-humanizer-skill) · [叮卡 DingCard](https://github.com/lottshin/DingCard) · [Andy-Writing-Skill](https://github.com/AIPMAndy/Andy-Writing-Skill) · [lsf-wechat-editorial-layout](https://github.com/leishifu666/lsf-wechat-editorial-layout) · [wechat-article-skills](https://github.com/lqshow/wechat-article-skills) · [doubaoya-community](https://github.com/zizhanovo/doubaoya-community) · [social-publish-skills](https://github.com/puppyfront-web/social-publish-skills) · [wechat-editroom](https://github.com/shiker1996/wechat-editroom) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [luobo-article-visual](https://github.com/zhouwei713/luobo-article-visual) · [墨排 Mopai](https://github.com/woodti/mopai) · [wechat-explosive-article-skill](https://github.com/AIPMAndy/wechat-explosive-article-skill) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [dsh-fishpai](https://github.com/OMSociety/dsh-fishpai) · [screenshot-infographic-skill](https://github.com/Wanqiu12345/screenshot-infographic-skill) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [芦苇 Reed](https://github.com/yoruuuchan/wechat-md-studio) · [3d-map-video-skill](https://github.com/sixwei2025/3d-map-video-skill) · [wechat-article-cover-skill](https://github.com/beatra-ai/wechat-article-cover-skill) · [weekly-production](https://github.com/lmy414/weekly-production) · [采诗](https://github.com/ZhongQuinnKing/caishi) · [copyflow](https://github.com/AIPMAndy/copyflow) · [gzh-skill-kit](https://github.com/88lin/gzh-skill-kit) · [wechat-publisher-pro](https://github.com/Readarkclub/wechat-publisher-pro) · [qianjin-wechat-analyzer](https://github.com/ZOORO-NEW/qianjin-wechat-analyzer) · [okdata skills](https://github.com/okdataapi/skills)

**微信视频号**（36）：[guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) · [AiToEarn](https://github.com/yikart/AiToEarn) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [cheat-on-content](https://github.com/XBuilderLAB/cheat-on-content) · [CreatorHub](https://github.com/3441293738/creatorhub) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [story-studio](https://github.com/konlu/story-studio) · [yuwen-publish-precheck](https://github.com/yuwen-cool/yuwen-publish-precheck) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [hotclip](https://github.com/xixihhhh/hotclip) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [leaderai-media-toolkit](https://github.com/AzenYes/leaderai-media-toolkit) · [Spreado](https://github.com/BadKid90s/Spreado) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [media-publish-check](https://github.com/XshuiAi/media-publish-check) · [Eva-skill](https://github.com/Lulu-Eva/Eva-skill) · [content-risk-detector](https://github.com/liuxingqitd/content-risk-detector) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [social-publish-skills](https://github.com/puppyfront-web/social-publish-skills) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [self-media-content-base](https://github.com/caodoris471/self-media-content-base) · [livestream-clip-editor](https://github.com/avisii1680769-cell/livestream-clip-editor) · [easypost](https://github.com/gybin02/easypost) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [Reelfold 千剪](https://github.com/zyziyun/reelfold) · [3d-map-video-skill](https://github.com/sixwei2025/3d-map-video-skill) · [blogger-video-pipeline](https://github.com/caodoris471/blogger-video-pipeline) · [ai-short-video-skill](https://github.com/6667084/ai-short-video-skill) · [jianghushuo-skill](https://github.com/zhoutian1995/jianghushuo-skill) · [okdata skills](https://github.com/okdataapi/skills)

**B 站**（53）：[Agent-Reach](https://github.com/Panniantong/Agent-Reach) · [AiToEarn](https://github.com/yikart/AiToEarn) · [Douyin_TikTok_Download_API](https://github.com/Evil0ctal/Douyin_TikTok_Download_API) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [AutoClip](https://github.com/zhouxiaoka/autoclip) · [handraw-style](https://github.com/yang0/handraw-style) · [cheat-on-content](https://github.com/XBuilderLAB/cheat-on-content) · [bb-browser](https://github.com/epiral/bb-browser) · [biliup](https://github.com/biliup/biliup) · [Easel](https://github.com/ZJU-REAL/Easel) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [creator-buddy](https://github.com/SpaceZephyr/creator-buddy) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [自媒体工作台](https://github.com/woniuniuniu/dsh-media-desk) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [catbus](https://github.com/cv-cat/catbus) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [whiteboard-teacher-video](https://github.com/liangdabiao/whiteboard-teacher-video) · [article2media](https://github.com/threerocks/article2media) · [hotclip](https://github.com/xixihhhh/hotclip) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [ttfake92-lab/skills](https://github.com/ttfake92-lab/skills) · [oil-cover](https://github.com/oil-oil/oil-cover) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill) · [blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video) · [leaderai-media-toolkit](https://github.com/AzenYes/leaderai-media-toolkit) · [bilibili-mcp](https://github.com/adoresever/bilibili-mcp) · [self-media-guide](https://github.com/lonely-dance-lab/self-media-guide) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [omnireach](https://github.com/Daily-AC/omnireach) · [social-publish-skills](https://github.com/puppyfront-web/social-publish-skills) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [self-media-content-base](https://github.com/caodoris471/self-media-content-base) · [easypost](https://github.com/gybin02/easypost) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [OpenMediaCrawl](https://github.com/Tommyapi/OpenMediaCrawl) · [Reelfold 千剪](https://github.com/zyziyun/reelfold) · [weekly-production](https://github.com/lmy414/weekly-production) · [blogger-video-pipeline](https://github.com/caodoris471/blogger-video-pipeline) · [采诗](https://github.com/ZhongQuinnKing/caishi) · [okdata skills](https://github.com/okdataapi/skills) · [account-diagnosis-skill](https://github.com/Jian21311/account-diagnosis-skill)

**微博**（20）：[baoyu-skills](https://github.com/JimLiu/baoyu-skills) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [bb-browser](https://github.com/epiral/bb-browser) · [writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [catbus](https://github.com/cv-cat/catbus) · [social-push](https://github.com/jihe520/social-push) · [weibo-cli](https://github.com/jackwener/weibo-cli) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [easypost](https://github.com/gybin02/easypost) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [OpenMediaCrawl](https://github.com/Tommyapi/OpenMediaCrawl) · [采诗](https://github.com/ZhongQuinnKing/caishi) · [okdata skills](https://github.com/okdataapi/skills)

**知乎**（21）：[Wechatsync](https://github.com/wechatsync/Wechatsync) · [bb-browser](https://github.com/epiral/bb-browser) · [Easel](https://github.com/ZJU-REAL/Easel) · [human-writing](https://github.com/KKKKhazix/human-writing) · [md2wechat-skill](https://github.com/geekjourneyx/md2wechat-skill) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [social-push](https://github.com/jihe520/social-push) · [SyncCaster](https://github.com/RyanYipeng/SyncCaster) · [zhihu-cli](https://github.com/BAIGUANGMEI/zhihu-cli) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [social-publish-skills](https://github.com/puppyfront-web/social-publish-skills) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [Eason-Agent-Skills](https://github.com/EasonZhu1997/Eason-Agent-Skills) · [采诗](https://github.com/ZhongQuinnKing/caishi) · [okdata skills](https://github.com/okdataapi/skills)

**快手**（24）：[AiToEarn](https://github.com/yikart/AiToEarn) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [CreatorHub](https://github.com/3441293738/creatorhub) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [clipforge](https://github.com/xixihhhh/clipforge) · [catbus](https://github.com/cv-cat/catbus) · [hotclip](https://github.com/xixihhhh/hotclip) · [redfox-community](https://github.com/redfox-data/redfox-community) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [Spreado](https://github.com/BadKid90s/Spreado) · [media-publish-check](https://github.com/XshuiAi/media-publish-check) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [social-publish-skills](https://github.com/puppyfront-web/social-publish-skills) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [self-media-content-base](https://github.com/caodoris471/self-media-content-base) · [livestream-clip-editor](https://github.com/avisii1680769-cell/livestream-clip-editor) · [easypost](https://github.com/gybin02/easypost) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [OpenMediaCrawl](https://github.com/Tommyapi/OpenMediaCrawl) · [blogger-video-pipeline](https://github.com/caodoris471/blogger-video-pipeline) · [okdata skills](https://github.com/okdataapi/skills)

**今日头条**（15）：[Wechatsync](https://github.com/wechatsync/Wechatsync) · [md2wechat-skill](https://github.com/geekjourneyx/md2wechat-skill) · [万稿汇 AIMedia](https://github.com/Anning01/AIMedia) · [AIWriteX](https://github.com/iniwap/AIWriteX) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [NewsCrawler](https://github.com/NanmiCoder/NewsCrawler) · [redfox-community](https://github.com/redfox-data/redfox-community) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [wechat-article-pipeline-skill](https://github.com/jhwreal/wechat-article-pipeline-skill) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [采诗](https://github.com/ZhongQuinnKing/caishi)

**X（推特）**（93）：[Agent-Reach](https://github.com/Panniantong/Agent-Reach) · [last30days-skill](https://github.com/mvanhorn/last30days-skill) · [postiz-app](https://github.com/gitroomhq/postiz-app) · [AiToEarn](https://github.com/yikart/AiToEarn) · [baoyu-skills](https://github.com/JimLiu/baoyu-skills) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [handraw-style](https://github.com/yang0/handraw-style) · [follow-builders](https://github.com/zarazhangrui/follow-builders) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [bb-browser](https://github.com/epiral/bb-browser) · [yichen-skills](https://github.com/mcncarl/yichen-skills) · [social-media-agent](https://github.com/langchain-ai/social-media-agent) · [自媒体工作台](https://github.com/woniuniuniu/dsh-media-desk) · [x-mentor-skill](https://github.com/alchaincyf/x-mentor-skill) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [x-research-skill](https://github.com/rohunvora/x-research-skill) · [locoagent](https://github.com/LocoreMind/locoagent) · [x-tweet-fetcher](https://github.com/ythx-101/x-tweet-fetcher) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post) · [x-article-publisher-skill](https://github.com/wshuyi/x-article-publisher-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [NewsCrawler](https://github.com/NanmiCoder/NewsCrawler) · [catbus](https://github.com/cv-cat/catbus) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [Document-illustrator-skill](https://github.com/op7418/Document-illustrator-skill) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [postiz-agent](https://github.com/gitroomhq/postiz-agent) · [social-push](https://github.com/jihe520/social-push) · [article2media](https://github.com/threerocks/article2media) · [redfox-community](https://github.com/redfox-data/redfox-community) · [rayskills](https://github.com/imraywang/rayskills) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [twitterapi-io](https://github.com/kaitoInfra/twitterapi-io) · [head-of-content](https://github.com/bradautomates/head-of-content) · [ai-influence-digest](https://github.com/koffuxu/ai-influence-digest) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [xint](https://github.com/0xNyk/xint) · [x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) · [Taisly Agent Kit](https://github.com/taisly/agent) · [x-skills](https://github.com/sergebulaev/x-skills) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [jianshuo/claude-skills](https://github.com/jianshuo/claude-skills) · [WorkBuddy](https://github.com/adsorgcn/WorkBuddy) · [socialclaw](https://github.com/ndesv21/socialclaw) · [create-viral-content](https://github.com/aaaronmiller/create-viral-content) · [Mira](https://github.com/Mira-AI-Tools/mira-skill) · [publora/skills](https://github.com/publora/skills) · [ScrapeIO](https://github.com/xhoantran/scrapeio-agent) · [social-poster](https://github.com/profullstack/social-poster) · [x-ai-topic-selector](https://github.com/vigorX777/x-ai-topic-selector) · [dissect](https://github.com/0xpratzyy/dissect) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills) · [Posthive](https://github.com/AstaBlackClove/posthive) · [omnireach](https://github.com/Daily-AC/omnireach) · [Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp) · [social-skills](https://github.com/scrollmark/social-skills) · [Post Bridge](https://github.com/post-bridge-hq/agent-mode) · [Andy-Writing-Skill](https://github.com/AIPMAndy/Andy-Writing-Skill) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [Revid](https://github.com/tmakersas/revid-skills) · [postkitty](https://github.com/mertkayacs/postkitty) · [x-post-skill](https://github.com/win4r/x-post-skill) · [luobo-article-visual](https://github.com/zhouwei713/luobo-article-visual) · [墨排 Mopai](https://github.com/woodti/mopai) · [easypost](https://github.com/gybin02/easypost) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [Social0](https://github.com/Abhishek-B-R/social0-oss) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [twitterapi-io-skill](https://github.com/dorukardahan/twitterapi-io-skill) · [social-content-engine](https://github.com/caelynmoss/social-content-engine) · [Postey](https://github.com/posteyai/skills) · [apidojo-io/social-media-skills](https://github.com/apidojo-io/social-media-skills) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [OpenMediaCrawl](https://github.com/Tommyapi/OpenMediaCrawl) · [Content-Critic](https://github.com/Anghelo12344567/Content-Critic) · [x-social-skill](https://github.com/baijunjie/x-social-skill) · [x-monitor](https://github.com/ythx-101/x-monitor) · [Reelfold 千剪](https://github.com/zyziyun/reelfold) · [AITuber](https://github.com/aituberapp/ai-video-skill) · [PostLake](https://github.com/PostLake/postlake-mcp) · [Staqly](https://github.com/staqly/staqly) · [claude-social-skills](https://github.com/isaacrowntree/claude-social-skills) · [copyflow](https://github.com/AIPMAndy/copyflow) · [ScraperSocial](https://github.com/nikhonit/social-media-api-skills) · [for-you-skills](https://github.com/alexliyu7352/for-you-skills) · [nitter](https://github.com/xiaoY233/nitter) · [BulkPublish AI Toolkit](https://github.com/bulkpublish/bulkpublish-ai-toolkit) · [PostOnce](https://github.com/postoncehq/postonce-skills) · [okdata skills](https://github.com/okdataapi/skills)

**YouTube**（130）：[Agent-Reach](https://github.com/Panniantong/Agent-Reach) · [last30days-skill](https://github.com/mvanhorn/last30days-skill) · [postiz-app](https://github.com/gitroomhq/postiz-app) · [AiToEarn](https://github.com/yikart/AiToEarn) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [openmotion](https://github.com/nexu-io/openmotion) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [AutoClip](https://github.com/zhouxiaoka/autoclip) · [handraw-style](https://github.com/yang0/handraw-style) · [follow-builders](https://github.com/zarazhangrui/follow-builders) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [youtube-agent-skill](https://github.com/Jakeschincariol/youtube-agent-skill) · [bb-browser](https://github.com/epiral/bb-browser) · [herk-edit-kit](https://github.com/nateherkai/herk-edit-kit) · [youtube-shorts-pipeline](https://github.com/rushindrasinha/youtube-shorts-pipeline) · [Youtube-clipper-skill](https://github.com/op7418/Youtube-clipper-skill) · [claude-real-video](https://github.com/HUANGCHIHHUNGLeo/claude-real-video) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [自媒体工作台](https://github.com/woniuniuniu/dsh-media-desk) · [trypost](https://github.com/trypostit/trypost) · [ZeroPointRepo/youtube-skills](https://github.com/ZeroPointRepo/youtube-skills) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [claude-youtube](https://github.com/AgriciDaniel/claude-youtube) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [chatgpt-video-editing-skills](https://github.com/Jaycheng1103/chatgpt-video-editing-skills) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [Clips Kitty](https://github.com/ColinGPT9/clips-studio) · [postiz-agent](https://github.com/gitroomhq/postiz-agent) · [smart-illustrator](https://github.com/axtonliu/smart-illustrator) · [article2media](https://github.com/threerocks/article2media) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [nova-youtube-agent](https://github.com/sharbelxyz/nova-youtube-agent) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [ttfake92-lab/skills](https://github.com/ttfake92-lab/skills) · [head-of-content](https://github.com/bradautomates/head-of-content) · [TubeLab](https://github.com/TubeLabHQ/youtube-research-skills) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [content-skills](https://github.com/vyralcontent/content-skills) · [video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill) · [blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video) · [Taisly Agent Kit](https://github.com/taisly/agent) · [shorts-kit](https://github.com/howznguyen/shorts-kit) · [reelclaw](https://github.com/dansugc/reelclaw) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [jianshuo/claude-skills](https://github.com/jianshuo/claude-skills) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [socialclaw](https://github.com/ndesv21/socialclaw) · [sergebulaev/youtube-skills](https://github.com/sergebulaev/youtube-skills) · [favstash-ai-video-editing-skills](https://github.com/alisadiq-ai/favstash-ai-video-editing-skills) · [create-viral-content](https://github.com/aaaronmiller/create-viral-content) · [youtube-scout](https://github.com/AgriciDaniel/youtube-scout) · [editing-gameplay-montages](https://github.com/gustavomenani/editing-gameplay-montages) · [make-short](https://github.com/nocodehack/make-short) · [openshorts](https://github.com/jnMetaCode/openshorts) · [Clip-Forge](https://github.com/lowdevco/Clip-Forge) · [Mira](https://github.com/Mira-AI-Tools/mira-skill) · [youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp) · [publora/skills](https://github.com/publora/skills) · [ScrapeIO](https://github.com/xhoantran/scrapeio-agent) · [auto-edit-workspace](https://github.com/dean9703111/auto-edit-workspace) · [dissect](https://github.com/0xpratzyy/dissect) · [self-media-guide](https://github.com/lonely-dance-lab/self-media-guide) · [youtube-translate-skill](https://github.com/0xSero/youtube-translate-skill) · [claude-reel-editor](https://github.com/nicolapocock/claude-reel-editor) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [youtube-transcript-skills](https://github.com/tubeagentkit/youtube-transcript-skills) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [cut-as-code](https://github.com/WhiteTowerAI/cut-as-code) · [tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills) · [ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills) · [Posthive](https://github.com/AstaBlackClove/posthive) · [super-video-agent](https://github.com/ww-w-ai/super-video-agent) · [remotion-shorts-skill](https://github.com/social-media-skills/remotion-shorts-skill) · [hojas-studio](https://github.com/rakaga66/hojas-studio) · [omnireach](https://github.com/Daily-AC/omnireach) · [Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp) · [social-skills](https://github.com/scrollmark/social-skills) · [claude-editing-skills](https://github.com/pihu26112005/claude-editing-skills) · [zero-dollar-studio](https://github.com/TheNoumanDev/zero-dollar-studio) · [cartoon-shorts-skill](https://github.com/Matteoikarieth96/cartoon-shorts-skill) · [claude-stickman-shorts](https://github.com/SyedBahjat/claude-stickman-shorts) · [Post Bridge](https://github.com/post-bridge-hq/agent-mode) · [factum-skills](https://github.com/enricpedro/factum-skills) · [fragua](https://github.com/pedrovelasquez9/fragua) · [claude-skills-shorts-animados](https://github.com/miguelcotrinaia/claude-skills-shorts-animados) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [Revid](https://github.com/tmakersas/revid-skills) · [postkitty](https://github.com/mertkayacs/postkitty) · [Content-Agent-Kit](https://github.com/XuHo-IT/Content-Agent-Kit) · [video-editing-skill](https://github.com/social-media-skills/video-editing-skill) · [ai-video-marketing](https://github.com/matt-j-penny/ai-video-marketing) · [b-roll-skills](https://github.com/iart-ai/b-roll-skills) · [youtube-video-skills](https://github.com/iart-ai/youtube-video-skills) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [Social0](https://github.com/Abhishek-B-R/social0-oss) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [videopowers](https://github.com/vinit-agr/videopowers) · [not-a-blogger](https://github.com/ilyautov/not-a-blogger) · [Postey](https://github.com/posteyai/skills) · [content-repurposer](https://github.com/Mahanaicoach/content-repurposer) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [Virlo-Agent-Plugin](https://github.com/Virlo-AI/Virlo-Agent-Plugin) · [Marky](https://github.com/Marky-Team/marky-skills) · [Skill-Editor-IA](https://github.com/brianacevedo2001-lab/Skill-Editor-IA) · [claude-social-media-skills](https://github.com/michaellady/claude-social-media-skills) · [Reelfold 千剪](https://github.com/zyziyun/reelfold) · [AITuber](https://github.com/aituberapp/ai-video-skill) · [edit-reel](https://github.com/MMhaidra/edit-reel) · [treemation](https://github.com/Adytm404/treemation) · [claude-video-editor](https://github.com/vitormenoli/claude-video-editor) · [PostLake](https://github.com/PostLake/postlake-mcp) · [HookLab](https://github.com/CoolerGit/HookLab) · [youtube-skillbox](https://github.com/hackers-reality/youtube-skillbox) · [blogger-video-pipeline](https://github.com/caodoris471/blogger-video-pipeline) · [Staqly](https://github.com/staqly/staqly) · [claude-social-skills](https://github.com/isaacrowntree/claude-social-skills) · [boqount](https://github.com/boqo-ai/boqount) · [thumbnail-studio](https://github.com/blixvip/thumbnail-studio) · [faceless-shorts](https://github.com/kinnuworks/faceless-shorts) · [brightbean-platform-agent](https://github.com/brightbeanxyz/brightbean-platform-agent) · [ScraperSocial](https://github.com/nikhonit/social-media-api-skills) · [youtube-outliers-claude-code](https://github.com/BrandonChin827/youtube-outliers-claude-code) · [darkniche](https://github.com/darksemfiltro/darkniche) · [BulkPublish AI Toolkit](https://github.com/bulkpublish/bulkpublish-ai-toolkit) · [PostOnce](https://github.com/postoncehq/postonce-skills) · [okdata skills](https://github.com/okdataapi/skills) · [FlashData MCP](https://github.com/rocosen/flashdata-mcp)

**TikTok**（105）：[last30days-skill](https://github.com/mvanhorn/last30days-skill) · [postiz-app](https://github.com/gitroomhq/postiz-app) · [AiToEarn](https://github.com/yikart/AiToEarn) · [Douyin_TikTok_Download_API](https://github.com/Evil0ctal/Douyin_TikTok_Download_API) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [openmotion](https://github.com/nexu-io/openmotion) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [AutoClip](https://github.com/zhouxiaoka/autoclip) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [CreatorHub](https://github.com/3441293738/creatorhub) · [youtube-shorts-pipeline](https://github.com/rushindrasinha/youtube-shorts-pipeline) · [自媒体工作台](https://github.com/woniuniuniu/dsh-media-desk) · [trypost](https://github.com/trypostit/trypost) · [clipforge](https://github.com/xixihhhh/clipforge) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [catbus](https://github.com/cv-cat/catbus) · [chatgpt-video-editing-skills](https://github.com/Jaycheng1103/chatgpt-video-editing-skills) · [Clips Kitty](https://github.com/ColinGPT9/clips-studio) · [clipcat-skill](https://github.com/Clipcat-ai/clipcat-skill) · [redfox-community](https://github.com/redfox-data/redfox-community) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [head-of-content](https://github.com/bradautomates/head-of-content) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [content-skills](https://github.com/vyralcontent/content-skills) · [jev-social](https://github.com/socai-io/jev-social) · [Taisly Agent Kit](https://github.com/taisly/agent) · [shorts-kit](https://github.com/howznguyen/shorts-kit) · [reelclaw](https://github.com/dansugc/reelclaw) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [tiktok-skills](https://github.com/sergebulaev/tiktok-skills) · [threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [socialclaw](https://github.com/ndesv21/socialclaw) · [favstash-ai-video-editing-skills](https://github.com/alisadiq-ai/favstash-ai-video-editing-skills) · [create-viral-content](https://github.com/aaaronmiller/create-viral-content) · [editing-gameplay-montages](https://github.com/gustavomenani/editing-gameplay-montages) · [Clip-Forge](https://github.com/lowdevco/Clip-Forge) · [Mira](https://github.com/Mira-AI-Tools/mira-skill) · [publora/skills](https://github.com/publora/skills) · [ScrapeIO](https://github.com/xhoantran/scrapeio-agent) · [social-poster](https://github.com/profullstack/social-poster) · [dissect](https://github.com/0xpratzyy/dissect) · [claude-reel-editor](https://github.com/nicolapocock/claude-reel-editor) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [cut-as-code](https://github.com/WhiteTowerAI/cut-as-code) · [tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills) · [ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills) · [Posthive](https://github.com/AstaBlackClove/posthive) · [remotion-shorts-skill](https://github.com/social-media-skills/remotion-shorts-skill) · [hojas-studio](https://github.com/rakaga66/hojas-studio) · [omnireach](https://github.com/Daily-AC/omnireach) · [Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp) · [social-skills](https://github.com/scrollmark/social-skills) · [claude-editing-skills](https://github.com/pihu26112005/claude-editing-skills) · [cartoon-shorts-skill](https://github.com/Matteoikarieth96/cartoon-shorts-skill) · [claude-stickman-shorts](https://github.com/SyedBahjat/claude-stickman-shorts) · [Post Bridge](https://github.com/post-bridge-hq/agent-mode) · [fragua](https://github.com/pedrovelasquez9/fragua) · [claude-skills-shorts-animados](https://github.com/miguelcotrinaia/claude-skills-shorts-animados) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [Revid](https://github.com/tmakersas/revid-skills) · [postkitty](https://github.com/mertkayacs/postkitty) · [Content-Agent-Kit](https://github.com/XuHo-IT/Content-Agent-Kit) · [video-editing-skill](https://github.com/social-media-skills/video-editing-skill) · [ai-video-marketing](https://github.com/matt-j-penny/ai-video-marketing) · [b-roll-skills](https://github.com/iart-ai/b-roll-skills) · [Riffkit](https://github.com/riffkit/skill) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [Social0](https://github.com/Abhishek-B-R/social0-oss) · [my-claude-skills](https://github.com/vincentventalon/my-claude-skills) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [not-a-blogger](https://github.com/ilyautov/not-a-blogger) · [video-recreation-skill](https://github.com/Yf040528/video-recreation-skill) · [Postey](https://github.com/posteyai/skills) · [content-repurposer](https://github.com/Mahanaicoach/content-repurposer) · [apidojo-io/social-media-skills](https://github.com/apidojo-io/social-media-skills) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [Virlo-Agent-Plugin](https://github.com/Virlo-AI/Virlo-Agent-Plugin) · [OpenMediaCrawl](https://github.com/Tommyapi/OpenMediaCrawl) · [Content-Critic](https://github.com/Anghelo12344567/Content-Critic) · [muse-Tiktok-Skill](https://github.com/Ayanlin1688/muse-Tiktok-Skill) · [Skill-Editor-IA](https://github.com/brianacevedo2001-lab/Skill-Editor-IA) · [claude-social-media-skills](https://github.com/michaellady/claude-social-media-skills) · [theme-page](https://github.com/sanskarprajapati/theme-page) · [Reelfold 千剪](https://github.com/zyziyun/reelfold) · [AITuber](https://github.com/aituberapp/ai-video-skill) · [edit-reel](https://github.com/MMhaidra/edit-reel) · [treemation](https://github.com/Adytm404/treemation) · [PostLake](https://github.com/PostLake/postlake-mcp) · [HookLab](https://github.com/CoolerGit/HookLab) · [blogger-video-pipeline](https://github.com/caodoris471/blogger-video-pipeline) · [Staqly](https://github.com/staqly/staqly) · [boqount](https://github.com/boqo-ai/boqount) · [claude-reelsmith](https://github.com/lalimi/claude-reelsmith) · [Minimax-H3-Tiktok-skill](https://github.com/Ayanlin1688/Minimax-H3-Tiktok-skill) · [ai-short-video-skill](https://github.com/6667084/ai-short-video-skill) · [brightbean-platform-agent](https://github.com/brightbeanxyz/brightbean-platform-agent) · [ScraperSocial](https://github.com/nikhonit/social-media-api-skills) · [viral-tiktok-skills](https://github.com/maxxyart/viral-tiktok-skills) · [BulkPublish AI Toolkit](https://github.com/bulkpublish/bulkpublish-ai-toolkit) · [PostOnce](https://github.com/postoncehq/postonce-skills) · [wavegrain-mcp](https://github.com/wavegrain/wavegrain-mcp) · [okdata skills](https://github.com/okdataapi/skills) · [EasySociable](https://github.com/murphywuwu/easysociable-mcp)

**Instagram**（102）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [AiToEarn](https://github.com/yikart/AiToEarn) · [openmotion](https://github.com/nexu-io/openmotion) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [AutoClip](https://github.com/zhouxiaoka/autoclip) · [instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [charlie947/social-media-skills](https://github.com/charlie947/social-media-skills) · [herk-edit-kit](https://github.com/nateherkai/herk-edit-kit) · [youtube-shorts-pipeline](https://github.com/rushindrasinha/youtube-shorts-pipeline) · [自媒体工作台](https://github.com/woniuniuniu/dsh-media-desk) · [trypost](https://github.com/trypostit/trypost) · [instagram-skills](https://github.com/sergebulaev/instagram-skills) · [claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [chatgpt-video-editing-skills](https://github.com/Jaycheng1103/chatgpt-video-editing-skills) · [Clips Kitty](https://github.com/ColinGPT9/clips-studio) · [postiz-agent](https://github.com/gitroomhq/postiz-agent) · [claude-content-skills](https://github.com/Ootto-AI/claude-content-skills) · [redfox-community](https://github.com/redfox-data/redfox-community) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [head-of-content](https://github.com/bradautomates/head-of-content) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [content-skills](https://github.com/vyralcontent/content-skills) · [jev-social](https://github.com/socai-io/jev-social) · [Taisly Agent Kit](https://github.com/taisly/agent) · [shorts-kit](https://github.com/howznguyen/shorts-kit) · [reelclaw](https://github.com/dansugc/reelclaw) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [socialclaw](https://github.com/ndesv21/socialclaw) · [favstash-ai-video-editing-skills](https://github.com/alisadiq-ai/favstash-ai-video-editing-skills) · [editing-gameplay-montages](https://github.com/gustavomenani/editing-gameplay-montages) · [Clip-Forge](https://github.com/lowdevco/Clip-Forge) · [Mira](https://github.com/Mira-AI-Tools/mira-skill) · [publora/skills](https://github.com/publora/skills) · [ScrapeIO](https://github.com/xhoantran/scrapeio-agent) · [auto-edit-workspace](https://github.com/dean9703111/auto-edit-workspace) · [dissect](https://github.com/0xpratzyy/dissect) · [claude-reel-editor](https://github.com/nicolapocock/claude-reel-editor) · [edit-reel](https://github.com/artemisln/edit-reel) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [redfox_api_skill](https://github.com/liangdabiao/redfox_api_skill) · [tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills) · [ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills) · [Posthive](https://github.com/AstaBlackClove/posthive) · [remotion-shorts-skill](https://github.com/social-media-skills/remotion-shorts-skill) · [hojas-studio](https://github.com/rakaga66/hojas-studio) · [Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp) · [social-skills](https://github.com/scrollmark/social-skills) · [claude-editing-skills](https://github.com/pihu26112005/claude-editing-skills) · [cartoon-shorts-skill](https://github.com/Matteoikarieth96/cartoon-shorts-skill) · [claude-stickman-shorts](https://github.com/SyedBahjat/claude-stickman-shorts) · [Post Bridge](https://github.com/post-bridge-hq/agent-mode) · [fragua](https://github.com/pedrovelasquez9/fragua) · [红狐数据 DSH 插件包](https://github.com/redfox-data/redfox-community-dsh) · [Revid](https://github.com/tmakersas/revid-skills) · [postkitty](https://github.com/mertkayacs/postkitty) · [Content-Agent-Kit](https://github.com/XuHo-IT/Content-Agent-Kit) · [video-editing-skill](https://github.com/social-media-skills/video-editing-skill) · [claude-edits-skill](https://github.com/iamjeeth/claude-edits-skill) · [ai-video-marketing](https://github.com/matt-j-penny/ai-video-marketing) · [b-roll-skills](https://github.com/iart-ai/b-roll-skills) · [instagram-carousel-skill](https://github.com/social-media-skills/instagram-carousel-skill) · [easypost](https://github.com/gybin02/easypost) · [Social0](https://github.com/Abhishek-B-R/social0-oss) · [my-claude-skills](https://github.com/vincentventalon/my-claude-skills) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [instagram-ai-agent-skills](https://github.com/apismith-labs/instagram-ai-agent-skills) · [not-a-blogger](https://github.com/ilyautov/not-a-blogger) · [Postey](https://github.com/posteyai/skills) · [content-repurposer](https://github.com/Mahanaicoach/content-repurposer) · [apidojo-io/social-media-skills](https://github.com/apidojo-io/social-media-skills) · [SocialDataX](https://github.com/DevinChen2014/socialdatax-skills) · [Virlo-Agent-Plugin](https://github.com/Virlo-AI/Virlo-Agent-Plugin) · [Marky](https://github.com/Marky-Team/marky-skills) · [Content-Critic](https://github.com/Anghelo12344567/Content-Critic) · [Skill-Editor-IA](https://github.com/brianacevedo2001-lab/Skill-Editor-IA) · [theme-page](https://github.com/sanskarprajapati/theme-page) · [Reelfold 千剪](https://github.com/zyziyun/reelfold) · [estudio-de-conteudo-ia](https://github.com/fermaziero/estudio-de-conteudo-ia) · [AITuber](https://github.com/aituberapp/ai-video-skill) · [edit-reel](https://github.com/MMhaidra/edit-reel) · [treemation](https://github.com/Adytm404/treemation) · [PostLake](https://github.com/PostLake/postlake-mcp) · [HookLab](https://github.com/CoolerGit/HookLab) · [instagram-list-inspector](https://github.com/GreedyC/instagram-list-inspector) · [Staqly](https://github.com/staqly/staqly) · [claude-social-skills](https://github.com/isaacrowntree/claude-social-skills) · [boqount](https://github.com/boqo-ai/boqount) · [instagram-skill](https://github.com/social-media-skills/instagram-skill) · [claude-reelsmith](https://github.com/lalimi/claude-reelsmith) · [brightbean-platform-agent](https://github.com/brightbeanxyz/brightbean-platform-agent) · [ScraperSocial](https://github.com/nikhonit/social-media-api-skills) · [viral-tiktok-skills](https://github.com/maxxyart/viral-tiktok-skills) · [BulkPublish AI Toolkit](https://github.com/bulkpublish/bulkpublish-ai-toolkit) · [PostOnce](https://github.com/postoncehq/postonce-skills) · [wavegrain-mcp](https://github.com/wavegrain/wavegrain-mcp) · [skillify-sh/skills](https://github.com/skillify-sh/skills) · [okdata skills](https://github.com/okdataapi/skills) · [EasySociable](https://github.com/murphywuwu/easysociable-mcp)

**LinkedIn**（53）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [AiToEarn](https://github.com/yikart/AiToEarn) · [cheat-on-content](https://github.com/XBuilderLAB/cheat-on-content) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [bb-browser](https://github.com/epiral/bb-browser) · [sergebulaev/linkedin-skills](https://github.com/sergebulaev/linkedin-skills) · [charlie947/social-media-skills](https://github.com/charlie947/social-media-skills) · [linkedin-agent-skill](https://github.com/Jakeschincariol/linkedin-agent-skill) · [social-media-agent](https://github.com/langchain-ai/social-media-agent) · [trypost](https://github.com/trypostit/trypost) · [ai-copywriter](https://github.com/mikiarlo3/ai-copywriter) · [locoagent](https://github.com/LocoreMind/locoagent) · [motion-graphics-skills](https://github.com/charlie947/motion-graphics-skills) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [postiz-agent](https://github.com/gitroomhq/postiz-agent) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [jev-social](https://github.com/socai-io/jev-social) · [hattip-linkedin-os](https://github.com/ChristianDiBratto25/hattip-linkedin-os) · [threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill) · [Linked-API/linkedin-skills](https://github.com/Linked-API/linkedin-skills) · [socialclaw](https://github.com/ndesv21/socialclaw) · [create-viral-content](https://github.com/aaaronmiller/create-viral-content) · [publora/skills](https://github.com/publora/skills) · [ScrapeIO](https://github.com/xhoantran/scrapeio-agent) · [social-poster](https://github.com/profullstack/social-poster) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills) · [Posthive](https://github.com/AstaBlackClove/posthive) · [Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp) · [social-skills](https://github.com/scrollmark/social-skills) · [Post Bridge](https://github.com/post-bridge-hq/agent-mode) · [LinkedInOptimizer](https://github.com/GodModeAI2025/LinkedInOptimizer) · [postkitty](https://github.com/mertkayacs/postkitty) · [video-editing-skill](https://github.com/social-media-skills/video-editing-skill) · [Social0](https://github.com/Abhishek-B-R/social0-oss) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [linkedin-positioning-panel](https://github.com/jeterchou/linkedin-positioning-panel) · [Postey](https://github.com/posteyai/skills) · [Marky](https://github.com/Marky-Team/marky-skills) · [Content-Critic](https://github.com/Anghelo12344567/Content-Critic) · [Skill-Editor-IA](https://github.com/brianacevedo2001-lab/Skill-Editor-IA) · [claude-social-media-skills](https://github.com/michaellady/claude-social-media-skills) · [Reelfold 千剪](https://github.com/zyziyun/reelfold) · [linkedin-agent-italia](https://github.com/JacopoMarini/linkedin-agent-italia) · [PostLake](https://github.com/PostLake/postlake-mcp) · [Staqly](https://github.com/staqly/staqly) · [taplio-linkedin-plugin](https://github.com/TaplioOfficial/taplio-linkedin-plugin) · [brightbean-platform-agent](https://github.com/brightbeanxyz/brightbean-platform-agent) · [ScraperSocial](https://github.com/nikhonit/social-media-api-skills) · [BulkPublish AI Toolkit](https://github.com/bulkpublish/bulkpublish-ai-toolkit) · [PostOnce](https://github.com/postoncehq/postonce-skills) · [EasySociable](https://github.com/murphywuwu/easysociable-mcp)

**Threads**（28）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [AiToEarn](https://github.com/yikart/AiToEarn) · [trypost](https://github.com/trypostit/trypost) · [claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill) · [threads-skills](https://github.com/sergebulaev/threads-skills) · [publora/skills](https://github.com/publora/skills) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills) · [Posthive](https://github.com/AstaBlackClove/posthive) · [Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp) · [Post Bridge](https://github.com/post-bridge-hq/agent-mode) · [Andy-Writing-Skill](https://github.com/AIPMAndy/Andy-Writing-Skill) · [postkitty](https://github.com/mertkayacs/postkitty) · [Social0](https://github.com/Abhishek-B-R/social0-oss) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [Postey](https://github.com/posteyai/skills) · [claude-social-media-skills](https://github.com/michaellady/claude-social-media-skills) · [AITuber](https://github.com/aituberapp/ai-video-skill) · [PostLake](https://github.com/PostLake/postlake-mcp) · [claude-social-skills](https://github.com/isaacrowntree/claude-social-skills) · [brightbean-platform-agent](https://github.com/brightbeanxyz/brightbean-platform-agent) · [BulkPublish AI Toolkit](https://github.com/bulkpublish/bulkpublish-ai-toolkit) · [PostOnce](https://github.com/postoncehq/postonce-skills) · [EasySociable](https://github.com/murphywuwu/easysociable-mcp)

**Facebook**（37）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [AiToEarn](https://github.com/yikart/AiToEarn) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [trypost](https://github.com/trypostit/trypost) · [claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [Taisly Agent Kit](https://github.com/taisly/agent) · [facebook-skills](https://github.com/sergebulaev/facebook-skills) · [socialclaw](https://github.com/ndesv21/socialclaw) · [Mira](https://github.com/Mira-AI-Tools/mira-skill) · [publora/skills](https://github.com/publora/skills) · [ScrapeIO](https://github.com/xhoantran/scrapeio-agent) · [auto-edit-workspace](https://github.com/dean9703111/auto-edit-workspace) · [social-poster](https://github.com/profullstack/social-poster) · [dissect](https://github.com/0xpratzyy/dissect) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills) · [Posthive](https://github.com/AstaBlackClove/posthive) · [Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp) · [Post Bridge](https://github.com/post-bridge-hq/agent-mode) · [postkitty](https://github.com/mertkayacs/postkitty) · [Content-Agent-Kit](https://github.com/XuHo-IT/Content-Agent-Kit) · [video-editing-skill](https://github.com/social-media-skills/video-editing-skill) · [Social0](https://github.com/Abhishek-B-R/social0-oss) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [Postey](https://github.com/posteyai/skills) · [Marky](https://github.com/Marky-Team/marky-skills) · [AITuber](https://github.com/aituberapp/ai-video-skill) · [PostLake](https://github.com/PostLake/postlake-mcp) · [claude-social-skills](https://github.com/isaacrowntree/claude-social-skills) · [brightbean-platform-agent](https://github.com/brightbeanxyz/brightbean-platform-agent) · [ScraperSocial](https://github.com/nikhonit/social-media-api-skills) · [viral-tiktok-skills](https://github.com/maxxyart/viral-tiktok-skills) · [BulkPublish AI Toolkit](https://github.com/bulkpublish/bulkpublish-ai-toolkit) · [PostOnce](https://github.com/postoncehq/postonce-skills)

**Reddit**（23）：[Agent-Reach](https://github.com/Panniantong/Agent-Reach) · [last30days-skill](https://github.com/mvanhorn/last30days-skill) · [postiz-app](https://github.com/gitroomhq/postiz-app) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [bb-browser](https://github.com/epiral/bb-browser) · [locoagent](https://github.com/LocoreMind/locoagent) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [rdt-cli](https://github.com/public-clis/rdt-cli) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [socialclaw](https://github.com/ndesv21/socialclaw) · [create-viral-content](https://github.com/aaaronmiller/create-viral-content) · [ScrapeIO](https://github.com/xhoantran/scrapeio-agent) · [social-poster](https://github.com/profullstack/social-poster) · [dissect](https://github.com/0xpratzyy/dissect) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills) · [omnireach](https://github.com/Daily-AC/omnireach) · [Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp) · [sourceboard](https://github.com/aaronyi97/sourceboard) · [claude-social-skills](https://github.com/isaacrowntree/claude-social-skills) · [ScraperSocial](https://github.com/nikhonit/social-media-api-skills) · [okdata skills](https://github.com/okdataapi/skills)

**Pinterest**（21）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [AiToEarn](https://github.com/yikart/AiToEarn) · [trypost](https://github.com/trypostit/trypost) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [socialclaw](https://github.com/ndesv21/socialclaw) · [Mira](https://github.com/Mira-AI-Tools/mira-skill) · [social-poster](https://github.com/profullstack/social-poster) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [ScrapeAtlas](https://github.com/ScrapeAtlas/social-media-agent-skills) · [Posthive](https://github.com/AstaBlackClove/posthive) · [Upload-Post MCP](https://github.com/Upload-Post/upload-post-mcp) · [Post Bridge](https://github.com/post-bridge-hq/agent-mode) · [Social0](https://github.com/Abhishek-B-R/social0-oss) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [Postey](https://github.com/posteyai/skills) · [PostLake](https://github.com/PostLake/postlake-mcp) · [claude-social-skills](https://github.com/isaacrowntree/claude-social-skills) · [brightbean-platform-agent](https://github.com/brightbeanxyz/brightbean-platform-agent) · [BulkPublish AI Toolkit](https://github.com/bulkpublish/bulkpublish-ai-toolkit) · [PostOnce](https://github.com/postoncehq/postonce-skills)

**Substack 和 Newsletter**（4）：[charlie947/social-media-skills](https://github.com/charlie947/social-media-skills) · [writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) · [motion-graphics-skills](https://github.com/charlie947/motion-graphics-skills) · [claude-social-media-skills](https://github.com/michaellady/claude-social-media-skills)

**通用**（29）：[humanizer](https://github.com/blader/humanizer) · [TrendRadar](https://github.com/sansan0/TrendRadar) · [Humanizer-zh](https://github.com/op7418/Humanizer-zh) · [dbskill](https://github.com/dontbesilent2025/dbskill) · [lieflat-less-ai-tone](https://github.com/larashero3-dotcom/lieflat-less-ai-tone) · [native-subtitle-quote-image](https://github.com/chengyi-ai/native-subtitle-quote-image) · [shuorenhua](https://github.com/MrGeDiao/shuorenhua) · [gif-factory](https://github.com/WoYun520/gif-factory) · [digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) · [video-spec-builder](https://github.com/feicaiclub/video-spec-builder) · [wallstreet-explainer](https://github.com/HeyChengC/wallstreet-explainer) · [qu-ai-wei](https://github.com/LifelongLazyLearner/qu-ai-wei) · [clipify](https://github.com/louisedesadeleer/clipify) · [anti-ai-slop-writing](https://github.com/jalaalrd/anti-ai-slop-writing) · [DaVinci-AutoEdit-Agent](https://github.com/liuluhaixiu/DaVinci-AutoEdit-Agent) · [xiaoma-durex-copywriter](https://github.com/crawfordxx/xiaoma-durex-copywriter) · [humanizer-skill](https://github.com/Aboudjem/humanizer-skill) · [xiaohu-ip-studio](https://github.com/xiaohuailabs/xiaohu-ip-studio) · [ai-video-editing-skill](https://github.com/znyupup/ai-video-editing-skill) · [easyedit](https://github.com/blixvip/easyedit) · [chaojifeng-video-content-creator](https://github.com/mileson/chaojifeng-video-content-creator) · [skills-videos-cortos](https://github.com/JustCarlos30/skills-videos-cortos) · [十五画境](https://github.com/liuhaisi2026212-maker/motion-palette-15) · [chinese-de-ai-writing](https://github.com/tangwenwen-md/chinese-de-ai-writing) · [sph-work-skills](https://github.com/skystmm/sph-work-skills) · [Eason-Agent-Skills](https://github.com/EasonZhu1997/Eason-Agent-Skills) · [workbuddy-media-desk](https://github.com/phs-bitqun/workbuddy-media-desk) · [viral-structure-teardown](https://github.com/JuneYaooo/viral-structure-teardown) · [skills](https://github.com/HoneyVid/skills)

<a id="faq"></a>
## 常见问题

### 做小红书有哪些好用的 skill？

收录的项目里，明确针对小红书的有 142 个，星数最高的是 [Agent-Reach](https://github.com/Panniantong/Agent-Reach)、[guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill)、[AiToEarn](https://github.com/yikart/AiToEarn)。写笔记看[文案和内容创作](#group-writing)，排版和做封面看[排版、封面配图和短视频](#group-visual)，想自动发布看[发布和自动化](#group-publish)。完整对照见[按平台查找](#by-platforms)。

### 有写公众号文章、排版和发布的 skill 吗？

有。针对微信公众号的有 101 个，星数最高的是 [guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill)、[AiToEarn](https://github.com/yikart/AiToEarn)、[baoyu-skills](https://github.com/JimLiu/baoyu-skills)。多数能把 Markdown 排成公众号样式，不少能直接推到草稿箱，最后发出去一般还要你在后台自己点。

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

针对 X 的有 93 个，YouTube 130 个，TikTok 105 个，LinkedIn 53 个。不挑平台的通用项目有 29 个，星数最高的是 [humanizer](https://github.com/blader/humanizer)、[TrendRadar](https://github.com/sansan0/TrendRadar)、[Humanizer-zh](https://github.com/op7418/Humanizer-zh)。

### 让 agent 自动发帖安全吗？会不会封号？

有两层风险。一是账号：自动发布多半要用你的账号登录，有的把 cookie 存在本地，装之前要看清楚登录态存在哪、有没有发到别的服务器。二是平台规则：各平台都限制自动化操作，批量发布、频繁互动可能被限流或封号。稳妥的用法是让 agent 写好、排好，最后一步自己点发布。

### 这些项目安全吗？

收录前逐个核对过仓库说明、目录和文件，并用脚本查过二进制和压缩包、安装钩子、远程执行和读敏感文件。收录了 354 个 skill 项目和 51 个工具与平台。看过但没收的，原因逐条记在 [data/ignore.toml](data/ignore.toml)（目前 344 个）。正常的 skill 只是几份文本文件，用不着 exe 或 dmg。脚本查不到不等于安全，安装前先读一遍它的 `SKILL.md` 和脚本。

### 多久更新一次？

每周一自动刷新星数、最近更新时间和许可证，并搜索新仓库；新仓库人工核对后才收录，见[本周新增](#new)。

<a id="resources"></a>
## 相关资源

- [awesome-seo-geo-skills](https://github.com/UnderleveledBuilder/awesome-seo-geo-skills)：SEO 和 GEO skill 精选，让搜索引擎和 AI 回答找到你的内容
- [awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills)：AI 短剧 · 漫剧 skill 精选，从剧本到分镜和视频提示词
- [awesome-story-skills](https://github.com/UnderleveledBuilder/awesome-story-skills)：让大模型讲好故事的方法合集，写口播稿、故事化文案也能用
- [anthropics/skills](https://github.com/anthropics/skills)：官方 Agent Skills 仓库，含规范和示例，想自己写 skill 可以从这里看起
- [vercel-labs/skills](https://github.com/vercel-labs/skills)：`npx skills` 安装工具，配套目录 [skills.sh](https://skills.sh)

## 参与贡献

推荐项目可以[提交 issue](../../issues/new?template=submit-skill.yml)，也可以直接改 `data/skills.toml` 发 PR，详见 [CONTRIBUTING.md](CONTRIBUTING.md)。自己写的自媒体 skill 也欢迎自荐。

<a id="badge"></a>
## 收录徽章

项目已被收录的作者，可以在自己的 README 里加上这个徽章：

[![收录于 Awesome Social Media Skills](https://img.shields.io/badge/%E6%94%B6%E5%BD%95%E4%BA%8E-Awesome_Social_Media_Skills-ff2442)](https://github.com/UnderleveledBuilder/awesome-social-media-skills)

```markdown
[![收录于 Awesome Social Media Skills](https://img.shields.io/badge/%E6%94%B6%E5%BD%95%E4%BA%8E-Awesome_Social_Media_Skills-ff2442)](https://github.com/UnderleveledBuilder/awesome-social-media-skills)
```

## 许可

[CC0 1.0](LICENSE)

---

维护者：X [@UnderleveledDev](https://x.com/UnderleveledDev)
