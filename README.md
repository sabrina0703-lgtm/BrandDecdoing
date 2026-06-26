# BrandDecdoing
品牌生意解码工作流 Skill — 一键启动7模块深度解码，输出LV高级商业风格交互式HTML报告。

这是什么？
BrandDecoding 是一个 WorkBuddy Skill，专为品牌总监/营销从业者设计。输入一个品牌名，即可按7大模块分步深度解码该品牌的生意现状：

宏观环境分析 (PEST)
行业洞察 (TAM-SAM-SOM / 波特五力 / CR5 / KSF)
品牌洞察 (4P框架 / BCG象限 / 生态位定位图)
用户洞察 (5A / CJM / JTBD / 需求金字塔)
竞争格局 (三级分层 / 雷达图 / 战略群组)
财务与增长 (商业模式画布 / S曲线 / UE / 飞轮)
综合诊断 (SWOT矩阵 / P0/P1/P2策略 / 5维评分)
每个模块完成后用户审核确认再推进，最终生成一份LV高级商业风格的交互式HTML网页报告。

报告风格预览
色板：深棕 #3E2D1C + 象牙白 #F5F0E8 + 金色 #C5A572
字体：Cormorant Garamond（英文标题） + Noto Serif SC（中文正文）
左侧固定导航栏，滚动自动高亮
BCG矩阵 + 品牌生态位用 SVG 象限图呈现
9张 Summary 信息卡片（规模/增速/市占/核心用户/城市/渠道/均价/核心产品/品牌主张）
安装方式
方式一：手动安装（推荐）
克隆或下载本仓库

bash
git clone https://github.com/<your-username>/BrandDecoding.git
或直接下载 ZIP 并解压。

将 BrandDecoding/ 文件夹复制到你的 WorkBuddy skills 目录：

Windows: %USERPROFILE%\.workbuddy\skills\brand-decoding\
macOS/Linux: ~/.workbuddy/skills/brand-decoding/
确保目录结构如下：

~/.workbuddy/skills/brand-decoding/
├── SKILL.md              (必须)
├── assets/
│   └── report-template.html
└── references/
    └── framework.md
重启 WorkBuddy 或刷新会话，skill 即自动生效。

方式二：直接下载 zip
下载 BrandDecoding.zip，解压后按上述路径放置即可。

使用方式
在 WorkBuddy 对话中输入品牌名即可触发：

"分析三养品牌"
"帮我解码瑞幸咖啡的生意"
"品牌分析 Nike"
"XX品牌怎么样"
"decode 三养"
也可在分析时提供 PDF/图片等内部资料作为补充数据源：

"分析三养品牌 @三养品牌公司介绍.pdf"
Skill 文件说明
文件	说明
SKILL.md	核心工作流定义：触发条件、7模块流程、写作规范、质量标准
assets/report-template.html	LV风格HTML报告模板：CSS变量、Google Fonts、侧边栏导航JS、全部组件样式
references/framework.md	7模块数据采集清单、搜索关键词模板、分析框架、数据来源映射
核心原则
数据来源真实权威 — 每条数据标注来源、时间和可信度等级
分析导向，而非数据堆砌 — 每个章节有分析归纳和 mini-conclusion
Key finding 必须附具体数值 — 不允许模糊表述
严格对齐用户框架 — 只用7模块模型，不自行增减维度
分步确认，逐步推进 — 不跳过用户审核
所有外币金额换算为人民币
许可
MIT License — 自由使用、修改和分发。
