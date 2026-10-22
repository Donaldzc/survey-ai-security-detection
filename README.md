# AI 赋能的软件与系统安全检测综述 — 数据与代码仓库

本仓库为综述论文《AI赋能的软件与系统安全检测综述：从代码表示到威胁感知》的配套数据仓库，公开 PRISMA 文献筛选记录、纳入文献清单与 Bibliometric 图表源文件。

## 论文摘要

本文遵循 PRISMA 2020 流程，对 2018 年 1 月至 2025 年 3 月期间发表于网络与软件安全领域顶级会议和期刊的 112 篇文献进行系统性综述。通过主题综合分析揭示五大核心发现，并提出覆盖检测时机、检测粒度与技术范式的三维六面分类框架。

## 文献筛选统计（PRISMA）

| 阶段 | 数量 |
|------|------|
| 数据库初检 | 1,247 |
| 去除重复 | 203 |
| 标题/摘要筛选后排除 | 732 |
| 全文评审 | 312 |
| 排除 | 200 |
| **最终纳入** | **112** |

**评审一致性**：两位作者独立评审，首轮一致率 89.1%（278/312），分歧 34 篇由第三位作者仲裁，全流程 Cohen's κ = 0.87（p < 0.001）。

**纳入文献来源分布**：CCF-A 会议 52 篇（46.4%）、CCF-B 会议 28 篇（25.0%）、SCI 期刊 32 篇（28.6%）。

## 仓库结构

```
survey-ai-security-detection/
├── README.md                    # 本文件
├── literature_list.csv          # 112 篇纳入文献清单
├── excluded_papers_full_list.csv# 200 篇排除文献清单（含 E1–E5 编码）
├── prisma/
│   ├── search_strategy.md       # 检索式、检索来源、时间窗
│   ├── screening_log.csv        # 筛选记录表
│   └── kappa_calculation.csv    # Cohen's κ 计算表
└── figures/
    ├── PRISMA流程图.html        # Fig.1 PRISMA 2020 流程图
    └── Bibliometric图表.html    # Fig.2–4 年度分布、来源分布、技术路线
```

## 开源链接核验状态

| 文献 | 链接 | 状态 |
|------|------|------|
| CodeBERT / GraphCodeBERT | https://github.com/microsoft/CodeBERT | ✅ 官方仓库 |
| Kitsune | https://github.com/ymirsky/Kitsune-py | ✅ 原作者仓库 |
| LineVD | https://github.com/davidhin/linevd | ✅ 作者仓库 |
| Devign | https://github.com/epicosy/devign | ⚠️ 第三方复现（官方未开源） |
| ReVeal | https://github.com/VulDetProject/ReVeal | ✅ 作者仓库 |
| DeepWukong | https://github.com/jumormt/DeepWukong | ✅ 作者仓库 |
| LogPPT | https://github.com/LogIntelligence/LogPPT | ✅ 作者仓库 |

## 可复现性统计（基于 112 篇纳入文献）

| 类别 | 占比 |
|------|------|
| 开源代码 | 69.6% |
| 公开数据集 | 79.5% |
| Docker 镜像 | 16.1% |
| 完全不可复现 | 10.7% |

## 引用

如使用本仓库数据，请引用本综述论文。

```
[待补充：论文引用信息]
```

仓库地址：https://github.com/Donaldzc/survey-ai-security-detection

## 数据更新

仓库随新文献发表持续更新，最近更新：2026-10-22
