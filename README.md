# 可售卖经验定位 Skill

这是一个符合 Agent Skills 格式的 AI 小助手，用来帮助用户从自己的经历、能力、成果和外部反馈里，找到一个值得验证的知识产品方向。

适用场景：

- 想做课，但不知道做什么
- 想做知识产品，但不知道自己有什么经验可以卖
- 想做副业、转型、自由职业，但还没有清晰方向
- 想把服务、内容、生活经验、职业经验整理成低交付压力产品

## Codex 安装

对 Codex 说：

```text
请帮我安装这个 Skill：
https://github.com/wuhuili2014/sellable-experience-skill/tree/main/sellable-experience-skill
```

安装后重启 Codex。

## Claude Code 安装

把 `sellable-experience-skill` 文件夹放到：

```text
~/.claude/skills/sellable-experience-skill/SKILL.md
```

也可以放到项目内：

```text
.claude/skills/sellable-experience-skill/SKILL.md
```

## Claude 网页版

把 `sellable-experience-skill` 文件夹打包成 ZIP，然后在 Claude 的 Customize > Skills 里上传并启用。

## WorkBuddy

如果你的 WorkBuddy 版本支持 Skills，可以尝试把文件夹放到：

```text
~/.workbuddy/skills/sellable-experience-skill/SKILL.md
```

或项目内：

```text
.workbuddy/skills/sellable-experience-skill/SKILL.md
```

如果 WorkBuddy 支持从 GitHub 安装 Skill，也可以直接使用本仓库链接。

## 无需安装：复制即用提示词版

如果你不用 Codex、Claude Code 或其他支持 Skills 的 Agent，可以直接打开：

[复制即用提示词版.md](复制即用提示词版.md)

把里面的完整提示词复制到 ChatGPT、Claude、豆包、Kimi、通义等 AI 对话框里使用。

## 启动方式

安装后可以这样说：

```text
用可售卖经验定位 Skill 帮我找到一个适合做成知识产品的方向。
```

或：

```text
我想做知识产品，但不知道自己有什么经验可以卖，你一步步问我。
```
