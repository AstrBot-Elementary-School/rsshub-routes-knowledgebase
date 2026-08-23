# iciba - Daily English Sentence

## Coverage
`index-only`

## Route
- Namespace: `iciba`
- Namespace Name: `iciba`
- Route Path: `/iciba/:days?/:img_type?`
- Route Name: `Daily English Sentence`
- Example: `/iciba/7/poster`
- URL: `news.iciba.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `mashirozx`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| `:img_type` | image style    |
| ----------- | -------------- |
| original    | Original size  |
| medium      | Medium size    |
| thumbnail   | Thumbnail size |
| poster      | Art poster     |

## Parameters
- `days`: number of items to show (min = 1, max = 7, default = 1)
- `img_type`: image style


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| `:img_type` | image style    |\n| ----------- | -------------- |\n| original    | Original size  |\n| medium      | Medium size    |\n| thumbnail   | Thumbnail size |\n| poster      | Art poster     |",
  "example": "/iciba/7/poster",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "mashirozx"
  ],
  "name": "Daily English Sentence",
  "parameters": {
    "days": "number of items to show (min = 1, max = 7, default = 1)",
    "img_type": "image style"
  },
  "path": "/:days?/:img_type?",
  "topFeeds": []
}
```
