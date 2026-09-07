# ✈️ Travel Plans

个人旅行计划仓库。每个目的地/行程作为一个独立子文件夹，内含自包含的 HTML 计划页面。

## 目录结构

```
travel-plans/
├── index.html                        # 总入口（列出所有行程）
├── README.md
└── 2026-australia-newzealand/        # 一次行程 = 一个子文件夹
    └── index.html                    # 该行程的完整计划页
```

## 扩展方式

后续新增行程有两种方式，二选一：

1. **子文件夹（推荐，集中管理）**：在本仓库新建 `YYYY-<destination>/index.html`，并在根 `index.html` 增加一个入口卡片。
2. **独立仓库**：为某个大行程单独建一个仓库，命名如 `travel-<destination>`。

## 当前行程

| 行程 | 时间 | 路线 | 页面 |
|------|------|------|------|
| 澳大利亚 + 新西兰 | 2026-10-01 ~ 10-11 | 北京→悉尼→皇后镇→悉尼转机→北京 | [2026-australia-newzealand](./2026-australia-newzealand/index.html) |

## 本地预览

直接用浏览器打开对应的 `index.html` 即可；无需构建，纯静态单文件。
