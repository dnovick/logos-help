# 05: Lemma Searches

## Concepts
- Searching for original language lemmas.

## Description
Many resources in Logos are morphologically tagged. Morphological tags associate the original language lemmas and morphology details with each word in a text. Searching on lemmas provideד a way to find how specific lemmas are used (e.g. translated) in the text.

To perform a lemma search, use the following syntax:

`lemma.[lang]:[lemma text]`

where [lang] is:

| Abbreviation | Language |
| ------------ | -------- |
| h            | Hebrew   |
| a            | Aramaic  |
| g            | Greek    |
NOTE: Additional language codes are supported and will be added to this list later.

The [lemma text] may either be entered in English, where Logos will provide a drop down lists of matches based on transliteration, or in the original language by switching keyboards.

## Search Configuration

| Name           | Value                       |
| -------------- | --------------------------- |
| Search Type    | Bible                       |
| Bible          | KJV 1900                    |
| Search Fields  | All Bible Text              |
| Match Within   | Verse                       |
| Search Filter  | Old Testament               |
| Match Criteria | - [ ] Match case            |
|                | - [ ] Match all forms       |
|                | Reference matching: Default |

| Search Text                                                                                                                                                                                                                                                                                                                                                                                         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [lemma.h:יד](https://ref.ly/logos4/Search?kind=BibleSearch&q=lemma.h%3a%D7%99%D6%B8%D7%93&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7CDataType%3dbible%7CResourceType%3dtext.monograph.bible%7CResultLimit%3d1%7CTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages)                                                     |
| [lemma.h:יד OR lemma.h:כף](https://ref.ly/logos4/Search?kind=BibleSearch&q=lemma.h%3a%D7%99%D6%B8%D7%93+OR+lemma.h%3a%D7%9B%D6%B7%D6%BC%D7%A3&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7CDataType%3dbible%7CResourceType%3dtext.monograph.bible%7CResultLimit%3d1%7CTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages) |
|                                                                                                                                                                                                                                                                                                                                                                                                     |
## Variations


## Logos Help/References
- 

## Related Searches
- 

## Notes
- While this example uses Bible search, much of the search syntax is the same for Morph searches.
- When selecting or typing a lemma, be careful to select the correct homonym for the lemma of interest.

