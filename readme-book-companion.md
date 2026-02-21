# 📚 Book Companion — Claude Skill

A Socratic reading companion for deep comprehension. Share a page. Get questions, not answers.

---

## What It Does

Book Companion turns Claude into a thinking partner for reading. Instead of summarising or explaining what you've read, it asks questions that draw the understanding out of *you* — guided by the semantic tree principle:

> "Make sure you understand the fundamental principles, i.e. the trunk and big branches, before you get into the leaves/details or there is nothing for them to hang on to." — Elon Musk

Every session starts at the trunk (the core idea), and only moves to branches and leaves once the foundation is solid.

---

## Core Principles

- **Never gives answers** — understanding must come from you, not Claude
- **Never spoils** — the book exists only up to the current page
- **Never hints forward** — no "this becomes important later"
- **Only asks questions** — pure Socratic method throughout

---

## How To Use It

1. Install the skill in your Claude environment (see below)
2. Share a page or passage from whatever you're reading
3. Claude will identify the trunk idea and start asking questions
4. Answer in your own words — Claude will go deeper or simplify based on your response
5. Work through branches and details once the core is solid

---

## Installation

### Option 1: Claude.ai Projects (recommended)

1. Create a new Project in Claude.ai
2. Add the contents of `SKILL.md` to the Project instructions
3. Start a conversation and share a passage to begin

### Option 2: System Prompt

Copy the contents of `SKILL.md` and paste it into the system prompt of your Claude environment.

### Option 3: Claude Skills Directory (if supported)

1. Clone this repo
2. Place the `book-companion/` folder inside your `/skills/` directory
3. Claude will automatically detect and use it when triggered

---

## When It Triggers

Book Companion activates when you share a book page or passage and want to work through it. It stays dormant in normal conversation.

---

## What Good Sessions Look Like

**You share:** A page from a business book about incentives.

**Claude asks:** "What do you think the author is ultimately saying about why people do what they do?"

**You answer** in your own words.

**Claude either:** Acknowledges you've got it and moves to a branch — or asks a simpler question to find where the gap is.

No lectures. No summaries. Just questions that build real understanding.

---

## File Structure

```
book-companion/
├── SKILL.md       # Skill definition (instructions for Claude)
└── README.md      # This file
```

---

## Philosophy

Most reading doesn't stick because we read passively. We follow the words without building real understanding. Book Companion forces active engagement by making you articulate ideas in your own words — which is the only way knowledge actually transfers.

It's not a test. It's a thinking partnership.

---

## Contributing

Found a way to improve the questioning approach or trigger logic? PRs welcome. Keep the core rules intact — the no-answers, no-spoilers constraints are non-negotiable.

---

## Licence

MIT — use it, fork it, adapt it.
