# kicad-missing-parts

> If you've spent hours looking for this footprint, you're in the right place.

An open-source collection of KiCad symbols, footprints, and STEP models for 
components missing from UltraLibrarian and SnapMagic. All designs verified 
against manufacturer datasheets.

---

## Contents

| Part Number | Manufacturer | Package | Symbol | Footprint | 3D Model | Tested on PCB | Description |
|-------------|--------------|---------|--------|-----------|----------|---------------|-------------|
| CR2032-BS-6-1 | Q&J  | 2 Pin SMT | ✅ | ✅ | ✅ | ✅ | CR2032 Battery Holder |
| F1015WR-S-08PNLNG1T01L | HR(Joint Tech Elec) | SMD,P=1mm,Surface Mount，Right Angle | ✅ | ✅ | ✅ | ✅ | 8_Pin_FFC |
| HY09-4TBE | HYDZ | DIP | ✅ | ✅ | ✅ | ✅ | Through-Hole DIP Buzzer |
| TS-1010GS-BR09526 | XUNPU | SMD-4P,6.2x6.2mm | ✅ | ✅ | ✅ | ✅ | IP67 Tactile Switches|
| CY75-68UH | SHOU HAN | SMD,7.8x7mm | ✅ | ✅ | ✅ | ✅ | 68uH Inductor|
| LCM0820A2908F | LEADER | ✅ | ✅ | ✅ | ✅ | Adhesive Mount | 15000rpm 3V 7mm 80mA DC Vibration Motor |


---

## Usage

### KiCad
1. Clone or download this repo
2. In KiCad, go to **Preferences → Manage Symbol Libraries** and add `symbols/mylib.kicad_sym`
3. Go to **Preferences → Manage Footprint Libraries** and add `footprints/mylib.pretty`
4. 3D models will resolve automatically if the repo is cloned to the path 
   referenced in each footprint

### Other EDA Tools
STEP models in `3d-models/` are AP214 format and import directly into:
- Altium Designer
- Autodesk EAGLE
- EasyEDA / JLCPCB EDA
- DipTrace
- SolidWorks
- Autodesk Fusion
- Onshape
- FreeCAD

---

## Standards
- Footprints follow IPC-7351 land pattern standards where applicable
- All dimensions verified against manufacturer datasheets
- STEP models are AP214 format

---

## Contributing
Found an error or want to add a part? Open an issue or submit a PR. 
Include the datasheet you used as a reference.

---

## License
MIT — use freely in personal and commercial projects.

---

## Disclaimer
Not affiliated with or endorsed by any component manufacturer. 
Verify all footprints against your manufacturer's datasheet before 
sending to fabrication.
