# CS61A 暑假两周冲刺学习项目

> UC Berkeley **CS61A: Structure and Interpretation of Computer Programs**  
> 主讲: John DeNero | 2024 Fall 官方课程  
> 学习周期: 2026.06.23 - 2026.07.06 (14天)  
> GitHub: [kiger-123/CS61A-Summer-Study](https://github.com/kiger-123/CS61A-Summer-Study)  
> Notion: 📋 [学习跟踪看板](待添加)

---

## 🎯 课程目标

| 模块 | 核心内容 |
|------|---------|
| 函数式编程基础 | 函数、控制流、高阶函数、环境图、递归 |
| 数据抽象 | 序列、列表、树、数据抽象、可变性 |
| 面向对象 | 类、继承、对象组合 |
| 解释器与元编程 | Scheme 解释器、Programs as Data、Macros |
| 数据库 | SQL 基础、表、聚合、数据库设计 |

## 📅 两周时间线

| 天 | 日期 | 主题 | 视频/阅读 | 练习 | 项目 |
|---|------|------|----------|------|------|
| 1 | 6/23 (一) | Functions & Control | Lec 1-2 | Lab 00/01, HW 01 | — |
| 2 | 6/24 (二) | Higher-Order Functions | Lec 3-4 | Lab 02, HW 02 | — |
| 3 | 6/25 (三) | Environments & Lambda | Lec 5-6 | Disc 02 | Hog Checkpt |
| 4 | 6/26 (四) | Recursion & Tree Recursion | Lec 7-9 | Lab 03, HW 03 | — |
| 5 | 6/27 (五) | Sequences & Data Abstraction | Lec 10-12 | Lab 04 | Hog |
| 6 | 6/28 (六) | Mutability & Iterators | Lec 13-15 | Lab 05, HW 04 | — |
| 7 | 6/29 (日) | Generators & OOP Intro | Lec 16-18 | Lab 06, HW 05 | Cats |
| 8 | 6/30 (一) | Inheritance & Composition | Lec 19-21 | Lab 07, HW 06 | — |
| 9 | 7/1 (二) | Efficiency & Data Structures | Lec 22-24 | Lab 08 | Ants |
| 10 | 7/2 (三) | Language Models (Optional) | Lec 25 | Disc 08 | — |
| 11 | 7/3 (四) | Scheme Basics | Lec 26-28 | Lab 10 | Scheme |
| 12 | 7/4 (五) | Programs as Data & Macros | Lec 29-31 | Lab 11, HW 09 | — |
| 13 | 7/5 (六) | SQL | Lec 32-36 | Lab 12, HW 10 | — |
| 14 | 7/6 (日) | Finale & Review | Lec 37 | HW 11 | 总结归档 |

## 🏗 项目进度

- [ ] **Hog** (Day 1-5) — 骰子游戏模拟，高阶函数 + 控制流
- [ ] **Cats** (Day 6-7) — 自动补全与打字游戏，数据抽象 + 递归
- [ ] **Ants** (Day 8-9) — 蚂蚁大战蜜蜂，面向对象 + 继承
- [ ] **Scheme** (Day 11-12) — Scheme 解释器，元编程 + 程序即数据

## 📁 仓库结构

```
CS61A-Summer-Study/
├── README.md              # 本文件
├── notes/                 # 每日笔记
│   ├── day01-functions.md
│   ├── day02-hof.md
│   └── ...
├── labs/                  # 实验代码
│   ├── lab00/
│   ├── lab01/
│   └── ...
├── homework/              # 作业代码
│   ├── hw01/
│   └── ...
├── projects/              # 大项目
│   ├── hog/
│   ├── cats/
│   ├── ants/
│   └── scheme/
└── assets/                # 截图、思维导图等
    └── env-diagrams/
```

## 🔗 核心资源

| 资源 | 链接 |
|------|------|
| 官方课程主页 | https://cs61a.org |
| 课程视频 | YouTube 官方频道 (John DeNero) |
| 教材 (Composing Programs) | https://www.composingprograms.com |
| 实验环境 | 本地 Python 3 + ok 测试框架 |
| 课程讨论区 | Ed (仅限注册学生) |
| 历年试卷 | cs61a.org → Resources → Past Exams |

## ⚙️ 本地环境配置

```bash
# 1. 克隆仓库
git clone https://github.com/kiger-123/CS61A-Summer-Study.git
cd CS61A-Summer-Study

# 2. 确保 Python 3.10+ 已安装
python3 --version

# 3. 创建虚拟环境 (推荐)
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 4. 下载 CS61A 的 ok 测试框架
# 见各 Lab/Project 目录下的 ok 文件
```

## 📊 学习统计

| 指标 | 目标 | 实际 |
|------|------|------|
| 视频观看 | 37 讲 | 0/37 |
| Labs 完成 | 12 个 | 0/12 |
| Homework 完成 | 11 份 | 0/11 |
| Projects 完成 | 4 个 | 0/4 |
| 笔记篇数 | 14 篇 | 0/14 |
| 总学习时长 | ~80h | 0h |

> 每日目标: 5-6 小时有效学习 (视频 2h + 阅读 0.5h + 练习 2h + 项目/作业 1.5h)

## 📝 每日学习流程 (参考)

```
08:30 - 09:00  复习昨日笔记 + 快速回顾
09:00 - 11:00  观看当日课程视频 (2x速, 暂停做笔记)
11:00 - 11:30  阅读教材对应章节
14:00 - 15:30  完成 Lab 或 Project 编码
15:30 - 17:00  完成 Homework 或 Project
17:00 - 17:30  写学习笔记 → 提交到 GitHub + Notion
17:30 - 18:00  总结 + 明日预习
```

## 💡 学习原则

1. **先理解后编码**: 看视频时手写笔记，不急着开编辑器
2. **环境图画三遍**: 环境图是CS61A的灵魂，每道涉及环境的题都画一遍
3. **测试驱动**: 用 `ok` 框架跑测试，绿了就过，红了就debug
4. **不抄答案**: 作业卡住先看教材/笔记，再搜思路，最后才看solution
5. **项目优先**: 如果某天时间不够，优先保证 Project 的进度
6. **每天提交**: 哪怕只写了一行笔记，也要 `git commit && git push`

## 🏆 完成标准

- [ ] 所有 Lab 通过 ok 测试
- [ ] 所有 Homework 通过 ok 测试
- [ ] 4 个 Project 全部完成（Hog, Cats, Ants, Scheme）
- [ ] 教材 Composing Programs 对应章节通读
- [ ] 14 天笔记完整归档到 GitHub + Notion
- [ ] 整理一份个人「CS61A 核心知识速查表」

---

> 既然选择了 MIT/UC 路线，就要按他们的标准要求自己。两周不是终点，是养成自学能力的起点。
>
> — 黄宗凯, 2026.06.22
