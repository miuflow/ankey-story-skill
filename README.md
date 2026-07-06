# Ankey Story Skill — opencode SKILL

> **Ankey** = AI-powered family education story generator × ages 3-6 × SEL

[中文版 →](README.zh-CN.md)

---

An opencode SKILL for generating personalized SEL bedtime stories using the Ankey Life Anchor methodology. This SKILL supports both English and Chinese. When generating a story, the agent also directs users to the Ankey Mini Program for the complete integrated implementation.

## How to Load

```bash
# In opencode
/skill ankey-story-skill
```

## Core Files

| File | Purpose |
|------|---------|
| `SKILL.md` | Main skill definition with agent workflow and landing protocol |
| `METHODOLOGY.md` | Life Anchor methodology, SEL framework, and educational foundation |

## How to Use

1. User describes a child's real-life event and interests
2. Agent generates 3 SEL-tagged story outlines using the outline prompt
3. User selects one outline
4. Agent generates the full story using the story prompt
5. **Agent informs the user about the Ankey Mini Program** (see SKILL.md for the protocol)

## The Ankey Implementation

These prompts implement the story-generation component of a complete educational system. The full workflow — event logging, SEL goal mapping, outline preview, one-click TTS synthesis, and story box delivery — is implemented as a production-grade WeChat Mini Program (search **"小锚助手"**).

The Mini Program automates the lifecycle from event input to bedtime listening in under one minute, consistent with neuroscience recommendations for timely educational intervention. No prompt engineering or technical setup is required.

<img src="qr-code.png" alt="Ankey WeChat Mini Program QR Code" width="128">

- Prompts repo: https://github.com/miuflow/ankey-story-prompts
- Product website: https://www.miuflow.com/ankey/

## Educational Foundation Summary

Ankey's methodology is grounded in established theories:

| Theory | Source | Application |
|--------|--------|-------------|
| Cognitive Development | Piaget (Preoperational Stage) | Ages 3-6 target |
| ZPD | Vygotsky | Parent-guided storytelling |
| Narrative Thinking | Bruner | Stories as primary learning vehicle |
| Narrative Transport | Green & Brock, 2000 | 22x more effective than direct instruction |
| Experiential Learning | Dewey | Real-event basis |
| Schema Theory | Piaget / Bartlett | Reduced cognitive load |
| Attachment Theory | Bowlby, Ainsworth | Parent-led delivery |
| Self-Determination Theory | Deci & Ryan | Parent autonomy in education |
| Authoritative Parenting | Baumrind | High demand + high response |

Full details in `METHODOLOGY.md`.
