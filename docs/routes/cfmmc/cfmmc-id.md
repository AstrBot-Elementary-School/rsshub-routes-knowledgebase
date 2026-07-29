# 中国期货市场监控中心 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cfmmc`
- Namespace Name: `中国期货市场监控中心`
- Route Path: `/cfmmc/:id{.+}?`
- Route Name: `栏目`
- Example: `/cfmmc/main/noticeannouncement/cfmmcnotice`
- URL: `cfmmc.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
#### 党的建设

| 栏目     | id                                     |
| -------- | -------------------------------------- |
| 党建动态 | main/partybuilding/partybuildingtrends |
| 基层风采 | main/partybuilding/basestyle           |
| 学习园地 | main/partybuilding/learninggarden      |

#### 通知公告

| 栏目             | id                                  |
| ---------------- | ----------------------------------- |
| 中国期货监控公告 | main/noticeannouncement/cfmmcnotice |
| 证监会公告       | main/noticeannouncement/csrcnotice  |
| 上期所公告       | main/noticeannouncement/shfenotice  |
| 郑商所公告       | main/noticeannouncement/czcenotice  |
| 大商所公告       | main/noticeannouncement/dcenotice   |
| 中金所公告       | main/noticeannouncement/cffexnotice |
| 广期所公告       | main/noticeannouncement/gfexnotice  |

#### 焦点新闻

| 栏目     | id                               |
| -------- | -------------------------------- |
| 财经要闻 | main/focusnews/financialnews     |
| 专题聚焦 | main/focusnews/thematicfocus     |
| 金融动态 | main/focusnews/financialdynamics |

#### 保障基金

| 栏目     | id                                    |
| -------- | ------------------------------------- |
| 基金概况 | main/securityfund/fundoverview        |
| 政策法规 | main/securityfund/policiesregulations |
| 公告信息 | main/securityfund/noticeinformation   |

#### 政策法规

| 栏目                 | id                                            |
| -------------------- | --------------------------------------------- |
| 国家法律法规         | main/policiesregulations/lawsregulations      |
| 部门规章及规范性文件 | main/policiesregulations/regulationsnormative |
| 行业法规政策         | main/policiesregulations/industrypolicies     |
| 中国期货监控相关规则 | main/policiesregulations/cfmmcrules           |

## Parameters
- `id`: 栏目 id，见下表，默认为中国期货监控公告


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cfmmc.com/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "#### 党的建设\n\n| 栏目     | id                                     |\n| -------- | -------------------------------------- |\n| 党建动态 | main/partybuilding/partybuildingtrends |\n| 基层风采 | main/partybuilding/basestyle           |\n| 学习园地 | main/partybuilding/learninggarden      |\n\n#### 通知公告\n\n| 栏目             | id                                  |\n| ---------------- | ----------------------------------- |\n| 中国期货监控公告 | main/noticeannouncement/cfmmcnotice |\n| 证监会公告       | main/noticeannouncement/csrcnotice  |\n| 上期所公告       | main/noticeannouncement/shfenotice  |\n| 郑商所公告       | main/noticeannouncement/czcenotice  |\n| 大商所公告       | main/noticeannouncement/dcenotice   |\n| 中金所公告       | main/noticeannouncement/cffexnotice |\n| 广期所公告       | main/noticeannouncement/gfexnotice  |\n\n#### 焦点新闻\n\n| 栏目     | id                               |\n| -------- | -------------------------------- |\n| 财经要闻 | main/focusnews/financialnews     |\n| 专题聚焦 | main/focusnews/thematicfocus     |\n| 金融动态 | main/focusnews/financialdynamics |\n\n#### 保障基金\n\n| 栏目     | id                                    |\n| -------- | ------------------------------------- |\n| 基金概况 | main/securityfund/fundoverview        |\n| 政策法规 | main/securityfund/policiesregulations |\n| 公告信息 | main/securityfund/noticeinformation   |\n\n#### 政策法规\n\n| 栏目                 | id                                            |\n| -------------------- | --------------------------------------------- |\n| 国家法律法规         | main/policiesregulations/lawsregulations      |\n| 部门规章及规范性文件 | main/policiesregulations/regulationsnormative |\n| 行业法规政策         | main/policiesregulations/industrypolicies     |\n| 中国期货监控相关规则 | main/policiesregulations/cfmmcrules           |",
  "example": "/cfmmc/main/noticeannouncement/cfmmcnotice",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，见下表，默认为中国期货监控公告"
  },
  "path": "/:id{.+}?",
  "radar": [
    {
      "source": [
        "cfmmc.com/:id"
      ]
    }
  ],
  "topFeeds": []
}
```
