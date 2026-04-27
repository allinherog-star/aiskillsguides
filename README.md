> 官网站点：[ai-skills.ai](https://ai-skills.ai/)
>
> AI Skills 官网是整个技能库的统一入口，可以按技能、职业、行业和应用场景查找内容，也能直接进入具体 Skill 的介绍与使用页面。本仓库是 AI Skills 的 guides 内容源，下面先用一组移动端截图快速看一下站点形态。

<p align="center">
  <picture><img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/mobile/%E9%A6%96%E9%A1%B5mobile.jpg" alt="AI Skills 官网首页（Mobile）" width="15%" /></picture>
  <picture><img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/mobile/%E6%8A%80%E8%83%BD%E5%88%97%E8%A1%A8mobile.jpg" alt="AI Skills 技能列表页（Mobile）" width="15%" /></picture>
  <picture><img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/mobile/%E5%B9%B3%E5%8F%B0%E6%B5%81%E9%87%8F.png" alt="AI Skills 平台流量页（Mobile）" width="15%" /></picture>
  <picture><img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/mobile/%E4%B8%8A%E5%8D%87%E7%83%AD%E7%82%B9mobile.png" alt="AI Skills 上升热点页（Mobile）" width="15%" /></picture>
  <picture><img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/mobile/%E6%89%BE%E5%AF%B9%E6%A0%87%E8%B4%A6%E5%8F%B7mobile2.jpg" alt="AI Skills 找对标账号页（Mobile）" width="15%" /></picture>
  <picture><img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/mobile/%E8%A7%86%E9%A2%91%E8%BF%90%E8%90%A5%E5%88%86%E6%9E%90.jpg" alt="AI Skills 视频运营分析页（Mobile）" width="15%" /></picture>
</p>

<p align="center"><sub>官网首页 · 技能列表 · 平台流量 · 上升热点 · 找对标账号 · 视频运营分析</sub></p>

# AI Skills Guides：为 AI Skills 场景内容提供写作源

> 大多数人用 AI 还停在「问一句答一句」。AI Skills（[ai-skills.ai](https://ai-skills.ai/)）想换一种姿势：把 AI 能力拆成一条条能直接执行的 Skill，像查字典一样调出来用。`aiskillsguides` 负责沉淀这些 Skill 背后的应用场景文章、配图和发布 meta，让站点内容可以持续更新。

<picture>
  <img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/content-01.webp" alt="AI Skills 官网场景导览图" />
</picture>

## AI Skills 是什么：一个能直接查的技能库

AI Skills 是一个面向各行各业的 AI 技能库。站点首屏给的定义很直接：「为你的职业发展、行业竞争力，增加更多可能。」

翻译成人话：这里不放论文、不讲 PPT，只放**能让你明天就用上的 AI 技能**。每个 Skill 都有三个固定栏目：

- **核心价值**——用一句话讲清楚这个技能解决什么问题
- **主要用途**——列出它最常被用来干什么
- **使用技能**——一个按钮，点进去就能跑

举首屏的例子：抖音赛道的创作者想知道「平台流量在哪」，对应的 Skill 叫「抖音流量分配大盘」，打开就是实时更新的大盘图和方向占比，不用自己再搭监测脚本。另外两个同系列 Skill 是「抖音全网实时热点」和「抖音上升热点选题助手」——一个告诉你全网最热的是什么，一个帮你把热点拆成可拍的选题。

## Skill 不是 Prompt：中间差了一整套流程

<picture>
  <img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/content-02.webp" alt="content-02" />
</picture>

很多人第一次看到「AI 技能库」，以为就是 Prompt 合集。这是个常见误会。

Prompt 是一句话，Skill 是一个**能被执行的流程**：它至少包含触发条件、上下文收集、工具调用、输出约束和适用边界。同一个关键词，Prompt 给你一段文本，Skill 给你一份能交付的结果。

这也解释了为什么 AI Skills 上的每个条目都挂着「使用技能」入口——背后接的是已经调通的 Agent 工作流，不是一段需要自己再 debug 的 prompt 模板。这件事意味着两点：

1. **边际质量稳定**：不会因为你 prompt 写得不够好就翻车
2. **可被二次集成**：同一个 Skill 能被放进不同的客户端（网页、Agent、企业系统）

对多数非 AI 岗位来说，这一层封装非常关键——没人愿意花一个下午去调一句 prompt。

## 四个主入口：技能列表 / 职业 / 行业 / 应用场景

<picture>
  <img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/content-03.webp" alt="content-03" />
</picture>

站点顶部导航给了四条主线，对应四种找技能的姿势：

| 入口 | 怎么查 | 适合谁 |
| --- | --- | --- |
| **正在被大量使用的 Skills** | 按热度排序，看别人已经在用什么 | 不确定从哪开始的新用户 |
| **职业 AI 路径** | 按岗位/职业切入，找匹配本职工作的技能 | 个人职业成长场景 |
| **行业 AI 路径** | 按行业切入，找行业专属的垂直技能 | 行业一线岗位、企业采购方 |
| **Skills 应用场景** | 按「要解决的问题」反查 | 已有明确问题的资深用户 |

这种「四象限导航」的好处是**任何一种姿势都能收敛到同一个 Skill 页**——不会因为你不知道自己属于哪个职业就找不到。对企业客户，还有一个「企业服务」入口对接定制化需求。

## 怎么接入：三种典型用法

<picture>
  <img src="https://raw.githubusercontent.com/allinherog-star/aiskillsguides/HEAD/guides/images/ai-skills-site-readme/content-04.webp" alt="content-04" />
</picture>

目前有三种推荐姿势：

1. **直接在站点用**：打开 [ai-skills.ai](https://ai-skills.ai/)，顶部搜索框输关键词（比如「抖音热点」「SEO 审计」「竞品分析」），点「使用技能」即可。这是 0 门槛上手的方式。
2. **放进自己的 Agent**：如果你在用 Claude Code / Cursor / 自建 Agent 框架，多数 Skill 都支持按 `SKILL.md` 结构被挂载——把 Skill 路径加进 agent 配置，就能作为一条可被调用的流程使用。
3. **企业对接**：对有批量化、定制化需求的公司，站点页脚有「企业服务」与企微咨询入口，支持按行业/岗位做私有化部署。

三种姿势本质上是**同一个 Skill 库的三种触达方式**——底下跑的是同一套执行流程，只是包装不同。

## 本仓库内容

`aiskillsguides` 是 AI Skills 的 guides 写作仓，专门存放文章源码、配图和发布所需 meta。

### 目录约定

- `guides/*.md`：文章源码
- `guides/images/<slug>/`：每篇文章的封面、配图和步骤图
- `meta/<slug>-guide-frontmatter.json`：发布到站点前的 frontmatter 补充信息
- `meta/<slug>-image-plan.json`：图文生成阶段的出图计划
- `meta/<slug>-image-summary.json`：图文生成结果摘要
- `meta/<slug>-article-spec.json`：拼装文章时使用的结构化 spec

### 发布链路

1. 在本仓编写或更新 `guides/<slug>.md`
2. 将对应图片放入 `guides/images/<slug>/`
3. 在 `meta/` 下补齐发布所需 JSON
4. 从根仓运行 `.agents/skills/guide-release-sync/scripts/sync.py`
5. 同步结果写入 `ai-skills-web/content/guides/**` 与 `ai-skills-web/public/guides/<slug>/`

根仓中的 `guide-release-sync` skill 把本仓作为 guides 的唯一写作源。
