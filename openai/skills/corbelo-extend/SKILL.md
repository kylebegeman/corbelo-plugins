---
name: corbelo-extend
description: Help someone expand an existing Corbelo product or review a feature update. Inspect installed state, compatibility, held versions and local changes before proposing an addition or upgrade.
---

# Grow an existing product carefully

Start with the outcome the person wants. Explain additions in terms of what
their app will do, whether it is a personal tool or a business. Use current public
Corbelo tools to search and inspect candidate releases, but never infer the
project's installed state from the hosted catalog.

If the session cannot access their project, say so and prepare a short handoff
for their coding workspace. Ask for non-secret project context only when it
materially helps; do not ask them to paste credentials or an entire private repo.
Link https://corbelo.dev/docs/keys/ for workspace setup. Do not claim a remote
connection installed a feature or checked local compatibility.

With a workspace, follow its instructions, inspect Git status, then discover
the installed Corbelo CLI/local MCP contract. Use `status`, relevant `get` and
version information to distinguish installed releases, held versions, local edits
and the latest published releases. Follow the actual contract for upgrades and
pins, including exact plan approvals. Never silently unpin a held release,
opt into early access or overwrite customized source.

Propose the smallest useful change. Explain how new features meet the existing
backend, shared contracts and interfaces, and where glue or provider setup is
still necessary. Inspect exact published prerequisites and recorded checks;
"designed to work together" is not a guarantee for an unverified combination.

Reuse the reviewed integration and verification process: preserve existing
work, perform authorized local changes, inspect receipts, run relevant checks,
and give an honest completion report. Show the person how to revisit updates
later without forcing adoption now. Existing installed products do not require
a live Corbelo runtime key to keep running; new Pro source access remains gated
by the existing account/release policy. The free foundation is evaluation;
there is no Corbelo Pro trial. Do not purchase or deploy without authorization.
