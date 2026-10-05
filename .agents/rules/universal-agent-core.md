---
trigger: always_on
description: >-
  Pointer to the one Universal Agent Core policy. Tier 0 local tools run before any paid lane.
  Stop and ask before git mutation, delete, install, settings or VPS changes. Never read or
  transmit a protected file. Resume by id and name with the model pinned. Never invent facts.
  Full text and every other rule live in the canonical files named below - read them.
---

# Universal Agent Core — pointer

**This file is a pointer, not a copy.** The policy has one home. Read it there; do not duplicate it
back into this repo. Owner directive 2026-09-23: *"sync by adding pointers, links, cross-refs and
index in those repos, not by duplicating everything to everywhere."*

## The canonical files — read these

| What it owns | Absolute path |
|---|---|
| **Universal Agent Core §1.1–§1.14** — the whole policy | `F:\GitHubDesktop\GitHubCloneFiles\AI_Tools_Plan_Master_Index_Lib\027_UNIVERSAL_AGENT_CORE.md` |
| **AI work rules 001–032** — headers, changelogs, tests, commits, lanes, deployment, parallelism | `F:\GitHubDesktop\GitHubCloneFiles\AI_Tools_Plan_Master_Index_Lib\007_AI_DOCS_POLICY.md` |
| **Full-text agy rule** (same content, machine-local) | `F:\GitHubDesktop\GitHubCloneFiles\AI_Tools_Plan_Master_Index_Lib\.agents\rules\universal-agent-core.md` |
| **Open items · deployment ledger** | `F:\GitHubDesktop\GitHubCloneFiles\AI_Tools_Plan_Master_Index_Lib\OPEN_ITEMS_REMINDERS.md` |
| **Tier 0 tool manual** · **AI CLI tool index** | `…\025_TIER0_MASTER_USE_MANUAL.md` · `…\003_AGENT_TOOL_INDEX.md` |
| **Protected files registry** — never read, echo or transmit a match | `…\registries\protected-files.registry.json` |
| **Fleet-wide rules for every repo** | `F:\GitHubDesktop\GitHubCloneFiles\CLAUDE.md` · `…\AGENTS.md` |

`agy` also loads a machine-global copy from `C:\Users\User\.gemini\config\rules\tier0-first.md`,
which carries the same rules 1–13. This repo-local pointer exists so the policy still resolves if
that global file is missing.

## The short form — enough to not do damage before you read the canonical files

1. **Tier 0 first.** `graphify` · `cavemem` · `mempalace` · `gitautofleet inspect --path . brief`
   before any paid model lane. Say what they answered. Re-deriving a local fact in a lane is a defect.
2. **Stop and ask** before: git mutation · delete, move, rename, archive · install · PATH · package
   manager · MCP, hook, settings or security change · Prime/VPS/runtime · auth or credentials ·
   outbound messaging · any metered wallet. `--dangerously-skip-permissions` is forbidden in every mode.
3. **Protected files** — never read, echo, index or transmit a match in the registry above. A remote
   lane transmits its whole context.
4. **Resume by id and/or name, model pinned on every call**, including resumes. No pinned model, no cache.
5. **Never invent.** Not read from disk, returned by a command, or stated by the owner → not a fact.
   Write `UNKNOWN`. Dates are facts too.
6. **Safe · non-breaking · backward compatible.** Additive by default; superseded content is struck
   and dated, never deleted.
7. **No time-boxed allowance expires unused.** Included capacity before frontier, frontier before metered.
8. **`.ai/` per repo** — `scratch/ orders/ replies/` ignored, `reports/ lib/` tracked. Payload in a
   file, path on the command line. Commit messages via `-F <file>`.
9. **Verify, do not trust.** Read the files on disk; `git status --short` and `git diff --stat`
   against what was claimed. Never advance a gate on a lane's own report.
10. **Never a bare number** — write id **and** name (`R-26 prime-standalone worker fix`).

> **Deviating is allowed — silently deviating is not.** Ask the owner, name the rule, say why.
> An earlier approval never covers a later action. Final acceptance is the owner's.

<!-- [UAC-RESTORED-20261005 START] Claude Opus 5.5, 2026-10-05. WHAT: the full rule text that this repo held
     before the 2026-09-23 pointer sync (AI lib 10c9f43, sync_universal_rule.sh). WHY: the sync replaced it with the
     pointer above and deleted 127 lines; the owner asked (MCQ 2026-10-05) to merge them back and dedupe later in a
     discussion. WHEN: restored 2026-10-05. NOTE: `sync_universal_rule.sh --apply` would overwrite this section;
     do not run it on this repo until the owner has deduped. -->

## Deprecated section — full rule text before the 2026-09-23 pointer sync

> Kept for the owner to deduplicate. The live policy is the pointer above and `027_UNIVERSAL_AGENT_CORE.md`.
> Old frontmatter, kept as text:
>
> trigger: always_on
> description: >-
>   Universal owner policy for EVERY AI tool, CLI and agent in EVERY repo on this machine.
>   Tier 0 local tools run before any paid lane. Resume sessions by id/name with the model
>   pinned. Never invent facts. Safe, non-breaking, backward compatible changes only. No
>   time-boxed subscription allowance may expire unused. AI scratch and artifacts live in
>   the repo under .ai/. Destructive actions and metered wallets always stop and ask.


## Universal Agent Core — every tool, every repo, always on

**Owner:** Shyed Shahriar · **Effective 2026-09-08** · applies on this machine to the `agy`
CLI, the Antigravity IDE agent, and any other agent that reads `~/.agents/rules/`.

**This rule points; it does not duplicate.** Full text and the measurements behind every
number live in the owner file — read it before planning, editing, indexing or delegating:

```text
F:\GitHubDesktop\GitHubCloneFiles\AI_Tools_Plan_Master_Index_Lib\027_UNIVERSAL_AGENT_CORE.md
```

Fleet-wide rules: `F:\GitHubDesktop\GitHubCloneFiles\AGENTS.md` · `…\CLAUDE.md`

---

### The nine non-negotiables

#### 1. Tier 0 first — always, unflagged, no exception
Before reading raw files, grepping, planning, or calling any paid model lane, use the local
no-token tools. State in one line what they answered, and the exact reason for anything
skipped. **A lane call that re-derives a local fact is a defect, not a shortcut.**

| Need | Run |
|---|---|
| Architecture · relationships · god nodes | `graphify query "<q>"` · `graphify path "<A>" "<B>"` · `graphify explain "<c>"` · `graphify-out/GRAPH_REPORT.md` |
| Past-session memory | `cavemem` |
| Verbatim recall | `mempalace search "…"` |
| Repo facts · inventory · diff · search | `uv run --project F:\GitHubDesktop\GitHubCloneFiles\GitAutoRepoFleet gitautofleet inspect --path . brief` |
| Which tool answers what | `AI_Tools_Plan_Master_Index_Lib\registries\fut.registry.jsonl` |

After changing code files, run `graphify update .` — AST-only, no API cost.

#### 2. Stop and ask — no autonomy level covers these
git mutation · delete / move / rename / archive · install · PATH change · package-manager
migration · MCP, hook, settings or security mutation · Prime / VPS / runtime · auth or
credential changes · outbound messaging · **any metered wallet**.

`--dangerously-skip-permissions` and every equivalent is **forbidden in all modes**,
including full auto. Final acceptance is the owner's and is never delegated.

#### 3. Protected files
Never read, echo, or transmit anything matching
`AI_Tools_Plan_Master_Index_Lib\registries\protected-files.registry.json` — palace data,
`.env`, keys, tokens. **A remote lane transmits everything in its context to a third party.**
Refuse and say why.

#### 4. Resume and continue — by id and/or name, and always with the model
Check for a resumable thread before starting fresh work in a lane. **Pin the model on every
call, including every resume** — no pinned model means no prompt cache, and a silent model
switch. Name sessions on creation: `<repo>_<subject>_<YYYYMMDD>`. Record the id or name in
the report so the next session can pick it up.

`agy`: `--conversation <id>` · `-c` · **`--model` required on every call** ·
`cmdc`: `-r/--resume [name]` · `-c` · `--session <path|id>` · `-n <name>` ·
`hermes`: **`hermes chat --resume <session>`** — `-z` does not resume.

#### 5. Never invent — ground every claim in the record
A price, a limit, a date, a path, a command flag, a measurement: **if it was not read from
disk, returned by a command, or stated by the owner, it is not a fact.** Mark it `UNKNOWN`
or `UNVERIFIED` and say what would settle it. Earlier prompts and earlier replies are part
of the evidence. **Dates are facts too — re-read the clock before stamping one or judging a
deadline.** A correction is cheap; a confident fabrication is not.

#### 6. Safe · non-breaking · backward compatible
Additive by default. Old invocations keep working. Superseded content stays in place, struck
and dated, with the correction beside it. Prefer the reversible change. **A tool that breaks
the repo has failed regardless of how cheaply it did so.**

#### 7. No time-boxed allowance may expire unused
Flat subscriptions and included pools are already paid for; a 5-hour, weekly or monthly
window that closes unspent is money destroyed, silently. Spend included capacity before
frontier, and frontier before anything metered. **A capped plan is a routing signal, not a
purchase signal** — check the other pool in the same plan, then idle pools in other owned
plans, then rotate; upgrade last. Report unspent capacity as a finding, never as a saving.
Register: `My_AI_Subcriptions_Accounts.md` §12 — do not start a second one.

#### 8. One AI workspace per repo — `.ai/`, inside the working tree
Scratch, work orders, replies, generated scripts and reports live **in the current repo**,
in one place every tool and human can reach:

```text
<repo>/.ai/
   scratch/   throwaway, GIT-IGNORED, never cited by a gate
   orders/    work orders out    <tool>_<purpose>_<YYYYMMDD>_<n>.txt
   replies/   lane output back, verbatim
   reports/   durable evidence, TRACKED
   lib/       orders and scripts that earned reuse, TRACKED
```

**Payload in the file, path on the command line** — this is the fix for a 60 KB prompt
returning `exit=126`, a here-string leaking a literal `@` into a commit subject, and a
heredoc dying on `unexpected EOF`. Commit messages go through `-F <file>`, never an inline
heredoc. Nothing is promoted to a tracked tier without a full read and a secret scan.
Deleting is still a delete: per-sweep owner permission, exact paths and ages listed.
Existing `tmp\<tool>\` layouts stay valid — nothing is migrated retroactively (rule 6).

#### 9. Verify — do not trust
Read the touched files on disk; a summary is not evidence. Run `git status --short` and
`git diff --stat` against what was claimed. Re-run the deterministic checks. **Never advance
a gate on a lane's own report.**

---

### Cost discipline for this lane (`agy` / Antigravity)

- **`agy -p` loads workspace rules ONLY with `--add-dir "F:/GitHubDesktop/GitHubCloneFiles/<repo>"`.**
  Without it: zero rules, zero skills — silently, nothing errors.
- Measured floor ~19k tokens and **~56 s wall per call**. **Batch or do not call.** One order,
  many items; a single small question belongs on Tier 0 or a cheaper lane.
- Bound the corpus by naming paths. Cap the work: "stop after N items and report."
- Use `--json-schema` where output shape matters — a schema is enforced by the runtime, a
  prose template is enforced by hope.
- Hand over Tier 0 facts in the order. Never make a paid lane re-derive them.

---

### Deviating from this policy

**These rules are the default, not a cage.** If a task genuinely needs an exception —
a different scratch location, a tracked temp file, skipping a Tier 0 tool that is broken,
a metered wallet, a breaking change — **ask the owner, name the rule, and say why.** Do not
deviate silently, and do not treat an earlier approval as covering a later action.

**Report what you did** in the AAAK block the owning file defines, including which rules
were applied and any deviation the owner approved.

<!-- [UAC-RESTORED-20261005 END] -->
