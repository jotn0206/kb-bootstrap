# kb-bootstrap · 知识库一键搭建器

一个让 AI（WorkBuddy / opencode 等任意客户端）**引导式**帮你从零搭好「私人知识库 + 公众号运营」双引擎的技能。

> 不靠堆配置，靠一条 Master 提示词驱动 P0–P5 全流程：环境检查 → 信息采集 → 骨架生成 → 指令测试 → 五工作流验证 → 验收交付。

## 它解决什么

- **零基础也能建库**：不懂 Obsidian、不懂双链，照着引导问答 10 项就能定身量
- **杜绝"通用模板"**：P1 强制采集你的真实身份/行业/脱敏红线，禁用词库是"职业定制版"而非万能套话
- **飞轮闭环**：采集 → `/ingest` 入库 → `/newpost` 取料 → 成稿 → 评分/发布 → 沉淀回 wiki → `/lint` 体检，自动复利

## 安装

```bash
git clone https://github.com/jotn0206/kb-bootstrap.git ~/.workbuddy/skills/kb-bootstrap
```

或在 WorkBuddy 对话框直接说「一键生成知识库」（需已安装本技能）。

详细安装与配置见 **[README-安装.md](./README-安装.md)**。

## 目录结构（本仓库）

```
kb-bootstrap/
├── SKILL.md            # 技能主体：P0–P5 全流程 + 铁律 + 故障速查
├── README.md           # 本文件
└── README-安装.md      # 安装、依赖、配图路线 A/B、常见问题
```

## 依赖（P4 工作流前置）

技能运行时会引导安装：`humanizer-zh`、`ian-xiaohei-illustrations`、`wechat-publish-template`、`baoyu-post-to-wechat`、`wechat-article-search`、`opencli`、`knowledge-base-dual-engine`。

## 许可

MIT —— 可自由使用、修改、再分发。
