# 16 Lipton Place, Regina

Listing website for **16 Lipton Place, Regina, SK S4R 3T6** (Coronation Park), MLS® SK049505, listed at $419,900 by Vipul Rabari and Sam Patel, Royal LePage Next Level.

It's a static site: `index.html` plus 46 photos. There is no build step.

## Put it online with Vercel (one time)

1. Go to vercel.com/new and sign in with GitHub.
2. Import this repository. Leave **Framework Preset** as **Other** and the build settings empty.
3. Click **Deploy**. The site goes live at `<project-name>.vercel.app`.
4. Optional: add a custom domain under **Settings → Domains** in the Vercel project.

Every commit to `main` redeploys the site automatically.

## Updating the listing

Make the change in **Listing Studio**, click **Download website**, and upload the unzipped files here with **Add file → Upload files**, replacing the old ones. Or ask Claude to make the change and push it.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The website page |
| `photos/` | Listing photos, 1600 px wide (`01.jpg` is the cover) |
| `vercel.json` | Vercel settings: clean URLs and one-week caching for photos |

Listing information and photos are from the brokerage's published listing. Information deemed reliable but not guaranteed.
