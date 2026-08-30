# 远程.work - Remote.work Job Information

## Coverage
`index-only`

## Route
- Namespace: `yuancheng.work`
- Namespace Name: `远程.work`
- Route Path: `/yuancheng.work/:caty?`
- Route Name: `Remote.work Job Information`
- Example: `/yuancheng.work/all`
- URL: `yuancheng.work`
- Language: `_None_`
- Categories: `other`
- Maintainers: `luyuhuang`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| All Jobs | Development | Design | Operation | Product | Function | Other | Marketing | Sales |
| :------: | :---------: | :----: | :-------: | :-----: | :------: | :---: | :-------: | :---: |
|    all   | development | design | operation | product | function | other | marketing | sales |

## Parameters
- `caty`: Job category, default to all


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `yuancheng.work/:caty`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| All Jobs | Development | Design | Operation | Product | Function | Other | Marketing | Sales |\n| :------: | :---------: | :----: | :-------: | :-----: | :------: | :---: | :-------: | :---: |\n|    all   | development | design | operation | product | function | other | marketing | sales |",
  "example": "/yuancheng.work/all",
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "luyuhuang"
  ],
  "name": "Remote.work Job Information",
  "parameters": {
    "caty": "Job category, default to all"
  },
  "path": "/:caty?",
  "radar": [
    {
      "source": [
        "yuancheng.work/:caty"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
