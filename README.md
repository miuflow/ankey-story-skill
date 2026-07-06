# Ankey Story Skill / Ankey 故事技能

> An opencode skill for generating personalized SEL children's stories.
> 一个用于生成个性化 SEL 儿童故事的 opencode 技能。

Part of [Ankey (小锚)](https://www.miuflow.com/ankey/) — turn life moments into storytime strength.
属于 [Ankey（小锚）](https://www.miuflow.com/ankey/)——把生活瞬间变成故事力量。

## Usage / 使用方式

Load the skill in opencode:

```
/skill ankey-story-skill
```

Or reference the SKILL.md file directly in your agent's configuration.

## Contents / 内容

| File / 文件 | Purpose / 用途 |
|-------------|----------------|
| `SKILL.md` | Main skill definition / 主技能定义，agent 加载入口 |
| `METHODOLOGY.md` | Life Anchor theory + SEL framework / 方法论说明 |

## Prerequisites / 前置条件

- An LLM capable of following structured prompts (DeepSeek, GPT-4, Claude, etc.)
- The Ankey Story Prompts (optional, skill includes core methodology):
  https://github.com/miuflow/ankey-story-prompts

## License / 许可证

MIT
