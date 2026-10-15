# Balise (remote computing beacon)

CAD files of the **remote computing device** made during the Eurobot 2026 season. The device holds:

- two **Raspberry Pi cameras**,
- a **Raspberry Pi 5**,
- a **laptop stand**, used to start and monitor the robot during the game.

## Contents
- `balise 1.0/`, `balise 2.0`, `balise 3.0 dxf files/` — design iterations and laser-cutting files
- `balise + map.SLDASM` — beacon placed on the map
- `camera positioning.SLDASM` / `camera positioning 2.0.SLDASM` — camera mounting angles
- `pi5 case beacon.SLDPRT`, `beacon button.SLDPRT`, `beacon cover dxf/`, `cases stl files/` — enclosure and 3D-print files

## IMPORTANT: camera angles

If you open the CAD you will notice both cameras are fixed at a certain angle. To determine these positions we used **Blender** to find the camera angle needed to cover the whole map from the yellow side and the blue side.

Each camera in Blender has a field of view made of 4 points. We took the coordinates of three of those points, plus the coordinates of the middle of the lens. Using the latter we positioned the camera, then used the other three FOV points to create a plane in SolidWorks that should be parallel to the camera lens, which gives the exact camera angle needed.

If this explanation is missing details, ask **Mahdi Bouzidi** or **Jihed Silini**.

Thank you for your attention to this file!

---

Part of the CAD work of the **Aerobotix (INSAT, Tunisia) Eurobot 2026 team** — see the [organization](https://github.com/Eurobot-2026-CAD-departement) for the other repositories. Files are mainly SolidWorks (`.SLDPRT` / `.SLDASM`) with STEP / STL / DXF exports. Released under the [MIT License](LICENSE). Questions about anything unclear? Contact a team member.
