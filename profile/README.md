# 欢迎来到 BigData2026QDU 👋

> **2026 大数据 Spark 核心项目组织** | 探索数据价值，构建标准化的全栈大数据流水线

我们是一个专注于 **大数据处理** 与 **Spark 计算框架** 的协作开发团队。本组织致力于构建从前端 Web 交互、后端数据库连接，到海量数据处理与分析的完整生态系统。我们极为重视**代码规范**与**工程化测试**，为不同的技术栈量身定制了标准的流水线与测试骨架。

---

## 🛠️ 技术栈 (Tech Stack)

![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![Scala](https://img.shields.io/badge/-Scala-DC322F?style=flat-square&logo=scala&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Apache Spark](https://img.shields.io/badge/-Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Pipelines](https://img.shields.io/badge/-CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 🗂️ 核心架构与仓库 (Repositories)

### 🌟 主线项目 (Core Projects)
* 🚀 [**SparkMain**](https://github.com/BigData2026QDU/SparkMain) - 大数据项目核心主仓库（Shell/Spark），负责统筹任务的执行与调度。
* 🌐 [**WebMain**](https://github.com/BigData2026QDU/WebMain) - 项目 Web 端主仓库，提供数据的可视化展示与交互界面。

### 📐 规范与约束 (Standards)
* 🛡️ [**AGENTS**](https://github.com/BigData2026QDU/AGENTS) - **核心规范仓库**。**【重要】** 所有子模块与仓库**必须**以 Git Submodule 的形式引入本仓库，并严格遵循其中的代码与协作规范。

### 🧩 功能模块 (Modules)
* 🌓 [**DayNightModule**](https://github.com/BigData2026QDU/DayNightModule) - 前端核心模块 (JavaScript)，提供平滑的日间/夜间模式切换功能。
* 🔗 [**DatabaseConnectModule**](https://github.com/BigData2026QDU/DatabaseConnectModule) - 后端核心模块 (Java)，提供稳定、高效的数据库连接服务。
* 🧑‍💻 [**SparkXTY**](https://github.com/BigData2026QDU/SparkXTY) - XTY 的专属 Spark 任务与实验仓库。

### 🧪 测试骨架与流水线 (Test Skeletons)
我们推崇测试驱动开发（TDD）与持续集成工程化。以下是我们为各技术栈提供的标准测试骨架，新项目开发请基于此进行构建：
* ☕ [**JavaTestSkeleton**](https://github.com/BigData2026QDU/JavaTestSkeleton) - Java 语言标准测试框架骨架
* 🐍 [**PythonTestSkeleton**](https://github.com/BigData2026QDU/PythonTestSkeleton) - Python 自动化流水线测试框架
* 🔴 [**ScalaTestSkeleton**](https://github.com/BigData2026QDU/ScalaTestSkeleton) - Scala 测试骨架
* ✨ [**SparkTestSkeleton**](https://github.com/BigData2026QDU/SparkTestSkeleton) - 针对 Spark 任务量身定制的专属测试框架
* 🎨 [**FrontendTestSkeleton**](https://github.com/BigData2026QDU/FrontendTestSkeleton) - 前端 (JavaScript) 工程测试骨架

---

## 🤝 参与指南 (How to Contribute)

1. **遵守规范**：开发新模块或项目时，请务必第一时间通过 Submodule 引入 `AGENTS` 仓库。
2. **使用骨架**：请根据你的开发语言，Clone/Fork 对应的 `TestSkeleton` 作为项目起点。
3. **提交代码**：确保所有本地测试通过，并在提交 PR 后关注自动化流水线（Pipeline）的结果。

