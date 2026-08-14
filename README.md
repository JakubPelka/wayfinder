# JakubPelka — GitHub Wayfinder

A compact navigation map for public, private, and archived GitHub repositories:
what each repository is for, its current status, and the next meaningful action.

Last reviewed: **2026-07-24**.

Current scan: **37 repositories** visible through the connected GitHub account.
Private links work only for accounts with access; this is intentional.

## Status legend

| Status | Meaning |
|---|---|
| ACTIVE | Actively developed or planned for further development. |
| TESTING | Usable development version under practical validation. |
| MAINTAINED | Works and may receive fixes, but no major rebuild is planned. |
| PAUSED | Useful milestone reached; resume only for a concrete need. |
| FIXED | The originating idea or task has been implemented and verified. |
| HOWTO | Documentation or reproducible workflow is the main value. |
| IDEA | Documented concept; implementation not currently active. |
| IDEA BANK | Parking place for concepts waiting for validation. |
| EXPERIMENT | Prototype, proof of concept, or development test. |
| SHOWCASE | Demo intended to show an idea or capability. |
| META | Repository used to organize or navigate other work. |
| TEMP PUBLIC | Public temporarily for cleanup, review, or development. |
| PRIVATE | Intentionally private; public detail should remain limited. |
| PRIVATE? | Review whether public visibility is still appropriate. |
| ARCHIVED | Historical trace with no planned development. |
| LEGACY / REVIEW | Older line that should be reconciled with a maintained successor. |

## Active, experimental, or requiring attention

| Repository | Short description | Status | Last update | Notes / next step |
|---|---|---|---|---|
| [cos](https://github.com/JakubPelka/cos) | Canonical Cognitive Operating System implementation and documentation: local-first context architecture, source contracts, reproducibility, and supervised agents. | ACTIVE / PRIVATE | 2026-07-24 | AgentBridge MVP is validated in PR #1. Next source workflow: Mail Source Contract v1, then location-history validation. |
| [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video) | Desktop YOLO video-analysis application with counting, zones, tracking, alerts, overlays, exports, and event statistics. | ACTIVE / TESTING | 2026-07-10 | Continue practical validation before promoting experiments to `main`. |
| [Mnemosyne](https://github.com/JakubPelka/Mnemosyne) | Local-first atlas of ChatGPT conversations and future personal sources with SQLite/FTS5, graphs, FastAPI, and React/Sigma UI. | ACTIVE / TEMP PUBLIC | 2026-07-19 | Keep exports, databases, indexes, sidecars, and logs outside Git; audit privacy before each push. |
| [GeoKombajn](https://github.com/JakubPelka/GeoKombajn) | AOI-driven GIS orchestration experiments combining data discovery, downloads, processing, and repeatable project packages. | ACTIVE / EXPERIMENT | 2026-07-17 | Convert working experiments into bounded modules only after credential and output hardening. |
| [GTB_connectivity](https://github.com/JakubPelka/GTB_connectivity) | QGIS/GuidosToolbox landscape-connectivity workflow with an experimental Processing plugin. | ACTIVE / EXPERIMENT / TESTING | 2026-05-24 | Validate plugin outputs and structure before a release-style package. |
| [BlenderDigitalTwin](https://github.com/JakubPelka/BlenderDigitalTwin) | Blender add-on/concept for reconstructing and visualising scenes from GIS data. | ACTIVE / EXPERIMENT | 2025-08-22 | Clean add-on structure and define a strict MVP before wider development. |
| [Sculptor_QGIS](https://github.com/JakubPelka/Sculptor_QGIS) | QGIS terrain-sculpting plugin for local raster editing and vector alignment. | ACTIVE / EXPERIMENT | 2026-07-17 | Consolidate versions, test on copies, and identify one release candidate. |
| [Artportalen_med_data](https://github.com/JakubPelka/Artportalen_med_data) | Enrichment of Artportalen/AGOL-derived records with conservation information. | TEMP PUBLIC / PRIVATE? | 2026-05-13 | Keep documentation neutral; no real data, tokens, endpoints, or operational details. |
| [hajk-gesture-demo](https://github.com/JakubPelka/hajk-gesture-demo) | Hand-gesture control demo for a Hajk/OpenLayers map using MediaPipe and OpenCV. | EXPERIMENT / SHOWCASE | 2026-05-08 | Add a short visual demo, gesture list, and known limitations. |
| [Excel2Word_with_presets](https://github.com/JakubPelka/Excel2Word_with_presets) | Tkinter/Python conversion of Excel rows into styled Word micro-tables using JSON presets. | MAINTAINED / TESTING | 2026-05-16 | Continue practical testing before the first release. |
| [MobileComputerVisionCounter](https://github.com/JakubPelka/MobileComputerVisionCounter) | Mobile object-counting idea/prototype using YOLO and iPhone. | EXPERIMENT | 2025-10-04 | Keep as proof of concept until a concrete mobile need appears. |
| [LaczTabeleNietoperzy](https://github.com/JakubPelka/LaczTabeleNietoperzy) | Autobox table merging, summaries, charts, and standalone parallel bat graph application. | ACTIVE / TEMP PUBLIC / PRIVATE? | 2026-07-17 | Test with synthetic data; keep real recordings and locations outside Git. |
| [przepisy](https://github.com/JakubPelka/przepisy) | Personal recipe application with calorie estimates and editing panel. | ACTIVE / PERSONAL | 2026-07-15 | Verify that any tracked database is deliberately public. |
| [Cesium_Sandbox](https://github.com/JakubPelka/Cesium_Sandbox) | CesiumJS sandbox for 3D Tiles, GeoJSON, photos, and map experiments. | EXPERIMENT / SHOWCASE | 2026-06-25 | Keep bounded and remove assets that should not be redistributed. |
| [Drone2Place](https://github.com/JakubPelka/Drone2Place) | Early place-identification concept based on drone imagery. | EXPERIMENT | 2025-09-22 | Add concise scope and limitations before further work. |
| [FusionCover](https://github.com/JakubPelka/FusionCover) | FUSION scripts for terrain or vegetation cover from LAS files. | EXPERIMENT / PRIVATE? | 2025-08-29 | Review public suitability and input/output documentation. |
| [FixaDataAutoboxar](https://github.com/JakubPelka/FixaDataAutoboxar) | WAV metadata extraction and readable Excel export. | MAINTAINED / TEMP PUBLIC | 2025-08-29 | Keep examples neutral and recording-derived data private. |
| [Osm-field-tagger-AI](https://github.com/JakubPelka/Osm-field-tagger-AI) | Human-verified mobile OSM field assistant using location, photo, and AI tag proposals. | IDEA / EXPERIMENT | 2026-05-16 | First PoC must remain small, local-first, and never upload automatically. |

## Idea bank

| Repository | Short description | Status | Last update | Notes / next step |
|---|---|---|---|---|
| [ideas](https://github.com/JakubPelka/ideas) | Lightweight bank for concepts waiting for discussion, validation, prioritisation, or prototyping. | IDEA BANK / MAINTAINED | 2026-07-24 | Implemented ideas leave this repository after verification; Git history preserves the original specification. |

## Documentation / HOWTO

| Repository | Short description | Status | Last update | Notes / next step |
|---|---|---|---|---|
| [jak-wytresowac-model-pt](https://github.com/JakubPelka/jak-wytresowac-model-pt) | Polish HOWTO for training a custom YOLO model with Linux/Windows setup and safety notes. | HOWTO / MAINTAINED | 2026-05-18 | Keep datasets, API links, model files, runs, archives, and private data outside Git. |
| [Julia_Omniscape](https://github.com/JakubPelka/Julia_Omniscape) | Private Omniscape workflow and working notes. | HOWTO / PRIVATE | 2026-06-15 | Keep study-area and project data private. |
| [LM_Hojddata_API_download](https://github.com/JakubPelka/LM_Hojddata_API_download) | Private elevation-download notes and scripts. | HOWTO / PRIVATE / REVIEW | 2025-08-29 | Reconcile with newer STAC work in GeoKombajn and remove obsolete authentication guidance. |

## Meta repositories

| Repository | Short description | Status | Last update | Notes / next step |
|---|---|---|---|---|
| [wayfinder](https://github.com/JakubPelka/wayfinder) | Navigation index for repository purpose, status, visibility, milestones, and next steps. | META / MAINTAINED | 2026-07-24 | Update after project creation, completion, release, archive, or visibility change. |

## Milestone reached

| Repository | Short description | Status | Last update | Notes / next step |
|---|---|---|---|---|
| [CVC_Bats_Thermal_detection](https://github.com/JakubPelka/CVC_Bats_Thermal_detection) | Thermal-video bat detection workflow with batch processing, event-clip extraction, human validation, manual counts/comments, and validated activity graphs. | MAINTAINED / PAUSED | 2026-08-14 | Release `v1.0.0` marks the first stable milestone: detection → event clips → human review → validated results is complete. Resume for concrete bug fixes, usability improvements, detector-metric analysis, or integration needs. |
| [ComputerVisionCounter_Images](https://github.com/JakubPelka/ComputerVisionCounter_Images) | Still-image object counting with local YOLO models and structured exports. | MAINTAINED / PAUSED | 2026-06-18 | Release `v0.2.0` completed; resume for a concrete bug or packaging need. |
| [Whisper](https://github.com/JakubPelka/Whisper) | Local transcription workflow for Swedish and multilingual recordings. | MAINTAINED / PAUSED | 2026-07-13 | Usable local workflow and watcher are complete; keep audio and transcripts outside Git. |
| [skyddstrad-field-reporter](https://github.com/JakubPelka/skyddstrad-field-reporter) | PWA field helper for protected-tree observations and reviewable exports. | MAINTAINED / PAUSED | 2026-05-18 | Proof-of-concept release `v0.1.0` published. |
| [MergeExcelFiles](https://github.com/JakubPelka/MergeExcelFiles) | Small GUI tool for merging equally structured Excel files. | MAINTAINED / PAUSED | 2026-05-15 | Release `v0.1.0` published. |
| [ROI_raster_histogram_QGIS](https://github.com/JakubPelka/ROI_raster_histogram_QGIS) | QGIS ROI raster statistics plugin with tables, charts, and HTML export. | MAINTAINED / PAUSED | 2026-05-15 | Release `v0.1.0` published. |
| [Exif_lat_lon](https://github.com/JakubPelka/Exif_lat_lon) | GPS metadata extraction from images to CSV and GeoJSON. | MAINTAINED / PAUSED | 2026-05-15 | Release `v0.1.0` published. |

## Private or intentionally limited repositories

Links in this section intentionally expose only minimal context.

| Repository | Short description | Status | Last update | Notes / next step |
|---|---|---|---|---|
| [AgentBridge_20260722_agentbridge-mvp](https://github.com/JakubPelka/AgentBridge_20260722_agentbridge-mvp) | Durable private validation and audit thread for the COS GPT ↔ Codex AgentBridge MVP. | FIXED / PRIVATE | 2026-07-24 | AgentBridge idea implemented and removed from `ideas`. Keep the repository private; continue development in COS, using this repository as the validated thread record. |
| [CognitiveOperatingSystem-COS](https://github.com/JakubPelka/CognitiveOperatingSystem-COS) | Earlier private COS implementation/recovery line. | PRIVATE / LEGACY / REVIEW | 2026-07-15 | Reconcile any unique journal, recovery, or setup material into canonical `cos`; avoid two competing implementation roadmaps. |
| [Hembygd_till_CSV](https://github.com/JakubPelka/Hembygd_till_CSV) | Private conversion experiment with a demo result. | PRIVATE / EXPERIMENT | 2026-03-31 | Verify that the demo contains only redistributable data. |
| [SpotifyImportExport](https://github.com/JakubPelka/SpotifyImportExport) | Private Spotify playlist CSV import/export scripts. | PRIVATE / MAINTAINED | 2025-08-29 | Review scopes, token handling, and generated playlist data before visibility changes. |
| [AGOL_med_data](https://github.com/JakubPelka/AGOL_med_data) | Archived predecessor for conservation-data enrichment. | PRIVATE / ARCHIVED | 2025-09-18 | Keep archived; never expose credentials or operational data. |
| [FME_PREBAT](https://github.com/JakubPelka/FME_PREBAT) | Private PREBAT/FME development workflow. | PRIVATE / EXPERIMENT | 2025-09-09 | Keep operational context and real data private. |
| [WykresyNietoperzy_legacy](https://github.com/JakubPelka/WykresyNietoperzy_legacy) | Archived legacy Excel-to-chart scripts. | PRIVATE / ARCHIVED | 2025-09-06 | Historical reference only. |

## Current priorities

1. Review and merge the AgentBridge MVP into canonical `cos`.
2. Use AgentBridge for `Mail Source Contract v1` discovery and validation.
3. Continue with location-history discovery and `Location Source Contract v1`.
4. Keep practical testing of ComputerVisionCounter_video and GTB_connectivity.
5. Reconcile unique material from `CognitiveOperatingSystem-COS` into `cos` before archiving or freezing the older line.

## Repository work rules

- One repository and one goal at a time.
- Small, reviewable commits.
- Security and repository hygiene before features.
- Code and documentation belong in Git; secrets, raw personal data, models,
  caches, outputs, and working backups do not.
- An implemented idea leaves `ideas` and is represented by its real project.
- Private repositories receive minimal public descriptions.