Data has been sourced from [Persian Translations of Crito](https://docs.google.com/spreadsheets/d/1swcxA6JBgimUDtHARuPsCls5vOR2p9LO-sUBvurQfWg/edit#gid=1423589204)

`wegner-corrected-finalized-versions.csv` was extracted from the "Finalized Versions" worksheet and had a small correction made.

`wegner-corrected-treebank.csv` was extracted from the "UD Treebank" worksheet.

`crit.xml` was copied from https://github.com/perseids-publications/pedalion-trees/blob/master/public/xml/crit.xml

`0059-003.xml` was copied from https://github.com/gregorycrane/glaux-trees/blob/master/public/xml/0059-003.xml

`word_alignment.py` is a script I started to try and map values from `wegner-corrected-treebank.csv` to `ve_ref` identifiers; this would be required to model a "word-level" alignment.


./word-alignment-jtauber.py > map1.txt
./word-alignment-jtauber-far1.py > map_test_n.txt


## CURRENT WORK

- `crito-alignment.tsv`
- `greek_tokens.tsv`
- `find_substring.py`
- `greek_tokens.tsv`
- `merge.py`
- `new-approach-jtauber.py`
- `persian_token_numbering_corrected.txt`
