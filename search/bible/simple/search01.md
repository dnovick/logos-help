# 01: Basic Search

## Concepts

- Basic Bible word search

- AND, OR and NOT search terms

- Parentheses for grouping words.

## Description

This is just a basic Bible search that searches for one or more words. Words can be combined with either AND (implicit) OR, or NOT. These terms have the intuitive meanings:

NOTE: The search context may be either "Verse" or "Chapter" and is set with the "Match within" criteria of the search.

| Term              | Meaning                                                                                                    |
| ----------------- | ---------------------------------------------------------------------------------------------------------- |
| `word1 AND word2` | Both `word1` and `word2` both appear within the search context.                                            |
| `word1 OR word2`  | Either (or both) `word1` or `word2` appear within the search context.                                      |
| `NOT word1`       | `word1` does not appear within the search context. This is usually used in combination with `AND` or `OR`. |

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

| Search Text                                                                                                                                                                                                                                                                                                                       |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [lord god](https://ref.ly/logos4/Search?kind=BibleSearch&q=lord+god&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages)         |
| [lord AND god](https://ref.ly/logos4/Search?kind=BibleSearch&q=lord+AND+god&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages) |
| [lord god](https://ref.ly/logos4/Search?kind=BibleSearch&q=lord+god&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages)         |
| [lord NOT god](https://ref.ly/logos4/Search?kind=BibleSearch&q=lord+NOT+god&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=analysis) |
## Variations

### A: Case Matching

#### Description

By default, Logos searches are case insensitive. Settting `Match case` will make the search case sensitive.

#### Search Configuration

| Name               | Value                       |
| ------------------ | --------------------------- |
| Search Type        | Bible                       |
| Bible              | KJV 1900                    |
| Search Fields      | All Bible Text              |
| Match Within       | Verse                       |
| Search Filter      | Old Testament               |
| **Match Criteria** | **- [x] Match case**        |
|                    | - [ ] Match all forms       |
|                    | Reference matching: Default |

| Search Text                                                                                                                                                                                                                                                                                                                 |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[Lord God](https://ref.ly/logos4/Search?kind=BibleSearch&q=Lord+God&syntax=v2&documentlevel=verse&match=case&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages)** |

### B: Match All Forms (stemming)

#### Description

By default, Logos performs an exact match on the search term. However, in some cases, it is desirable to return all forms of the search term (e.g., plurals, -ed for past tense, etc.). Setting `Match all forms` enables this expanded search matching.

#### Search Configuration

| Name           | Value                       |
| -------------- | --------------------------- |
| Search Type    | Bible                       |
| Bible          | KJV 1900                    |
| Search Fields  | All Bible Text              |
| Match Within   | Verse                       |
| Search Filter  | Old Testament               |
| Match Criteria | - [ ] Match case            |
|                | - [x] Match all forms       |
|                | Reference matching: Default |

| Search Text                                                                                                                                                                                                                                                                                                     |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [love](https://ref.ly/logos4/Search?kind=BibleSearch&q=love&syntax=v2&documentlevel=verse&match=stem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=analysis) |
|                                                                                                                                                                                                                                                                                                                 |
### C: More Than Two Words

#### Description

When searching for more than two words and using a combination of the `AND` and `OR` terms, it may be necessary to use parentheses to ensure the intended search is executed.

#### Search Configuration

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

| Search Text                                                                                                                                                                                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [(lord OR god) AND almighty](https://ref.ly/logos4/Search?kind=BibleSearch&q=(lord+OR+god)+AND+almighty&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages) |
| [(lord AND god) OR almighty](https://ref.ly/logos4/Search?kind=BibleSearch&q=(lord+AND+god)+OR+almighty&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages) |
|                                                                                                                                                                                                                                                                                                                                                               |

### D: Exclusive OR (XOR)

#### Description
An exclusive OR (XOR) search is used when one wants to find cases where 1 of 2 terms are present, excluding those where both are present.

While Logos does not have an explicit XOR operator, the same results can be achieved by combining 2 search clauses, one with an AND and one with an OR.

#### Search Configuration

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

| Search Text                                                                                                                                                                                                                                                                                                                                                                   |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [(love OR hate) NOT (love AND hate)](https://ref.ly/logos4/Search?kind=BibleSearch&q=(love+OR+hate)+NOT+(love+AND+hate)&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=analysis) |
|                                                                                                                                                                                                                                                                                                                                                                               |
|                                                                                                                                                                                                                                                                                                                                                                               |



## Logos Help/References
- [How do I use search operators?](https://support.logos.com/hc/en-us/articles/360044454351-How-do-I-use-Search-Operators-in-Logos#AND)

  
## Related Searches
- [Wildcards](search02.md) 
- 
## Notes
-

