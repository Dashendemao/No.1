# Bio-Ribs Simulation Engine (v3.5)

> A biomechanical soft-body physics engine designed specifically for simulating realistic tissue dynamics under gravity and tension.

**Designed & Engineered by: Dashendemao (大神的毛)**

---

## 📖 项目简介 (Introduction)

Bio-Ribs 不是一个传统的基于贝塞尔曲线的简单动画。它是一个基于**有限元肋位理论 (Finite Element Rib-based Structure)** 构建的生物力学模拟器。

作为一名工业设计师，我开发这个引擎是为了解决传统 2D 模拟中常见的“气球感”和“缺乏体积感”的问题。它模拟了真实的生物组织在重力、内部压力和悬韧带约束下的复杂形变。

## ⚙️ 核心特性 (Key Features)

* **肋位离散架构 (Rib-based Discretization)**: 摒弃抽象控制点，使用 40 个相互关联的物理肋位，实现细腻的局部形变与整体联动的平衡。
* **穹顶滑移与水滴形仿真 (Dome Slip & Teardrop Simulation)**: 引入解剖学上的“悬韧带张力”控制。当张力不足以对抗重力时，质量中心会真实地滑向底部，形成自然下垂的“水滴形”。
* **重力溢出动力学 (Gravity Overflow)**: 模拟大体量组织在倾斜姿态下，受自重影响漫出底盘边界的物理现象。
* **0.99 拖拽缓冲规则**: 独创的交互逻辑，确保用户交互极限略小于物理极限，保证松手瞬间获得真实的物理回弹力 (F=ma)。

## 🎮 如何运行 (How to Run)

本项目是一个纯前端实现的单文件工具，无需安装任何依赖或服务器。

1.  下载 `index.html` 文件。
2.  使用任意现代浏览器（Chrome, Firefox, Edge, Safari）打开即可运行。

## ⚠️ 许可与法律声明 (License & Legal)

本项目采用 **CC BY-NC-SA 4.0** (署名-非商业性使用-相同方式共享 4.0 国际) 协议进行开源。

在使用本项目的任何代码、逻辑或衍生作品时，您必须严格遵守以下条款：

### ✅ 您可以 (You are free to):
* **学习与研究**: 分析代码逻辑用于学术或个人学习目的。
* **非营利性创作**: 将其用于不产生任何直接或间接收益的艺术项目中。
* **分享与演绎**: 在保留原作者署名和相同协议的前提下，修改和再发布代码。

### ❌ 您绝不可以 (You MUST NOT):
* **商业使用**: 【严禁】将本引擎或其衍生品的任何部分用于商业产品、付费服务、广告盈利内容或任何形式的变现渠道。
* **闭源发布**: 如果您基于此代码进行了修改，您发布的新版本必须也开源且采用相同的 CC BY-NC-SA 4.0 协议。

---
© 2024-2026 Dashendemao. All rights reserved.