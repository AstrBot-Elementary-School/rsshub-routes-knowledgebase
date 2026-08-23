# 江南大学 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `jiangnan`
- Namespace Name: `江南大学`
- Route Path: `/jiangnan/jwc/:type?`
- Route Name: `教务处通知`
- Example: `/jiangnan/jwc/all`
- URL: `jiangnan.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `fuzy112`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| all  | tzgg     | ksap     | wjgg     | tmgz     | djks     | xjgl     | bysj     | syjs     |
| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 全部 | 通知公告 | 考试安排 | 违纪公告 | 推免工作 | 等级考试 | 学籍管理 | 毕业设计 | 实验教学 |

| sjcx     | xkjs     | yjszj      | jxgg     | zyjs     | kcjs     | jcjs     | jxcg     | xsbg     |
| -------- | -------- | ---------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 实践创新 | 学科竞赛 | 研究生助教 | 教学改革 | 专业建设 | 课程建设 | 教材建设 | 教学成果 | 学术报告 |

## Parameters
- `type`: 默认为 `all`


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| all  | tzgg     | ksap     | wjgg     | tmgz     | djks     | xjgl     | bysj     | syjs     |\n| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| 全部 | 通知公告 | 考试安排 | 违纪公告 | 推免工作 | 等级考试 | 学籍管理 | 毕业设计 | 实验教学 |\n\n| sjcx     | xkjs     | yjszj      | jxgg     | zyjs     | kcjs     | jcjs     | jxcg     | xsbg     |\n| -------- | -------- | ---------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| 实践创新 | 学科竞赛 | 研究生助教 | 教学改革 | 专业建设 | 课程建设 | 教材建设 | 教学成果 | 学术报告 |",
  "example": "/jiangnan/jwc/all",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "fuzy112"
  ],
  "name": "教务处通知",
  "parameters": {
    "type": "默认为 `all`"
  },
  "path": "/jwc/:type?",
  "topFeeds": []
}
```
