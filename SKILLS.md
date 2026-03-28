# 📚 Skills 清单

## 已包含的 Skills (8 个)

### 1. Atlassian Skills (236 KB)
**描述：** Jira、Confluence、Bitbucket 集成  
**功能：**
- Jira 问题管理
- Confluence 文档管理
- Bitbucket 代码仓库管理

**文件：**
- SKILL.md - 完整文档
- REFERENCE.md - API 参考
- requirements.txt - Python 依赖
- scripts/ - 20+ 个脚本文件

---

### 2. GitHub Skill
**描述：** GitHub CLI 集成  
**功能：**
- 使用 gh CLI 与 GitHub 交互
- Issue、PR、CI 运行管理
- 高级 API 查询

**文件：**
- SKILL.md - 完整文档
- _meta.json - 元数据

---

### 3. Agent Browser Skill
**描述：** 快速 Rust 浏览器自动化  
**功能：**
- 页面导航、点击、输入
- 快照和截图
- Node.js 回退支持

**文件：**
- SKILL.md - 完整文档
- CONTRIBUTING.md - 贡献指南

---

### 4. Self-Improving Agent Skill
**描述：** 持续学习和改进系统  
**功能：**
- 捕获学习和错误
- 自动改进工作流
- 知识库管理

**文件：**
- SKILL.md - 完整文档 (19.7 KB)
- scripts/ - 自动化脚本
- hooks/ - OpenClaw 集成钩子
- references/ - 示例和集成指南
- assets/ - 模板和学习文件

---

### 5. Find Skills Skill ✨ NEW
**描述：** 发现和安装 Agent Skills  
**功能：**
- 帮助用户发现 Skills
- 搜索功能
- 安装指导

**文件：**
- SKILL.md - 完整文档
- _meta.json - 元数据

---

### 6. Ontology Skill ✨ NEW
**描述：** 类型化知识图谱  
**功能：**
- 结构化记忆管理
- 实体创建和查询
- 依赖链接和约束

**文件：**
- SKILL.md - 完整文档
- scripts/ - Python 脚本
- references/ - 查询和模式文档

---

### 7. Self-Improving Skill ✨ NEW
**描述：** 自我改进和主动代理系统  
**功能：**
- 自我反思和批评
- 自我学习
- 自我组织记忆
- 工作流优化

**文件：**
- SKILL.md - 完整文档
- HEARTBEAT.md - 心跳配置
- 多个参考文档 (corrections, learning, operations 等)

---

### 8. Summarize Skill ✨ NEW
**描述：** URL 和文件摘要  
**功能：**
- 网页摘要
- PDF 摘要
- 图片、音频、YouTube 摘要

**文件：**
- SKILL.md - 完整文档
- _meta.json - 元数据

---

## 📊 统计信息

| Skill | 大小 | 文件数 | 类型 |
|-------|------|--------|------|
| Atlassian | 236 KB | 20+ | Python |
| GitHub | - | 2 | CLI |
| Agent Browser | - | 3 | Rust/Node |
| Self-Improving Agent | 100 KB | 15+ | Shell/JS/TS |
| Find Skills | - | 2 | 工具 |
| Ontology | 52 KB | 5+ | Python |
| Self-Improving | 72 KB | 12+ | 文档 |
| Summarize | 8 KB | 2 | CLI |

**总计：** 8 个 Skills，约 468 KB

---

## 🚀 使用方法

### 安装到 OpenClaw
```bash
cp -r skills/* ~/.qclaw/workspace/skills/
```

### 配置环境变量
```bash
# Atlassian Skills
export JIRA_URL="https://your-instance.atlassian.net"
export JIRA_USERNAME="your-email@example.com"
export JIRA_API_TOKEN="your-api-token"

# GitHub
export GH_TOKEN="your-github-token"
```

### 使用 Skills
```bash
# 在 OpenClaw 中使用
# 每个 skill 都可以通过 SKILL.md 中的说明使用
```

---

## 🎓 Skills 分类

### 工作流自动化
- Atlassian Skills - Jira/Confluence/Bitbucket
- GitHub Skill - GitHub 管理
- Agent Browser - 网页自动化

### 学习和改进
- Self-Improving Agent - 错误和学习记录
- Self-Improving - 工作流优化
- Ontology - 知识管理

### 工具和发现
- Find Skills - 发现 Skills
- Summarize - 内容摘要

---

## 📝 下一步

- [ ] 添加更多 skills
- [ ] 创建 skill 模板
- [ ] 设置 GitHub Actions
- [ ] 发布到 ClawHub
- [ ] 编写使用指南

---

## 🔗 相关链接

- [Atlassian Skills](skills/atlassian-skills/SKILL.md)
- [GitHub Skill](skills/github/SKILL.md)
- [Agent Browser Skill](skills/agent-browser/SKILL.md)
- [Self-Improving Agent Skill](skills/self-improving-agent/SKILL.md)
- [Find Skills](skills/find-skills/SKILL.md)
- [Ontology](skills/ontology/SKILL.md)
- [Self-Improving](skills/self-improving/SKILL.md)
- [Summarize](skills/summarize/SKILL.md)

---

**更新时间：** 2026-03-28
