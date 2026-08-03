# Hong Kong Department of Health 香港卫生署 - Category

## Coverage
`index-only`

## Route
- Namespace: `hongkong`
- Namespace Name: `Hong Kong Department of Health 香港卫生署`
- Route Path: `/hongkong/chp/:category?/:language?`
- Route Name: `Category`
- Example: `/hongkong/chp`
- URL: `dh.gov.hk/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `chp.ts`
- Source Module: `_None_`

## Description
Category

| Important Topics | Press Releases     | Response Level | Periodicals & Publications | Health Notice |
| ---------------- | ------------------ | -------------- | -------------------------- | ------------- |
| important\_ft    | press\_data\_index | ResponseLevel  | publication                | HealthAlert   |

Language

| English | 中文简体 | 中文繁體 |
| ------- | -------- | -------- |
| en      | zh\_cn   | zh\_tw   |

## Parameters
- `category`: Category, see below, Important Topics by default
- `language`: Language, see below, zh_tw by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `dh.gov.hk/`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Category\n\n| Important Topics | Press Releases     | Response Level | Periodicals & Publications | Health Notice |\n| ---------------- | ------------------ | -------------- | -------------------------- | ------------- |\n| important\\_ft    | press\\_data\\_index | ResponseLevel  | publication                | HealthAlert   |\n\nLanguage\n\n| English | 中文简体 | 中文繁體 |\n| ------- | -------- | -------- |\n| en      | zh\\_cn   | zh\\_tw   |",
  "example": "/hongkong/chp",
  "heat": 0,
  "location": "chp.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category, see below, Important Topics by default",
    "language": "Language, see below, zh_tw by default"
  },
  "path": "/chp/:category?/:language?",
  "radar": [
    {
      "source": [
        "dh.gov.hk/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "dh.gov.hk/"
}
```
