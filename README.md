# Awesome Crowd Counting Papers

> 📚 A curated list of Crowd Counting papers (2008–2026) with paper links, official code, and Chinese blog/video tutorials.
> 人群计数论文、代码与中文讲解一站式汇总

![Papers](https://img.shields.io/badge/Papers-276-blue) ![Code Repos](https://img.shields.io/badge/Code_Repos-31-green) ![Blog Tutorials](https://img.shields.io/badge/Blog_Tutorials-22-orange) ![Video Tutorials](https://img.shields.io/badge/Video_Tutorials-3-ff69b4) ![Last Updated](https://img.shields.io/badge/Last_Updated-2026--11-yellow)

---

## 🎯 项目目的

人群计数（Crowd Counting）方向论文数量庞大、方法演进迅速（密度图回归 → 点回归 → Transformer / CLIP / SAM / 扩散模型……），论文链接与官方代码分散在 arXiv、CVF、IEEE、GitHub 等各处，初学者往往要花大量时间找论文、找代码、找讲解。

本项目将 2008–2026 年的经典与前沿人群计数论文系统化整理为一份结构化清单，**每篇论文均提供**：

- **标题与发表信息**（会议 / 期刊、年份）
- **论文下载链接**：arXiv / CVF Open Access / DOI 永久链接
- **代码链接**：官方实现 / 非官方 PyTorch 实现 / 复现代码（如有）
- **中文讲解**：配套的 CSDN 博客详解与 Bilibili 视频讲解（作者：[Keep_Trying_Go](https://blog.csdn.net/Keep_Trying_Go)）

> 💡 无论你是刚进入该方向的研究生、准备复现论文的算法工程师，还是需要快速调研某类方法的研究者，都可以按图索骥，一步直达目标论文及其全部资源。

## 📂 仓库结构

```
├── README.md                        # 本文件：项目概述与使用指引
└── CrowdCounting-Papers-Summary.md  # 完整论文清单（276 篇论文 + 31 个代码仓库 + 讲解链接）
```

## 🗂️ 内容速览

完整清单见 **[CrowdCounting-Papers-Summary.md](./CrowdCounting-Papers-Summary.md)**，按六大板块组织：

| 板块 | 收录内容 | 数量 |
|---|---|---|
| 一、综述（Survey） | 人群计数领域三篇代表性综述 | 3 篇 |
| 二、按年份分类论文（2012–2026） | 从早期经典到最新成果：2016（MCNN）→ 2018（CSRNet）→ 2019（Bayesian Loss、S-DCNet）→ 2020（DM-Count、LSC-CNN）→ 2021（P2PNet）→ 2022（MAN、TransCrowd）→ 2023（STEERER、PET、CrowdCLIP）→ 2024（CrowdDiff、MPCount、CLIP-EBC）→ 2025–2026（TMTB、P2RLoss 等最新工作） | 156 篇 |
| 三、其他经典论文 | 未按年份归类的经典方法（CAN、GauNet、ChfL、FIDTM、NLT 等） | 26 篇 |
| 四、专题方向论文 | 跨域与域适应 / 点回归框架 / 半监督 / RGB-T 多模态 / 视频人群计数 / 密度图生成 / 白化与风格迁移 / 基础模块 / 轻量化与知识蒸馏 等 11 个子方向 | 91 篇 |
| 五、代码仓库汇总 | 论文对应代码仓库（含官方 / 非官方 / 复现版）与相关开源资源 | 31 + 2 个 |
| 六、论文讲解博客与视频 | Keep_Trying_Go 的 CSDN 博客详解与 B 站视频讲解对应表、扩展阅读、学习资源 | 22 篇博客 + 3 个视频 |

## 🚀 快速开始

| 你想做什么 | 建议入口 |
|---|---|
| 🆕 系统入门人群计数 | 从「一、综述」开始，再按年份顺序精读 2016–2020 经典（MCNN → CSRNet → Bayesian Loss → DM-Count），配合第六部分对应博客讲解 |
| 🔍 查找某篇具体论文 | 打开清单后 `Ctrl+F` 搜索论文名称或简称（如 P2PNet、CLIP-EBC） |
| 🧭 调研某一类方法 | 直接跳到「四、专题方向论文」对应小节（半监督 / RGB-T / 视频 / 点回归 / 轻量化……） |
| 💻 复现某篇论文 | 查看「五、代码仓库汇总」获取官方 / 复现代码链接；带「博客」「视频」标注的论文还配有逐行代码讲解 |
| 📺 看中文视频讲解 | 前往 [B 站视频空间](https://space.bilibili.com/625095571/upload/video)；「六、6.1」给出论文与视频的对应关系 |

## 🔗 配套框架项目

本清单配套一个基于 PyTorch 的人群计数统一框架：

**[KeepTryingTo/CrowdCounting-framework-PyTorch](https://github.com/KeepTryingTo/CrowdCounting-framework-PyTorch)** —— 涵盖**密度图回归**与**点回归**两大类人群计数算法的多种实现（P2PNet、PET、Consistent-Point、P2RLoss、Uncertainty 等），并提供可视化演示应用，可用于论文复现与算法对比实验。

> 💡 建议用法：在清单中选定目标论文 → 通过链接下载论文与官方代码 → 使用配套框架快速跑通基线并开展改进实验。

## 📊 数据统计

- 论文总数：**276 篇**（含综述、数据集论文与相关基础论文），覆盖 2008–2026 年
- 代码仓库：**31 个**（官方 / 非官方 / 复现）
- 中文讲解：**22 篇 CSDN 博客详解**（对应 21 篇收录论文）+ **3 个 B 站视频讲解**（另有 SAM / 文生图等相关视频）
- 链接策略：优先 arXiv / CVF Open Access / DOI 永久链接；极少数无正式链接的论文给出 Google Scholar 检索链接

## 🙏 致谢

- 感谢所有人群计数论文的作者们开源论文与代码；
- 本清单在整理过程中参考并借鉴了 [gjy3035/Awesome-Crowd-Counting](https://github.com/gjy3035/Awesome-Crowd-Counting) 的部分条目与链接，推荐一并关注；
- 感谢 [Keep_Trying_Go](https://blog.csdn.net/Keep_Trying_Go) 提供的高质量中文博客与视频讲解。

## 📌 维护与贡献

- 清单持续更新中，欢迎通过 **Issue / PR** 补充新论文、修正失效链接或完善讲解资源；
- 若清单对你的学习或研究有帮助，欢迎 **Star ⭐** 支持让更多人看到；
- 推荐配合阅读：第六部分「6.3 相关学习资源文章」中的人群计数数据集使用总结与概念辨析。

## 📄 License

本清单文档以 [MIT License](https://opensource.org/licenses/MIT) 开源；所有论文与代码的版权归原作者所有，请遵循其各自的许可协议。
