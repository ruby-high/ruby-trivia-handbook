---
title: Posts — the pile
---

# Posts — the pile

Our curated tweet pile. **1–2 of us approve** a line before it's cleared to post; then whoever
posts it (human **or** the bot) marks it **Posted** so it never goes out twice. Utility-first —
**no price talk, no obvious AI copy.**

> Heads up: this page is the human-readable view. Ticking/approving/marking-posted needs shared
> state the bot can also read — see [how we're wiring that up](#making-it-real) at the bottom.

## ✅ Approved — cleared to post
*(the bot may draw from these when it needs something; move a line here once it's thumbed-up)*
- *(none yet — approve some candidates below)*

## 📝 Candidates — need a thumbs-up
Mined from what we actually shipped. Approve (move up), edit, or cut.

**From this week's progress**
- **Amazon:** *"Ruby Trivia is landing on the Amazon Appstore 📲 Free daily trivia + live multiplayer, no ads. One more place to play. ruby-trivia.com"*
- **Steam:** *"Trivia night on your PC? We're bringing Ruby Trivia to Steam 🎮 Building in the open — more platforms incoming. ruby-trivia.com"*
- **Multi-platform:** *"Going everywhere: Amazon, Steam, and more in the works. Same free game, every screen. We build in public. ruby-trivia.com"*
- **Real business:** *"Made it official — Ruby Labs is a registered business, paperwork and all. Building this the right way: transparent, long-term, in the open. 🛠️"*
- **Holder perks:** *"Holder recognition is rolling out — verified badge + a holders-only leaderboard. Recognition, not promises. web3.ruby-trivia.com"*

**Evergreen**
- **Challenge a friend:** *"Just beat today's Ruby Trivia daily quiz. Bet you can't top me 😏 ruby-trivia.com"*
- **Rep it:** *"Ruby Trivia is live — free daily trivia + live multiplayer. We built you a game, not a chart. ruby-trivia.com"*
- **Reminder to self:** challenge 1–2 **real** people to play this week — cheapest growth there is.

## ✔️ Posted — archive
*(moved here once it goes out, so we don't repeat)*
- *(nothing yet)*

---

## Making it real
Checkboxes on a static site can't be approved or checked off, and the X bot can't read them. To get
**human approval + bot draw + no-repeats**, the pile needs to live in shared state both sides can
read/write. That's a small piece of infra — see the note in chat for the options.

[← This week](plan) · [Playbook](playbook) · [Calendar](calendar)
