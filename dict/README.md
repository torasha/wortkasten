# Dictionaries for Wortkasten

Every file listed in `index.json` appears in the app under **Load dictionary → Ready-made dictionaries**.

## File format
Tab-separated text (`.tsv`), UTF-8, one word per line:

```
word<TAB>translation<TAB>example<TAB>example translation<TAB>example 2<TAB>translation 2<TAB>example 3<TAB>translation 3
```

Only the first two columns are required; up to three examples per word are supported, and Gap and Sentence use a different one each time. For the Gap exercise, put the word form in the example in curly braces:
`Ich {nehme} an einem Kongress {teil}.`

Tip: build the list in Excel or Google Sheets and save it as “Text (tab-delimited)”, or export a dictionary from the app (Dictionaries → Export).

## index.json
```json
[
  {
    "file": "de-en-b1-verbs-prepositions.tsv",
    "name": "Verbs with prepositions",
    "level": "B1",
    "pair": "DE → EN",
    "words": 16,
    "desc": "Short description"
  }
]
```
`file` and `name` are required; `level` is used for the level filter.
