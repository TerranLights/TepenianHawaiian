# Source acquisition to-do

Material still needed in `source_reference/` (or reference by path from `slang-synthesis/source_reference/languages/` where it already exists).

| Subject | What to look for | Status |
|---|---|---|
| Hawaiʻi Creole English | Sakoda & Siegel, *Pidgin Grammar* (2003); creole-genesis studies (Bickerton on Hawaiian Creole; Roberts; Siegel) | partly acquired: Siegel, "Substrate influence in Hawaiʻi Creole English," *Language in Society* 29:2 (2000), pp. 197-236, saved in `source_reference/Hawaii_Creole_English/` (git-ignored, 2026-10-20; read for the Cantonese and Portuguese influence on the grammar). *Pidgin Grammar*, Bickerton and Roberts not yet acquired. Other works cited in Siegel's reference list: Reinecke, *Language and Dialect in Hawaii: A Sociolinguistic History to 1935* (University of Hawaii Press, 1969); Carr, *Da Kine Talk: From Pidgin to Standard English in Hawaii* (University of Hawaii Press, 1972); Bickerton, *Roots of Language* (Karoma, 1981) |
| Real Hawaiian (ʻŌlelo Hawaiʻi) | Pukui & Elbert, *Hawaiian Dictionary* (revised and enlarged edition, University of Hawaii Press, 1986); Elbert & Pukui, *Hawaiian Grammar* (University of Hawaii Press, 1979), the companion grammar by the same authors. Free online: Ulukau (Hawaiian Electronic Library), whose dictionary search combines several works including the Pukui & Elbert dictionary; a web resource, so it is recorded by name and would not be extractable as a file. For how Hawaiian entered contact varieties: J. Roberts, "Pidgin Hawaiian: A sociohistorical study," *Journal of Pidgin and Creole Languages* 10:1-56 (1995), and "A structural sketch of Pidgin Hawaiian," *Amsterdam Creole Studies* 12:97-126 (1995) | not acquired (developer is looking for the sources, 2026-10-20); extraction would be done in `slang-synthesis` |
| English | Reference grammars; histories of the language (layering by source) | partly in `slang-synthesis` (24-file *English Grammar Ebook collection*; not opened). **First priority for extraction** under D-19 Build order: English and Japanese first, since Japanese is already extracted and English is the missing half of the primary pair. The developer's own English grammar diagrams (16 redraws in `slang-synthesis/supplementary_diagrams/`) already exist |
| Japanese | Reference grammar, Sino-Japanese vocabulary, kana and kanji | `language-stash/Japanese/` has one book (a frequency dictionary); the full set (619 files) is in `slang-synthesis/source_reference/languages/Japanese/`, where a parallel triage is under way (2026-10-18) |
| Tagalog | Reference grammar, dictionary | located, not yet opened: 27 files in `w-lang/Tagalog (Filipino)/` plus 5 in `language-stash/Tagalog (Filipino)/` (see survey below) |
| Ilocano | Reference grammar, dictionary, Hawaii-specific studies | partly acquired: 3 PDFs by one author in `language-stash/Ilocano [Philippines]/`; no Hawaii-specific studies yet |
| Korean | Already extracted in `slang-synthesis` | done there; 109 files also located in `w-lang/Korean/` (see survey below) |
| Spanish (Mexican) | Already extracted in `slang-synthesis` | done there; no Spanish folder on the external drive; the Spanish set (137 files, including two *Colloquial Spanish of Latin America* volumes) is in `slang-synthesis/source_reference/languages/Spanish/` (see survey below) |
| Okinawan | Short grammar and Hawaii contact notes | Not found. Cantonese (21 files on the external drive) is excluded as a source (D-11 Chinese excluded as a source) but kept as a reinforcement reference (D-13 Chinese as an auxiliary reinforcement mechanism), so its grammar material is still wanted. Portuguese is excluded as a source (D-10 Portuguese excluded as a source), so no Portuguese material is needed |
| Pidgin and creole theory | Textbook on pidgin and creole genesis; contact-linguistics reference | not acquired |
| Other models | Tok Pisin, Chavacano, Sranan and similar contact languages | not acquired |

## Reference translations for the public-domain translations (2026-10-26)
Used to check readings of original-language texts (`public_domain_translations/PLAN.md`); read privately, never copied.

| Book | Reference | Status |
|---|---|---|
| *The Art of War* (Sun Tzu) | Thomas Cleary's English translation (developer's suggestion) | owned by the developer, a 1991 pocket edition (physically small; completeness to check) (2026-10-26); publisher and title page still to be recorded from the book; not in any local library folder |

## Survey of the external stash (2026-10-18, read-only, filenames only)

**Locations.** Main stash: `/media/kuroskalacs/Home-Theater/w-lang/` (about 53 GB, audio and video already removed, 28 language folders). Smaller local stash: `/home/kuroskalacs/Documents/Doll-Fi/media/y-files/language-stash/` (Ilocano, Japanese, Polish, Tagalog). **Nothing is written to either location; all writing is in this repo. All extraction of these sources is done in `slang-synthesis` (D-9 Extraction in slang-synthesis, absorption here); this repo only records and absorbs.** The contents below are known from file and folder names only; no book has been opened or checked yet.

**Priority languages (developer, 2026-10-18):** Japanese, Tagalog, Korean, Latin American Spanish (especially Mexican), then Ilocano.

| Language | What is there | Gap or note |
|---|---|---|
| Tagalog | `w-lang`: 27 files, including a Tagalog grammar, *Tagalog* in The World's Major Languages, an advanced reader, a Filipino basic course, a three-part English-Spanish-Tagalog dictionary, and a study of language and national identity in the Philippines. `language-stash`: 5 files, including a Tagalog slang dictionary. | Several titles come as both PDF and DjVu, so the real count of distinct works is lower. The Spanish-Tagalog dictionary may bear on Spanish loanwords. |
| Korean | `w-lang/Korean/`: 109 files (and 19 files in `slang-synthesis/source_reference/languages/Korean/`) in seven numbered folders (courses, grammar, dictionaries, culture, video courses). The grammar folder includes *A History of the Korean Language*, a Cambridge Language Surveys volume and a London Oriental and African Language Library volume. | Folder `00 Book List` holds only six images. Korean's role here is "supplementary" in the contributing-language roster; the developer says it enters "to varying degrees". |
| Japanese | `slang-synthesis/source_reference/languages/Japanese/`: 619 files in nine folders (writing system, textbooks, grammar, vocabulary, dictionaries, culture and others). `language-stash/Japanese/` adds a frequency dictionary. Nothing on the external drive. | A parallel triage is under way in `slang-synthesis`; this repo reads its catalog and does not duplicate it. |
| Spanish (Latin American, Mexican) | `slang-synthesis/source_reference/languages/Spanish/`: 137 files, including *Colloquial Spanish of Latin America* (two volumes), grammar practice books, and audio courses. Nothing on the external drive. | Whether any of it is specifically Mexican (not just Latin American) is not yet checked. |
| Ilocano | `language-stash/Ilocano [Philippines]/`: 3 PDFs (about 278 MB), all by one author: a reference grammar and two copies of an Ilocano-English dictionary-and-grammar. | The two dictionary-and-grammar files differ greatly in size (68 MB versus 195 MB); they may be one work in two scans, not verified. No Hawaii-specific Ilocano material yet. |
| Cantonese | `w-lang/Cantonese/`: 21 files, including a comprehensive grammar and a dictionary of Cantonese slang. | Excluded as a source (D-11 Chinese excluded as a source) but needed as a reinforcement reference (D-13 Chinese as an auxiliary reinforcement mechanism). The comprehensive grammar is the key file; extraction would be done in `slang-synthesis`. Mandarin material already sits in `slang-synthesis/source_reference/languages/`. |
| Portuguese | `w-lang/Portuguese/`: 167 files in Brazilian and European subfolders. | Excluded as a source (D-10 Portuguese excluded as a source); no action here. |
| English, real Hawaiian, Hawaii Creole English, Okinawan, pidgin and creole theory, other contact languages | Not found in either location (searched by name). | Still to acquire; see the table above. |

The other `w-lang` folders (Arabic, Basque, Bulgarian, Khmer, Catalan, Danish, Hindi-Urdu, Hungarian, Icelandic, Irish, Kazakh, Malay-Indonesian, Mongolian, Nepali, Norwegian, Polish and Ukrainian, Serbo-Croatian, Slovene, Swahili, Swedish, Thai and Lao, Tibetan, Vietnamese) are outside this repo's roster for now.

