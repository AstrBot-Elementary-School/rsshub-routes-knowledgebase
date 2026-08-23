# 劍心．回憶 - 分类

## Coverage
`index-only`

## Route
- Namespace: `kenshin`
- Namespace Name: `劍心．回憶`
- Route Path: `/kenshin/:category?/:type?`
- Route Name: `分类`
- Example: `/kenshin`
- URL: `kenshin.hk`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
如 `藝能新聞` 的 `日劇新聞` 分类，路由为 `/jnews/news_drama`
:::

藝能新聞 jnews

| 日劇新聞    | 日影新聞    | 日樂新聞    | 日藝新聞            |
| ----------- | ----------- | ----------- | ------------------- |
| news\_drama | news\_movie | news\_music | news\_entertainment |

| 動漫新聞  | 藝人美照     | 清涼寫真   | 日本廣告 | 其他日聞     |
| --------- | ------------ | ---------- | -------- | ------------ |
| news\_acg | artist-photo | photoalbum | jpcm     | news\_others |

旅遊情報 jpnews

| 日本美食情報 | 日本甜點情報  | 日本零食情報  | 日本飲品情報  | 日本景點情報       |
| ------------ | ------------- | ------------- | ------------- | ------------------ |
| jpnews-food  | jpnews-sweets | jpnews-okashi | jpnews-drinks | jpnews-attractions |

| 日本玩樂情報 | 日本住宿情報 | 日本活動情報  | 日本購物情報    | 日本社會情報   |
| ------------ | ------------ | ------------- | --------------- | -------------- |
| jpnews-play  | jpnews-hotel | jpnews-events | jpnews-shopping | jpnews-society |

| 日本交通情報   | 日本天氣情報   |
| -------------- | -------------- |
| jpnews-traffic | jpnews-weather |

日劇世界 jdrama

| 每周劇評              | 日劇總評             | 資料情報    |
| --------------------- | -------------------- | ----------- |
| drama\_review\_weekly | drama\_review\_final | drama\_data |

| 深度日劇    | 收視報告      | 日劇專欄      | 劇迷互動           |
| ----------- | ------------- | ------------- | ------------------ |
| drama\_deep | drama\_rating | drama\_column | drama\_interactive |

## Parameters
- `category`: 分类，见下表，默认为首页
- `type`: 子分类，见下表，默认为首页


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "::: tip\n如 `藝能新聞` 的 `日劇新聞` 分类，路由为 `/jnews/news_drama`\n:::\n\n藝能新聞 jnews\n\n| 日劇新聞    | 日影新聞    | 日樂新聞    | 日藝新聞            |\n| ----------- | ----------- | ----------- | ------------------- |\n| news\\_drama | news\\_movie | news\\_music | news\\_entertainment |\n\n| 動漫新聞  | 藝人美照     | 清涼寫真   | 日本廣告 | 其他日聞     |\n| --------- | ------------ | ---------- | -------- | ------------ |\n| news\\_acg | artist-photo | photoalbum | jpcm     | news\\_others |\n\n旅遊情報 jpnews\n\n| 日本美食情報 | 日本甜點情報  | 日本零食情報  | 日本飲品情報  | 日本景點情報       |\n| ------------ | ------------- | ------------- | ------------- | ------------------ |\n| jpnews-food  | jpnews-sweets | jpnews-okashi | jpnews-drinks | jpnews-attractions |\n\n| 日本玩樂情報 | 日本住宿情報 | 日本活動情報  | 日本購物情報    | 日本社會情報   |\n| ------------ | ------------ | ------------- | --------------- | -------------- |\n| jpnews-play  | jpnews-hotel | jpnews-events | jpnews-shopping | jpnews-society |\n\n| 日本交通情報   | 日本天氣情報   |\n| -------------- | -------------- |\n| jpnews-traffic | jpnews-weather |\n\n日劇世界 jdrama\n\n| 每周劇評              | 日劇總評             | 資料情報    |\n| --------------------- | -------------------- | ----------- |\n| drama\\_review\\_weekly | drama\\_review\\_final | drama\\_data |\n\n| 深度日劇    | 收視報告      | 日劇專欄      | 劇迷互動           |\n| ----------- | ------------- | ------------- | ------------------ |\n| drama\\_deep | drama\\_rating | drama\\_column | drama\\_interactive |",
  "example": "/kenshin",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为首页",
    "type": "子分类，见下表，默认为首页"
  },
  "path": "/:category?/:type?",
  "topFeeds": []
}
```
