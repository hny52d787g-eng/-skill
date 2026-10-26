# NovelForge Skill

结构化 AI 小说创作工作流 Skill。

## 安装到 DeepSeek Harness（用户级）

```bash
git clone https://github.com/<你的用户名>/novelforge-skill.git
mkdir -p ~/.dsh/skills
cp -R novelforge-skill/skills/novelforge ~/.dsh/skills/
```

安装后路径应为 `~/.dsh/skills/novelforge/SKILL.md`，通常无需重启 Harness。

## 目录结构

- `skills/novelforge/SKILL.md`：入口指令
- `skills/novelforge/references/`：按需加载的模块、模板和质量检查表