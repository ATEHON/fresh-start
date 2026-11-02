# For your AI: how to use Fresh Start

This file tells you, the AI, how to apply the Fresh Start skill well.
The skill itself is in `SKILL.md`.

## Your app has no skills feature?

That is fine. The skill is just text.

1. Open `SKILL.md` and copy everything from the heading "# Fresh Start" to the end of the file.
2. Paste it into your chat as a message, or into your project instructions.
3. Then type "fresh start".

This works in ChatGPT, Claude, Gemini and most other chat apps.

## Start questions

These are also in `SKILL.md` under "First run". On the first run, ask the user these five questions. Ask them together, in one short message. If the user skips one, use the default in brackets.

1. Which app are you using: ChatGPT, Claude or Gemini? (default: just build the card)
2. In one line, what is this chat about? (default: read it from the chat)
3. What must never get lost: names, numbers, dates or decisions? (default: all four)
4. Short card (about 80 words) or full card (about 150 words)? (default: full)
5. Which language should the card be in? (default: the language of the chat)

## When to load it

- The chat is long and answers get slow or vague.
- The user changes the topic but wants to keep earlier decisions.
- The user asks for a summary to start a new chat.
- One of the three restart signs in `SKILL.md` shows up.

## When not to load it

- Short chats. A card adds nothing if the chat fits on one screen.
- The user wants a full summary or meeting notes. That is a different task.
- The chat is mostly private data. Ask first what may go on the card.

## Typical mistakes

- **The card is too long.** More than 150 words means you copied the chat instead of shrinking it.
- **Opinions instead of decisions.** Only write what the user settled. Drop ideas that were rejected.
- **Old versions win.** If the user changed a decision later, only the last version goes on the card.
- **Details get lost.** Names, dates and numbers must be copied exactly. Check each one against the chat.
- **Made up facts.** If it is not in the chat, it is not on the card.
- **Style is missing.** The user corrected your tone or length? That belongs in STYLE, or the new chat repeats the mistake.

## What a good result looks like

```
CARRY-OVER CARD
GOAL: one sentence
DECISIONS: final choice; final choice; final choice
FACTS TO KEEP: name; date; number; link
STYLE: length; tone; format; language
NEXT STEP: one clear task
```

Paste this as the first message of a new chat.

See `examples/` for a full before and after.
