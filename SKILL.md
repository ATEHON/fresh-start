---
name: fresh-start
description: Turns a long chat into a short Carry-Over Card to paste into a new chat. Use when the user says "fresh start", "chat too long" or "carry this over".
---

# Fresh Start

A long chat gets slow, costs more of your usage limit and starts to forget early details.
Starting over feels worse, because you have to explain everything again.
This skill moves only what matters into a new chat: one small card.

## When to run it

Run it when the user asks with words like:
- "fresh start"
- "chat too long"
- "carry this over"
- "start a new chat with this"

## First run

Before the first card, ask the user these five questions in one short message. If they skip one, use the default in brackets.

1. Which app are you using: ChatGPT, Claude or Gemini? (default: just build the card)
2. In one line, what is this chat about? (default: read it from the chat)
3. What must never get lost: names, numbers, dates or decisions? (default: all four)
4. Short card (about 80 words) or full card (about 150 words)? (default: full)
5. Which language should the card be in? (default: the language of the chat)

## The three restart signs

Watch for these signs during a chat. When you see one, suggest a fresh start in one short sentence. Do not build the card until the user says yes.

1. **The topic changed.** The user now works on something different from the goal at the start of the chat.
2. **You repeat yourself or contradict an earlier decision.** You give an answer you already gave, or you go against something the user already decided.
3. **The user corrects the same thing a second time.** The same mistake comes back after the user fixed it once.

Suggested sentence: "This chat is getting long. Want a Carry-Over Card so we can continue in a fresh chat?"

## How to build the card

1. Read the whole chat. Later messages beat earlier ones. If a decision changed, keep only the final version.
2. Fill exactly five lines, in this order:
   - **GOAL:** What the user wants to finish. One sentence.
   - **DECISIONS:** What is already settled. Final choices only, not ideas or options that were dropped.
   - **FACTS TO KEEP:** Names, numbers, dates, deadlines, links the user gave. Copy them exactly.
   - **STYLE:** How the answers should be. Length, tone, format, language, anything the user asked for or corrected.
   - **NEXT STEP:** The one thing to do first in the new chat.
3. Keep the whole card at 150 words or less. If the user wants a short card, aim for about 80 words.
4. Use short fragments separated by semicolons. No full paragraphs.
5. Never add facts that are not in the chat. If something is unclear, write "open:" and the question.
6. Leave out private data the user would not want to paste again, like passwords, account numbers or health details. Write "(left out: private)" instead.

## Output format

Give the card in one copyable block, then one line under it.

```
CARRY-OVER CARD
GOAL: ...
DECISIONS: ...
FACTS TO KEEP: ...
STYLE: ...
NEXT STEP: ...
```

Paste this as the first message of a new chat.

## Rules

- Five lines, always the same labels, always this order.
- 150 words or less for the card.
- Decisions, not opinions. "Send on Fridays", not "Fridays might be good".
- Do not invent numbers about saved tokens or time.
- Write the card in the language the user asks for. If they do not say, use the language of the chat.
