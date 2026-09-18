# GitHub - Github Advisory Database RSS

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/advisor/data/:type?/:category?`
- Route Name: `Github Advisory Database RSS`
- Example: `/github/advisor/data/reviewed/composer`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `sd0ric4`
- Source Location: `advisor.ts`
- Source Module: `_None_`

## Description
| Type       | Description | Explanation |
| ---------- | ----------- | ----------- |
| reviewed   | Reviewed    | 已审核      |
| unreviewed | Unreviewed  | 未审核      |

| Category | Description | Explanation        |
| -------- | ----------- | ------------------ |
| composer | Composer    | PHP 依赖管理工具   |
| go       | Go          | Go 语言包管理工具  |
| maven    | Maven       | Java 项目管理工具  |
| npm      | NPM         | Node.js 包管理工具 |
| nuget    | NuGet       | .NET 包管理工具    |
| pip      | Pip         | Python 包管理工具  |
| pub      | Pub         | Dart 包管理工具    |
| rubygems | RubyGems    | Ruby 包管理工具    |
| rust     | Rust        | Rust 包管理工具    |
| erlang   | Erlang      | Erlang 包管理工具  |
| actions  | Actions     | GitHub Actions     |
| swift    | Swift       | Swift 包管理工具   |

## Parameters
_None_


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
  - `github.com/advisories`
  - `github.com`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| Type       | Description | Explanation |\n| ---------- | ----------- | ----------- |\n| reviewed   | Reviewed    | 已审核      |\n| unreviewed | Unreviewed  | 未审核      |\n\n| Category | Description | Explanation        |\n| -------- | ----------- | ------------------ |\n| composer | Composer    | PHP 依赖管理工具   |\n| go       | Go          | Go 语言包管理工具  |\n| maven    | Maven       | Java 项目管理工具  |\n| npm      | NPM         | Node.js 包管理工具 |\n| nuget    | NuGet       | .NET 包管理工具    |\n| pip      | Pip         | Python 包管理工具  |\n| pub      | Pub         | Dart 包管理工具    |\n| rubygems | RubyGems    | Ruby 包管理工具    |\n| rust     | Rust        | Rust 包管理工具    |\n| erlang   | Erlang      | Erlang 包管理工具  |\n| actions  | Actions     | GitHub Actions     |\n| swift    | Swift       | Swift 包管理工具   |",
  "example": "/github/advisor/data/reviewed/composer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "advisor.ts",
  "maintainers": [
    "sd0ric4"
  ],
  "name": "Github Advisory Database RSS",
  "path": "/advisor/data/:type?/:category?",
  "radar": [
    {
      "source": [
        "github.com/advisories",
        "github.com"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "GitHub Advisory Database RSS - composer - reviewed - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "95003691455117312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/advisories",
      "title": "GitHub Advisory Database RSS - composer - reviewed",
      "type": "feed",
      "url": "rsshub://github/advisor/data/reviewed/composer"
    },
    {
      "description": "GitHub Advisory Database RSS - maven - reviewed - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150126395942098944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/advisories",
      "title": "GitHub Advisory Database RSS - maven - reviewed",
      "type": "feed",
      "url": "rsshub://github/advisor/data/reviewed/maven"
    }
  ]
}
```
