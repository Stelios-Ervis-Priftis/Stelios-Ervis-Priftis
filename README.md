# Stelios-Ervis Priftis

**GIS Developer — Earth observation & geospatial web applications**
📍 Ljubljana, Slovenia · Working remotely with international teams

I build user-facing platforms for satellite and geospatial data. I spent two years on the team behind the **Copernicus Data Space Ecosystem Browser** and **EO Browser** at Sinergise (later Planet Labs), and most recently delivered **ZAGreen**, a web-GIS platform for green-roof prioritization funded by the City of Zagreb. My toolkit combines front-end development (Angular, React, TypeScript) with Python-based geospatial analysis (QGIS, GeoPandas, Rasterio) — and more recently, drone photogrammetry.

[LinkedIn](https://www.linkedin.com/in/ervispriftis) · [Portfolio](https://sep-gis-portfolio.netlify.app/#top)

---

## Featured projects

### 🌱 [ZAGreen](https://zagreen.listlabs.net/) — Green-roof prioritization for Zagreb
*LIST LABS d.o.o. · City of Zagreb 2025 open-data grant · 2026–ongoing*

Interactive web-GIS application that maps and ranks green-roof candidates across the City of Zagreb to support urban heat-island mitigation.

- Five-phase Python analysis pipeline (GeoPandas, Rasterio, rioxarray, NumPy) implementing a custom unvegetated index, applied to **11,477 landuse zones**, buffer zones around **132,167 buildings**, and a **70,855 flat-roof dataset** from aerial LiDAR
- NDVI composited from peak heat-stress Sentinel-2 imagery (June–August 2025), exported as Cloud-Optimized GeoTIFF and served via GeoServer WMS; vector data via PMTiles
- Bilingual HR/EN viewer (**React 19, TypeScript, OpenLayers 10, Zustand, Tailwind**) with 10 map layers — NDVI, priority-ranked roofs, landuse, trees, live air quality, and a Destination Earth climate model — with Jenks natural-breaks classification into five priority tiers

### 🔥 [Ember Lens](https://ember-lens.netlify.app/) — European wildfire visualization
*Personal project · 2024–ongoing · Angular 19, ngx-maplibre-gl, PrimeNG*

Web map for visualising wildfire incidents across **Europe, 2018–2025**, based on EFFIS fire perimeters and hotspots. → [Jump straight into an incident analysis](https://ember-lens.netlify.app/?mode=analysis&selectedEventId=213578&center=23.31895351409912,38.87002171064155)

- Interactive heatmap with time-range filtering; point intensity scaled by burned area (200–10,000+ ha)
- Per-incident view: fire boundary polygons, incident details, **3D terrain with hillshade**, and pre-/post-fire **Sentinel-2 imagery** (L1C/L2A via Sentinel Hub / Copernicus Data Space) with a before–after compare slider
- True-colour, false-colour infrared, and NDVI composites for inspecting burn-scar footprints
- Shareable event URLs that restore the exact incident and application state

### 🛩️ Tolmin Parcel — Drone survey & GIS mapping
*Independent pro bono project · 2026–ongoing · DJI Mini 2, Litchi, WebODM, QGIS*

Drone survey and GIS digitisation of a residential property (~770 m²) in Tolmin, Slovenia, delivering a measurable digital base map for the owners.

- Automated Litchi area-mapping mission; **106 nadir images** processed in WebODM into a **sub-centimetre orthophoto (0.85 cm GSD)** and a 3D model
- Georeferenced in QGIS against the official **GURS national orthophoto** into the Slovene National Grid (**EPSG:3794, D96/TM**)
- Multi-layer GeoPackage data model (property boundary, land-use zones, structures) with auto-calculated areas, standardised attribute forms, and all parcel features digitised

---

## Experience

| Period    | Role                                                                                                 | Where                                                |
| --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| 2026–now  | Drone Mapping & GIS Developer — independent project (pro bono)                                       | Private homeowner, Tolmin                            |
| 2026–now  | GIS Developer — [ZAGreen](https://zagreen.listlabs.net/) and upcoming projects                       | LIST LABS d.o.o., Zagreb (remote)                    |
| 2024–now  | Independent GIS Developer — professional development & [Ember Lens](https://ember-lens.netlify.app/) | Self-directed, Ljubljana                             |
| 2022–2024 | Front-End Developer — Copernicus Data Space Ecosystem Browser & EO Browser                           | Sinergise (acquired by Planet Labs, 2023), Ljubljana |
| 2021–2022 | Front-End Developer — CONTROL-PRO food-safety SaaS (Corvium Inc.)                                    | Valmore Technologies, Athens                         |

## Tech stack

- **Front-end:** TypeScript, JavaScript, Angular, React, Zustand, Tailwind, PrimeNG
- **Web mapping:** OpenLayers, MapLibre GL
- **Geospatial:** QGIS, GeoPandas, Rasterio, rioxarray, NumPy, GDAL, remote sensing (Sentinel-2, NDVI), cartography
- **Drone & photogrammetry:** DJI Mini 2, Litchi mission planning, WebODM/ODX, aerial photography, georeferencing
- **Data serving & infra:** PMTiles, Cloud-Optimized GeoTIFF, GeoServer (WMS), Sentinel Hub APIs, Hetzner Object Storage, REST APIs, Git

## Education

- **Web Development Immersive** — General Assembly, London (2016, 420 hours)
- **Vocational Training Certificate — Sound Technician** — I.E.K. AKMI, Athens (EQF 4)
- **Vocational Upper-Secondary Diploma — Electrical Installations** — 1st EPAL Athens (EQF 4)

## Beyond the code

Greek mother tongue, English C1 listening / B2 working proficiency. Before software: sound engineering. Off-screen: windsurfing, snowboarding, cocktail mixology, Thai boxing.
