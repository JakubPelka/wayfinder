# JakubPelka — GitHub Wayfinder

A compact guide to my public GitHub repositories.

This repository is not a portfolio page in the strict sense. It is a practical navigation map: what each repository is for, what its current status is, and what should be cleaned, maintained, developed, paused, or treated carefully.

Last reviewed: 2026-05-18.

The column `Last visible update` refers to the public `Updated` date visible on GitHub or to the latest significant manual repository work noted during cleanup. It is not a full commit history audit.

## Status legend

| Status | Meaning |
|---|---|
| ACTIVE | Actively developed or planned for further development. |
| TESTING | Usable development version under practical testing; feedback should become issues or small follow-up commits. |
| MAINTAINED | Works and may receive fixes, but no major rebuild is planned. |
| PAUSED | A useful milestone has been reached. No active development is planned, except possible bug fixes or small updates. |
| HOWTO | Instruction/manual repository. The main value is documentation, workflow explanation, or reproducible steps rather than application code. |
| IDEA | Concept repository. The idea is documented, but implementation is not currently started or prioritized. |
| EXPERIMENT | Prototype, proof of concept, development test, or idea under exploration. |
| SHOWCASE | Demo or portfolio-style repository intended to show an idea or capability. |
| TEMP PUBLIC | Public temporarily, mainly for joint cleanup, review, or development. |
| PRIVATE? | Consider making private again or keeping the public description intentionally limited. |
| ARCHIVED | Kept as a historical trace, with no planned development. |

## Repositories — active, experimental, or still requiring attention

| Repository | Short description | Status | Last visible update | Notes / next step |
|---|---|---|---|---|
| [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video) | Desktop video-analysis application for counting detected objects in recordings or streams using YOLO, with counters, zones, line crossings, alerts, snapshots, heatmaps, HUD overlays, zone dwell time, class peak statistics, and structured CSV outputs. | ACTIVE / TESTING | 2026-05-18 | Latest release: `v0.1.2 – Zone dwell time and class peak statistics`. Repository cleanup and code organization baseline completed. The application is ready for practical testing, but development continues. Next work should be issue-based: test runs, bug fixes, UX polish, output validation, release packaging, and later tracking/segmentation/heatmap improvements. |
| [Artportalen_med_data](https://github.com/JakubPelka/Artportalen_med_data) | Enriching Artportalen / AGOL-derived records with protection-status information and additional columns. | TEMP PUBLIC / PRIVATE? | 2026-05-13 | Sensitive topic. Keep documentation careful: no real data, no tokens, no endpoints, no unnecessary operational context. |
| [hajk-gesture-demo](https://github.com/JakubPelka/hajk-gesture-demo) | Demo for controlling a Hajk / OpenLayers map with hand gestures using MediaPipe and OpenCV. | EXPERIMENT / SHOWCASE | 2026-05-08 | Good showcase candidate. Add GIF/video, gesture list, architecture notes, and known limitations. |
| [Sculptor_QGIS](https://github.com/JakubPelka/Sculptor_QGIS) | Experiment with terrain modelling / sculpting in QGIS, inspired by Blender-style sculpting workflows. | EXPERIMENT | 2026-05-07 | Clean up MVP versions, ZIPs, plugin structure, and clearly label it as experimental. |
| [ComputerVisionCounter_Images](https://github.com/JakubPelka/ComputerVisionCounter_Images) | Object counting in images using YOLO models; image-based version with a cleaner code structure. | ACTIVE / MAINTAINED | 2025-10-14 | Strong product and portfolio potential. Keep models outside the repository, ignore outputs, and improve end-user README. |
| [MobileComputerVisionCounter](https://github.com/JakubPelka/MobileComputerVisionCounter) | Idea / prototype for a mobile object-counting application using YOLO and iPhone. | EXPERIMENT | 2025-10-04 | Keep as proof of concept. Add clear scope, status, and decision whether it should be developed further. |
| [Excel2Word_with_presets](https://github.com/JakubPelka/Excel2Word_with_presets) | Tkinter/Python tool for converting Excel rows into Word micro-tables using JSON presets, editable field mapping, layouts, photo/map placeholders, sorting, styling, margins, and image handling. | MAINTAINED / TESTING | 2026-05-16 | Repository has been significantly cleaned and organized after recent work. No release yet. Current focus: practical testing before first release, checking presets, GUI behaviour, DOCX output, photo handling, sample-data safety, and whether the Polish README should later be translated or left as-is. |
| [LaczTabeleNietoperzy](https://github.com/JakubPelka/LaczTabeleNietoperzy) | Combining tables from Autoboxes and generating summary and daily charts. | TEMP PUBLIC / PRIVATE? | 2025-09-24 | Sensitive topic. Keep a neutral description and avoid location data, real recordings, or unnecessary biological detail. |
| [Drone2Place](https://github.com/JakubPelka/Drone2Place) | Early idea for identifying places from drone photos and locating them on a map. | EXPERIMENT | 2025-09-22 | Add a short README with purpose, limitations, and possible direction. |
| [Osm-field-tagger-AI](https://github.com/JakubPelka/Osm-field-tagger-AI) | Idea for a mobile, human-verified OpenStreetMap field survey assistant: geolocation, photo, local AI tag suggestions, user verification, and OSM-ready tags. | IDEA / EXPERIMENT | 2026-05-16 | Idea only for now. Prepare later after higher-priority repository cleanup. Keep the first PoC small: local/on-device first, no automatic uploads, human verification required. |
| [FusionCover](https://github.com/JakubPelka/FusionCover) | Scripts for calculating terrain or vegetation cover from LAS files using FUSION. | EXPERIMENT / PRIVATE? | 2025-08-29 | Verify public suitability. Clean input/output description and check whether the repository should remain public. |
| [FixaDataAutoboxar](https://github.com/JakubPelka/FixaDataAutoboxar) | Automatic extraction of metadata from WAV files and export to a readable Excel sheet. | MAINTAINED / TEMP PUBLIC | 2025-08-29 | Practical tool, but related to recording-derived data. Be careful with examples and public wording. |
| [BlenderDigitalTwin](https://github.com/JakubPelka/BlenderDigitalTwin) | Blender Digital Twin add-on / concept: reconstructing and visualising scenes from GIS data. | ACTIVE / EXPERIMENT | 2025-08-22 | Very strong long-term potential. First clean the add-on structure, MVP scope, and repository hygiene. |

## Documentation / HOWTO repositories

These repositories are mainly manuals, guides, notes, or reproducible workflows. They may contain helper scripts, but the primary value is the documentation rather than a maintained application.

| Repository | Short description | Status | Last visible update | Notes / next step |
|---|---|---|---|---|
| [jak-wytresowac-model-pt](https://github.com/JakubPelka/jak-wytresowac-model-pt) | Polish HOWTO for training a custom YOLO `.pt` model from a Roboflow dataset, with Linux and Windows paths, PyTorch/CUDA setup, dataset preparation, safety notes, smoke tests, training commands, and helper scripts. | HOWTO / MAINTAINED | 2026-05-18 | Manual-style repository, not an application project. No release needed unless the guide becomes stable enough to tag as `v0.1.0`. Keep datasets, Roboflow API links, trained `.pt` files, `runs/`, temporary ZIPs, and private data outside the repository. |

## Repositories — milestone reached

These repositories have reached a useful public milestone. They are not abandoned. They are kept in `MAINTAINED / PAUSED` mode: usable, documented, released, and only expected to receive fixes or small improvements if needed.

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Short description</th>
      <th>Status</th>
      <th>Last visible update</th>
      <th>Notes / next step</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td bgcolor="#edf7ed"><a href="https://github.com/JakubPelka/skyddstrad-field-reporter">skyddstrad-field-reporter</a></td>
      <td bgcolor="#edf7ed">Mobile-first PWA / field helper for recording potential särskilt skyddsvärda träd, checking existing public tree records, saving local browser drafts, and exporting XLSX/GeoJSON for later review/import into Artportalen.</td>
      <td bgcolor="#edf7ed"><strong>MAINTAINED / PAUSED</strong></td>
      <td bgcolor="#edf7ed">2026-05-18</td>
      <td bgcolor="#edf7ed">Release <code>v0.1.0 – Proof of Concept</code> published and GitHub Pages app available. Current README status: Early proof of concept. No active development planned right now; return for Artportalen import testing, improved Lokalnamn handling, optional aerial imagery/orthophoto background, desktop layout, or clearer QA/export summary.</td>
    </tr>
    <tr>
      <td bgcolor="#edf7ed"><a href="https://github.com/JakubPelka/MergeExcelFiles">MergeExcelFiles</a></td>
      <td bgcolor="#edf7ed">Small Tkinter/Python tool for merging multiple Excel files with the same structure into one combined workbook, with optional CSV export. Originally used for tree-related Artportalen-style Excel data, but potentially reusable for other similarly structured Excel files.</td>
      <td bgcolor="#edf7ed"><strong>MAINTAINED / PAUSED</strong></td>
      <td bgcolor="#edf7ed">2026-05-15</td>
      <td bgcolor="#edf7ed">Release <code>v0.1.0</code> published. Repository cleaned and structured with English README, <code>src/</code>, <code>run_gui.py</code>, <code>requirements.txt</code>, <code>.gitignore</code>, <code>.gitattributes</code>, and MIT LICENSE. No active development planned; return only for bug fixes, packaging, or if the tool should become more generic.</td>
    </tr>
    <tr>
      <td bgcolor="#edf7ed"><a href="https://github.com/JakubPelka/ROI_raster_histogram_QGIS">ROI_raster_histogram_QGIS</a></td>
      <td bgcolor="#edf7ed">QGIS plugin for calculating raster class statistics inside ROI polygons, with tables, charts, HTML export, and optional percentage fields written back to the ROI layer.</td>
      <td bgcolor="#edf7ed"><strong>MAINTAINED / PAUSED</strong></td>
      <td bgcolor="#edf7ed">2026-05-15</td>
      <td bgcolor="#edf7ed">Release <code>v0.1.0</code> published. Plugin works and installs from the prepared ZIP package. Return only for bug fixes, UI improvements, new export needs, or later refactoring.</td>
    </tr>
    <tr>
      <td bgcolor="#edf7ed"><a href="https://github.com/JakubPelka/Exif_lat_lon">Exif_lat_lon</a></td>
      <td bgcolor="#edf7ed">Tool for reading GPS coordinates from image metadata and exporting them to CSV and GeoJSON.</td>
      <td bgcolor="#edf7ed"><strong>MAINTAINED / PAUSED</strong></td>
      <td bgcolor="#edf7ed">2026-05-15</td>
      <td bgcolor="#edf7ed">Release <code>v0.1.0</code> published. Repository cleaned, tested, and left as-is for now. Return only for bugs, new input formats, or packaging needs.</td>
    </tr>
  </tbody>
</table>

## Private or intentionally limited repositories

This section is for repositories that are private, temporarily private, or intentionally kept with limited public exposure.

Links may work only for me or for people with repository access. This is intentional. The goal is to keep a lightweight index of important repositories without exposing unnecessary details to the public.

| Repository | Short description | Status | Last visible update | Notes / next step |
|---|---|---|---|---|
| _None listed yet_ | Repositories will be moved here after cleanup and visibility review. | — | — | Example future candidate: `FixaDataAutoboxar`, after hygiene cleanup and possible move to private. |

### Rule for moving repositories here

Move a repository to this section when:

- it is useful to keep in the wayfinder,
- it should no longer be promoted as a public project,
- it contains or relates to sensitive, semi-internal, biological, recording-derived, or operational workflows,
- the public repository would expose more context than needed,
- or the repository is kept public only temporarily during cleanup.

When a repository is moved here, remove it from the main public table unless it still needs to be visible as a public showcase or public tool.

## Cleanup priority

1. [BlenderDigitalTwin](https://github.com/JakubPelka/BlenderDigitalTwin) — add-on structure, working folders, builds, and MVP scope.
2. [Sculptor_QGIS](https://github.com/JakubPelka/Sculptor_QGIS) — MVP versions, ZIPs, and plugin structure.
3. [ComputerVisionCounter_Images](https://github.com/JakubPelka/ComputerVisionCounter_Images) — product structure, models outside repo, output handling, and user README.
4. [Artportalen_med_data](https://github.com/JakubPelka/Artportalen_med_data) — cautious documentation, safe test data, and clear dev/prod split.
5. [LaczTabeleNietoperzy](https://github.com/JakubPelka/LaczTabeleNietoperzy) / [FixaDataAutoboxar](https://github.com/JakubPelka/FixaDataAutoboxar) — privacy, neutral README wording, and no sensitive data.

## Post-cleanup testing / follow-up

- [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video) — cleanup baseline and release `v0.1.2` completed. It is no longer a top cleanup priority. Current focus: practical testing, output validation, bug reports as issues, small fixes, UX polish, and further feature development.
- [Excel2Word_with_presets](https://github.com/JakubPelka/Excel2Word_with_presets) — repository has been significantly cleaned, but no release has been published yet. Current focus: practical testing, preset validation, DOCX output checks, photo/map placeholder behaviour, and preparing a possible first release after successful tests.

## Development priority

1. [ComputerVisionCounter_Images](https://github.com/JakubPelka/ComputerVisionCounter_Images) — strong product and portfolio potential.
2. [hajk-gesture-demo](https://github.com/JakubPelka/hajk-gesture-demo) — effective AI + GIS showcase.
3. [Artportalen_med_data](https://github.com/JakubPelka/Artportalen_med_data) — high practical value, but public wording must stay cautious.
4. [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video) — major potential; current baseline is `v0.1.2`, now continue through practical testing, bug fixes, UX polish, output validation, and future tracking/segmentation experiments.
5. [BlenderDigitalTwin](https://github.com/JakubPelka/BlenderDigitalTwin) — largest long-term potential, but requires strict architecture discipline.
6. [Osm-field-tagger-AI](https://github.com/JakubPelka/Osm-field-tagger-AI) — promising AI + OSM mobile idea; prepare after current cleanup backlog.

## Milestones already reached

- [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video) — active development baseline reached with latest release `v0.1.2`; project remains in `ACTIVE / TESTING`.
- [ROI_raster_histogram_QGIS](https://github.com/JakubPelka/ROI_raster_histogram_QGIS) — first public release completed: `v0.1.0`.
- [Exif_lat_lon](https://github.com/JakubPelka/Exif_lat_lon) — first public release completed: `v0.1.0`.
- [MergeExcelFiles](https://github.com/JakubPelka/MergeExcelFiles) — first cleaned release completed: `v0.1.0`.
- [skyddstrad-field-reporter](https://github.com/JakubPelka/skyddstrad-field-reporter) — first proof-of-concept release completed: `v0.1.0`.

## Repository work rules

- One repository at a time.
- One goal at a time.
- Small commits.
- Security and repository hygiene first.
- Then README, structure, documentation, and roadmap.
- New features only after the repository is clean enough to safely continue.
- GitHub repositories are for source code, documentation, collaboration, and releases — not for backups or working-disk storage.

## Minimum checklist for each repository

- `README.md` exists and clearly explains the purpose of the project.
- `LICENSE` exists, or its absence is intentional.
- `.gitignore` blocks secrets, outputs, cache, archives, local temporary files, and AI models where relevant.
- No tokens, API keys, passwords, `.env` files, or private credentials.
- No private or real test data unless there is a deliberate and safe reason.
- No backup ZIPs or old working folders.
- Folder structure is logical.
- It is possible to understand how to run or use the project.
- Repository status is clear.

## Notes on public visibility

Not every repository needs to be promoted as a portfolio project.

Some repositories may stay public only temporarily while they are cleaned or reviewed. Sensitive or semi-internal topics should use neutral wording, minimal context, and safe sample data. Repositories related to protected species, recordings, municipal workflows, API endpoints, or operational data should be treated especially carefully.
