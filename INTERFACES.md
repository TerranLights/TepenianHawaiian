# Interfaces

## Inner Tepenia GDD (canon authority)
Path: `/home/kuroskalacs/Documents/Doll-Fi/media/games/Inner Tepenia/InnerTepeniaGDD/`
- **Reads:** its note `Worldspace/Modern_Hawaiian_Language.md`; city specs and timeline files when a stage or word needs an in-world anchor. Founders and city origins come only from `Worldspace/Locations-and-Levels/Outside-World/Tepenian-Federation/Locations/Cities/Founding_Register.md`.
- **Writes back (only on explicit decision):** the language's name and era names, dates, and vocabulary the GDD needs (for example, the proper name of Dome Fuji).
- **Law that binds across:** no national stereotypes; differentiate locally, converge nationally.

## slang-synthesis (sibling)
Path: `/home/kuroskalacs/Documents/Doll-Fi/media/Reference/slang-synthesis/`
- **This repo reads (read-only):** its `datasets/<Language>/` extractions (`established/` and, as they appear, `analysis/` and `grammar_logic/`) and its `source_reference/languages/`. As of 2026-10-20 Phase 1 extraction is complete there for Japanese, Korean, Spanish and Tagalog; English, Ilocano and the rest are not extracted.
- **Who extracts (D-9 Extraction in slang-synthesis, absorption here):** all extraction happens in that repo, directed by the developer. This repo never extracts or writes there. It absorbs the extracted data by path, cites it with page or section, quotes selectively and does not copy it in bulk. If this repo needs something extracted differently (for example phonology, historical contact or morphology, since that repo's tagging is aimed at slang), the developer directs that work there.
- **slang-synthesis reads from here:** the finished language, as an input language for in-universe slang.
- **Boundary:** this repo builds the language; that repo builds slang from a language's real patterns. Do not put slang work here.

## eBooks
`ebooks/` compiles from `language/` and `history/`. See `ebooks/README.md`.
