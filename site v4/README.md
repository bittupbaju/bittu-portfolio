# Bittu P Baju — Portfolio Site

This is a single self-contained static site (`index.html`) — no build step, no dependencies to install.

## Option A — Netlify or Vercel (easiest, free, live in ~1 minute)
1. Go to https://app.netlify.com/drop (or https://vercel.com/new)
2. Drag the whole `site` folder (the one containing `index.html`) onto the page
3. You'll get a live URL immediately (e.g. yourname.netlify.app)
4. Both let you connect a custom domain later for free, under Site settings > Domain management

## Option B — GitHub Pages
1. Create a new repository on GitHub, e.g. `bittu-portfolio`
2. Upload `index.html` to the root of the repo (GitHub website: Add file > Upload files)
3. Go to Settings > Pages > set Source to "Deploy from a branch" > branch `main`, folder `/root`
4. Your site will be live at https://yourusername.github.io/bittu-portfolio within a couple of minutes

## Option C — Any other static host (Hostinger, GoDaddy, Bluehost, etc.)
Just upload `index.html` into the public/www root folder via their file manager or FTP. No special configuration needed since there's no backend.

## Images
All photos now live locally in the `images` folder and are referenced as `images/filename.jpg` in `index.html` — nothing is pulled from Google Sites anymore, so this will keep working regardless of what happens to the old site.

Want to swap or add photos? Just replace a file in `images` with the same filename, or add a new file and add a matching `<figure>` block in the relevant section of `index.html`.

## Custom domain
All three options above support pointing a custom domain (e.g. bittupbaju.com) at the site for free — just needs a DNS change with whoever you buy the domain from. Ask if you'd like the exact steps once you've picked a host.
