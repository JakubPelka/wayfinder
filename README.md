# JakubPelka — GitHub Wayfinder

Krótki drogowskaz po publicznych repozytoriach GitHub.

Ten README ma pomóc szybko odnaleźć projekt, ocenić jego status i zdecydować, co warto sprzątać lub rozwijać dalej.

Dane startowe: 2026-05-14.  
Pole „ostatnia widoczna aktualizacja” oznacza datę `Updated` widoczną na publicznej liście repozytoriów GitHub. To nie jest pełny audyt historii commitów.

## Statusy

| Status | Znaczenie |
|---|---|
| ACTIVE | Aktywnie rozwijane lub planowane do dalszego rozwoju |
| MAINTAINED | Działa; możliwe poprawki, ale bez dużej przebudowy |
| EXPERIMENT | Prototyp, PoC, wersja rozwojowa albo pomysł do testów |
| TEMP PUBLIC | Publiczne tymczasowo, głównie do wspólnej pracy i porządkowania |
| PRIVATE? | Warto rozważyć powrót do repo prywatnego albo ograniczenie opisu publicznego |
| ARCHIVED | Zachowane jako ślad, bez planowanego rozwoju |
| PAUSED | Kamień milowy osiągnięty; brak aktywnych planów rozwoju. Tylko ewentualne poprawki błędów lub małe aktualizacje. |

## Repozytoria

| Repozytorium | Krótki opis | Status | Ostatnia widoczna aktualizacja | Uwagi / następny krok |
|---|---|---|---|---|
| [ComputerVisionCounter_video](https://github.com/JakubPelka/ComputerVisionCounter_video) | Liczenie obiektów w nagraniach wideo z użyciem YOLO; strefy, zdarzenia, alerty i eksport wyników. | ACTIVE / EXPERIMENT | 2026-05-13 | Wysoki priorytet sprzątania: backupy, modele AI, outputy, struktura, README, release policy. |
| [MergeExcelFiles](https://github.com/JakubPelka/MergeExcelFiles) | Łączenie kilku plików Excel z danymi o drzewach / Artportalen w jeden plik. | MAINTAINED / TEMP PUBLIC | 2026-05-13 | Uporządkować README, przykładowe dane i zakres publiczności. |
| [ROI_raster_histogram_QGIS](https://github.com/JakubPelka/ROI_raster_histogram_QGIS) | Plugin QGIS do obliczania statystyk klas rastra w obrębie polygonów ROI, z tabelami, wykresami, eksportem HTML i opcjonalnym zapisem procentów do warstwy ROI. | MAINTAINED / PAUSED | 2026-05-15 | Release `v0.1.0` opublikowany. Plugin działa i instaluje się z przygotowanej paczki ZIP. Repo uporządkowane jako publiczne repo GIS; wracać tylko przy błędach, poprawkach UI, nowych potrzebach eksportu albo dalszym refaktorze. |
| [Exif_lat_lon](https://github.com/JakubPelka/Exif_lat_lon) | Odczyt współrzędnych GPS z metadanych zdjęć i eksport do CSV oraz GeoJSON. | MAINTAINED / PAUSED | 2026-05-15 | Release `v0.1.0` opublikowany. Repo uporządkowane i przetestowane. Brak aktywnych planów dalszego rozwoju; wracać tylko przy błędach, nowych formatach wejściowych albo potrzebie pakietowania. |
| [Artportalen_med_data](https://github.com/JakubPelka/Artportalen_med_data) | Uzupełnianie danych z Artportalen / AGOL o informacje o statusie ochrony i dodatkowe kolumny. | TEMP PUBLIC / PRIVATE? | 2026-05-13 | Temat wrażliwy. Dokumentacja ostrożna, bez realnych danych, tokenów, endpointów i nadmiarowego kontekstu. |
| [hajk-gesture-demo](https://github.com/JakubPelka/hajk-gesture-demo) | Demo sterowania mapą Hajk / OpenLayers gestami dłoni z użyciem MediaPipe i OpenCV. | EXPERIMENT / SHOWCASE | 2026-05-08 | Dobre repo pokazowe. Dodać GIF/video, listę gestów, architekturę i known limitations. |
| [Sculptor_QGIS](https://github.com/JakubPelka/Sculptor_QGIS) | Eksperyment z modelowaniem / rzeźbieniem terenu w QGIS podobnie jak sculpting w Blenderze. | EXPERIMENT | 2026-05-07 | Uporządkować wersje MVP, zipy i strukturę pluginu. Jasno oznaczyć jako eksperyment. |
| [ComputerVisionCounter_Images](https://github.com/JakubPelka/ComputerVisionCounter_Images) | Liczenie obiektów na obrazach z użyciem modeli YOLO; wersja z lepszą strukturą kodu. | ACTIVE / MAINTAINED | 2025-10-14 | Duży potencjał produktowy. Modele poza repo, output ignorowany, dopracować README użytkownika. |
| [MobileComputerVisionCounter](https://github.com/JakubPelka/MobileComputerVisionCounter) | Pomysł / prototyp mobilnej aplikacji do liczenia obiektów z użyciem YOLO i iPhone. | EXPERIMENT | 2025-10-04 | Zachować jako PoC. Warto dopisać status, zakres i decyzję czy rozwijać dalej. |
| [Excel2Word_with_presets](https://github.com/JakubPelka/Excel2Word_with_presets) | Eksport wierszy z tabeli Excel do dokumentów Word z użyciem presetów. | MAINTAINED | 2025-09-25 | Praktyczne narzędzie. Uporządkować README i przykłady bez danych prywatnych. |
| [LaczTabeleNietoperzy](https://github.com/JakubPelka/LaczTabeleNietoperzy) | Łączenie tabel z Autoboxów oraz generowanie wykresów zbiorczych i dziennych. | TEMP PUBLIC / PRIVATE? | 2025-09-24 | Temat wrażliwy. Zachować neutralny opis, bez danych lokalizacyjnych i realnych nagrań. |
| [Drone2Place](https://github.com/JakubPelka/Drone2Place) | Pomysł na znajdowanie miejsc ze zdjęć dronowych i lokalizowanie ich na mapie. | EXPERIMENT | 2025-09-22 | Wczesny pomysł. Dodać krótki README z celem, ograniczeniami i możliwym kierunkiem. |
| [FusionCover](https://github.com/JakubPelka/FusionCover) | Seria skryptów do obliczania pokrycia terenu z plików LAS z użyciem FUSION. | EXPERIMENT / PRIVATE? | 2025-08-29 | Do weryfikacji. Uporządkować opis wejścia/wyjścia i sprawdzić, czy repo powinno być publiczne. |
| [FixaDataAutoboxar](https://github.com/JakubPelka/FixaDataAutoboxar) | Automatyczne zbieranie metadanych z plików WAV i zapis do czytelnego arkusza Excel. | MAINTAINED / TEMP PUBLIC | 2025-08-29 | Praktyczne narzędzie, ale powiązane z danymi z nagrań. Ostrożnie z przykładami i opisem. |
| [BlenderDigitalTwin](https://github.com/JakubPelka/BlenderDigitalTwin) | Add-on / koncepcja Blender Digital Twin: odtwarzanie sceny z danych GIS. | ACTIVE / EXPERIMENT | 2025-08-22 | Bardzo duży potencjał długoterminowy. Najpierw uporządkować strukturę add-onu i zakres MVP. |

## Priorytet sprzątania

1. ComputerVisionCounter_video — bezpieczeństwo, modele, backupy, outputy.
2. BlenderDigitalTwin — struktura add-onu, buildy, foldery robocze.
3. Sculptor_QGIS — wersje MVP, zipy, struktura pluginu.
4. ComputerVisionCounter_Images — struktura produktu, modele poza repo.
5. Artportalen_med_data — ostrożna dokumentacja i dane testowe.
6. LaczTabeleNietoperzy / FixaDataAutoboxar — prywatność danych, neutralne README.

## Priorytet rozwoju

1. ComputerVisionCounter_Images — potencjał produktowy i portfolio.
2. hajk-gesture-demo — efektowne demo AI + GIS.
3. Artportalen_med_data — duża wartość robocza, ale ostrożnie z publicznością.
4. ComputerVisionCounter_video — duży potencjał po cleanupie.
5. BlenderDigitalTwin — największy potencjał długoterminowy, ale wymaga dyscypliny architektury.

## Standard pracy z repo

- Jedno repozytorium na raz.
- Jeden cel na raz.
- Małe commity.
- Najpierw bezpieczeństwo i higiena.
- Potem README, struktura i roadmapa.
- Dopiero potem nowe funkcje.
- GitHub to kod źródłowy, dokumentacja i release, nie folder backupowy.

## Minimalna checklista dla każdego repo

- README.md istnieje i jasno wyjaśnia cel projektu.
- LICENSE istnieje albo świadomie go brak.
- .gitignore blokuje sekrety, outputy, cache, zipy i modele.
- Brak tokenów, kluczy API, haseł i plików .env.
- Brak prywatnych lub realnych danych testowych.
- Brak backup zipów i folderów roboczych.
- Struktura folderów jest logiczna.
- Da się zrozumieć, jak uruchomić projekt.
- Status repo jest jasny.
