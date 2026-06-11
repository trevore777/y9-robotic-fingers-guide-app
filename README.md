# Year 9 STEM Robotic Fingers Guide App

This is the integrated version.

## Included

- Main `index.html` with:
  - Weekly guide tab
  - Student Evidence Scaffold tab
  - Success Criteria tab
- `styles.css`
- `app.js`
- Browser progress saving with localStorage
- Copy full scaffold button

## Run

Open `index.html` in a browser.

## Deploy

Upload the folder contents to Vercel, Netlify, GitHub Pages or any static web host.


## Teacher PIN Tab

A protected Teacher Answers tab has been added.

Default PIN:

```text
Kings2026
```

The PIN is checked with a SHA-256 hash in `app.js`. This is suitable for classroom convenience, but students can still inspect static source code if they are determined. For stronger protection, use a server-side login.
