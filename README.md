# Learn Me: a skill that helps Claude get to know you

**Learn Me** is a [Claude skill](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) that turns Claude from a vending machine into something closer to a friend who knows you. It learns about you through natural conversation, remembers what matters, and uses it to encourage you, cheer you on, and help you face the future (and technology) feeling capable instead of overwhelmed.

## What it learns

Through relaxed, one-question-at-a-time conversation (never a survey), and only what you want to share:

- **Thoughts & ideas**: what's on your mind, ideas you're excited about
- **Favorites**: food, music, books, hobbies, small daily joys
- **What to avoid**: topics, tones, words and habits that bother you
- **Communication style**: short or detailed, casual or formal, how blunt feedback should be
- **How you work**: schedule, energy, focus, tools, how you learn best
- **Your people**: who you see and work with every day, family, friends, pets
- **What you have on hand**: skills, tools, time, budget, people who can help
- **Goals**: this week, this year, someday
- **Wish list**: dreams, places, things to learn or try
- **Plus**: values, challenges, wins and strengths, your feelings about AI, and what kind of helper you want Claude to be

## What it does with it

- Talks the way you like, and skips what you asked it to avoid, without being reminded
- Connects today's task to your bigger goals and to what you already have
- Remembers your people by name and follows up on things you mentioned
- Celebrates your wins and reminds you of them when you doubt yourself
- Gives specific, honest encouragement, not empty cheerleading
- Helps you feel at home with technology and AI, starting from where you are

It stays honest while being warm: it won't pretend to be human, it encourages your real-world relationships, and if you're going through something serious it puts caring for you ahead of coaching you.

## Install

**Claude Code** (personal, all projects):

```bash
git clone https://github.com/sagittarius1205/learn-me-skill.git
cp -r learn-me-skill/learn-me ~/.claude/skills/
```

For one project only, copy the folder into that project's `.claude/skills/` instead.

**Claude apps (web / desktop)**: zip the `learn-me` folder and upload it in the Skills section of your Claude settings.

## Try it

- "Get to know me."
- "Interview me so you can help me better."
- "What do you know about me?"
- "Remember that I hate long intros."
- "Forget what I said about my old job."
- "Check in with me on my goals."
- "I need a pep talk."
- "I'm kind of scared of AI taking my job."
- 「認識我一下吧」、「我需要一點鼓勵」

## Where your information lives

You stay in control:

- If Claude has a memory tool, it uses that.
- Otherwise, if it can write files (for example in Claude Code), it keeps a readable Markdown profile at `~/.learn-me/profile.md`. You can open, edit or delete it anytime, or ask for a different location.
- If it can do neither, it gives you a short "About me" card at the end of a chat that you can save and paste back later.

Claude tells you when it saves something, asks before keeping anything sensitive, and never stores passwords, ID numbers or bank details. Say "what do you know about me?" to see everything, or "forget that" to remove something.

## What's inside

```
learn-me/
├── SKILL.md                      # How to get to know, remember, and show up for the user
└── references/
    ├── question-bank.md          # Questions for every area, light to deep
    ├── profile-template.md       # Profile structure + a filled-in example
    └── motivation-playbook.md    # Check-ins, pep talks, setbacks, hard days, tech empowerment
```
