# 学堂在线 - 课程信息

## Coverage
`index-only`

## Route
- Namespace: `xuetangx`
- Namespace Name: `学堂在线`
- Route Path: `/xuetangx/course/:sign`
- Route Name: `课程信息`
- Example: `/xuetangx/course/THU08091000320`
- URL: `www.xuetangx.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `sanmmm`
- Source Location: `course-info.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `sign`: 课程 sign（如 `THU08091000320`），从课程页 URL 中可得到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.xuetangx.com/course/:sign`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/xuetangx/course/THU08091000320",
  "heat": 0,
  "location": "course-info.ts",
  "maintainers": [
    "sanmmm"
  ],
  "name": "课程信息",
  "parameters": {
    "sign": "课程 sign（如 `THU08091000320`），从课程页 URL 中可得到"
  },
  "path": "/course/:sign",
  "radar": [
    {
      "source": [
        "www.xuetangx.com/course/:sign"
      ]
    }
  ],
  "topFeeds": []
}
```
