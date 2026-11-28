# ONAROOM

A mirror sky where up to **4 orbs** fly, talk, type, share screens and use windows together.

- One file: `index.html`. No server, no accounts, no build step.
- Browsers connect directly to each other over WebRTC. Public Nostr relays only make the first introduction.
- Voice is spatial: people sound louder when you're close, and everyone in the centre can hear each other.

Live: **https://samtreetv.github.io/ONAROOM/**

## In the room
- **Landing:** 24 orbs float between "enter lobby" and "create your own room". Touch them and yours comes to the middle with the rest orbiting; ◀ ▶ or tap to choose, Aa for your name's colour, type your name, press enter. *Float in*: your orb breaks into its own glowing dots, which gather into your orb in the world and settle in a soft flash.
- **Make a new room:** works like hosting a lobby. ✚ default · 🎲 random · 📐 architect. Architect sets the shape (circle, rounded square, oval, rounded rectangle), the number of windows (3–12) and a theme (blue42, dusk, night, peach, mint, mono). These choices are stored in the link, e.g. `#drift-u0pr-433`, so everyone who opens it gets the same room.
- **The world:** a mirror floor. The centre glows softly in the room's shape. Past the windows the floor curves into a waterfall. Fall over the edge and you drop back in over the centre. Fly up through the clouds into space, where the menu forms; you skydive back down when it closes. Flick down on a phone (or press S twice) to hop backwards.
- **Menu:** press ✚ or I. It's a solar system: 🎙 mic · 🎥 camera · 📺 screen · 👥 people · 🪟 windows · 🔊 volume (drag a person closer to make them louder) · 👁 spectate · ⚙ settings · 🕹 controls.
- **Windows:** whiteboard, YouTube or notes. 🎤 Present locks a window while you talk about it.
- **Tiles:** cameras and screens open as tiles you can drag, resize, set to 4:3 / 1:1 / 3:4, or shrink to a dot.
- **Birds:** swallows, doves, cardinals, the occasional blue jay, and every few minutes a murmuration.
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
- **v21:** float-in back to the soft flash (no lens warp), the dots start from the orb you picked and no longer leave trails; making a room: the orb picker steps aside and architect shows the real room, even from the lobby; the orb ring tilts more so orbs are easier to tap.
- **v19:** choosing your orb: it sits in the middle while the other 23 orbit around it; ◀ ▶ under them step through. Aa gives your name a new colour (it shows over your orb for everyone). Yellow game text across the whole UI. Float-in: your orb and the view hold still while the dots gather to that exact spot, then a soft flash dissolves into your orb and your name fades in above it.
- **v20:** the lobby is call mode: a plain blue gradient seen from straight above, just the orbs, everyone heard at full volume, up to 4. Calm load-in: a blue cover until the page is ready, and the landing orbs start pixely and sharpen (no flashing). Host carries weight: if two people can't connect directly, the best-connected person (a computer first) passes messages and streams between them. Rejoins on its own after wifi drops or the phone wakes.
- **v18:** a new landing: your 24 orbs float together between two words, "enter lobby" and "create your own room". Touch them and they spread into a helix, each to its nearest place; tap one, type your name, press enter and you float in. Making a room goes orb → name → room setup, then straight in. Softer orb styles (no fine threads), two-tone orbs, and the square glow is gone.
- **v17:** a new orb body made of light (threads of energy, a bright core that follows your pointer, a glowing rim); ◀ ▶ orb arrows choose from 12 colours with a sliding colour change; the landing orb breathes, spins, hops and looks at you; a short lens warp as you land; glassier menu orbs with coloured rims; a full volume page (everything, voices, closer-is-louder on/off, my orb, others' orbs, menu sounds, waterfall and wind, each person, each video window).
- **v16:** menu sounds 25% quieter, orb engine 50% quieter.
- **v15:** far fewer birds (2 small swallow schools, 3 doves, 2 cardinals, the blue jay every 4 minutes, the murmuration about 2 minutes in every 15).
- **v14:** schools of birds on separate paths: swallows in high loops, doves circling slowly, cardinals bounding low in small groups, an occasional blue jay passing alone, and a starling murmuration that dances far out every few minutes. All on a shared clock, so everyone sees the same sky.
- **v13:** float-in dots glow and dissolve into a soft flash as your orb forms, with a bell and you hold still until it has formed; prettier birds (swept wings whose tips follow a beat late, forked tails).
- **v12:** float-in dots become your actual orb.
- **v11:** host choices (shape, windows, theme) carried in the link; the centre glow matches the shape.
- **v10:** mirror floor and waterfall, falling, flying up into space, skydiving back, hop back.
- **v9:** colour landing, solar-system menu, sky orb, spectate, orb buttons.
- **v8:** screen share, tiles, 9 windows, presenter mode.
- **v7:** birds, soft aura, sky colours that blend.
