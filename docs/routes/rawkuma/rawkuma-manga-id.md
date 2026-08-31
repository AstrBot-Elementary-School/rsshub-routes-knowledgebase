# Rawkuma - Manga

## Coverage
`index-only`

## Route
- Namespace: `rawkuma`
- Namespace Name: `Rawkuma`
- Route Path: `/rawkuma/manga/:id`
- Route Name: `Manga`
- Example: `/rawkuma/manga/tensei-shitara-dai-nana-ouji-dattanode-kimamani-majutsu-o-kiwamemasu`
- URL: `rawkuma.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `manga.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Manga ID, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `rawkuma.com/manga/:id`
  - `rawkuma.com/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/rawkuma/manga/tensei-shitara-dai-nana-ouji-dattanode-kimamani-majutsu-o-kiwamemasu",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "manga.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Manga",
  "parameters": {
    "id": "Manga ID, can be found in URL"
  },
  "path": "/manga/:id",
  "radar": [
    {
      "source": [
        "rawkuma.com/manga/:id",
        "rawkuma.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "「魔術を極めたい…！」たった一つの願望を胸に死んだ男は、生前の記憶を持ったままサルーム国の第七王子として転生を果たした！ただの庶民だった前世と違い、有り余る金！使いきれぬ時間！そしてなにより読み切れない魔導書！！”太すぎる実家”という人生バフもりもりの圧倒的勝ち組となった王子の名はロイド。小説家になろう発、ハイスピード成り上がりファンタジー！！ ※「小説家になろう」は株式会社ヒナプロジェクトの登録商標です A magic nerd’s life came to an end after a dreadful encounter with the nobles who ended his life with a powerful spell. His last wish, being able to study and master more magic, has been answered when he was reincarnated as Lloyd de Saloom, the 7th prince of Saloom Kingdom. Now he’ll be able to perfect his magic as he pleases… - Powered by RSSHub",
      "errorAt": "2025-10-04T20:56:49.456Z",
      "errorMessage": "[GET] \"https://rawkuma.com/manga/tensei-shitara-dai-nana-ouji-dattanode-kimamani-majutsu-o-kiwamemasu\": 404 Not Found\n",
      "id": "83128916068674560",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rawkuma.com/manga/tensei-shitara-dai-nana-ouji-dattanode-kimamani-majutsu-o-kiwamemasu",
      "title": "Tensei Shitara dai Nana Ouji dattanode, Kimamani Majutsu o Kiwamemasu – Rawkuma",
      "type": "feed",
      "url": "rsshub://rawkuma/manga/tensei-shitara-dai-nana-ouji-dattanode-kimamani-majutsu-o-kiwamemasu"
    },
    {
      "description": "異世界転生したら全裸で森にひとりきり。魔法なし、チートなしで、頼れるものは己の知識と拳のみ……！ If you’re reincarnated in another world, you will be naked and alone in the forest. The only things you can rely on without magic or cheats is your wits and fists! - Powered by RSSHub",
      "errorAt": "2025-10-04T19:37:10.580Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "189554121482481664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rawkuma.com/manga/yajin-tensei-karate-survivor-in-another-world",
      "title": "Yajin Tensei: Karate Survivor in Another World – Rawkuma",
      "type": "feed",
      "url": "rsshub://rawkuma/manga/yajin-tensei-karate-survivor-in-another-world"
    }
  ]
}
```
