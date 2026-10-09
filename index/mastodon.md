# Mastodon Route Index

## Namespace
- Namespace: `mastodon`
- Display Name: `Mastodon`
- URL: `mastodon.social`
- Language: `_None_`
- Aliases: `mastodon, mastodon.social`
- Route Count: `6`

## Routes

### User timeline (by account ID)
- Route ID: `mastodon:/mastodon/account_id/:site/:account_id/statuses/:only_media?`
- Route Path: `/mastodon/account_id/:site/:account_id/statuses/:only_media?`
- File: `docs/routes/mastodon/mastodon-account_id-site-account_id-statuses-only_media.md`
- File Name: `mastodon-account_id-site-account_id-statuses-only_media.md`
- Categories: `social-media`
- Maintainers: `notofoe, pseudoyu`

### User timeline
- Route ID: `mastodon:/mastodon/acct/:acct/statuses/:only_media?`
- Route Path: `/mastodon/acct/:acct/statuses/:only_media?`
- File: `docs/routes/mastodon/mastodon-acct-acct-statuses-only_media.md`
- File Name: `mastodon-acct-acct-statuses-only_media.md`
- Categories: `social-media`
- Maintainers: `notofoe`

### Instance timeline (federated)
- Route ID: `mastodon:/mastodon/remote/:site/:only_media?`
- Route Path: `/mastodon/remote/:site/:only_media?`
- File: `docs/routes/mastodon/mastodon-remote-site-only_media.md`
- File Name: `mastodon-remote-site-only_media.md`
- Categories: `social-media`
- Maintainers: `hoilc`

### Hashtag timeline
- Route ID: `mastodon:/mastodon/tag/:site/:hashtag/:only_media?`
- Route Path: `/mastodon/tag/:site/:hashtag/:only_media?`
- File: `docs/routes/mastodon/mastodon-tag-site-hashtag-only_media.md`
- File Name: `mastodon-tag-site-hashtag-only_media.md`
- Categories: `social-media`
- Maintainers: `yuikisaito`

### Instance timeline (local)
- Route ID: `mastodon:/mastodon/timeline/:site/:only_media?`
- Route Path: `/mastodon/timeline/:site/:only_media?`
- File: `docs/routes/mastodon/mastodon-timeline-site-only_media.md`
- File Name: `mastodon-timeline-site-only_media.md`
- Categories: `social-media`
- Maintainers: `hoilc`

### Trending posts, hashtags and links
- Route ID: `mastodon:/mastodon/trends/:site/:type?`
- Route Path: `/mastodon/trends/:site/:type?`
- File: `docs/routes/mastodon/mastodon-trends-site-type.md`
- File Name: `mastodon-trends-site-type.md`
- Categories: `social-media`
- Maintainers: `DIYgod`
