repo-for-bioinformatics/
├─ README.md
├─ .gitignore
├─ environment.yml            # 或 requirements.txt（二选一）
├─ docs/                      # 课程笔记与知识整理
│  ├─ syllabus.md
│  ├─ notes/
│  │  ├─ 01-sequencing.md
│  │  ├─ 02-alignment.md
│  │  └─ 03-variant-calling.md
│  └─ cheatsheets/
│     ├─ bash-one-liners.md
│     └─ bioinfo-tools.md
├─ assignments/               # 作业（按作业编号/主题）
│  └─ hw01/
│     ├─ README.md
│     ├─ data/
│     ├─ src/
│     ├─ notebooks/
│     └─ outputs/
├─ projects/                  # 课程 mini project / 大作业
│  └─ project1-rnaseq/
│     ├─ README.md
│     ├─ data/
│     ├─ src/
│     ├─ notebooks/
│     ├─ configs/
│     └─ outputs/
├─ src/                       # 你沉淀的通用代码（可复用库）
├─ scripts/                   # 可执行脚本：下载/跑流程/批处理
├─ data/                      # 全局共享数据（谨慎提交大文件）
│  ├─ raw/
│  ├─ interim/
│  └─ processed/
└─ outputs/                   # 全局输出：图表/表格/日志
   ├─ figures/
   ├─ tables/
   └─ logs/
