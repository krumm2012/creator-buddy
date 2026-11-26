# Creator Buddy

创作者全域内容搜索总控 Skill。输入平台名 + 关键词、平台链接，或提出分析博主、文章风格、热度、点赞收藏评论、爆款原因、选题方向等需求时触发，按平台与任务自动路由到对应的分支能力完成搜索、分析与报告生成。

## 适用场景

- 平台名 + 关键词：`小红书 Codex`、`B站 AI编程`、`公众号 Agent`、`抖音 剪辑Agent`
- 平台链接：小红书笔记/主页、B站视频/空间、公众号文章、抖音视频/主页
- 内容分析：分析这个博主、看文章风格、查热度、看点赞收藏评论、找爆款原因
- 运营分析：帮我找选题、拆标题、看竞品、找近期热门内容、比较不同平台

## 目录结构

```
.
├── SKILL.md              # 主入口：输入识别、路由分发、输出规范
└── references/
    ├── xhs-guide.md      # 小红书检索与分析指引
    ├── gzh-guide.md      # 公众号检索与分析指引
    └── video-guide.md    # B站/抖音视频检索与分析指引
```

## 路由的分支能力

- `xhs-hotnotes`：小红书热门笔记搜索
- `global-content-search`：全域内容搜索（小红书 / B站 / 抖音）
- `gzh-explosive-content-detector`：公众号爆款内容检索
- `baokuan-article-analysis`：公众号爆款文章数据分析

## 安装

把本仓库目录放入 skills 目录即可，例如：

```bash
git clone https://github.com/krumm2012/creator-buddy.git ~/.openclaw/workspace-task/skills/creator-buddy
```

## License

MIT
