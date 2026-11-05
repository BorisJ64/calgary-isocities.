CALGARY IN MINIATURE — ISOCITIES PROJECT

WHAT THIS IS
A static, interactive isometric city map for central Calgary, styled as a miniature city atlas. It uses your uploaded OpenStreetMap building and place footprints.

COVERAGE
Eau Claire, downtown core, East Village, Beltline and Stampede Park. The supplied central dataset is filtered from your original Calgary export.

FILES
- index.html: the map application
- data/calgary-central.geojson: central Calgary building/place geometry
- data/landmarks.json: named landmark jump points

RUN LOCALLY
Open index.html using a local static server (recommended), because the page fetches the GeoJSON from ./data. You can use VS Code Live Server, or upload the whole folder to Cloudflare Pages.

PUBLISH WITH CLOUDFLARE PAGES
1. Sign in to Cloudflare Dashboard.
2. Open Workers & Pages → Create application → Pages → Upload assets (Direct Upload).
3. Upload the contents of this folder, keeping the data folder beside index.html.
4. Deploy. Cloudflare will provide a *.pages.dev URL.

DATA & ATTRIBUTION
Building and place data derived from the uploaded OpenStreetMap Overpass export. © OpenStreetMap contributors, licensed under the Open Database License (ODbL). Basemap tiles are served by OpenStreetMap tile servers and require an internet connection. Building heights use mapped height/levels tags where present; missing heights are visually estimated for display and should not be treated as surveyed measurements.

ISOCITIES SUBMISSION
The directory currently states that maker submissions open when the directory launches. This project is prepared as a standalone map website and listing draft, but it has not been submitted or added to the directory.

SUGGESTED LISTING
City: Calgary
Country: Canada
Map title: Calgary in Miniature
Maker: [your preferred public name]
Description: An interactive isometric map of central Calgary, from Eau Claire and the downtown towers to East Village, the Beltline and Stampede Park. Built from OpenStreetMap footprints with an illustrated 3D treatment.
Technique: 3D scene / drawn in code
Base data: Open data (OpenStreetMap)
