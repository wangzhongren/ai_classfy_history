# AI分类模型演进史：统一理论框架

> 一个初中生也能懂的人工智能分类发展史，极客风格呈现，聚焦“分类”这一AI核心能力的70年演进。

![AI Classification Evolution](https://img.shields.io/badge/AI-分类演进-blue) ![Static Site](https://img.shields.io/badge/Type-静态网站-lightgrey)

## 📖 项目简介

本项目通过一个单页网站，系统梳理人工智能在**分类任务**上的三次范式跃迁：

1. **[1950s–2010] 规则匹配分类**：人类专家编写显式规则（如专家系统、决策树）；
2. **[2012–2022] 监督学习分类**：深度学习从标注数据中自动学习特征（如CNN、ResNet）；
3. **[2023–未来] 自回归语义分类**：大模型通过自回归生成，在连续语义空间中动态构建分类体系。

核心观点：**所有AI进步，都是为了解决“如何更好分类”这一根本问题**。

## ✨ 项目特色

- **统一理论框架**：以“分类”为主线，贯穿AI 70年发展史；
- **双重视角**：
  - 👦 **初中生友好**：每个阶段配生活化例子（垃圾邮件过滤、认猫狗、情绪分析）；
  - 💻 **极客风格**：深色主题、等宽字体、代码块高亮，技术细节准确；
- **精准技术解释**：
  - 明确区分 RNN 与 Transformer 在自回归机制上的异同；
  - 强调 **“自回归 = 输出作为新输入的连续分类闭环”**；
- **可视化辅助**：包含 3 张原创 SVG 示意图，直观展示各阶段核心机制；
- **结构化呈现**：每阶段严格遵循 **问题 → 解决思路 → 例子 → 技术对照 → 局限性** 逻辑链。

## 🖼️ 页面预览

![Website Preview](preview.png)  
*(注：实际部署时可替换为真实截图)*

## 📂 项目结构

```
├── index.html                # 主页面（极客风格，深色主题）
├── stage1_decision_tree.svg  # 第一阶段：决策树规则匹配示意图
├── stage2_cnn.svg            # 第二阶段：CNN特征学习示意图
├── stage2_transformer.svg    # 第三阶段：Transformer自回归机制示意图
└── README.md                 # 本文件
```

## 🚀 本地运行

1. 克隆本项目：
   ```bash
   git clone https://github.com/your-name/ai-classification-evolution.git
   cd ai-classification-evolution
   ```

2. 直接用浏览器打开 `index.html` 即可浏览（无需服务器）。

## 💡 设计理念

- **通俗不失深度**：初中生能看懂故事，开发者能看到技术脉络；
- **问题驱动演进**：每个新阶段都源于对前一阶段局限性的突破；
- **聚焦核心机制**：不堆砌技术名词，而是解释“为什么这样做”和“解决了什么问题”。

## 📜 技术栈

- **HTML5 + CSS3**：纯静态页面，无外部依赖；
- **SVG**：矢量图形，清晰可缩放；
- **原生 JavaScript**：仅用于导航高亮，轻量高效。

## 📝 致谢

- SVG 图标灵感来源于 [TensorFlow](https://www.tensorflow.org/) 与 [PyTorch](https://pytorch.org/) 官方文档；
- 极客风格参考 [Vercel](https://vercel.com/) 与 [GitHub Dark Mode](https://github.com/)。

---

© 2025 your.name | 为教学与科普而生，欢迎传播并注明出处。