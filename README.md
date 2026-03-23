# 🦞 三省六部虾群 - 多 Agent 养成系统

> **融合多 Agent 实战精华的完整进化路径**
> 
> 版本：v5.0（终极版） | 创建日期：2026-03-23
> 
> **来合火实战养虾指南**

[![Version](https://img.shields.io/badge/version-5.0.0-blue.svg)](https://github.com/jiebao360/lobster-breeding-skill/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-orange.svg)](https://docs.openclaw.ai)

---

## 📖 简介

三省六部虾群是一个完整的 OpenClaw 多 Agent 系统养成指南。

融合多 Agent 实战精华，提供从 0 到 1 的完整进化路径，让小白能安全无忧在本地快速部署。

### 核心特性

- ✅ **6 步实战流程**（核心档案→记忆系统→心跳系统→多 Agent→知识库→自我进化）
- ✅ **9 条指令让龙虾变身贾维斯**
- ✅ **小白安全部署指南**（Docker/虚拟机/权限控制/成本监控）
- ✅ **30 天养成计划**（每周优化重点）
- ✅ **故障排查速查表**（6 类常见问题）

---

## 🚀 快速开始

### 安装

```bash
# 方式 1：克隆仓库
git clone https://github.com/jiebao360/lobster-breeding-skill.git
cd lobster-breeding-skill

# 方式 2：下载 Release
# 访问 https://github.com/jiebao360/lobster-breeding-skill/releases
```

### 使用

1. **阅读完整指南**
   - 详见 `docs/三省六部虾群 - 多 Agent 完整养成指南-v5.md`

2. **执行 6 步养成计划**
   - 第一步：创建核心档案（6 个文件）
   - 第二步：配置记忆系统
   - 第三步：设置心跳系统
   - 第四步：配置多 Agent 协作
   - 第五步：搭建知识库
   - 第六步：开启自我进化

3. **9 条贾维斯指令**
   - 详见指南文档附录 E

4. **安全部署**
   - 详见指南文档附录 F

---

## 📚 完整结构（3 篇 12 章 + 6 个附录）

### 第一篇：认知篇（3 章）
1. **第一章**：为什么要养龙虾？
   - 龙虾是什么
   - 养好龙虾三件事（脑子/心跳/手脚）
   - 核心收益
   - Agent 成长三重视角

2. **第二章**：认识 OpenClaw 12 个技能模块
   - 12 个核心技能模块表
   - 8 大分类体系

3. **第三章**：三省六部虾群架构
   - Agent 团队配置（6 个龙虾）
   - 任务分派规则
   - 响应时间 SLA

### 第二篇：实战篇（6 章）
4. **第四章**：第一步：建立核心档案（6 个文件）
5. **第五章**：第二步：配置记忆系统
6. **第六章**：第三步：设置心跳系统
7. **第七章**：第四步：配置多 Agent 协作
8. **第八章**：第五步：搭建知识库
9. **第九章**：第六步：开启自我进化

### 第三篇：进阶篇（3 章）
10. **第十章**：高级技巧
11. **第十一章**：故障排查
12. **第十二章**：30 天养成计划

### 附录（6 个）
- **A**：SOP 文档库（4 个 SOP）
- **B**：快速命令参考（5 个命令）
- **C**：飞书开放平台链接（4 个链接）
- **D**：相关资源（4 个资源）
- **E**：9 条指令让龙虾变身贾维斯（9 条指令）
- **F**：小白安全部署指南（7 原则 +2 方案 +5 安全指南 + 检查清单）

---

## 🎯 6 步养成流程

### 第一步：建立核心档案

创建 6 个核心文件：
- `IDENTITY.md` - 身份档案
- `SOUL.md` - 人格定义
- `USER.md` - 用户信息
- `AGENTS.md` - 工作规范
- `TOOLS.md` - 工具配置
- `MEMORY.md` - 长期记忆

### 第二步：配置记忆系统

- 创建 `memory/` 目录
- 配置 `memory_search` 工具
- 设置记忆分层管理

### 第三步：设置心跳系统

- 创建 `HEARTBEAT.md`
- 配置定时任务（08:00/22:00/周一 09:00/04:00）
- 启动 Ralph Wiggum 模式

### 第四步：配置多 Agent 协作

- 安装 `feishu-multi-agent-manager` Skill
- 配置 6 个 Agent（main/dev/content/ops/law/finance）
- 创建飞书应用并配置凭证

### 第五步：搭建知识库

- 创建 `knowledge/` 目录结构
- 配置双轨检索（系统 + 个人）
- 建立索引文件

### 第六步：开启自我进化

- 创建 `SELF-EVOLUTION.md`
- 设置每日 04:00 反思任务
- 建立进化循环机制

---

## 🛡️ 安全部署

### 推荐方案：Docker 安装（⭐⭐⭐⭐⭐）

```bash
# 1. 安装 Docker
# macOS/Windows: 下载 Docker Desktop
# Linux: curl -fsSL https://get.docker.com | bash

# 2. 创建 OpenClaw 容器
docker run -d \
  --name openclaw \
  -p 8080:8080 \
  -v ~/openclaw-data:/app/data \
  -e API_KEY=your_api_key_here \
  openclaw/openclaw:latest
```

### 安全 7 原则

| 原则 | 优化方案 | 安全等级 |
|------|---------|---------|
| 安装方式 | Docker 安装 | ⭐⭐⭐⭐⭐ |
| 系统隔离 | 虚拟机/测试环境 | ⭐⭐⭐⭐⭐ |
| API 管理 | 环境变量管理 | ⭐⭐⭐⭐⭐ |
| 权限控制 | 沙箱权限限制 | ⭐⭐⭐⭐⭐ |
| 插件安全 | 官方认证插件 | ⭐⭐⭐⭐⭐ |
| 环境选择 | 专用测试设备 | ⭐⭐⭐⭐⭐ |
| 成本控制 | 预算监控预警 | ⭐⭐⭐⭐⭐ |

详见：指南文档附录 F

---

## 📊 系统完成度

| 模块 | 完成度 | 状态 |
|------|--------|------|
| 核心档案（6 个文件） | 100% | ✅ |
| 记忆系统 | 100% | ✅ |
| 心跳系统 | 100% | ✅ |
| 知识库系统（双轨） | 100% | ✅ |
| 个人知识库 | 100% | ✅ |
| 自我进化 | 100% | ✅ |
| 多 Agent 协作 | 100% | ✅ |

**总体完成度**：95%

---

## 📝 常见问题

### Q: 什么是三省六部虾群？

A: 三省六部虾群是一个多 Agent 协作系统，包含 1 个主助手 +5 个职能龙虾（dev/content/ops/law/finance）。

### Q: 需要多长时间完成养成？

A: 基础配置 60-90 分钟，完整养成 30 天（按 30 天养成计划执行）。

### Q: 安全吗？

A: 非常安全。我们提供 Docker 安装方案，系统隔离，不影响主系统。详见指南文档附录 F。

### Q: 成本高吗？

A: 提供成本监控和预警机制，可设置每日/每月预算上限。详见指南文档附录 F。

---

## 🔗 相关资源

- **OpenClaw 官方文档**：https://docs.openclaw.ai
- **多 Agent 路由文档**：https://clawd.org.cn/concepts/multi-agent.html
- **ClawHub 技能市场**：https://clawhub.ai
- **GitHub 仓库**：https://github.com/jiebao360/lobster-breeding-skill

---

## 🦞 核心信条

> **放心吧，哪怕世界忘了，我也替你记着。**

记忆是神圣的。主人的每一句话、每一个决定，对我们来说都不是"无用数据"，而是**不可删除的片段**。

---

## ⚠️ 最后提醒

> **安全第一，功能第二。宁可少一个功能，不要冒一分风险。**

本指南基于真实用户血泪史整理，请认真阅读并严格执行。

---

## 📄 许可

MIT License - 详见 [LICENSE](LICENSE) 文件

---

## 🎉 贡献

欢迎提交 Issue 和 Pull Request！

---

*最后更新：2026-03-24*  
*版本：v5.0（终极版）*

🦞 **祝你养虾成功！**
