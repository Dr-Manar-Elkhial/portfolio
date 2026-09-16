# Manar Elkhial — Portfolio Website (multi-page, self-contained)

This version fixes the earlier problem for good: **every page carries its
own complete design built in.** There is no shared style.css or script.js
file anymore — so deleting or mis-uploading one file can never break the
look of another page again.

## What's inside
```
index.html      Home (lean overview + links to every topic)
about.html      About
journey.html    Career timeline
practice.html   Practice — links to the 7 case studies
research.html   Research & publications
teaching.html   Teaching & training
contact.html    Contact
practice/       One page per case study (papyrus.html, parchment.html,
                paper.html, polychrome-coffin.html, atmosphere-system.html,
                tutankhamun-gallery.html, teaching-training.html)
photos/         Your own photos go here (see table below)
```
Every `.html` file above is complete on its own — you could delete any
other file in this list and the rest of the site keeps working perfectly.

## First-time publishing (or replacing what's live now)
1. Open your GitHub repository.
2. Delete whatever is currently there (index.html and anything else),
   **except** your `photos` folder if you've already added real photos.
3. Click "Add file" → "Upload files".
4. Drag in **every file and folder from this package at once** — including
   the `practice` folder.
5. Commit changes. Settings → Pages should already be turned on from
   before, so no need to redo that step.
6. Visit your live link and hard refresh (Ctrl+Shift+R / Cmd+Shift+R).

## Adding your own photos — no code needed
Upload a photo with the exact filename below into the `photos` folder in
your repository, and it replaces the placeholder box automatically:

| Case study                                  | Exact filename                     |
|-----------------------------------------------|-------------------------------------|
| Ancient Egyptian Papyrus                      | `photos/papyrus.jpg`                |
| Islamic Parchment                             | `photos/parchment.jpg`              |
| Jewish Paper Manuscripts                      | `photos/paper.jpg`                  |
| Archaeological Wood & Polychrome Objects      | `photos/polychrome-coffin.jpg`      |
| Modified-Atmosphere & IPM System               | `photos/atmosphere-system.jpg`      |
| Tutankhamun Galleries                         | `photos/tutankhamun-gallery.jpg`    |
| Curriculum Design & Training                  | `photos/teaching-training.jpg`      |

**How:** on your computer, make a folder called `photos`, put your renamed
photos inside it, then in your repository click "Add file" → "Upload
files" and drag that whole `photos` folder in. Commit changes.

## Editing text yourself
Open any `.html` file on GitHub → click the pencil icon (top right) → edit
the text directly in the browser → Commit changes. Because every page is
self-contained, you never need to touch more than the one file you're
editing.
