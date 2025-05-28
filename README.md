
# 🚀 Getting Started with AI: Resources and Guides

Welcome to this repository of curated resources and tutorials for beginners in AI!

## 📚 What’s Inside
- Introductory AI concepts
- Hands-on tutorials
- Recommended courses and readings

👉 **Looking for Chinese version? [点击查看中文介绍 🇨🇳](README.zh.md)**

## 🔧 编程语言
### Python

关于 Python 的基础知识和环境配置，请参考 [菜鸟教程](https://www.runoob.com/python3/python3-tutorial.html) 或其他相关书籍。 

#### 创建和管理 Python 虚拟环境

创建虚拟环境是处理多个项目或解决环境依赖冲突的重要方法。主要原因包括：

- 便于版本管理和项目隔离：不同项目可能需要不同的 Python 版本和依赖库，使用虚拟环境可以轻松解决兼容性问题。
- 避免权限问题：在虚拟环境中安装库不需要管理员权限，更加灵活安全。

使用 Anaconda 管理虚拟环境，建议掌握以下基本操作。以下示例中演示了如何创建环境名为myenv,python版本为3.8的虚拟环境，并安装numpy包：

1. 安装 Anaconda（参考：[Anaconda官方下载页面](https://www.anaconda.com/download)）
2. 创建虚拟环境：`conda create --name myenv python=3.8`
3. 激活虚拟环境：`conda activate myenv`
4. 安装库（如 numpy）：`conda install numpy` 或 `pip install numpy`
5. 删除虚拟环境：`conda remove --name myenv --all`
6. 查看所有虚拟环境：`conda info --envs`
7. 查看当前环境的所有依赖包：`conda list` 或 `pip list`
## 深度学习
李沐老师在哔哩哔哩（Bilibili）平台上主讲的《动手学深度学习 PyTorch版》课程，旨在通过实践引导学习者掌握深度学习的核心概念和技术，特别是使用PyTorch框架进行实现。

**主要讲授内容：**

课程涵盖深度学习的基础知识、模型构建、优化算法以及在计算机视觉和自然语言处理等领域的应用。通过结合理论讲解和代码实现，帮助学习者理解并应用深度学习技术。

**主要讲授内容：**  

[动手学深度学习-电子书](https://zh.d2l.ai/)  

[bilibili视频授课](https://space.bilibili.com/1567748478/lists/358497?type=series)

**章节安排：**

1. **深度学习基础**：介绍深度学习概念、数据操作、线性代数、自动求导等预备知识。
2. **线性神经网络**：讲解线性回归、Softmax回归等基础模型及其实现。
3. **多层感知机**：深入探讨多层感知机的结构、模型选择、正则化方法等。
4. **卷积神经网络**：介绍卷积层、池化层等CNN基础组件及经典网络结构，如LeNet、AlexNet等。
5. **循环神经网络**：讲解RNN、LSTM、GRU等序列模型及其应用。
6. **注意力机制**：介绍注意力机制的概念及Transformer模型。
7. **优化算法与计算性能**：讨论深度学习中的优化方法和提升计算性能的技巧。
8. **应用实践**：展示深度学习在计算机视觉和自然语言处理中的实际应用案例。

**学习建议：**

* **实践为主**：结合课程中的代码示例，动手实现各类模型，加深理解。
* **系统学习**：按照课程章节顺序学习，逐步构建对深度学习的全面认识。
* **参与讨论**：利用课程提供的论坛或社区，与其他学习者交流问题和经验。
* **参考教材**：配合《动手学深度学习》第二版教材，获取更详细的理论和实践指导。
* **需求导向**：结合自身的应用场景和研究需求，有针对性地选择重点章节进行学习，避免盲目从头到尾照搬式学习。
通过以上学习路径，可以扎实掌握深度学习的理论基础和实践技能，为进一步研究或应用奠定坚实基础。



---

## 📘 实用机器学习（Practical Machine Learning）
[![李沐: 实用机器学习(斯坦福21秋季) - 知乎](https://tse1.mm.bing.net/th?id=OIP.W-d9RWukeCMauZURrob6WwHaEK\&pid=Api)](https://zhuanlan.zhihu.com/p/411337554)

李沐老师在 Bilibili 上的《斯坦福 2021 秋季·实用机器学习（CS329P）》课程，聚焦于机器学习在工业界的实际应用，强调从数据获取到模型部署的完整流程。课程内容丰富，涵盖数据处理、模型训练、评估与部署等关键环节，适合希望将机器学习技术应用于实际项目的学习者。

* **主讲教师**：李沐（Mu Li）、黄清清（Qingqing Huang）、Alex Smola
* **课程平台**：Bilibili（[课程链接](https://www.bilibili.com/video/BV13U4y1N7Uo/)）
* **课程主页**：[https://c.d2l.ai/stanford-cs329p/](https://c.d2l.ai/stanford-cs329p/)
* **课程语言**：中文讲解，配有英文资料
* **适合人群**：具备基础编程和机器学习知识，期望深入了解机器学习在实际应用中的完整流程的学习者

### 🧭 课程结构与主要内容

课程共分为四大模块，涵盖以下内容：

1. **数据收集与处理**

   * 数据获取与爬取
   * 数据清洗与预处理
   * 特征工程与数据变换
   * 数据标注与半监督学习

2. **模型训练与评估**

   * 常用模型介绍（线性模型、决策树、神经网络等）
   * 模型评估指标与验证方法
   * 过拟合与欠拟合的识别与处理
   * 模型融合技术（Bagging、Boosting、Stacking）

3. **高级主题与优化**

   * 超参数调优与自动化搜索（AutoML）
   * 迁移学习与微调策略
   * 模型压缩与蒸馏
   * 多任务学习与多模态融合

4. **模型部署与维护**

   * 模型上线与服务部署
   * 性能监控与反馈机制
   * 公平性与可解释性
   * 因果推理与决策支持

课程还特别强调了数据偏移（如协变量偏移、概念漂移）对模型性能的影响，并介绍了应对策略。  

### 🎯 学习建议

* **结合实践**：在学习过程中，结合实际项目或案例进行练习，加深理解。
* **关注数据质量**：重视数据的获取与处理，确保模型训练的基础可靠。
* **持续迭代**：模型部署后，持续监控其性能，并根据反馈进行优化。
* **拓展知识面**：深入学习课程中提到的高级主题，如迁移学习、模型压缩等，提升模型的实用性和效率。

通过系统学习本课程，学习者将能够全面掌握机器学习在实际应用中的各个环节，从而更有效地将理论知识应用于实际项目中。


根据你提供的图片，《Machine Learning From Scratch》教程的目录结构非常系统化，内容不仅涵盖了机器学习算法本身，还包括数据处理与数学基础模块。以下是按照之前 GitHub `README.md` 风格整理的课程介绍：

---

## 🧠 Machine Learning From Scratch 教程概览

《Machine Learning From Scratch》是一个面向初中高级学习者的开源教程，旨在从零构建机器学习模型，并深入理解其数学原理与实现方法。教程强调理论与实战相结合，适合作为系统学习机器学习的路径资源。

📚 **项目地址**：[Machine Learning From Scratch](https://machine-learning-from-scratch.readthedocs.io/zh_CN/latest/)

---

### 📘 教程模块与主要内容

#### 📂 数据处理模块（Data Processing）

* **数据探索**：如何理解和浏览原始数据。
* **特征清洗**：处理缺失值、异常值等预处理任务。
* **特征工程**：进行编码、变换等操作。
* **特征选择**：基于信息增益、方差等方法选择有效特征。

#### 📐 数学基础模块（Math）

* **单变量微积分（Calculus P1）**
* **多变量微积分（Calculus P2）**
* **线性代数（Linear Algebra）** *（进行中）*
* **概率论（Probability）** *（进行中）*
* **统计学（Stats）** *（TODO）*
* **最优化算法（Optimization）** *（TODO）*

> ✅ 数学模块为后续算法打下坚实理论基础，非常适合同时搭配数学学习者使用。

#### ⚙️ 机器学习算法模块（Algorithm）

* **模型评估与模型调优**
* **正则化方法（Regularization）** *（TODO）*
* **损失函数（Loss Function）** *（TODO）*

### 🎯 学习建议

* **循序渐进**：先从数学与数据处理模块入手，再进入机器学习算法的学习。
* **理论结合实践**：每个知识点配有简洁代码，建议手动实现核心算法以加深理解。
* **查漏补缺**：TODO 和 InProcess 项目代表尚在完善，建议关注官方动态或自行扩展补充学习。
* **配合 GitHub 项目**：可结合 [开源代码库](https://github.com/eriklindernoren/ML-From-Scratch) 实现更多算法。

通过本教程的系统学习，你将能从零构建起对机器学习的理解框架，掌握从数据准备到模型评估的完整流程，并为后续深入学习或工程应用打下坚实基础。




## 📌 License
...
