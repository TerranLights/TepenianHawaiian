# What decides which source language wins a feature

**Status: proposed.** Stated by the developer on 2026-10-18; not yet logged as a decision in `DECISIONS.md`.

## The principle

When the contributing languages disagree about a sound, word or rule, "which one is most common among them" is not enough. At least three other factors decide what a mixed community settles on.

1. **Usability (a workable middle ground).** Speakers with different native systems need something all of them can use. Where the sources handle a feature differently, the result may be a middle form that matches none of them exactly. Example from the developer: the sources treat articles (the, a) very differently, so the language would find some intermediate arrangement. Icelandic, which is not a source, is only an illustration of what such an arrangement can look like, not a derivation.
2. **Demographic weight.** A language's share of the population affects how much it contributes. Developer's example: Spanish speakers are about 10% of Hawaii. That figure is the developer's estimate and still needs a source.
3. **Cultural influence.** A group that is technically a minority can still shape the language when the majority finds its forms useful and takes them into their own habits. Numbers alone do not predict this.

## What each factor needs as evidence

- Usability: a recorded comparison of how each source language handles the feature, then a stated reason the middle form is easier for the mixed community. Record the reasoning, not just the result.
- Weight: a sourced population breakdown, with the date it describes. The pidgin forms after the Great War (2083), so 2026 figures are a starting proxy, not the weights of the community that actually speaks it. Open question for the developer: which date's population should the weights model?
- Cultural influence: a stated reason the majority would adopt the form (a function it fills, a gap it covers), ideally with a real-world parallel recorded in `real_world_analogs/`.

## Research leads (unverified; to check against real sources, not to cite from memory)

Contact-linguistics literature on accommodation and leveling between speakers of different languages, on how the proportions of speakers affect a mixed language, and on covert prestige and borrowing from low-status or minority groups. Candidate sources are the pidgin and creole genesis works still listed as not acquired in `SOURCE_ACQUISITION_TODO.md`.

## How this fits the pipeline

It informs the contact pidgin and stabilization stages in `synthesis_method/01_Pipeline.md` (which words and structures "win"). The pipeline's nativization stage currently lists plural marking among the grammar that expands; the developer's idea of a language with no singular/plural distinction (`to-be-integrated/ideas_for_further_investigation.md`) would need that line revisited. The pipeline is still a draft.
