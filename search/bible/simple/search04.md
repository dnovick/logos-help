# 04: Proximity Operators 

## Concepts
- Constraining word searches with operators ```WITHIN```, ```BEFORE```, and ```AFTER```.

## Description
Sometimes, in addition to searching for a combination of words with operators such as ```AND```, it is desirable to constrain the distance and ordering of the search terms. This can be performed with the following operators:

NOTE: [units] may be either CHARS or WORDS.

| Term                               | Meaning                                                |
| ---------------------------------- | ------------------------------------------------------ |
| ```word1 WITHIN x [units] word2``` | ```word1``` occurs within ```x``` units of ```word2``` |


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

| Name        | Value                                                                                                                                                                                                                                                                                                                                                       |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Search Text | [david WITHIN 3 WORDS saul](https://ref.ly/logos4/Search?kind=BibleSearch&q=david+WITHIN+3+WORDS+saul&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages) |
|             | [saul BEFORE 3 WORDS david](https://ref.ly/logos4/Search?kind=BibleSearch&q=saul+BEFORE+3+WORDS+david&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages) |
|             | [david AFTER 10 CHARS saul](https://ref.ly/logos4/Search?kind=BibleSearch&q=david+AFTER+10+CHARS+saul&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages) |

## Variations


## Logos Help/References
- https://community.logos.com/kb/articles/884#Proximity_Operators
- 

## Related Searches
- 

## Notes
- 

