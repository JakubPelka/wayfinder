# JakubPelka — GitHub Wayfinder

A compact guide to my public GitHub repositories.

This repository is not a portfolio page in the strict sense. It is a practical navigation map: what each repository is for, what its current status is, and what should be cleaned, maintained, developed, tested, paused, or treated carefully.

Last reviewed: 2026-07-20.

The column `Last visible update` refers to the public `Updated` date visible on GitHub or to the latest significant manual repository work noted during cleanup. It is not a full commit history audit.

Current scan: 36 repositories visible through the connected GitHub account,
including public, private and archived repositories. Local checkouts were also
reviewed; upstream Hajk and the duplicate local BlenderDT working tree are not
counted as separate JakubPelka account repositories.

## Status legend

| Status      | Meaning                                                                                                                                                       |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ACTIVE      | Actively developed or planned for further development.                                                                                                        |
| TESTING     | Usable development version under practical testing; feedback should become issues or small follow-up commits.                                                 |
| MAINTAINED  | Works and may receive fixes, but no major rebuild is planned.                                                                                                 |
| PAUSED      | A useful milestone has been reached. No active development is planned, except possible bug fixes or small updates.                                            |
| HOWTO       | Instruction/manual repository. The main value is documentation, workflow explanation, or reproducible steps rather than application code.                     |
| IDEA        | Concept repository. The idea is documented, but implementation is not currently started or prioritized.                                                       |
| IDEA BANK   | Repository used as a parking place for ideas, concepts, future directions, and topics waiting for validation. Not every idea is expected to become a project. |
| EXPERIMENT  | Prototype, proof of concept, development test, or idea under exploration.                                                                                     |
| SHOWCASE    | Demo or portfolio-style repository intended to show an idea or capability.                                                                                    |
| META        | Repository used to manage, document, or navigate other repositories.                                                                                          |
| TEMP PUBLIC | Public temporarily, mainly for joint cleanup, review, or development.                                                                                         |
| PRIVATE?    | Consider making private again or keeping the public description intentionally limited.                                                                        |
| ARCHIVED    | Kept as a historical trace, with no planned development.                                                                                                      |

## Repositories — active, experimental, or still requiring attention

| Repository                                                                                 | Short description                                                                                                                                                                                                                                                                                             | Status                          | Last visible update | Notes / next step                                                                                                                                                                                                                                                                                           |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------- | ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video)   | Desktop video-analysis application for counting detected objects in recordings or streams using YOLO, with counters, zones, line crossings, alerts, snapshots, heatmaps, HUD overlays, zone dwell time, class peak statistics, annotated video export, incremental event writing, and structured CSV outputs. | ACTIVE / TESTING                | 2026-07-10          | Latest release baseline: `v0.1.2`. The current feature branch adds configurable streaming tracking, inference benchmarking, optional OpenVINO/TensorRT export helpers, backend notes and CLI/geometry tests. Continue practical validation before choosing which experiments belong on `main`.              |
| [Mnemosyne](https://github.com/JakubPelka/Mnemosyne)                                       | Local-first, private atlas of ChatGPT conversations and future personal sources, with SQLite/FTS5, a shared event model, topic/term graphs, FastAPI and a React/Sigma visual interface.                                                                                                                       | ACTIVE / TEMP PUBLIC            | 2026-07-19          | Visual MVP is stable on `main`. The local branch `feat/local-llm-semantic-tagger` develops an auditable, resumable semantic-tagging pipeline for a local Ollama model. Keep exports, databases, indexes, sidecars and logs outside Git and audit privacy before every push.                                 |
| [CognitiveOperatingSystem-COS](https://github.com/JakubPelka/CognitiveOperatingSystem-COS) | Private parent repository for a portable personal architecture of knowledge, attention, projects, decisions, agents and reproducible environments.                                                                                                                                                            | ACTIVE / PRIVATE                | 2026-07-15          | Sprint 0 is initialized and a deterministic journal builder is present. Treat this as the canonical implementation repository; continue with small, documented and reversible automation steps.                                                                                                             |
| [GeoKombajn](https://github.com/JakubPelka/GeoKombajn)                                     | Experimental AOI-driven GIS orchestration concept combining GDAL/OGR, SAGA, GWB, QGIS/HNAT, Julia/Omniscape and data preparation into repeatable project packages.                                                                                                                                            | ACTIVE / EXPERIMENT             | 2026-07-17          | A working QGIS-console experiment now discovers regional Lantmateriet `mhm-*` STAC collections and downloads NMT GeoTIFF / optional COPC data with interactive credentials. Convert it into a bounded module only after testing and credential/output hardening.                                            |
| [GTB_connectivity](https://github.com/JakubPelka/GTB_connectivity)                         | QGIS/GuidosToolbox workflow for landscape connectivity analysis based on GTB Proximity outputs, with an experimental QGIS Processing plugin under `DEV/qgis_plugin/`.                                                                                                                                         | ACTIVE / EXPERIMENT / TESTING   | 2026-05-24          | Current focus is validating the QGIS Processing plugin workflow. Keep GTB/GWB execution outside scope for now; clean plugin structure, docs, sample-data policy, and output handling before any public release.                                                                                             |
| [BlenderDigitalTwin](https://github.com/JakubPelka/BlenderDigitalTwin)                     | Blender Digital Twin add-on / concept: reconstructing and visualising scenes from GIS data.                                                                                                                                                                                                                   | ACTIVE / EXPERIMENT             | 2025-08-22          | Very strong long-term potential. First clean the add-on structure, MVP scope, and repository hygiene.                                                                                                                                                                                                       |
| [Sculptor_QGIS](https://github.com/JakubPelka/Sculptor_QGIS)                               | Experimental QGIS terrain-sculpting plugin with raise/lower, smooth, level, cut/fill and vector-alignment tools for local GDAL rasters.                                                                                                                                                                       | ACTIVE / EXPERIMENT             | 2026-07-17          | Development ZIP iterations now extend through `v0.2.8`, with background-worker processing. Consolidate packages, verify metadata/versioning, test on raster copies and prepare one clearly identified release candidate.                                                                                    |
| [Artportalen_med_data](https://github.com/JakubPelka/Artportalen_med_data)                 | Enriching Artportalen / AGOL-derived records with protection-status information and additional columns.                                                                                                                                                                                                       | TEMP PUBLIC / PRIVATE?          | 2026-05-13          | Sensitive topic. Keep documentation careful: no real data, no tokens, no endpoints, no unnecessary operational context.                                                                                                                                                                                     |
| [hajk-gesture-demo](https://github.com/JakubPelka/hajk-gesture-demo)                       | Demo for controlling a Hajk / OpenLayers map with hand gestures using MediaPipe and OpenCV.                                                                                                                                                                                                                   | EXPERIMENT / SHOWCASE           | 2026-05-08          | Good showcase candidate. Add GIF/video, gesture list, architecture notes, and known limitations.                                                                                                                                                                                                            |
| [Excel2Word_with_presets](https://github.com/JakubPelka/Excel2Word_with_presets)           | Tkinter/Python tool for converting Excel rows into Word micro-tables using JSON presets, editable field mapping, layouts, photo/map placeholders, sorting, styling, margins, and image handling.                                                                                                              | MAINTAINED / TESTING            | 2026-05-16          | Repository has been significantly cleaned and organized after recent work. No release yet. Current focus: practical testing before first release, checking presets, GUI behaviour, DOCX output, photo handling, sample-data safety, and whether the Polish README should later be translated or left as-is. |
| [MobileComputerVisionCounter](https://github.com/JakubPelka/MobileComputerVisionCounter)   | Idea / prototype for a mobile object-counting application using YOLO and iPhone.                                                                                                                                                                                                                              | IDEA                            | 2025-10-04          | Keep as proof of concept. Add clear scope, status, and decision whether it should be developed further.                                                                                                                                                                                                     |
| [LaczTabeleNietoperzy](https://github.com/JakubPelka/LaczTabeleNietoperzy)                 | Combining Autobox Excel tables, generating summaries/charts, and comparing multiple sources in the new standalone Parallel Bat Graph HTML application.                                                                                                                                                        | ACTIVE / TEMP PUBLIC / PRIVATE? | 2026-07-17          | The original Tkinter workflow remains, while `parallel-graph/` adds multilingual filters, synchronized data tables, time navigation and PNG/CSV/report export. Continue testing with synthetic data and keep locations and real recordings out of Git.                                                      |
| [przepisy](https://github.com/JakubPelka/przepisy)                                         | Small recipe application/site based on an earlier diet, extended with estimated calories and an editing panel.                                                                                                                                                                                                | ACTIVE / PERSONAL               | 2026-07-15          | Working web application with a published project URL. Review whether the tracked database is deliberately public and keep personal meal or health data out of examples.                                                                                                                                     |
| [Cesium_Sandbox](https://github.com/JakubPelka/Cesium_Sandbox)                             | CesiumJS sandbox for 3D Tiles, GeoJSON, photos and map-display experiments.                                                                                                                                                                                                                                   | EXPERIMENT / SHOWCASE           | 2026-06-25          | Cleaned baseline with an updated README. Keep it as a bounded sandbox; replace or remove any sample assets that should not be redistributed.                                                                                                                                                                |
| [Drone2Place](https://github.com/JakubPelka/Drone2Place)                                   | Early idea for identifying places from drone photos and locating them on a map.                                                                                                                                                                                                                               | EXPERIMENT                      | 2025-09-22          | Add a short README with purpose, limitations, and possible direction.                                                                                                                                                                                                                                       |
| [FusionCover](https://github.com/JakubPelka/FusionCover)                                   | Scripts for calculating terrain or vegetation cover from LAS files using FUSION.                                                                                                                                                                                                                              | EXPERIMENT / PRIVATE?           | 2025-08-29          | Verify public suitability. Clean input/output description and check whether the repository should remain public.                                                                                                                                                                                            |
| [FixaDataAutoboxar](https://github.com/JakubPelka/FixaDataAutoboxar)                       | Automatic extraction of metadata from WAV files and export to a readable Excel sheet.                                                                                                                                                                                                                         | MAINTAINED / TEMP PUBLIC        | 2025-08-29          | Practical tool, but related to recording-derived data. Be careful with examples and public wording. Candidate for private visibility after cleanup.                                                                                                                                                         |
| [Osm-field-tagger-AI](https://github.com/JakubPelka/Osm-field-tagger-AI)                   | Idea for a mobile, human-verified OpenStreetMap field survey assistant: geolocation, photo, local AI tag suggestions, user verification, and OSM-ready tags.                                                                                                                                                  | IDEA / EXPERIMENT               | 2026-05-16          | Idea only for now. Prepare later after higher-priority repository cleanup. Keep the first PoC small: local/on-device first, no automatic uploads, human verification required.                                                                                                                              |

## Idea bank / concept repositories

These repositories collect ideas, early concepts, future directions, and topics waiting for validation. They are not implementation commitments. Some ideas may later become separate repositories, issues, prototypes, or roadmap items; others may stay as notes only.

| Repository | Short description | Status | Last visible update | Notes / next step |
|---|---|---|---|---|
| [ideas](https://github.com/JakubPelka/ideas) | Bank of ideas and future concepts: promising, experimental, unfinished, or speculative thoughts waiting for discussion, validation, prioritisation, or later prototyping. | IDEA BANK / MAINTAINED | 2026-05-21 | Use as a lightweight parking place for ideas from discussions and personal notes. Keep entries short, clearly labelled, and separate from active project documentation. Do not treat listed ideas as committed roadmap items unless they are later moved into a specific project repository or issue. |
| [cos](https://github.com/JakubPelka/cos) | Original concept document for a Cognitive Operating System joining project memory, knowledge, attention, context and carefully supervised automation. | IDEA / PRIVATE | 2026-07-12 | Preserve as the conceptual predecessor or explicitly redirect it to `CognitiveOperatingSystem-COS`; avoid maintaining two competing implementation roadmaps. |

## Documentation / HOWTO repositories

These repositories are mainly manuals, guides, notes, or reproducible workflows. They may contain helper scripts, but the primary value is the documentation rather than a maintained application.

| Repository | Short description | Status | Last visible update | Notes / next step |
|---|---|---|---|---|
| [jak-wytresowac-model-pt](https://github.com/JakubPelka/jak-wytresowac-model-pt) | Polish HOWTO for training a custom YOLO `.pt` model from a Roboflow dataset, with Linux and Windows paths, PyTorch/CUDA setup, dataset preparation, safety notes, smoke tests, training commands, and helper scripts. | HOWTO / MAINTAINED | 2026-05-18 | Manual-style repository, not an application project. No release needed unless the guide becomes stable enough to tag as `v0.1.0`. Keep datasets, Roboflow API links, trained `.pt` files, `runs/`, temporary ZIPs, and private data outside the repository. |
| [Julia_Omniscape](https://github.com/JakubPelka/Julia_Omniscape) | Private HOWTO and working notes for ecological connectivity analysis with Julia/Omniscape and NMD/Topo50 preprocessing. | HOWTO / PRIVATE | 2026-06-15 | Keep project data and study-area details private; retain only reusable workflow documentation and safe parameter examples. |
| [LM_Hojddata_API_download](https://github.com/JakubPelka/LM_Hojddata_API_download) | Private notes/scripts for downloading Lantmateriet elevation tiles by grid or API workflow. | HOWTO / PRIVATE / REVIEW | 2025-08-29 | Verify against the newer STAC findings in GeoKombajn, remove obsolete authentication guidance and decide whether this should be consolidated or archived. |

## Meta / repository management repositories

These repositories exist mainly to organize, document, or navigate other work.

| Repository | Short description | Status | Last visible update | Notes / next step |
|---|---|---|---|---|
| [wayfinder](https://github.com/JakubPelka/wayfinder) | Navigation index for JakubPelka GitHub repositories: statuses, priorities, public/private notes, cleanup state, milestones, and future direction. | META / MAINTAINED | 2026-07-20 | Updated after the July repository audit, including Mnemosyne, both COS repositories and previously omitted private/archived projects. Keep it synchronized after releases, visibility changes and new repository creation. |

## Repositories — milestone reached

These repositories have reached a useful public milestone. Most are kept in
`MAINTAINED / PAUSED` mode; a project may return to active testing when a new
development cycle starts.

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
      <td bgcolor="#edf7ed"><a href="https://github.com/JakubPelka/CVC_Bats_Thermal_detection">CVC_Bats_Thermal_detection</a></td>
      <td bgcolor="#edf7ed">Thermal video blob detection and simple track filtering for bat monitoring, with GUI-first workflow, ROI/exclude zones, counting geometry, CSV/JSON statistics, and optional annotated video output.</td>
      <td bgcolor="#edf7ed"><strong>MAINTAINED / PAUSED</strong></td>
      <td bgcolor="#edf7ed">2026-07-20</td>
      <td bgcolor="#edf7ed">Release <code>v.0.2.1 – Small HUD improvements</code> completes the July development cycle: presets, configurable annotation styles, side-by-side verification, batch/automatic folder processing, recording timestamps and clearer event-clip HUD/export information. The project now returns to maintained/paused mode; resume for concrete bug fixes, validation needs or future CVC integration. Keep real recordings and outputs outside Git.</td>
    </tr>
    <tr>
      <td bgcolor="#edf7ed"><a href="https://github.com/JakubPelka/ComputerVisionCounter_Images">ComputerVisionCounter_Images</a></td>
      <td bgcolor="#edf7ed">Desktop application for counting objects in still images with local YOLO <code>.pt</code> models, class selection, optional AOI filtering, annotated image output, CSV/JSON exports, and GIS-friendly export paths where supported.</td>
      <td bgcolor="#edf7ed"><strong>MAINTAINED / PAUSED</strong></td>
      <td bgcolor="#edf7ed">2026-06-18</td>
      <td bgcolor="#edf7ed">First cleaned release <code>v0.2.0</code> completed. The project works for the current intended scope and is paused for now. Future changes may include bug fixes, packaging polish, stronger documentation, ONNX/segmentation experiments, or later alignment with the video/CVC family.</td>
    </tr>
    <tr>
      <td bgcolor="#edf7ed"><a href="https://github.com/JakubPelka/Whisper">Whisper</a></td>
      <td bgcolor="#edf7ed">Local audio transcription toolkit with one launcher and two clean backends: KB-Whisper for Swedish recordings and OpenAI Whisper for Polish, English, auto-detection and other languages.</td>
      <td bgcolor="#edf7ed"><strong>MAINTAINED / PAUSED</strong></td>
      <td bgcolor="#edf7ed">2026-07-13</td>
      <td bgcolor="#edf7ed">Release <code>v0.1.0</code> and a usable local workflow are complete. A systemd-style watcher can now transcribe new recordings automatically into source-adjacent output folders. Keep audio, transcripts, caches, environments and secrets outside Git; verify watcher configuration locally before enabling it.</td>
    </tr>
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
| [Hembygd_till_CSV](https://github.com/JakubPelka/Hembygd_till_CSV) | Private conversion experiment with a demo result. | PRIVATE / EXPERIMENT | 2026-03-31 | Add a neutral README and verify that the demo contains only redistributable synthetic or public data. |
| [SpotifyImportExport](https://github.com/JakubPelka/SpotifyImportExport) | Private scripts for Spotify playlist CSV import/export. | PRIVATE / MAINTAINED | 2025-08-29 | Review token handling, scopes and generated playlist data before any visibility change. |
| [AGOL_med_data](https://github.com/JakubPelka/AGOL_med_data) | Archived private predecessor for enriching AGOL-derived data with conservation information. | PRIVATE / ARCHIVED | 2025-09-18 | Keep archived; use Artportalen_med_data for any maintained successor workflow and never expose credentials or real operational data. |
| [FME_PREBAT](https://github.com/JakubPelka/FME_PREBAT) | Private development workflow for PREBAT/FME processing. | PRIVATE / EXPERIMENT | 2025-09-09 | Keep operational context and real data private; document only a safe, high-level run contract if work resumes. |
| [WykresyNietoperzy_legacy](https://github.com/JakubPelka/WykresyNietoperzy_legacy) | Archived legacy Excel-to-chart scripts retained as historical reference. | PRIVATE / ARCHIVED | 2025-09-06 | No active development. Confirm that sample data is safe, then leave archived. |

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
3. [Artportalen_med_data](https://github.com/JakubPelka/Artportalen_med_data) — cautious documentation, safe test data, and clear dev/prod split.
4. [LaczTabeleNietoperzy](https://github.com/JakubPelka/LaczTabeleNietoperzy) / [FixaDataAutoboxar](https://github.com/JakubPelka/FixaDataAutoboxar) — privacy, neutral README wording, and no sensitive data.
5. [GTB_connectivity](https://github.com/JakubPelka/GTB_connectivity) — validate QGIS Processing plugin structure, ignore working GIS data/outputs, document workflow limits, and prepare safe sample-data guidance.

## Post-cleanup testing / follow-up

- [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video) — cleanup baseline and release `v0.1.2` completed, with additional June 2026 commits after the release baseline. It is no longer a top cleanup priority. Current focus: practical testing, output validation, bug reports as issues, small fixes, UX polish, and further feature development.
- [Excel2Word_with_presets](https://github.com/JakubPelka/Excel2Word_with_presets) — repository has been significantly cleaned, but no release has been published yet. Current focus: practical testing, preset validation, DOCX output checks, photo/map placeholder behaviour, and preparing a possible first release after successful tests.
- [ComputerVisionCounter_Images](https://github.com/JakubPelka/ComputerVisionCounter_Images) — first cleaned release `v0.2.0` completed. Current state: `MAINTAINED / PAUSED`. The application works for the current scope; future changes can wait until there is a concrete bug, packaging need, or new CVC direction.
- [GTB_connectivity](https://github.com/JakubPelka/GTB_connectivity) — plugin workflow exists and is under validation. Current focus: compare outputs with reference scripts, test on more GTB Proximity datasets, and decide when it is clean enough for a release-style package.
- [CVC_Bats_Thermal_detection](https://github.com/JakubPelka/CVC_Bats_Thermal_detection) — release `v.0.2.1 – Small HUD improvements` completed. Current state: `MAINTAINED / PAUSED`. Return for concrete bug fixes, additional validation, tracking/counting improvements, CVC integration planning or sample-data/privacy decisions.

## Development priority

1. [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video) — major potential; current release baseline is `v0.1.2`, with newer June 2026 commits already added. Continue through practical testing, bug fixes, UX polish, output validation, and future tracking/segmentation experiments.
2. [GTB_connectivity](https://github.com/JakubPelka/GTB_connectivity) — promising QGIS/GTB post-processing plugin idea; continue validation before refactoring into a cleaner public plugin package.
3. [hajk-gesture-demo](https://github.com/JakubPelka/hajk-gesture-demo) — effective AI + GIS showcase.
4. [Artportalen_med_data](https://github.com/JakubPelka/Artportalen_med_data) — high practical value, but public wording must stay cautious.
5. [BlenderDigitalTwin](https://github.com/JakubPelka/BlenderDigitalTwin) — largest long-term potential, but requires strict architecture discipline.
6. [Osm-field-tagger-AI](https://github.com/JakubPelka/Osm-field-tagger-AI) — promising AI + OSM mobile idea; prepare after current cleanup backlog.
7. [ComputerVisionCounter_Images](https://github.com/JakubPelka/ComputerVisionCounter_Images) — first cleaned release `v0.2.0` completed; paused for now, but remains a future CVC-family candidate if new image-counting needs appear.
8. [CVC_Bats_Thermal_detection](https://github.com/JakubPelka/CVC_Bats_Thermal_detection) — release `v.0.2.1` completed and paused; keep as a future CVC-family candidate rather than an active development priority.

## Milestones already reached

- [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video) — active development baseline reached with release `v0.1.2`; newer June 2026 commits continue the testing/development track, so the project remains in `ACTIVE / TESTING`.
- [ROI_raster_histogram_QGIS](https://github.com/JakubPelka/ROI_raster_histogram_QGIS) — first public release completed: `v0.1.0`.
- [Exif_lat_lon](https://github.com/JakubPelka/Exif_lat_lon) — first public release completed: `v0.1.0`.
- [MergeExcelFiles](https://github.com/JakubPelka/MergeExcelFiles) — first cleaned release completed: `v0.1.0`.
- [skyddstrad-field-reporter](https://github.com/JakubPelka/skyddstrad-field-reporter) — first proof-of-concept release completed: `v0.1.0`.
- [CVC_Bats_Thermal_detection](https://github.com/JakubPelka/CVC_Bats_Thermal_detection) — release `v.0.2.1 – Small HUD improvements` completed; current state: `MAINTAINED / PAUSED`.
- [ComputerVisionCounter_Images](https://github.com/JakubPelka/ComputerVisionCounter_Images) — first cleaned release completed: `v0.2.0`.
- [Whisper](https://github.com/JakubPelka/Whisper) — usable local transcription workflow reached; maintained and paused without release for now.

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
