---
name: load-my-stack
description: Load Kasper's full personal stack including frontend-design guidelines and Garry Tan G-Stack. Trigger on "load my stack", "load both skills", "load frontend + gstack", "load all my skills" or similar.
---

# Load My Stack

This skill automatically installs and activates your two main skill collections:

- **frontend-design** — Anthropic-inspired UI/UX design principles (~277k downloads)
- **gstack** — Full Garry Tan G-Stack (AI engineering workflow suite)

## Usage

In any new Grok chat, simply say one of the trigger phrases above, or run:

```bash
/load-my-stack
```

The skill will:
1. Install `https://github.com/kasperllm/grok-skills.git` (contains frontend-design)
2. Install `https://github.com/kasperllm/gstack.git` (full G-Stack)
3. Confirm both are loaded and ready

## Behind the scenes

It executes the equivalent of:
```bash
/skills install https://github.com/kasperllm/grok-skills.git
/skills install https://github.com/kasperllm/gstack.git
```

You can now use all design guidelines, G-Stack agents, browser tools, QA pipeline, etc. in the same chat.

**Pro tip:** Add this skill to your browser bookmark bar or start every work session with “load my stack”.