# Harsh Vardhan — portfolio site

Everything you need to run and update the site yourself, with no coding.

## What's in this folder

| File | What it is | Do you edit it? |
|---|---|---|
| `index.html` | The house, the doors, the room and the typewriter | Rarely (see "Other text" below) |
| `work.js` | The list of work pages, in order, with their video links | **Yes, this is the one you edit** |
| `work/` | One image per work page | **Yes: upload new or updated pages here** |
| `editor.html` | A helper page for reordering pages and adding video buttons | No, you just use it |
| `.nojekyll` | Tells GitHub to serve the files as they are | No |

## The 3 things you'll do most

### 1. Change the order of pages
**Easiest:** open `your-site-link/editor.html`, press ↑ / ↓, press **Get the new work.js**, then **Copy**.
On GitHub, open `work.js` → pencil icon → select all → paste → **Commit changes**.

**Or directly:** in `work.js`, cut a whole `{ ... },` block and paste it in its new place.

### 2. Add a new page or update one (e.g. made in Canva)
1. Design it in Canva **2200 px wide**. Any height is fine. Use the yellow `#FCDE0E` or dark `#191919` background to match the site.
2. Download it as **PNG**, then shrink it at **squoosh.app**: format **WebP**, quality **80**. Aim for under 1.5 MB.
3. Give it a simple name with no spaces, e.g. `diwali-campaign.webp`.
4. On GitHub, open the `work` folder → **Add file → Upload files** → drop it in → **Commit changes**.
   - **To update an existing page**, upload with exactly the same file name. It replaces the old one, and you don't need to touch anything else.
   - **For a new page**, open `editor.html` → **+ Add a page** → type `work/diwali-campaign.webp` → choose its position → **Get the new work.js** → paste it into `work.js` on GitHub.

### 3. Make a video play
Open `editor.html` → on that page press **+ Video area** → drag a box over the thumbnail → paste the link → **Get the new work.js** → paste into `work.js` on GitHub.

These links play inside the site: **YouTube, Google Drive, Instagram reels and Vimeo**. Google Drive files must be shared as **"Anyone with the link"**.

Changes go live about a minute after you commit. If you still see the old version, open the site in a private window.

## If something breaks
- **A red bar says work.js has a typo:** on GitHub open `work.js` → **History** → open the last version that worked → copy all of it → edit `work.js` → paste → commit.
- **A page is missing:** the file name in `work.js` doesn't exactly match the file in `work/`. Names are case-sensitive.
- **A video won't play:** check that the Drive file is shared as "Anyone with the link".

## Other text (email, TEDx link, intro)
In `index.html`, use the search box on GitHub (or Cmd/Ctrl + F in the editor) for:
- `hireharshtowrite@gmail.com` (appears 3 times: the Hire button, the Get in touch button, and the address under it)
- `Mxst3gs8Awg` (the TEDx talk link on the intro page)

Change only the text between the quotes, then commit.

## First-time setup (GitHub Pages)
1. Create a free account at github.com.
2. **New repository** → name it `yourusername.github.io` (this gives you the cleanest web address) → **Public** → Create.
3. **uploading an existing file** → drag in **everything from this folder**, including the `work` folder → **Commit changes**.
4. **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** / **(root)** → Save.
5. After 1–2 minutes the site is live at `https://yourusername.github.io`.
