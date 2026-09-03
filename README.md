<div align="center">

# 🧮 数学征途 Math Quest

**一款类似多邻国的游戏化数学学习APP，内容覆盖从小学到大学的完整数学知识体系**

[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Web-blue)](https://github.com/wandering2027/math-quest)
[![Version](https://img.shields.io/badge/Version-1.0-green)](https://github.com/wandering2027/math-quest/releases)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/wandering2027/math-quest/blob/main/LICENSE)
[![PRD](https://img.shields.io/badge/PRD-完整文档-orange)](https://github.com/wandering2027/math-quest/blob/main/PRD.md)

[功能特性](#-功能特性) · [内容体系](#-内容体系) · [技术栈](#-技术栈) · [快速开始](#-快速开始) · [项目结构](#-项目结构)

</div>

---

## 📖 项目简介

「数学征途」是一款**完全免费、离线可用**的数学学习应用。通过**关卡闯关、经验升级、每日打卡、成就徽章**等游戏化机制，让数学学习变得有趣且可持续。

应用内容覆盖**小学→初中→高中→大学**四个阶段，共 **27个关卡、135道题目**，每个关卡包含知识点讲解、公式展示、例题解析和练习题，适合各年龄段学习者使用。

## ✨ 功能特性

### 🎮 游戏化学习
- **关卡路径**：垂直式学习路径，左右交替的关卡节点，一目了然
- **经验升级**：15个等级，从「数学新手」到「数学大师」，答题打卡获得经验
- **爱心生命**：答错扣心，30分钟自动恢复1颗，防止过度刷题
- **星级评价**：每关1-3星，根据正确率评定，激励反复练习
- **成就徽章**：8枚成就徽章，记录学习里程碑

### 📚 完整内容
- **小学**：认识数字、加减乘除、分数、运算定律、简易方程、百分数
- **初中**：有理数、一元一次方程、全等三角形、一次函数、二次函数、圆
- **高中**：集合与函数、三角函数、数列、立体几何、导数、概率统计
- **大学**：极限与连续、导数与微分、不定积分、定积分、矩阵与行列式、概率论

### 📅 打卡系统
- 每日打卡，连续天数统计
- 月历视图，直观展示打卡记录
- 本周目标进度条

### 👤 个人中心
- 总经验、通关数、正确率统计
- 各阶段学习进度可视化
- 成就徽章墙
- 一键重置学习进度

### 📱 体验优化
- 移动端优先设计，适配手机屏幕
- 完全离线运行，无需网络
- 数据本地存储，隐私安全
- 流畅的动画过渡和交互反馈

## 📐 内容体系

| 阶段 | 关卡数 | 题目数 | 核心知识领域 |
|------|--------|--------|--------------|
| 🟢 小学 | 9 | 45 | 算术基础、分数小数、运算定律、方程入门、几何初步 |
| 🔵 初中 | 6 | 30 | 有理数、方程、三角形、函数、圆 |
| 🟣 高中 | 6 | 30 | 集合函数、三角、数列、立体几何、导数、概率 |
| 🔴 大学 | 6 | 30 | 极限、微分、积分、线性代数、概率论 |
| **合计** | **27** | **135** | — |

<details>
<summary>📋 查看完整关卡列表</summary>

### 小学阶段
| 关卡 | 标题 | 核心知识点 |
|------|------|------------|
| e1-1 | 认识数字 | 1-10的认识、数的顺序 |
| e1-2 | 10以内加法 | 加法含义、凑十法 |
| e1-3 | 10以内减法 | 减法含义、加减法关系 |
| e2-1 | 表内乘法 | 乘法意义、乘法口诀 |
| e2-2 | 表内除法 | 平均分、乘除法关系 |
| e3-1 | 分数初步认识 | 分数意义、读写、大小比较 |
| e4-1 | 运算定律 | 交换律、结合律、分配律 |
| e5-1 | 简易方程 | 用字母表示数、解方程 |
| e6-1 | 百分数 | 百分数意义、折扣应用 |

### 初中阶段
| 关卡 | 标题 | 核心知识点 |
|------|------|------------|
| m1-1 | 有理数 | 正负数、相反数、绝对值 |
| m1-2 | 一元一次方程 | 方程概念、解法步骤 |
| m2-1 | 全等三角形 | SSS/SAS/ASA/AAS/HL判定 |
| m2-2 | 一次函数 | 函数概念、图像性质 |
| m3-1 | 二次函数 | 抛物线、顶点坐标、最值 |
| m3-2 | 圆 | 圆的性质、周长面积 |

### 高中阶段
| 关卡 | 标题 | 核心知识点 |
|------|------|------------|
| h1-1 | 集合与函数 | 集合运算、函数概念 |
| h1-2 | 三角函数 | 任意角三角函数、诱导公式 |
| h2-1 | 数列 | 等差、等比数列、求和 |
| h2-2 | 立体几何 | 空间几何体、体积公式 |
| h3-1 | 导数及其应用 | 导数概念、求导公式 |
| h3-2 | 概率统计 | 古典概型、期望方差 |

### 大学阶段
| 关卡 | 标题 | 核心知识点 |
|------|------|------------|
| u1-1 | 极限与连续 | 数列极限、两个重要极限 |
| u1-2 | 导数与微分 | 复合函数求导、洛必达法则 |
| u1-3 | 不定积分 | 原函数、换元积分法 |
| u1-4 | 定积分 | 牛顿-莱布尼茨公式 |
| u2-1 | 矩阵与行列式 | 矩阵运算、行列式性质 |
| u3-1 | 概率论基础 | 随机变量、期望方差、正态分布 |

</details>

## 🛠 技术栈

| 类别 | 技术 |
|------|------|
| **前端** | 原生 HTML5 + CSS3 + JavaScript（单文件，无框架依赖） |
| **移动端封装** | Android WebView（API 21+） |
| **构建工具** | Gradle 8.4 + Android Gradle Plugin 8.2.2 |
| **编译SDK** | Android SDK 34 |
| **数据存储** | 浏览器 localStorage / WebView localStorage |
| **字体** | Noto Sans SC（系统字体回退） |
| **图标** | 内联 SVG（无外部图标库依赖） |

## 🚀 快速开始

### 📱 Android 安装

1. 下载最新的 `数学征途-v1.0.apk`
2. 将APK文件传输到手机
3. 在手机上点击APK文件进行安装
4. 如提示「未知来源」，在设置中允许安装即可
5. 安装后桌面会出现「数学征途」图标，点击即可使用

> **最低要求**：Android 5.0（API 21）及以上

### 🌐 Web 版本

直接用浏览器打开 `math-quest/index.html` 即可使用，手机和电脑浏览器均适配。

### 🔧 从源码构建 APK

```bash
# 1. 克隆仓库
git clone https://github.com/wandering2027/math-quest.git
cd math-quest

# 2. 进入Android项目目录
cd math-quest-android

# 3. 构建Debug版本APK
gradle assembleDebug

# 4. APK输出路径
# app/build/outputs/apk/debug/app-debug.apk
```

**构建环境要求**：
- JDK 17+（推荐 JDK 21）
- Android SDK（需安装 platform-tools、build-tools 34.0.0、platforms android-34）
- Gradle 8.4

## 📁 项目结构

```
math-quest/
├── 📄 README.md                    # 项目说明文档（本文件）
├── 📄 PRD.md                       # 产品需求文档
├── 📄 .gitignore                   # Git忽略配置
├── 📦 数学征途-v1.0.apk           # 已构建的Android安装包
│
├── 📂 math-quest/                  # Web版本（单文件HTML应用）
│   └── 📄 index.html               # 完整应用（HTML+CSS+JS）
│
└── 📂 math-quest-android/          # Android项目
    ├── 📄 build.gradle             # 项目级Gradle配置
    ├── 📄 settings.gradle          # Gradle设置
    ├── 📄 gradle.properties        # Gradle属性
    ├── 📂 gradle/wrapper/          # Gradle Wrapper配置
    └── 📂 app/
        ├── 📄 build.gradle         # 模块级Gradle配置
        ├── 📄 proguard-rules.pro   # 代码混淆规则
        └── 📂 src/main/
            ├── 📄 AndroidManifest.xml  # 应用清单
            ├── 📂 assets/
            │   └── 📄 index.html       # Web应用资产（与Web版同步）
            ├── 📂 java/com/mathquest/app/
            │   └── 📄 MainActivity.java # 主Activity（WebView封装）
            └── 📂 res/
                ├── 📂 drawable/          # 应用图标（Vector Drawable）
                └── 📂 values/            # 字符串、主题等资源
```

## 📊 数据存储

所有学习数据存储在设备本地，**不上传任何服务器**，保护用户隐私。

```json
{
  "xp": 0,
  "hearts": 5,
  "completedLessons": {
    "e1-1": {
      "stars": 3,
      "bestScore": 100,
      "attempts": 2,
      "completedAt": "2026-09-03T10:00:00.000Z"
    }
  },
  "checkinDates": ["2026-09-01", "2026-09-02"],
  "streak": 2,
  "totalQuestions": 50,
  "correctQuestions": 42,
  "currentStage": "elementary"
}
```

## 🎨 设计规范

| 设计元素 | 色值 |
|----------|------|
| 主色调 | `#1A2744` 深靛蓝 |
| 强调色 | `#F59E0B` 琥珀金 |
| 成功色 | `#10B981` 翠绿 |
| 错误色 | `#EF4444` 珊瑚红 |
| 背景色 | `#F8F6F1` 米白 |
| 卡片色 | `#FFFFFF` 纯白 |

## 🗺 路线图

### ✅ v1.0（已发布）
- [x] 小学到大学完整知识体系（27关，135题）
- [x] 游戏化关卡学习路径
- [x] 答题系统（选择题+填空题）
- [x] 经验值与15级等级系统
- [x] 爱心生命值系统
- [x] 每日打卡与连续天数
- [x] 个人中心与学习统计
- [x] 成就徽章系统
- [x] Android APK 安装包
- [x] Web H5 版本
- [x] 完整 PRD 文档

### 🔮 v1.1（规划中）
- [ ] 错题本功能
- [ ] 题目收藏
- [ ] 学习提醒（本地通知）
- [ ] 题目扩充（每关10题）
- [ ] 搜索关卡功能
- [ ] 深色模式

### 🔮 v2.0（远期规划）
- [ ] 用户账号与云端同步
- [ ] 排行榜与社交功能
- [ ] 知识点视频讲解
- [ ] 个性化学习路径推荐
- [ ] iOS 版本

## 🤝 贡献指南

欢迎贡献代码、报告问题或提出建议！

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 📄 许可证

本项目采用 [MIT License](https://opensource.org/licenses/MIT) 开源协议。

## 🙏 致谢

- [多邻国 Duolingo](https://www.duolingo.com/) - 游戏化学习模式的灵感来源
- [可汗学院 Khan Academy](https://www.khanacademy.org/) - 知识体系结构参考
- [Noto Sans SC](https://fonts.google.com/noto/specimen/Noto+Sans+SC) - 开源中文字体

## 📞 联系我们

- **GitHub Issues**：[提交问题或建议](https://github.com/wandering2027/math-quest/issues)
- **项目主页**：https://github.com/wandering2027/math-quest

---

<div align="center">

**如果这个项目对你有帮助，欢迎给个 ⭐ Star 支持！**

Made with ❤️ for math learners

</div>
