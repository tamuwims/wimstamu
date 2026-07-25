[README.md](https://github.com/user-attachments/files/30380372/README.md)
# WIMS TAMU Website

A single-page site for Women in Materials Science at Texas A&M. Styled
plainly and simply — everything, including the logo, lives inside one file:
`index.html`.

## What you have

Just **`index.html`**. That's it — the logo is embedded directly inside the
file as image data, so there's no separate `assets` folder or logo file to
keep track of. Upload this one file to GitHub and you're done.

⚠️ Make sure the file is named exactly **`index.html`** (not `.htm`) —
GitHub Pages looks for that exact name to serve as your homepage.

## 1. Google Calendar — already connected ✅

The site is wired up to `tamu.wims@gmail.com`. One thing to double check:

- In Google Calendar → **Settings** → your WIMS calendar → **Access
  permissions**, make sure **"Make available to public"** is checked, or
  the embed will show blank to visitors who aren't logged in as an editor.

If you ever need to point the site at a *different* calendar:
1. Open **Google Calendar** → gear icon → **Settings**.
2. Click the calendar you want under "Settings for my calendars."
3. Scroll to **Integrate calendar** and copy the **Calendar ID**
   (e.g. `abc123xyz@group.calendar.google.com`).
4. Open `index.html`, search for `tamu.wims%40gmail.com` (appears twice —
   once in the embed `iframe`, once in the "Add to my Google Calendar"
   button) and replace both with your new ID. Keep the `%40` — it's just
   an encoded `@` symbol.

## 2. Edit placeholder content

- **Officers section**: search for `<div class="officer">` to find each
  card — names, roles, and initials are already filled in with your real
  officers. Add photos or bios if you'd like by editing that markup.
- **About section**: the mission text is a first draft — search for
  `id="about"` and edit freely to match your chapter's voice.
- **Contact section**: email and social links (Instagram, LinkedIn) are
  already live. Update them if they ever change — search for `instagram.com`
  or `linkedin.com` to find those lines.

## 3. Publish it (GitHub Pages — free)

1. Create a new **public** repo on GitHub (e.g. `wims-website`).
2. Upload `index.html` (drag and drop it in via "uploading an existing file").
3. Commit the change.
4. Go to **Settings → Pages**, set Branch to `main` / `/(root)`, and Save.
5. Your site goes live at `https://yourusername.github.io/wims-website/`
   within a minute or two.

## 4. Want to update it later?

- **Easiest**: edit directly on GitHub.com — open `index.html`, click the
  pencil icon, make changes, commit. The live site updates automatically.
- **With AI help**: paste the relevant section of `index.html` into a chat
  with Claude, describe the change you want, and paste back the replacement
  code it gives you.
- **Claude Code** (claude.ai/code): if you're on a paid Claude plan, you can
  connect this GitHub repo directly and describe changes in plain English —
  it edits and commits for you.
