# 中国环球电视网 - Most Read & Most Share

## Coverage
`index-only`

## Route
- Namespace: `cgtn`
- Namespace Name: `中国环球电视网`
- Route Path: `/cgtn/most/:type?/:time?`
- Route Name: `Most Read & Most Share`
- Example: `/cgtn/most/read/day`
- URL: `cgtn.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `most.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Type, `read` as most read, `share` as most share, `read` by default
- `time`: Time range, `all` as all the time, `day` as today, `week` as this week, `month` as this month, `year` as this year, `all` by default


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/cgtn/most/read/day",
  "heat": 0,
  "location": "most.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Most Read & Most Share",
  "parameters": {
    "time": "Time range, `all` as all the time, `day` as today, `week` as this week, `month` as this month, `year` as this year, `all` by default",
    "type": "Type, `read` as most read, `share` as most share, `read` by default"
  },
  "path": "/most/:type?/:time?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
