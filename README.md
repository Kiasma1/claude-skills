# Claude Code Skills Collection

我的 Claude Code 全局技能集合，包含英文和中文技能包。

## 技能来源

### Matt Pocock Skills (英文)
**来源：** https://github.com/mattpocock/claude-code-skills

- ask-matt - 技能导航和工作流指南
- codebase-design - 深层模块设计
- diagnosing-bugs - 系统化 bug 诊断
- domain-modeling - 领域模型构建
- grilling 系列 - 压力测试设计和计划
- tdd - 测试驱动开发
- 等等...

### Superpowers-ZH (中文)
**来源：** https://github.com/jnMetaCode/superpowers-zh

安装方式：
```bash
npx superpowers-zh --tool claude
```

包含技能：
- brainstorming - 头脑风暴
- chinese-* 系列 - 中文环境相关（代码审查、文档排版、Git 工作流等）
- test-driven-development - 测试驱动开发
- systematic-debugging - 系统性调试
- subagent-driven-development - 子代理驱动开发
- requesting-code-review - 请求代码审查
- 等等...

### Andrej Karpathy Skills
**来源：** https://github.com/forrestchang/andrej-karpathy-skills

- karpathy-guidelines - 减少 LLM 编码错误的行为准则

## 安装

将此仓库克隆到 Claude Code 的全局 skills 目录：

```bash
# Windows
git clone <repo-url> C:\Users\<username>\.claude\skills

# macOS/Linux
git clone <repo-url> ~/.claude/skills
```

## 使用

在 Claude Code 中，使用 `/skill-name` 调用对应的技能。例如：

- `/brainstorming` - 开始头脑风暴
- `/test-driven-development` - 启动 TDD 流程
- `/requesting-code-review` - 请求代码审查
- `/karpathy-guidelines` - 应用编码准则

## 更新

```bash
cd ~/.claude/skills  # 或 Windows 路径
git pull
```

## 许可

各技能包遵循其原始许可证。
