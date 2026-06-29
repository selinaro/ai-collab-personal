---
audience: personal
scope: universal
topic: work-style
---

# Git workflow — the agent does push & pull

Selina has the agent perform git **`push` and `pull` directly**. She does **not**
use Sourcetree for syncing.

**Why:** the ai-collab carrier specs and `setup-protocol.md` forbid `git push` and
assume Sourcetree (that is *Hannes's* workflow). Selina's setup is different — she
relies on the agent to commit and sync.

**How to apply:**
- After committing in any ai-collab audience repo (or project repo) on Selina's
  machine, `pull` (rebase to stay linear) then `push` — don't leave it for a manual
  Sourcetree step.
- `git rebase`/`merge`/`reset` remain hands-off unless Selina asks; the override is
  specifically about `push`/`pull` syncing.
- This is a personal/universal override of the carrier's "never push" rule, which
  applies to Hannes, not Selina.
