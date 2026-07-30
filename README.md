# Midway Residency website

Premium static property website for Syed Real Estate Builders & Developers, ready for GitHub Pages.

## Publish

Push this repository to GitHub, then open **Settings → Pages** and select **GitHub Actions** as the source. Every push to `main` or `master` will publish the `website` folder automatically.

## Directory layout

| Path | Contents | In Git? |
|---|---|---|
| `website/` | The published site (HTML, images, video) | Yes — deployed to GitHub Pages |
| `channel/` | YouTube channel workspace: branding, launch plan, voice scripts, video production | No (local only) |
| `source-media/` | Raw WhatsApp exports from the developer: `images/`, `videos/`, `audio/`, `chat-export/` | No (local only) |
| `private/` | Financial documents (bank receipt) | No (local only) |

Private WhatsApp exports, financial documents, the channel workspace and other raw source media are excluded from Git by `.gitignore`.
