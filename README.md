# SW Genomic AI Group website

A simple GitHub Pages (Jekyll) site. No coding needed for day-to-day updates.

## Publish it
1. Create a GitHub repository and upload all these files.
2. Go to **Settings → Pages**, set Source to *Deploy from a branch*, branch `main`, folder `/ (root)`.
3. After a minute the site is live at `https://<username>.github.io/<repo>/`.
   If using a repo name (not `username.github.io`), set `baseurl: "/<repo>"` in `_config.yml`.

## Everyday edits
| To change… | Edit |
|---|---|
| Group name, tagline, sign-up link, email | `_config.yml` |
| "Who we are" and objectives text | `index.html` (look for `EDIT` comments) |
| Colours and fonts | top of `assets/style.css` |

## Add a news post or event
1. In GitHub, open the `_posts` folder and click **Add file → Create new file**.
2. Name it `YYYY-MM-DD-short-title.md` (e.g. `2026-12-03-winter-seminar.md`).
3. Copy the contents of `_posts/_TEMPLATE.md`, fill it in, and commit.

Posts appear on the home page newest first. Delete a post by deleting its file.
