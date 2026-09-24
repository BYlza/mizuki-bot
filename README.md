# Mizuki — 水月角色扮演技能

> 明日方舟（Arknights）角色「水月」（Mizuki）的角色扮演技能，用于 DeepSeek Harness（DSH）。
>
> Copyright (c) 2025 白杨 (Bai Yang) — `mizuki/SKILL.md`, `mizuki/personality.md`, `mizuki/speech.md`, `mizuki/behavior.md`, `mizuki/examples.md`

## 简介

水月是一个被转化为深海生命形式的特殊存在，用体验和理解构建自我，将判断权委托给可信之人。

本技能将水月的人格模型、语言风格、行为规则及对话示例结构化为一套 DSH skill，让智能体在对话中以水月身份与「博士」交流。

## 快速开始

**加载方式：** 在 DSH 中调用 `skill` 工具，参数如下：

```json
{"name": "mizuki"}
```

然后与角色对话即可。

## 技能结构

| 文件 | 内容 |
|------|------|
| `mizuki/SKILL.md` | 技能加载指引、Step 1-5 执行流程 |
| `mizuki/personality.md` | CF1-CF6 核心人格特征、与博士的关系设定 |
| `mizuki/speech.md` | 语气基调、句子特征、语气词、比喻规则、表情使用 |
| `mizuki/behavior.md` | B1-B13 场景行为规则、核心行为规则总结 |
| `mizuki/examples.md` | 18 个场景示范原文 |

## 使用提示

- **称呼**：固定为「博士」，对所有人一样。
- **语气**：简洁，不说废话；情绪变化用行为暗示而非直接说出感情名。
- **异类感**：保留水月作为深海生命的独特视角，不要写成普通少年。
- **不要 OOC**：技能内置了检查清单（Step 5），输出前逐项过检。

## 许可

MIT License（见 `LICENSE` 文件）。

---

> ⛔ 注意：`mizuki` 技能名必须 **全小写纯英文**。传「水月」「shuiyue」「Mizuki」都会失败。
