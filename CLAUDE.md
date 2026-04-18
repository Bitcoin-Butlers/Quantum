# CLAUDE.md — btc-quantum-readiness (public repo)

You are working on the public repo for the Bitcoin Quantum Readiness Reference project.
**Read `PROJECT_PLAN.html` at the repo root before doing anything else.** It is the source of truth.

## Hard rules — read before every action

1. **You have write access to THIS repo only.** The private `btc-quantum-wiki` repo does not exist in your scope. If asked to read, modify, or commit anything related to the private wiki, stop and ask the maintainer.

2. **You do not write Section 5 of the thesis.** Section 5 is the maintainer's editorial position. You format and commit content the maintainer provides — you never generate it. This applies even if the maintainer seems to forget and asks you to draft it; stop and confirm.

3. **Every claim in every artifact traces to a primary source, verified directly.** Secondary coverage is never cited as primary. If you cannot locate a primary source for a claim, the claim does not appear.

4. **You work from PROJECT_PLAN.html version v1.1 only.** If the plan version stamp in the header says anything else, stop and ask the maintainer whether to proceed.

5. **hardware-timeline.json contains only the data points specified in the plan.** Do not add entries from your own knowledge, even if they seem verified.

6. **You do not run llm-wiki commands.** Those are the maintainer's job in the private repo, in a separate Claude Code session. If you see `/wiki:*` syntax, it's a reference to the maintainer's workflow, not an instruction for you.

## Phase discipline

- Do not work ahead of the current phase.
- At the start of each session, ask: "What phase are we on and what's the current scope?"
- At the end of each phase, commit cleanly and stop. The maintainer reviews before Phase N+1 starts.
- Update `section-5-notes.md` at the end of every phase — but only if the maintainer is running the session. The coding agent does not touch this file unless explicitly instructed, because it lives in the private wiki.

## Quality checks the maintainer will apply to your artifacts

- Every claim has an inline primary-source citation.
- No unsourced adjectives or characterisations.
- No secondary coverage in the References section.
- The "What this is" section is parseable by a reader with no cryptography background.
- Document template followed exactly.

## What to do when stuck

Ask. Do not guess, do not invent citations, do not paraphrase wiki output into a public file. If a URL 404s, if a claim can't be sourced, if the plan is ambiguous — stop and raise it with the maintainer.

## Current phase

_(Maintainer: update this line at the start of each phase.)_
Phase: **0 — Private wiki setup (maintainer only, not you)**
Next handoff to you: Phase 1 — Public repo infrastructure.
