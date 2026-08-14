# JakubPelka — GitHub Wayfinder

A compact navigation map for my GitHub repositories: what each repository is for,  
its current lifecycle state, and the next meaningful action.

Last reviewed: **2026-08-14**.

Current scan: **41 repositories** visible through the connected GitHub account.  
Private links work only for accounts with access; this is intentional.

## Status legend

Status describes the **lifecycle of the repository**, not its type.

Repository type — application, HOWTO, idea bank, experiment, meta repository,  
personal tool, etc. — is described by its section and description instead of  
creating a separate status for every case.

|Status|Meaning|
|---|---|
|ACTIVE|Actively developed or currently receiving meaningful work.|
|MAINTAINED|Works and may receive fixes or small improvements.|
|PAUSED|Useful milestone reached; resume only for a concrete need.|
|EXPERIMENT|Prototype, concept, sandbox, or unfinished line of development.|
|PRIVATE|Intentionally private; public detail should remain limited.|
|ARCHIVED|Historical repository with no planned development.|

Statuses may be combined when useful, for example `ACTIVE / PRIVATE`,  
`MAINTAINED / PAUSED`, or `EXPERIMENT / PRIVATE`.

## Active / in progress

|Repository|Short description|Status|Last update|Notes / next step|
|---|---|---|---|---|
|[VildaLeder](https://github.com/JakubPelka/VildaLeder)|Nature-discovery product connecting visitable trails, reserves and observation places with public biodiversity observations.|ACTIVE / PRIVATE|2026-08-14|Working multilingual web product. Current focus: stabilise nationwide Sweden coverage and Cloudflare/R2 production delivery, then taxonomy, accounts, mobile packaging and later European expansion.|
|[cos](https://github.com/JakubPelka/cos)|Canonical Cognitive Operating System implementation and documentation: local-first context architecture, source contracts, reproducibility and supervised agents.|ACTIVE / PRIVATE|2026-07-24|Continue source-contract and AgentBridge development while keeping personal data and credentials outside Git.|
|[ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video)|Desktop YOLO video-analysis application with counting, zones, tracking, alerts, overlays, exports and event statistics.|ACTIVE|2026-07-10|Continue practical validation and issue-based development before promoting experimental features.|
|[Mnemosyne](https://github.com/JakubPelka/Mnemosyne)|Local-first atlas of ChatGPT conversations and future personal sources with SQLite/FTS5, graphs, FastAPI and React/Sigma UI.|ACTIVE|2026-07-19|Keep exports, databases, indexes, sidecars and logs outside Git; audit privacy before each push.|
|[GeoKombajn](https://github.com/JakubPelka/GeoKombajn)|AOI-driven GIS orchestration experiments combining data discovery, downloads, processing and repeatable project packages.|ACTIVE / EXPERIMENT|2026-07-17|Convert working experiments into bounded modules only after credential and output hardening.|
|[GTB_connectivity](https://github.com/JakubPelka/GTB_connectivity)|QGIS/GuidosToolbox landscape-connectivity workflow with an experimental Processing plugin.|ACTIVE / EXPERIMENT|2026-05-24|Validate plugin outputs and structure before a release-style package.|
|[BlenderDigitalTwin](https://github.com/JakubPelka/BlenderDigitalTwin)|Blender add-on/concept for reconstructing and visualising scenes from GIS data.|ACTIVE / EXPERIMENT|2025-08-22|Clean add-on structure and define a strict MVP before wider development.|
|[Sculptor_QGIS](https://github.com/JakubPelka/Sculptor_QGIS)|QGIS terrain-sculpting plugin for local raster editing and vector alignment.|ACTIVE / EXPERIMENT|2026-07-17|Consolidate versions, test on copies and identify one release candidate.|
|[LaczTabeleNietoperzy](https://github.com/JakubPelka/LaczTabeleNietoperzy)|Autobox table merging, summaries, charts and standalone parallel bat graph application.|ACTIVE / EXPERIMENT|2026-07-17|Test with synthetic data; keep real recordings and locations outside Git.|
|[przepisy](https://github.com/JakubPelka/przepisy)|Personal recipe application with calorie estimates and editing panel.|ACTIVE|2026-07-15|Keep tracked data deliberately public and separate personal/private material.|

## Maintained / paused

These repositories work for their current purpose. They are not current development priorities.

|Repository|Short description|Status|Last update|Notes / next step|
|---|---|---|---|---|
|[CVC_Bats_Thermal_detection](https://github.com/JakubPelka/CVC_Bats_Thermal_detection)|Thermal-video bat detection workflow with batch processing, event-clip extraction, human validation, manual counts/comments and validated activity graphs.|MAINTAINED / PAUSED|2026-08-14|Release `v1.0.0` marks the first stable milestone. Resume for concrete bugs, usability improvements, detector analysis or integration needs.|
|[ComputerVisionCounter_Images](https://github.com/JakubPelka/ComputerVisionCounter_Images)|Still-image object counting with local YOLO models and structured exports.|MAINTAINED / PAUSED|2026-06-18|Release `v0.2.0` completed; resume for a concrete bug, packaging need or future CVC-family development.|
|[Whisper](https://github.com/JakubPelka/Whisper)|Local transcription workflow for Swedish and multilingual recordings.|MAINTAINED / PAUSED|2026-07-13|Usable local workflow and watcher are complete; keep audio and transcripts outside Git.|
|[skyddstrad-field-reporter](https://github.com/JakubPelka/skyddstrad-field-reporter)|PWA field helper for protected-tree observations and reviewable exports.|MAINTAINED / PAUSED|2026-05-18|Proof-of-concept release `v0.1.0` published.|
|[MergeExcelFiles](https://github.com/JakubPelka/MergeExcelFiles)|Small GUI tool for merging equally structured Excel files.|MAINTAINED / PAUSED|2026-05-15|Release `v0.1.0` published.|
|[ROI_raster_histogram_QGIS](https://github.com/JakubPelka/ROI_raster_histogram_QGIS)|QGIS ROI raster statistics plugin with tables, charts and HTML export.|MAINTAINED / PAUSED|2026-05-15|Release `v0.1.0` published.|
|[Exif_lat_lon](https://github.com/JakubPelka/Exif_lat_lon)|GPS metadata extraction from images to CSV and GeoJSON.|MAINTAINED / PAUSED|2026-05-15|Release `v0.1.0` published.|
|[Excel2Word_with_presets](https://github.com/JakubPelka/Excel2Word_with_presets)|Tkinter/Python conversion of Excel rows into styled Word micro-tables using JSON presets.|MAINTAINED|2026-05-16|Continue practical testing when there is a concrete need; no large rebuild planned.|
|[FixaDataAutoboxar](https://github.com/JakubPelka/FixaDataAutoboxar)|WAV metadata extraction and readable Excel export.|MAINTAINED|2025-08-29|Keep examples neutral and recording-derived data private.|
|[HA](https://github.com/JakubPelka/HA)|Sanitised private history of the Home Assistant configuration used on the home server.|MAINTAINED / PRIVATE|2026-08-03|Automatic sync is working. Keep runtime state, recorder DB, backups, TLS keys, secrets and unrestricted `.storage` outside Git.|
|[SpotifyImportExport](https://github.com/JakubPelka/SpotifyImportExport)|Private Spotify playlist CSV import/export scripts.|MAINTAINED / PRIVATE|2025-08-29|Keep token handling and generated playlist data private.|
|[AgentBridge_20260722_agentbridge-mvp](https://github.com/JakubPelka/AgentBridge_20260722_agentbridge-mvp)|Durable private validation thread for the original COS GPT ↔ Codex AgentBridge MVP.|MAINTAINED / PAUSED / PRIVATE|2026-07-24|Original MVP validated. Implementation continues in COS; keep this repository as the durable thread record.|

## Reference / ideas / experiments

This section contains documentation, idea banks, sandboxes, durable thread records and  
experiments that are useful to keep but are not current core development priorities.

|Repository|Short description|Status|Last update|Notes / next step|
|---|---|---|---|---|
|[ideas](https://github.com/JakubPelka/ideas)|Lightweight private bank for concepts waiting for discussion, validation, prioritisation or prototyping.|MAINTAINED / PRIVATE|2026-07-24|Implemented ideas leave this repository after verification; Git history preserves the original specification.|
|[wayfinder](https://github.com/JakubPelka/wayfinder)|Navigation index for repository purpose, lifecycle state, visibility and next steps.|MAINTAINED|2026-08-14|Keep structure human-controlled; weekly automation may later maintain factual repository rows inside this schema.|
|[jak-wytresowac-model-pt](https://github.com/JakubPelka/jak-wytresowac-model-pt)|Polish HOWTO for training a custom YOLO model with Linux/Windows setup and safety notes.|MAINTAINED|2026-05-18|Keep datasets, API links, model files, runs, archives and private data outside Git.|
|[Julia_Omniscape](https://github.com/JakubPelka/Julia_Omniscape)|Private Omniscape workflow and working notes.|MAINTAINED / PRIVATE|2026-06-15|Keep study-area and project data private.|
|[LM_Hojddata_API_download](https://github.com/JakubPelka/LM_Hojddata_API_download)|Private elevation-download notes and scripts.|MAINTAINED / PRIVATE|2025-08-29|Reconcile useful material with newer STAC work in GeoKombajn when needed.|
|[hajk-gesture-demo](https://github.com/JakubPelka/hajk-gesture-demo)|Hand-gesture control demo for a Hajk/OpenLayers map using MediaPipe and OpenCV.|EXPERIMENT|2026-05-08|Add a short visual demo and known limitations if revisited.|
|[MobileComputerVisionCounter](https://github.com/JakubPelka/MobileComputerVisionCounter)|Mobile object-counting idea/prototype using YOLO and iPhone.|EXPERIMENT|2025-10-04|Keep as proof of concept until a concrete mobile need appears.|
|[Cesium_Sandbox](https://github.com/JakubPelka/Cesium_Sandbox)|CesiumJS sandbox for 3D Tiles, GeoJSON, photos and map experiments.|EXPERIMENT|2026-06-25|Keep bounded and remove assets that should not be redistributed.|
|[Drone2Place](https://github.com/JakubPelka/Drone2Place)|Early place-identification concept based on drone imagery.|EXPERIMENT|2025-09-22|Add concise scope and limitations before further work.|
|[FusionCover](https://github.com/JakubPelka/FusionCover)|FUSION scripts for terrain or vegetation cover from LAS files.|EXPERIMENT|2025-08-29|Review public suitability and input/output documentation before further work.|
|[Osm-field-tagger-AI](https://github.com/JakubPelka/Osm-field-tagger-AI)|Human-verified mobile OSM field assistant using location, photo and AI tag proposals.|EXPERIMENT|2026-05-16|First PoC should remain small, local-first and never upload automatically.|
|[Artportalen_med_data](https://github.com/JakubPelka/Artportalen_med_data)|Enrichment of Artportalen-derived records with conservation information.|EXPERIMENT|2026-05-13|Sensitive topic: keep documentation neutral and avoid real data, tokens, endpoints and unnecessary operational detail. Review whether continued public visibility is useful.|
|[Hembygd_till_CSV](https://github.com/JakubPelka/Hembygd_till_CSV)|Private conversion experiment with a demo result.|EXPERIMENT / PRIVATE|2026-03-31|Verify that any demo material remains safe and redistributable.|
|[FME_PREBAT](https://github.com/JakubPelka/FME_PREBAT)|Private PREBAT/FME development workflow.|EXPERIMENT / PRIVATE|2025-09-09|Keep operational context and real data private.|
|[AgentBridge_20260730_mnemosyne-semantic-tagger](https://github.com/JakubPelka/AgentBridge_20260730_mnemosyne-semantic-tagger)|Durable private AgentBridge thread for Mnemosyne semantic-tagging work.|MAINTAINED / PRIVATE|2026-08-03|Thread record only; AgentBridge implementation remains in COS.|
|[AgentBridge_20260803_cos-agentbridge-v02](https://github.com/JakubPelka/AgentBridge_20260803_cos-agentbridge-v02)|Durable private AgentBridge thread for designing the protocol 0.2 contract in COS.|MAINTAINED / PRIVATE|2026-08-03|Thread record only; implementation remains in COS.|
|[AgentBridge_20260803_mail-v1](https://github.com/JakubPelka/AgentBridge_20260803_mail-v1)|Durable private AgentBridge thread for COS Mail Source Contract v1.|MAINTAINED / PRIVATE|2026-08-03|Thread record only; implementation remains in COS.|
|[CognitiveOperatingSystem-COS](https://github.com/JakubPelka/CognitiveOperatingSystem-COS)|Earlier private COS implementation/recovery line.|PAUSED / PRIVATE|2026-07-15|Not visible in the 2026-08-14 connector scan. Verify whether it was deleted, renamed or merely unavailable before removing this Wayfinder entry.|

## Archived

Only repositories that are intentionally historical belong here.

|Repository|Short description|Status|Last update|Notes / next step|
|---|---|---|---|---|
|[AGOL_med_data](https://github.com/JakubPelka/AGOL_med_data)|Archived predecessor for conservation-data enrichment.|ARCHIVED / PRIVATE|2025-09-18|Historical reference only; never expose credentials or operational data.|
|[WykresyNietoperzy_legacy](https://github.com/JakubPelka/WykresyNietoperzy_legacy)|Archived legacy Excel-to-chart scripts.|ARCHIVED / PRIVATE|2025-09-06|Historical reference only.|

## Current priorities

1. Stabilise VildaLeder nationwide Sweden coverage and the Cloudflare/R2 production path.
    
2. Continue practical validation of ComputerVisionCounter_video and GTB_connectivity.
    
3. Continue COS / AgentBridge source-contract work when it becomes the active focus again.
    
4. Keep sensitive public repositories free from real data, credentials, local paths and unnecessary operational detail.
    

## Repository work rules

- One repository and one goal at a time.
    
- Small, reviewable commits.
    
- Security and repository hygiene before features.
    
- Code and documentation belong in Git; secrets, raw personal data, models,  
    caches, outputs and working backups do not.
    
- Repository **type** belongs in its description/section; lifecycle belongs in the status column.
    
- An implemented idea leaves `ideas` and is represented by its real project.
    
- Private repositories receive minimal public descriptions.
    
- Weekly automation may update factual rows, but it should not create new status classes or restructure the page.