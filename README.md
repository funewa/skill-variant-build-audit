# skill-variant-build-audit

> WorkBuddy Skill — `skill-variant-build-audit`

## 简介

审计并修复「同一母版 + N 个变体马甲」型 Skill 集合的合规问题，并在 Windows + 宿主安全钩子环境下可靠重建 dist 与升版发布。覆盖：专属包「声明窄、内容宽」（ClawHub T01 指令劫持）、只修声明层后换编号复发的 T05 越权/Description-Behavior Mismatch/Intent-Code Divergence、构建期用 AST 裁剪包内 CLI 的能力层收窄 + 运行期命令白名单闸、全功能马甲包「少声明」、allowed-tools 最小权限（

## 安装

```bash
git clone https://github.com/funewa/skill-variant-build-audit.git
cp -r skill-variant-build-audit ~/.workbuddy/skills/skill-variant-build-audit
```

## 使用

在 WorkBuddy 中直接描述你的需求，Agent 会依据 `SKILL.md` 的 `description` 自动匹配本技能。详见 `SKILL.md`。

## 目录结构

```
├── SKILL.md      # 技能定义（frontmatter + 说明）
└── README.md
```

---

Published from the `user`-level WorkBuddy skill library.
