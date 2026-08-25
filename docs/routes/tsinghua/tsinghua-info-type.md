# 清华大学 - 校内信息发布平台

## Coverage
`index-only`

## Route
- Namespace: `tsinghua`
- Namespace Name: `清华大学`
- Route Path: `/tsinghua/info/:type`
- Route Name: `校内信息发布平台`
- Example: `/tsinghua/info/zhongyao`
- URL: `www.tsinghua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `prnake`
- Source Location: `info.ts`
- Source Module: `_None_`

## Description
| 重要公告 | 教务公告 | 科研通知 | 办公通知 | 海报列表 | 疫情防控 |
| -------- | -------- | -------- | -------- | -------- | :------: |
| zhongyao | jiaowu   | keyan    | bangong  | haibao   |  yiqing  |

::: warning
由于学校通知仅允许校园网访问，需自行部署。
:::

## Parameters
- `type`: 默认为重要公告


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 重要公告 | 教务公告 | 科研通知 | 办公通知 | 海报列表 | 疫情防控 |\n| -------- | -------- | -------- | -------- | -------- | :------: |\n| zhongyao | jiaowu   | keyan    | bangong  | haibao   |  yiqing  |\n\n::: warning\n由于学校通知仅允许校园网访问，需自行部署。\n:::",
  "example": "/tsinghua/info/zhongyao",
  "heat": 0,
  "location": "info.ts",
  "maintainers": [
    "prnake"
  ],
  "name": "校内信息发布平台",
  "parameters": {
    "type": "默认为重要公告"
  },
  "path": "/info/:type",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
