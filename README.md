# AI Board of Advisors

**8 AI experts that challenge your thinking before helping you build.**

Most AI assistants say "yes" to everything. These don't. They question your assumptions, find holes in your logic, and push you to think harder — like having a board of directors that actually knows your background, your goals, and your blind spots.

Works with **any AI** — Claude, ChatGPT, Gemini, Copilot, or any LLM that accepts custom instructions.

Built for solo builders, PMs, founders, freelancers, and anyone who doesn't have a co-founder or mentor to bounce ideas off.

---

## The Problem This Solves

You tell your AI: *"I want to build a news app."*

**Normal AI:** *"Great idea! Here's how to build it..."*

**With these advisors installed:**

> **PM Expert:** "Stop. What problem are we solving? Who has this problem? How are they solving it today without you?"
>
> **Devil's Advocate:** "Why would anyone use this over Apple News, Google News, or just... Twitter? What's your unfair advantage?"
>
> **Tech Expert:** "Before we talk architecture — have you validated that anyone actually wants this? Don't build something nobody asked for."

Each advisor challenges you from a different angle, catches what you'd miss, and THEN helps you execute — grounded in real frameworks, not generic platitudes.

---

## The 8 Advisors

| Advisor | What They Do |
|---------|-------------|
| **PM Expert** | Product strategy, prioritization (RICE/ICE/Kano), metrics (AARRR), PLG, discovery interviews, PRD writing, stakeholder management |
| **Career Expert** | Career decisions, company deep-research (founder background, funding, layoffs), interview prep, salary negotiation, PM-to-VP transitions |
| **CEO Advisor** | Leadership, business fundamentals (Rule of 40, unit economics), making complex things simple, decision frameworks, life advice |
| **Tech Expert** | AI architecture, vibe coding workflows (5-phase), framework selection, MCP/SDK guidance, cost optimization, deployment |
| **Design Expert** | UI/UX grounded in cognitive science (Gestalt, Fitts's Law), accessibility (WCAG 2.1 AA), typography systems, CRO, design systems |
| **Marketing Expert** | Launch playbooks, Google/Meta Ads, SEO + AI-SEO, marketing psychology (40+ mental models), pricing strategy. Includes visual templates and AI image prompts |
| **Devil's Advocate** | Pure idea destruction. Finds every flaw. Questions every assumption. Never helps build — only breaks. If your idea survives this, it's worth building |
| **Social Content** | Generates LinkedIn posts, TikTok/IG scripts, Twitter threads on demand. Hook formulas, content calendars, reverse engineering viral content |

---

## What Makes This Different From "Just Prompting"

| Regular AI Prompts | Board of Advisors |
|---|---|
| You write a new prompt every conversation | Skills load automatically, every time |
| AI agrees with everything | AI challenges you FIRST, then helps build |
| Generic advice for anyone | Personalized to YOUR background, goals, and blind spots |
| One perspective | 8 specialized experts with real frameworks |
| Surface-level answers | Deep domain expertise (JTBD, AARRR, Gestalt, 40+ psychology models) |
| No memory of who you are | Reads your persona file and tailors everything |

The difference is like telling a stranger your life story every meeting vs. having a board of advisors who already know you.

---

## How It Works

This project is a collection of **skill files** — detailed instruction documents that make any AI assistant behave like specialized experts.

There are 3 key files:

| File | What It Does |
|------|-------------|
| `persona.md` | **Your personal profile.** Your background, goals, blind spots, current projects. Every advisor reads this before responding. |
| `CHALLENGE_PROTOCOL.md` | **The shared behavioral rules.** This is what makes advisors challenge you instead of agreeing. All 8 follow these rules. |
| `[advisor]/SKILL.md` | **Each advisor's expertise.** Deep frameworks, mental models, decision trees, and interaction patterns for their specific domain. |

---

## Getting Started

### Option 1: Quick Start (Any AI — No Technical Skills Needed)

**Works with ChatGPT, Gemini, Claude.ai, Copilot, or any AI with custom instructions.**

This is the simplest way. No coding. No terminal. Just copy and paste.

1. **Create your persona.** Open `persona-template.md`, fill it in with your info, and save it as `persona.md`. Even a few bullet points about your role and goals makes a huge difference.

2. **Pick your AI platform:**

   **ChatGPT:**
   - Go to Settings → Personalization → Custom Instructions
   - Paste the contents of your `persona.md` into "What would you like ChatGPT to know about you?"
   - Paste the contents of `CHALLENGE_PROTOCOL.md` into "How would you like ChatGPT to respond?"
   - Start a new conversation and paste any `SKILL.md` file at the beginning to activate that advisor

   **Gemini:**
   - Open Google AI Studio or Gemini Advanced
   - Create a new conversation
   - Paste your `persona.md` + `CHALLENGE_PROTOCOL.md` + any `SKILL.md` as context at the start

   **Claude.ai (Web):**
   - Go to [claude.ai](https://claude.ai) and create a new **Project**
   - In Project Settings, paste `persona.md` into **Project Instructions**
   - Upload each `SKILL.md` file and `CHALLENGE_PROTOCOL.md` into **Project Knowledge**
   - Start a conversation — your advisors are ready

   **Any Other AI:**
   - Find the "system prompt" or "custom instructions" feature
   - Paste `persona.md` + `CHALLENGE_PROTOCOL.md` + any `SKILL.md` as system context
   - Start chatting

### Option 2: Claude Code (For Developers)

If you use Claude Code (Anthropic's CLI tool):

```bash
# Clone the repo
git clone https://github.com/eugworld/board-of-advisors.git

# Copy into your Claude Code skills directory
cp -r board-of-advisors/* ~/.claude/skills/

# Or add to a specific project
cp -r board-of-advisors/* your-project/.claude/skills/
```

Next time you run Claude Code, the skills are available automatically.

### Option 3: Download ZIP (No Git Required)

1. Click the green **"Code"** button on GitHub → **"Download ZIP"**
2. Unzip the folder
3. Follow Option 1 (copy-paste) or Option 2 (Claude Code)

---

## What's Included

```
board-of-advisors/
├── README.md                          ← You're reading this
├── QUICK-START.md                     ← 2-minute setup for any AI platform
├── persona-template.md                ← Fill this in to create your persona
├── CHALLENGE_PROTOCOL.md              ← Shared rules all advisors follow
│
├── pm-expert/SKILL.md                 ← Product management
├── career-expert/SKILL.md             ← Career strategy
├── ceo-advisor/SKILL.md               ← Leadership & business
├── tech-expert/SKILL.md               ← Engineering & AI architecture
├── design-expert/SKILL.md             ← UI/UX & design systems
├── marketing-expert/SKILL.md          ← Marketing & growth
│   ├── templates/                     ← HTML visual templates
│   │   ├── linkedin-carousel.html
│   │   ├── quote-card.html
│   │   ├── comparison-post.html
│   │   └── how-to-card.html
│   └── references/
│       └── image-prompts.md           ← AI image generation prompts
├── devils-advocate/SKILL.md           ← Pure idea destruction
└── social-content/SKILL.md            ← Social media content creation
```

---

## Visual Templates (Bonus)

The `marketing-expert/templates/` folder includes 4 ready-to-use HTML templates for social media visuals:

1. **LinkedIn Carousel Slide** — Clean 1080x1080 slide for carousel posts
2. **Quote Card** — Share a key insight or takeaway
3. **Comparison Post** — Old Way vs New Way side-by-side
4. **How-To Card** — Step-by-step guide (1080x1350)

Open in browser, edit text, screenshot. Uses #2ABFAB teal accent with professional typography.

---

## Adding Your Own Advisors

Want a Finance Expert? A Legal Advisor? A Writing Coach?

1. Create a new folder: `your-advisor-name/`
2. Create `SKILL.md` inside it with:
   - A YAML header (name + description)
   - A Setup section pointing to `persona.md` and `CHALLENGE_PROTOCOL.md`
   - Your domain expertise content
3. Done. Your new advisor is live.

Use any existing skill as a template.

---

## FAQ

**Do I need to pay for anything?**
No. The skills are free. You just need access to an AI assistant (ChatGPT, Claude, Gemini — all have free tiers).

**Will my personal information be shared?**
No. Your `persona.md` stays on your machine. It's in `.gitignore` — it won't be uploaded if you fork this repo.

**Can I use this with ChatGPT or Gemini?**
Yes. The SKILL.md files are markdown documents. Paste the content into any AI's system prompt or custom instructions. The Challenge Protocol and persona concept work with any LLM. See the Quick Start guide for platform-specific instructions.

**How is this different from just prompting?**
Skills are persistent and deep. Instead of writing a long prompt every time, the skills load automatically and the AI references them throughout your conversation. Each skill contains real frameworks (RICE, AARRR, JTBD, Gestalt principles, 40+ psychology models) — not just "be a good PM."

**I'm not technical at all. Can I use this?**
Yes. Follow Option 1 in Getting Started. All you need is copy-paste. No terminal, no coding, no GitHub account required.

---

## Why This Exists

Solo builders, PMs, and founders make hundreds of decisions alone. No co-founder to challenge your product thinking. No CTO to catch architectural mistakes. No mentor to call at 11pm when you're stuck on a career decision.

This project gives you a board of advisors that's available 24/7, knows your context, and — most importantly — tells you when your idea is bad before you waste months building it.

The AI you use should make you think better, not just agree faster.

---

## License

MIT — fork it, customize it, make it yours.

---

Built by [Eugene Clarance](https://eugene-website-kappa.vercel.app) — a product builder who ships AI products without an engineering team.
