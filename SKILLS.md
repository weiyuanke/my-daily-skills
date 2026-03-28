# 📚 Skills 清单

## 已添加的 Skills

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
- .env.example - 环境变量示例

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

### 3. Gmail Skill
**描述：** Gmail API 集成  
**功能：**
- 读取、发送、管理邮件
- 线程和标签管理
- 草稿管理

**文件：**
- SKILL.md - 完整文档
- LICENSE.txt - 许可证
- _meta.json - 元数据

---

### 4. OpenAI Whisper Skill
**描述：** 本地语音转文字  
**功能：**
- 无需 API Key 的本地 STT
- 支持多种音频格式
- 高精度转录

**文件：**
- SKILL.md - 完整文档
- _meta.json - 元数据

---

### 5. Agent Browser Skill
**描述：** 快速 Rust 浏览器自动化  
**功能：**
- 页面导航、点击、输入
- 快照和截图
- Node.js 回退支持

**文件：**
- SKILL.md - 完整文档
- CONTRIBUTING.md - 贡献指南
- _meta.json - 元数据

---

## 📊 统计信息

| Skill | 大小 | 文件数 | 类型 |
|-------|------|--------|------|
| Atlassian | 236 KB | 20+ | Python |
| GitHub | - | 2 | CLI |
| Gmail | - | 3 | API |
| Whisper | - | 2 | CLI |
| Agent Browser | - | 3 | Rust/Node |

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

# Gmail
export GMAIL_CREDENTIALS="path/to/credentials.json"

# GitHub
export GH_TOKEN="your-github-token"
```

### 使用 Skills
```bash
# 在 OpenClaw 中使用
# 每个 skill 都可以通过 SKILL.md 中的说明使用
```

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
- [Gmail Skill](skills/gmail/SKILL.md)
- [Whisper Skill](skills/openai-whisper/SKILL.md)
- [Agent Browser Skill](skills/agent-browser/SKILL.md)

---

**更新时间：** 2026-03-28
