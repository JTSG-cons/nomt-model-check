# НОМТ Model Check

Review page for the НОМТ tower 3D model and walkthrough. It shows how the model's windows and doors were checked against the architect's drawing set (`Номт хэвлэх 2-11 БА.pdf`) and the Revit DWG export.

## What's on the page
- **Walkthrough video:** currently the 2:25 preview cut (`walkthrough.mp4`).
- **Overlays:** the model drawn over the original sheets (plan p11, east elevation p17).
- **Windows and doors per flat (A–H):** cross-checked across the plan, the elevations and the DWG (346 + 38 automated checks).
- **Drawing discrepancies to raise with the architect:** for example, the Ц-2 window is 1400 mm high in its detail drawing but 1500 mm in the p19 schedule table.
- **Interactive 3D:** the furnished typical floor (floors 9–15), shown with `<model-viewer>` (`typical-floor.json`, an embedded glTF).
- **Stills:** from each shot.

## View it
Open `index.html` through any static server, for example `python -m http.server`, or turn on GitHub Pages (Settings → Pages → branch `main`, root). Opening it straight from disk as a `file://` page may block the 3D model from loading.

All renders are artist's impressions (Зураглал). Furniture follows the architect's DWG layout.
