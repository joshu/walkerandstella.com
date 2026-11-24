# walkerandstella.com

The website for The Adventures of Walker and Stella: a static site, no build step.

- `index.html` home page ("coming soon" until launch)
- `get/` the address on stickers and T-shirts (QR codes in `print/`). Until launch it
  sends people to the home page. **On launch day** change the two URLs in
  `get/index.html` to the App Store page, and swap the home page's "Coming soon"
  badge for the App Store link.
- `privacy/`, `support/` the pages Apple requires for the App Store listing
- `print/` QR codes (`https://walkerandstella.com/get`) and large dog sprites for stickers.
  The sprites come from the game (`Content/sprites`, via spritegen).

Preview: `python3 -m http.server 8411` here, then http://localhost:8411/.
