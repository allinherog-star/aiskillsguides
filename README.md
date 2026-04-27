# AI Skills Guides

`skills-guides` 是 AI Skills 的 guides 写作仓，专门存放文章源码、配图和发布所需 meta。

## 目录约定

- `guides/*.md`：文章源码
- `guides/images/<slug>/`：每篇文章的封面、配图和步骤图
- `meta/<slug>-guide-frontmatter.json`：发布到站点前的 frontmatter 补充信息
- `meta/<slug>-image-plan.json`：图文生成阶段的出图计划
- `meta/<slug>-image-summary.json`：图文生成结果摘要
- `meta/<slug>-article-spec.json`：拼装文章时使用的结构化 spec

## 发布链路

1. 在本仓编写或更新 `guides/<slug>.md`
2. 将对应图片放入 `guides/images/<slug>/`
3. 在 `meta/` 下补齐发布所需 JSON
4. 从根仓运行 `.agents/skills/guide-release-sync/scripts/sync.py`
5. 同步结果写入 `ai-skills-web/content/guides/**` 与 `ai-skills-web/public/guides/<slug>/`

根仓中的 `guide-release-sync` skill 把本仓作为 guides 的唯一写作源。
