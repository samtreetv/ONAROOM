# ONAROOM

A mirror sky where up to **4 orbs** fly, talk, type, share screens and use windows together.

- One file: `index.html`. No server, no accounts, no build step.
- Browsers connect directly to each other over WebRTC. Public Nostr relays only make the first introduction.
- Voice is spatial: people sound louder when you're close, and everyone in the centre can hear each other.

Live: **https://samtreetv.github.io/onaroom/**

## In the room
- **Landing:** pick your orb's colour on the ring. Orbs already in the room sit on the ring in their colours. *Float in*: your orb breaks into its own dots, which gather into your orb in the world.
- **Make a new room:** works like hosting a lobby. ✚ default · 🎲 random · 📐 architect. Architect sets the shape (circle, rounded square, oval, rounded rectangle), the number of windows (3–12) and a theme (blue42, dusk, night, peach, mint, mono). These choices are stored in the link, e.g. `#drift-u0pr-433`, so everyone who opens it gets the same room.
- **The world:** a mirror floor. The centre glows softly in the room's shape. Past the windows the floor curves into a waterfall. Fall over the edge and you drop back in over the centre. Fly up through the clouds into space, where the menu forms; you skydive back down when it closes. Flick down on a phone (or press S twice) to hop backwards.
- **Menu:** press ✚ or I. It's a solar system: 🎙 mic · 🎥 camera · 📺 screen · 👥 people · 🪟 windows · 🔊 volume (drag a person closer to make them louder) · 👁 spectate · ⚙ settings · 🕹 controls.
- **Windows:** whiteboard, YouTube or notes. 🎤 Present locks a window while you talk about it.
- **Tiles:** cameras and screens open as tiles you can drag, resize, set to 4:3 / 1:1 / 3:4, or shrink to a dot.
- **Sky orb** (top left): choose from 9 skies; a history shows who added which colour.

## Host it yourself
1. Upload `index.html` to a repo.
2. Go to Settings → Pages → Deploy from a branch → `main` / root.
3. Open `https://<you>.github.io/<repo>/`.

## Notes
- The mic only works on `https://` pages, which GitHub Pages already uses.
- Headphones stop echo.
- About 1 in 10 networks (some work, school or phone networks) block direct connections. A TURN relay would fix that later.

## Credits
- three.js r128 (MIT), loaded from cdnjs. Trystero 0.27 (MIT), inlined.
- The tilt and aspect ideas are ported from Bencho free blocks (MIT, © 2026 Lorenzo Cabra).
- Pixelify Sans and Noto Emoji: SIL Open Font License.

## Versions
- **v12:** float-in dots become your actual orb.
- **v11:** host choices (shape, windows, theme) carried in the link; the centre glow matches the shape.
- **v10:** mirror floor and waterfall, falling, flying up into space, skydiving back, hop back.
- **v9:** colour landing, solar-system menu, sky orb, spectate, orb buttons.
- **v8:** screen share, tiles, 9 windows, presenter mode.
- **v7:** birds, soft aura, sky colours that blend.
