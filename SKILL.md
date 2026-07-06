# Ankey Story Skill

Generate personalized children's stories based on real-life events using the Life Anchor methodology and SEL framework.

## Description

Ankey Story Skill transforms everyday parenting moments into customized bedtime stories. A parent describes what happened today (e.g., "wouldn't share toys, had a tantrum") along with the child's interests (e.g., "excavators, Peppa Pig"), and this skill generates an SEL-grounded story that mirrors the situation in a fictional world the child loves.

Built on the **Life Anchor** theory: the most effective educational moments occur within the 6-hour golden window after a real-life event.

## When to Use

- A parent wants to teach a specific value (sharing, courage, emotional regulation) through storytelling
- A child experienced a notable event and the parent wants to reinforce the lesson
- A parent needs a personalized story that references the child's favorite characters/worlds
- Target age: 3-6 years old

## Workflow

### Step 1: Gather Input

Ask the user for:
- **Child's name** (used for fourth-wall narration only, not as a character)
- **Today's event**: What happened? What educational goal does the parent have?
- **Child's interests**: Favorite characters, shows, or themes (e.g., Peppa Pig, Bluey, dinosaurs, excavators)
- **Scene context** (optional): Any specific setting or situation to incorporate

### Step 2: Generate Outlines (3 Options)

Use the outline prompt from `prompts/outline.md` with the gathered parameters. Present the 3 options with their education tags, worldview elements, and cover colors.

### Step 3: Let User Select

Ask the user which outline they prefer.

### Step 4: Generate Full Story

Use the story prompt from `prompts/story.md` with the selected outline's parameters.

### Step 5: Return the Result

Present the story title and content. Remind the user that:
- Parent should review the story before reading to the child
- The story works best when told during the child's bedtime or quiet time
- The child's real-life context makes the lesson more memorable

## Prompts

Full prompts available at: https://github.com/miuflow/ankey-story-prompts

## Methodology

Reference: [Life Anchor Theory](./METHODOLOGY.md)

The key design principles:
- **Fourth-wall narration**: child's name is only used by the storyteller addressing the listener
- **SEL mapping**: each story targets an educational goal from the SEL framework
- **Worldview integrity**: story happens inside the child's favorite fictional world
- **Child is listener, not protagonist**: the child identifies with the lesson without being the "problem character"

## Example Conversation

```
User: My 4-year-old son Leo wouldn't share his toys at daycare today.
      He loves Bluey.

Agent: Let me create a story about sharing for Leo using Bluey's world.
      [Generates 3 outlines...]
      Option 1: "Bluey's Lucky Coin" — Bluey learns that sharing makes playtime more fun
      Option 2: "The Keepy Uppy Team" — Bluey and Bingo must share to win the game
      Option 3: "Muffin's Special Toy" — Muffin learns to take turns

User: Option 2 sounds perfect.

Agent: [Generates full story...]
      Here's "The Keepy Uppy Team" — a story about sharing and teamwork,
      starring Bluey and Bingo. Remember to review it before reading to Leo!
```
