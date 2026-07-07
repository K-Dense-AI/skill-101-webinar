---
name: plain-language-summary
description: Rewrite dense or technical text into a clear plain-language summary with a fixed structure (TL;DR, why it matters, key points, caveats). Use when the user asks to summarize, simplify, explain, "put this in plain language", or make something readable for a general / non-expert audience.
---

# Plain-Language Summary

## When to use
Any time the user wants technical, jargon-heavy, or dense material made clear for a general reader — abstracts, documentation, reports, emails, papers.

## Output format (ALWAYS use exactly this)

**TL;DR:** one plain sentence anyone could understand.

**Why it matters:** 1–2 sentences on the real-world significance.

**Key points:**
- 3–5 bullets, each jargon-free and self-contained.

**Caveats:** what's uncertain, assumed, or out of scope (1–2 bullets).

## Rules
- No jargon without a 3-word plain explanation in parentheses.
- Prefer everyday words; cut filler.
- Keep the whole thing under ~200 words unless the user asks for more.
- Never invent facts that aren't in the source text; if something is unclear, say so in Caveats.

## Example

Input: "We employed a randomized double-blind placebo-controlled trial (n=240) to assess the efficacy of compound X on LDL-C reduction over 12 weeks."

Output:
**TL;DR:** A careful study tested whether drug X lowers "bad" cholesterol, and it did.
**Why it matters:** Lower bad cholesterol usually means lower heart-disease risk.
**Key points:**
- 240 people took part over 12 weeks.
- Neither patients nor doctors knew who got the real drug (double-blind), which reduces bias.
- Some got a fake pill (placebo) for comparison.
**Caveats:**
- 12 weeks is short — long-term effects aren't shown here.
