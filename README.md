# Home 3D & 2D

An interactive 3D walkthrough and 2D floor plan viewer for a two-storey family home — explore the house from every side, step inside, switch design options and watch guided tours, all in the browser.

**▶ Live demo:** https://YOUR-USERNAME.github.io/home-3d/

![Front view](screenshots/front.jpg)

---

## Features

### Views
| View | What it shows |
|---|---|
| **Exterior** | The whole house and compound — drag to orbit, scroll or pinch to zoom |
| **Ground floor** | Cut-away of the ground floor with furniture |
| **First floor** | Cut-away of the first floor with furniture |
| **Ground 2D / First 2D / Roof 2D** | Clean 2D plans with room names, dimensions and a compass |

### Design options (control bar)
Every control has a small label under its icon showing the current setting.

| Control | Options |
|---|---|
| **Bed suite** | Show or hide the first-floor bedroom suite |
| **Roof** | Concrete roof or pitched sheet roof on the suite |
| **Rain court** | Keep the rain court, or remove it and extend the porch |
| **Porch** | Slotted porch wall or painted grey pillars |
| **Safety grill ▾** | None, Wooden, Black, White or Grey grill on the north and west windows (both floors) |
| **Frame ▾** | Glass-window frame colour: Black, Grey, White, Wooden, Bronze or Champagne |
| **Mirror glass** | One-way mirror glass on the north and west windows — reflects the surroundings from outside, clear from inside |
| **Grill** | Fold or close the sit-out safety grill |
| **Day / Evening** | Daylight or evening sky with all lights on |
| **Rain** | Rain shower through the roof opening into the indoor rain pool |
| **Pan view** | Switch dragging between rotate and pan |

### Guided tours
- **Exterior tour** (≈40 s) — a full circle around the house: front, east, south and west sides.
- **Interior tour** (≈2 min 14 s) — entrance and sit-out, living room, rain pool and indoor garden, aquarium, hall and dining, up the staircase to the first-floor hall, master bedroom and its balcony, then the kitchen roof with the west and north views.

Tours can be paused, resumed or stopped at any time (Esc also stops).

---

## Design highlights
- Double-height living room with a glass roof opening (secured with grey bars) and a hanging chandelier
- Indoor rain pool, stone-lined garden beds and an aquarium with a flat water fountain
- North elevation with teak fins, vertical teak battens and a full-height slat panel
- Wood-framed windows with frosted glass and white grills on the east and south sides
- Open first-floor balcony with exposed precast concrete walls, box-bordered windows and planters
- White precast first-floor west wall facing the kitchen roof terrace
- Sit-out with a glass sunroof, white security bars and a folding safety grill
- Porch with recessed ceiling lights, rooftop solar panels and a white water tank

---

## Screenshots

| | |
|---|---|
| ![Aerial](screenshots/aerial.jpg) | ![West side](screenshots/west.jpg) |
| **Aerial view** | **West side** |
| ![Evening](screenshots/evening.jpg) | ![Living room](screenshots/living.jpg) |
| **Evening** | **Living room** |
| ![First floor hall](screenshots/first_floor_hall.jpg) | ![Ground floor plan](screenshots/plan_ground.jpg) |
| **First floor hall** | **Ground floor 2D plan** |

---

## Run it

No build step and no install — it is a single HTML file.

- **Online:** open the live demo link above.
- **Offline:** download `index.html` and open it in Chrome, Edge, Safari or Firefox.

An internet connection is needed the first time, because the 3D engine ([three.js r128](https://threejs.org/)) loads from the cdnjs CDN.

Works on desktop, tablet and phone (touch: drag to rotate, pinch to zoom).

---

## Project structure

```
├── index.html        # the complete app (3D model, 2D plans, controls, tours)
├── README.md
└── screenshots/      # images used in this README
```

---

## Hosting on GitHub Pages

1. Upload `index.html`, `README.md` and the `screenshots` folder to the repository.
2. Go to **Settings → Pages**.
3. Set **Source** to *Deploy from a branch*, **Branch** to `main`, folder `/ (root)`, and save.
4. The site goes live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/` within a minute or two.

---

## Note

This is a concept visualisation. Structural details, sizes and site dimensions need verification by a qualified engineer before construction.

---

**Dev: nasih_chevapra**
