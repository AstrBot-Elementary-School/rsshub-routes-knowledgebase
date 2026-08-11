# 吉林大学 - 物理学院

## Coverage
`index-only`

## Route
- Namespace: `jlu`
- Namespace Name: `吉林大学`
- Route Path: `/jlu/phy/:category/:column/:subcolumn?`
- Route Name: `物理学院`
- Example: `/jlu/phy/xzgz/tzgg`
- URL: `phy.jlu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `tsurumi-yizhou`
- Source Location: `phy/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类，为「行政工作」、「科学研究」、「人才培养」的拼音小写首字母。
- `column`: 栏目，当分类为「行政工作」时，为「通知公告」、「学院新闻」、「学院文件」的拼音小写首字母。当分类为「科学研究」时，为「科研动态」、「学术活动」的拼音小写首字母。当分类为「人才培养」时。为「本科生教育」、「研究生教育」、「学团工作」的拼音小写首字母。
- `subcolumn`: 子栏目。当栏目为「本科生教育」时，为「本科资讯」的拼音大写首字母，或为「教育思想大讨论系列活动」、「培养方案」的拼音小写首字母。当栏目为「研究生教育」时，为「教学通知」的拼音小写首字母。


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
  - `phy.jlu.edu.cn/:category/:column`
  - `phy.jlu.edu.cn/:category/:column/:subcolumn`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/jlu/phy/xzgz/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "phy/index.ts",
  "maintainers": [
    "tsurumi-yizhou"
  ],
  "name": "物理学院",
  "parameters": {
    "category": "分类，为「行政工作」、「科学研究」、「人才培养」的拼音小写首字母。",
    "column": "栏目，当分类为「行政工作」时，为「通知公告」、「学院新闻」、「学院文件」的拼音小写首字母。当分类为「科学研究」时，为「科研动态」、「学术活动」的拼音小写首字母。当分类为「人才培养」时。为「本科生教育」、「研究生教育」、「学团工作」的拼音小写首字母。",
    "subcolumn": "子栏目。当栏目为「本科生教育」时，为「本科资讯」的拼音大写首字母，或为「教育思想大讨论系列活动」、「培养方案」的拼音小写首字母。当栏目为「研究生教育」时，为「教学通知」的拼音小写首字母。"
  },
  "path": "/phy/:category/:column/:subcolumn?",
  "radar": [
    {
      "source": [
        "phy.jlu.edu.cn/:category/:column",
        "phy.jlu.edu.cn/:category/:column/:subcolumn"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "吉林大学物理学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76929307340722176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://phy.jlu.edu.cn/",
      "title": "吉林大学物理学院",
      "type": "feed",
      "url": "rsshub://jlu/phy/xzgz/tzgg"
    }
  ],
  "url": "phy.jlu.edu.cn"
}
```
