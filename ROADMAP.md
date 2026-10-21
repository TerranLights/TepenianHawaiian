# Roadmap

**Status legend:** `not started` · `in progress` · `complete`. Update when work actually begins or finishes.

## Phase 0 — Foundation *(in progress, 2026-10-13)*
Repo structure, standing rules, canon record. **Done:** structure created. **Next:** developer review of this structure.

## Phase 1 — Source acquisition and triage *(not started)*
Gather reference material (`SOURCE_ACQUISITION_TODO.md`). Triage and extraction are done in `slang-synthesis`, not here (D-9 Extraction in slang-synthesis, absorption here); this phase records what exists, what is missing, and what is extracted. Existing English, Japanese, Korean, Spanish and other material already sits in `slang-synthesis/source_reference/languages/`, with extractions in its `datasets/`; reference it by path, do not duplicate.

## Phase 2 — Contributing-language analysis *(not started; the sibling repo has completed Phase 1 extraction for Japanese, Korean, Spanish and Tagalog as of 2026-10-20, and this phase absorbs it)*
For each language in `contributing_languages/`: phonology, morphology, syntax, lexicon strata, what contact would keep and what it would drop. English, Japanese and Tagalog in full; Korean and Spanish (Mexican) supplementary; Ilocano and others as research decides. Output per language into its own folder.

## Phase 3 — Contact-language modeling *(not started)*
Study real pidgins and creoles (`real_world_analogs/`): how pidgins form, stabilize and nativize; typical outcomes for grammar, sound system and lexicon. Hawaiʻi Creole English first.

## Phase 4 — Layering table *(not started)*
Decide, with the developer, which source language governs which levels and domains (`synthesis_method/02_Layering_Table.md`) and which language supplies the grammatical frame.

## Phase 5 — Stage-by-stage derivation *(not started)*
Derive the language through its stages: contact pidgin, stabilized pidgin, creole, regularized standard (Falkland era), then Federation-era usage. Record sound changes and grammaticalization in `language/` and the story of each stage in `history/`.

## Phase 6 — Core language build *(not started)*
Phonology, orthography, morphology, syntax, core lexicon, registers, dialects, pragmatics. Every item provenance-tagged.

## Phase 7 — Lexicon expansion and the Dome Fuji name *(not started)*
Grow the dictionary; derive the vocabulary the GDD needs (starting with the proper name of Dome Fuji, "The Temple").

## Phase 8 — History books *(not started)*
Write the language's history (and the history of Hawaii as it bears on it) from `history/`.

## Phase 9 — eBook assembly *(not started)*
Compile the grammar reference, dictionary and history books (`ebooks/`).

## Phase 10 — Handoff to slang-synthesis *(not started)*
Modern Hawaiian becomes an input language for in-universe slang work.
