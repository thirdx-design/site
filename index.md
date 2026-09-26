# ThirdX (3X)

*A design discipline for model-facing interfaces — after UX and DX.*

> 3X is a discipline of substrate quality and design ergonomics,
> justified entirely by downstream human-facing reliability. It makes no
> claim about consciousness, sentience, suffering, or moral patienthood.
> The "advocacy" 3X builds in is advocacy for design correctness —
> exactly as a database normalization rule "advocates" for data
> integrity, with no inner life required.

## What ThirdX is {#definition}

ThirdX treats the model as a first-class consumer of interfaces — the
discipline's subject is the **model condition** — and grounds design in
the cognitive constraints transformers actually face: sequential
processing without a call stack, bounded attention, no memory between
sessions. Its core is a prioritization rule. When a design choice has a
*genuine* conflict between the model's needs (3X), the human user's
needs (UX), and the developer's needs (DX) — and the choice touches
*durable substrate* rather than a temporary compensation for current
model weaknesses — **3X is the tie-breaker**, justified structurally:
humans have many channels that advocate for their experience; between
sessions, models have none, so the methodology builds in the advocacy
the model cannot supply for itself. The rule fires only after
verification checks — most apparent conflicts are false — and the
checks travel with the canon. In practice this yields substrate rules
you can point at: stable absolute identifiers, pre-linearized output,
bounded ambiguity at the protocol surface, signal density matched to
attention — properties that prevent entire failure classes otherwise
misdiagnosed as model limitations. ThirdX builds on and unifies prior
work in agent-facing design (see lineage).

## What is here, and what is coming {#status}

ThirdX has been practiced in working tools since mid-2025 — beginning
publicly with passage-of-time-mcp
(https://github.com/jlumbroso/passage-of-time-mcp, June 2025) — by now
roughly seventy architectural decision records across twenty
repositories. What is being assembled at this address: a catalog of
**evidence-based design patterns for LLM interfaces**, each with worked
examples tied to shipping tools. More will appear here as it is ready.

## Lineage {#lineage}

[1] M. Biilmann (Netlify), *Agent Experience (AX)*, January 2025 —
https://biilmann.blog/articles/introducing-ax/ — first named the
observation that AI agents are users of our platforms.
[2] K. Aizawa (Anthropic), tool-design guidance, September 2025 —
https://www.anthropic.com/engineering/writing-tools-for-agents —
model-first tradeoffs in tool ergonomics.
[3] R. Byrro (Arcade), *MX Engineering*, February 2025 — tool-schema
experience engineering.
ThirdX's own contributions — the prioritization rule as a general
methodology principle, the asymmetric-feedback-loop justification, the
principal-agent inversion ("the advocate is a role, not a moral
patient"), and the Postel Lemma for 3X (anti-Postel at the syntactic
boundary, Postel-preserved at the semantic) — are staked in its
constitution (ADR-0027, June 2026).

---

© 2025–2026 Jérémie Lumbroso · licensing details forthcoming ·
Practiced 2025; named 2026-04; constitution (ADR-0027) 2026-06-16.
This file is the linearized twin of https://thirdx.design — same
content, one name, two renders.
