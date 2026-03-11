# Accredo Scripts - Project Rules

## Project Structure
- `scripts/` — Our actual scripts, organised by feature:
  - `scripts/order-picking/` — OE order picking forms and scripts
  - `scripts/tinting/` — Tinting forms and scripts
  - `scripts/mixbank/` — MixBank scripts
  - New features get their own folder under `scripts/`
- `reference/barcoding/` — Existing third-party barcoding scripts (not ours). Use as reference for patterns and examples when building new scripts.
- `docs/accredo/` — Accredo documentation split by topic (see INDEX.md)
- `_archive/` — Old pre-git backups (gitignored, local only)
- Only generate shared modules (auth, config, API helpers, etc.) when they are actually needed — not upfront.
- Keep things lean. Don't over-engineer or scaffold beyond what's required for the current task.

## Accredo Documentation (MANDATORY - READ THIS)
**CRITICAL RULE: You MUST Grep `docs/accredo/` BEFORE writing ANY Accredo/MaxBasic code.**
Do NOT rely on your training data for Accredo — it is frequently wrong. Accredo is niche software and your knowledge of it is unreliable. The docs are the single source of truth.

**When you MUST look things up (non-negotiable):**
- Before using ANY MaxBasic function → Grep `docs/accredo/` to confirm it exists and check its exact syntax
- Before using ANY MaxBasic statement or construct → check `docs/accredo/maxbasic_language.md`
- Before using ANY scripted form property/method/event → check `docs/accredo/scripted_forms.md`
- Before using ANY API endpoint or web service call → check `docs/accredo/api_webservices.md`
- Before working with ANY Accredo module (AR, AP, IC, OE, etc.) → check the module's doc file
- When debugging an error you don't understand → search the docs for the relevant function/property

**How to look things up:**
  1. `Grep` the term across `docs/accredo/` directory — this is fast and finds the right file instantly.
  2. If unsure which file, check `docs/accredo/INDEX.md` for the quick lookup table.
  3. Read the matching section to confirm syntax, parameters, and behaviour.

**Key files:**
  - MaxBasic function syntax → `docs/accredo/maxbasic_functions.md`
  - MaxBasic statements, loops, events, memory tables → `docs/accredo/maxbasic_language.md`
  - Scripted form properties/methods/events → `docs/accredo/scripted_forms.md`
  - API / OData / web service calls → `docs/accredo/api_webservices.md`
  - Form designer → `docs/accredo/forms_designer.md`
  - SQL functions → `docs/accredo/sql_reference.md`
  - Module-specific (AR, AP, IC, OE, IN, etc.) → named by module in `docs/accredo/`

**If you write Accredo code without checking docs first, you WILL introduce bugs. Always verify.**

## Known Issues & Lessons Learned (MANDATORY - READ THIS)
**BEFORE writing or debugging any Accredo code, you MUST also check `docs/accredo/KNOWN_ISSUES.md`.**
This file contains every bug, workaround, and gotcha discovered in previous sessions. Searching it first prevents you from repeating the same mistakes.

**Workflow:**
1. Before coding: `Grep` relevant keywords (function names, module names, error text) in `docs/accredo/KNOWN_ISSUES.md`
2. If you find a matching entry, follow the documented solution — do NOT try a different approach unless the user asks.
3. When you hit a new problem and solve it, **immediately** add an entry to `docs/accredo/KNOWN_ISSUES.md` using the template format in that file.
4. When the user tells you something doesn't work or corrects you, **immediately** log it there too.

**You must log a new entry whenever:**
- You write code that fails and you fix it
- The user corrects you on Accredo behaviour
- You discover a function doesn't work as documented
- You find a workaround for an Accredo limitation
- An approach that seemed right turned out wrong

## Accredo API Basics
- The Accredo API is a RESTful OData 4 JSON API using OAuth 2.0 (password grant) for authorisation.
- Demo/test API base URL: https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('demo')
- Common endpoints: ARCustomerList, ICProductList, INInvoiceList, OEOrderList

## Error Log
Moved to `docs/accredo/KNOWN_ISSUES.md` — log all errors, fixes, and lessons learned there.