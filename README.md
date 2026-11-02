# Skills

我为自己实现的 AI Agent Skills，按 [Agent Skills 规范](https://agentskills.io)（SKILL.md）组织。

每个子目录一个 skill，`SKILL.md` 为入口。

## 目录

| Skill | 说明 |
|---|---|
| [source-code-walkthrough](source-code-walkthrough/) | 源码走读导师：贴真实源码逐行讲解，参数逐个解释，语法就地补课 |

## 安装到本机

```bash
# 备份已有 skills 目录后
git clone git@github.com:SteveY4ng/skills.git ~/.agents/skills
# 或只同步单个 skill
git clone git@github.com:SteveY4ng/skills.git /tmp/skills
cp -r /tmp/skills/source-code-walkthrough ~/.agents/skills/
```

第三方 skill（如 skill-creator）不入库，见 `.gitignore`。
