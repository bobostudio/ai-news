# 🤖 AI News Daily

AI 资讯自动收集仓库，由 AI 信息雷达维护。

## 📁 目录结构

```
ai-news/
├── README.md
├── template.md           # 报告模板
└── 2026-02-25/          # 按日期分类
    ├── openai-093022.md
    └── claude-103045.md
```

## 📝 报告格式

每份报告包含：
- 搜索主题和关键词
- 信息来源（X/YouTube/Reddit/Web）
- 重要性分级（🔥重要 / 📰其他）
- 趋势观察

## 🤖 自动化流程

1. **研究员 Agent** 接收搜索任务
2. 从多平台搜集资讯
3. 生成结构化报告
4. 保存到 `ai-news/YYYY-MM-DD/`
5. 通知主 Agent 推送到 GitHub

---

*Maintained by AI 信息雷达 | bobostudio*
