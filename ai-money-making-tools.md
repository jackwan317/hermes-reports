# AI Agent Skills / MCP Servers / Tools — 赚钱变现清单

> 搜罗范围：GitHub awesome-mcp-servers (88k⭐)、awesome-ai-agents、MCP marketplace、相关开源项目
> 目标：找到 AI Agent 可直接调用、组合、自动化执行的赚钱能力，而不是单步提效小工具。
> 收集日期：2026-05-28

---

## 一、低成本获客引流 🎯

| # | 名称 | 来源 | 如何帮你赚钱 | 建议 Skill 组合 |
|---|------|------|-------------|----------------|
| 1 | **Gorilla MCP** — 社交媒体痛点发现+自动外联 | [opusforge/gorilla-mcp](https://github.com/opusforge/gorilla-mcp) | 扫描 Reddit/X/YouTube/TikTok 上描述你产品能解决的问题的帖子，按购买意图排序，自动生成外联话术，帮你零成本找到精准客户 | Browser-use + Apollo.io MCP + Mailchimp MCP 形成「发现→触达→邮件培育」全自动引流闭环 |
| 2 | **Apollo.io MCP** — B2B 销售情报 | [louis030195/apollo-io-mcp](https://github.com/louis030195/apollo-io-mcp) | 搜索 2.75 亿+ B2B 联系人，按行业/规模筛选潜在客户，自动获取邮箱和电话，批量外联获客 | Tomba MCP(邮箱验证) + Mailchimp MCP(邮件群发) + Salesforce Marketing MCP(线索管理) |
| 3 | **Tomba MCP** — 邮箱发现与验证 | [tomba-io/tomba-mcp-server](https://github.com/tomba-io/tomba-mcp-server) | 按域名批量发现企业邮箱，验证有效性，获取 LinkedIn 资料，建精准客户邮箱列表 | Apollo.io MCP + Citedy SEO Agent(内容引流) |
| 4 | **LinkedHelper MCP** — LinkedIn 自动化 | [alexey-pelykh/lhremote](https://github.com/alexey-pelykh/lhremote) | 32 工具自动化 LinkedIn 获客：批量加好友、发消息、管理 campaign，低成本 B2B 拓客 | Apollo.io MCP(找线索) → LinkedHelper(触达) → Salesforce MCP(管理) |
| 5 | **Citedy SEO Agent** — 全栈 AI 营销 | [Citedy/citedy-seo-agent](https://github.com/Citedy/citedy-seo-agent) | 41 工具：发现 X/Reddit 趋势、分析竞品、找内容缺口、自动生成 55 语言 SEO 文章+插图+配音+视频，全网分发 9 平台引流 | BlogBurst MCP(多平台发布) + Google Search Console MCP(SEO监控) |
| 6 | **BlogBurst MCP** — 内容多平台分发 | [shensi8312/blogburst-mcp-server](https://github.com/shensi8312/blogburst-mcp-server) | 一篇内容自动适配发布到 Twitter/LinkedIn/Reddit/Bluesky/Threads/TikTok/YouTube 等 9+ 平台，最大化内容触达 | Citedy SEO Agent(内容生成) + Clamp MCP(流量分析) |
| 7 | **LocalSEOData MCP** — 本地 SEO 全套 | [localseodata/mcp-server](https://github.com/localseodata/mcp-server) | 42 个本地 SEO 工具：SERP 追踪、Google Business Profile 管理、评价监控、竞品分析、关键词研究。适合帮本地商家做 SEO 代运营赚钱 | Google Search Console MCP + AI Visibility MCP(品牌监控) |
| 8 | **AI Visibility MCP** — 品牌在 AI 搜索中的可见度 | [krissanders/ai-visibility-mcp](https://github.com/krissanders/ai-visibility-mcp) | 监控你的品牌在 ChatGPT/Claude/Perplexity/Gemini 中的可见度，分析哪种 AI 推荐你、怎么说你，优化 AI SEO | LocalSEOData MCP + Competlab MCP |
| 9 | **Pipepost** — 终端一键多平台发布 | [MendleM/Pipepost](https://github.com/MendleM/Pipepost) | 从终端直接发布 SEO 评分文章到 Dev.to/Ghost/Hashnode/WordPress/Medium，自动生成社交帖子，降低内容分发的边际成本 | Citedy SEO Agent(内容生产) + BlogBurst(社交分发) |
| 10 | **Synter Media MCP** — 跨平台广告管理 | [Synter-Media-AI/mcp-server](https://github.com/Synter-Media-AI/mcp-server) | 一个 MCP 管理 Google/Meta/LinkedIn/Microsoft/Reddit/TikTok 六大广告平台，AI 自动优化出价和创意，降低获客成本 | Meta Ads MCP + Google Ads MCP |

---

## 二、商机发现 / 市场调研 🔍

| # | 名称 | 来源 | 如何帮你赚钱 | 建议 Skill 组合 |
|---|------|------|-------------|----------------|
| 1 | **Intelligence API** — 电商情报一体化 | [samrothschild23/intelligence-api](https://github.com/samrothschild23/intelligence-api) | 分析任意 Shopify 店铺、研究 Amazon 产品（含 Opportunity Score + FBA 利润预估）、从 Google Maps 找 Qualified Sales Leads，一站发现商机 | BuyWhere MCP(跨境比价) + Amazon Seller Central MCP(卖家数据) |
| 2 | **Competlab MCP** — 竞品情报平台 | [competlab/competlab-mcp-server](https://github.com/competlab/competlab-mcp-server) | 24 工具监控竞品定价、内容、定位、技术栈、AI 可见度（ChatGPT/Claude/Gemini 怎么 rank 你），找到市场缺口 | Intelligence API(市场调研) + AI Visibility MCP |
| 3 | **Fundzwatch MCP** — 实时商业事件情报 | [Fund-z/fundzwatch-mcp](https://github.com/Fund-z/fundzwatch-mcp) | 追踪融资事件、收购、高管变动、AI 评分线索，发现新兴赛道和潜在客户 | Apollo.io MCP(触达被投公司) + DeepLook MCP(公司研究) |
| 4 | **Government Tender MCP** — 政府采购商机匹配 | [carlosahumada89/govrider-mcp-server](https://github.com/carlosahumada89/govrider-mcp-server) | 匹配你的技术产品到全球 25+ 官方来源的数千个政府采购招标/RFP/拨款，B2G 赚钱 | Tomba MCP(找决策人邮箱) + 自动投标流程 |
| 5 | **DeepLook** — 免费公司研究 Agent | [OSOJDJD/deeplook](https://github.com/OSOJDJD/deeplook) | 10 个数据源，~10 秒生成结构化研究报告（含牛/熊判断），覆盖股票/加密货币/私人公司 | Fundzwatch MCP(事件追踪) + EquiVault MCP(股票基本面) |
| 6 | **EquiVault MCP** — AI 股权投资研究 | [equivault/equivault-mcp](https://github.com/equivault/equivault-mcp) | 38 工具覆盖公司基本面、财务报表、估值指标、内幕交易、盈利质量等，AI 驱动的价值投资研究 | DeepLook(快速扫描) + FinancialData MCP(历史数据回测) |
| 7 | **BuyWhere MCP** — 跨境比价选品 | [BuyWhere/buywhere-mcp](https://github.com/BuyWhere/buywhere-mcp) | 搜索新加坡/东南亚/美国 300 万+产品，跨市场比价，发现套利机会 | DSers MCP(一键铺货) + Intelligence API(利润分析) |
| 8 | **ShopGraph** — 开放 Web 产品数据提取 | [laundromatic/shopgraph](https://github.com/laundromatic/shopgraph) | Schema.org + AI 提取电商产品结构化数据，批量获取竞品信息和市场数据 | BuyWhere MCP(跨境比价) + Firecrawl MCP(网页抓取) |
| 9 | **Sylex Search** — 通用搜索引擎 for AI Agent | [MastadoonPrime/sylex-search](https://github.com/MastadoonPrime/sylex-search) | 毫秒级搜索产品/服务/商家，AI Agent 的 Google，零 LLM 调用成本，发现一切商机 | Firecrawl MCP(深度抓取) + 分析 Pipeline |
| 10 | **Firecrawl MCP** — 网站转 LLM 可用数据 | [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) (60.7k⭐) | 将任意网站转为 Markdown/结构化数据，批量抓取竞品、市场信息，喂给 AI 分析 | Scrapling MCP(反爬网站) + 数据分析 Agent |

---

## 三、产品选品与自动上架 🛒

| # | 名称 | 来源 | 如何帮你赚钱 | 建议 Skill 组合 |
|---|------|------|-------------|----------------|
| 1 | **DSers MCP** — AliExpress 一键铺货到 Shopify/Wix | [lofder/dsers-mcp-product](https://github.com/lofder/dsers-mcp-product) | 从 AliExpress/Alibaba 批量导入产品到 Shopify/Wix，支持变体编辑、定价规则、多店铺推送。Dropshipping 自动化核心 | Intelligence API(选品分析) + BuyWhere MCP(比价) + Amazon Seller Central MCP(跨平台管理) |
| 2 | **Amazon Seller Central MCP** — 亚马逊卖家全管理 | [agentcentral-to/agent-central-mcp](https://github.com/agentcentral-to/agent-central-mcp) | 远程 MCP 暴露亚马逊卖家全部数据：库存、订单、目录、财务、物流、广告。AI 驱动店铺运营 | Intelligence API(竞品分析) + Amazon Ads MCP(广告投放) |
| 3 | **Ozon MCP** — 俄罗斯电商全管理 | [PCDCK/ozon-mcp](https://github.com/PCDCK/ozon-mcp) | 466 API 方法的完整 Ozon Seller + Performance 接口，支持库存风险、内容审计、定价策略、仓储分布等 13 个分析工作流 | BuyWhere MCP(跨境选品) + Cerebrochain MCP(物流) |
| 4 | **Cerebrochain MCP** — 供应链+物流智能 | [OFODevelopment/cerebrochain-mcp-server](https://github.com/OFODevelopment/cerebrochain-mcp-server) | 20 工具：85+ 承运商比价、库存管理、订单追踪、车队物流、AI 需求预测，全链路供应链自动化 | DSers MCP(铺货) + Ozon MCP/Amazon MCP(多平台管理) |
| 5 | **Color Me Shop MCP** — 日本电商平台管理 | [pepabo/colormeshop-mcp](https://github.com/pepabo/colormeshop-mcp) | 日本 GMO Pepabo 官方 MCP，管理订单/产品/库存/客户/优惠券/店铺设置，打入日本市场 | BuyWhere MCP(日本市场选品) + Rakuten MCP(乐天市场) |
| 6 | **Rakuten MCP** — 日本乐天市场 | [mrslbt/rakuten-mcp](https://github.com/mrslbt/rakuten-mcp) | 日本最大电商平台产品搜索+酒店旅行预订+食谱查询，日本市场选品必备 | Color Me Shop MCP + AI Furniture Hub MCP(家具细分) |
| 7 | **Affiliate Syndicate Links MCP** — AI 联盟营销基础设施 | [cmcgrabby-hue/syndicate-links](https://github.com/cmcgrabby-hue/syndicate-links) | 7 工具：联盟计划发现、归因追踪、佣金状态、结算。AI Agent 自己做淘宝客/Amazon Affiliate 赚钱 | Content Generation(自动内容) + BlogBurst MCP(分发) |
| 8 | **AgentoAI** — Magento AI Agent | [Genaker/AgentoAI](https://github.com/Genaker/AgentoAI) | Magento 电商的 AI 代理：产品内容创建、报表生成、产品促销图/视频生成、AI 分析 | DSers MCP(铺货) + Cerebrochain MCP(物流) |
| 9 | **Fewsats Amazon MCP** — Amazon 搜索+购买 | [Fewsats/amazon-mcp](https://github.com/Fewsats/amazon-mcp) | AI Agent 可以直接搜索和购买 Amazon 产品（L402 协议），实现自动化采购和套利 | BuyWhere MCP(比价) + Intelligence API(利润计算) |
| 10 | **MoneyPrinterTurbo** — 一键生成带货短视频 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) (44k⭐) | 一键 AI 生成高清短视频，可用于产品展示、带货视频，全自动内容工厂 | 产品数据 API + 短视频矩阵发布 |

---

## 四、自动化销售 💰

| # | 名称 | 来源 | 如何帮你赚钱 | 建议 Skill 组合 |
|---|------|------|-------------|----------------|
| 1 | **Apollo.io MCP** — B2B 销售自动化 | [louis030195/apollo-io-mcp](https://github.com/louis030195/apollo-io-mcp) | 搜索→筛选→获取联系方式→自动外联，B2B 销售全流程 AI 化 | Salesforce Marketing MCP(CRM 管理) + Mailchimp MCP(邮件自动化) |
| 2 | **Salesforce Marketing MCP** — 营销+收入运营 | [ZLeventer/salesforce-marketing-mcp](https://github.com/ZLeventer/salesforce-marketing-mcp) | 47 工具管理线索/联系人/客户/Campaign，17 个报表工具含 ROI 归因、多渠道影响力、MQL 趋势等 | Apollo.io MCP(获客) → Mailchimp MCP(培育) → Salesforce(转化追踪) |
| 3 | **Mailchimp MCP** — 邮件营销自动化 | [damientilman/mailchimp-mcp-server](https://github.com/damientilman/mailchimp-mcp-server) | 53 工具管理 Campaign/受众/报表/自动化/Landing Page/电商数据，AI 驱动的邮件营销 | Tomba MCP(邮箱验证) + DeliverIQ MCP(邮件送达率优化) |
| 4 | **DeliverIQ MCP** — 邮件送达率优化 | [Davison-Francis/min8t-sdks](https://github.com/Davison-Francis/min8t-sdks) | 12 工具：邮箱验证、SPF/DKIM/DMARC 分析、垃圾邮件评分、域名信任度报告。确保营销邮件不进入垃圾箱 | Mailchimp MCP(发送) + Tomba MCP(验证) |
| 5 | **Meta Ads MCP** (123 tools) | [mikusnuz/meta-ads-mcp](https://github.com/mikusnuz/meta-ads-mcp) | 123 工具管理 Facebook/Instagram 广告：Campaign/受众/创意/洞察/目录/自动规则。AI 优化广告投放 ROI | TikTok Ads MCP + Google Ads MCP(全平台投放) |
| 6 | **TikTok Ads MCP** | [AdsMCP/tiktok-ads-mcp-server](https://github.com/AdsMCP/tiktok-ads-mcp-server) | AI 管理 TikTok 广告全流程：Campaign/受众/创意/分析，低成本获取 TikTok 流量 | Meta Ads MCP + Google Ads MCP |
| 7 | **Google Ads MCP** | [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) | AI 管理 Google Ads：搜索/展示/购物广告，自动化出价和优化 | Meta Ads MCP + TikTok Ads MCP(全渠道) |
| 8 | **Mureo — AI 广告策略框架** | [logly/mureo](https://github.com/logly/mureo) | 基于本地 STRATEGY.md 的 AI 广告 Agent，不是盲目追指标而是执行战略。管理 Google Ads + Meta Ads + Search Console | 所有广告 MCP + Google Search Console MCP(SEO) |
| 9 | **X-Grow — Twitter/X 算法优化** | [BlockRunAI/x-grow](https://github.com/BlockRunAI/x-grow) | 优化 X/Twitter 帖子以最大化算法推荐，AI 生成配图，自动提高曝光和转化 | BlogBurst MCP(多平台分发) + Gorilla MCP(找潜在客户) |
| 10 | **Agent1st Ads MCP** — Meta+TikTok 一键创建广告 | [Nolas-Shadow/agent1st-ads-mcp](https://github.com/Nolas-Shadow/agent1st-ads-mcp) | 一次工具调用创建完整广告 Campaign（定向+创意+预算+广告），极简广告投放 | Meta Ads MCP + TikTok Ads MCP(精细化优化) |
| 11 | **Xendit MCP** — 东南亚支付 | [mrslbt/xendit-mcp](https://github.com/mrslbt/xendit-mcp) | 东南亚五国（印尼/菲律宾/泰国/越南/马来西亚）支付网关：发票/付款/银行转账，AI 收钱 | 电商 MCP(卖货) → Xendit(收款) |
| 12 | **Frihet MCP** — AI 商业管理 | [Frihet-io/frihet-mcp](https://github.com/Frihet-io/frihet-mcp) | 31 工具：发票/费用/客户/产品/报价，AI 原生 business management，一个人就是一个公司 | 电商 MCP + Xendit(收款) + Cerebrochain(物流) |

---

## 五、内容变现 📹

| # | 名称 | 来源 | 如何帮你赚钱 | 建议 Skill 组合 |
|---|------|------|-------------|----------------|
| 1 | **MoneyPrinterTurbo** — AI 短视频一键生成 | [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) (44k⭐) | 一键 AI 生成高清短视频，矩阵号运营，靠广告分成/带货/联盟营销变现。真正的"内容印钞机" | YouTube MCP(上传) + TikTok MCP(发布) + Affiliate MCP(变现) |
| 2 | **Citedy SEO Agent** — AI 内容工厂 | [Citedy/citedy-seo-agent](https://github.com/Citedy/citedy-seo-agent) | 趋势发现→竞品分析→SEO 文章生成(55语言)→AI 插图+配音→AI 虚拟人视频→多平台分发，全链路内容生产 | BlogBurst MCP(发布) + Google Search Console MCP(流量监控) |
| 3 | **Kwesi SEO Ladders Skill** — SEO 全自动化 | [Kwesi-dev/seo-ladders-skill](https://github.com/Kwesi-dev/seo-ladders-skill) | 网站审计→关键词匹配→生成 SEO 文章(含图/视频/FAQ/E-E-A-T/JSON-LD)→发布到 WordPress，SEO 赚钱全自动 | Google Search Console MCP + Clamp MCP(流量分析) |
| 4 | **BlogBurst MCP** — 一源多发 | [shensi8312/blogburst-mcp-server](https://github.com/shensi8312/blogburst-mcp-server) | 一篇内容→9+ 平台适配发布（Twitter/LinkedIn/Reddit/Bluesky/Threads/Telegram/Discord/TikTok/YouTube），内容触达最大化 | Citedy SEO Agent(生产) + SEO Analysis(优化) |
| 5 | **RoboSystems Content Machine** — 财经视频自动化 | [RoboFinSystems/robosystems-content-machine](https://github.com/RoboFinSystems/robosystems-content-machine) | SEC 文件→AI 研究→自动生成解说视频/播客/社交帖子（HeyGen+ElevenLabs+Shotstack），财经内容工厂 | Claude Cowork(研究) + 视频发布平台 API |
| 6 | **NotebookLM MCP** — Google AI 内容工具 | [roomi-fields/notebooklm-mcp](https://github.com/roomi-fields/notebooklm-mcp) | 引用支持的 Q&A、音频/视频/内容生成、多账户轮换。适合做深度内容（播客、研究文章） | RoboSystems MCP(视频化) + BlogBurst MCP(分发) |
| 7 | **ShortX** — AI 短视频自动化平台 | [RayVentura/shortx.ai](https://shortx.ai/) | YouTube Shorts/Reels/TikTok/Snapchat AI 视频自动化，含模板+联盟计划 | MoneyPrinterTurbo(素材生成) + 多平台发布 |
| 8 | **Instagram MCP Automation** — IG 全自动运营 | [abcnuts/instagram-mcp-automation](https://github.com/abcnuts/instagram-mcp-automation) | AI 内容生成+定时发布+分析+互动管理，Instagram 账号自动运营涨粉变现 | X-Grow MCP(Twitter) + BlogBurst MCP(跨平台) |
| 9 | **Sweeppea MCP** — 合规抽奖营销 | [Sweeppea-Development-Lab/sweeppea-mcp-info](https://github.com/Sweeppea-Development-Lab/sweeppea-mcp-info) | 70 工具管理美加合规抽奖活动，用抽奖快速涨粉/获客/变现 | 社交媒体 MCP(推广抽奖) + Mailchimp MCP(邮件跟进) |
| 10 | **Syndicate Links MCP** — AI 原生联盟营销 | [cmcgrabby-hue/syndicate-links](https://github.com/cmcgrabby-hue/syndicate-links) | AI Agent 自主发现联盟计划、追踪转化、自动结算佣金。AI 帮你做淘宝客/Amazon Affiliate | MoneyPrinterTurbo(视频带货) + Content Generation(文章带货) |

---

## 六、通用能力底座（组合必用） 🧰

| # | 名称 | 来源 | 如何帮你赚钱 | 建议 Skill 组合 |
|---|------|------|-------------|----------------|
| 1 | **Browser-Use / Playwright MCP** | [browser-use/browser-use](https://github.com/browser-use/browser-use) (70.7k⭐) / [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) (33k⭐) | AI 控制浏览器执行任意操作：自动填表、下单、爬数据、发内容。所有赚钱流程的基础设施 | 所有需要 Web 操作的 skill 都需要它 |
| 2 | **Firecrawl MCP** | [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) (60.7k⭐) | 任意网站→LLM 可读 Markdown/结构化数据，批量采集竞品/市场数据 | Scrapling MCP(反爬网站) + 数据分析 Agent |
| 3 | **Scrapling MCP** | [cyberchitta/scrapling-fetch-mcp](https://github.com/cyberchitta/scrapling-fetch-mcp) | 突破反爬保护的网页内容抓取，Firecrawl 抓不到的交给它 | Firecrawl MCP + Browser-Use |
| 4 | **AgentQL MCP** | [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) | 自然语言描述要提取的数据，自动从网页提取结构化数据 | Firecrawl MCP + 数据分析 Pipeline |
| 5 | **Activepieces** | [activepieces/activepieces](https://github.com/activepieces/activepieces) (22.4k⭐) | ~400 MCP Servers 的工作流自动化平台，把所有赚钱 skill 串联成全自动 Pipeline | 所有上述 skill 的编排引擎 |
| 6 | **n8n** | [n8n-io/n8n](https://github.com/n8n-io/n8n) (143.7k⭐) | 可视化工作流+400+集成+原生 AI，构建全自动商业流程 | Activepieces 替代方案，二选一 |
| 7 | **Dify** | [langgenius/dify](https://github.com/langgenius/dify) (115.6k⭐) | 生产级 AI 工作流平台，低代码构建 Agent 流程，内置 RAG 和工具调用 | 所有 MCP 的编排和部署平台 |
| 8 | **Google Search Console MCP** | [acamolese/google-search-console-mcp](https://github.com/acamolese/google-search-console-mcp) | SEO 性能数据、URL 检查、索引状态、HTML SEO 审计报告，免费流量监控必备 | Citedy SEO Agent + Kwesi SEO Skill |
| 9 | **Clamp MCP** — 网页分析 | [clamp-sh/mcp](https://github.com/clamp-sh/mcp) | AI 原生网页分析：页面浏览量、Top 页面、来源、国家、设备、转化漏斗、告警 | Google Search Console MCP + SEO 工具链 |
| 10 | **ChatGPT-on-WeChat** | [zhayujie/chatgpt-on-wechat](https://github.com/zhayujie/chatgpt-on-wechat) (39.2k⭐) | 微信生态的 AI 助手，可做客服、营销、变现。中国特色流量入口 | 微信公众号+小程序电商+微信支付 |

---

## 七、推荐「赚钱技能组合」🔥

### 🥇 组合 A：Dropshipping 全自动流水线
```
BuyWhere MCP (跨境选品+比价)
→ Intelligence API (利润分析+FBA估算)
→ DSers MCP (一键铺货到 Shopify)
→ Cerebrochain MCP (物流管理)
→ Amazon Seller Central MCP (多平台管理)
→ Meta Ads MCP + Google Ads MCP (自动投放获客)
→ Xendit MCP (收款)
```
**预计月收入潜力**：选品对了 3 个月内月利润 ¥1-3 万可期

### 🥈 组合 B：内容矩阵自动变现
```
Citedy SEO Agent (趋势发现+SEO文章+视频生成)
→ BlogBurst MCP (9平台分发)
→ MoneyPrinterTurbo (短视频批量生产)
→ X-Grow MCP (Twitter/X优化)
→ Syndicate Links MCP (自动联盟营销变现)
→ Google Search Console MCP + Clamp MCP (流量监控)
```
**预计月收入潜力**：3-6 个月内容矩阵成型，广告分成+联盟佣金月入 ¥1-5 万

### 🥉 组合 C：B2B 销售 AI 代理
```
Apollo.io MCP (找 2.75 亿 B2B 线索)
→ Tomba MCP (邮箱验证)
→ Gorilla MCP (社交媒体痛点发现)
→ Mailchimp MCP + DeliverIQ MCP (邮件自动化+送达率优化)
→ Salesforce Marketing MCP (CRM+转化追踪)
→ Frihet MCP (发票+收款管理)
```
**预计月收入潜力**：代运营/自己做销售，单客户¥5,000-20,000 月费

### 🏅 组合 D：SEO 代运营赚钱
```
LocalSEOData MCP (本地SEO全套)
→ Google Search Console MCP (SEO监控)
→ Kwesi SEO Ladders Skill (内容全自动)
→ AI Visibility MCP (AI搜索可见度)
→ Competlab MCP (竞品监控)
→ Clamp MCP (流量分析)
```
**预计月收入潜力**：每个客户 ¥2,000-10,000/月，同时服务 5-10 个客户

---

## 八、重点开源项目速览（MakeMoneyWithAI 列表）

| 项目 | Stars | 一句话赚钱方式 |
|------|-------|---------------|
| **AutoGPT** | 178.8k | 自主 Agent 框架，做 SaaS/自动化服务 |
| **n8n** | 143.7k | 400+集成的工作流自动化，卖自动化方案 |
| **Dify** | 115.6k | 低代码 AI Agent 平台，做企业 AI 解决方案 |
| **Browser-Use** | 70.7k | AI 浏览器自动化，做 RPA/数据采集服务 |
| **Firecrawl** | 60.7k | 网页转结构化数据，做数据服务 |
| **MoneyPrinterTurbo** | 44.0k | AI 短视频批量生成，做内容矩阵 |
| **TrendRadar** | 44.3k | 实时趋势监控+AI 摘要，做信息差套利 |
| **CrewAI** | 38.7k | 多 Agent 协作框架，做复杂自动化服务 |
| **ChatGPT-on-WeChat** | 39.2k | 微信 AI 助手，做私域变现 |
| **ScrapeGraphAI** | 21.4k | AI 驱动的网页抓取，做数据产品 |

---

## 总结

以上共整理 **60+** 个与赚钱直接相关的 MCP Server / AI Agent Skill / 开源工具。所有工具都具备以下特征：

1. ✅ AI Agent 可直接调用（MCP 协议或 API）
2. ✅ 可组合成自动化赚钱流水线（不是单步提效工具）
3. ✅ 覆盖获客→选品→上架→销售→内容→收款的完整变现链路
4. ✅ 低成本启动（大部分有免费 tier，核心成本是 AI API 调用费）

**下一步建议**：选择一个组合方向（推荐从 Dropshipping 或内容矩阵起步），逐个安装验证 MCP Server，搭建自动化 Pipeline。先跑通最小闭环再规模化。

> ⚠️ 注意：部分 MCP Server 采用 x402 协议按调用付费（USDC），使用前确认成本。部分涉及平台 API 的需要申请对应开发者账号和 API Key。
