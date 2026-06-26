# Chess Set — 3D Modeled in Blender

> A complete **Staunton-style chess set** modeled from reference in Blender — all six piece types plus a board — with each piece exported to STL for 3D printing. An original 3D-modeling project: every piece built by hand from reference photographs of a classic tournament set.

## About

This project recreates a traditional **Staunton** chess set — the standardized design used in tournament play — as 3D models. Each piece was modeled individually in Blender using reference images of a real set, then exported as an STL so it can be 3D-printed. The goal was a faithful, printable set and the modeling practice of capturing each piece's distinct silhouette: the rook's crenellations, the bishop's mitre, the knight's carved horse head, the queen's coronet, and the king's cross finial.

---

## What's in the repo

```
chess-set/
├── Pieces/                 # Each piece as its own Blender file
│   ├── Base.blend          #   shared base/foot used across pieces
│   ├── Pawn.blend
│   ├── Rook.blend
│   ├── Knight.blend
│   ├── Bishop.blend
│   ├── Queen.blend
│   └── King.blend
├── Models/
│   └── ChessBoard.blend    # The board
├── Final Scenes/
│   └── Beginning.blend     # The pieces assembled into a scene
├── Stls/                   # STL exports of each piece (3D-print ready)
│   └── Pawn.stl, Rook.stl, Knight.stl, Bishop.stl, Queen.stl, King.stl
└── References/             # Reference images used while modeling
    ├── White/
    └── Brown/
```

---

## 3D printing

Every piece is provided as an STL in `Stls/`. Drop any of them into a slicer (Cura, PrusaSlicer, Bambu Studio) to print. A few practical notes:

- The taller pieces (King, Queen) may benefit from supports depending on your printer and orientation.
- Scale all pieces by the same factor in your slicer to keep the set proportional.

---

## Opening the models

1. Install [Blender](https://www.blender.org/download/) (free).
2. Open any `.blend` file in `Pieces/`, or open `Final Scenes/Beginning.blend` to see the assembled set.

---

## Adding a render

This repo currently ships the model files but no final image. To give it a proper showcase:

1. Open `Final Scenes/Beginning.blend`.
2. Set up lighting and a material for the pieces (a smooth off-white/ivory works well for a Staunton set).
3. Render (`F12`) and save the image as `render.png` in the repo root.

A single good render is what turns this from a folder of files into a portfolio piece. Uploading the set to **Sketchfab** is also worth considering — it gives viewers an interactive 3D model they can rotate.

---

## Tools

- **Blender** — modeling and STL export.
- Modeled from reference photographs of a classic Staunton tournament set.
