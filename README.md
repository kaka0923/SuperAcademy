# Super Academy (超能学院)

<div align="center">

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-v1.0.0-green.svg)
![Python](https://img.shields.io/badge/python-3.14+-orange.svg)

**A teacher-oriented AI Agent system providing one-stop solutions for science and AI education courses**

[功能介绍](#功能介绍) • [快速开始](#快速开始) • [文档](#文档) • [贡献](#贡献) • [许可证](#许可证)

</div>

---

## 项目简介

**超能学院**是一个专为科学课程和人工智能教育设计的教师智能助手 Agent 系统。

只需输入课程主题和基本需求，即可一站式生成：
- 📚 课程大纲
- 📝 教案
- 📊 PPT 课件
- 🛠️ 教具清单
- 📋 课程互动设计
- 📝 课上作业
- ⭐ 课程评价

---

## 功能介绍

### 🤖 多角色协同

超能学院采用四个专业角色协同工作：

| 角色 | 职责 |
|------|------|
| 🧑‍🏫 **教研员** | 根据需求生成课程大纲 |
| 👨‍🏫 **主讲老师** | 根据大纲生成每节课的详细教案 |
| 👩‍🏫 **助教** | 根据教案生成PPT及配套教学材料 |
| 👨‍💼 **教务人员** | 全流程审核、进度管理、质量把控 |

### 📏 灵活课程方案

根据教学场景和学生情况，生成不同课时长度的课程：

- **DEMO** - 1节课体验
- **短期课程** - 4-8节课
- **标准课程** - 16节课
- **完整课程** - 32节课
- **自定义** - 按需定制

### ✅ 质量保障

- 教务人员逐级审核，不合格产品不输出
- 严格遵循国家课标要求
- 支持主流教学法（BOPPPS、5E、传统讲授等）

---

## 快速开始

### 环境要求

- Python 3.14+
- Windows / macOS / Linux

### 安装

```bash
# 克隆仓库
git clone https://github.com/your-repo/super-academy.git
cd super-academy

# 安装依赖
pip install -r requirements.txt
```

### 使用

```bash
# 启动超能学院
python main.py
```

然后在浏览器中打开 http://localhost:3080 开始使用。

---

## 系统架构

```
┌─────────────────────────────────────────────────────────────┐
│                      👨‍💼 教务人员                           │
│                   (审核 / 进度 / 存档)                      │
└─────────────────────────────────────────────────────────────┘
                              │
    ┌─────────────────────────┼─────────────────────────┐
    ▼                         ▼                         ▼
┌─────────────┐         ┌─────────────┐         ┌─────────────┐
│  🧑‍🏫 教研员  │────────▶│ 👨‍🏫 主讲老师 │────────▶│  👩‍🏫 助教    │
│  课程大纲    │         │    教案     │         │  PPT/材料   │
└─────────────┘         └─────────────┘         └─────────────┘
```

---

## 文档

| 文档 | 说明 |
|------|------|
| [超能学院Agent系统说明](超能学院Agent系统说明.md) | Agent系统完整说明 |
| [AGENTS.md](AGENTS.md) | AI助手指南 |
| [CONTRIBUTING.md](CONTRIBUTING.md) | 贡献指南 |
| [LICENSE](LICENSE) | 许可证 |

更多文档请查看 `/docs` 目录。

---

## 贡献

欢迎贡献代码！请阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何参与项目开发。

### 提交问题

- 🐛 Bug 报告：请使用 [Issue Template](./.github/ISSUE_TEMPLATE/bug_report.md)
- ✨ 功能请求：请使用 [Issue Template](./.github/ISSUE_TEMPLATE/feature_request.md)

---

## 许可证

本项目采用 [MIT 许可证](LICENSE)。

---

## 联系方式

- 📧 邮箱：support@super-academy.example.com
- 💬 讨论组：[GitHub Discussions](https://github.com/your-repo/super-academy/discussions)

---

<div align="center">

**如果这个项目对你有帮助，欢迎 ⭐ Star！**

</div>
