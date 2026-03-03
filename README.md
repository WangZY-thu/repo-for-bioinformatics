# repo-for-bioinformatics
this is a repository for my  bioinformatics lesson

## 功能 Features
- 课程笔记与知识整理
- 作业与实验可复现
- 数据分析与可视化的可追溯
- 环境管理
- 报告/实验记录

## 目录结构 Structure
bioinfo-course/
├─ README.md
├─ LICENSE                    # 可选：MIT
├─ .gitignore
├─ environment.yml            # 或 requirements.txt（二选一）
├─ docs/                      # 文档与课程笔记（可直接当知识库）
│  ├─ syllabus.md
│  ├─ notes/
│  │  ├─ 01-sequencing.md
│  │  ├─ 02-alignment.md
│  │  ├─ 03-variant-calling.md
│  │  └─ ...
│  └─ cheatsheets/
│     ├─ bash-one-liners.md
│     ├─ bioinfo-tools.md
│     └─ stats-ml.md
├─ assignments/               # 作业（按作业编号/主题归档）
│  ├─ hw01/
│  │  ├─ README.md            # 作业说明、任务、结论
│  │  ├─ data/                # hw01 专用小数据（可提交）
│  │  ├─ src/                 # hw01 代码
│  │  ├─ notebooks/           # 分析过程（可选）
│  │  └─ outputs/             # 图表/结果（可提交）
│  └─ hw02/
├─ projects/                  # 课程大作业/mini project
│  └─ project1-rnaseq/
│     ├─ README.md
│     ├─ data/
│     ├─ src/
│     ├─ notebooks/
│     ├─ configs/             # 参数配置（非常推荐）
│     └─ outputs/
├─ src/                       # 你自己沉淀的通用代码（可复用库）
│  ├─ __init__.py
│  ├─ io_fasta.py
│  ├─ qc.py
│  ├─ stats.py
│  └─ plotting.py
├─ scripts/                   # 可执行脚本：跑流程、下载数据、批处理
│  ├─ setup_env.sh
│  ├─ download_example_data.sh
│  └─ run_hw01.sh
├─ data/                      # 全局共享的数据（谨慎提交）
│  ├─ raw/                    # 原始数据（一般不提交大文件）
│  ├─ interim/                # 中间数据
│  └─ processed/              # 处理后的可复现实验数据（可选择提交小样本）
└─ outputs/                   # 全局输出（图表、表格、日志）
   ├─ figures/
   ├─ tables/
   └─ logs/
