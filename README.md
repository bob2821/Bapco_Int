# BE journey · Sliding screen (Zone 04)

Interactive content for the 6 m sliding screen at the Bapco Energies BE Journey Exhibition / Annual Employee Awards 2026.

- Native canvas 2160 × 3840 (65" 4K portrait); scales to fit any window.
- Flow: logo reveal → logo to top → one main stroke → start screen forms and stays.
- Touch a topic (or a stop on the position bar) to open it; **Home** and **Next** on every topic page.
- 60 fps, GPU transforms only.

## Launch on GitHub Pages
1. Create a new repository and upload **all files in this folder** to the root (no subfolders needed).
2. Repository **Settings → Pages → Build and deployment → Deploy from a branch**, branch `main`, folder `/ (root)` → **Save**.
3. Open the URL GitHub shows (e.g. `https://<user>.github.io/<repo>/`).

## Run on the kiosk PC (offline)
Open `index.html` in Chrome, ideally in kiosk mode:
```
chrome.exe --kiosk --autoplay-policy=no-user-gesture-required "file:///C:/path/to/folder/index.html"
```

## Files
| File | What it is |
|---|---|
| `index.html` | The app (all layout, animation and navigation) |
| `home_bg.mp4` | Intro background: logo reveal + main stroke (60 fps) |
| `BeTomorrow-*.ttf` | Brand typeface |
| `logo_stacked_white.png`, `logo_horizontal_white.png` | Bapco Energies logos |
| `stroke_bottom.png` | Start-screen supergraphic stroke |
| `t1-000.png … t4-003.png` | Topic photos (4 per topic) |

Note: the repository will contain client brand assets and photos. Keep it **private** unless the client approves public hosting (GitHub Pages on private repos needs a paid plan).
