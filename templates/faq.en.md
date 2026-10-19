### What are the best agent skills for social media?

This list has {{count}} hand-checked skill projects (data updated {{updated}}). Start with [All-in-one](#group-pipeline) if you run the whole loop yourself; otherwise go straight to [Writing and content](#group-writing), [Publishing and automation](#group-publish) or [Topics, trends and analytics](#group-research). The [By platform](#by-platforms) index lists every project per platform.

### Which skills work for X, YouTube, TikTok and LinkedIn?

{{facet:platforms:x}} projects target X, {{facet:platforms:youtube}} YouTube, {{facet:platforms:tiktok}} TikTok and {{facet:platforms:linkedin}} LinkedIn. {{facet:platforms:general}} work on any platform; the most-starred are {{top:facet:platforms:general}}.

### What is a social media skill, and how is it different from an MCP server?

A skill is a capability pack for an AI agent: a folder built around a `SKILL.md` file, sometimes with scripts and templates. Once installed, the agent follows it for one job, such as writing a LinkedIn post in your voice or turning an article into a thread. An MCP server is a tool that lets the agent read from or post to a platform directly. They are often used together: the skill decides what to write, the MCP server publishes it. MCP servers are listed separately under [MCP servers and CLI tools](#group-mcp) and are not counted as skills.

### Is it safe to let an agent post for me? Can my account get banned?

There are two risks. Your account: automated posting usually logs in as you, and some tools store your cookies on disk, so check where your session is kept and whether it is sent to another server. Platform rules: every platform limits automation, and bulk posting or heavy engagement can get an account throttled or banned. The safe pattern is to let the agent draft and schedule, and click publish yourself.

### What about Chinese platforms like Xiaohongshu (RedNote), Douyin and WeChat?

{{facet:platforms:xiaohongshu}} projects target Xiaohongshu, {{facet:platforms:douyin}} Douyin and {{facet:platforms:wechat}} WeChat Official Accounts. Most are documented in Chinese; the descriptions here are translated.

### Are these projects safe to install?

Every repo was checked by hand (README, folders and files) and scanned by a script for binaries and archives, install hooks, remote code execution and reads of sensitive files. {{count}} skill projects and {{platforms}} tools and platforms made the list. Repos that were reviewed and turned down are recorded with the reason in [data/ignore.toml](data/ignore.toml) (in Chinese; {{ignored}} so far). A normal skill is a few text files and never needs an .exe or .dmg. A clean scan does not prove a skill is safe, so read its `SKILL.md` and scripts before installing.

### How often is the list updated?

Every Monday, stars, last-updated dates and licenses refresh automatically and new repos are searched; new repos are added only after a manual check. See [New this week](#new).
