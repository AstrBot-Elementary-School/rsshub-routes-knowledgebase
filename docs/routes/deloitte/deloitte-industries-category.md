# Deloitte - Articles

## Coverage
`index-only`

## Route
- Namespace: `deloitte`
- Namespace Name: `Deloitte`
- Route Path: `/deloitte/industries/:category?`
- Route Name: `Articles`
- Example: `/deloitte/industries/consumer`
- URL: `www2.deloitte.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `laampui`
- Source Location: `industries.ts`
- Source Module: `_None_`

## Description
| 消费行业 | 能源、资源及工业行业 | 金融服务行业       | 政府及公共服务    | 生命科学与医疗            | 科技、传媒及电信行业 |
| -------- | -------------------- | ------------------ | ----------------- | ------------------------- | -------------------- |
| consumer | energy               | financial-services | government-public | life-sciences-health-care | tmt                  |

## Parameters
- `category`: 默认为 energy


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "| 消费行业 | 能源、资源及工业行业 | 金融服务行业       | 政府及公共服务    | 生命科学与医疗            | 科技、传媒及电信行业 |\n| -------- | -------------------- | ------------------ | ----------------- | ------------------------- | -------------------- |\n| consumer | energy               | financial-services | government-public | life-sciences-health-care | tmt                  |",
  "example": "/deloitte/industries/consumer",
  "heat": 0,
  "location": "industries.ts",
  "maintainers": [
    "laampui"
  ],
  "name": "Articles",
  "parameters": {
    "category": "默认为 energy"
  },
  "path": "/industries/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
