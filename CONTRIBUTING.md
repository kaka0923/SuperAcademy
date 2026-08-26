# 贡献指南

感谢您对超能学院的兴趣！我们欢迎任何形式的贡献。

---

## 如何贡献

### 1. 报告 Bug

- 使用 [Issue Template](./.github/ISSUE_TEMPLATE/bug_report.md) 报告 Bug
- 描述清楚问题现象和预期行为
- 提供复现步骤和系统环境信息

### 2. 提议新功能

- 使用 [Issue Template](./.github/ISSUE_TEMPLATE/feature_request.md) 提议新功能
- 详细描述功能需求和使用场景
- 解释为什么这个功能对项目有价值

### 3. 提交代码

#### 开发环境搭建

```bash
# 克隆仓库
git clone https://github.com/your-repo/super-academy.git
cd super-academy

# 创建分支
git checkout -b feature/your-feature-name

# 安装依赖
pip install -r requirements.txt

# 运行测试
python -m pytest
```

#### 代码规范

- 使用 **Python 3.14+**
- 遵循 PEP 8 代码风格
- 变量和函数命名使用英文，注释使用中文
- 所有新增功能必须包含测试

#### 提交 PR

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交你的更改 (`git commit -m 'Add some amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 创建 Pull Request

#### PR 模板

```markdown
## 描述
请简要描述此 PR 的内容和目的。

## 解决的问题
此 PR 解决了哪些问题？（如有）

## 类型
- [ ] Bug 修复
- [ ] 新功能
- [ ] 文档更新
- [ ] 代码重构

## 检查清单
- [ ] 我的代码遵循项目的代码规范
- [ ] 我已经进行了自我审查
- [ ] 我已经添加了必要的测试
- [ ] 所有测试都通过了
```

---

## 开发指南

### 项目结构

```
超能学院/
├── prompts/              # Agent Prompt 文件
├── 课程大纲/            # 课程大纲输出
├── 教案/                # 教案输出
├── PPT/                 # PPT 输出
├── knowledge/           # 知识库
├── docs/                # 文档
└── main.py              # 入口文件
```

### 添加新的 Agent 角色

1. 在 `/prompts/` 目录创建新的 Prompt 文件
2. 更新 `超能学院Agent系统说明.md`
3. 添加对应的检查标准到教务人员 Prompt

---

## 问题解答

**Q: 开发环境需要什么？**
A: Python 3.14+，推荐使用虚拟环境。

**Q: 如何运行测试？**
A: `python -m pytest`

**Q: 代码审查需要多长时间？**
A: 通常 1-3 个工作日内会回复。

---

## 社区

- 💬 [GitHub Discussions](https://github.com/your-repo/super-academy/discussions)
- 📧 邮箱：support@super-academy.example.com

---

再次感谢您的贡献！ 🎉
