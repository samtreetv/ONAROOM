# BLUE42 · Together

The sky, its mirror, the ring of 42, and up to **4 orbs** who can fly, talk and type together.

- One file: `index.html`. There's no server and no build step.
- Browsers connect straight to each other (WebRTC). Public Nostr relays only make the first introduction.
- Voice is spatial: it's louder when you're close, and everyone hears everyone inside the center circle.
- Press **I** in the world to see every control.

## Put it on GitHub Pages
1. Make a new repo (for example `blue42-together`) and upload `index.html` and this README.
2. Go to **Settings → Pages → Deploy from a branch → main / root → Save**.
3. Wait about a minute. Then open `https://<you>.github.io/blue42-together/`.
4. The address gets a room code like `#sky-7k2f`. Send that whole link to up to 3 people.

## Notes
- Mic access only works on `https://` pages, which GitHub Pages already uses.
- Headphones stop echo.
- About 1 in 10 networks (some work, school or phone networks) block direct connections. A TURN relay fixes that. One can be added later.
- Libraries: three.js r128 (loaded from cdnjs) and Trystero 0.27 (MIT, inlined).
