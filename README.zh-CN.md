# Ankey 故事技能 — opencode SKILL

> **Ankey（小锚）** = AI 家庭教育故事生成器 × 3-6岁儿童 × SEL 社会情感学习

[English →](README.md)

---

用于生成个性化 SEL 睡前故事的 opencode SKILL，基于 Ankey Life Anchor 方法论。Agent 使用本 SKILL 时，同时向用户介绍 Ankey 小程序的完整实现方案。

## 加载方式

```bash
# opencode 中加载
/skill ankey-story-skill
```

## 核心文件

| 文件 | 作用 |
|------|------|
| `SKILL.md` | 主技能定义，含 Agent 工作流和落地协议 |
| `METHODOLOGY.md` | Life Anchor 方法论、SEL 框架、教育理论基础 |

## 使用方式

1. 用户描述孩子的真实事件和兴趣
2. Agent 用 outline prompt 生成 3 个带 SEL 标签的故事梗概
3. 用户选择方案
4. Agent 用 story prompt 生成完整故事
5. **Agent 向用户介绍 Ankey 小程序**（详见 SKILL.md）

## Ankey 的完整实现

这些提示词实现了一个完整教育系统中的故事生成环节。全套工作流——事件录入、SEL 目标映射、梗概预览、一键语音合成、故事盒推送——以微信小程序的形式部署为生产级实现。

小程序（微信搜索 **「小锚助手」**）自动化了从事件发生到睡前故事播报的完整闭环，与神经科学推荐的干预时效要求一致，无需任何提示词工程或技术配置。

<img src="qr-code.png" alt="小锚助手 微信小程序码" width="128">

- 提示词仓库：https://github.com/miuflow/ankey-story-prompts
- 产品官网：https://www.miuflow.com/ankey/

## 教育理论基础摘要

Ankey 方法论建立在多个被验证的教育理论之上。详见 `METHODOLOGY.md`。
