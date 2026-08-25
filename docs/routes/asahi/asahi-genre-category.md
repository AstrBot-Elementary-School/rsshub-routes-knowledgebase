# 朝日新聞デジタル - 新聞

## Coverage
`index-only`

## Route
- Namespace: `asahi`
- Namespace Name: `朝日新聞デジタル`
- Route Path: `/asahi/:genre?/:category?`
- Route Name: `新聞`
- Example: `/asahi`
- URL: `www.asahi.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip

以下小标题即类型 `genre`，标题下表格中为对应类型的分类 `category`，两者需要配合使用。

如订阅 **社会** 类型中的 **事件・事故・裁判** 分类，填入 [`/asahi/national/incident`](https://rsshub.app/asahi/national/incident)。

若类型下没有分类，如 **トップ** 类型，直接填入 [`/asahi/top`](https://rsshub.app/asahi/top)。

或者欲订阅该类型下的所有分类，如订阅 **社会** 中的所有分类，则直接将分类 `category` 留空，即 [`/asahi/national`](https://rsshub.app/asahi/national)。

:::

トップ top

社会 national

| 事件・事故・裁判 | 災害・交通情報 | その他・話題 | おくやみ   |
| ---------------- | -------------- | ------------ | ---------- |
| incident         | calamity       | etc          | obituaries |

経済 business

| 産業・商品 | 金融・財政 | 経済政策       | 労働・雇用 | 市況・統計 |
| ---------- | ---------- | -------------- | ---------- | ---------- |
| industry   | finance    | economicpolicy | work       | statistics |

政治 politics

| 国政       | 地方政治 | 発言録       | 世論調査 |
| ---------- | -------- | ------------ | -------- |
| government | local    | hatsugenroku | yoron    |

国際 international

| アジア・太平洋 | 北米     | 中南米   | ヨーロッパ | 中東       | アフリカ | 国連・その他 |
| -------------- | -------- | -------- | ---------- | ---------- | -------- | ------------ |
| asia           | namerica | samerica | europe     | middleeast | africa   | etc          |

スポーツ sports

| 野球     | サッカー | 相撲 | フィギュア          | ゴルフ | 一般スポーツ | 東京オリンピック 2020 | 東京パラリンピック 2020 |
| -------- | -------- | ---- | ------------------- | ------ | ------------ | --------------------- | ----------------------- |
| baseball | soccer   | sumo | winter\_figureskate | golf   | general      | olympics              | paralympics             |

IT・科学 tech\_science

| 環境・エネルギー | 科学    | デジもの | 企業・サービス | 製品ファイル |
| ---------------- | ------- | -------- | -------------- | ------------ |
| eco              | science | digital  | service        | products     |

文化・芸能 culture

| 映画   | 音楽  | アイドル | アート | テレビ・芸能 | 舞台・演芸 | マンガ・アニメ・ゲーム | ひと・歴史 | 囲碁 | 将棋   |
| ------ | ----- | -------- | ------ | ------------ | ---------- | ---------------------- | ---------- | ---- | ------ |
| movies | music | idol     | art    | showbiz      | stage      | manga                  | history    | igo  | shougi |

ライフ life

| 介護      | 働き方・就活 | 食・料理 |
| --------- | ------------ | -------- |
| eldercare | hataraku     | food     |

教育・子育て edu

| 小中高  | 大学       | 教育制度・話題 | 教育問題 | 地域の教育ニュース | 吹奏楽    | 合唱   | 子育て   | ハグスタ |
| ------- | ---------- | -------------- | -------- | ------------------ | --------- | ------ | -------- | -------- |
| student | university | system         | issue    | chiiki             | suisogaku | gassho | hagukumu | msta     |

## Parameters
- `genre`: 类型，见下表，默认为トップ
- `category`: 分类，见下表，默认为空，即该类型下所有新闻


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n\n以下小标题即类型 `genre`，标题下表格中为对应类型的分类 `category`，两者需要配合使用。\n\n如订阅 **社会** 类型中的 **事件・事故・裁判** 分类，填入 [`/asahi/national/incident`](https://rsshub.app/asahi/national/incident)。\n\n若类型下没有分类，如 **トップ** 类型，直接填入 [`/asahi/top`](https://rsshub.app/asahi/top)。\n\n或者欲订阅该类型下的所有分类，如订阅 **社会** 中的所有分类，则直接将分类 `category` 留空，即 [`/asahi/national`](https://rsshub.app/asahi/national)。\n\n:::\n\nトップ top\n\n社会 national\n\n| 事件・事故・裁判 | 災害・交通情報 | その他・話題 | おくやみ   |\n| ---------------- | -------------- | ------------ | ---------- |\n| incident         | calamity       | etc          | obituaries |\n\n経済 business\n\n| 産業・商品 | 金融・財政 | 経済政策       | 労働・雇用 | 市況・統計 |\n| ---------- | ---------- | -------------- | ---------- | ---------- |\n| industry   | finance    | economicpolicy | work       | statistics |\n\n政治 politics\n\n| 国政       | 地方政治 | 発言録       | 世論調査 |\n| ---------- | -------- | ------------ | -------- |\n| government | local    | hatsugenroku | yoron    |\n\n国際 international\n\n| アジア・太平洋 | 北米     | 中南米   | ヨーロッパ | 中東       | アフリカ | 国連・その他 |\n| -------------- | -------- | -------- | ---------- | ---------- | -------- | ------------ |\n| asia           | namerica | samerica | europe     | middleeast | africa   | etc          |\n\nスポーツ sports\n\n| 野球     | サッカー | 相撲 | フィギュア          | ゴルフ | 一般スポーツ | 東京オリンピック 2020 | 東京パラリンピック 2020 |\n| -------- | -------- | ---- | ------------------- | ------ | ------------ | --------------------- | ----------------------- |\n| baseball | soccer   | sumo | winter\\_figureskate | golf   | general      | olympics              | paralympics             |\n\nIT・科学 tech\\_science\n\n| 環境・エネルギー | 科学    | デジもの | 企業・サービス | 製品ファイル |\n| ---------------- | ------- | -------- | -------------- | ------------ |\n| eco              | science | digital  | service        | products     |\n\n文化・芸能 culture\n\n| 映画   | 音楽  | アイドル | アート | テレビ・芸能 | 舞台・演芸 | マンガ・アニメ・ゲーム | ひと・歴史 | 囲碁 | 将棋   |\n| ------ | ----- | -------- | ------ | ------------ | ---------- | ---------------------- | ---------- | ---- | ------ |\n| movies | music | idol     | art    | showbiz      | stage      | manga                  | history    | igo  | shougi |\n\nライフ life\n\n| 介護      | 働き方・就活 | 食・料理 |\n| --------- | ------------ | -------- |\n| eldercare | hataraku     | food     |\n\n教育・子育て edu\n\n| 小中高  | 大学       | 教育制度・話題 | 教育問題 | 地域の教育ニュース | 吹奏楽    | 合唱   | 子育て   | ハグスタ |\n| ------- | ---------- | -------------- | -------- | ------------------ | --------- | ------ | -------- | -------- |\n| student | university | system         | issue    | chiiki             | suisogaku | gassho | hagukumu | msta     |",
  "example": "/asahi",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新聞",
  "parameters": {
    "category": "分类，见下表，默认为空，即该类型下所有新闻",
    "genre": "类型，见下表，默认为トップ"
  },
  "path": "/:genre?/:category?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
