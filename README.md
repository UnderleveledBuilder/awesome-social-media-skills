<!-- 本文件由 scripts/build.py 生成，请勿手改。要改内容请编辑 data/ 或 templates/ 后重新生成。 -->

# Awesome Social Media Skills

**中文** · [English](README.en.md)

> 自媒体运营 Skill（技能包）精选：小红书、抖音、公众号、视频号、B 站，以及 X、YouTube、TikTok、LinkedIn。从选题、写稿、配图到发布和看数据，装进千问、豆包、龙虾（OpenClaw）、WorkBuddy、Claude Code、Codex 等智能体就能用。
>
> A curated list of agent skills for social media: Xiaohongshu (RedNote), Douyin, WeChat, Bilibili, X, YouTube, TikTok and LinkedIn.

这里收录给 AI 智能体（agent）用的自媒体 skill：写小红书笔记和公众号文章、做封面和短视频、定时发布、追热点、回评论、看数据。大多是标准 SKILL.md 格式，支持技能的智能体都能装，装法见[常见问题](#faq)。每个项目都经过人工核对，收录前用脚本做过安全检查，按要干的活和平台整理。

收录 174 个 skill 项目 + 24 个 MCP 工具和开源平台 · 元数据更新于 2026-10-27

**图例**：🌟 精选 · 📝 提示词文件（非标准 skill）· 🔌 MCP 或命令行工具 · 🧩 完整应用 · 💤 超过 180 天未更新 · 📦 已归档 · ⚠️ 仓库失效

**让 agent 帮你挑**：这份清单也是一个 skill。运行 `npx skills add UnderleveledBuilder/awesome-social-media-skills` 装上 social-media-skill-finder，再问你的 agent「我做小红书美妆号，装哪个 skill 写笔记？」。

> [!WARNING]
> 能替你发帖、回私信的工具，多半要用你的账号登录，有的会把 cookie 存在本地。装之前先读它的 SKILL.md 和脚本，看登录态存在哪、发给了谁。平台限制自动化操作，批量发布可能被限流或封号。

> [!NOTE]
> 「人工核对」指核对过仓库说明、目录结构和分类，不等于实测过效果。「安全检查」是用脚本查二进制和压缩包、安装钩子、远程执行和读敏感文件，并列出脚本里的联网地址；查不到不等于安全。

## 目录

- [本周新增](#new)（3）
- [按类型](#by-group)
  - [全流程运营：选题 → 创作 → 发布 → 复盘](#group-pipeline)（34）
  - [文案和内容创作](#group-writing)（18）
  - [排版、封面配图和短视频](#group-visual)（51）
  - [发布和自动化](#group-publish)（22）
  - [选题、热点和数据分析](#group-research)（41）
  - [账号定位和增长](#group-strategy)（8）
  - [MCP 和命令行工具（不是 skill）](#group-mcp)（15）
  - [相关开源平台（完整应用，不是 skill）](#group-apps)（9）
- [按平台查找](#by-platforms)
- [常见问题](#faq)
- [相关资源](#resources)
- [收录徽章](#badge)

<a id="new"></a>
## 本周新增

近 7 天新收录 3 个：

- [cy-carousel-skill](https://github.com/chengyi-ai/cy-carousel-skill) ★428：AI 科技类小红书图文轮播：给一个选题，查证一手出处、只用开放授权素材，排成封面加 10 页，附标题、正文、置顶评论和来源清单，出图前自动检查
- [digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) ★1k：AI 数字人口播：一张照片加一句话出成片，写稿、分段对口型生成、统一音色、加字幕，5 种剪辑风格和 48 个包装组件，生成前先报价等你确认
- [ian-xhs-carousel](https://github.com/helloianneo/ian-xhs-carousel) ★272：把文章、案例或笔记排成 3:4 小红书图文：先出分镜表等你确认，再按 20 个母版出图，浅色深色两套，附总览图和可改的 HTML

<a id="by-group"></a>
## 按类型

<a id="group-pipeline"></a>
### 全流程运营：选题 → 创作 → 发布 → 复盘

一套 skill 管到底：找选题、写稿配图、发出去、看数据，适合一个人运营一个或几个账号。

- 🌟 **[baoyu-skills](https://github.com/JimLiu/baoyu-skills)** · ★ 27k<br>宝玉的 skill 合集：小红书图文、文章配图、封面、信息图，发布到公众号、X 和微博，另有翻译和网页转 Markdown<br><sub>平台：小红书 · 公众号 · 微博 · X</sub><br><sub>更新于 2026-09-10 · 多语言 · 22 个 skill · MIT</sub>

- 🌟 **[wewrite](https://github.com/imraywang/wewrite)** · ★ 3.5k<br>公众号全流程：抓热点、评选题、搜素材、按你的风格写稿并审稿，可选配图、18 套排版和推送草稿箱，改稿后能学你的改法<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-10-26 · 中文 · 10 个 skill · MIT</sub>

- **[sergebulaev/linkedin-skills](https://github.com/sergebulaev/linkedin-skills)** · ★ 5.2k<br>LinkedIn 12 个 skill：按你的口吻写帖子和评论、分析信息流、排发帖节奏，去 AI 腔，发布前等你批准<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-10-27 · 英文 · 14 个 skill · MIT</sub>

- **[yichen-skills](https://github.com/mcncarl/yichen-skills)** · ★ 4.8k<br>逸尘的创作者 skill：写作、把内容切成 X 推文、推送 X Articles 草稿、存公众号文章，导出自己的小红书、抖音收藏和 X 书签<br><sub>平台：小红书 · 抖音 · 公众号 · X</sub><br><sub>更新于 2026-10-27 · 多语言 · 17 个 skill</sub>

- **[charlie947/social-media-skills](https://github.com/charlie947/social-media-skills)** · ★ 4.4k<br>17 个社媒 skill：学你的口吻、写 LinkedIn 帖子、调研、看数据、写 Reels 脚本、生成 Gemini 配图提示词<br><sub>平台：Instagram · LinkedIn · Newsletter</sub><br><sub>更新于 2026-10-18 · 英文 · 17 个 skill · MIT</sub>

- **[instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill)** · ★ 3.3k<br>Instagram 13 个 skill：26 种钩子公式写 Reels、找本领域爆款、查文案、去 AI 腔，免费、不用注册和 API Key<br><sub>平台：Instagram</sub><br><sub>更新于 2026-09-13 · 英文 · 13 个 skill · MIT</sub>

- **[youtube-agent-skill](https://github.com/Jakeschincariol/youtube-agent-skill)** · ★ 3.3k<br>YouTube 11 个 skill：钩子打分的脚本、标题和缩略图配对检查、按字幕出剪辑单、找观众流失点、切 Shorts<br><sub>平台：YouTube</sub><br><sub>更新于 2026-09-16 · 英文 · 11 个 skill · MIT</sub><br><sub>💡 另有 ChatGPT 版：Jakeschincariol/chatgpt-youtube-agent-skill</sub>

- **[linkedin-agent-skill](https://github.com/Jakeschincariol/linkedin-agent-skill)** · ★ 2.8k<br>LinkedIn 11 个 skill：21 种钩子写帖子、评论、回复、主页打分、周计划，去 AI 腔并在发出前打分<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-09-17 · 英文 · 11 个 skill · MIT</sub>

- **[xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill)** · ★ 2.5k<br>OpenClaw 小红书运营：推荐流和账号分析、选题、创作、发布、复盘，能输入爆款链接复刻同类笔记；用浏览器自动化，首次扫码登录<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-19 💤 · 中文</sub>

- **[growth-lab](https://github.com/tsingyuai/growth-lab)** · ★ 2k<br>产品增长闭环：读懂产品、用 MediaCrawler 采小红书/抖音/B站/快手等数据做调研，执行增长动作再按结果改进<br><sub>平台：小红书 · 抖音 · B 站 · 微博 · 知乎 · 快手</sub><br><sub>更新于 2026-09-28 · 中文 · 22 个 skill · Apache-2.0</sub>

- **[creator-buddy](https://github.com/SpaceZephyr/creator-buddy)** · ★ 1.7k<br>创作者工具箱：搜小红书/B站/抖音热门、挖公众号爆款、拆竞品和评论，再起标题、写正文、配图、剪视频、出封面<br><sub>平台：小红书 · 抖音 · 公众号 · B 站</sub><br><sub>更新于 2026-08-26 · 中文 · 33 个 skill</sub>

- **[claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post)** · ★ 743<br>学你在 Facebook 的口吻写贴文，排 14 天日历，确认后发到 FB、IG、Threads、X，用已登录的 Chrome 管理留言<br><sub>平台：X · Instagram · Threads · Facebook</sub><br><sub>更新于 2026-10-15 · 中文 · 2 个 skill · MIT</sub>

- **[wechat-article-skills](https://github.com/aiworkskills/wechat-article-skills)** · ★ 713<br>公众号运营助手：选题、写稿、审稿（敏感词、错别字、AI 味）、排版、配图、发布 8 个 skill 串成一条线，每步停下等你确认<br><sub>平台：公众号</sub><br><sub>更新于 2026-09-23 · 中文 · 9 个 skill · Apache-2.0</sub>

- **[instagram-skills](https://github.com/sergebulaev/instagram-skills)** · ★ 632<br>Instagram 9 个 skill：前 125 字钩子的文案、轮播逐页规划、话题标签和周计划，读数据要 Apify，发布走 Publora<br><sub>平台：Instagram</sub><br><sub>更新于 2026-10-27 · 英文 · 11 个 skill · MIT</sub>

- **[self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow)** · ★ 626<br>模块化自媒体工作流：创作简报、账号策略、热点与竞品研究、平台原生文案、短视频方案、多平台发布、数据复盘和归档，不绑定工具<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · YouTube</sub><br><sub>更新于 2026-10-13 · 多语言 · 10 个 skill · MIT</sub>

- **[blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills)** · ★ 600<br>14 个社媒 skill：内容策略、日历、配图文案、轮播文案、涨粉分析，覆盖文字型和图片型平台<br><sub>平台：X · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-05-01 · 英文 · 14 个 skill · MIT</sub>

- **[claude-youtube](https://github.com/AgriciDaniel/claude-youtube)** · ★ 570<br>YouTube 创作者 skill：频道审计、视频 SEO、留存脚本和钩子、缩略图、内容策略、Shorts、数据和变现<br><sub>平台：YouTube</sub><br><sub>更新于 2026-04-10 💤 · 英文 · MIT</sub>

- **[rayskills](https://github.com/imraywang/rayskills)** · ★ 355<br>WeWrite 作者的工具箱：本地知识库、长文、口播稿、封面、解说视频，内容直达公众号和 X Articles 草稿箱<br><sub>平台：公众号 · X</sub><br><sub>更新于 2026-10-27 · 中文 · 8 个 skill</sub>

- **[wechat_article_skills](https://github.com/BND-1/wechat_article_skills)** · ★ 318<br>公众号四件套：科技科普写作、AI 产品经理视角写作、Markdown 转公众号排版、推送草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-01-16 💤 · 中文 · 4 个 skill</sub>

- **[claude-content-skills](https://github.com/Ootto-AI/claude-content-skills)** · ★ 297<br>Instagram Reels 内容工厂：找爆款格式、拆钩子、按你的口吻写脚本和配文、排两周日历，把评论变成销售线索<br><sub>平台：Instagram</sub><br><sub>更新于 2026-10-17 · 英文 · 54 个 skill · MIT</sub>

- **[jiji262/wechat-publisher](https://github.com/jiji262/wechat-publisher)** · ★ 286<br>公众号文章一条命令：多轮搜素材、写 3000-5000 字长文、每章配手绘信息图、排版、推送草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-08-01 · 中文</sub>

- **[social-ai-team](https://github.com/stevenflanagan1/social-ai-team)** · ★ 259<br>给小企业的社媒团队：品牌建档、月度内容日历、配图文案、LinkedIn 文章、创意和月度复盘<br><sub>平台：X · TikTok · Instagram · LinkedIn · Threads · Facebook</sub><br><sub>更新于 2026-10-07 · 英文 · 10 个 skill</sub>

- **[content-pipeline](https://github.com/OrangeViolin/content-pipeline)** · ★ 217<br>一个 skill 管内容生产和分发：收素材、出稿、排版、封面、朋友圈文案、多平台改写，用 Chrome 自动发布<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-04-12 💤 · 中文 · MIT</sub>

- **[social-media-skills/skills](https://github.com/social-media-skills/skills)** · ★ 206<br>106 个社媒 skill：品牌和口吻、内容日历、LinkedIn 帖子、短视频、设计、各平台增长、发布和数据分析<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-10-15 · 英文 · 106 个 skill · MIT</sub>

- **[wenzi-xiaohongshu-workflow](https://github.com/wenziai/wenzi-xiaohongshu-workflow)** · ★ 183<br>文子的小红书冷启动工作流：账号定位、选题标题、真人化改稿和合规检查、图文规划、排期和数据复盘<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-12 · 中文 · 6 个 skill</sub>

- **[x-skills](https://github.com/sergebulaev/x-skills)** · ★ 158<br>X 的 9 个 skill：按你的口吻写推文和长串、拆爆款推文的钩子、写回复和引用、排一周内容，发布前等你批准<br><sub>平台：X</sub><br><sub>更新于 2026-10-27 · 英文 · 11 个 skill · MIT</sub><br><sub>💡 发布走 Publora，它的免费档不含 X</sub>

- **[843645440/wechat-skill](https://github.com/843645440/wechat-skill)** · ★ 126<br>公众号内容工具包：追热点、科技写作、去 AI 味、配图和封面、12 套排版主题，写入多个账号的草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-25 · 中文 · 10 个 skill</sub>

- **[wemp-operator](https://github.com/IanShaw027/wemp-operator)** · ★ 113<br>OpenClaw 公众号运营：从 20 多个来源采集热点，生成日报周报和数据分析，检查并回复评论，写文章<br><sub>平台：公众号</sub><br><sub>更新于 2026-02-02 💤 · 中文 · MIT</sub><br><sub>💡 要先装 wemp skill</sub>

- **[tiktok-skills](https://github.com/sergebulaev/tiktok-skills)** · ★ 95<br>TikTok 8 个 skill：前 3 秒钩子脚本、配文和话题标签、蹭趋势、一周计划，按真实数据读赛道，发布走 Publora<br><sub>平台：TikTok</sub><br><sub>更新于 2026-10-27 · 英文 · 10 个 skill · MIT</sub>

- **[sergebulaev/youtube-skills](https://github.com/sergebulaev/youtube-skills)** · ★ 75<br>YouTube 和 Shorts 的包装 skill：高点击标题、带章节的 SEO 描述、留存钩子、缩略图简报、社区帖和频道主页审计<br><sub>平台：YouTube</sub><br><sub>更新于 2026-10-27 · 英文 · 11 个 skill · MIT</sub>

- **[Fully-automatic-article-generation-skill](https://github.com/solar-luna/Fully-automatic-article-generation-skill)** · ★ 72<br>AI 资讯号自动发文：抓 AI 热点，按早中晚写工具介绍、教程或行业动态，发到公众号草稿箱和小红书<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-01-21 💤 · 中文 · 5 个 skill · MIT</sub>

- **[facebook-skills](https://github.com/sergebulaev/facebook-skills)** · ★ 71<br>Facebook 公共主页 8 个 skill：按你的口吻写帖子并审稿、控制在 80 字符内提高互动、读评论、排一周内容<br><sub>平台：Facebook</sub><br><sub>更新于 2026-10-27 · 英文 · 10 个 skill · MIT</sub>

- **[threads-skills](https://github.com/sergebulaev/threads-skills)** · ★ 52<br>Threads 8 个 skill：按你的口吻写单帖和串帖、写回复、按真实数据读赛道、排一周内容，发布前等你批准<br><sub>平台：Threads</sub><br><sub>更新于 2026-10-27 · 英文 · 10 个 skill · MIT</sub>

- **[doubaoya-community](https://github.com/zizhanovo/doubaoya-community)** · ★ 11<br>都爆鸭的 13 个新媒体 skill：挖选题、追热点、写抖音小红书公众号脚本、三平台违禁词检测、写进公众号草稿箱<br><sub>平台：小红书 · 抖音 · 公众号</sub><br><sub>更新于 2026-10-14 · 中文 · 13 个 skill</sub><br><sub>💡 大部分 skill 要在 doubaoya.com 生成 API Key</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# baoyu-skills
npx skills add JimLiu/baoyu-skills
# wewrite
npx skills add imraywang/wewrite
# sergebulaev/linkedin-skills
npx skills add sergebulaev/linkedin-skills
# yichen-skills
npx skills add mcncarl/yichen-skills
# charlie947/social-media-skills
npx skills add charlie947/social-media-skills
# instagram-agent-skill
npx skills add Jakeschincariol/instagram-agent-skill
# youtube-agent-skill
npx skills add Jakeschincariol/youtube-agent-skill
# linkedin-agent-skill
npx skills add Jakeschincariol/linkedin-agent-skill
# xiaohongshu-ops-skill
npx skills add Xiangyu-CAS/xiaohongshu-ops-skill
# growth-lab
npx skills add tsingyuai/growth-lab
# creator-buddy
npx skills add SpaceZephyr/creator-buddy
# claude-skill-social-post
npx skills add Hao0321/claude-skill-social-post
# wechat-article-skills
npx skills add aiworkskills/wechat-article-skills
# instagram-skills
npx skills add sergebulaev/instagram-skills
# self-media-content-workflow
npx skills add yanhua1010/self-media-content-workflow
# blacktwist/social-media-skills
npx skills add blacktwist/social-media-skills
# claude-youtube
npx skills add AgriciDaniel/claude-youtube
# rayskills
npx skills add imraywang/rayskills
# wechat_article_skills
npx skills add BND-1/wechat_article_skills
# claude-content-skills
npx skills add Ootto-AI/claude-content-skills
# jiji262/wechat-publisher
npx skills add jiji262/wechat-publisher
# social-ai-team
npx skills add stevenflanagan1/social-ai-team
# content-pipeline
npx skills add OrangeViolin/content-pipeline
# social-media-skills/skills
npx skills add social-media-skills/skills
# wenzi-xiaohongshu-workflow
npx skills add wenziai/wenzi-xiaohongshu-workflow
# x-skills
npx skills add sergebulaev/x-skills
# 843645440/wechat-skill
npx skills add 843645440/wechat-skill
# wemp-operator
npx skills add IanShaw027/wemp-operator
# tiktok-skills
npx skills add sergebulaev/tiktok-skills
# sergebulaev/youtube-skills
npx skills add sergebulaev/youtube-skills
# Fully-automatic-article-generation-skill
npx skills add solar-luna/Fully-automatic-article-generation-skill
# facebook-skills
npx skills add sergebulaev/facebook-skills
# threads-skills
npx skills add sergebulaev/threads-skills
# doubaoya-community
npx skills add zizhanovo/doubaoya-community
```

</details>

<a id="group-writing"></a>
### 文案和内容创作

写笔记、推文、标题、口播稿和长文，改写成各平台的口吻，去 AI 味，发布前查违禁词和限流风险。

- 🌟 **[humanizer](https://github.com/blader/humanizer)** · ★ 61.4k<br>英文去 AI 腔：按维基百科编辑识别 AI 文本的那份特征清单逐条改写，不改原意<br><sub>平台：通用</sub><br><sub>更新于 2026-10-16 · 英文 · MIT</sub>

- 🌟 **[Humanizer-zh](https://github.com/op7418/Humanizer-zh)** · ★ 21.2k<br>中文去 AI 味：删改空话、重复和模板化表达，保留事实、确定程度和作者声音，没问题的句子不改<br><sub>平台：通用</sub><br><sub>更新于 2026-09-23 · 中文 · MIT</sub>

- **[human-writing](https://github.com/KKKKhazix/human-writing)** · ★ 4.2k<br>活人感写作：知乎回答、公众号文章、评测、口播稿等中文写作，先查够材料再写，读起来像一个具体的人在说话<br><sub>平台：公众号 · 知乎</sub><br><sub>更新于 2026-08-11 · 中文 · MIT</sub>

- **[writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill)** · ★ 2.7k<br>写作蒸馏器：从至少 20 篇文章里蒸馏一个账号或作者的写作 DNA（语言、结构、选题、素材），之后按这套 DNA 写<br><sub>平台：小红书 · 公众号 · 微博 · Newsletter</sub><br><sub>更新于 2026-08-24 · 中文 · 2 个 skill · MIT</sub>

- **[ai-copywriter](https://github.com/mikiarlo3/ai-copywriter)** · ★ 1.2k<br>文案和去 AI 腔一起做：标题、短描述、微文案、邮件主题，按 LinkedIn 的短段落节奏写帖子<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-08-01 · 英文 · MIT</sub>

- **[Viral_Writer_Skill](https://github.com/nashsu/Viral_Writer_Skill)** · ★ 808<br>给一个主题，按 11 个内容洞见维度写成整篇文章，附 5 个备选标题和每张配图的提示词，公众号、小红书、抖音三种写法<br><sub>平台：小红书 · 抖音 · 公众号</sub><br><sub>更新于 2026-03-24 💤 · 中文</sub>

- **[yuwen-publish-precheck](https://github.com/yuwen-cool/yuwen-publish-precheck)** · ★ 794<br>发布前审：口播稿、图文、字幕、封面字能不能发抖音/小红书/视频号，指出哪句踩线、依据哪条官方规则，给改法<br><sub>平台：小红书 · 抖音 · 视频号</sub><br><sub>更新于 2026-10-08 · 中文 · MIT</sub>

- **[qu-ai-wei](https://github.com/LifelongLazyLearner/qu-ai-wei)** · ★ 703<br>简体中文去 AI 味：清理套话、翻译腔和机械排比，保留事实、正式程度和原文声口<br><sub>平台：通用</sub><br><sub>更新于 2026-09-10 · 中文 · MIT</sub>

- **[anti-ai-slop-writing](https://github.com/jalaalrd/anti-ai-slop-writing)** · ★ 572<br>英文去 AI 腔：推文、邮件、文章、简介、配图文案都按可检测的 AI 写作特征逐条避开<br><sub>平台：通用</sub><br><sub>更新于 2026-04-18 💤 · 英文</sub>

- **[writing-agent](https://github.com/dongbeixiaohuo/writing-agent)** · ★ 442<br>多 agent 写稿：写作导演、主笔、读者审校、去 AI 味专家一起从选题写到成稿，能从公众号样文建风格档案；另有 Windows 客户端<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-22 · 中文 · 3 个 skill · MIT</sub>

- **[xiaoma-durex-copywriter](https://github.com/crawfordxx/xiaoma-durex-copywriter)** · ★ 338<br>杜蕾斯式借势文案和海报：双层语义和 8 个文案公式，拆自 260 张原始海报，适合热点、节日、产品卖点<br><sub>平台：通用</sub><br><sub>更新于 2026-08-08 · 中文</sub>

- **[humanizer-skill](https://github.com/Aboudjem/humanizer-skill)** · ★ 291<br>英文去 AI 腔并打分：识别 55 种 AI 写作特征，按 5 种口吻改写，给 0-100 的 AI 痕迹分，本地运行<br><sub>平台：通用</sub><br><sub>更新于 2026-09-06 · 英文 · MIT</sub>

- **[content-skills](https://github.com/vyralcontent/content-skills)** · ★ 173<br>短视频钩子、脚本和轮播：从 20 万条爆款视频总结写法，覆盖 TikTok、Reels 和 Shorts，也写配文和行动号召<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-06-22 · 英文 · 7 个 skill · MIT</sub>

- **[gainubi/wechat-skills](https://github.com/gainubi/wechat-skills)** · ★ 172<br>小盖的公众号写作 skill：从 3–10 篇文章梳理文风 DNA，按 DNA 写初稿，给文章做扁平风解释配图<br><sub>平台：公众号</sub><br><sub>更新于 2026-05-21 · 中文 · 7 个 skill</sub>

- **[traffic-compass](https://github.com/code-wahaha/traffic-compass)** · ★ 96<br>抖音发布前自查：查广告法违禁词、引流词、AI 标注和资质红线，给最小改法，再按粉丝量和赛道估播放区间<br><sub>平台：抖音</sub><br><sub>更新于 2026-07-07 · 中文 · MIT</sub>

- **[media-publish-check](https://github.com/XshuiAi/media-publish-check)** · ★ 69<br>发布前审核：抖音、小红书、视频号、快手的视频和图文能不能直接发、问题在哪、怎么改，并按平台改写<br><sub>平台：小红书 · 抖音 · 视频号 · 快手</sub><br><sub>更新于 2026-07-22 · 中文 · MIT</sub>

- **[content-risk-detector](https://github.com/liuxingqitd/content-risk-detector)** · ★ 57<br>短视频逐字稿合规检测：按抖音、小红书、视频号社区规范找风险点，出分级报告和修改建议<br><sub>平台：小红书 · 抖音 · 视频号</sub><br><sub>更新于 2026-09-14 · 中文 · MIT</sub>

- **[xiaohongshu-doctor](https://github.com/softbread/xiaohongshu-doctor)** · ★ 3<br>小红书笔记发布前体检：内容质量、关键词、标题吸引力、敏感内容风险、商业化程度和互动潜力<br><sub>平台：小红书</sub><br><sub>更新于 2026-01-15 💤 · 中文</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# humanizer
npx skills add blader/humanizer
# Humanizer-zh
npx skills add op7418/Humanizer-zh
# human-writing
npx skills add KKKKhazix/human-writing
# writing-dna-skill
npx skills add larashero3-dotcom/writing-dna-skill
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
# media-publish-check
npx skills add XshuiAi/media-publish-check
# content-risk-detector
npx skills add liuxingqitd/content-risk-detector
# xiaohongshu-doctor
npx skills add softbread/xiaohongshu-doctor
```

</details>

<a id="group-visual"></a>
### 排版、封面配图和短视频

公众号排版、做封面和信息卡片、配图，剪短视频、加字幕、写分镜。

- 🌟 **[guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill)** · ★ 7.8k<br>歸藏的图文卡片：小红书组图、Live Photo 动态卡、公众号 21:9+1:1 封面对，杂志风和瑞士风两套视觉、28 种版式<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-07-01 · 中文 · AGPL-3.0</sub>

- 🌟 **[gzh-design-skill](https://github.com/isjiamu/gzh-design-skill)** · ★ 4.2k<br>公众号排版：Markdown 排成能直接粘进公众号编辑器的 HTML，6 套主题加主题生成器，样式全内联不掉格式<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-21 · 中文</sub>

- **[html-anything](https://github.com/nexu-io/html-anything)** · ★ 9.3k<br>本地 agent 写 HTML 的编辑器：75 个 skill 做杂志长文、海报、小红书图、推文卡、幻灯片，一键发公众号、X、知乎或导出 PNG<br><sub>平台：小红书 · 公众号 · 知乎 · X</sub><br><sub>更新于 2026-10-13 · 🧩 应用 · 多语言 · 81 个 skill · Apache-2.0</sub>

- **[md2wechat-skill](https://github.com/geekjourneyx/md2wechat-skill)** · ★ 3.8k<br>公众号创作与发布 CLI：Markdown 排版、AI 配图和封面、预览校验、推送草稿箱，也能让浏览器 agent 存知乎、头条草稿<br><sub>平台：公众号 · 知乎 · 头条</sub><br><sub>更新于 2026-10-14 · 中文</sub><br><sub>💡 部分功能要向作者申请 API Key</sub>

- **[youtube-shorts-pipeline](https://github.com/rushindrasinha/youtube-shorts-pipeline)** · ★ 2.3k<br>竖屏短视频流水线：一个选题自动调研、写脚本、出画面、配音、加字幕并上传，每条约 0.11 美元<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-06-09 · 英文 · MIT</sub>

- **[herk-edit-kit](https://github.com/nateherkai/herk-edit-kit)** · ★ 2.3k<br>Nate Herk 的口播剪辑包：按字幕剪掉停顿和口误、规划叙事、406 张动效卡片和 HyperFrames 模板，做 Reels 和 Shorts<br><sub>平台：YouTube · Instagram</sub><br><sub>更新于 2026-10-14 · 英文 · 15 个 skill</sub>

- **[Youtube-clipper-skill](https://github.com/op7418/Youtube-clipper-skill)** · ★ 2.3k<br>YouTube 剪辑：下载视频、按语义分章节、剪片段、字幕翻译成双语并烧进视频<br><sub>平台：YouTube</sub><br><sub>更新于 2026-01-22 💤 · 中文 · MIT</sub>

- **[video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker)** · ★ 1.7k<br>选题变成 4K 解说视频：调研、写稿、本地免费 TTS、Remotion 合成，适配 B 站、YouTube、小红书、抖音、视频号<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · YouTube</sub><br><sub>更新于 2026-10-01 · 多语言 · 3 个 skill · MIT</sub>

- **[rnskill](https://github.com/Pluviobyte/rnskill)** · ★ 1.7k<br>雪踏乌云的 skill 合集：选题、脚本改写、AI 配音、数字人、剪口播、字幕、封面和图文，另有编码类 skill<br><sub>平台：小红书 · 抖音 · 公众号</sub><br><sub>更新于 2026-09-21 · 中文 · 62 个 skill</sub>

- **[xhs-visual-director-skill](https://github.com/ziguishian/xhs-visual-director-skill)** · ★ 1.4k<br>小红书视觉导演：先问 10 个问题，规划多页图文和每页视觉，出 1 张样图确认后生成整套，附发布文案和自检清单<br><sub>平台：小红书</sub><br><sub>更新于 2026-07-03 · 中文 · MIT</sub>

- **[Punk-Skill](https://github.com/adrianpunk/Punk-Skill)** · ★ 1.4k<br>Punk 风格视觉：文章封面（小红书、公众号）、头像、人物 IP 视频封面，共用一个风格库<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-10-11 · 中文 · 3 个 skill</sub><br><sub>💡 个人非商用免费；企业、团队或商业用途要先买授权</sub>

- **[qiaomu-mondo-poster-design](https://github.com/joeseesun/qiaomu-mondo-poster-design)** · ★ 1.3k<br>乔木的 Mondo 风海报：一句话按 33 位设计师风格生成海报、书封、专辑封面，支持公众号封面 21:9、小红书配图 3:4<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-03-19 💤 · 中文 · MIT</sub>

- **[clipforge](https://github.com/xixihhhh/clipforge)** · ★ 1.1k<br>带货短视频：上传一张商品图，提炼卖点、写种草脚本、配画面配音字幕，出抖音小店、快手、小红书、TikTok Shop 视频<br><sub>平台：小红书 · 抖音 · 快手 · TikTok</sub><br><sub>更新于 2026-10-26 · 中文 · 2 个 skill · AGPL-3.0</sub><br><sub>💡 skill 调用本地部署的 ClipForge 应用</sub>

- **[video-spec-builder](https://github.com/feicaiclub/video-spec-builder)** · ★ 1k<br>视频导演式追问：把「想做个视频」问成精确到秒的分镜脚本 video-spec.md，交给 HyperFrames 渲染<br><sub>平台：通用</sub><br><sub>更新于 2026-05-18 · 多语言 · MIT</sub>

- **[digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo)** · ★ 1k<br>AI 数字人口播：一张照片加一句话出成片，写稿、分段对口型生成、统一音色、加字幕，5 种剪辑风格和 48 个包装组件，生成前先报价等你确认<br><sub>平台：通用</sub><br><sub>更新于 2026-10-26 · 多语言 · 2 个 skill · MIT</sub><br><sub>💡 视频经 Renoise MCP 生成，按积分付费</sub>

- **[gbro-cover-design](https://github.com/pyang5166/gbro-cover-design)** · ★ 932<br>公众号/小红书封面提示词：读完文章问三轮，按 10 种构图出 3:4 真人出镜封面提示词，基于 oh-my-cover-design 改进<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-07-15 · 中文</sub>

- **[vibe-knowledge-film](https://github.com/HeyChengC/vibe-knowledge-film)** · ★ 715<br>抖音「知识大赏」类知识短片：两种热门画风，写字幕稿、排分镜表、配音效，先出 30 秒样片再出成片<br><sub>平台：抖音</sub><br><sub>更新于 2026-10-13 · 中文</sub>

- **[gimi-illustration-skill](https://github.com/GiMi-Xiaomi/gimi-illustration-skill)** · ★ 712<br>中文文章和口播配图：把判断、流程、对比画成一眼能懂的图，三种画风，可换成自己的 IP 形象<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-03 · 中文 · MIT</sub>

- **[xiaohu-wechat-format](https://github.com/xiaohuailabs/xiaohu-wechat-format)** · ★ 706<br>公众号一键排版加发布：Markdown 转微信兼容 HTML，85 套主题和可视化画廊挑选，可选生成封面，推送草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-06-12 · 中文 · 2 个 skill</sub>

- **[clipify](https://github.com/louisedesadeleer/clipify)** · ★ 613<br>长视频切短片：转写后找笑点、反转和高能片段，剪成 9:16 并跟踪人脸，烧录 Opus 风格字幕<br><sub>平台：通用</sub><br><sub>更新于 2026-08-24 · 英文 · MIT</sub>

- **[chatgpt-video-editing-skills](https://github.com/Jaycheng1103/chatgpt-video-editing-skills)** · ★ 606<br>用 ChatGPT/Codex 剪竖屏短视频：一个 skill 装好剪辑环境，一个按 8 步把你的素材剪成 Reels、Shorts、TikTok<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-07-26 · 多语言 · 2 个 skill · MIT</sub>

- **[Document-illustrator-skill](https://github.com/op7418/Document-illustrator-skill)** · ★ 606<br>从文档归纳要点生成多张配图，歸藏调过的三种风格，16:9 和 3:4 两种比例，适合发小红书和推特<br><sub>平台：小红书 · X</sub><br><sub>更新于 2026-01-21 💤 · 中文 · MIT</sub>

- **[smart-illustrator](https://github.com/axtonliu/smart-illustrator)** · ★ 566<br>文章配图：自动找该配图的位置生成插图，也能批量出 PPT 信息图和 YouTube 缩略图，Gemini、Excalidraw、Mermaid 三种引擎<br><sub>平台：YouTube</sub><br><sub>更新于 2026-06-26 · 多语言 · MIT</sub>

- **[DaVinci-AutoEdit-Agent](https://github.com/liuluhaixiu/DaVinci-AutoEdit-Agent)** · ★ 496<br>达芬奇自动剪辑：分析素材、写文案、配音、搭剪辑蓝图并在 DaVinci Resolve 时间线成片，每步等你确认<br><sub>平台：通用</sub><br><sub>更新于 2026-06-12 · 多语言 · 3 个 skill · MIT</sub><br><sub>💡 要 DaVinci Resolve Studio</sub>

- **[claude-design-card](https://github.com/geekjourneyx/claude-design-card)** · ★ 471<br>把文本或网页做成可发布卡片：平台封面、社交分享卡、长文排版 14 种格式，统一 Claude 设计风格<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · YouTube</sub><br><sub>更新于 2026-05-27 · 中文</sub>

- **[motion-graphics-skills](https://github.com/charlie947/motion-graphics-skills)** · ★ 435<br>用代码做动效：发布会视频、动态图表、数字滚动，适合发 LinkedIn 和 Newsletter，不用 After Effects<br><sub>平台：LinkedIn · Newsletter</sub><br><sub>更新于 2026-10-11 · 英文 · 15 个 skill · MIT</sub>

- **[atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover)** · ★ 429<br>阿囤囤风小红书封面提示词：真人出镜、超大浅黄白描边标题、勾选清单和贴纸，适合 AI 工具、测评和教程类内容<br><sub>平台：小红书</sub><br><sub>更新于 2026-05-30 · 中文</sub>

- **[cy-carousel-skill](https://github.com/chengyi-ai/cy-carousel-skill)** · ★ 428<br>AI 科技类小红书图文轮播：给一个选题，查证一手出处、只用开放授权素材，排成封面加 10 页，附标题、正文、置顶评论和来源清单，出图前自动检查<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-17 · 中文</sub>

- **[hotclip](https://github.com/xixihhhh/hotclip)** · ★ 385<br>长视频和直播回放切成竖屏爆款片段：AI 找高光并说明理由、横转竖、自动字幕、去气口，本地运行不上传<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手</sub><br><sub>更新于 2026-10-26 · 中文 · AGPL-3.0</sub>

- **[clipcat-skill](https://github.com/Clipcat-ai/clipcat-skill)** · ★ 350<br>TikTok Shop 带货视频：找爆款视频、研究商品店铺达人和直播间、拆为什么能卖，生成可拍的提示词<br><sub>平台：TikTok</sub><br><sub>更新于 2026-10-24 · 英文</sub><br><sub>💡 要 Clipcat 账号</sub>

- **[xiaohu-ip-studio](https://github.com/xiaohuailabs/xiaohu-ip-studio)** · ★ 300<br>小互的中文深度文配图：挑认知锚点、现编隐喻、反 PPT 自检，自带 31 个原创 IP 角色出演<br><sub>平台：通用</sub><br><sub>更新于 2026-06-26 · 中文 · MIT</sub>

- **[panda-video-generator](https://github.com/szhshp/panda-video-generator)** · ★ 292<br>程序员式视频自动化：抓素材、生成字幕脚本、Remotion 渲染、Playwright 多平台发布，每个环节可单独用<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手 · YouTube</sub><br><sub>更新于 2026-10-18 · 中文 · 6 个 skill</sub>

- **[oil-cover](https://github.com/oil-oil/oil-cover)** · ★ 282<br>从视频画面做小红书和 B 站封面：本地选帧打分，按真实屏幕画面加标题出三种画幅，适合 AI 工具实操视频<br><sub>平台：小红书 · B 站</sub><br><sub>更新于 2026-10-04 · 中文</sub>

- **[ian-xhs-carousel](https://github.com/helloianneo/ian-xhs-carousel)** · ★ 272<br>把文章、案例或笔记排成 3:4 小红书图文：先出分镜表等你确认，再按 20 个母版出图，浅色深色两套，附总览图和可改的 HTML<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-21 · 中文 · MIT</sub>

- **[oh-my-cover-design](https://github.com/hongfamonvAI/oh-my-cover-design)** · ★ 272<br>小红书/公众号封面提示词：问完构图、人脸、表情、产品图、配色和字体，输出能直接跑图的提示词，10 种构图<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-05-16 · 中文</sub>

- **[douyin-live-recorder](https://github.com/WeiZhuochun/douyin-live-recorder)** · ★ 261<br>抖音直播切片号：多直播间监控、开播自动录制、边录边传百度网盘、高光识别剪辑、生成标题、多授权账号发布<br><sub>平台：抖音</sub><br><sub>更新于 2026-08-26 · 中文</sub>

- **[blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video)** · ★ 255<br>一句话出中文竖屏短视频：脚本、配音、画面、配乐、字幕、音效全自动，脚本、配音、画面三道关都可审<br><sub>平台：小红书 · 抖音 · B 站 · YouTube</sub><br><sub>更新于 2026-07-20 · 中文 · 2 个 skill</sub>

- **[xhs-cover-skill](https://github.com/Vivixiao980/xhs-cover-skill)** · ★ 213<br>小红书封面生成：18 种预设风格，命令行出图或改图，优先用 Codex 自带的生图，Gemini 作备用<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-24 · 中文</sub>

- **[blcaptain-style-skill](https://github.com/dososo/blcaptain-style-skill)** · ★ 176<br>中文图文卡片：一段内容做成小红书 3:4 组图或公众号封面，三套视觉语言（静纸、实证、图桥）<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-07-08 · 中文</sub>

- **[ai-video-editing-skill](https://github.com/znyupup/ai-video-editing-skill)** · ★ 166<br>旅行 Vlog 自动剪辑：给一个素材文件夹，agent 挑镜头、排叙事、加字幕出成片，用 ffmpeg、Whisper 和视觉模型<br><sub>平台：通用</sub><br><sub>更新于 2026-04-27 💤 · 中文 · MIT</sub>

- **[xhs-writer-skill](https://github.com/JuneYaooo/xhs-writer-skill)** · ★ 165<br>小红书笔记一条龙：一句话生成竖版卡片组或短视频脚本，配文案和话题标签，有真实素材时用 gpt-image-2 图生图<br><sub>平台：小红书</sub><br><sub>更新于 2026-04-25 💤 · 中文 · Apache-2.0</sub>

- **[reelclaw](https://github.com/dansugc/reelclaw)** · ★ 147<br>给你在做的产品做 UGC 短视频广告：真人创作者反应镜头加产品画面，本地剪辑渲染，出 TikTok、Reels、Shorts<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-10-23 · 英文</sub><br><sub>💡 反应镜头来自 DansUGC，按条用积分付费</sub>

- **[jianshuo/claude-skills](https://github.com/jianshuo/claude-skills)** · ★ 137<br>王建硕日常用的 skill：转写、翻译、配音、多机位剪辑、字幕烧录、横转竖，另有公众号发布<br><sub>平台：公众号 · X · YouTube</sub><br><sub>更新于 2026-10-27 · 多语言 · 42 个 skill · MIT</sub>

- **[threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill)** · ★ 117<br>把文字帖做成轮播图：适配 Threads、Instagram、LinkedIn、TikTok 和快拍尺寸<br><sub>平台：TikTok · Instagram · LinkedIn · Threads</sub><br><sub>更新于 2026-04-19 💤 · 英文 · MIT</sub>

- **[freestylefly/xiaohongshu-skills](https://github.com/freestylefly/xiaohongshu-skills)** · ★ 97<br>按主题生成小红书风格封面，生图用 Nano Banana Pro<br><sub>平台：小红书</sub><br><sub>更新于 2026-01-26 💤 · 中文</sub><br><sub>💡 要在 api.canghe.ai 申请 API Key</sub>

- **[wechat-article-formatter-skill](https://github.com/iamzifei/wechat-article-formatter-skill)** · ★ 76<br>公众号排版：Markdown 经 bm.md 渲染成带样式的 HTML，可自定义样式，再用官方 API 发布<br><sub>平台：公众号</sub><br><sub>更新于 2026-08-12 · 英文</sub>

- **[wechat-typesetting-cy](https://github.com/CY-CHENYUE/wechat-typesetting-cy)** · ★ 74<br>公众号智能排版：不套模板，读懂文章后现场设计版式和配色，生成全内联 HTML，预览页一键复制<br><sub>平台：公众号</sub><br><sub>更新于 2026-09-19 · 中文 · Apache-2.0</sub>

- **[claude-reel-editor](https://github.com/nicolapocock/claude-reel-editor)** · ★ 35<br>口播原片剪成品牌化短视频：清理音频、剪掉口头禅、加图形和字幕，渲染前先让你审，用 HyperFrames<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-10-12 · 英文 · MIT</sub>

- **[tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills)** · ★ 18<br>短视频模板：Reels、TikTok、Shorts 的钩子和结构、逐字动态字幕、倒计时、人名条<br><sub>平台：YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-06-22 · 英文 · 4 个 skill · MIT</sub>

- **[social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes)** · ★ 7<br>检查并裁切社媒图片尺寸：按 Instagram、Facebook、X、LinkedIn、YouTube、TikTok、Pinterest 等平台规格校验<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-04-30 · 英文 · 2 个 skill · MIT</sub>

- **[xiaohongshu-images-skill](https://github.com/iamzifei/xiaohongshu-images-skill)** · ★ 7<br>把 Markdown、HTML 或文字排成 3:4 的小红书图片，配 AI 生成的封面<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-12 · 英文</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# guizang-social-card-skill
npx skills add op7418/guizang-social-card-skill
# gzh-design-skill
npx skills add isjiamu/gzh-design-skill
# md2wechat-skill
npx skills add geekjourneyx/md2wechat-skill
# youtube-shorts-pipeline
npx skills add rushindrasinha/youtube-shorts-pipeline
# herk-edit-kit
npx skills add nateherkai/herk-edit-kit
# Youtube-clipper-skill
npx skills add op7418/Youtube-clipper-skill
# video-podcast-maker
npx skills add Agents365-ai/video-podcast-maker
# rnskill
npx skills add Pluviobyte/rnskill
# xhs-visual-director-skill
npx skills add ziguishian/xhs-visual-director-skill
# Punk-Skill
npx skills add adrianpunk/Punk-Skill
# qiaomu-mondo-poster-design
npx skills add joeseesun/qiaomu-mondo-poster-design
# clipforge
npx skills add xixihhhh/clipforge
# video-spec-builder
npx skills add feicaiclub/video-spec-builder
# digital-human-koubo
npx skills add andyhuo520/digital-human-koubo
# gbro-cover-design
npx skills add pyang5166/gbro-cover-design
# vibe-knowledge-film
npx skills add HeyChengC/vibe-knowledge-film
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
# smart-illustrator
npx skills add axtonliu/smart-illustrator
# DaVinci-AutoEdit-Agent
npx skills add liuluhaixiu/DaVinci-AutoEdit-Agent
# claude-design-card
npx skills add geekjourneyx/claude-design-card
# motion-graphics-skills
npx skills add charlie947/motion-graphics-skills
# atutun-xhs-cover
npx skills add panggungunvibe/atutun-xhs-cover
# cy-carousel-skill
npx skills add chengyi-ai/cy-carousel-skill
# hotclip
npx skills add xixihhhh/hotclip
# clipcat-skill
npx skills add Clipcat-ai/clipcat-skill
# xiaohu-ip-studio
npx skills add xiaohuailabs/xiaohu-ip-studio
# panda-video-generator
npx skills add szhshp/panda-video-generator
# oil-cover
npx skills add oil-oil/oil-cover
# ian-xhs-carousel
npx skills add helloianneo/ian-xhs-carousel
# oh-my-cover-design
npx skills add hongfamonvAI/oh-my-cover-design
# douyin-live-recorder
npx skills add WeiZhuochun/douyin-live-recorder
# blcaptain-lingjian-video
npx skills add dososo/blcaptain-lingjian-video
# xhs-cover-skill
npx skills add Vivixiao980/xhs-cover-skill
# blcaptain-style-skill
npx skills add dososo/blcaptain-style-skill
# ai-video-editing-skill
npx skills add znyupup/ai-video-editing-skill
# xhs-writer-skill
npx skills add JuneYaooo/xhs-writer-skill
# reelclaw
npx skills add dansugc/reelclaw
# jianshuo/claude-skills
npx skills add jianshuo/claude-skills
# threads-carousel-claude-skill
npx skills add itchernetski/threads-carousel-claude-skill
# freestylefly/xiaohongshu-skills
npx skills add freestylefly/xiaohongshu-skills
# wechat-article-formatter-skill
npx skills add iamzifei/wechat-article-formatter-skill
# wechat-typesetting-cy
npx skills add CY-CHENYUE/wechat-typesetting-cy
# claude-reel-editor
npx skills add nicolapocock/claude-reel-editor
# tiktok-video-skills
npx skills add iart-ai/tiktok-video-skills
# social-media-image-sizes
npx skills add Branding5/social-media-image-sizes
# xiaohongshu-images-skill
npx skills add iamzifei/xiaohongshu-images-skill
```

</details>

<a id="group-publish"></a>
### 发布和自动化

把内容发到平台上：定时发布、一稿多发、浏览器自动化。多数要登录你的账号，装之前先看它怎么保存登录态。

- 🌟 **[social-auto-upload](https://github.com/dreammis/social-auto-upload)** · ★ 15.9k<br>一键上传视频到抖音、小红书、视频号、B站、快手、微博、TikTok、YouTube 等，支持定时发布，带 sau 命令和 4 个 skill<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 微博 · 快手 · YouTube · TikTok</sub><br><sub>更新于 2026-10-22 · 中文 · 18 个 skill · MIT</sub>

- **[Wechatsync](https://github.com/wechatsync/Wechatsync)** · ★ 6.5k<br>文章同步助手：公众号文章一键同步到知乎、头条、小红书、掘金、CSDN 等 29+ 平台，Chrome 扩展用你自己的登录态，带 MCP<br><sub>平台：小红书 · 公众号 · 知乎 · 头条</sub><br><sub>更新于 2026-10-23 · 中文 · GPL-3.0</sub>

- **[XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills)** · ★ 3.5k<br>小红书自动发布、评论和检索：通过 Chrome 开发者协议发图文和视频，支持多账号和无头模式<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-27 · 中文 · MIT</sub>

- **[autoclaw-cc/xiaohongshu-skills](https://github.com/autoclaw-cc/xiaohongshu-skills)** · ★ 2k<br>小红书自动化：用你已登录的浏览器和真实账号登录、发图文和视频、搜索、评论点赞，开箱即用<br><sub>平台：小红书</sub><br><sub>更新于 2026-05-23 · 中文 · 6 个 skill · MIT</sub>

- **[MatrixMedia](https://github.com/hanliang97/MatrixMedia)** · ★ 1.1k<br>矩媒：视频矩阵批量发布到抖音、快手、视频号、小红书、B站、百家号、头条、番茄视频，查登录状态和发布记录<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手 · 头条</sub><br><sub>更新于 2026-10-24 · 中文 · 4 个 skill · GPL-2.0</sub><br><sub>💡 skill 驱动矩媒桌面端，要先装应用</sub>

- **[x-article-publisher-skill](https://github.com/wshuyi/x-article-publisher-skill)** · ★ 872<br>Markdown 长文一条命令发到 X Articles（推特长文），支持分割线、表格转图片和 Mermaid<br><sub>平台：X</sub><br><sub>更新于 2026-01-25 💤 · 中文 · MIT</sub>

- **[social-push](https://github.com/jihe520/social-push)** · ★ 541<br>用 agent-browser 把内容发到小红书、微博、知乎、公众号、X 等平台，流程能自我改进<br><sub>平台：小红书 · 公众号 · 微博 · 知乎 · X</sub><br><sub>更新于 2026-06-28 · 中文 · 2 个 skill</sub>

- **[SyncCaster](https://github.com/RyanYipeng/SyncCaster)** · ★ 512<br>多平台文章同步 Chrome 扩展：Markdown 编辑，一键发到掘金、CSDN、知乎、公众号等 17+ 平台，带 MCP 桥给 agent 用<br><sub>平台：公众号 · 知乎</sub><br><sub>更新于 2026-08-25 · 中文 · MIT</sub>

- **[xiaohongshu-mcp-skills](https://github.com/autoclaw-cc/xiaohongshu-mcp-skills)** · ★ 275<br>配合 xiaohongshu-mcp 用的 skill：部署服务、扫码登录、发笔记、搜索、内容规划<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-05 💤 · 中文 · 9 个 skill · MIT</sub>

- **[video-publisher-skill](https://github.com/oil-oil/video-publisher-skill)** · ★ 263<br>把视频、标题、封面准备成小红书、抖音、B站、视频号、YouTube 的已核验草稿，可续传，默认停在最终发布前<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · YouTube</sub><br><sub>更新于 2026-10-18 · 中文 · MIT</sub>

- **[Taisly Agent Kit](https://github.com/taisly/agent)** · ★ 221<br>Taisly 短视频发布套件：skill、MCP、CLI 和 SDK，从 agent 发视频到 TikTok、Reels、Shorts、X 和 Facebook<br><sub>平台：X · YouTube · TikTok · Instagram · Facebook</sub><br><sub>更新于 2026-10-22 · 英文 · MIT</sub><br><sub>💡 要 Taisly 账号，可以免费开始</sub>

- **[wechat-article-publisher-skill](https://github.com/iamzifei/wechat-article-publisher-skill)** · ★ 157<br>通过 API 把 Markdown 或 HTML 文章推送到公众号草稿箱<br><sub>平台：公众号</sub><br><sub>更新于 2026-08-12 · 多语言 · MIT</sub>

- **[Spreado](https://github.com/BadKid90s/Spreado)** · ★ 144<br>开源视频发布工具：一键同步到抖音、小红书、快手、视频号，扫码登录、管理 Cookie，带 skill<br><sub>平台：小红书 · 抖音 · 视频号 · 快手</sub><br><sub>更新于 2026-10-27 · 中文 · 2 个 skill · Apache-2.0</sub>

- **[douyin-image-post-scheduler](https://github.com/chengyi-ai/douyin-image-post-scheduler)** · ★ 107<br>抖音图文批量定时发布：从本地素材文件夹排队，在已登录的 Chrome 里上传、选话题和音乐、定时并回后台核验<br><sub>平台：抖音</sub><br><sub>更新于 2026-10-14 · 中文 · MIT</sub>

- **[Linked-API/linkedin-skills](https://github.com/Linked-API/linkedin-skills)** · ★ 107<br>LinkedIn 自动化：查人和公司、发私信、加好友、发帖，另有按目标客户筛选并跟进的获客流程<br><sub>平台：LinkedIn</sub><br><sub>更新于 2026-10-16 · 英文 · 2 个 skill · MIT</sub><br><sub>💡 通过 Linked API 云服务操作你的账号，要先注册</sub>

- **[socialclaw](https://github.com/ndesv21/socialclaw)** · ★ 102<br>社媒排期 CLI 和 OpenClaw skill：发到 X、LinkedIn、Instagram、Facebook 主页、TikTok、YouTube 等<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-10-12 · 英文 · 3 个 skill · MIT</sub><br><sub>💡 要 SocialClaw 账号，CLI 和 API 要试用或付费方案</sub>

- **[douyin-upload-mcp-skill](https://github.com/WJZ-P/douyin-upload-mcp-skill)** · ★ 87<br>抖音视频和图文全自动发布：通过 CDP 操作创作者平台，MCP 优先、脚本兜底，适合 OpenClaw<br><sub>平台：抖音</sub><br><sub>更新于 2026-04-01 💤 · 中文 · AGPL-3.0</sub>

- **[publora/skills](https://github.com/publora/skills)** · ★ 60<br>Publora 官方 skill：从 agent 发帖或排期到 LinkedIn、X、Instagram、Threads、TikTok 等 10 个平台<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook</sub><br><sub>更新于 2026-10-27 · 英文 · 9 个 skill · MIT</sub><br><sub>💡 要 Publora 账号，免费档覆盖除 X 以外的平台</sub>

- **[0731coderlee-sudo/wechat-publisher](https://github.com/0731coderlee-sudo/wechat-publisher)** · ★ 46<br>一键把 Markdown 发到公众号草稿箱：基于 wenyan-cli，多主题、代码高亮、图片自动上传<br><sub>平台：公众号</sub><br><sub>更新于 2026-02-05 💤 · 中文 · MIT</sub>

- **[upload-post-skill](https://github.com/Upload-Post/upload-post-skill)** · ★ 38<br>通过 Upload-Post API 把视频、图片、文字和文档发到 TikTok、Instagram、YouTube、LinkedIn、X 等平台<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-07-20 · 英文</sub><br><sub>💡 要 Upload-Post 账号和 API Key</sub>

- **[douyin-mcp-server](https://github.com/lancelin111/douyin-mcp-server)** · ★ 35<br>抖音视频上传 skill 和 MCP：管理登录、上传视频、自动发到创作者平台，支持 OpenClaw、Claude Code<br><sub>平台：抖音</sub><br><sub>更新于 2026-06-12 · 中文 · MIT</sub>

- **[red-publisher-skill](https://github.com/iamzifei/red-publisher-skill)** · ★ 11<br>一条命令把图片和笔记发到小红书：通过 CDP 连浏览器，始终存为草稿<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-12 · 多语言 · MIT</sub>


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
# xiaohongshu-mcp-skills
npx skills add autoclaw-cc/xiaohongshu-mcp-skills
# video-publisher-skill
npx skills add oil-oil/video-publisher-skill
# Taisly Agent Kit
npx skills add taisly/agent
# wechat-article-publisher-skill
npx skills add iamzifei/wechat-article-publisher-skill
# Spreado
npx skills add BadKid90s/Spreado
# douyin-image-post-scheduler
npx skills add chengyi-ai/douyin-image-post-scheduler
# Linked-API/linkedin-skills
npx skills add Linked-API/linkedin-skills
# socialclaw
npx skills add ndesv21/socialclaw
# douyin-upload-mcp-skill
npx skills add WJZ-P/douyin-upload-mcp-skill
# publora/skills
npx skills add publora/skills
# 0731coderlee-sudo/wechat-publisher
npx skills add 0731coderlee-sudo/wechat-publisher
# upload-post-skill
npx skills add Upload-Post/upload-post-skill
# douyin-mcp-server
npx skills add lancelin111/douyin-mcp-server
# red-publisher-skill
npx skills add iamzifei/red-publisher-skill
```

</details>

<a id="group-research"></a>
### 选题、热点和数据分析

追热点、拆爆款、看竞品和评论，读账号数据。

- 🌟 **[last30days-skill](https://github.com/mvanhorn/last30days-skill)** · ★ 65.7k<br>查任意话题最近 30 天大家在说什么：Reddit、X、YouTube、TikTok、HN、Polymarket 等按点赞和真金白银排序，写成有出处的摘要<br><sub>平台：X · YouTube · TikTok · Reddit</sub><br><sub>更新于 2026-10-27 · 多语言 · MIT</sub>

- **[wechatDownload](https://github.com/qiye45/wechatDownload)** · ★ 9.9k<br>公众号文章批量下载：历史文章、评论、合集，存成 html/md/pdf/docx/csv，保存图片视频音频，支持 MCP 和 Skill 调用<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-07 · 中文</sub><br><sub>💡 skill 调用作者的桌面软件</sub>

- **[follow-builders](https://github.com/zarazhangrui/follow-builders)** · ★ 7k<br>AI 圈一线建设者摘要：追踪 X 上的研究员、创始人和 YouTube 播客，按天或周推送整理好的要点<br><sub>平台：X · YouTube</sub><br><sub>更新于 2026-10-27 · 英文</sub>

- **[social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills)** · ★ 4.9k<br>社媒调研：找超常爆款、挖评论、拆竞品、看广告库和趋势，覆盖 TikTok、Instagram、YouTube、Reddit、X、LinkedIn<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Reddit</sub><br><sub>更新于 2026-08-26 · 英文 · 13 个 skill · MIT</sub><br><sub>💡 数据来自 ScrapeCreators，要它的 API Key（付费）</sub>

- **[claude-real-video](https://github.com/HUANGCHIHHUNGLeo/claude-real-video)** · ★ 2.3k<br>让 AI 看视频：从链接或本地文件抽场景关键帧并去重、配时间戳字幕，用来总结和拆解对标视频，本地运行<br><sub>平台：YouTube</sub><br><sub>更新于 2026-10-23 · 英文 · 3 个 skill · MIT</sub>

- **[last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn)** · ★ 2k<br>中文版近 30 天研究：微博、小红书、B站、知乎、抖音、公众号、百度、头条 8 个平台并行检索，按互动和时效排序，结论都有出处<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · 微博 · 知乎 · 头条</sub><br><sub>更新于 2026-10-27 · 中文 · 2 个 skill</sub>

- **[chubbyskills](https://github.com/chubbyguan/chubbyskills)** · ★ 1.3k<br>把抖音、B站、小红书、公众号、X、播客内容存进个人知识库：图文存图、视频转文字稿、订阅和每日简报，附知识库 MCP<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · X</sub><br><sub>更新于 2026-10-14 · 中文 · 14 个 skill · MIT</sub>

- **[x-research-skill](https://github.com/rohunvora/x-research-skill)** · ★ 1.2k<br>X 调研：搜索按互动排序、跟帖、监控账号，输出带出处的简报<br><sub>平台：X</sub><br><sub>更新于 2026-02-19 💤 · 英文</sub><br><sub>💡 要自己的 X API 凭证（按量付费）</sub>

- **[ZeroPointRepo/youtube-skills](https://github.com/ZeroPointRepo/youtube-skills)** · ★ 1.1k<br>YouTube 字幕、搜索视频、浏览频道和播放列表，走 TranscriptAPI<br><sub>平台：YouTube</sub><br><sub>更新于 2026-10-20 · 英文 · 12 个 skill · MIT</sub><br><sub>💡 要 TranscriptAPI 的 API Key</sub>

- **[wechat-article-to-markdown](https://github.com/jackwener/wechat-article-to-markdown)** · ★ 1.1k<br>公众号文章抓取转 Markdown：防检测抓取，提取标题、作者、时间，图片存本地<br><sub>平台：公众号</sub><br><sub>更新于 2026-03-22 💤 · 多语言</sub>

- **[x-tweet-fetcher](https://github.com/ythx-101/x-tweet-fetcher)** · ★ 994<br>不登录、不用 API Key 抓 X 推文、回复、时间线、列表和长文，三种后端自动切换<br><sub>平台：X</sub><br><sub>更新于 2026-10-14 · 英文 · MIT</sub>

- **[autocli-skill](https://github.com/nashsu/autocli-skill)** · ★ 927<br>让 agent 用 autocli 读 55+ 个网站：B站、知乎、X、YouTube、微博、Reddit、小红书等，复用你 Chrome 的登录态<br><sub>平台：小红书 · B 站 · 微博 · 知乎 · X · YouTube · Reddit</sub><br><sub>更新于 2026-04-20 💤 · 多语言</sub>

- **[union-search-skill](https://github.com/runningZ1/union-search-skill)** · ★ 763<br>统一搜索：一条命令搜小红书、抖音、B站、YouTube、X、公众号、Reddit 等 20+ 平台，输出统一格式<br><sub>平台：小红书 · 抖音 · 公众号 · B 站 · 微博 · 知乎 · 头条 · X · YouTube · Reddit</sub><br><sub>更新于 2026-10-26 · 中文 · MIT</sub>

- **[blogger-distiller](https://github.com/otter1101/blogger-distiller)** · ★ 745<br>博主蒸馏器：输入博主账号，从真实笔记里蒸馏 TA 的爆款打法和认知，装进你的 AI 当内容教练<br><sub>平台：小红书 · 抖音</sub><br><sub>更新于 2026-09-23 · 中文 · MIT</sub>

- **[NewsCrawler](https://github.com/NanmiCoder/NewsCrawler)** · ★ 636<br>新闻和内容提取 skill：给一条链接拿到正文、图片和元数据，支持公众号、头条、X、网易、腾讯新闻等 12 个平台<br><sub>平台：公众号 · 头条 · X</sub><br><sub>更新于 2026-08-08 · 中文 · GPL-3.0</sub>

- **[feedgrab](https://github.com/iBigQiang/feedgrab)** · ★ 619<br>18+ 平台内容抓取：输入链接或关键词批量抓 X、小红书、公众号、YouTube、B站等，输出带元数据的 Obsidian Markdown<br><sub>平台：小红书 · 公众号 · B 站 · X · YouTube</sub><br><sub>更新于 2026-10-24 · 中文 · 5 个 skill · MIT</sub>

- **[redfox-community](https://github.com/redfox-data/redfox-community)** · ★ 450<br>红狐数据的 132 个 skill：多平台主页视频提取、B站评论分析、AI 信息日报、选题、文案和数据复盘<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · B 站 · 快手 · 头条 · X · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-10-27 · 中文 · 134 个 skill</sub>

- **[xhs-claude-skills](https://github.com/chenxiachan/xhs-claude-skills)** · ★ 427<br>小红书转 Obsidian：提取帖子文字、图片 OCR、视频字幕或转录，批量入库后做总结对比，也能做封面<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-14 · 中文 · 4 个 skill · MIT</sub>

- **[twitterapi-io](https://github.com/kaitoInfra/twitterapi-io)** · ★ 336<br>twitterapi.io 官方 skill：查推文、主页、粉丝、高级搜索、趋势，也能发帖等操作<br><sub>平台：X</sub><br><sub>更新于 2026-10-14 · 英文 · 2 个 skill · MIT</sub><br><sub>💡 twitterapi.io 按量付费</sub>

- **[ai-influence-digest](https://github.com/koffuxu/ai-influence-digest)** · ★ 320<br>AI 影响力周报：用浏览器扫 65+ 个 AI 建设者过去 7 天的推文，筛出创作者能立刻用的工具和方法，导出海报<br><sub>平台：X</sub><br><sub>更新于 2026-04-18 💤 · 中文 · MIT</sub>

- **[social-account-doctor](https://github.com/JuneYaooo/social-account-doctor)** · ★ 319<br>自媒体账号体检和爆款拆解：扫同赛道找对标、拆爆款为什么爆、诊断没人看的原因，顺手出仿写初稿，支持带货模式<br><sub>平台：小红书 · 抖音 · 视频号 · B 站 · 快手</sub><br><sub>更新于 2026-09-19 · 中文 · MIT</sub>

- **[lingzao-skill](https://github.com/atian-create/lingzao-skill)** · ★ 303<br>灵造：小红书为主的公开内容研究，账号诊断、找对标、拆爆款、标题封面优化、仿写模板，也覆盖抖音和公众号<br><sub>平台：小红书 · 抖音 · 公众号</sub><br><sub>更新于 2026-07-02 · 中文 · 12 个 skill · MIT-0</sub>

- **[head-of-content](https://github.com/bradautomates/head-of-content)** · ★ 285<br>内容调研同事：在 X、Instagram、YouTube、TikTok 上找表现好的内容，拆共性，做内容计划<br><sub>平台：X · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-01-23 💤 · 英文 · 6 个 skill · MIT</sub><br><sub>💡 抓数据用 Apify，按用量付费</sub>

- **[bigpeng-hot-gzh](https://github.com/BigPengSays/bigpeng-hot-gzh)** · ★ 275<br>公众号选题和标题：从约 100 篇 AI 爆款文章拆出 7 种标题公式和 8 个选题模板，只做选题和标题<br><sub>平台：公众号</sub><br><sub>更新于 2026-08-19 · 中文 · MIT</sub>

- **[social-media-data-tools](https://github.com/jinchenma94/social-media-data-tools)** · ★ 252<br>抖音博主和视频导出：标题、文案、完整逐字稿和互动数据，可写入飞书多维表格；要在豆包里运行<br><sub>平台：抖音</sub><br><sub>更新于 2026-08-27 · 中文</sub>

- **[ah-douyin-clean-downloader](https://github.com/ahang008/ah-douyin-clean-downloader)** · ★ 251<br>抖音原视频下载和逐字稿：归档博主公开作品和指标，可按点赞批量改写口播稿，只用于自有或已授权内容<br><sub>平台：抖音</sub><br><sub>更新于 2026-10-03 · 中文</sub>

- **[video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill)** · ★ 236<br>短视频转字幕加 AI 总结：抖音、小红书、B 站、YouTube 链接或本地音视频，faster-whisper 本地转写<br><sub>平台：小红书 · 抖音 · B 站 · YouTube</sub><br><sub>更新于 2026-07-19 · 中文 · MIT</sub><br><sub>💡 抖音、小红书、B 站要配视频解析接口：作者推荐的 top9.cc（新用户有免费额度）或 TikHub</sub>

- **[x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper)** · ★ 220<br>Xquik 的 X 数据：搜索、主页、粉丝、回复、时间线、媒体下载，带远程 MCP<br><sub>平台：X</sub><br><sub>更新于 2026-10-26 · 英文 · 3 个 skill · MIT</sub><br><sub>💡 Xquik 是付费服务</sub>

- **[jev-social](https://github.com/socai-io/jev-social)** · ★ 187<br>社媒调研 agent：在你已登录的 Chrome 里搜 Instagram、TikTok、LinkedIn 的帖子、主页和评论，出带出处的报告，只读不发<br><sub>平台：TikTok · Instagram · LinkedIn</sub><br><sub>更新于 2026-10-12 · 英文 · MIT</sub><br><sub>💡 要装 socai CLI；默认模型走 OpenRouter，要它的 API Key</sub>

- **[wechat-article-extractor-skill](https://github.com/freestylefly/wechat-article-extractor-skill)** · ★ 140<br>从公众号文章链接提取标题、作者、正文、封面和公众号信息，支持图文、视频、图片集、语音和转载<br><sub>平台：公众号</sub><br><sub>更新于 2026-02-19 💤 · 中文</sub>

- **[tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill)** · ★ 130<br>TikHub API 助手：帮 agent 查找和调用抖音、TikTok、小红书、Instagram、YouTube、X、Reddit 等平台的数据接口<br><sub>平台：小红书 · 抖音 · X · YouTube · TikTok · Instagram · Reddit</sub><br><sub>更新于 2026-07-08 · 中文</sub><br><sub>💡 TikHub 是付费数据接口</sub>

- **[openclaw-xhs](https://github.com/zhjiang22/openclaw-xhs)** · ★ 125<br>让 OpenClaw 读懂你的小红书：MCP 搜索浏览评论、热点报告、把收藏导出成个人记忆库<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-08 💤 · 中文</sub>

- **[hook-lab](https://github.com/hongfamonvAI/hook-lab)** · ★ 102<br>拆解 TikTok、Reels、Shorts 爆款：数据面板、钩子和脚本结构、为什么能火，给出改编到小红书和视频号的方向<br><sub>平台：小红书 · 视频号 · YouTube · TikTok · Instagram</sub><br><sub>更新于 2026-06-11 · 中文 · MIT</sub>

- **[wechat-search-weread](https://github.com/KANIKIG/wechat-search-weread)** · ★ 83<br>搜公众号文章：通过微信读书搜一搜拿最新文章的标题、公众号、时间、简介和直链，不抓正文<br><sub>平台：公众号</sub><br><sub>更新于 2026-06-09 · 中文</sub><br><sub>💡 要登录微信读书</sub>

- **[youtube-scout](https://github.com/AgriciDaniel/youtube-scout)** · ★ 66<br>YouTube 选题调研：输入一个话题，按播放、互动或爆发度排出视频和频道，导出含评论、字幕和钩子的 Excel 表<br><sub>平台：YouTube</sub><br><sub>更新于 2026-09-11 · 英文 · MIT</sub><br><sub>💡 要 YouTube Data API Key</sub>

- **[x-ai-topic-selector](https://github.com/vigorX777/x-ai-topic-selector)** · ★ 57<br>从 X 列表、首页或书签抓推文，按互动数据和 AI 多维打分，出选题推荐报告<br><sub>平台：X</sub><br><sub>更新于 2026-02-20 💤 · 中文</sub><br><sub>💡 AI 评分和书签模式要 Gemini API Key</sub>

- **[xiaohongshu-summarizer-skill](https://github.com/piekill/xiaohongshu-summarizer-skill)** · ★ 40<br>小红书搜索和总结：按关键词抓前 N 篇笔记的文字、图片和评论，合成一份调研报告<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-10 💤 · 中文</sub>

- **[openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news)** · ★ 13<br>每日热榜：查微博、知乎、B 站、抖音等 54 个平台的热榜，跨平台聚合，支持定时推送<br><sub>平台：抖音 · B 站 · 微博 · 知乎 · 快手 · 头条</sub><br><sub>更新于 2026-02-06 💤 · 中文 · MIT</sub>

- **[apidojo-io/social-media-skills](https://github.com/apidojo-io/social-media-skills)** · ★ 2<br>批量抓 X、TikTok、Instagram 公开数据：推文、主页、话题、评论，不用登录<br><sub>平台：X · TikTok · Instagram</sub><br><sub>更新于 2026-09-02 · 英文 · 3 个 skill</sub><br><sub>💡 跑在 Apify 上，按用量付费</sub>

- **[douyin-video-summary](https://github.com/liu-wei-ai/douyin-video-summary)** · ★ 2<br>OpenClaw 抖音视频总结：提取音频、whisper.cpp 转写、生成结构化摘要，可同步到飞书文档<br><sub>平台：抖音</sub><br><sub>更新于 2026-02-10 💤 · 英文</sub>

- **[skillify-sh/skills](https://github.com/skillify-sh/skills)** · ★ 0<br>抓 Instagram 公开数据，不要登录，花钱前先告诉你费用<br><sub>平台：Instagram</sub><br><sub>更新于 2026-08-23 · 英文 · MIT</sub><br><sub>💡 按次付费的数据服务</sub>


<details><summary>安装命令</summary>

```bash
# 默认命令基于 skills CLI，未逐个验证，以各仓库 README 为准
# last30days-skill
npx skills add mvanhorn/last30days-skill
# wechatDownload
npx skills add qiye45/wechatDownload
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
# union-search-skill
npx skills add runningZ1/union-search-skill
# blogger-distiller
npx skills add otter1101/blogger-distiller
# NewsCrawler
npx skills add NanmiCoder/NewsCrawler
# feedgrab
npx skills add iBigQiang/feedgrab
# redfox-community
npx skills add redfox-data/redfox-community
# xhs-claude-skills
npx skills add chenxiachan/xhs-claude-skills
# twitterapi-io
npx skills add kaitoInfra/twitterapi-io
# ai-influence-digest
npx skills add koffuxu/ai-influence-digest
# social-account-doctor
npx skills add JuneYaooo/social-account-doctor
# lingzao-skill
npx skills add atian-create/lingzao-skill
# head-of-content
npx skills add bradautomates/head-of-content
# bigpeng-hot-gzh
npx skills add BigPengSays/bigpeng-hot-gzh
# social-media-data-tools
npx skills add jinchenma94/social-media-data-tools
# ah-douyin-clean-downloader
npx skills add ahang008/ah-douyin-clean-downloader
# video-to-subtitle-summary-skill
npx skills add imlewc/video-to-subtitle-summary-skill
# x-twitter-scraper
npx skills add Xquik-dev/x-twitter-scraper
# jev-social
npx skills add socai-io/jev-social
# wechat-article-extractor-skill
npx skills add freestylefly/wechat-article-extractor-skill
# tikhub_api_skill
npx skills add liangdabiao/tikhub_api_skill
# openclaw-xhs
npx skills add zhjiang22/openclaw-xhs
# hook-lab
npx skills add hongfamonvAI/hook-lab
# wechat-search-weread
npx skills add KANIKIG/wechat-search-weread
# youtube-scout
npx skills add AgriciDaniel/youtube-scout
# x-ai-topic-selector
npx skills add vigorX777/x-ai-topic-selector
# xiaohongshu-summarizer-skill
npx skills add piekill/xiaohongshu-summarizer-skill
# openclaw-daily-hot-news
npx skills add one-box-u/openclaw-daily-hot-news
# apidojo-io/social-media-skills
npx skills add apidojo-io/social-media-skills
# douyin-video-summary
npx skills add liu-wei-ai/douyin-video-summary
# skillify-sh/skills
npx skills add skillify-sh/skills
```

</details>

<a id="group-strategy"></a>
### 账号定位和增长

定人设和赛道、做内容规划、涨粉和变现的方法。

- 🌟 **[dbskill](https://github.com/dontbesilent2025/dbskill)** · ★ 10.9k<br>dontbesilent 的 34 个商业诊断 skill：找生意问题、选对标、把选题做成内容方案、写标题封面和开头、发布前查违规<br><sub>平台：通用</sub><br><sub>更新于 2026-10-26 · 中文 · 35 个 skill</sub>

- **[x-mentor-skill](https://github.com/alchaincyf/x-mentor-skill)** · ★ 1.3k<br>X 运营导师：蒸馏 Dan Koe、Justin Welsh 等 6 位创作者的方法和开源算法资料，管选题、写推文和长文、账号诊断和增长<br><sub>平台：X</sub><br><sub>更新于 2026-10-13 · 中文 · MIT</sub>

- **[xhs-virtual-product](https://github.com/chenjin-cmd/xhs-virtual-product)** · ★ 740<br>小红书虚拟资料生意：选品、对标、制作、上架、发内容、复盘 7 步，附模板和版权合规红线<br><sub>平台：小红书</sub><br><sub>更新于 2026-09-30 · 中文 · MIT</sub>

- **[xiaohongshu-ai-workbench](https://github.com/mengke-wang/xiaohongshu-ai-workbench)** · ★ 599<br>《小红书运营手册》配套的 Codex skill：标题、主页、选题、评论区回复和成交路径，作者是《爆款》作者王梦珂<br><sub>平台：小红书</sub><br><sub>更新于 2026-08-07 · 中文 · 7 个 skill · MIT</sub>

- **[agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_)** · ★ 591<br>起号专家：视频号、抖音、公众号、小红书和中文 X 账号从 0 到 1，定位、选题、脚本、小样本实验、复盘和 30 天计划<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号 · X</sub><br><sub>更新于 2026-07-08 · 中文 · 5 个 skill · MIT</sub>

- **[vivy-yi/xiaohongshu-skills](https://github.com/vivy-yi/xiaohongshu-skills)** · ★ 506<br>小红书运营知识库 139 个 skill：内容创作、账号运营、互动、数据分析、电商转化、平台规则和增长策略<br><sub>平台：小红书</sub><br><sub>更新于 2026-01-23 💤 · 中文 · 9 个 skill</sub>

- **[nova-youtube-agent](https://github.com/sharbelxyz/nova-youtube-agent)** · ★ 391<br>YouTube 增长 agent：扫竞品、分析频道、想选题、写脚本、追踪表现并按反馈改进，给 Hermes 和 OpenClaw 用<br><sub>平台：YouTube</sub><br><sub>更新于 2026-07-06 · 英文</sub>

- **[Eva-skill](https://github.com/Lulu-Eva/Eva-skill)** · ★ 62<br>创作者思考陪练：把模糊想法理成有依据的判断，做账号阶段定位、挑题，再写成短视频或非虚构文章，带新手教程和稿件批改<br><sub>平台：小红书 · 抖音 · 公众号 · 视频号</sub><br><sub>更新于 2026-09-19 · 中文 · 13 个 skill</sub><br><sub>💡 个人非商业使用免费；用于获客或商业推广可能要授权</sub>


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
# Eva-skill
npx skills add Lulu-Eva/Eva-skill
```

</details>

<a id="group-mcp"></a>
### MCP 和命令行工具（不是 skill）

让 agent 能读写平台的工具，常和上面的 skill 搭配用。不计入 skill 数。

- 🌟 **[xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp)** · ★ 16.6k<br>小红书 MCP：登录、发图文和视频、搜索、看笔记和评论、点赞收藏，Docker 或本地运行<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-26 · 🔌 MCP · 中文 · Apache-2.0</sub>

- **[bb-browser](https://github.com/epiral/bb-browser)** · ★ 6.3k<br>你的浏览器就是 API：CLI + MCP 让 agent 用你的登录态操作 Chrome，36 个平台 103 条现成命令<br><sub>平台：小红书 · B 站 · 微博 · 知乎 · X · YouTube · LinkedIn · Reddit</sub><br><sub>更新于 2026-05-29 · 🔌 MCP · 多语言 · 2 个 skill · MIT</sub>

- **[xiaohongshu-cli](https://github.com/jackwener/xiaohongshu-cli)** · ★ 2.7k<br>小红书命令行：搜索、阅读、点赞、收藏、评论、发布，走逆向接口，附 skill<br><sub>平台：小红书</sub><br><sub>更新于 2026-03-21 💤 · 🔌 MCP · 多语言</sub>

- **[wechat-download-api](https://github.com/tmwgsicp/wechat-download-api)** · ★ 1.2k<br>公众号文章获取和 RSS API：整号导出 7 种格式、定时订阅，内置 MCP，可自己部署<br><sub>平台：公众号</sub><br><sub>更新于 2026-07-27 · 🔌 MCP · 中文 · AGPL-3.0</sub>

- **[trypost](https://github.com/trypostit/trypost)** · ★ 758<br>开源社媒排程工具，给 agent 提供 MCP 和 REST API 来写、排期、发布各平台帖子，可自己部署<br><sub>平台：YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Pinterest</sub><br><sub>更新于 2026-10-27 · 🔌 MCP · 英文 · 18 个 skill · AGPL-3.0</sub>

- **[xhs-cli](https://github.com/jackwener/xhs-cli)** · ★ 673<br>小红书命令行的无头浏览器版：搜索、看主页、点赞、收藏、评论，比逆向接口版更像真人操作<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-09 · 🔌 MCP · 多语言 · Apache-2.0</sub>

- **[postiz-agent](https://github.com/gitroomhq/postiz-agent)** · ★ 555<br>Postiz 的 agent CLI：让 Claude、OpenClaw 等 agent 把帖子排进 X、LinkedIn、Instagram 等 28+ 渠道<br><sub>平台：X · YouTube · Instagram · LinkedIn</sub><br><sub>更新于 2026-10-22 · 🔌 MCP · 英文 · 2 个 skill</sub><br><sub>💡 要 Postiz 云服务或自己部署的 Postiz</sub>

- **[rdt-cli](https://github.com/public-clis/rdt-cli)** · ★ 546<br>Reddit 命令行：浏览、读帖、搜索、点赞、收藏、订阅，附 skill<br><sub>平台：Reddit</sub><br><sub>更新于 2026-03-21 💤 · 🔌 MCP · 英文</sub>

- **[redbook](https://github.com/lucasygu/redbook)** · ★ 531<br>小红书 CLI：搜笔记、读内容、分析博主、发图文，用浏览器 Cookie 认证，不要 API Key<br><sub>平台：小红书</sub><br><sub>更新于 2026-09-12 · 🔌 MCP · 多语言 · MIT</sub>

- **[catbus](https://github.com/cv-cat/catbus)** · ★ 521<br>一个命令操作小红书、抖音、TikTok、B站、快手、微博、X 等：搜索、评论、下载、发布、私信、直播弹幕，统一 JSON 输出<br><sub>平台：小红书 · 抖音 · B 站 · 微博 · 快手 · X · TikTok</sub><br><sub>更新于 2026-10-25 · 🔌 MCP · 中文 · MIT</sub>

- **[x-mcp](https://github.com/xpzouying/x-mcp)** · ★ 479<br>xiaohongshu-mcp 的浏览器插件版：装插件即用，不用部署 Docker 或 Python，在你常用的浏览器里发小红书<br><sub>平台：小红书</sub><br><sub>更新于 2026-09-10 · 🔌 MCP · 中文</sub>

- **[xint](https://github.com/0xNyk/xint)** · ★ 256<br>本地优先的 X 数据命令行：搜索、监控、分析、导出、OAuth 操作，用你的 X API<br><sub>平台：X</sub><br><sub>更新于 2026-10-27 · 🔌 MCP · 英文 · MIT</sub>

- **[zhihu-cli](https://github.com/BAIGUANGMEI/zhihu-cli)** · ★ 114<br>知乎命令行：搜索、热榜、看问题和回答、发想法、提问和文章，扫码或 Cookie 登录，附 skill<br><sub>平台：知乎</sub><br><sub>更新于 2026-05-04 · 🔌 MCP · 中文 · Apache-2.0</sub>

- **[weibo-cli](https://github.com/jackwener/weibo-cli)** · ★ 88<br>微博命令行：热搜、关键词搜索、时间线、评论转发、用户主页，附 skill<br><sub>平台：微博</sub><br><sub>更新于 2026-03-14 💤 · 🔌 MCP · 多语言</sub>

- **[dy-cli](https://github.com/Youhai020616/douyin)** · ★ 68<br>抖音命令行 dy-cli：搜索、下载、发布、互动、热榜、直播和数据分析，输出适合 agent 读<br><sub>平台：抖音</sub><br><sub>更新于 2026-09-12 · 🔌 MCP · 中文 · MIT</sub>


<a id="group-apps"></a>
### 相关开源平台（完整应用，不是 skill）

能自己部署的运营平台和桌面应用。不计入 skill 数。

- 🌟 **[postiz-app](https://github.com/gitroomhq/postiz-app)** · ★ 39.1k<br>开源社媒排程平台：排期、自动化和数据分析，可用云版或自己部署，支持 agent 接入<br><sub>平台：X · YouTube · TikTok · Instagram · LinkedIn · Threads · Facebook · Reddit · Pinterest</sub><br><sub>更新于 2026-10-24 · 🧩 应用 · 英文 · AGPL-3.0</sub>

- **[OpenCreator](https://github.com/krillinai/OpenCreator)** · ★ 14k<br>原 KrillinAI：创作者 AI 工作台，视频下载、翻译配音、做视频图片和语音、剪辑，内置 Codex agent<br><sub>平台：小红书 · 抖音 · B 站 · X · YouTube · TikTok · Instagram · Facebook</sub><br><sub>更新于 2026-10-26 · 🧩 应用 · 英文 · 9 个 skill · Apache-2.0</sub>

- **[xiaobei](https://github.com/TeamWiseFlow/xiaobei)** · ★ 8.6k<br>小贝：给小微企业的自媒体获客智能体（基于 OpenClaw），公众号写作推送、小红书图文、视频分发、评论区获客、数据复盘<br><sub>平台：小红书 · 公众号</sub><br><sub>更新于 2026-10-16 · 🧩 应用 · 中文 · 59 个 skill</sub>

- **[we-mp-rss](https://github.com/rachelos/we-mp-rss)** · ★ 5k<br>WeRSS：公众号订阅助手，定时抓新文章生成 RSS，转 Markdown/PDF，支持 Webhook 和 API 给 agent 用<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-20 · 🧩 应用 · 多语言</sub>

- **[Easel](https://github.com/ZJU-REAL/Easel)** · ★ 4.1k<br>Easel：ZJU-REAL 开源的社媒 agent，在小红书、抖音、知乎、B 站等平台找趋势、策划、创作、发布和复盘，记住你的账号画像<br><sub>平台：小红书 · 抖音 · B 站 · 知乎</sub><br><sub>更新于 2026-10-25 · 🧩 应用 · 多语言 · Apache-2.0</sub>

- **[social-media-agent](https://github.com/langchain-ai/social-media-agent)** · ★ 3k<br>LangChain 的社媒 agent：读一个链接生成 X 和 LinkedIn 帖子，人工确认后排期发布<br><sub>平台：X · LinkedIn</sub><br><sub>更新于 2026-10-26 · 🧩 应用 · 英文 · MIT</sub>

- **[Beav](https://github.com/Jamailar/Beav)** · ★ 2.2k<br>Beav（原 RedBox）：小红书 AI 运营工作台，采集笔记和评论、素材库、选题、写作和配图，本地桌面应用<br><sub>平台：小红书</sub><br><sub>更新于 2026-10-27 · 🧩 应用 · 中文 · 16 个 skill</sub>

- **[chatwiki](https://github.com/zhimaAi/chatwiki)** · ★ 2.1k<br>ChatWiki：公众号 AI 知识库和客服工作流平台，拖拽搭建自动回复等应用<br><sub>平台：公众号</sub><br><sub>更新于 2026-10-16 · 🧩 应用 · 多语言 · 2 个 skill</sub>

- **[locoagent](https://github.com/LocoreMind/locoagent)** · ★ 1.1k<br>用真实浏览器自动运营社媒的 agent：X、LinkedIn、Reddit 的浏览、互动和发帖<br><sub>平台：X · LinkedIn · Reddit</sub><br><sub>更新于 2026-06-27 · 🧩 应用 · 英文 · 2 个 skill · MIT</sub>


<a id="by-platforms"></a>
## 按平台查找

仓库说明里明确写了针对哪个平台（按星数排序）。「通用」是不挑平台的。

**小红书**（83）：[baoyu-skills](https://github.com/JimLiu/baoyu-skills) · [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [html-anything](https://github.com/nexu-io/html-anything) · [xiaobei](https://github.com/TeamWiseFlow/xiaobei) · [guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill) · [Wechatsync](https://github.com/wechatsync/Wechatsync) · [bb-browser](https://github.com/epiral/bb-browser) · [yichen-skills](https://github.com/mcncarl/yichen-skills) · [Easel](https://github.com/ZJU-REAL/Easel) · [wewrite](https://github.com/imraywang/wewrite) · [XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills) · [writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) · [xiaohongshu-cli](https://github.com/jackwener/xiaohongshu-cli) · [xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill) · [Beav](https://github.com/Jamailar/Beav) · [autoclaw-cc/xiaohongshu-skills](https://github.com/autoclaw-cc/xiaohongshu-skills) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [creator-buddy](https://github.com/SpaceZephyr/creator-buddy) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [rnskill](https://github.com/Pluviobyte/rnskill) · [xhs-visual-director-skill](https://github.com/ziguishian/xhs-visual-director-skill) · [Punk-Skill](https://github.com/adrianpunk/Punk-Skill) · [qiaomu-mondo-poster-design](https://github.com/joeseesun/qiaomu-mondo-poster-design) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [clipforge](https://github.com/xixihhhh/clipforge) · [gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [Viral_Writer_Skill](https://github.com/nashsu/Viral_Writer_Skill) · [yuwen-publish-precheck](https://github.com/yuwen-cool/yuwen-publish-precheck) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [blogger-distiller](https://github.com/otter1101/blogger-distiller) · [xhs-virtual-product](https://github.com/chenjin-cmd/xhs-virtual-product) · [gimi-illustration-skill](https://github.com/GiMi-Xiaomi/gimi-illustration-skill) · [xhs-cli](https://github.com/jackwener/xhs-cli) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [Document-illustrator-skill](https://github.com/op7418/Document-illustrator-skill) · [xiaohongshu-ai-workbench](https://github.com/mengke-wang/xiaohongshu-ai-workbench) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [social-push](https://github.com/jihe520/social-push) · [redbook](https://github.com/lucasygu/redbook) · [catbus](https://github.com/cv-cat/catbus) · [vivy-yi/xiaohongshu-skills](https://github.com/vivy-yi/xiaohongshu-skills) · [x-mcp](https://github.com/xpzouying/x-mcp) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover) · [cy-carousel-skill](https://github.com/chengyi-ai/cy-carousel-skill) · [xhs-claude-skills](https://github.com/chenxiachan/xhs-claude-skills) · [hotclip](https://github.com/xixihhhh/hotclip) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [lingzao-skill](https://github.com/atian-create/lingzao-skill) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [oil-cover](https://github.com/oil-oil/oil-cover) · [xiaohongshu-mcp-skills](https://github.com/autoclaw-cc/xiaohongshu-mcp-skills) · [ian-xhs-carousel](https://github.com/helloianneo/ian-xhs-carousel) · [oh-my-cover-design](https://github.com/hongfamonvAI/oh-my-cover-design) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video) · [video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill) · [content-pipeline](https://github.com/OrangeViolin/content-pipeline) · [xhs-cover-skill](https://github.com/Vivixiao980/xhs-cover-skill) · [wenzi-xiaohongshu-workflow](https://github.com/wenziai/wenzi-xiaohongshu-workflow) · [blcaptain-style-skill](https://github.com/dososo/blcaptain-style-skill) · [xhs-writer-skill](https://github.com/JuneYaooo/xhs-writer-skill) · [Spreado](https://github.com/BadKid90s/Spreado) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [openclaw-xhs](https://github.com/zhjiang22/openclaw-xhs) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [freestylefly/xiaohongshu-skills](https://github.com/freestylefly/xiaohongshu-skills) · [Fully-automatic-article-generation-skill](https://github.com/solar-luna/Fully-automatic-article-generation-skill) · [media-publish-check](https://github.com/XshuiAi/media-publish-check) · [Eva-skill](https://github.com/Lulu-Eva/Eva-skill) · [content-risk-detector](https://github.com/liuxingqitd/content-risk-detector) · [xiaohongshu-summarizer-skill](https://github.com/piekill/xiaohongshu-summarizer-skill) · [doubaoya-community](https://github.com/zizhanovo/doubaoya-community) · [red-publisher-skill](https://github.com/iamzifei/red-publisher-skill) · [xiaohongshu-images-skill](https://github.com/iamzifei/xiaohongshu-images-skill) · [xiaohongshu-doctor](https://github.com/softbread/xiaohongshu-doctor)

**抖音**（45）：[social-auto-upload](https://github.com/dreammis/social-auto-upload) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [yichen-skills](https://github.com/mcncarl/yichen-skills) · [Easel](https://github.com/ZJU-REAL/Easel) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [creator-buddy](https://github.com/SpaceZephyr/creator-buddy) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [rnskill](https://github.com/Pluviobyte/rnskill) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [clipforge](https://github.com/xixihhhh/clipforge) · [Viral_Writer_Skill](https://github.com/nashsu/Viral_Writer_Skill) · [yuwen-publish-precheck](https://github.com/yuwen-cool/yuwen-publish-precheck) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [blogger-distiller](https://github.com/otter1101/blogger-distiller) · [vibe-knowledge-film](https://github.com/HeyChengC/vibe-knowledge-film) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [catbus](https://github.com/cv-cat/catbus) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [hotclip](https://github.com/xixihhhh/hotclip) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [lingzao-skill](https://github.com/atian-create/lingzao-skill) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [douyin-live-recorder](https://github.com/WeiZhuochun/douyin-live-recorder) · [blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video) · [social-media-data-tools](https://github.com/jinchenma94/social-media-data-tools) · [ah-douyin-clean-downloader](https://github.com/ahang008/ah-douyin-clean-downloader) · [video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill) · [Spreado](https://github.com/BadKid90s/Spreado) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [douyin-image-post-scheduler](https://github.com/chengyi-ai/douyin-image-post-scheduler) · [traffic-compass](https://github.com/code-wahaha/traffic-compass) · [douyin-upload-mcp-skill](https://github.com/WJZ-P/douyin-upload-mcp-skill) · [media-publish-check](https://github.com/XshuiAi/media-publish-check) · [dy-cli](https://github.com/Youhai020616/douyin) · [Eva-skill](https://github.com/Lulu-Eva/Eva-skill) · [content-risk-detector](https://github.com/liuxingqitd/content-risk-detector) · [douyin-mcp-server](https://github.com/lancelin111/douyin-mcp-server) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news) · [doubaoya-community](https://github.com/zizhanovo/doubaoya-community) · [douyin-video-summary](https://github.com/liu-wei-ai/douyin-video-summary)

**微信公众号**（57）：[baoyu-skills](https://github.com/JimLiu/baoyu-skills) · [wechatDownload](https://github.com/qiye45/wechatDownload) · [html-anything](https://github.com/nexu-io/html-anything) · [xiaobei](https://github.com/TeamWiseFlow/xiaobei) · [guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill) · [Wechatsync](https://github.com/wechatsync/Wechatsync) · [we-mp-rss](https://github.com/rachelos/we-mp-rss) · [yichen-skills](https://github.com/mcncarl/yichen-skills) · [human-writing](https://github.com/KKKKhazix/human-writing) · [gzh-design-skill](https://github.com/isjiamu/gzh-design-skill) · [md2wechat-skill](https://github.com/geekjourneyx/md2wechat-skill) · [wewrite](https://github.com/imraywang/wewrite) · [writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) · [chatwiki](https://github.com/zhimaAi/chatwiki) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [creator-buddy](https://github.com/SpaceZephyr/creator-buddy) · [rnskill](https://github.com/Pluviobyte/rnskill) · [Punk-Skill](https://github.com/adrianpunk/Punk-Skill) · [qiaomu-mondo-poster-design](https://github.com/joeseesun/qiaomu-mondo-poster-design) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [wechat-download-api](https://github.com/tmwgsicp/wechat-download-api) · [wechat-article-to-markdown](https://github.com/jackwener/wechat-article-to-markdown) · [gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) · [Viral_Writer_Skill](https://github.com/nashsu/Viral_Writer_Skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [wechat-article-skills](https://github.com/aiworkskills/wechat-article-skills) · [xiaohu-wechat-format](https://github.com/xiaohuailabs/xiaohu-wechat-format) · [NewsCrawler](https://github.com/NanmiCoder/NewsCrawler) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [social-push](https://github.com/jihe520/social-push) · [SyncCaster](https://github.com/RyanYipeng/SyncCaster) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [writing-agent](https://github.com/dongbeixiaohuo/writing-agent) · [rayskills](https://github.com/imraywang/rayskills) · [wechat_article_skills](https://github.com/BND-1/wechat_article_skills) · [lingzao-skill](https://github.com/atian-create/lingzao-skill) · [jiji262/wechat-publisher](https://github.com/jiji262/wechat-publisher) · [bigpeng-hot-gzh](https://github.com/BigPengSays/bigpeng-hot-gzh) · [oh-my-cover-design](https://github.com/hongfamonvAI/oh-my-cover-design) · [content-pipeline](https://github.com/OrangeViolin/content-pipeline) · [blcaptain-style-skill](https://github.com/dososo/blcaptain-style-skill) · [gainubi/wechat-skills](https://github.com/gainubi/wechat-skills) · [wechat-article-publisher-skill](https://github.com/iamzifei/wechat-article-publisher-skill) · [wechat-article-extractor-skill](https://github.com/freestylefly/wechat-article-extractor-skill) · [jianshuo/claude-skills](https://github.com/jianshuo/claude-skills) · [843645440/wechat-skill](https://github.com/843645440/wechat-skill) · [wemp-operator](https://github.com/IanShaw027/wemp-operator) · [wechat-search-weread](https://github.com/KANIKIG/wechat-search-weread) · [wechat-article-formatter-skill](https://github.com/iamzifei/wechat-article-formatter-skill) · [wechat-typesetting-cy](https://github.com/CY-CHENYUE/wechat-typesetting-cy) · [Fully-automatic-article-generation-skill](https://github.com/solar-luna/Fully-automatic-article-generation-skill) · [Eva-skill](https://github.com/Lulu-Eva/Eva-skill) · [0731coderlee-sudo/wechat-publisher](https://github.com/0731coderlee-sudo/wechat-publisher) · [doubaoya-community](https://github.com/zizhanovo/doubaoya-community)

**微信视频号**（17）：[social-auto-upload](https://github.com/dreammis/social-auto-upload) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [yuwen-publish-precheck](https://github.com/yuwen-cool/yuwen-publish-precheck) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [hotclip](https://github.com/xixihhhh/hotclip) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [Spreado](https://github.com/BadKid90s/Spreado) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [media-publish-check](https://github.com/XshuiAi/media-publish-check) · [Eva-skill](https://github.com/Lulu-Eva/Eva-skill) · [content-risk-detector](https://github.com/liuxingqitd/content-risk-detector)

**B 站**（24）：[social-auto-upload](https://github.com/dreammis/social-auto-upload) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [bb-browser](https://github.com/epiral/bb-browser) · [Easel](https://github.com/ZJU-REAL/Easel) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [creator-buddy](https://github.com/SpaceZephyr/creator-buddy) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [catbus](https://github.com/cv-cat/catbus) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [hotclip](https://github.com/xixihhhh/hotclip) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [oil-cover](https://github.com/oil-oil/oil-cover) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video) · [video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news)

**微博**（12）：[baoyu-skills](https://github.com/JimLiu/baoyu-skills) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [bb-browser](https://github.com/epiral/bb-browser) · [writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [social-push](https://github.com/jihe520/social-push) · [catbus](https://github.com/cv-cat/catbus) · [weibo-cli](https://github.com/jackwener/weibo-cli) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news)

**知乎**（14）：[html-anything](https://github.com/nexu-io/html-anything) · [Wechatsync](https://github.com/wechatsync/Wechatsync) · [bb-browser](https://github.com/epiral/bb-browser) · [human-writing](https://github.com/KKKKhazix/human-writing) · [Easel](https://github.com/ZJU-REAL/Easel) · [md2wechat-skill](https://github.com/geekjourneyx/md2wechat-skill) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [social-push](https://github.com/jihe520/social-push) · [SyncCaster](https://github.com/RyanYipeng/SyncCaster) · [zhihu-cli](https://github.com/BAIGUANGMEI/zhihu-cli) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news)

**快手**（12）：[social-auto-upload](https://github.com/dreammis/social-auto-upload) · [growth-lab](https://github.com/tsingyuai/growth-lab) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [clipforge](https://github.com/xixihhhh/clipforge) · [catbus](https://github.com/cv-cat/catbus) · [redfox-community](https://github.com/redfox-data/redfox-community) · [hotclip](https://github.com/xixihhhh/hotclip) · [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [Spreado](https://github.com/BadKid90s/Spreado) · [media-publish-check](https://github.com/XshuiAi/media-publish-check) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news)

**今日头条**（8）：[Wechatsync](https://github.com/wechatsync/Wechatsync) · [md2wechat-skill](https://github.com/geekjourneyx/md2wechat-skill) · [last30days-skill-cn](https://github.com/Jesseovo/last30days-skill-cn) · [MatrixMedia](https://github.com/hanliang97/MatrixMedia) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [NewsCrawler](https://github.com/NanmiCoder/NewsCrawler) · [redfox-community](https://github.com/redfox-data/redfox-community) · [openclaw-daily-hot-news](https://github.com/one-box-u/openclaw-daily-hot-news)

**X（推特）**（46）：[last30days-skill](https://github.com/mvanhorn/last30days-skill) · [postiz-app](https://github.com/gitroomhq/postiz-app) · [baoyu-skills](https://github.com/JimLiu/baoyu-skills) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [html-anything](https://github.com/nexu-io/html-anything) · [follow-builders](https://github.com/zarazhangrui/follow-builders) · [bb-browser](https://github.com/epiral/bb-browser) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [yichen-skills](https://github.com/mcncarl/yichen-skills) · [social-media-agent](https://github.com/langchain-ai/social-media-agent) · [x-mentor-skill](https://github.com/alchaincyf/x-mentor-skill) · [chubbyskills](https://github.com/chubbyguan/chubbyskills) · [x-research-skill](https://github.com/rohunvora/x-research-skill) · [locoagent](https://github.com/LocoreMind/locoagent) · [x-tweet-fetcher](https://github.com/ythx-101/x-tweet-fetcher) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [x-article-publisher-skill](https://github.com/wshuyi/x-article-publisher-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post) · [NewsCrawler](https://github.com/NanmiCoder/NewsCrawler) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [Document-illustrator-skill](https://github.com/op7418/Document-illustrator-skill) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_) · [postiz-agent](https://github.com/gitroomhq/postiz-agent) · [social-push](https://github.com/jihe520/social-push) · [catbus](https://github.com/cv-cat/catbus) · [redfox-community](https://github.com/redfox-data/redfox-community) · [rayskills](https://github.com/imraywang/rayskills) · [twitterapi-io](https://github.com/kaitoInfra/twitterapi-io) · [ai-influence-digest](https://github.com/koffuxu/ai-influence-digest) · [head-of-content](https://github.com/bradautomates/head-of-content) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [xint](https://github.com/0xNyk/xint) · [Taisly Agent Kit](https://github.com/taisly/agent) · [x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [x-skills](https://github.com/sergebulaev/x-skills) · [jianshuo/claude-skills](https://github.com/jianshuo/claude-skills) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [socialclaw](https://github.com/ndesv21/socialclaw) · [publora/skills](https://github.com/publora/skills) · [x-ai-topic-selector](https://github.com/vigorX777/x-ai-topic-selector) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [apidojo-io/social-media-skills](https://github.com/apidojo-io/social-media-skills)

**YouTube**（46）：[last30days-skill](https://github.com/mvanhorn/last30days-skill) · [postiz-app](https://github.com/gitroomhq/postiz-app) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [follow-builders](https://github.com/zarazhangrui/follow-builders) · [bb-browser](https://github.com/epiral/bb-browser) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [youtube-agent-skill](https://github.com/Jakeschincariol/youtube-agent-skill) · [youtube-shorts-pipeline](https://github.com/rushindrasinha/youtube-shorts-pipeline) · [herk-edit-kit](https://github.com/nateherkai/herk-edit-kit) · [claude-real-video](https://github.com/HUANGCHIHHUNGLeo/claude-real-video) · [Youtube-clipper-skill](https://github.com/op7418/Youtube-clipper-skill) · [video-podcast-maker](https://github.com/Agents365-ai/video-podcast-maker) · [ZeroPointRepo/youtube-skills](https://github.com/ZeroPointRepo/youtube-skills) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [trypost](https://github.com/trypostit/trypost) · [self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) · [feedgrab](https://github.com/iBigQiang/feedgrab) · [chatgpt-video-editing-skills](https://github.com/Jaycheng1103/chatgpt-video-editing-skills) · [claude-youtube](https://github.com/AgriciDaniel/claude-youtube) · [smart-illustrator](https://github.com/axtonliu/smart-illustrator) · [postiz-agent](https://github.com/gitroomhq/postiz-agent) · [claude-design-card](https://github.com/geekjourneyx/claude-design-card) · [redfox-community](https://github.com/redfox-data/redfox-community) · [nova-youtube-agent](https://github.com/sharbelxyz/nova-youtube-agent) · [panda-video-generator](https://github.com/szhshp/panda-video-generator) · [head-of-content](https://github.com/bradautomates/head-of-content) · [video-publisher-skill](https://github.com/oil-oil/video-publisher-skill) · [blcaptain-lingjian-video](https://github.com/dososo/blcaptain-lingjian-video) · [video-to-subtitle-summary-skill](https://github.com/imlewc/video-to-subtitle-summary-skill) · [Taisly Agent Kit](https://github.com/taisly/agent) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [content-skills](https://github.com/vyralcontent/content-skills) · [reelclaw](https://github.com/dansugc/reelclaw) · [jianshuo/claude-skills](https://github.com/jianshuo/claude-skills) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [socialclaw](https://github.com/ndesv21/socialclaw) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [sergebulaev/youtube-skills](https://github.com/sergebulaev/youtube-skills) · [youtube-scout](https://github.com/AgriciDaniel/youtube-scout) · [publora/skills](https://github.com/publora/skills) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [claude-reel-editor](https://github.com/nicolapocock/claude-reel-editor) · [tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes)

**TikTok**（31）：[last30days-skill](https://github.com/mvanhorn/last30days-skill) · [postiz-app](https://github.com/gitroomhq/postiz-app) · [social-auto-upload](https://github.com/dreammis/social-auto-upload) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [youtube-shorts-pipeline](https://github.com/rushindrasinha/youtube-shorts-pipeline) · [clipforge](https://github.com/xixihhhh/clipforge) · [trypost](https://github.com/trypostit/trypost) · [chatgpt-video-editing-skills](https://github.com/Jaycheng1103/chatgpt-video-editing-skills) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [catbus](https://github.com/cv-cat/catbus) · [redfox-community](https://github.com/redfox-data/redfox-community) · [clipcat-skill](https://github.com/Clipcat-ai/clipcat-skill) · [head-of-content](https://github.com/bradautomates/head-of-content) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [Taisly Agent Kit](https://github.com/taisly/agent) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [jev-social](https://github.com/socai-io/jev-social) · [content-skills](https://github.com/vyralcontent/content-skills) · [reelclaw](https://github.com/dansugc/reelclaw) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill) · [socialclaw](https://github.com/ndesv21/socialclaw) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [tiktok-skills](https://github.com/sergebulaev/tiktok-skills) · [publora/skills](https://github.com/publora/skills) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [claude-reel-editor](https://github.com/nicolapocock/claude-reel-editor) · [tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [apidojo-io/social-media-skills](https://github.com/apidojo-io/social-media-skills)

**Instagram**（33）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [charlie947/social-media-skills](https://github.com/charlie947/social-media-skills) · [instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill) · [youtube-shorts-pipeline](https://github.com/rushindrasinha/youtube-shorts-pipeline) · [herk-edit-kit](https://github.com/nateherkai/herk-edit-kit) · [trypost](https://github.com/trypostit/trypost) · [claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post) · [instagram-skills](https://github.com/sergebulaev/instagram-skills) · [chatgpt-video-editing-skills](https://github.com/Jaycheng1103/chatgpt-video-editing-skills) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [postiz-agent](https://github.com/gitroomhq/postiz-agent) · [redfox-community](https://github.com/redfox-data/redfox-community) · [claude-content-skills](https://github.com/Ootto-AI/claude-content-skills) · [head-of-content](https://github.com/bradautomates/head-of-content) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [Taisly Agent Kit](https://github.com/taisly/agent) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [jev-social](https://github.com/socai-io/jev-social) · [content-skills](https://github.com/vyralcontent/content-skills) · [reelclaw](https://github.com/dansugc/reelclaw) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill) · [socialclaw](https://github.com/ndesv21/socialclaw) · [hook-lab](https://github.com/hongfamonvAI/hook-lab) · [publora/skills](https://github.com/publora/skills) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [claude-reel-editor](https://github.com/nicolapocock/claude-reel-editor) · [tiktok-video-skills](https://github.com/iart-ai/tiktok-video-skills) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes) · [apidojo-io/social-media-skills](https://github.com/apidojo-io/social-media-skills) · [skillify-sh/skills](https://github.com/skillify-sh/skills)

**LinkedIn**（22）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [bb-browser](https://github.com/epiral/bb-browser) · [sergebulaev/linkedin-skills](https://github.com/sergebulaev/linkedin-skills) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [charlie947/social-media-skills](https://github.com/charlie947/social-media-skills) · [social-media-agent](https://github.com/langchain-ai/social-media-agent) · [linkedin-agent-skill](https://github.com/Jakeschincariol/linkedin-agent-skill) · [ai-copywriter](https://github.com/mikiarlo3/ai-copywriter) · [locoagent](https://github.com/LocoreMind/locoagent) · [trypost](https://github.com/trypostit/trypost) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [postiz-agent](https://github.com/gitroomhq/postiz-agent) · [motion-graphics-skills](https://github.com/charlie947/motion-graphics-skills) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [jev-social](https://github.com/socai-io/jev-social) · [threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill) · [Linked-API/linkedin-skills](https://github.com/Linked-API/linkedin-skills) · [socialclaw](https://github.com/ndesv21/socialclaw) · [publora/skills](https://github.com/publora/skills) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes)

**Threads**（11）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [trypost](https://github.com/trypostit/trypost) · [claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [threads-carousel-claude-skill](https://github.com/itchernetski/threads-carousel-claude-skill) · [publora/skills](https://github.com/publora/skills) · [threads-skills](https://github.com/sergebulaev/threads-skills) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes)

**Facebook**（13）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [OpenCreator](https://github.com/krillinai/OpenCreator) · [trypost](https://github.com/trypostit/trypost) · [claude-skill-social-post](https://github.com/Hao0321/claude-skill-social-post) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [social-ai-team](https://github.com/stevenflanagan1/social-ai-team) · [Taisly Agent Kit](https://github.com/taisly/agent) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [socialclaw](https://github.com/ndesv21/socialclaw) · [facebook-skills](https://github.com/sergebulaev/facebook-skills) · [publora/skills](https://github.com/publora/skills) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes)

**Reddit**（11）：[last30days-skill](https://github.com/mvanhorn/last30days-skill) · [postiz-app](https://github.com/gitroomhq/postiz-app) · [bb-browser](https://github.com/epiral/bb-browser) · [social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) · [locoagent](https://github.com/LocoreMind/locoagent) · [autocli-skill](https://github.com/nashsu/autocli-skill) · [union-search-skill](https://github.com/runningZ1/union-search-skill) · [rdt-cli](https://github.com/public-clis/rdt-cli) · [tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) · [socialclaw](https://github.com/ndesv21/socialclaw) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill)

**Pinterest**（7）：[postiz-app](https://github.com/gitroomhq/postiz-app) · [trypost](https://github.com/trypostit/trypost) · [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) · [social-media-skills/skills](https://github.com/social-media-skills/skills) · [socialclaw](https://github.com/ndesv21/socialclaw) · [upload-post-skill](https://github.com/Upload-Post/upload-post-skill) · [social-media-image-sizes](https://github.com/Branding5/social-media-image-sizes)

**Substack 和 Newsletter**（3）：[charlie947/social-media-skills](https://github.com/charlie947/social-media-skills) · [writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) · [motion-graphics-skills](https://github.com/charlie947/motion-graphics-skills)

**通用**（13）：[humanizer](https://github.com/blader/humanizer) · [Humanizer-zh](https://github.com/op7418/Humanizer-zh) · [dbskill](https://github.com/dontbesilent2025/dbskill) · [video-spec-builder](https://github.com/feicaiclub/video-spec-builder) · [digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) · [qu-ai-wei](https://github.com/LifelongLazyLearner/qu-ai-wei) · [clipify](https://github.com/louisedesadeleer/clipify) · [anti-ai-slop-writing](https://github.com/jalaalrd/anti-ai-slop-writing) · [DaVinci-AutoEdit-Agent](https://github.com/liuluhaixiu/DaVinci-AutoEdit-Agent) · [xiaoma-durex-copywriter](https://github.com/crawfordxx/xiaoma-durex-copywriter) · [xiaohu-ip-studio](https://github.com/xiaohuailabs/xiaohu-ip-studio) · [humanizer-skill](https://github.com/Aboudjem/humanizer-skill) · [ai-video-editing-skill](https://github.com/znyupup/ai-video-editing-skill)

<a id="faq"></a>
## 常见问题

### 做小红书有哪些好用的 skill？

收录的项目里，明确针对小红书的有 83 个，星数最高的是 [baoyu-skills](https://github.com/JimLiu/baoyu-skills)、[xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp)、[social-auto-upload](https://github.com/dreammis/social-auto-upload)。写笔记看[文案和内容创作](#group-writing)，排版和做封面看[排版、封面配图和短视频](#group-visual)，想自动发布看[发布和自动化](#group-publish)。完整对照见[按平台查找](#by-platforms)。

### 有写公众号文章、排版和发布的 skill 吗？

有。针对微信公众号的有 57 个，星数最高的是 [baoyu-skills](https://github.com/JimLiu/baoyu-skills)、[wechatDownload](https://github.com/qiye45/wechatDownload)、[html-anything](https://github.com/nexu-io/html-anything)。多数能把 Markdown 排成公众号样式，不少能直接推到草稿箱，最后发出去一般还要你在后台自己点。

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

针对 X 的有 46 个，YouTube 46 个，TikTok 31 个，LinkedIn 22 个。不挑平台的通用项目有 13 个，星数最高的是 [humanizer](https://github.com/blader/humanizer)、[Humanizer-zh](https://github.com/op7418/Humanizer-zh)、[dbskill](https://github.com/dontbesilent2025/dbskill)。

### 让 agent 自动发帖安全吗？会不会封号？

有两层风险。一是账号：自动发布多半要用你的账号登录，有的把 cookie 存在本地，装之前要看清楚登录态存在哪、有没有发到别的服务器。二是平台规则：各平台都限制自动化操作，批量发布、频繁互动可能被限流或封号。稳妥的用法是让 agent 写好、排好，最后一步自己点发布。

### 这些项目安全吗？

收录前逐个核对过仓库说明、目录和文件，并用脚本查过二进制和压缩包、安装钩子、远程执行和读敏感文件。收录了 174 个 skill 项目和 24 个工具与平台。看过但没收的，原因逐条记在 [data/ignore.toml](data/ignore.toml)（目前 20 个）。正常的 skill 只是几份文本文件，用不着 exe 或 dmg。脚本查不到不等于安全，安装前先读一遍它的 `SKILL.md` 和脚本。

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
