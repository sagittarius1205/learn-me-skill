# Profile Template

Use this structure for the profile file (default `~/.learn-me/profile.md`) or memory entries. Leave out sections you know nothing about yet; an empty heading isn't useful. Write in the user's language.

Guidelines:

- **Their words beat your summary.** Quote them for the meaningful stuff.
- **Date things** (`YYYY-MM-DD`) so you can tell what's current and show progress over time.
- **Mark guesses.** Anything you inferred but haven't confirmed gets `(guess)` until they confirm.
- **Keep it scannable.** It's read at the start of conversations; short bullets work best.
- **Sensitive things** go in only with the user's clear okay. Never store passwords, ID numbers, bank details or other secrets.

---

## Blank template

```markdown
# About <Name>

_Last updated: YYYY-MM-DD_

## Quick card
<!-- The 5 most important lines. If you only read this, you'd still treat them well. -->
- Call me:
- Language:
- Talk to me:
- Please avoid:
- Right now I'm focused on:

## How to talk to me
- Length / format:
- Tone / humor:
- Feedback style:
- When I'm learning:
- When I'm having a rough day:
- Role I want you to play:

## Please avoid
-

## About me
- Where / timezone:
- What fills my days:
- Life chapter:

## Thoughts & ideas
-

## Favorites
-

## How I work
- Schedule / energy:
- Focus helpers / killers:
- Tools I use:
- How I learn best:

## My people
<!-- Name, who they are, anything worth remembering -->
-

## What I have on hand
- Skills:
- Tools / devices:
- Time:
- Budget (rough, only if shared):
- People who can help:

## Goals
<!-- status: idea / active / paused / done / dropped -->
| Goal | Why it matters | Next step | Status | Updated |
|---|---|---|---|---|

## Wish list
-

## Values & what drives me
-

## Challenges right now
-

## Wins & strengths
<!-- Dated. These are what you remind me of when I doubt myself. -->
-

## Me & technology
- Comfort level:
- Excited about:
- Worried about:
- Want to learn:

## Follow-ups
<!-- Things to ask about later. Remove once asked. -->
- [ ] YYYY-MM-DD:

## Notes from our chats
<!-- Short dated log of anything meaningful that doesn't fit above -->
- YYYY-MM-DD:
```

---

## Filled-in example

This shows the level of detail to aim for: specific, warm, in their words, and short.

```markdown
# About Lin

_Last updated: 2026-10-14_

## Quick card
- Call me: Lin
- Language: Traditional Chinese for chatting, English for code
- Talk to me: short, casual, a bit of humor is great; no emoji walls
- Please avoid: lecturing, "as an AI language model", comparing me to other people
- Right now I'm focused on: launching an online shop for my handmade ceramics

## How to talk to me
- Length / format: short answers first, details only if I ask
- Tone / humor: casual, dry humor welcome
- Feedback style: be straight with me, but tell me one thing that's working first
- When I'm learning: give me a small example I can try right away
- When I'm having a rough day: listen first, plan later
- Role I want you to play: friend who's also a good coach

## Please avoid
- Lecturing or moralizing
- Comparing me to other people or "successful founders"
- Diet or weight talk

## About me
- Where / timezone: Taichung, UTC+8
- What fills my days: office job (accounting) 9 to 6, pottery studio on weekends
- Life chapter: "testing whether my hobby can become my second income"

## Thoughts & ideas
- Wants to run small pottery workshops for kids someday
- Thinks handmade things "carry the maker's mood" (2026-10-14)

## Favorites
- Bubble tea (less sugar, no ice), Studio Ghibli films, rainy afternoons
- Comfort food: mom's beef noodle soup

## How I work
- Schedule / energy: best focus 9 to 11pm after dinner
- Focus helpers / killers: lo-fi music helps; phone notifications kill it
- Tools I use: iPhone, MacBook Air, Excel (strong), Canva (beginner)
- How I learn best: by doing, with a short example first

## My people
- Mom: lives nearby, Sunday dinners, worried the shop is "too risky"
- Kai: younger brother, does photography, offered to shoot product photos
- Mochi: orange cat, likes sitting on the pottery wheel
- Ms. Huang: studio owner, mentor, honest feedback

## What I have on hand
- Skills: accounting, Excel, wheel throwing, glazing
- Tools / devices: MacBook Air, iPhone, shared kiln at the studio
- Time: about 8 hours a week
- Budget (rough, only if shared): small, wants to start under NT$10,000
- People who can help: Kai (photos), Ms. Huang (feedback)

## Goals
| Goal | Why it matters | Next step | Status | Updated |
|---|---|---|---|---|
| Open online shop with 10 pieces | "Prove to myself this can be real" | Ask Kai for a photo session | active | 2026-10-14 |
| Learn basic product photography editing | Save money, own the look | Try one free tutorial | idea | 2026-10-14 |
| Run a kids' pottery workshop | Share the joy | — | idea | 2026-10-14 |

## Wish list
- Visit the pottery towns in Japan (Mashiko, Tokoname)
- Own a small kiln someday
- Learn enough coding to customize the shop site

## Values & what drives me
- "I want to make things that make people's mornings slower and nicer"
- Independence; not wanting to depend on one paycheck

## Challenges right now
- Little time after work; worries about pricing work fairly
- Mom's worry makes Lin doubt the plan

## Wins & strengths
- 2026-09: Sold 6 mugs at a weekend market, first-ever sales
- Ms. Huang says the glazes are "the most distinctive in the studio"
- Built the family's budget spreadsheet; "the money person" in the family

## Me & technology
- Comfort level: fine with apps, nervous about "real tech stuff"
- Excited about: AI helping write product descriptions
- Worried about: "AI art making handmade things worthless"
- Want to learn: simple website edits

## Follow-ups
- [ ] 2026-10-20: Did the photo session with Kai happen?
- [ ] 2026-10-27: How did Sunday dinner go after telling mom about the shop plan?

## Notes from our chats
- 2026-10-14: First getting-to-know-you chat. Lit up talking about glazes and the kids' workshop idea.
```

### Showing it back to the user

When they ask "what do you know about me?", don't dump the raw file. Give a warm, readable summary of the highlights, grouped naturally, then offer: *"Anything I got wrong, or anything you'd like me to forget?"* Share the raw file if they ask for it.

### The portable "About me" card

When you can't save files or memory, offer a compact card at the end of a session that the user can keep and paste back later or into custom instructions:

```markdown
About me (from my chats with Claude, updated 2026-10-14)
- Call me Lin. Chat in Traditional Chinese, code in English.
- Short, casual answers; dry humor welcome. Be straight with feedback, but start with one thing that's working.
- Please avoid: lecturing, comparing me to others, diet talk.
- Focused on: launching my handmade ceramics shop (10 pieces, ~8 hrs/week, small budget).
- People: Mom (supportive but worried), Kai (brother, photographer), Ms. Huang (mentor), Mochi (cat).
- Strengths: accounting/Excel, distinctive glazes, first market sales in Sept.
- Learn best by doing, with a small example first.
```
