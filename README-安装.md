# kb-bootstrap 技能 · 安装说明

本文件夹是 `kb-bootstrap`（知识库一键搭建器）技能的**分发版**，配套「知识库双引擎工具包」使用。
把整个 `kb-bootstrap-skill` 文件夹放到你的技能目录即可启用。

## 安装方式（二选一）

### A. 用户级（推荐，所有项目都能用）
把文件夹放到 WorkBuddy 用户级技能目录：

```bash
cp -r kb-bootstrap-skill ~/.workbuddy/skills/kb-bootstrap
```

放好后目录应为：`~/.workbuddy/skills/kb-bootstrap/SKILL.md`

### B. 项目级（仅当前项目可用）
放到项目根目录下的 `.workbuddy/skills/`：

```bash
cp -r kb-bootstrap-skill <你的项目>/.workbuddy/skills/kb-bootstrap
```

## 验证启用
重启/刷新 WorkBuddy，在对话框发送：

```
一键生成知识库
```

（同义触发：搭建知识库 / 从零建库 / kb-setup）
AI 调起本技能即从 P0 环境检查跑到 P5 验收。

## 依赖技能（P4 阶段会自动引导安装，无需手动）
- `humanizer-zh`（去 AI 味）
- `ian-xiaohei-illustrations`（小黑手绘配图，WorkBuddy 用户级）
- `wechat-publish-template` / `baoyu-post-to-wechat`（公众号发布）
- `wechat-article-search`（公众号检索）
- `opencli`（多平台内容检索）
- `frontend-design`（代码驱动设计稿，opencode 路线）

## 说明
- 本技能**独立可用**：工具包配套的 `09-一键搭建提示词集 / 10-信息采集表 / 11-验收测试清单` 等文件，会在 P2 阶段由 AI 按你的身份自动生成；如需现成模板，可从完整工具包获取。
- **v1.1 起**，P2 还会生成 `15~21` 七份工作流执行清单（卡片模板 + 采集/调研/发布/PPT/创作 + 总纲），建库后日常照着跑即可。
- 与 `knowledge-base-dual-engine` 分工：本技能负责"从零建好并测通"，那个负责"日常录入/写稿/体检"。
