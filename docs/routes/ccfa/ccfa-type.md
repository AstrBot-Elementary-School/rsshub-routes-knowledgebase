# 中国连锁经营协会 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ccfa`
- Namespace Name: `中国连锁经营协会`
- Route Path: `/ccfa/:type?`
- Route Name: `分类`
- Example: `/ccfa/1`
- URL: `www.ccfa.org.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
::: tip
若订阅 [协会动态](https://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=1)，网址为 `https://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=1`。截取 `https://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=` 到末尾的部分 `1` 作为参数填入，此时路由为 [`/ccfa/1`](https://rsshub.app/ccfa/1)。
:::

| 分类                                                                         | ID                                     |
| ---------------------------------------------------------------------------- | -------------------------------------- |
| [协会动态](http://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=1)          | [1](https://rsshub.app/ccfa/1)         |
| [行业动态](http://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=2)          | [2](https://rsshub.app/ccfa/2)         |
| [政策 / 报告 / 标准](http://www.ccfa.org.cn/portal/cn/hybz_list.jsp?type=33) | [33](https://rsshub.app/ccfa/33)       |
| [行业统计](http://www.ccfa.org.cn/portal/cn/lsbq.jsp?type=10003)             | [10003](https://rsshub.app/ccfa/10003) |
| [创新案例](http://www.ccfa.org.cn/portal/cn/hybzs_list.jsp?type=10004)       | [10004](https://rsshub.app/ccfa/10004) |
| [党建工作](http://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=7)          | [7](https://rsshub.app/ccfa/7)         |
| [新消费论坛](http://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=10005)    | [10005](https://rsshub.app/ccfa/10005) |

#### [政策 / 报告 / 标准](http://www.ccfa.org.cn/portal/cn/hybz_list.jsp?type=33)

| 分类                                                                            | ID                               |
| ------------------------------------------------------------------------------- | -------------------------------- |
| [行业报告](http://www.ccfa.org.cn/portal/cn/hybz_list.jsp?type=33)              | [33](https://rsshub.app/ccfa/33) |
| [行业标准](http://www.ccfa.org.cn/portal/cn/hybz_list.jsp?type=34)              | [34](https://rsshub.app/ccfa/34) |
| [行业政策](http://www.ccfa.org.cn/portal/cn/fangyizhuanqu_list.jsp?type=39)     | [39](https://rsshub.app/ccfa/39) |
| [政策权威解读](http://www.ccfa.org.cn/portal/cn/fangyizhuanqu_list.jsp?type=40) | [40](https://rsshub.app/ccfa/40) |

## Parameters
- `type`: 分类，默认为 `1`，即协会动态，可在对应分类页 URL 中找到


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
- `title`: `协会动态`
- `source`:
  - `www.ccfa.org.cn/portal/cn/xiehui_list.jsp`
- `target`: `/1`
### Rule 2
- `title`: `行业动态`
- `source`:
  - `www.ccfa.org.cn/portal/cn/xiehui_list.jsp`
- `target`: `/2`
### Rule 3
- `title`: `政策/报告/标准`
- `source`:
  - `www.ccfa.org.cn/portal/cn/hybz_list.jsp`
- `target`: `/33`
### Rule 4
- `title`: `行业统计`
- `source`:
  - `www.ccfa.org.cn/portal/cn/lsbq.jsp`
- `target`: `/10003`
### Rule 5
- `title`: `创新案例`
- `source`:
  - `www.ccfa.org.cn/portal/cn/hybzs_list.jsp`
- `target`: `/10004`
### Rule 6
- `title`: `党建工作`
- `source`:
  - `www.ccfa.org.cn/portal/cn/xiehui_list.jsp`
- `target`: `/7`
### Rule 7
- `title`: `新消费论坛`
- `source`:
  - `www.ccfa.org.cn/portal/cn/xiehui_list.jsp`
- `target`: `/10005`
### Rule 8
- `title`: `政策/报告/标准 - 行业报告`
- `source`:
  - `www.ccfa.org.cn/portal/cn/hybz_list.jsp`
- `target`: `/33`
### Rule 9
- `title`: `政策/报告/标准 - 行业标准`
- `source`:
  - `www.ccfa.org.cn/portal/cn/hybz_list.jsp`
- `target`: `/34`
### Rule 10
- `title`: `政策/报告/标准 - 行业政策`
- `source`:
  - `www.ccfa.org.cn/portal/cn/fangyizhuanqu_list.jsp`
- `target`: `/39`
### Rule 11
- `title`: `政策/报告/标准 - 政策权威解读`
- `source`:
  - `www.ccfa.org.cn/portal/cn/fangyizhuanqu_list.jsp`
- `target`: `/40`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [协会动态](https://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=1)，网址为 `https://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=1`。截取 `https://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=` 到末尾的部分 `1` 作为参数填入，此时路由为 [`/ccfa/1`](https://rsshub.app/ccfa/1)。\n:::\n\n| 分类                                                                         | ID                                     |\n| ---------------------------------------------------------------------------- | -------------------------------------- |\n| [协会动态](http://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=1)          | [1](https://rsshub.app/ccfa/1)         |\n| [行业动态](http://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=2)          | [2](https://rsshub.app/ccfa/2)         |\n| [政策 / 报告 / 标准](http://www.ccfa.org.cn/portal/cn/hybz_list.jsp?type=33) | [33](https://rsshub.app/ccfa/33)       |\n| [行业统计](http://www.ccfa.org.cn/portal/cn/lsbq.jsp?type=10003)             | [10003](https://rsshub.app/ccfa/10003) |\n| [创新案例](http://www.ccfa.org.cn/portal/cn/hybzs_list.jsp?type=10004)       | [10004](https://rsshub.app/ccfa/10004) |\n| [党建工作](http://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=7)          | [7](https://rsshub.app/ccfa/7)         |\n| [新消费论坛](http://www.ccfa.org.cn/portal/cn/xiehui_list.jsp?type=10005)    | [10005](https://rsshub.app/ccfa/10005) |\n\n#### [政策 / 报告 / 标准](http://www.ccfa.org.cn/portal/cn/hybz_list.jsp?type=33)\n\n| 分类                                                                            | ID                               |\n| ------------------------------------------------------------------------------- | -------------------------------- |\n| [行业报告](http://www.ccfa.org.cn/portal/cn/hybz_list.jsp?type=33)              | [33](https://rsshub.app/ccfa/33) |\n| [行业标准](http://www.ccfa.org.cn/portal/cn/hybz_list.jsp?type=34)              | [34](https://rsshub.app/ccfa/34) |\n| [行业政策](http://www.ccfa.org.cn/portal/cn/fangyizhuanqu_list.jsp?type=39)     | [39](https://rsshub.app/ccfa/39) |\n| [政策权威解读](http://www.ccfa.org.cn/portal/cn/fangyizhuanqu_list.jsp?type=40) | [40](https://rsshub.app/ccfa/40) |",
  "example": "/ccfa/1",
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
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "type": "分类，默认为 `1`，即协会动态，可在对应分类页 URL 中找到"
  },
  "path": "/:type?",
  "radar": [
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/xiehui_list.jsp"
      ],
      "target": "/1",
      "title": "协会动态"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/xiehui_list.jsp"
      ],
      "target": "/2",
      "title": "行业动态"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/hybz_list.jsp"
      ],
      "target": "/33",
      "title": "政策/报告/标准"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/lsbq.jsp"
      ],
      "target": "/10003",
      "title": "行业统计"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/hybzs_list.jsp"
      ],
      "target": "/10004",
      "title": "创新案例"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/xiehui_list.jsp"
      ],
      "target": "/7",
      "title": "党建工作"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/xiehui_list.jsp"
      ],
      "target": "/10005",
      "title": "新消费论坛"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/hybz_list.jsp"
      ],
      "target": "/33",
      "title": "政策/报告/标准 - 行业报告"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/hybz_list.jsp"
      ],
      "target": "/34",
      "title": "政策/报告/标准 - 行业标准"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/fangyizhuanqu_list.jsp"
      ],
      "target": "/39",
      "title": "政策/报告/标准 - 行业政策"
    },
    {
      "source": [
        "www.ccfa.org.cn/portal/cn/fangyizhuanqu_list.jsp"
      ],
      "target": "/40",
      "title": "政策/报告/标准 - 政策权威解读"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.ccfa.org.cn"
}
```
