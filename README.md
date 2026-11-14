# vocab-dictionaries

Dictionary packs for the Vocab app (spaced repetition vocabulary learning). The app downloads
`manifest.json` and the pack files from the GitHub Pages site of this repository. The files are
generated; please do not edit them by hand.

## Files

- `manifest.json`: the list of packs with sizes, checksums, licences and sources.
- `<language>-<scope>-v<packVersion>.sqlite.gz`: one gzip-compressed SQLite database per language and scope
  (`common` = common words, `full` = complete dictionary).

| Language | Scope | Pack version | File | Size (bytes) |
|---|---|---|---|---|
| de | common | 2026111300 | de-common-v2026111300.sqlite.gz | 6544896 |
| de | full | 2026111300 | de-full-v2026111300.sqlite.gz | 24528214 |
| en | common | 2026111300 | en-common-v2026111300.sqlite.gz | 8882386 |
| en | full | 2026111300 | en-full-v2026111300.sqlite.gz | 41144836 |
| es | common | 2026111300 | es-common-v2026111300.sqlite.gz | 6143326 |
| es | full | 2026111300 | es-full-v2026111300.sqlite.gz | 25097487 |
| fr | common | 2026111300 | fr-common-v2026111300.sqlite.gz | 6365732 |
| fr | full | 2026111300 | fr-full-v2026111300.sqlite.gz | 22612797 |
| ja | common | 2026111300 | ja-common-v2026111300.sqlite.gz | 4790481 |
| ja | full | 2026111300 | ja-full-v2026111300.sqlite.gz | 37232847 |
| zh | common | 2026111300 | zh-common-v2026111300.sqlite.gz | 5067516 |
| zh | full | 2026111300 | zh-full-v2026111300.sqlite.gz | 26898954 |

## Licence

The pack content is licensed under CC-BY-SA-4.0 (https://creativecommons.org/licenses/by-sa/4.0/).
See `LICENSE.md`. Each pack also carries its licence and its sources inside the database, and the
app shows them on its credits screen.

## Sources and attribution

The packs are derived from the following sources. Thank you to everyone who contributes to them.

- **CC-CEDICT (MDBG)**, version 1.0 (2026-11-13T04:51:32Z)
  - Licence: CC-BY-SA-4.0 (https://creativecommons.org/licenses/by-sa/4.0/)
  - Homepage: https://www.mdbg.net/chinese/dictionary?page=cc-cedict
  - Data: https://www.mdbg.net/chinese/export/cedict/cedict_1_0_ts_utf-8_mdbg.txt.gz
  - Note: CC-CEDICT is a community-maintained Chinese-English dictionary published by MDBG under CC BY-SA 4.0, based on CEDICT, Copyright (C) 1997, 1998 Paul Andrew Denisowski.
- **JMdict (jmdict-simplified)**, version 3.6.2+20261109214828 (2026-11-09)
  - Licence: CC-BY-SA-4.0 (https://www.edrdg.org/edrdg/licence.html)
  - Homepage: https://www.edrdg.org/wiki/JMdict-EDICT_Dictionary_Project.html
  - Data: https://github.com/scriptin/jmdict-simplified/releases/download/3.6.2%2B20261109214828/jmdict-eng-3.6.2%2B20261109214828.json.zip
  - Note: This pack uses the JMdict/EDICT dictionary files. These files are the property of the Electronic Dictionary Research and Development Group, and are used in conformance with the Group's licence. Packs are rebuilt from new JMdict releases and offered as updates.
- **Tatoeba**, version 2026-11-07 (2026-11-07)
  - Licence: CC-BY-2.0-FR (https://creativecommons.org/licenses/by/2.0/fr/)
  - Homepage: https://tatoeba.org/
  - Data: https://downloads.tatoeba.org/exports/per_language/deu/deu_sentences_detailed.tsv.bz2
  - Note: Example sentences and their translations are from Tatoeba (tatoeba.org), contributed by its community under CC BY 2.0 FR; the author of each sentence and translation is named with the example, and a sentence without a recorded author is credited to Tatoeba. Many Japanese sentences come from the Tanaka Corpus.
- **Wiktionary contributors (English edition, via kaikki.org wiktextract)**, version 2026-10-30 (2026-10-30)
  - Licence: CC-BY-SA-4.0 OR GFDL-1.3-or-later (https://en.wiktionary.org/wiki/Wiktionary:Copyrights)
  - Homepage: https://en.wiktionary.org/
  - Data: https://kaikki.org/dictionary/raw-wiktextract-data.jsonl.gz
  - Note: Text by Wiktionary contributors, available under CC BY-SA 4.0 and GFDL; extracted by wiktextract and published by kaikki.org. The date is the Last-Modified time of the file the generator read.
- **Wiktionary contributors (German edition, via kaikki.org wiktextract)**, version 2026-11-01 (2026-11-01)
  - Licence: CC-BY-SA-4.0 OR GFDL-1.3-or-later (https://creativecommons.org/licenses/by-sa/4.0/deed.de)
  - Homepage: https://de.wiktionary.org/
  - Data: https://kaikki.org/dewiktionary/raw-wiktextract-data.jsonl.gz
  - Note: Text by Wiktionary contributors, available under CC BY-SA 4.0 and GFDL; extracted by wiktextract and published by kaikki.org. The date is the Last-Modified time of the file the generator read.
- **Wiktionary contributors (Spanish edition, via kaikki.org wiktextract)**, version 2026-11-02 (2026-11-02)
  - Licence: CC-BY-SA-4.0 OR GFDL-1.3-or-later (https://creativecommons.org/licenses/by-sa/4.0/deed.es)
  - Homepage: https://es.wiktionary.org/
  - Data: https://kaikki.org/eswiktionary/raw-wiktextract-data.jsonl.gz
  - Note: Text by Wiktionary contributors, available under CC BY-SA 4.0 and GFDL; extracted by wiktextract and published by kaikki.org. The date is the Last-Modified time of the file the generator read.
- **Wiktionary contributors (French edition, via kaikki.org wiktextract)**, version 2026-11-02 (2026-11-02)
  - Licence: CC-BY-SA-4.0 OR GFDL-1.3-or-later (https://fr.wiktionary.org/wiki/Wiktionnaire:Licence)
  - Homepage: https://fr.wiktionary.org/
  - Data: https://kaikki.org/frwiktionary/raw-wiktextract-data.jsonl.gz
  - Note: Text by Wiktionary contributors, available under CC BY-SA 4.0 and GFDL; extracted by wiktextract and published by kaikki.org. The date is the Last-Modified time of the file the generator read.
- **Wiktionary contributors (Japanese edition, via kaikki.org wiktextract)**, version 2026-11-02 (2026-11-02)
  - Licence: CC-BY-SA-4.0 OR GFDL-1.3-or-later (https://ja.wiktionary.org/wiki/Wiktionary:%E8%91%97%E4%BD%9C%E6%A8%A9)
  - Homepage: https://ja.wiktionary.org/
  - Data: https://kaikki.org/jawiktionary/raw-wiktextract-data.jsonl.gz
  - Note: Text by Wiktionary contributors, available under CC BY-SA 4.0 and GFDL; extracted by wiktextract and published by kaikki.org. The date is the Last-Modified time of the file the generator read.
- **Wiktionary contributors (Chinese edition, via kaikki.org wiktextract)**, version 2026-11-02 (2026-11-02)
  - Licence: CC-BY-SA-4.0 OR GFDL-1.3-or-later (https://zh.wiktionary.org/wiki/Wiktionary:%E7%89%88%E6%9D%83%E4%BF%A1%E6%81%AF)
  - Homepage: https://zh.wiktionary.org/
  - Data: https://kaikki.org/zhwiktionary/raw-wiktextract-data.jsonl.gz
  - Note: Text by Wiktionary contributors, available under CC BY-SA 4.0 and GFDL; extracted by wiktextract and published by kaikki.org. The date is the Last-Modified time of the file the generator read.
- **wordfreq**, version 3.1.1 (2023-11-21)
  - Licence: CC-BY-SA-4.0 (https://github.com/rspeer/wordfreq#license)
  - Homepage: https://github.com/rspeer/wordfreq
  - Data: https://files.pythonhosted.org/packages/24/61/62835c475d69872d30689f284497853fe33fe1d6dd18f57346d13305861d/wordfreq-3.1.1-py3-none-any.whl
  - Note: Frequency data from wordfreq by Robyn Speer. It includes the SUBTLEX word lists created by Marc Brysbaert et al. (SUBTLEX is freely available data), data from OPUS OpenSubtitles 2018 originating from the OpenSubtitles project, Google Books Ngrams (books.google.com/ngrams) and the Leeds Internet Corpus, Wikipedia and ParaCrawl.

Example sentences from Tatoeba carry their author's name on each example row inside the packs.

## Changes

The packs are rebuilt from the sources from time to time; a new build has a new pack version in
its file name and in `manifest.json`.
