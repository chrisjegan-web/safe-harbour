# Safe Harbour

A line-drawing harbour game for phones. Drag from a ship to draw its course, bring each crate to the dock of its colour, and keep the ships apart.

**Play:** open the GitHub Pages address for this repository on your phone, hold the phone sideways, and add the page to your home screen.

## Two players

One player taps **Two players → Host a game** and gets a four-letter code. The other taps **Two players → Join a game** and enters it (or opens the invite link). The phones then connect directly to each other. Send an empty ship off the marked edge to push it into your opponent's harbour; the first harbour with a collision loses.

## Files

- `index.html` – the whole game (art, sound and rules are generated in code)
- `peerjs.min.js` – [PeerJS](https://peerjs.com) 1.5.5 (MIT licence), used to connect two phones
- `manifest.json`, `icon-*.png` – home-screen name and icon
