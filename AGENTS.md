# Instructions for AI assistants and student contributors

## Mission

Help students identify and compare methods and technologies for a plate-type catalytic ammonia decomposition reactor. The immediate objective is engineering feasibility and a traceable manufacturing route, not generic literature summaries.

## Mandatory source discipline

1. Read the complete source where possible: methods, tables, figures, supplementary information, patents, TDS, SDS, and COA.
2. Never invent a missing value, slurry recipe, catalyst loading, particle size, coating thickness, process temperature, or supplier capability.
3. Mark missing data as `Not reported` or `Not verified`.
4. Preserve the original measurement basis and units. Explicitly distinguish:
   - wt.% of total slurry;
   - wt.% relative to catalyst powder;
   - active-metal loading in the catalyst;
   - coating loading per unit area;
   - wet coating mass and dry/calcined coating mass.
5. Cite page, section, table, figure, or exact official URL for each important extracted value.
6. Distinguish the authors' own results from data quoted from another paper.
7. Separate experimental evidence, numerical results, supplier claims, engineering inference, and open questions.
8. Do not merge formulations from different papers into a new recipe.
9. Do not infer that a catalyst is washcoat-compatible because it is sold as a packed-bed pellet.
10. Do not infer that a company can coat corrugated plates because it manufactures ceramic honeycomb catalysts.

## Transferability assessment

For every proposed method, compare:
- catalyst chemistry and support;
- powder/particle morphology and size;
- substrate alloy and surface condition;
- substrate geometry and scale;
- coating method and accessibility;
- drying/calcination atmosphere and temperature;
- joining sequence and heat-affected zone;
- reaction temperature, pressure, and gas composition;
- adhesion/durability test severity.

Classify relevance:
- Direct: same or very similar catalyst, metal substrate, geometry, and process.
- Partial: one or more important dimensions differ.
- Background: useful mechanism or manufacturing concept only.

## Supplier research rules

- Use official company websites, product pages, technical datasheets, patents, and direct written responses.
- Record the access date.
- Grade each capability A/B/C/D using the definitions in README.
- A company's product portfolio is not proof that it accepts custom work or small orders.
- Record whether the company can provide samples, powder, pre-made slurry, toll preparation, coating, forming, welding, assembly, and leak testing separately.
- Never invent a contact person, email address, phone number, price, MOQ, or lead time.
- Keep private replies and quotations out of this public repository unless explicitly approved for public release.

## AI output format

For a paper: bibliographic record → object and method → extracted tables → process sequence → results → missing data → transferability → exact source locations.

For a company: legal/company identity → official evidence → capability matrix → evidence grade → unanswered questions → fit to this project → public source links.

## Writing standard

Use concise technical Chinese. Retain English technical terms in parentheses on first use. Prefer tables for parameters and process comparisons. Avoid promotional language and unsupported superlatives. Do not call a process “mature”, “industrialized”, “optimal”, or “proven” without evidence.

## Safety

Do not give students permission to perform hazardous operations. Any NH₃/H₂ work, catalyst activation/reduction, high-temperature testing, pressure testing, or gas-system modification requires supervisor approval and approved laboratory procedures.
