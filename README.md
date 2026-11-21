# 🎮 tinyLM-10M-ru

A lightweight language model (~10M parameters) for generating Russian-language dialogues. Designed as a base for fine-tuning in the game development segment: building in-game dialogue models without high system load.

## Purpose 🎯

The model is focused exclusively on:
- coherent speech and natural line generation;
- conversational style and typical dialogue patterns;
- colloquial vocabulary and slang (within language norms);
- maintaining context in short dialogues.

It is **not** intended for programming, design, image generation, complex reasoning, or multimodal tasks. Text only, dialogue only, Russian language only.

## Key Features ✨

- **Small footprint** — ~10M parameters: runs on resource-limited devices, easy to embed in game engines.
- **Narrow specialization** — training is concentrated on linguistic behavior and dialogue structure, without dilution by unrelated tasks.
- **Fine-tuning flexibility** — optimized for quick adaptation to a specific game universe, characters, and stylistics.
- **System prompt support** — control style and behavior via system prompts.

## Use Cases 🕹️

- Generating NPC lines in games (everyday conversations, quests, reactions to player actions).
- Creating a base for fine-tuning to a specific character or setting.
- Prototyping dialogue systems with minimal hardware requirements.
- Testing dialogue mechanics and branching in game scenarios.

## Requirements and Limitations ⚠️

- Language: Russian only.
- Input: text dialogues, system prompts.
- Not designed for multi-step logical reasoning, code, formulas, or media generation.

## Example Usage 💬
----
