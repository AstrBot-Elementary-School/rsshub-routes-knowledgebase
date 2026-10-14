# 中国百货商业协会 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `ccagm`
- Namespace Name: `中国百货商业协会`
- Route Path: `/ccagm/:category{.+}?`
- Route Name: `栏目`
- Example: `/ccagm/association-news`
- URL: `www.ccagm.org.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [协会动态](http://www.ccagm.org.cn/association-news)，其源网址为 `http://www.ccagm.org.cn/association-news`，请参考该 URL 指定部分构成参数，此时路由为 [`/ccagm/association-news`](https://rsshub.app/ccagm/association-news)。
:::

<details>
  <summary>更多分类</summary>

| 栏目                                                                                         | ID                                                                                                                      |
| -------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| [协会动态](http://www.ccagm.org.cn/association-news.html)                                    | [association-news](https://rsshub.app/ccagm/association-news)                                                           |
| [会议活动](http://www.ccagm.org.cn/xh-activity/activities-huiyi.html)                        | [xh-activity/activities-huiyi](https://rsshub.app/ccagm/xh-activity/activities-huiyi)                                   |
| [调研与报告](http://www.ccagm.org.cn/xh-activity/bg-yj.html)                                 | [xh-activity/bg-yj](https://rsshub.app/ccagm/xh-activity/bg-yj)                                                         |
| [协会党建](http://www.ccagm.org.cn/xie-hui-dang-jian.html)                                   | [xie-hui-dang-jian](https://rsshub.app/ccagm/xie-hui-dang-jian)                                                         |
| [行业新闻](http://www.ccagm.org.cn/members-info.html)                                        | [members-info](https://rsshub.app/ccagm/members-info)                                                                   |
| [行业研究](http://www.ccagm.org.cn/bg-yj.html)                                               | [bg-yj](https://rsshub.app/ccagm/bg-yj)                                                                                 |
| [行业标准](http://www.ccagm.org.cn/industry-policy/industry-standard.html)                   | [industry-policy/industry-standard](https://rsshub.app/ccagm/industry-policy/industry-standard)                         |
| [法律法规](http://www.ccagm.org.cn/industry-policy/policies-regulations.html)                | [industry-policy/policies-regulations](https://rsshub.app/ccagm/industry-policy/policies-regulations)                   |
| [资料下载](http://www.ccagm.org.cn/download.html)                                            | [download](https://rsshub.app/ccagm/download)                                                                           |
| [工作总结与计划](http://www.ccagm.org.cn/about-association/gong-zuo-zong-jie-yu-ji-hua.html) | [about-association/gong-zuo-zong-jie-yu-ji-hua](https://rsshub.app/ccagm/about-association/gong-zuo-zong-jie-yu-ji-hua) |

</details>

## Parameters
- `category`: {"description": "分类，默认为 `association-news`，即协会动态，可在对应分类页 URL 中找到", "options": [{"label": "协会动态", "value": "association-news"}, {"label": "会议活动", "value": "xh-activity/activities-huiyi"}, {"label": "调研与报告", "value": "xh-activity/bg-yj"}, {"label": "协会党建", "value": "xie-hui-dang-jian"}, {"label": "行业新闻", "value": "members-info"}, {"label": "行业研究", "value": "bg-yj"}, {"label": "行业标准", "value": "industry-policy/industry-standard"}, {"label": "法律法规", "value": "industry-policy/policies-regulations"}, {"label": "资料下载", "value": "download"}, {"label": "工作总结与计划", "value": "about-association/gong-zuo-zong-jie-yu-ji-hua"}]}


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
  - `www.ccagm.org.cn/`
- `target`: `/association-news`
### Rule 2
- `title`: `协会动态`
- `source`:
  - `www.ccagm.org.cn/association-news`
  - `www.ccagm.org.cn/association-news.html`
- `target`: `/association-news`
### Rule 3
- `title`: `会议活动`
- `source`:
  - `www.ccagm.org.cn/xh-activity/activities-huiyi`
  - `www.ccagm.org.cn/xh-activity/activities-huiyi.html`
- `target`: `/xh-activity/activities-huiyi`
### Rule 4
- `title`: `调研与报告`
- `source`:
  - `www.ccagm.org.cn/xh-activity/bg-yj`
  - `www.ccagm.org.cn/xh-activity/bg-yj.html`
- `target`: `/xh-activity/bg-yj`
### Rule 5
- `title`: `协会党建`
- `source`:
  - `www.ccagm.org.cn/xie-hui-dang-jian`
  - `www.ccagm.org.cn/xie-hui-dang-jian.html`
- `target`: `/xie-hui-dang-jian`
### Rule 6
- `title`: `行业新闻`
- `source`:
  - `www.ccagm.org.cn/members-info`
  - `www.ccagm.org.cn/members-info.html`
- `target`: `/members-info`
### Rule 7
- `title`: `行业研究`
- `source`:
  - `www.ccagm.org.cn/bg-yj`
  - `www.ccagm.org.cn/bg-yj.html`
- `target`: `/bg-yj`
### Rule 8
- `title`: `行业标准`
- `source`:
  - `www.ccagm.org.cn/industry-policy/industry-standard`
  - `www.ccagm.org.cn/industry-policy/industry-standard.html`
- `target`: `/industry-policy/industry-standard`
### Rule 9
- `title`: `法律法规`
- `source`:
  - `www.ccagm.org.cn/industry-policy/policies-regulations`
  - `www.ccagm.org.cn/industry-policy/policies-regulations.html`
- `target`: `/industry-policy/policies-regulations`
### Rule 10
- `title`: `资料下载`
- `source`:
  - `www.ccagm.org.cn/download`
  - `www.ccagm.org.cn/download.html`
- `target`: `/download`
### Rule 11
- `title`: `工作总结与计划`
- `source`:
  - `www.ccagm.org.cn/about-association/gong-zuo-zong-jie-yu-ji-hua`
  - `www.ccagm.org.cn/about-association/gong-zuo-zong-jie-yu-ji-hua.html`
- `target`: `/about-association/gong-zuo-zong-jie-yu-ji-hua`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [协会动态](http://www.ccagm.org.cn/association-news)，其源网址为 `http://www.ccagm.org.cn/association-news`，请参考该 URL 指定部分构成参数，此时路由为 [`/ccagm/association-news`](https://rsshub.app/ccagm/association-news)。\n:::\n\n<details>\n  <summary>更多分类</summary>\n\n| 栏目                                                                                         | ID                                                                                                                      |\n| -------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |\n| [协会动态](http://www.ccagm.org.cn/association-news.html)                                    | [association-news](https://rsshub.app/ccagm/association-news)                                                           |\n| [会议活动](http://www.ccagm.org.cn/xh-activity/activities-huiyi.html)                        | [xh-activity/activities-huiyi](https://rsshub.app/ccagm/xh-activity/activities-huiyi)                                   |\n| [调研与报告](http://www.ccagm.org.cn/xh-activity/bg-yj.html)                                 | [xh-activity/bg-yj](https://rsshub.app/ccagm/xh-activity/bg-yj)                                                         |\n| [协会党建](http://www.ccagm.org.cn/xie-hui-dang-jian.html)                                   | [xie-hui-dang-jian](https://rsshub.app/ccagm/xie-hui-dang-jian)                                                         |\n| [行业新闻](http://www.ccagm.org.cn/members-info.html)                                        | [members-info](https://rsshub.app/ccagm/members-info)                                                                   |\n| [行业研究](http://www.ccagm.org.cn/bg-yj.html)                                               | [bg-yj](https://rsshub.app/ccagm/bg-yj)                                                                                 |\n| [行业标准](http://www.ccagm.org.cn/industry-policy/industry-standard.html)                   | [industry-policy/industry-standard](https://rsshub.app/ccagm/industry-policy/industry-standard)                         |\n| [法律法规](http://www.ccagm.org.cn/industry-policy/policies-regulations.html)                | [industry-policy/policies-regulations](https://rsshub.app/ccagm/industry-policy/policies-regulations)                   |\n| [资料下载](http://www.ccagm.org.cn/download.html)                                            | [download](https://rsshub.app/ccagm/download)                                                                           |\n| [工作总结与计划](http://www.ccagm.org.cn/about-association/gong-zuo-zong-jie-yu-ji-hua.html) | [about-association/gong-zuo-zong-jie-yu-ji-hua](https://rsshub.app/ccagm/about-association/gong-zuo-zong-jie-yu-ji-hua) |\n\n</details>",
  "example": "/ccagm/association-news",
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
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "category": {
      "description": "分类，默认为 `association-news`，即协会动态，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "协会动态",
          "value": "association-news"
        },
        {
          "label": "会议活动",
          "value": "xh-activity/activities-huiyi"
        },
        {
          "label": "调研与报告",
          "value": "xh-activity/bg-yj"
        },
        {
          "label": "协会党建",
          "value": "xie-hui-dang-jian"
        },
        {
          "label": "行业新闻",
          "value": "members-info"
        },
        {
          "label": "行业研究",
          "value": "bg-yj"
        },
        {
          "label": "行业标准",
          "value": "industry-policy/industry-standard"
        },
        {
          "label": "法律法规",
          "value": "industry-policy/policies-regulations"
        },
        {
          "label": "资料下载",
          "value": "download"
        },
        {
          "label": "工作总结与计划",
          "value": "about-association/gong-zuo-zong-jie-yu-ji-hua"
        }
      ]
    }
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.ccagm.org.cn/"
      ],
      "target": "/association-news"
    },
    {
      "source": [
        "www.ccagm.org.cn/association-news",
        "www.ccagm.org.cn/association-news.html"
      ],
      "target": "/association-news",
      "title": "协会动态"
    },
    {
      "source": [
        "www.ccagm.org.cn/xh-activity/activities-huiyi",
        "www.ccagm.org.cn/xh-activity/activities-huiyi.html"
      ],
      "target": "/xh-activity/activities-huiyi",
      "title": "会议活动"
    },
    {
      "source": [
        "www.ccagm.org.cn/xh-activity/bg-yj",
        "www.ccagm.org.cn/xh-activity/bg-yj.html"
      ],
      "target": "/xh-activity/bg-yj",
      "title": "调研与报告"
    },
    {
      "source": [
        "www.ccagm.org.cn/xie-hui-dang-jian",
        "www.ccagm.org.cn/xie-hui-dang-jian.html"
      ],
      "target": "/xie-hui-dang-jian",
      "title": "协会党建"
    },
    {
      "source": [
        "www.ccagm.org.cn/members-info",
        "www.ccagm.org.cn/members-info.html"
      ],
      "target": "/members-info",
      "title": "行业新闻"
    },
    {
      "source": [
        "www.ccagm.org.cn/bg-yj",
        "www.ccagm.org.cn/bg-yj.html"
      ],
      "target": "/bg-yj",
      "title": "行业研究"
    },
    {
      "source": [
        "www.ccagm.org.cn/industry-policy/industry-standard",
        "www.ccagm.org.cn/industry-policy/industry-standard.html"
      ],
      "target": "/industry-policy/industry-standard",
      "title": "行业标准"
    },
    {
      "source": [
        "www.ccagm.org.cn/industry-policy/policies-regulations",
        "www.ccagm.org.cn/industry-policy/policies-regulations.html"
      ],
      "target": "/industry-policy/policies-regulations",
      "title": "法律法规"
    },
    {
      "source": [
        "www.ccagm.org.cn/download",
        "www.ccagm.org.cn/download.html"
      ],
      "target": "/download",
      "title": "资料下载"
    },
    {
      "source": [
        "www.ccagm.org.cn/about-association/gong-zuo-zong-jie-yu-ji-hua",
        "www.ccagm.org.cn/about-association/gong-zuo-zong-jie-yu-ji-hua.html"
      ],
      "target": "/about-association/gong-zuo-zong-jie-yu-ji-hua",
      "title": "工作总结与计划"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.ccagm.org.cn",
  "view": 0
}
```
