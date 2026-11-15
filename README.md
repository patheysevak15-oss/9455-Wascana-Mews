# 9455 Wascana Mews, Regina

Listing website for **9455 Wascana Mews, Regina, SK S4V 2V5** (Wascana View), MLS® SK053302, listed at $829,000. Presented by The Real Estate Gurus. Listing agents: Qing Zhang and Sam Patel, Royal LePage Next Level.

It's a static, single-page site in black and red: address, photos, highlights, video (when added) and agent contact. There is no build step.

## Put it online with Vercel (one time)

1. Go to vercel.com/new and sign in with the Vercel account you want to use, connected to GitHub.
2. Import this repository. Leave **Framework Preset** as **Other** and the build settings empty.
3. Click **Deploy**. The site goes live at `<project-name>.vercel.app`.
4. Optional: add a custom domain under **Settings → Domains** in the Vercel project.

Every commit to `main` redeploys the site automatically.

## Updating the site

Make changes in **RE Listing** (address, highlights, photos, video, agents, navbar title and logo), click **Download website**, and upload the unzipped files here with **Add file → Upload files**, replacing the old ones. Or ask Claude to make the change and push it.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The website page |
| `photos/` | 64 listing photos (`01.jpg` is the cover) |
| `images/` | Logo and agent headshots, when added |
| `media/` | Uploaded video, when added |
| `vercel.json` | Vercel settings: clean URLs and one-week caching for photos and media |

Listing information and photos are from the brokerage's published listing. Information deemed reliable but not guaranteed.
