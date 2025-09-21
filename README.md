# 《从基础到 Transformer：大型语言模型（LLM）核心原理教程》

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/your-username/your-repo-name/pulls)

欢迎来到本开源教程！本教程旨在为学习者提供一个系统、清晰且由浅入深的学习路径，以理解现代大型语言模型（尤其是 Transformer）背后的核心机器学习原理。我们将从最基础的机器学习概念开始，逐步推导至复杂的 Transformer 架构。

> **核心理念**：真正的理解源于从头构建。本教程鼓励动手实践，每个核心概念都配有可运行的代码实现。

## 📖 教程目录结构

本教程按部分（Part）组织，建议按顺序学习。

| 部分 | 标题 | 内容概述 | 状态 |
| :--- | :--- | :--- | :--- |
| **Part 0** | **[前言与基础概念](./part0-preface/)** | 学习指南、环境配置、数学基础 | ✅ |
| Part 1 | [线性回归](./part1-linear_regression/) | 损失函数、梯度下降、多元线性回归 | 🚧 |
| Part 2 | [逻辑回归](./part2-logistic_regression/) | 分类问题、Sigmoid、交叉熵损失 | TODO |
| Part 3 | [神经网络基础](./part3-neural_networks/) | 激活函数、反向传播、多层感知机（MLP） | TODO |
| ... | ...（您的其他章节）... | ... | TODO |
| Part N | [Transformer 架构](./partN-transformer/) | 自注意力机制、编码器-解码器结构、位置编码 | TODO |

## 🚀 开始学习

### 先修知识
*具备基本的 Python 编程能力。
*了解高中级别的数学（线性代数、微积分、概率）基本概念更佳，但教程会附带必要知识的复习。

### 环境配置

1.**克隆本仓库**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2.**创建虚拟环境（推荐）**
我们强烈建议使用 `conda` 或 `venv` 来管理依赖。
```bash
# 使用 conda
conda create -n llm-tutorial python=3.10
conda activate llm-tutorial

# 或使用 venv
python -m venv llm-tutorial-env
source llm-tutorial-env/bin/activate# Linux/macOS
# llm-tutorial-env\Scripts\activate# Windows
```

3.**安装依赖**
```bash
pip install -r requirements.txt
```

### 如何学习
1.每个部分都是一个独立的文件夹。
2.首先阅读该部分的 `README.md`，了解本章的理论知识。
3.阅读并运行提供的 Jupyter Notebook (`.ipynb`) 或 Python 脚本 (`.py`)，亲手实践和修改代码。
4.通过练习题巩固所学知识。

---

## 🧭 Part 0：前言与基础概念

**位置**： [`./part0-preface/`](./part0-preface/)

这是您学习之旅的起点。本章节将为您准备好一切必要的工具和背景知识。

### 内容详情
*`README.md`: 本章的详细说明文档。
***0.1 教程简介与学习路径**
*为什么选择本教程？
*整体课程结构地图。
***0.2 环境配置指南**
*详细的环境配置步骤（Python, Jupyter, NumPy 等）。
***0.3 必备数学知识回顾**
***线性代数**: 向量、矩阵、点积、矩阵乘法。
***微积分**: 导数、偏导数、梯度的直观理解。
***概率**: 基本概念、Softmax 函数。
***0.4 核心工具介绍**
*NumPy 快速入门。
*Jupyter Notebook 使用指南。
***0.5 【实战】: 使用 NumPy 进行线性代数操作**

### 代码与实战
*`math_review.ipynb`: 交互式地复习核心数学概念，并附有代码示例。
*`numpy_basics.ipynb`: 学习本章后，确保您可以熟练运行此 Notebook 中的所有代码。

---

## 🤝 如何贡献

我们非常欢迎和鼓励任何形式的贡献！

1.**发现错误**：如果您发现错别字、代码错误或表述不清的地方，请直接提交一个 Issue。
2.**改进内容**：如果您有更好的解释方式或更有趣的例子，欢迎 Fork 本仓库并提交 Pull Request。
3.**提出建议**：对于教程后续内容或结构的建议，也请在 Issue 中讨论。

请阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 了解详细的贡献指南和行为准则。

## 📜 许可证

本项目采用 MIT 许可证。请查看 [LICENSE](LICENSE) 文件了解更多信息。

## 🙏 致谢

*感谢诸多优秀的机器学习开源课程和书籍提供的灵感。
*感谢所有为本项目提交 Issue 和 PR 的贡献者。

## ❓ 常见问题

**Q: 我需要非常厉害的数学水平吗？**
**A:** 不需要。教程会涵盖所有必要的数学知识，并注重直观理解而非复杂的推导。

**Q: 学习完整个教程需要多久？**
**A:** 这取决于您的背景和学习速度。如果您每天花费2-3小时，预计需要数周至数月来完成全部内容。建议循序渐进，重在理解。

**Q: 会讲如何训练像 GPT 这样的模型吗？**
**A:** 本教程重点在于**核心原理**。理解了 Transformer，您就掌握了理解所有现代 LLM 的基石。大规模预训练、分布式计算等内容可能不会在本教程中深入涉及。

---

如果这个项目对您有帮助，请给它一个 ⭐️ ！这是对作者最大的鼓励。

---

**Happy Learning!**
