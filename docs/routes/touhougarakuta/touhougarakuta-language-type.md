# Touhougarakuta 东方我乐多丛志 - Articles

## Coverage
`index-only`

## Route
- Namespace: `touhougarakuta`
- Namespace Name: `Touhougarakuta 东方我乐多丛志`
- Route Path: `/touhougarakuta/:language/:type`
- Route Name: `Articles`
- Example: `/touhougarakuta/ja/news`
- URL: `touhougarakuta.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `ttyfly`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Languages:

| Chinese | English | Japanese | Korean |
| ------- | ------- | -------- | ------ |
| cn      | en      | ja       | ko     |

Article types:

| Index | Series | Interviews | Novels | Comics | News |
| ----- | ------ | ---------- | ------ | ------ | ---- |
| index | series | interviews | novels | comics | news |

| Music review  | Game review  | Book review  | Where are you   |
| ------------- | ------------ | ------------ | --------------- |
| music\_review | game\_review | book\_review | where\_are\_you |

**Note:** The index type includes all types of articles. Think twice before using it.

## Parameters
- `language`: language
- `type`: article type


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "Languages:\n\n| Chinese | English | Japanese | Korean |\n| ------- | ------- | -------- | ------ |\n| cn      | en      | ja       | ko     |\n\nArticle types:\n\n| Index | Series | Interviews | Novels | Comics | News |\n| ----- | ------ | ---------- | ------ | ------ | ---- |\n| index | series | interviews | novels | comics | news |\n\n| Music review  | Game review  | Book review  | Where are you   |\n| ------------- | ------------ | ------------ | --------------- |\n| music\\_review | game\\_review | book\\_review | where\\_are\\_you |\n\n**Note:** The index type includes all types of articles. Think twice before using it.",
  "example": "/touhougarakuta/ja/news",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "ttyfly"
  ],
  "name": "Articles",
  "parameters": {
    "language": "language",
    "type": "article type"
  },
  "path": "/:language/:type",
  "topFeeds": []
}
```
