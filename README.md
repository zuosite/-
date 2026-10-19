# 引火生气盲派 · 实战断盘 skill

一套**完全采信盲派命理**的实战断盘体系，从「定旺衰 → 定喜忌用神」十步链直接落地断盘，不夹学术免责、不做学说中立。

## 体系要点

- **十步链**：①定旺衰 ②分家里家外 ③寻根基出处 ④分体用 ⑤找做工 ⑥比力量 ⑦定格局 ⑧断职业 ⑨走运 ⑩定喜忌用神
- **十五铁则**：印≠学历、官杀得根三路、冲转伤只担保转伤不担保落点、唯一根优先于紧贴……（详见手册）
- **结论先行**：输出流程前先给「喜忌用神」结论，再走盘
- **实战手册**：`references/实战断盘手册.md` 为可落地断盘总纲；`references/校准日志.md` 为逐册 6296 例校准记录

## 安装

### 方式一：git clone（推荐，一句话）

```bash
git clone <本仓库URL> ~/.workbuddy/skills/yinhuo-shengqi-mangpai
```

装完重启 WorkBuddy（或开新对话）即生效，对所有项目可用。

### 方式二：自包含安装脚本（离线、零依赖）

把仓库里的 `install-yinhuo-skill.sh` 内容复制到目标机器，执行：

```bash
bash install-yinhuo-skill.sh
```

该脚本将整个 skill 以 tar.gz+base64 内嵌，无需网络、无需 API。

## 目录结构

```
yinhuo-shengqi-mangpai/
├── SKILL.md                 # 技能入口（WorkBuddy 自动识别）
├── README.md               # 本文件
└── references/
    ├── 实战断盘手册.md       # 可落地断盘体系总纲
    └── 校准日志.md           # 逐册校准记录
```

## 使用

在 WorkBuddy 对话中直接说"用引火生气盲派走一下我的盘"，并给出四柱（年月日时＋性别）即可。
