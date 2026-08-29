# The Blackwake — Three.js pirate ship viewer

Interactive Three.js scene with Kenney's CC0 `ship-pirate-large` galleon on animated water.

## View it

These files must be served over HTTP (browsers block `file://` GLB loads).

```bash
cd pirate-ship-viewer
python3 -m http.server 8080
```

Then open http://localhost:8080

Live:

- GitHub: https://github.com/lukebrady/blackwake-pirate-ship-viewer
- jsDelivr page: https://cdn.jsdelivr.net/gh/lukebrady/blackwake-pirate-ship-viewer@main/index.html

## Controls

- Drag to orbit
- Scroll / pinch to zoom onto the deck and sails
- Right-drag or two-finger drag to pan
- Press **R** (or the Reset button on phones) to reset the camera

## Credits

Ship: [Kenney Pirate Kit](https://kenney.nl/assets/pirate-kit) — CC0 1.0
Scene: Three.js r170
