# 清华大学 - 附属中学

## Coverage
`index-only`

## Route
- Namespace: `tsinghua`
- Namespace Name: `清华大学`
- Route Path: `/tsinghua/thuhs/:category?`
- Route Name: `附属中学`
- Example: `/tsinghua/thuhs/tzgg`
- URL: `www.tsinghua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Aquarius-Situla`
- Source Location: `thuhs.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学生活动 | 教师风采 | 新闻动态 |
| -------- | -------- | -------- | -------- |
| tzgg     | xstd     | jsfc     | xwdt     |

## Parameters
- `category`: 分类，见下表，留空则默认获取通知公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.qhfz.edu.cn/:category.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 学生活动 | 教师风采 | 新闻动态 |\n| -------- | -------- | -------- | -------- |\n| tzgg     | xstd     | jsfc     | xwdt     |",
  "example": "/tsinghua/thuhs/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "thuhs.ts",
  "maintainers": [
    "Aquarius-Situla"
  ],
  "name": "附属中学",
  "parameters": {
    "category": "分类，见下表，留空则默认获取通知公告"
  },
  "path": "/thuhs/:category?",
  "radar": [
    {
      "source": [
        "www.qhfz.edu.cn/:category.htm"
      ]
    }
  ],
  "topFeeds": []
}
```
