# 活人感写作

`human-writing` 是一套通用中文创作与改稿 Skill，当前版本为 1.0.0。

它适合知乎回答、论坛长帖、公众号文章、博客、评论、人物故事、历史叙事、新闻与行业解读、科普、教程、评测、个人叙事、小说、故事、对白、口播和演讲稿。

这套 Skill 想解决的事情很具体。长文不能靠重复同一个意思凑篇幅，现实写作不能用想象补事实，虚构创作也不能只换景色而没有事情发生。成稿要像一个知道自己在说什么的人写出来的中文，不像报告、广告或模型生成的标准答案。

## 核心做法

- 现实写作先查材料够不够。事实、数字、引语和亲历要能说明来路。
- 虚构写作允许创造人物、场景、对白和情节，同时检查人物目标、行动、因果与前后关系。
- 每个新段落都要带来新事实、新动作、新例子、新区别或新后果。
- 白话打底，重视词序、停顿、照应和分寸。动作已经说清的感情，不再追着解释。
- 成稿清除冒号、破折号、翻案句、商业黑话和常见模型腔。
- 初稿完成后再审稿，检查脚本只执行已经写明的硬规则，不替作者决定文体。

## 安装

最省事的方式是打开 [Releases](https://github.com/KKKKhazix/human-writing/releases/latest)，下载 `活人感写作.skill`，再交给支持 Skill 的应用安装。

也可以把仓库里的 `human-writing` 文件夹完整复制到本机的 Skills 目录。目录名必须保留为 `human-writing`。

```text
~/.agents/skills/human-writing/
```

安装后可以这样调用。

```text
使用 $human-writing，把我的材料写成一篇有活人感和中文韵律的作品。
```

## 仓库结构

| 位置 | 用途 |
| --- | --- |
| `human-writing/SKILL.md` | 入口、材料门槛、现实与虚构分流、写作流程和交付禁令 |
| `human-writing/references/forum-prose.md` | 知乎回答、论坛长帖、公众号文章和其他长篇散文写法 |
| `human-writing/references/reality.md` | 真人、历史、新闻、数据、评测、教程和个人经历的事实边界 |
| `human-writing/references/fiction.md` | 小说、故事、虚构散文、对白和剧本的创作规则 |
| `human-writing/references/formats.md` | 短内容、口播、演讲、教程、评测、对白和诗歌等形式规则 |
| `human-writing/references/revision.md` | 初稿完成后的删改、节奏、词语和事实检查 |
| `human-writing/scripts/check_prose.py` | 检查成稿是否命中明确禁用项 |

## 使用边界

这是一套创作规则与工作流程，不是训练数据，也不附带模型。仓库不包含第三方文章全文、训练语料或模型权重。

## 许可证

[MIT License](LICENSE)
