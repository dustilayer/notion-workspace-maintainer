# Notion Workspace Maintainer

用于维护 Notion 页面、关联数据库视图、个人待办和课程日历的 Agent Skill。

适用示例：

- 把任务表直接嵌入主页，并与原数据库同步编辑。
- 让每日事项动态显示当天个人任务，课程保留在课程日历。
- 保留原有筛选条件的同时增加新条件。
- 根据确认的选课和课表导入日程，避免重复。

## 使用

将本目录放入 Codex 的技能目录，例如 `~/.codex/skills/notion-workspace-maintainer`，然后在新的会话中调用：

```text
使用 $notion-workspace-maintainer，把我的每日事项改成只显示当天个人任务。
```

需要可用的 Notion 连接器，或已登录 Notion 的浏览器操作工具。某些视图选项需要通过浏览器设置；本 Skill 本身不提供账户访问权限。

## 隐私

此发布包仅包含通用操作规则，没有真实页面链接、数据库 ID、个人待办、课程安排、账户凭据或本机路径。工作区信息应在使用时通过已授权连接读取。

页面设计能力：布局、视图选择、关系汇总与公式边界检查。设计思路参考 https://github.com/Anusara14/notion-pages-skill ，说明为独立编写，详见 references/page-design.md。
