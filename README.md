# 最优化与机器学习的数学基石：精选笔记

本仓库整理了一套关于最优化与机器学习数学基础的讲义。

## 🎯 编写初衷

借助现代机器学习框架与数值求解器，我们可以轻松地将各类算法当作“黑盒”直接调用。然而，不少经典教材在讲解底层算法（如 Dantzig 的单纯形法）时，往往偏向于机械的主元消去（Pivoting）步骤，忽略了背后的几何直觉与理论来源（例如对偶变量究竟因何引入）。

本讲义旨在从第一性原理出发，提供一套循序渐进、注重启发的推演路径：

* **完整推导：** 补全主流教材中常见的逻辑断层与推导跳跃。
* **几何直观：** 结合多面体几何、凸锥与代数特征，还原算法背后的几何本质。
* **洞察底层：** 跨越单纯的 API 调用，真正理解最优化与机器学习算法的运行机制。

## 📚 内容大纲

- [:white_check_mark:] **线性优化与多面体几何**
  - 实分析与凸几何预备知识
  - 基于 Farkas 引理推导对偶理论
  - 极点与多面体的代数特征
  - 单纯形法背后的几何机制
- [ ] **凸优化与对偶理论** *(in-progress)*
- [ ] **机器学习算法的数学基础** *(in progress：SVM、核方法等)*

# Selected Notes on the Mathematical Groundwork for Optimization and Learning

This repository contains a collection of lecture notes exploring the mathematical foundations of optimization and machine learning.

## 🎯 Motivation

Modern machine learning frameworks and numerical solvers make it remarkably easy to apply optimization algorithms as black boxes. However, standard introductory materials often treat algorithms such as George Dantzig's Simplex Method as purely mechanical pivoting routines, skipping the underlying geometric intuition and theoretical derivations. 

The goal of these notes is to take a **pedagogical, first-principles route**:
* **Complete Proofs:** Filling in logical gaps commonly found in standard textbooks.
* **Geometric Viewpoints:** Reconstructing algorithms through polyhedral geometry, convex cones, and algebraic characterizations.
* **Deep Mechanics:** Building a mathematical baseline that enables a genuine understanding of modern optimization and machine learning algorithms beyond simple API invocations.

## 📚 Scope & Roadmap

- [x] **Linear Optimization & Polyhedral Geometry**
  - Real analysis & convex geometry preliminaries
  - Duality from Farkas' Lemma
  - Extreme points and polyhedral characterization
  - The geometry behind the Simplex Method
- [ ] **Convex Optimization & Duality** (In Progress)
- [ ] **Mathematical Foundations of Learning Algorithms** (e.g., SVM, Kernel Methods) (Planned)

