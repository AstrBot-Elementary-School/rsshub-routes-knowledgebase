# S&P Global - Ratings

## Coverage
`index-only`

## Route
- Namespace: `spglobal`
- Namespace Name: `S&P Global`
- Route Path: `/spglobal/ratings/:language?`
- Route Name: `Ratings`
- Example: `/spglobal/ratings/en`
- URL: `www.spglobal.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Cedaric`
- Source Location: `ratings.ts`
- Source Module: `_None_`

## Description
| language | Description |
| -------- | ----------- |
| zh       | 中文        |
| en       | English     |
| es       | Español     |
| pt       | Português   |
| jp       | 日本語      |
| ru       | Русский     |
| ar       | العربية     |

## Parameters
- `language`: {"description": "语言", "options": [{"label": "中文", "value": "zh"}, {"label": "English", "value": "en"}, {"label": "Español", "value": "es"}, {"label": "Português", "value": "pt"}, {"label": "日本語", "value": "jp"}, {"label": "Русский", "value": "ru"}, {"label": "العربية", "value": "ar"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.spglobal.com/ratings/:language`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| language | Description |\n| -------- | ----------- |\n| zh       | 中文        |\n| en       | English     |\n| es       | Español     |\n| pt       | Português   |\n| jp       | 日本語      |\n| ru       | Русский     |\n| ar       | العربية     |",
  "example": "/spglobal/ratings/en",
  "heat": 114,
  "location": "ratings.ts",
  "maintainers": [
    "Cedaric"
  ],
  "name": "Ratings",
  "parameters": {
    "language": {
      "description": "语言",
      "options": [
        {
          "label": "中文",
          "value": "zh"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Español",
          "value": "es"
        },
        {
          "label": "Português",
          "value": "pt"
        },
        {
          "label": "日本語",
          "value": "jp"
        },
        {
          "label": "Русский",
          "value": "ru"
        },
        {
          "label": "العربية",
          "value": "ar"
        }
      ]
    }
  },
  "path": "/ratings/:language?",
  "radar": [
    {
      "source": [
        "www.spglobal.com/ratings/:language"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "S&P Global Ratings(undefined) - Powered by RSSHub",
      "errorAt": "2025-08-25T23:36:01.310Z",
      "errorMessage": "[GET] \"https://www.spglobal.com/crownpeaksearchproxy.aspx?q=https%3A%2F%2Fsearchg2-restricted.crownpeak.net%2Fsandpglobal-spglobal-live%2Fselect%3Fq%3D*%253A*%26echoParams%3Dexplicit%26fl%3Dtitle%2Ccustom_i_article_id%2Ccustom_ss_theme%2Ccustom_ss_theme_full%2Ccustom_dt_meta_publish_date%2Ccustom_s_meta_location%20%2Ccustom_s_local_url%2Ccustom_s_tile_image%2Ccustom_s_cshtml_path%2Ccustom_s_sub_type%2Ccustom_s_meta_type%2Cscore%2Ccustom_s_division%2Ccustom_ss_contenttype%2Ccustom_ss_location%2Ccustom_ss_region%2Ccustom_ss_theme%2Ccustom_ss_author_thumbnails%2Ccustom_ss_authors%2Ccustom_ss_author_titles%2Ccustom_s_meta_videoid%2Ctaxonomy_tag_freeform%2Ccustom_ss_tags%2Ccustom_ss_freeform%26defType%3Dedismax%26wt%3Djson%26start%3D0%26rows%3D10%26fq%3Dcustom_s_type%3Aarticle%26fq%3Dcustom_s_sub_type%3A(%22blog%22%2C%20%22news%22%2C%20%22research%22%2C%20%22podcast%22%2C%20%22video%22%2C%20%22article%22%2C%20%22pdf%20details%22)%26fq%3Dcustom_s_division%3A%22Ratings%22%26fq%3Dcustom_s_region%3A%22undefined%22%26facet%3Dtrue%26facet.mincount%3D1%26facet.field%3Dcustom_ss_theme_full%26facet.limit%3D15%26sort%3Dcustom_dt_meta_publish_date%20desc%26f.custom_ss_theme_full.facet.sort%3Dindex\": 503 Service Unavailable\n",
      "id": "150939418810558464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.spglobal.com/ratings/undefined/",
      "title": "S&P Global Ratings(undefined)",
      "type": "feed",
      "url": "rsshub://spglobal/ratings"
    },
    {
      "description": "S&P Global Ratings(zh) - Powered by RSSHub",
      "errorAt": "2025-08-25T19:17:28.173Z",
      "errorMessage": "[GET] \"https://www.spglobal.com/crownpeaksearchproxy.aspx?q=https%3A%2F%2Fsearchg2-restricted.crownpeak.net%2Fsandpglobal-spglobal-live%2Fselect%3Fq%3D*%253A*%26echoParams%3Dexplicit%26fl%3Dtitle%2Ccustom_i_article_id%2Ccustom_ss_theme%2Ccustom_ss_theme_full%2Ccustom_dt_meta_publish_date%2Ccustom_s_meta_location%20%2Ccustom_s_local_url%2Ccustom_s_tile_image%2Ccustom_s_cshtml_path%2Ccustom_s_sub_type%2Ccustom_s_meta_type%2Cscore%2Ccustom_s_division%2Ccustom_ss_contenttype%2Ccustom_ss_location%2Ccustom_ss_region%2Ccustom_ss_theme%2Ccustom_ss_author_thumbnails%2Ccustom_ss_authors%2Ccustom_ss_author_titles%2Ccustom_s_meta_videoid%2Ctaxonomy_tag_freeform%2Ccustom_ss_tags%2Ccustom_ss_freeform%26defType%3Dedismax%26wt%3Djson%26start%3D0%26rows%3D10%26fq%3Dcustom_s_type%3Aarticle%26fq%3Dcustom_s_sub_type%3A(%22blog%22%2C%20%22news%22%2C%20%22research%22%2C%20%22podcast%22%2C%20%22video%22%2C%20%22article%22%2C%20%22pdf%20details%22)%26fq%3Dcustom_s_division%3A%22Ratings%22%26fq%3Dcustom_s_region%3A%22zh%22%26facet%3Dtrue%26facet.mincount%3D1%26facet.field%3Dcustom_ss_theme_full%26facet.limit%3D15%26sort%3Dcustom_dt_meta_publish_date%20desc%26f.custom_ss_theme_full.facet.sort%3Dindex\": 503 Service Unavailable\n",
      "id": "91850787540336640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.spglobal.com/ratings/zh/",
      "title": "S&P Global Ratings(zh)",
      "type": "feed",
      "url": "rsshub://spglobal/ratings/zh"
    }
  ],
  "view": 5
}
```
