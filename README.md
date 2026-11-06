# find-skills-cn

GitHub 搜索助手：根据中文或英文需求查找 GitHub 上的项目、Agent Skill、MCP、提示词库及其他资源。历史名称和调用名 `find-skills-cn` 保持不变。

只搜索 GitHub，Agent 根据任务自主选择 GitHub 的搜索方式、资源类型和核验深度。结果先按需求匹配度排序，匹配程度相近时参考 GitHub 可查到的 star 或下载量。通常最多展示 6 条；确认还有符合条件的结果时会说明。

每条结果依次展示名称与 GitHub 链接、介绍和匹配说明、可查到的 GitHub 数据。搜索受限时会说明；只搜索和输出，不安装或执行候选项目。

## 文件

- `SKILL.md` — 主要说明与输出格式
- `references/search.md` — 搜索范围和指标参考
- `agents/openai.yaml` — Codex 接口配置

## 安装

- **Claude Code**：复制整个目录到 `~/.claude/skills/find-skills-cn/`
- **Codex**：复制整个目录到 `~/.codex/skills/find-skills-cn/`
- **其他 agent**：需要时复制一份到对应 skills 目录即可

## 许可

MIT License
