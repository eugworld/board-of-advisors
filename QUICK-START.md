# Quick Start: Set Up Your AI Board of Advisors in 2 Minutes

No coding required. No terminal. Just copy and paste.

---

## Step 1: Create Your Persona (60 seconds)

Open `persona-template.md` and fill it in. Save it as `persona.md`.

You don't need to write everything. Start with:
- Your current role
- 2-3 key achievements (with numbers)
- Your biggest blind spot
- Your 1-year goal
- How you like feedback (gentle / direct / brutal)

That's enough to get started. You can add more later.

---

## Step 2: Pick Your Platform

### ChatGPT (Free or Plus)

1. Go to **Settings** → **Personalization** → **Custom Instructions**
2. In "What would you like ChatGPT to know about you?" — paste your `persona.md`
3. In "How would you like ChatGPT to respond?" — paste `CHALLENGE_PROTOCOL.md`
4. Start a new chat. At the beginning, paste the content of any `SKILL.md` file (e.g., `pm-expert/SKILL.md`)
5. Start asking questions — the advisor is active

**Pro tip:** Create a separate Custom GPT for each advisor if you have ChatGPT Plus. Upload `persona.md`, `CHALLENGE_PROTOCOL.md`, and one `SKILL.md` to each GPT.

### Google Gemini

1. Open [Gemini](https://gemini.google.com) or [Google AI Studio](https://aistudio.google.com)
2. In AI Studio: Create a new prompt. Paste `persona.md` + `CHALLENGE_PROTOCOL.md` + any `SKILL.md` into the System Instructions
3. In Gemini chat: Start a conversation and paste all three files at the beginning as context
4. Start chatting — the advisor will follow the challenge protocol

### Claude.ai (Free or Pro)

1. Go to [claude.ai](https://claude.ai)
2. Create a new **Project** (left sidebar)
3. In **Project Settings**, paste `persona.md` into **Project Instructions**
4. Upload `CHALLENGE_PROTOCOL.md` and each `SKILL.md` file into **Project Knowledge**
5. Start a conversation in that project — all advisors are ready

### Claude Code (Developers)

```bash
git clone https://github.com/eugworld/enhanced-ourselves-skills.git
cp -r enhanced-ourselves-skills/* ~/.claude/skills/
```

Skills load automatically in your next Claude Code session.

### Microsoft Copilot

1. Open Copilot and look for custom instructions or notebook mode
2. Paste `persona.md` + `CHALLENGE_PROTOCOL.md` + any `SKILL.md` as context
3. Start chatting

### Any Other AI

If your AI tool has a "system prompt", "custom instructions", or "context" feature:
1. Paste `persona.md` (who you are)
2. Paste `CHALLENGE_PROTOCOL.md` (how to challenge you)
3. Paste any `SKILL.md` (the domain expertise)
4. Start chatting

---

## Step 3: Start Talking

Just ask naturally. The advisor will challenge you before helping:

- *"I want to build a new feature for my app"* → PM Expert
- *"Should I take this job offer?"* → Career Expert
- *"Tear apart my startup idea"* → Devil's Advocate
- *"Write me a LinkedIn post about AI agents"* → Social Content
- *"How should I design this landing page?"* → Design Expert
- *"I want to launch this product next week"* → Marketing Expert
- *"What tech stack should I use?"* → Tech Expert
- *"Help me make a tough business decision"* → CEO Advisor

---

## Tips for Best Results

1. **Be honest in your persona.** The more real you are about your blind spots, the better the challenges.
2. **Don't skip the Challenge Protocol.** That's the whole point — AI that thinks before it builds.
3. **Start with one advisor.** Get comfortable with PM Expert or Devil's Advocate first.
4. **Update your persona over time.** As your goals change, update the file.
5. **Use multiple advisors on big decisions.** Ask PM Expert, then switch to Devil's Advocate on the same idea.

---

## Which Advisor Should I Start With?

| Your situation | Start with |
|---|---|
| Building a product | PM Expert |
| Evaluating a job offer | Career Expert |
| Testing a business idea | Devil's Advocate |
| Planning a launch | Marketing Expert |
| Choosing a tech stack | Tech Expert |
| Making a big life decision | CEO Advisor |
| Creating social media content | Social Content |
| Designing a feature | Design Expert |

---

That's it. 2 minutes. Your AI just went from agreeing with everything to actually making you think.
