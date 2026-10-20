# Syosetu - R18 Rankings

## Coverage
`index-only`

## Route
- Namespace: `syosetu`
- Namespace Name: `Syosetu`
- Route Path: `/syosetu/rankingr18/:sub/:type`
- Route Name: `R18 Rankings`
- Example: `/syosetu/rankingr18/noc/daily_total?limit=50`
- URL: `syosetu.com/site/group`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `SnowAgar25`
- Source Location: `ranking-r18.ts`
- Source Module: `_None_`

## Description
| Period  | Description       | 説明             |
| ------- | ----------------- | ---------------- |
| daily   | Daily Ranking     | 日間ランキング   |
| weekly  | Weekly Ranking    | 週間ランキング   |
| monthly | Monthly Ranking   | 月間ランキング   |
| quarter | Quarterly Ranking | 四半期ランキング |
| yearly  | Yearly Ranking    | 年間ランキング   |

| Novel Type | Description      | 説明   |
| ---------- | ---------------- | ------ |
| total      | All Works        | 総合   |
| t          | Short Stories    | 短編   |
| r          | Ongoing Series   | 連載中 |
| er         | Completed Series | 完結済 |

::: tip
Combine Period and Novel Type with `_`.
For example: `daily_total`, `weekly_r`, `monthly_er`
:::

## Parameters
- `sub`: {"description": "Target site for R18 rankings", "options": [{"label": "ノクターン", "value": "noc"}, {"label": "ムーンライト", "value": "mnlt"}, {"label": "ミッドナイト", "value": "mid"}, {"label": "ムーンライト BL", "value": "mnlt-bl"}]}
- `type`: {"description": "Detailed ranking type (format: period_noveltype)", "options": [{"label": "日間 (DAILY) 総合 (TOTAL)", "value": "daily_total"}, {"label": "日間 (DAILY) 短編 (SHORT)", "value": "daily_t"}, {"label": "日間 (DAILY) 連載中 (ONGOING)", "value": "daily_r"}, {"label": "日間 (DAILY) 完結済 (COMPLETE)", "value": "daily_er"}, {"label": "週間 (WEEKLY) 総合 (TOTAL)", "value": "weekly_total"}, {"label": "週間 (WEEKLY) 短編 (SHORT)", "value": "weekly_t"}, {"label": "週間 (WEEKLY) 連載中 (ONGOING)", "value": "weekly_r"}, {"label": "週間 (WEEKLY) 完結済 (COMPLETE)", "value": "weekly_er"}, {"label": "月間 (MONTHLY) 総合 (TOTAL)", "value": "monthly_total"}, {"label": "月間 (MONTHLY) 短編 (SHORT)", "value": "monthly_t"}, {"label": "月間 (MONTHLY) 連載中 (ONGOING)", "value": "monthly_r"}, {"label": "月間 (MONTHLY) 完結済 (COMPLETE)", "value": "monthly_er"}, {"label": "四半期 (QUARTER) 総合 (TOTAL)", "value": "quarter_total"}, {"label": "四半期 (QUARTER) 短編 (SHORT)", "value": "quarter_t"}, {"label": "四半期 (QUARTER) 連載中 (ONGOING)", "value": "quarter_r"}, {"label": "四半期 (QUARTER) 完結済 (COMPLETE)", "value": "quarter_er"}, {"label": "年間 (YEARLY) 総合 (TOTAL)", "value": "yearly_total"}, {"label": "年間 (YEARLY) 短編 (SHORT)", "value": "yearly_t"}, {"label": "年間 (YEARLY) 連載中 (ONGOING)", "value": "yearly_r"}, {"label": "年間 (YEARLY) 完結済 (COMPLETE)", "value": "yearly_er"}]}


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
  - `noc.syosetu.com/rank/list/type/:type`
- `target`: `/rankingr18/noc/:type`
### Rule 2
- `source`:
  - `mid.syosetu.com/rank/list/type/:type`
- `target`: `/rankingr18/mid/:type`
### Rule 3
- `source`:
  - `mnlt.syosetu.com/rank/list/type/:type`
- `target`: `/rankingr18/mnlt/:type`
### Rule 4
- `source`:
  - `mnlt.syosetu.com/rank/bllist/type/:type`
- `target`: `/rankingr18/mnlt-bl/:type`
### Rule 5
- `title`: `ノクターン 日間ランキング BEST5`
- `source`:
  - `noc.syosetu.com/rank/top`
- `target`: `/rankingr18/noc/daily_total?limit=5`
### Rule 6
- `title`: `ノクターン 週間ランキング BEST5`
- `source`:
  - `noc.syosetu.com/rank/top`
- `target`: `/rankingr18/noc/weekly_total?limit=5`
### Rule 7
- `title`: `ノクターン 月間ランキング BEST5`
- `source`:
  - `noc.syosetu.com/rank/top`
- `target`: `/rankingr18/noc/monthly_total?limit=5`
### Rule 8
- `title`: `ノクターン 四半期ランキング BEST5`
- `source`:
  - `noc.syosetu.com/rank/top`
- `target`: `/rankingr18/noc/quarter_total?limit=5`
### Rule 9
- `title`: `ノクターン 年間ランキング BEST5`
- `source`:
  - `noc.syosetu.com/rank/top`
- `target`: `/rankingr18/noc/yearly_total?limit=5`
### Rule 10
- `title`: `ムーンライト 日間ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/top`
- `target`: `/rankingr18/mnlt/daily_total?limit=5`
### Rule 11
- `title`: `ムーンライト 週間ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/top`
- `target`: `/rankingr18/mnlt/weekly_total?limit=5`
### Rule 12
- `title`: `ムーンライト 月間ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/top`
- `target`: `/rankingr18/mnlt/monthly_total?limit=5`
### Rule 13
- `title`: `ムーンライト 四半期ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/top`
- `target`: `/rankingr18/mnlt/quarter_total?limit=5`
### Rule 14
- `title`: `ムーンライト 年間ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/top`
- `target`: `/rankingr18/mnlt/yearly_total?limit=5`
### Rule 15
- `title`: `ミッドナイト 日間ランキング BEST5`
- `source`:
  - `mid.syosetu.com/rank/top`
- `target`: `/rankingr18/mid/daily_total?limit=5`
### Rule 16
- `title`: `ミッドナイト 週間ランキング BEST5`
- `source`:
  - `mid.syosetu.com/rank/top`
- `target`: `/rankingr18/mid/weekly_total?limit=5`
### Rule 17
- `title`: `ミッドナイト 月間ランキング BEST5`
- `source`:
  - `mid.syosetu.com/rank/top`
- `target`: `/rankingr18/mid/monthly_total?limit=5`
### Rule 18
- `title`: `ミッドナイト 四半期ランキング BEST5`
- `source`:
  - `mid.syosetu.com/rank/top`
- `target`: `/rankingr18/mid/quarter_total?limit=5`
### Rule 19
- `title`: `ミッドナイト 年間ランキング BEST5`
- `source`:
  - `mid.syosetu.com/rank/top`
- `target`: `/rankingr18/mid/yearly_total?limit=5`
### Rule 20
- `title`: `ムーンライト BL 日間ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/bltop`
- `target`: `/rankingr18/mnlt-bl/daily_total?limit=5`
### Rule 21
- `title`: `ムーンライト BL 週間ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/bltop`
- `target`: `/rankingr18/mnlt-bl/weekly_total?limit=5`
### Rule 22
- `title`: `ムーンライト BL 月間ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/bltop`
- `target`: `/rankingr18/mnlt-bl/monthly_total?limit=5`
### Rule 23
- `title`: `ムーンライト BL 四半期ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/bltop`
- `target`: `/rankingr18/mnlt-bl/quarter_total?limit=5`
### Rule 24
- `title`: `ムーンライト BL 年間ランキング BEST5`
- `source`:
  - `mnlt.syosetu.com/rank/bltop`
- `target`: `/rankingr18/mnlt-bl/yearly_total?limit=5`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "| Period  | Description       | 説明             |\n| ------- | ----------------- | ---------------- |\n| daily   | Daily Ranking     | 日間ランキング   |\n| weekly  | Weekly Ranking    | 週間ランキング   |\n| monthly | Monthly Ranking   | 月間ランキング   |\n| quarter | Quarterly Ranking | 四半期ランキング |\n| yearly  | Yearly Ranking    | 年間ランキング   |\n\n| Novel Type | Description      | 説明   |\n| ---------- | ---------------- | ------ |\n| total      | All Works        | 総合   |\n| t          | Short Stories    | 短編   |\n| r          | Ongoing Series   | 連載中 |\n| er         | Completed Series | 完結済 |\n\n::: tip\nCombine Period and Novel Type with `_`.\nFor example: `daily_total`, `weekly_r`, `monthly_er`\n:::",
  "example": "/syosetu/rankingr18/noc/daily_total?limit=50",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "ranking-r18.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "R18 Rankings",
  "parameters": {
    "sub": {
      "description": "Target site for R18 rankings",
      "options": [
        {
          "label": "ノクターン",
          "value": "noc"
        },
        {
          "label": "ムーンライト",
          "value": "mnlt"
        },
        {
          "label": "ミッドナイト",
          "value": "mid"
        },
        {
          "label": "ムーンライト BL",
          "value": "mnlt-bl"
        }
      ]
    },
    "type": {
      "description": "Detailed ranking type (format: period_noveltype)",
      "options": [
        {
          "label": "日間 (DAILY) 総合 (TOTAL)",
          "value": "daily_total"
        },
        {
          "label": "日間 (DAILY) 短編 (SHORT)",
          "value": "daily_t"
        },
        {
          "label": "日間 (DAILY) 連載中 (ONGOING)",
          "value": "daily_r"
        },
        {
          "label": "日間 (DAILY) 完結済 (COMPLETE)",
          "value": "daily_er"
        },
        {
          "label": "週間 (WEEKLY) 総合 (TOTAL)",
          "value": "weekly_total"
        },
        {
          "label": "週間 (WEEKLY) 短編 (SHORT)",
          "value": "weekly_t"
        },
        {
          "label": "週間 (WEEKLY) 連載中 (ONGOING)",
          "value": "weekly_r"
        },
        {
          "label": "週間 (WEEKLY) 完結済 (COMPLETE)",
          "value": "weekly_er"
        },
        {
          "label": "月間 (MONTHLY) 総合 (TOTAL)",
          "value": "monthly_total"
        },
        {
          "label": "月間 (MONTHLY) 短編 (SHORT)",
          "value": "monthly_t"
        },
        {
          "label": "月間 (MONTHLY) 連載中 (ONGOING)",
          "value": "monthly_r"
        },
        {
          "label": "月間 (MONTHLY) 完結済 (COMPLETE)",
          "value": "monthly_er"
        },
        {
          "label": "四半期 (QUARTER) 総合 (TOTAL)",
          "value": "quarter_total"
        },
        {
          "label": "四半期 (QUARTER) 短編 (SHORT)",
          "value": "quarter_t"
        },
        {
          "label": "四半期 (QUARTER) 連載中 (ONGOING)",
          "value": "quarter_r"
        },
        {
          "label": "四半期 (QUARTER) 完結済 (COMPLETE)",
          "value": "quarter_er"
        },
        {
          "label": "年間 (YEARLY) 総合 (TOTAL)",
          "value": "yearly_total"
        },
        {
          "label": "年間 (YEARLY) 短編 (SHORT)",
          "value": "yearly_t"
        },
        {
          "label": "年間 (YEARLY) 連載中 (ONGOING)",
          "value": "yearly_r"
        },
        {
          "label": "年間 (YEARLY) 完結済 (COMPLETE)",
          "value": "yearly_er"
        }
      ]
    }
  },
  "path": "/rankingr18/:sub/:type",
  "radar": [
    {
      "source": [
        "noc.syosetu.com/rank/list/type/:type"
      ],
      "target": "/rankingr18/noc/:type"
    },
    {
      "source": [
        "mid.syosetu.com/rank/list/type/:type"
      ],
      "target": "/rankingr18/mid/:type"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/list/type/:type"
      ],
      "target": "/rankingr18/mnlt/:type"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/bllist/type/:type"
      ],
      "target": "/rankingr18/mnlt-bl/:type"
    },
    {
      "source": [
        "noc.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/noc/daily_total?limit=5",
      "title": "ノクターン 日間ランキング BEST5"
    },
    {
      "source": [
        "noc.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/noc/weekly_total?limit=5",
      "title": "ノクターン 週間ランキング BEST5"
    },
    {
      "source": [
        "noc.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/noc/monthly_total?limit=5",
      "title": "ノクターン 月間ランキング BEST5"
    },
    {
      "source": [
        "noc.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/noc/quarter_total?limit=5",
      "title": "ノクターン 四半期ランキング BEST5"
    },
    {
      "source": [
        "noc.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/noc/yearly_total?limit=5",
      "title": "ノクターン 年間ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mnlt/daily_total?limit=5",
      "title": "ムーンライト 日間ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mnlt/weekly_total?limit=5",
      "title": "ムーンライト 週間ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mnlt/monthly_total?limit=5",
      "title": "ムーンライト 月間ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mnlt/quarter_total?limit=5",
      "title": "ムーンライト 四半期ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mnlt/yearly_total?limit=5",
      "title": "ムーンライト 年間ランキング BEST5"
    },
    {
      "source": [
        "mid.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mid/daily_total?limit=5",
      "title": "ミッドナイト 日間ランキング BEST5"
    },
    {
      "source": [
        "mid.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mid/weekly_total?limit=5",
      "title": "ミッドナイト 週間ランキング BEST5"
    },
    {
      "source": [
        "mid.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mid/monthly_total?limit=5",
      "title": "ミッドナイト 月間ランキング BEST5"
    },
    {
      "source": [
        "mid.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mid/quarter_total?limit=5",
      "title": "ミッドナイト 四半期ランキング BEST5"
    },
    {
      "source": [
        "mid.syosetu.com/rank/top"
      ],
      "target": "/rankingr18/mid/yearly_total?limit=5",
      "title": "ミッドナイト 年間ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/bltop"
      ],
      "target": "/rankingr18/mnlt-bl/daily_total?limit=5",
      "title": "ムーンライト BL 日間ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/bltop"
      ],
      "target": "/rankingr18/mnlt-bl/weekly_total?limit=5",
      "title": "ムーンライト BL 週間ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/bltop"
      ],
      "target": "/rankingr18/mnlt-bl/monthly_total?limit=5",
      "title": "ムーンライト BL 月間ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/bltop"
      ],
      "target": "/rankingr18/mnlt-bl/quarter_total?limit=5",
      "title": "ムーンライト BL 四半期ランキング BEST5"
    },
    {
      "source": [
        "mnlt.syosetu.com/rank/bltop"
      ],
      "target": "/rankingr18/mnlt-bl/yearly_total?limit=5",
      "title": "ムーンライト BL 年間ランキング BEST5"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "小説家になろう (noc) - 日間総合ランキング BEST300 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82945591703756800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://noc.syosetu.com/rank/list/type/daily_total",
      "title": "小説家になろう (noc) - 日間総合ランキング BEST300",
      "type": "feed",
      "url": "rsshub://syosetu/rankingr18/noc/daily_total"
    },
    {
      "description": "小説家になろう (noc) - 日間完結済ランキング BEST300 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "146209536416978944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://noc.syosetu.com/rank/list/type/daily_er",
      "title": "小説家になろう (noc) - 日間完結済ランキング BEST300",
      "type": "feed",
      "url": "rsshub://syosetu/rankingr18/noc/daily_er"
    }
  ],
  "url": "syosetu.com/site/group"
}
```
