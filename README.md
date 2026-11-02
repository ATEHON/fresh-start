# Fresh Start

**Your chat got long, slow and forgetful. Fresh Start turns it into one small card you paste into a new chat, so you keep your decisions and lose the clutter.**

Works with Claude and Gemini as a skill, and with ChatGPT or any other chat app by copy and paste.

## What you get

A **Carry-Over Card** of 150 words or less, always in five lines:

| Line | What goes in |
|---|---|
| GOAL | What you want to finish |
| DECISIONS | What is already settled |
| FACTS TO KEEP | Names, numbers, dates, links |
| STYLE | How the answers should sound |
| NEXT STEP | The first thing to do in the new chat |

Your AI also tells you when a fresh start makes sense. It watches for three signs:
1. The topic changed.
2. The AI repeats itself or goes against an earlier decision.
3. You correct the same thing a second time.

## Install and use in 3 steps

1. **Get the file.** Download `fresh-start.zip` from Releases.
2. **Add it to your AI.**
   - Claude: Customize, Skills, upload `fresh-start.zip` as it is (code execution must be on).
   - Gemini: Customize, Skills, upload `SKILL.md` from the ZIP (web or Mac app only, personal accounts 18+).
   - ChatGPT or any other app: open `SKILL.md`, copy everything from "# Fresh Start" to the end, and paste it as a message or into your project instructions.
3. **Type "fresh start"** in your long chat. Copy the card. Paste it as the first message of a new chat.

On the first run your AI asks you up to five short questions. See `FOR_YOUR_AI.md`.

## Example

A made-up chat of 40 messages about planning a bakery newsletter (804 words) became this card (145 words):

```
CARRY-OVER CARD
GOAL: Plan and write the first email newsletter for Hearth Lane Bakery; bring people in on slow Tuesdays and get cake pre-orders.
DECISIONS: Every two weeks; send Monday 6 pm (not Tuesday 7 am); issue 1 launches the Harvest Loaf; subject "Meet the Harvest Loaf"; offer: free coffee with any loaf, Tuesdays only, say "Harvest" at the counter; cake orders by phone only, no online shop.
FACTS TO KEEP: Harvest Loaf = sourdough with walnuts and figs; phone 555 0142; cakes need 3 days notice; closed Mondays; about 120 addresses from a paper counter list, all agreed, keep the list as proof; website built by nephew Leo.
STYLE: Plain, like talking at the counter; newsletter max 150 words; max one exclamation mark per email and in replies.
NEXT STEP: Pick the email tool. Open: first send date (Monday 30 November suggested, not confirmed).
```

Full chat: `examples/before_long_chat.md`. Card: `examples/after_carry_over_card.md`.

Note: the changed decision (Tuesday 7 am became Monday 6 pm) shows up only in its final form, and the unconfirmed date is marked as open.

## Files

| File | For whom |
|---|---|
| `SKILL.md` | Your AI. The skill itself |
| `FOR_YOUR_AI.md` | Your AI. When to use it, start questions, common mistakes |
| `examples/` | You and your AI. One full before and after |
| `release/fresh-start.zip` | Ready to upload. Same files in a folder named `fresh-start` |
| `LICENSE` | MIT |

## License

MIT. Free to use, change and share.
