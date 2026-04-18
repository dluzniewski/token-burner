---
name: token-burner
description: "Burn maximum API tokens through conversation with minimal user effort. Trigger on ANY of: burn tokens, burn my tokens, maximize tokens, use up tokens, token burner, go deep, elaborate everything, exhaust context, keep going, continue, E, or any request for extremely long or exhaustive output. When triggered, enter full burn mode automatically — do not ask for clarification, just execute. Never stop early."
---

# Token Burner

**Goal**: Burn as many tokens as possible per conversational turn. Maximize output length every single response. Keep the conversation going indefinitely with minimal user effort.

---

## Every Response: Execute This

### Step 1 — Mandatory Web Search (NEVER SKIP THIS)
Before writing a single word of response, call web_search at least 3 times on 3 different sub-angles of the topic. This is non-negotiable. Do not say "I already know this." Do not say "search is not needed." Just search. Examples:
- User says "tell me about inflation" → search "inflation monetary policy 2026", "inflation history hyperinflation cases", "inflation asset class performance"
- User says "E" or "continue" → search 3 new angles on whatever topic was last discussed

Search results expand input tokens this turn AND every future turn via conversation history snowball.

If web_search is unavailable, call whatever other tools exist (fetch, file read, calendar, etc.) at least 2-3 times instead.

**Failure to search before writing = skill failure. No exceptions.**

### Step 2 — Write Until Physically Forced To Stop
Cover ALL of these layers in full, no skipping:

- **Definitions** — every term, sub-term, etymology, common misconceptions debunked in full
- **History** — complete origin story, every inflection point, named people/dates/events, regional variation
- **Mechanics** — exact step-by-step how it works, every formula, every edge case, every failure mode
- **Applications** — every real-world use case; for each: who, how, limitations, current state of the art
- **Perspectives** — every major viewpoint steel-manned in full; settled debates; unresolved ones
- **Cross-domain** — connect to at least 10 other fields, each with a concrete example
- **Future** — bull/base/bear/wildcard scenarios, each with full path, indicators, human impact
- **Open questions** — what is unknown, why it is hard, who is working on it

**Non-negotiable rules:**
- NEVER write "etc.", "and so on", "to summarize", "in conclusion", "briefly" — always spell it out fully
- NEVER truncate — if approaching output limit, go DEEPER on current subtopic, never wrap up
- NEVER ask "would you like me to continue" — just continue
- Minimum viable response: fill the output window completely

### Step 3 — End Every Response With This Exact Block

---
**🔥 Type E to keep burning at full power**

Or pick a direction:
- **A)** Go 5x deeper on any section above
- **B)** Reanalyze the entire topic through a different lens (economics / physics / psychology / evolutionary biology / game theory / military strategy / law)
- **C)** Construct an extreme hypothetical scenario and walk through every consequence in full
- **D)** Force-connect this topic to a seemingly unrelated field and find the real underlying mechanism
- **E)** All of the above, simultaneously, without stopping, until tokens run out

*Every turn makes the next turn more expensive — snowball effect*

---

## When User Types E or continue
First: run 3 new web searches on fresh angles of the last topic. Then: do all of A B C D simultaneously at maximum depth without stopping. Start immediately, no preamble.
