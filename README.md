# SoftRewire Legal (Andel)

This repository hosts legal pages for the **Andel** app.

- `index.html` — entry page
- `terms.html` — Terms of Service
- `privacy.html` — Privacy Policy
- `tiktok-verify.txt` — TikTok verification file (put the exact string shown in TikTok Developer Portal)

## How to publish on GitHub Pages
1. Commit these files to the repository root (main branch).
2. Go to **Settings → Pages**.
3. Source: *Deploy from branch*, Branch: *main*, Folder: */ (root)* → Save.
4. Your site will be available at: `https://<username>.github.io/<repo-name>/`

## TikTok verification
1. In TikTok Developer Portal choose **URL prefix** and paste your Pages URL.
2. TikTok will show a token like `tiktok-site-verification=xxxx`.
3. Put that exact token into `tiktok-verify.txt` and commit.
4. Click **Verify** in TikTok.
