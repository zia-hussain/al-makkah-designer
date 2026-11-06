# Al-Makkah Estate – Post & Video Maker

Two static pages, no build step, no server:

- `index.html` – Post Maker (images)
- `video.html` – Video Maker (video, captions, end page)

Everything runs in the browser. Photos and videos are never uploaded anywhere.

## Deploy (pick one, all free)

**Netlify (easiest):** go to app.netlify.com/drop and drag this folder onto the page. You get a link instantly.

**Cloudflare Pages:** Workers & Pages > Create > Pages > Upload assets > drop this folder.

**Vercel:** install the CLI (`npm i -g vercel`), open a terminal in this folder, run `vercel --prod`.

**GitHub Pages:** create a repo, upload these files, then Settings > Pages > Deploy from branch > main / root.

Share the link with your team. Open it in Safari (iPhone) or Chrome.

## Notes

- AI caption conversion (English / Roman Urdu) needs an Anthropic API key. The first time someone converts captions, the page asks for a key and stores it only in that person's browser. Without a key, type or paste captions in the language you want; timing sync still works.
- Do not put a shared key inside the HTML. A key in a public page can be copied by anyone.
- The logo, phone numbers and office text are inside the files. Edit them in a text editor if they change.
