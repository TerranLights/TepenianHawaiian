# Possession marker: the developer's proposal and a first check

**Status: `proposed` (developer's proposal, 2026-10-30).** Pilot area for RQ-D1 (How English and Japanese interact). It is not a decision and nothing here enters `language/`; a form with no recorded derivation is not allowed there (rule 1), and this proposal's derivation is still being worked out. The proposal below is the developer's own and is separate from what the sources say.

## The developer's proposal (2026-10-30)
The possessor takes a marker attached to it, as in English, and the marker is a form of the letter *n*, as in Japanese. The possessor comes before the possessed.

| The possessor ends in | Add | Pattern |
|---|---|---|
| a vowel | *n* | `{...}[V] + n` |
| *a* + consonant | *an* | `{...}a[C] + an` |
| *o* or *u* + consonant | *on* | `{...}(o/u)[C] + on` |
| *e*, *i* or *y* + consonant | *in* | `{...}(e/i/y)[C] + in` |

Developer's examples, using English words before any synthesized words exist:
- *the car of John* becomes "Johnon car"
- *the car of Dasha* becomes "Dashan car"
- *the color of the tarp* becomes "the tarpan color"
- *the brightness of the sun* becomes "the sunon brightness"

All four examples follow the table as written (*Dasha* ends in a vowel, so only *n* is added).

## First check against the extractions (read-only, 2026-10-30)
Citations are to the `slang-synthesis` extractions, not to the original books; quoted descriptions are paraphrase. The extractors' own confidence labels are kept.

**English.**
- The possessive is an attached ending on the possessor, and the possessor comes first. CMOS §5.19 (p. 539) lists seven relations the genitive covers: ownership, relationship, agency, description, role of subject, role of object, and idiomatic shorthand for an *of*-phrase (`established/001_cmos_ch05_grammar_and_usage_pt01.md`).
- CMOS ch. 7 §§7.23–7.28 (`established/018_cmos_ch07_spelling_compounds_pt02.md`) covers the attachment rules: the ending goes on the last word of a compound (§7.23, p. 930), a genitive survives in time expressions (*three days' time*, §7.24), possessive versus attributive nouns (§7.25), possessive with a gerund (§7.26), and the "double" form *a friend of Dick's* (§7.27).
- The extractions do not contain the developer's observation that animate possessors take *'s* and inanimate ones take *of*. That observation is the developer's own (see RQ-B8).

**Japanese.**
- の (*no*) sits between two nouns, possessor first (N1 の N2). The *Dictionary of Japanese Particles* entry "no / n (の/ん)" (pp. 143-158; `established/032i_dictionary_japanese_particles.md`) shows it covering plain possession, relative location, material, creative authorship, relationship, category membership, attribution, and more.
- The advanced-grammar dictionary calls "N1 no N2" "radically underspecified": the relation depends on context (`established/031_dictionary_advanced_japanese_grammar.md`, Special Topic 2, pp. [29]-[35]).
- Pronouns take の like any other noun, with no separate possessive pronoun forms (`established/035b_barrons_japanese_grammar.md`; `established/038d_japanese_beyond_words.md`).
- **A precedent for the *n* form:** in colloquial speech の contracts to *n* after *watashi* and *boku* when a noun follows (*boku-n chi*, "my house"), per *Nihongo Notes* vol. 7, pp. 86-87 (`established/053_nihongo_notes_07_08.md`). The extractor marked this `plausible_unverified`, so it needs a second source before anything rests on it.

## Observations (analysis, not findings)
1. **Where each language shows up.** The attachment to the possessor and the possessor-first order are shared by English *'s* and Japanese の. The *n* sound comes from Japanese. This is consistent with D-18 Source layers as ways of thinking, but the derivation is not yet recorded.
2. **The proposal makes no animate/inanimate split.** *Tarpan* and *sunon* use the same marker as *Johnon*. English's *'s* versus *of* split (developer's observation) would be dropped, which matches Japanese, where の does not split. Whether this is intended connects to Q-13 Grammatical classing of robots, humans and objects and RQ-A6.
3. **Breadth.** Japanese の covers far more relations than English *'s*. Which relations the new marker covers is not yet stated.
4. **Letters or sounds.** The rule is written on letters. In English spelling, a silent *e* (*Jane*) or *y* (*Mary*) and digraphs (*team*) make "last vowel" ambiguous. The real rule would be written on sounds, which waits on the phonology.
5. **The vowel mapping.** *a*, *o/u* and *e/i/y* collapse to three vowels (*a*, *o*, *i*). The reason for this specific mapping, and for copying the preceding vowel at all, needs a recorded derivation. Candidate leads, none checked: how Japanese adapts consonant-final loanwords, and the open-syllable pattern of real Hawaiian.
6. **Possible collisions.** A possessor already ending in *-an* or *-on* (*Dan*, *son*) gives *Danan*, *sonon*; a noun ending in a vowel plus *n* may be confused with a possessor.
7. **Not yet covered:** pronouns, plurals, and compounds.
8. **Chinese reinforcement (D-13, D-14).** Mandarin and Cantonese have a possessive particle after the possessor, but that is recalled, not checked. The Mandarin grammar misfiled in the English collection is the natural source once it is extracted.

## Open questions for the developer
Recorded as Q-14 Possession marker: scope and form.

## Revision history
- 2026-10-30: proposal recorded; first check against the English and Japanese extractions.
