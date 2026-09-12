# Manar Elkhial — Portfolio Website (multi-page)

This is now a real multi-page site. Every menu item and every case study
opens its own page with its own address — nothing is a pop-up anymore.

## What's inside
```
index.html          Home
about.html           About
journey.html         Career timeline
practice.html        Practice — links to the 7 case studies below
research.html        Research & publications
teaching.html        Teaching & training
contact.html         Contact
style.css            Shared design for every page
script.js            Shared mobile-menu behaviour
practice/            One real page per case study:
  papyrus.html
  parchment.html
  paper.html
  polychrome-coffin.html      (flagship)
  atmosphere-system.html      (flagship)
  tutankhamun-gallery.html
  teaching-training.html
photos/              Drop your own photos here (see below)
```

## Publishing it (first time) — GitHub Pages, free
1. Create a free account at https://github.com if you don't have one.
2. New repository → Public → don't add a README/license (you already have one).
3. On the repo's empty page, click **"uploading an existing file"**.
4. **Drag the whole `portfolio-site` folder** (not just one file) into the
   upload box — GitHub keeps the `practice/` and `photos/` subfolders intact
   when you drop a folder. Commit changes.
5. Go to **Settings → Pages** → Branch: `main`, folder `/(root)` → Save.
6. Your live URL appears on that same page after about a minute, e.g.
   `https://yourusername.github.io/portfolio/`

If you already have the single-page version live in a repository, you can
instead open that existing repo and use **Add file → Upload files**, drag
this whole folder in, and commit — it will add the new pages alongside
(or replace) what's there.

## Adding your own photos — no code needed
Upload a photo with the **exact filename** below into the `photos/` folder
in your repository, and it replaces the placeholder box automatically:

| Where it appears                          | Exact filename                     |
|--------------------------------------------|-------------------------------------|
| Ancient Egyptian Papyrus                    | `photos/papyrus.jpg`                |
| Islamic Parchment                           | `photos/parchment.jpg`              |
| Jewish Paper Manuscripts                    | `photos/paper.jpg`                  |
| Archaeological Wood & Polychrome Objects    | `photos/polychrome-coffin.jpg`      |
| Modified-Atmosphere & IPM System            | `photos/atmosphere-system.jpg`      |
| Tutankhamun Galleries                       | `photos/tutankhamun-gallery.jpg`    |
| Curriculum Design & Training                | `photos/teaching-training.jpg`      |

**How:** open your repo → open the `photos` folder → **Add file → Upload
files** → drag your photo in (rename it first on your computer to match the
filename above) → Commit changes. Refresh the live site.

## Editing text yourself
Every page is plain HTML. Open any `.html` file on GitHub → click the pencil
icon (top right) to edit in the browser → find the text → change it →
**Commit changes**. The site updates within about a minute.

To edit a case study's text (the four stages under Condition, Analysis,
Treatment, Outcome), open its file inside the `practice/` folder.

## Sending me updates
Anytime you want a change, tell me (or send me new photos) in chat — I'll
hand you the updated file(s). Re-upload them the same way: **Add file →
Upload files**, drop the file(s) in, Commit changes.
