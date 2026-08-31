# 中国黄金协会 - 分类

## Coverage
`index-only`

## Route
- Namespace: `cngold`
- Namespace Name: `中国黄金协会`
- Route Path: `/cngold/:category?`
- Route Name: `分类`
- Example: `/cngold/news-325`
- URL: `www.cngold.org.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [行业资讯](https://www.cngold.org.cn/news-325.html)，网址为 `https://www.cngold.org.cn/news-325.html`。截取 `https://www.cngold.org.cn/` 到末尾 `.html` 的部分 `news-325` 作为参数填入，此时路由为 [`/cngold/news-325`](https://rsshub.app/cngold/news-325)。
:::

#### 资讯中心

| [图片新闻](https://www.cngold.org.cn/news-323.html) | [通知公告](https://www.cngold.org.cn/news-324.html) | [党建工作](https://www.cngold.org.cn/news-326.html) | [行业资讯](https://www.cngold.org.cn/news-325.html) | [黄金矿业](https://www.cngold.org.cn/news-327.html) | [黄金消费](https://www.cngold.org.cn/news-328.html) |
| --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |
| [news-323](https://rsshub.app/cngold/news-323)      | [news-324](https://rsshub.app/cngold/news-324)      | [news-326](https://rsshub.app/cngold/news-326)      | [news-325](https://rsshub.app/cngold/news-325)      | [news-327](https://rsshub.app/cngold/news-327)      | [news-328](https://rsshub.app/cngold/news-328)      |

| [黄金市场](https://www.cngold.org.cn/news-329.html) | [社会责任](https://www.cngold.org.cn/news-330.html) | [黄金书屋](https://www.cngold.org.cn/news-331.html) | [工作交流](https://www.cngold.org.cn/news-332.html) | [黄金统计](https://www.cngold.org.cn/news-333.html) | [协会动态](https://www.cngold.org.cn/news-334.html) |
| --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |
| [news-329](https://rsshub.app/cngold/news-329)      | [news-330](https://rsshub.app/cngold/news-330)      | [news-331](https://rsshub.app/cngold/news-331)      | [news-332](https://rsshub.app/cngold/news-332)      | [news-333](https://rsshub.app/cngold/news-333)      | [news-334](https://rsshub.app/cngold/news-334)      |

<details>
<summary>更多分类</summary>

#### [政策法规](https://www.cngold.org.cn/policies.html)

| [法律法规](https://www.cngold.org.cn/policies-245.html) | [产业政策](https://www.cngold.org.cn/policies-262.html) | [黄金标准](https://www.cngold.org.cn/policies-281.html) |
| ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |
| [policies-245](https://rsshub.app/cngold/policies-245)  | [policies-262](https://rsshub.app/cngold/policies-262)  | [policies-281](https://rsshub.app/cngold/policies-281)  |

#### [行业培训](https://www.cngold.org.cn/training.html)

| [黄金投资分析师](https://www.cngold.org.cn/training-242.html) | [教育部 1+X](https://www.cngold.org.cn/training-246.html) | [矿业权评估师](https://www.cngold.org.cn/training-338.html) | [其他培训](https://www.cngold.org.cn/training-247.html) |
| ------------------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------- |
| [training-242](https://rsshub.app/cngold/training-242)        | [training-246](https://rsshub.app/cngold/training-246)    | [training-338](https://rsshub.app/cngold/training-338)      | [training-247](https://rsshub.app/cngold/training-247)  |

#### [黄金科技](https://www.cngold.org.cn/technology.html)

| [黄金协会科学技术奖](https://www.cngold.org.cn/technology-318.html) | [科学成果评价](https://www.cngold.org.cn/technology-319.html) | [新技术推广](https://www.cngold.org.cn/technology-320.html) | [黄金技术大会](https://www.cngold.org.cn/technology-350.html) |
| ------------------------------------------------------------------- | ------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------- |
| [technology-318](https://rsshub.app/cngold/technology-318)          | [technology-319](https://rsshub.app/cngold/technology-319)    | [technology-320](https://rsshub.app/cngold/technology-320)  | [technology-350](https://rsshub.app/cngold/technology-350)    |

</details>

## Parameters
- `category`: 分类，默认为 `news-325`，即行业资讯，可在对应分类页 URL 中找到, Category, `news-325`，即行业资讯by default


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
  - `www.cngold.org.cn/:category?`
### Rule 2
- `title`: `政策法规 - 法律法规`
- `source`:
  - `www.cngold.org.cn/policies-245.html`
- `target`: `/policies-245`
### Rule 3
- `title`: `政策法规 - 产业政策`
- `source`:
  - `www.cngold.org.cn/policies-262.html`
- `target`: `/policies-262`
### Rule 4
- `title`: `政策法规 - 黄金标准`
- `source`:
  - `www.cngold.org.cn/policies-281.html`
- `target`: `/policies-281`
### Rule 5
- `title`: `行业培训 - 黄金投资分析师`
- `source`:
  - `www.cngold.org.cn/training-242.html`
- `target`: `/training-242`
### Rule 6
- `title`: `行业培训 - 教育部1+X`
- `source`:
  - `www.cngold.org.cn/training-246.html`
- `target`: `/training-246`
### Rule 7
- `title`: `行业培训 - 矿业权评估师`
- `source`:
  - `www.cngold.org.cn/training-338.html`
- `target`: `/training-338`
### Rule 8
- `title`: `行业培训 - 其他培训`
- `source`:
  - `www.cngold.org.cn/training-247.html`
- `target`: `/training-247`
### Rule 9
- `title`: `黄金科技 - 黄金协会科学技术奖`
- `source`:
  - `www.cngold.org.cn/technology-318.html`
- `target`: `/technology-318`
### Rule 10
- `title`: `黄金科技 - 科学成果评价`
- `source`:
  - `www.cngold.org.cn/technology-319.html`
- `target`: `/technology-319`
### Rule 11
- `title`: `黄金科技 - 新技术推广`
- `source`:
  - `www.cngold.org.cn/technology-320.html`
- `target`: `/technology-320`
### Rule 12
- `title`: `黄金科技 - 黄金技术大会`
- `source`:
  - `www.cngold.org.cn/technology-350.html`
- `target`: `/technology-350`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [行业资讯](https://www.cngold.org.cn/news-325.html)，网址为 `https://www.cngold.org.cn/news-325.html`。截取 `https://www.cngold.org.cn/` 到末尾 `.html` 的部分 `news-325` 作为参数填入，此时路由为 [`/cngold/news-325`](https://rsshub.app/cngold/news-325)。\n:::\n\n#### 资讯中心\n\n| [图片新闻](https://www.cngold.org.cn/news-323.html) | [通知公告](https://www.cngold.org.cn/news-324.html) | [党建工作](https://www.cngold.org.cn/news-326.html) | [行业资讯](https://www.cngold.org.cn/news-325.html) | [黄金矿业](https://www.cngold.org.cn/news-327.html) | [黄金消费](https://www.cngold.org.cn/news-328.html) |\n| --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |\n| [news-323](https://rsshub.app/cngold/news-323)      | [news-324](https://rsshub.app/cngold/news-324)      | [news-326](https://rsshub.app/cngold/news-326)      | [news-325](https://rsshub.app/cngold/news-325)      | [news-327](https://rsshub.app/cngold/news-327)      | [news-328](https://rsshub.app/cngold/news-328)      |\n\n| [黄金市场](https://www.cngold.org.cn/news-329.html) | [社会责任](https://www.cngold.org.cn/news-330.html) | [黄金书屋](https://www.cngold.org.cn/news-331.html) | [工作交流](https://www.cngold.org.cn/news-332.html) | [黄金统计](https://www.cngold.org.cn/news-333.html) | [协会动态](https://www.cngold.org.cn/news-334.html) |\n| --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |\n| [news-329](https://rsshub.app/cngold/news-329)      | [news-330](https://rsshub.app/cngold/news-330)      | [news-331](https://rsshub.app/cngold/news-331)      | [news-332](https://rsshub.app/cngold/news-332)      | [news-333](https://rsshub.app/cngold/news-333)      | [news-334](https://rsshub.app/cngold/news-334)      |\n\n<details>\n<summary>更多分类</summary>\n\n#### [政策法规](https://www.cngold.org.cn/policies.html)\n\n| [法律法规](https://www.cngold.org.cn/policies-245.html) | [产业政策](https://www.cngold.org.cn/policies-262.html) | [黄金标准](https://www.cngold.org.cn/policies-281.html) |\n| ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |\n| [policies-245](https://rsshub.app/cngold/policies-245)  | [policies-262](https://rsshub.app/cngold/policies-262)  | [policies-281](https://rsshub.app/cngold/policies-281)  |\n\n#### [行业培训](https://www.cngold.org.cn/training.html)\n\n| [黄金投资分析师](https://www.cngold.org.cn/training-242.html) | [教育部 1+X](https://www.cngold.org.cn/training-246.html) | [矿业权评估师](https://www.cngold.org.cn/training-338.html) | [其他培训](https://www.cngold.org.cn/training-247.html) |\n| ------------------------------------------------------------- | --------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------- |\n| [training-242](https://rsshub.app/cngold/training-242)        | [training-246](https://rsshub.app/cngold/training-246)    | [training-338](https://rsshub.app/cngold/training-338)      | [training-247](https://rsshub.app/cngold/training-247)  |\n\n#### [黄金科技](https://www.cngold.org.cn/technology.html)\n\n| [黄金协会科学技术奖](https://www.cngold.org.cn/technology-318.html) | [科学成果评价](https://www.cngold.org.cn/technology-319.html) | [新技术推广](https://www.cngold.org.cn/technology-320.html) | [黄金技术大会](https://www.cngold.org.cn/technology-350.html) |\n| ------------------------------------------------------------------- | ------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------- |\n| [technology-318](https://rsshub.app/cngold/technology-318)          | [technology-319](https://rsshub.app/cngold/technology-319)    | [technology-320](https://rsshub.app/cngold/technology-320)  | [technology-350](https://rsshub.app/cngold/technology-350)    |\n\n</details>",
  "example": "/cngold/news-325",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 18,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，默认为 `news-325`，即行业资讯，可在对应分类页 URL 中找到, Category, `news-325`，即行业资讯by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.cngold.org.cn/:category?"
      ]
    },
    {
      "source": [
        "www.cngold.org.cn/policies-245.html"
      ],
      "target": "/policies-245",
      "title": "政策法规 - 法律法规"
    },
    {
      "source": [
        "www.cngold.org.cn/policies-262.html"
      ],
      "target": "/policies-262",
      "title": "政策法规 - 产业政策"
    },
    {
      "source": [
        "www.cngold.org.cn/policies-281.html"
      ],
      "target": "/policies-281",
      "title": "政策法规 - 黄金标准"
    },
    {
      "source": [
        "www.cngold.org.cn/training-242.html"
      ],
      "target": "/training-242",
      "title": "行业培训 - 黄金投资分析师"
    },
    {
      "source": [
        "www.cngold.org.cn/training-246.html"
      ],
      "target": "/training-246",
      "title": "行业培训 - 教育部1+X"
    },
    {
      "source": [
        "www.cngold.org.cn/training-338.html"
      ],
      "target": "/training-338",
      "title": "行业培训 - 矿业权评估师"
    },
    {
      "source": [
        "www.cngold.org.cn/training-247.html"
      ],
      "target": "/training-247",
      "title": "行业培训 - 其他培训"
    },
    {
      "source": [
        "www.cngold.org.cn/technology-318.html"
      ],
      "target": "/technology-318",
      "title": "黄金科技 - 黄金协会科学技术奖"
    },
    {
      "source": [
        "www.cngold.org.cn/technology-319.html"
      ],
      "target": "/technology-319",
      "title": "黄金科技 - 科学成果评价"
    },
    {
      "source": [
        "www.cngold.org.cn/technology-320.html"
      ],
      "target": "/technology-320",
      "title": "黄金科技 - 新技术推广"
    },
    {
      "source": [
        "www.cngold.org.cn/technology-350.html"
      ],
      "target": "/technology-350",
      "title": "黄金科技 - 黄金技术大会"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "中国黄金协会 - Powered by RSSHub",
      "errorAt": "2026-01-20T06:51:52.014Z",
      "errorMessage": "[GET] \"https://www.cngold.org.cn/news-325.html\": <no response> fetch failed (Connect Timeout Error (attempted address: www.cngold.org.cn:443, timeout: 10000ms))\n",
      "id": "75398969878147072",
      "image": "https://www.cngold.org.cn/public/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.cngold.org.cn/news-325.html",
      "title": "中国黄金协会 - 行业资讯",
      "type": "feed",
      "url": "rsshub://cngold/news-325"
    },
    {
      "description": "中国黄金协会 - Powered by RSSHub",
      "errorAt": "2026-01-20T07:34:08.193Z",
      "errorMessage": "[GET] \"https://www.cngold.org.cn/news-329.html\": <no response> fetch failed (Connect Timeout Error (attempted address: www.cngold.org.cn:443, timeout: 10000ms))\n",
      "id": "78383227152557056",
      "image": "https://www.cngold.org.cn/public/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.cngold.org.cn/news-329.html",
      "title": "中国黄金协会 - 黄金市场",
      "type": "feed",
      "url": "rsshub://cngold/news-329"
    }
  ],
  "url": "www.cngold.org.cn"
}
```
