[English](README.md) · [中文](README_cn.md)

# Durweg workflows

**The public list of [Durweg](https://github.com/durweg/durweg) workflows: ready-made ways of
working that you install by name and run with your AI agent.**

## 🧭 Install one

With Durweg installed, tell your agent "Show me the durweg workflows I can install", or run:

1. `durweg library available` to see this list;
2. `durweg library add <name>` (for example `durweg library add human-readme`);
3. tell your agent: "Run <name> with durweg."

## 📚 The workflows

| Name | What it does | Repository |
| :--- | :--- | :--- |
| `write-your-method` | Comes with Durweg, nothing to install: write down your own way of working as a workflow. Tell your agent: "Run write-your-method with durweg." | [durweg/durweg](https://github.com/durweg/durweg/blob/main/docs/example.md) |
| `human-readme` | AI agents write a project's README in 7 fixed steps, for a first-time reader | [durweg/durweg-human-readme](https://github.com/durweg/durweg-human-readme) |
| `name-project` | Find a name for a project: core value, white space, candidates, a collision check, one decision | [musetee/name-project](https://github.com/musetee/name-project) |
| `stepaper` | An AI agent reads a research paper with you one step at a time, lets you question every step, then builds the group-meeting slides | [durweg/durweg-stepaper](https://github.com/durweg/durweg-stepaper) |

To let your AI agents work through your requests on their own, install the plugin [durweg-todo](https://github.com/durweg/durweg-todo): requests become cards on an AI Board of your own (a private GitHub Project), agents take them one after another, a second agent reviews each, and only what needs you (decide, do something, accept a result) waits there for you. It brings its own workflows: todo-kanban (the coordinator that hands out the cards), todo-daily and todo-weekly (your daily and weekly review) and todo-issues (GitHub issues onto the board). It is a plugin with several workflows and the `ai-board` command, so it is not an entry in this catalog; install it as its README says.

## 🙋 Add yours

Publish your workflow as a public repository with a LICENSE and say yes when Durweg asks whether
to propose it to the public catalog ([publishing](https://github.com/durweg/durweg/blob/main/docs/publish.md)).
That opens a pull request here. A check makes sure the repository is public, has a README and a
LICENSE and a valid `workflow.json`; the entry is listed once the owner merges it.
