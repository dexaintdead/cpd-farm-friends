# Farm Friends · farmfriends.contentpad.io

The kids' page for **Oak Hill Farm: Farm Friends**. This is the address printed (with a QR code) on
The End page of the Oak Hill Farm mini story books.

- `index.html` plays the game from `https://arcade.contentpad.io/oak-hill-farm.html?home=farm` in a
  full-screen frame. There are **no links to the rest of the Arcade** on purpose: the Arcade has games
  that are not for young children.
- `?home=farm` tells the game to say "Leave the game" instead of mentioning the Arcade. Leaving (or the
  browser's back button) returns to this page.
- The game's on/off switch in Arcade HQ still applies. If it's off, the frame shows a link-free
  "Farm Friends is resting right now" note (arcade `gate.js` + `unavailable.html?home=farm`).
- Coloring pages print through this page (the frame is sandboxed without modals), the same way the
  Arcade's play page does it.
- Hosting: GitHub Pages, custom domain via `CNAME`. Cloudflare DNS: `farmfriends` CNAME
  `dexaintdead.github.io`, **DNS only** (grey cloud).
