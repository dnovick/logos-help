# 01: Basic Search

## Concepts
- Basic Bible word search
- AND vs OR search terms
- Parentheses for grouping words.

## Description
This is just a basic Bible search that searches for one or more words. Words can be combined with either AND (implicit) or OR.

## Search Configuration

**Search Type:** Bible

**Bible:** KJV 1900

**Search Fields:** All Bible Text

**Match Within**: Verse

**Search Filter:** Old Testament

**Match Criteria:** 
- [ ] Match case
- [ ] Match all forms
- Reference Matching: Default

## Search Text

- [lord god](https://ref.ly/logos4/Search?kind=BibleSearch&q=lord+god&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages)
- [lord AND god](https://ref.ly/logos4/Search?kind=BibleSearch&q=lord+AND+god&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages)
- [lord OR god](https://ref.ly/logos4/Search?kind=BibleSearch&q=lord+OR+god&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages)


## Variations

### A: Case Matching

#### Description

By default, Logos searches are case insensitive. Settting ```Match case``` will make the search case sensitive.

#### Search Configuration

**Match Criteria:** 
- [x] Match case
- [ ] Match all forms
- Reference Matching: Default

#### Search Text

-[Lord God](https://ref.ly/logos4/Search?kind=BibleSearch&q=Lord+God&syntax=v2&documentlevel=verse&match=case&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages) 

### B: More Than Two Words

#### Description

When searching for more than two words and using a combination of the ```AND``` and ```OR``` terms, it may be necessary to use parentheses to ensure the intended search is executed.

#### Search Text

- [(lord OR god) AND almighty](https://ref.ly/logos4/Search?kind=BibleSearch&q=(lord+OR+god)+AND+almighty&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages)

- [(lord AND god) OR almighty](https://ref.ly/logos4/Search?kind=BibleSearch&q=(lord+AND+god)+OR+almighty&syntax=v2&documentlevel=verse&match=nostem&references=bible%2bkjv.1-17.10.3%0abible%2bkjv.18-39&in=raw%3aTop%7cDataType%3dbible%7cResourceType%3dtext.monograph.bible%7cResultLimit%3d1%7cTitle%3dTop%2520Bible%2520(KJV%25201900)&viewkind=passages)

## Logos Help/References
- [How do I use search operators?](https://support.logos.com/hc/en-us/articles/360044454351-How-do-I-use-Search-Operators-in-Logos#AND)


## Related Searches
- 

## Notes

- 

