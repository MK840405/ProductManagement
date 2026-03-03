# 产品管理系统

## 项目介绍

这是一个全面的产品生命周期管理平台，旨在帮助团队高效管理产品信息、跟踪需求进展、监控项目进度，并通过数据分析驱动决策。

## 项目结构

```
ProductManagement/
├── docs/                          # 📁 产品级文档
│   ├── README.md                  # 本文件 - 项目导航
│   ├── architecture.md            # 🏗️ [技术架构设计](architecture.md)
│   └── product-overview.md        # 📋 [产品规格总览](product-overview.md)
├── specs/                         # 📁 功能规格文档
│   └── 001-product-management/    # [产品管理系统功能规格](../specs/001-product-management/spec.md)
├── .specify/                      # ⚙️ speckit工作流配置
│   ├── memory/                    # 📚 项目记忆和模板
│   ├── scripts/                   # 🔧 自动化脚本
│   └── templates/                 # 📄 文档模板
└── .windsurf/workflows/           # 🔄 speckit工作流定义
```

## 快速导航

### 📖 产品文档
- **[产品概述](product-overview.md)** - 产品级需求规格和核心功能
- **[技术架构](architecture.md)** - 系统架构设计和技术选型

### 📝 功能规格
- **[产品管理系统](../specs/001-product-management/spec.md)** - 具体功能实现规格
- **[质量检查清单](../specs/001-product-management/checklists/requirements.md)** - 规格质量验证

### ⚙️ 开发工具
- **[speckit工作流](../.windsurf/workflows/)** - 规范化开发流程
  - [`/speckit.specify`](../.windsurf/workflows/speckit.specify.md) - 创建功能规格
  - [`/speckit.clarify`](../.windsurf/workflows/speckit.clarify.md) - 澄清需求细节
  - [`/speckit.plan`](../.windsurf/workflows/speckit.plan.md) - 设计技术方案
  - [`/speckit.tasks`](../.windsurf/workflows/speckit.tasks.md) - 分解开发任务

## 开发状态

| 模块 | 状态 | 文档 |
|------|------|------|
| 产品信息管理 | 🟡 规格中 | [spec.md](../specs/001-product-management/spec.md) |
| 需求跟踪管理 | 🟡 规格中 | [spec.md](../specs/001-product-management/spec.md) |
| 项目进度监控 | 🟡 规格中 | [spec.md](../specs/001-product-management/spec.md) |
| 数据分析可视化 | 🟡 规格中 | [spec.md](../specs/001-product-management/spec.md) |

## 开发指南

### 1. 新功能开发
```bash
# 创建新功能规格
/speckit.specify "功能描述"

# 澄清需求细节
/speckit.clarify

# 设计技术方案
/speckit.plan

# 分解开发任务
/speckit.tasks
```

### 2. 文档维护
- 产品级文档更新：直接编辑 `docs/` 目录下的文件
- 功能规格更新：通过 speckit 工作流
- 提交前确保所有文档同步更新

### 3. 质量保证
- 每个功能规格都有对应的[质量检查清单](../specs/001-product-management/checklists/requirements.md)
- 代码提交前必须通过完整测试
- 文档与代码保持同步

## 项目信息

- **维护者**: MK
- **开始时间**: 2026-03-03
- **开发框架**: speckit规范化开发流程
- **代码仓库**: [GitHub](https://github.com/MK840405/ProductManagement)

## 相关链接

- [项目章程](../.specify/memory/constitution.md) - 开发原则和规范
- [GitHub Issues](https://github.com/MK840405/ProductManagement/issues) - 问题反馈
- [提交历史](https://github.com/MK840405/ProductManagement/commits/main) - 开发记录

---

**最后更新**: 2026-03-03  
**文档版本**: v1.0
