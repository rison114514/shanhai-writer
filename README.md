<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-black" />
  <img src="https://img.shields.io/badge/Hermes-Skill-orange" />
  <img src="https://img.shields.io/badge/Type-Writing%20Suite-purple" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" />
  <img src="https://img.shields.io/badge/朱雀-全人工特征-success" />
</p>

<h1 align="center">山海写作</h1>

<p align="center">
  <i>「AI 写骨架，人类注灵魂。4 版迭代，100% → 全人工。」</i>
</p>

<p align="center">
  <b>一套完整的中文长文写作工具包。逐段协作创作 + 系统化降 AI 率，从生成到发布全流程覆盖。</b>
</p>

<br>

<p align="center">
  <a href="#快速开始">快速开始</a> ·
  <a href="#实测数据">实测数据</a> ·
  <a href="#核心方法">核心方法</a> ·
  <a href="#技能架构">技能架构</a> ·
  <a href="#原理">原理</a>
</p>

---

## 快速开始

**创作**：说「写一篇关于 XX 的文章」，自动进入逐段协作——你给思路，AI 填空。

**降 AI**：把文章发来说「降 AI」，自动进入 5 步快速路径，4 版到全人工。

---

## 实测数据

| 文章 | 原文 | v1 | v2 | v3 | v4 |
|---|---|---|---|---|---|
| HTML 评测 | 100% AI | — | — | — | **全人工** |
| Hermes Agent 教程 | 100% AI | 疑似 AI | ↓10% | 中间脱离 | **全人工** |

> 第二篇仅用 4 版完成。字节数从 5309 → 6364，增长的 +22% 全是噪声——与原文信息量无关的私有细节。

---

## 核心方法

### 8 种有效噪声

| # | 类型 | 示例 |
|---|---|---|
| 1 | 生理细节 | 「宫保鸡丁。花生多，鸡丁少。」 |
| 2 | 口是心非 | 「准备划走了。但是没划。」 |
| 3 | 具体失败 + 精确时间 | 「三十秒。4 点 47 到 5 点 07。」 |
| 4 | 叙事故意打断 | 「中间回了条微信。同事问会还开不开。」 |
| 5 | 自打断吐槽 | 「等一下，咖啡凉了我之前是不是说过。」 |
| 6 | 中途自我怀疑 | 「这是教程吗。网上已经有一百篇了。」 |
| 7 | 口是心非链 | 先说不拉扯 → 立刻承认拉扯 |
| 8 | 失败清单收束 | 结尾盘点所有失败，不总结观点 |

### 3 种无效噪声（黑名单）

| 类型 | 为什么无效 |
|---|---|
| 「泡了杯咖啡」 | AI 训练数据高频 |
| 「用了十年 Windows」 | 噪声模板 |
| 「我也在反思」 | AI 也会模仿 |

---

## 技能架构

```
shanhai-writer
│
├── 创作模式 → rui-writer
│   ├── 逐段协作：人给骨架，AI 填空
│   └── 继承 16 条公理 + 不修正原则
│
└── 降AI模式 → de-ai
    ├── Step 1 · 砍结构
    ├── Step 2 · 注噪声（8 种有效 + 3 种黑名单）
    ├── Step 3 · 改语调
    ├── Step 4 · 碎叙事
    ├── Step 5 · 环状回扣
    └── 执行纪律 7 条
```

---

## 原理

朱雀不是判断「像不像人」——是判断「像不像某个 AI 训练集里的文本」。公众号 AI 科技评测是朱雀训练数据最密集的类型。

降 AI 率的核心不是「更像人」，是**让文章偏离朱雀见过的 AI 文本分布**。有效噪声 = 奇怪、具体、不可迁移。

---

## 文件结构

```
shanhai-writer/
├── README.md
├── SKILL.md              # 入口（自动路由 创作 / 降AI）
├── rui-writer.md         # 逐段协作写作
├── de-ai.md              # 降AI率（5 步 + 样本 + 纪律）
└── references/
    ├── zhang-writer.md   # 16 条公理 + 不修正原则
    ├── banned_patterns.md
    ├── chat_voice.md
    └── content_methodology.md
```

---

<p align="center">
  <sub>MIT · Made with 🍗 宫保鸡丁</sub>
</p>
