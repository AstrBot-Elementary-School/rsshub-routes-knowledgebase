# 多知网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `duozhi`
- Namespace Name: `多知网`
- Route Path: `/duozhi/:category{.+}?`
- Route Name: `分类`
- Example: `/duozhi/industry`
- URL: `www.duozhi.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `WenryXu, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [行业](http://www.duozhi.com/industry/)，其源网址为 `http://www.duozhi.com/industry/`，请参考该 URL 指定部分构成参数，此时路由为 [`/duozhi/industry`](http://rsshub.app/duozhi/industry)。
:::

| [行业](http://www.duozhi.com/industry/)        | [多知商学院](http://www.duozhi.com/DBS/) | [OpenTalk](http://www.duozhi.com/opentalk/)    |
| ---------------------------------------------- | ---------------------------------------- | ---------------------------------------------- |
| [industry](https://rsshub.app/duozhi/industry) | [DBS](https://rsshub.app/duozhi/DBS)     | [opentalk](https://rsshub.app/duozhi/opentalk) |

#### [行业](http://www.duozhi.com/industry/)

| [观察](http://www.duozhi.com/industry/insight/)                | [早幼教](http://www.duozhi.com/industry/preschool/)                | [家庭教育](http://www.duozhi.com/industry/jiatingjiaoyu/)                  | [K12](http://www.duozhi.com/industry/K12/)             | [素质教育](http://www.duozhi.com/industry/qualityedu/)               |
| -------------------------------------------------------------- | ------------------------------------------------------------------ | -------------------------------------------------------------------------- | ------------------------------------------------------ | -------------------------------------------------------------------- |
| [industry/insight](https://rsshub.app/duozhi/industry/insight) | [industry/preschool](https://rsshub.app/duozhi/industry/preschool) | [industry/jiatingjiaoyu](https://rsshub.app/duozhi/industry/jiatingjiaoyu) | [industry/K12](https://rsshub.app/duozhi/industry/K12) | [industry/qualityedu](https://rsshub.app/duozhi/industry/qualityedu) |

| [职教 / 大学生](http://www.duozhi.com/industry/adult/)     | [教育信息化](http://www.duozhi.com/industry/EduInformatization/)                     | [财报](http://www.duozhi.com/industry/earnings/)                 | [民办学校](http://www.duozhi.com/industry/privateschools/)                   | [留学](http://www.duozhi.com/industry/overseas/)                 |
| ---------------------------------------------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| [industry/adult](https://rsshub.app/duozhi/industry/adult) | [industry/EduInformatization](https://rsshub.app/duozhi/industry/EduInformatization) | [industry/earnings](https://rsshub.app/duozhi/industry/earnings) | [industry/privateschools](https://rsshub.app/duozhi/industry/privateschools) | [industry/overseas](https://rsshub.app/duozhi/industry/overseas) |

## Parameters
- `category`: {"description": "分类，默认为 `industry`，即行业，可在对应分类页 URL 中找到", "options": [{"label": "行业", "value": "industry"}, {"label": "多知商学院", "value": "DBS"}, {"label": "OpenTalk", "value": "opentalk"}, {"label": "行业 - 观察", "value": "industry/insight"}, {"label": "行业 - 早幼教", "value": "industry/preschool"}, {"label": "行业 - 家庭教育", "value": "industry/jiatingjiaoyu"}, {"label": "行业 - K12", "value": "industry/K12"}, {"label": "行业 - 素质教育", "value": "industry/qualityedu"}, {"label": "行业 - 职教/大学生", "value": "industry/adult"}, {"label": "行业 - 教育信息化", "value": "industry/EduInformatization"}, {"label": "行业 - 财报", "value": "industry/earnings"}, {"label": "行业 - 民办学校", "value": "industry/privateschools"}, {"label": "行业 - 留学", "value": "industry/overseas"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.duozhi.com/:category`
- `target`: `/:category`
### Rule 2
- `title`: `行业`
- `source`:
  - `www.duozhi.com/industry/`
- `target`: `/industry`
### Rule 3
- `title`: `多知商学院`
- `source`:
  - `www.duozhi.com/DBS/`
- `target`: `/DBS`
### Rule 4
- `title`: `OpenTalk`
- `source`:
  - `www.duozhi.com/opentalk/`
- `target`: `/opentalk`
### Rule 5
- `title`: `行业 - 观察`
- `source`:
  - `www.duozhi.com/industry/insight/`
- `target`: `/industry/insight`
### Rule 6
- `title`: `行业 - 早幼教`
- `source`:
  - `www.duozhi.com/industry/preschool/`
- `target`: `/industry/preschool`
### Rule 7
- `title`: `行业 - 家庭教育`
- `source`:
  - `www.duozhi.com/industry/jiatingjiaoyu/`
- `target`: `/industry/jiatingjiaoyu`
### Rule 8
- `title`: `行业 - K12`
- `source`:
  - `www.duozhi.com/industry/K12/`
- `target`: `/industry/K12`
### Rule 9
- `title`: `行业 - 素质教育`
- `source`:
  - `www.duozhi.com/industry/qualityedu/`
- `target`: `/industry/qualityedu`
### Rule 10
- `title`: `行业 - 职教/大学生`
- `source`:
  - `www.duozhi.com/industry/adult/`
- `target`: `/industry/adult`
### Rule 11
- `title`: `行业 - 教育信息化`
- `source`:
  - `www.duozhi.com/industry/EduInformatization/`
- `target`: `/industry/EduInformatization`
### Rule 12
- `title`: `行业 - 财报`
- `source`:
  - `www.duozhi.com/industry/earnings/`
- `target`: `/industry/earnings`
### Rule 13
- `title`: `行业 - 民办学校`
- `source`:
  - `www.duozhi.com/industry/privateschools/`
- `target`: `/industry/privateschools`
### Rule 14
- `title`: `行业 - 留学`
- `source`:
  - `www.duozhi.com/industry/overseas/`
- `target`: `/industry/overseas`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [行业](http://www.duozhi.com/industry/)，其源网址为 `http://www.duozhi.com/industry/`，请参考该 URL 指定部分构成参数，此时路由为 [`/duozhi/industry`](http://rsshub.app/duozhi/industry)。\n:::\n\n| [行业](http://www.duozhi.com/industry/)        | [多知商学院](http://www.duozhi.com/DBS/) | [OpenTalk](http://www.duozhi.com/opentalk/)    |\n| ---------------------------------------------- | ---------------------------------------- | ---------------------------------------------- |\n| [industry](https://rsshub.app/duozhi/industry) | [DBS](https://rsshub.app/duozhi/DBS)     | [opentalk](https://rsshub.app/duozhi/opentalk) |\n\n#### [行业](http://www.duozhi.com/industry/)\n\n| [观察](http://www.duozhi.com/industry/insight/)                | [早幼教](http://www.duozhi.com/industry/preschool/)                | [家庭教育](http://www.duozhi.com/industry/jiatingjiaoyu/)                  | [K12](http://www.duozhi.com/industry/K12/)             | [素质教育](http://www.duozhi.com/industry/qualityedu/)               |\n| -------------------------------------------------------------- | ------------------------------------------------------------------ | -------------------------------------------------------------------------- | ------------------------------------------------------ | -------------------------------------------------------------------- |\n| [industry/insight](https://rsshub.app/duozhi/industry/insight) | [industry/preschool](https://rsshub.app/duozhi/industry/preschool) | [industry/jiatingjiaoyu](https://rsshub.app/duozhi/industry/jiatingjiaoyu) | [industry/K12](https://rsshub.app/duozhi/industry/K12) | [industry/qualityedu](https://rsshub.app/duozhi/industry/qualityedu) |\n\n| [职教 / 大学生](http://www.duozhi.com/industry/adult/)     | [教育信息化](http://www.duozhi.com/industry/EduInformatization/)                     | [财报](http://www.duozhi.com/industry/earnings/)                 | [民办学校](http://www.duozhi.com/industry/privateschools/)                   | [留学](http://www.duozhi.com/industry/overseas/)                 |\n| ---------------------------------------------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------- |\n| [industry/adult](https://rsshub.app/duozhi/industry/adult) | [industry/EduInformatization](https://rsshub.app/duozhi/industry/EduInformatization) | [industry/earnings](https://rsshub.app/duozhi/industry/earnings) | [industry/privateschools](https://rsshub.app/duozhi/industry/privateschools) | [industry/overseas](https://rsshub.app/duozhi/industry/overseas) |",
  "example": "/duozhi/industry",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "WenryXu",
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": {
      "description": "分类，默认为 `industry`，即行业，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "行业",
          "value": "industry"
        },
        {
          "label": "多知商学院",
          "value": "DBS"
        },
        {
          "label": "OpenTalk",
          "value": "opentalk"
        },
        {
          "label": "行业 - 观察",
          "value": "industry/insight"
        },
        {
          "label": "行业 - 早幼教",
          "value": "industry/preschool"
        },
        {
          "label": "行业 - 家庭教育",
          "value": "industry/jiatingjiaoyu"
        },
        {
          "label": "行业 - K12",
          "value": "industry/K12"
        },
        {
          "label": "行业 - 素质教育",
          "value": "industry/qualityedu"
        },
        {
          "label": "行业 - 职教/大学生",
          "value": "industry/adult"
        },
        {
          "label": "行业 - 教育信息化",
          "value": "industry/EduInformatization"
        },
        {
          "label": "行业 - 财报",
          "value": "industry/earnings"
        },
        {
          "label": "行业 - 民办学校",
          "value": "industry/privateschools"
        },
        {
          "label": "行业 - 留学",
          "value": "industry/overseas"
        }
      ]
    }
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.duozhi.com/:category"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "www.duozhi.com/industry/"
      ],
      "target": "/industry",
      "title": "行业"
    },
    {
      "source": [
        "www.duozhi.com/DBS/"
      ],
      "target": "/DBS",
      "title": "多知商学院"
    },
    {
      "source": [
        "www.duozhi.com/opentalk/"
      ],
      "target": "/opentalk",
      "title": "OpenTalk"
    },
    {
      "source": [
        "www.duozhi.com/industry/insight/"
      ],
      "target": "/industry/insight",
      "title": "行业 - 观察"
    },
    {
      "source": [
        "www.duozhi.com/industry/preschool/"
      ],
      "target": "/industry/preschool",
      "title": "行业 - 早幼教"
    },
    {
      "source": [
        "www.duozhi.com/industry/jiatingjiaoyu/"
      ],
      "target": "/industry/jiatingjiaoyu",
      "title": "行业 - 家庭教育"
    },
    {
      "source": [
        "www.duozhi.com/industry/K12/"
      ],
      "target": "/industry/K12",
      "title": "行业 - K12"
    },
    {
      "source": [
        "www.duozhi.com/industry/qualityedu/"
      ],
      "target": "/industry/qualityedu",
      "title": "行业 - 素质教育"
    },
    {
      "source": [
        "www.duozhi.com/industry/adult/"
      ],
      "target": "/industry/adult",
      "title": "行业 - 职教/大学生"
    },
    {
      "source": [
        "www.duozhi.com/industry/EduInformatization/"
      ],
      "target": "/industry/EduInformatization",
      "title": "行业 - 教育信息化"
    },
    {
      "source": [
        "www.duozhi.com/industry/earnings/"
      ],
      "target": "/industry/earnings",
      "title": "行业 - 财报"
    },
    {
      "source": [
        "www.duozhi.com/industry/privateschools/"
      ],
      "target": "/industry/privateschools",
      "title": "行业 - 民办学校"
    },
    {
      "source": [
        "www.duozhi.com/industry/overseas/"
      ],
      "target": "/industry/overseas",
      "title": "行业 - 留学"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.duozhi.com",
  "view": 0
}
```
