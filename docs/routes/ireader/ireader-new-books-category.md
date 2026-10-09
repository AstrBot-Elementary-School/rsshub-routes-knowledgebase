# 掌阅 iReader - 新书上架

## Coverage
`index-only`

## Route
- Namespace: `ireader`
- Namespace Name: `掌阅 iReader`
- Route Path: `/ireader/new-books/:category?`
- Route Name: `新书上架`
- Example: `/ireader/new-books/320`
- URL: `pweb.d.ireader.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `DIYgod`
- Source Location: `new-books.ts`
- Source Module: `_None_`

## Description
Uses the website’s newest-first new-book selection (order=update, status=4). Select a native book category using its cid value.

## Parameters
- `category`: 分类 ID，对应网站 cid 参数，默认 320（计算机）。


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `pweb.d.ireader.com/index.php`
  - `www.ireader.com/index.php`
- `target`: `/new-books/320`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "Uses the website’s newest-first new-book selection (order=update, status=4). Select a native book category using its cid value.",
  "example": "/ireader/new-books/320",
  "heat": 0,
  "location": "new-books.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "新书上架",
  "parameters": {
    "category": "分类 ID，对应网站 cid 参数，默认 320（计算机）。"
  },
  "path": "/new-books/:category?",
  "radar": [
    {
      "source": [
        "pweb.d.ireader.com/index.php",
        "www.ireader.com/index.php"
      ],
      "target": "/new-books/320"
    }
  ],
  "topFeeds": []
}
```
