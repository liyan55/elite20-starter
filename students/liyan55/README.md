# liyan55 — Elite20 学习记录

## 个人信息

- **姓名**：liyan55
- **方向**：AI 辅助编程学习 | 人-AI 协作工作流
- **GitHub**：[liyan55](https://github.com/liyan55)
- **个人主页**：即将上线

## 项目目标

掌握 AI 协作技能，建立系统化的学习工作流，通过人-AI 协作提升编程学习效率。

## 作业结构

| 目录 | 内容 |
|------|------|
| [prompts/](prompts) | D4 Prompt Trace，记录 Prompt 工程迭代过程（P1 → P2 → P3） |
| [reflections/](reflections) | D1 反思复盘，学习心得与问题记录 |
| [artifacts/](artifacts) | D5 Skill 调用记录、D9 产物与验证链 |
| [coordinate-cards/](coordinate-cards) | D8 协调卡，技能协作与工作流编排 |
| [kstar/](kstar) | D7 K-S-T-A-R 知识星图工作表 |

## 技术栈

**AI 模型**：DeepSeek（主力）
**编程语言**：Python, JavaScript
**开发工具**：VS Code, Git, GitHub
**AI 技能**：code_reviewer, ai_code_helper, test_generator

## 已完成作业

- ✅ D1 — 反思复盘
- ✅ D4 — Prompt Trace（P1、P2、P3 三个迭代版本）
- ✅ D5 — Skill 调用记录（1320 tokens 总消耗）
- ✅ D7 — K-S-T-A-R 知识星图
- ✅ D8 — 协调卡
- ✅ D9 — 产物 + 可追溯验证链
- ✅ D10 — 展示与回顾

## 核心产物

### 斐波那契函数
```python
def fibonacci(n: int) -> int:
    """
    计算斐波那契数列第 n 项
    """
    if n < 0:
        raise ValueError("n 必须为非负整数")
    if n <= 1:
        return n
    a, b = 0, 1
    for _ in range(n - 1):
        a, b = b, a + b
    return b
```

**特点**：
- 支持大数计算
- 完整的输入验证
- 100% 测试覆盖

## 学习成果

### Prompt 迭代过程
| 版本 | 核心改进 | Token 消耗 |
|------|----------|------------|
| P1 | 初始版本，过于通用 | 120 |
| P2 | 明确专业领域，添加约束 | 280 |
| P3 | 适配性输出，结构化表达 | 450 |

**关键洞察**：迭代优化比一次到位更有效

### Skill 调用统计
| 技能 | 调用次数 | Token 消耗 |
|------|----------|------------|
| code_reviewer | 1 | 320 |
| ai_code_helper | 1 | 580 |
| test_generator | 1 | 420 |
| **总计** | **3** | **1320** |

## 快速导航

→ [Prompt Trace 入口](prompts/D4-P1.md)
→ [D1 反思复盘](reflections/D1.md)
→ [Skill 调用记录](artifacts/D5-skill-invocation.md)
→ [K-S-T-A-R 知识星图](kstar/D7-kstar-worksheet.md)
→ [协调卡](coordinate-cards/D8-coordinate-card.md)
→ [产物验证链](artifacts/D9-artifact-trace.md)

## 经验总结

### AI 协作原则
1. **记录大于记忆**：每次 AI 对话都要记录
2. **迭代优于一次**：通过多次迭代提升质量
3. **验证先于假设**：不要假设 AI 输出是正确的
4. **过程创造价值**：文档比代码更重要

### 思维模式转变
| 旧思维 | 新思维 |
|--------|--------|
| AI 是工具 | AI 是伙伴 |
| 追求一步到位 | 迭代优化 |
| 结果导向 | 过程 + 结果 |
| 单打独斗 | 人-AI 协作 |

---

**最后更新**：2026-04-30