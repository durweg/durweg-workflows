[English](README.md) · [中文](README_cn.md)

# Durweg 工作流

**[Durweg](https://github.com/durweg/durweg) 工作流的公开目录：别人做好的工作方法，按名字安装，用你的 AI agent 运行。**

## 🧭 装一个

装好 Durweg 以后，对 agent 说“给我看看能装哪些 durweg 工作流”，或者运行：

1. `durweg library available`，看这份目录；
2. `durweg library add <名字>`（例如 `durweg library add human-readme`）；
3. 对 agent 说：“用 durweg 运行 <名字>。”

## 📚 工作流

| 名字 | 做什么 | 仓库 |
| :--- | :--- | :--- |
| `write-your-method` | 随 Durweg 一起装好，不用另装：把你自己的做事方法写成一个工作流。对 agent 说：“用 durweg 运行 write-your-method。” | [durweg/durweg](https://github.com/durweg/durweg/blob/main/README_cn.md) |
| `human-readme` | 让 AI agent 按 7 个固定步骤写项目的 README，写给第一次来的读者 | [durweg/durweg-human-readme](https://github.com/durweg/durweg-human-readme) |
| `name-project` | 给项目起名字：核心价值、空白地带、候选名、查重、一次决定 | [musetee/name-project](https://github.com/musetee/name-project) |
| `stepaper` | AI agent 陪你一步一步读论文，每一步都可以质疑，最后做出组会 PPT | [durweg/durweg-stepaper](https://github.com/durweg/durweg-stepaper) |
| `todo-daily` | 每天早上，AI agent 收集各个 agent 等你处理的事，给你看 Todoist 里交给 AI 的队列，帮你选出今天最多 3 件事。属于 [durweg-todo](https://github.com/durweg/durweg-todo)，完整安装见那里。 | [durweg/durweg-todo-daily](https://github.com/durweg/durweg-todo-daily) |
| `todo-weekly` | 每周一次，AI agent 陪你过一遍 Todoist：各个 agent 等你处理的事、交给 AI 的队列、过期和很久没动的待办、下周重点。属于 [durweg-todo](https://github.com/durweg/durweg-todo)。 | [durweg/durweg-todo-weekly](https://github.com/durweg/durweg-todo-weekly) |

## 🙋 加上你的

把你的工作流发布成一个带 LICENSE 的公开仓库，Durweg 问要不要申请加进公开目录时说要（[发布](https://github.com/durweg/durweg/blob/main/docs/publish_cn.md)）。这会在这里开一个 pull request。检查会确认仓库公开、有 README 和 LICENSE、`workflow.json` 有效；所有者合并后就列出来。
