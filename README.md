# AR Coin Flip 🪙

A web-based 3D augmented reality coin flip — runs entirely in the browser, no app install needed.

**[▶ Live Demo](https://YOUR-USERNAME.github.io/ar-coin-flip/)**

---

## How it works

Built with [A-Frame](https://aframe.io) + [AR.js](https://ar-js-org.github.io/AR.js-Docs/). A gold 3D coin appears anchored to a **Hiro marker** through your camera. Tap **Flip Coin** (or tap the coin itself) to flip — heads or tails lands randomly with a spin animation and sound.

## Usage

1. Open the live URL on your phone (requires HTTPS — GitHub Pages provides this)
2. Allow camera access
3. Print the Hiro marker **or** open it on another screen:  
   👉 https://raw.githack.com/AR-js-org/AR.js/master/data/images/hiro.png
4. Point your camera at the marker — the coin appears
5. Tap **Flip Coin**

## Host on GitHub Pages (5 steps)

1. Create a new GitHub repo (e.g. `ar-coin-flip`)
2. Upload `index.html` to the `main` branch
3. Go to **Settings → Pages**
4. Set source: **Deploy from branch → main → / (root)**
5. Your site is live at `https://YOUR-USERNAME.github.io/ar-coin-flip/`

> **Note:** Camera access requires HTTPS. GitHub Pages handles this automatically.

## Tech stack

| Library | Purpose |
|---------|---------|
| [A-Frame 1.5](https://aframe.io) | Declarative 3D/WebGL scene |
| [AR.js 3.4.5](https://ar-js-org.github.io/AR.js-Docs/) | Marker-based AR via webcam |
| Web Audio API | Procedural coin-flip sound |

Everything loads from CDN — `index.html` is the only file needed.
