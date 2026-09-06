# roversa-rally - 3D Print and CAD files

Game pieces matching the Roversa buttons and faces of the direction-die.

The direction-die itself has a separate repository: https://github.com/Roversa-Robotics/direction-die-3dp

---

## Repository Structure

The files in this repository are organized as follows:

├── cad/
│   └── roversa-rally.f3d         # Native Fusion 360 parametric design archive
├── exports/
│   ├── directional-die.step      # Universal CAD exchange format for solid modeling
│   ├── 3mf/                      # Mesh format preserving 2-color print structure
│       ├── 3mf/roversa-text-piece.3mf
│       ├── 3mf/logo-piece.3mf
│       ├── 3mf/left-turn-piece.3mf
│       ├── 3mf/right-turn-piece.3mf
│       ├── 3mf/down-arrow-piece.3mf
│       └── 3mf/up-arrow-piece.3mf
└── README.md                     # Project overview and finishing guide

* **`cad/`**: Contains the original Fusion 360 source archive (`.f3d`) preserving feature history, sketches, and parametric dimensions.
* **`exports/`**: Contains production-ready files including standard `.3mf` for 3D printer slicers and high-precision `.step` files for import into other CAD software.

NOTE: each update that changes the f3d file should also update the step and 3mf files accordingly.
