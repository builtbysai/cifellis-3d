# Cifelli's Pizza — 3D Pizza Shop

A 3D pizza shop you can walk around. Built for Cifelli's Pizza, 700 Chews Landing Road, Lindenwold, NJ — as a fresh, single-file Three.js scene.

**Live:** https://builtbysai.github.io/cifellis-3d/

## What it is

One self-contained `index.html` (Three.js inlined, no build step, no external assets). Open it in a browser and:

- **Enter the shop** — the camera pulls back from a close-up of the neon sign to the storefront, after dark.
- **🍕 Menu** — glides in close on the storefront and opens the real menu: Large 16" $15.99, The Works, Buffalo Chicken, and the home of the Original Tarantini Panzarotti® ($8.25). Prices and items from [cifellis.com/menu](https://www.cifellis.com/menu/).
- **🔥 The Oven** — glides in close on the oven on the side wall, fire glowing in the mouth. Click the pizza on the peel (or the button) to toss it.
- **📍 Visit** — glides in close on the poster by the door: address, hours, and phone: 700 Chews Landing Road, Lindenwold, NJ 08021 · (856) 435-8799 · Sun–Wed 11am–9pm, Thu–Sat 11am–10pm.
- **🏠 Rooftop** — an isometric aerial of the whole diorama.
- **After dark, by default** — the shop stands in a black void under a warm spotlight pool, neon on, stars out, fireflies drifting. The ☀️ Day button switches to daylight. Light all four lanterns and the neon burns brightest.

Drag to look around, scroll to zoom. Click the hero pizza to toss it, the menu board to open the menu.

## How to run

No server needed — open `index.html` in any modern browser. Or serve the folder:

```
python3 -m http.server
```

## Credits

- Concept inspired by Ariyan Molazem's 3D burger-shop portfolio ([ariyanmolazem.ir](https://ariyanmolazem.ir/), [threejs-react-Portfolio](https://github.com/AriyanMLZM/threejs-react-Portfolio), [three.js forum thread](https://discourse.threejs.org/t/my-3d-portfolio-burger-shop/67946)). The structure was studied from a private reference copy; every line of code and every visual in this repo is original.
- The shop itself is modeled from photos of the real Cifelli's storefront (tan brick, red-and-green sign board, neon OPEN sign, white bench) and the real menu from cifellis.com.
- Three.js r160 (MIT), inlined. No other dependencies.

Not affiliated with Cifelli's Pizza. Order the real thing at [cifellis.com](https://www.cifellis.com/).
