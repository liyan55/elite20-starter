# Elite20 学习指南

## 目录
1. Elite20 挑战提交规范
2. GitHub 仓库管理
3. AI 论文写作工具
4. 技能使用指南

---

## 一、Elite20 挑战提交规范

### 核心要求
- **一句话规则**：可复现的产出 + 可追溯的 AI 日志 + 可验证的"拿来"说明
- **审核流程**：G1（人审思路）→ G2（AI 审证据）→ G3（人审完成）
- **三条红线**：AI 日志缺失/伪造、伪拿来主义、不可复现

### 证据账本
```
证据账本包含：
├── AI 对话日志
├── REUSE.md（拿来主义说明）
├── 实验日志
└── Portfolio 条目
```

### 提交检查清单
- [ ] 可复现的产出
- [ ] AI 日志完整
- [ ] REUSE.md 完整
- [ ] 通过 G1 方案背书
- [ ] 无"三条红线"违规

---

## 二、GitHub 仓库管理

### 仓库地址
- **精英20 starter**：https://github.com/liyan55/elite20-starter

### 常用命令
```bash
# 克隆仓库
git clone https://github.com/liyan55/elite20-starter.git

# 添加文件
git add .

# 提交更改
git commit -m "提交信息"

# 推送到远程
git push origin main
```

### Commit 规范
- `feat:` 新功能
- `docs:` 文档更新
- `fix:` bug 修复
- `refactor:` 代码重构

---

## 三、AI 论文写作工具

### 推荐资源
- **awesome-ai-research-writing**: https://github.com/Leey21/awesome-ai-research-writing

### 核心功能
| 功能 | 用途 |
|------|------|
| 中转英 | 中文→英文学术论文 |
| 英转中 | 英文论文翻译 |
| 表达润色 | 优化语言表达 |
| 逻辑检查 | 检查逻辑漏洞 |
| arxiv-translator-skill | ArXiv 论文翻译 |

### 使用方法
1. 访问 GitHub 仓库
2. 复制需要的 Prompt
3. 粘贴到 AI 工具中使用

---

## 四、技能使用指南

### 可用技能
| 技能 ID | 功能 |
|---------|------|
| ai_code_helper | AI 代码助手 |
| document_generator | 文档生成器 |
| code_reviewer | 代码审查工具 |
| data_visualizer | 数据可视化工具 |
| test_generator | 测试生成器 |

### 调用流程
```python
from elite20.skills import SkillName

skill = SkillName()
result = skill.method_name(param1, param2)
print(result)
```

### 日志记录要求
每次调用技能必须记录：
- 调用时间
- 技能 ID
- 输入参数
- 输出结果
- 执行时长

---

## 五、学习进度跟踪

### 已完成任务
- [x] Fork elite20-starter 仓库
- [x] 创建 3 个 Commit
- [x] 阅读 SKILL.md
- [x] 学习代码审查技能

### 待学习内容
- [ ] 实践代码审查
- [ ] 学习其他技能
- [ ] 完成第一个挑战任务

---

## 六、快速参考

### Elite20 规范速查
- 审核门：G1→G2→G3
- 资源阈值：¥70 RMB
- 证据账本：4 个核心文件

### 常用链接
- Elite20 学习指南：当前文件
- GitHub 仓库：https://github.com/liyan55/elite20-starter
- 论文写作工具：https://github.com/Leey21/awesome-ai-research-writing

---

**最后更新**：2024-01-17  
**版本**：v1.0