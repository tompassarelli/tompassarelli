# Tom Passarelli

Building agent-native systems from the bottom up: a database, a typed language, and a coordination layer for humans and agents.

## Building

**[Fram](https://github.com/tompassarelli/fram)** — append-only fact-graph database (triples + Datalog). Every fact is an immutable, addressable triple; lifecycle is derived, never stored. Agents commit facts to one canonical log, so a whole class of merge conflict is impossible by construction — and renames re-point references by identity, not spelling.

**[Beagle](https://github.com/tompassarelli/beagle)** — a typed Lisp where one source compiles to multiple targets, each rendered idiomatically. Built as an authoring surface for AI coding agents: ordinary text source plus a warm, def-level type checker that returns pointed errors fast enough to collapse the authoring loop.

**[North](https://github.com/tompassarelli/north)** — human + agent coordination/orchestration on Fram. Capture an intention as facts, then ask what's ready, blocked, and highest-leverage; the board is derived, never hand-maintained. The same coordinator drives multi-agent work: spawn, steer, dispatch.

## Declarative Systems, Tooling, and Apps

- **[firn](https://github.com/tompassarelli/firn)** — typed authoring layer for NixOS / nix-darwin; catches config errors at the source line, before rebuild.
- **[gjoa](https://github.com/tompassarelli/gjoa)** — a Firefox fork where the power-user stack — blocking, tree-style tabs, vim navigation, workspaces — is native, not bolted on through extensions.
- **[wake](https://github.com/tompassarelli/wake)** — declarative web-app compiler; one checked entity graph projects to direct-DOM UI, SQL, a REST server, and tests — no virtual DOM, no runtime.

## Contributor

- [Firefox](https://github.com/mozilla-firefox/firefox) - vertical-tabs bug fix
- [Kanata](https://github.com/jtroo/kanata) - `tap-hold-order` mechanism
- [Datastar Python SDK](https://github.com/starfederation/datastar-python) - Litestar bug fix

## Now

Founder at Passer, building products on that substrate. Fractional CTO at MSA, leading a platform rebuild in TypeScript and Postgres.

## Writing

Essays on process-primitive ontology, evaluation gates, and agency theory, published CC0 — start with *The Consistency Gate*.

---

[tompassarelli.org](https://tompassarelli.org) · tom.passarelli@protonmail.com · [in/tom-passarelli-33759b229](https://www.linkedin.com/in/tom-passarelli-33759b229/)
