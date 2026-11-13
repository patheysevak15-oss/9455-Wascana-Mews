# 4154 Fieldstone Way, Regina

The listing website for 4154 Fieldstone Way (The Creeks), hosted on Vercel.

Until the real site is added, `index.html` shows a "Coming soon" page.

## Put the listing website in this repository

1. In **Listing Studio**, fill in the listing, add photos and video, and click **Download website**.
2. Unzip the download. It contains `index.html` and the folders `photos/`, `images/` and `media/`.
3. On GitHub, open this repository and choose **Add file → Upload files**.
4. Drag in everything from the unzipped folder (the files and folders themselves, not the outer folder). Replace the existing `index.html`.
5. Click **Commit changes**. Vercel publishes the update within a minute.

GitHub's website accepts files up to 25 MB each. If the video is bigger, upload it to YouTube or Vimeo and paste that link into Listing Studio instead.

## Connect to Vercel (one time)

1. Go to vercel.com/new and sign in with GitHub.
2. Import this repository. Leave **Framework Preset** as **Other** and the build settings empty.
3. Click **Deploy**. Your site is live at `<project-name>.vercel.app`.
4. Optional: in the Vercel project, open **Settings → Domains** to add a domain such as `4154fieldstoneway.com`.

Every change committed to `main` redeploys the site automatically.

## Updating the listing

Change it in Listing Studio (price, status, photos), download again, and upload the new files the same way.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The website page |
| `photos/` | Listing photos (01.jpg is the cover) |
| `images/` | Agent headshot and brokerage logo |
| `media/` | Uploaded video tour |
| `vercel.json` | Vercel settings: clean URLs and one-week caching for photos and video |
