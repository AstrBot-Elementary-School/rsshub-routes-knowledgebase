# 喜马拉雅 - 专辑

## Coverage
`index-only`

## Route
- Namespace: `ximalaya`
- Namespace Name: `喜马拉雅`
- Route Path: `/ximalaya/:type/:id/:all?/:shownote?`
- Route Name: `专辑`
- Example: `/ximalaya/album/299146`
- URL: `ximalaya.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `lengthmin, jjeejj, prnake`
- Source Location: `album.ts`
- Source Module: `_None_`

## Description
目前喜马拉雅的 API 只能一集一集的获取各节目上的 ShowNote，会极大的占用系统资源，所以默认为不获取节目的 ShowNote。

::: warning
专辑类型即 url 中的分类拼音，使用通用分类 `album` 通常是可行的，专辑 id 是跟在**分类拼音**后的那个 id, 不要输成某集的 id 了

**付费内容需要配置好已购买账户的 token 才能收听，详情见部署页面的配置模块**
:::

## Parameters
- `type`: 专辑类型, 通常可以使用 `album`，可在对应专辑页面的 URL 中找到
- `id`: 专辑 id, 可在对应专辑页面的 URL 中找到
- `all`: 是否需要获取全部节目，填入 `1`、`true`、`all` 视为获取所有节目，填入其他则不获取。
- `shownote`: 是否需要获取节目的 ShowNote，填入 `1`、`true`,`shownote` 视为获取，填入其他则不获取。


## Features
- `requireConfig`: [{"description": "", "name": "XIMALAYA_TOKEN"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "目前喜马拉雅的 API 只能一集一集的获取各节目上的 ShowNote，会极大的占用系统资源，所以默认为不获取节目的 ShowNote。\n\n::: warning\n专辑类型即 url 中的分类拼音，使用通用分类 `album` 通常是可行的，专辑 id 是跟在**分类拼音**后的那个 id, 不要输成某集的 id 了\n\n**付费内容需要配置好已购买账户的 token 才能收听，详情见部署页面的配置模块**\n:::",
  "example": "/ximalaya/album/299146",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "XIMALAYA_TOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "album.ts",
  "maintainers": [
    "lengthmin",
    "jjeejj",
    "prnake"
  ],
  "name": "专辑",
  "parameters": {
    "all": "是否需要获取全部节目，填入 `1`、`true`、`all` 视为获取所有节目，填入其他则不获取。",
    "id": "专辑 id, 可在对应专辑页面的 URL 中找到",
    "shownote": "是否需要获取节目的 ShowNote，填入 `1`、`true`,`shownote` 视为获取，填入其他则不获取。",
    "type": "专辑类型, 通常可以使用 `album`，可在对应专辑页面的 URL 中找到"
  },
  "path": "/:type/:id/:all?/:shownote?",
  "topFeeds": []
}
```
