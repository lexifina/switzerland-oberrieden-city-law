# Oberrieden (city): law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Oberrieden, Zurich, Switzerland, which global-law reads at `switzerland/zurich/oberrieden/acts/`.

The municipal law of the municipality of Oberrieden (Gemeinde Oberrieden, canton of Zurich, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Zurich is in [lexifina/switzerland-zurich-law](https://github.com/lexifina/switzerland-zurich-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

49 acts with 66 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1-go/` | Gemeindeordnung (SRS 1.1-1) | 1 | as enacted, 1 January 2022 |
| `1-2-1-ivar/` | Reglement Informationsverwaltung und Archivierung (SRS 1.2-1) | 1 | as enacted, 1 January 2026 |
| `1-6-1-entschadigungsverordnung-evo/` | Verordnung über die Entschädigung von Behördenmitgliedern und weiteren Funktionären (SRS 1.6-1) | 1 | as enacted, 1 January 2023 |
| `1-6-2/` | Verwaltungsreglement (SRS 1.6-2) | 2 | as enacted, then each consolidated version: 1 July 2018 to 18 August 2026 |
| `1-6-3/` | Spesenreglement für Behörden und Kommissionen (SRS 1.6-3) | 1 | as enacted, 1 July 2024 |
| `1-6-4/` | Geschäftsordnung Werkkommission (SRS 1.6-4) | 1 | as enacted, 1 July 2022 |
| `1-6-5/` | Geschäftsordnung der Liegenschaftskommission (SRS 1.6-5) | 1 | as enacted, 1 July 2022 |
| `1-7-1-pvo/` | Personalverordnung (SRS 1.7-1) | 2 | as enacted, then each consolidated version: 1 January 2000 to 1 October 2025 |
| `1-7-1-1-pr/` | Personalreglement (SRS 1.7-1.1) | 1 | one version (the oldest available), 1 January 2026 |
| `1-7-3-spesenreglement/` | Spesenreglement (SRS 1.7-3) | 1 | as enacted, 1 July 2024 |
| `4-1-1/` | Betriebsreglement Kita Freihofstrasse (SRS 4.1-1) | 3 | as enacted, then each consolidated version: 1 August 2022 to 1 October 2026 |
| `4-1-2/` | Betriebsreglement inkl. Tarifordnung Schulergänzende Betreuung Oberrieden, Hort Momina (SRS 4.1-2) | 1 | as enacted, 1 August 2022 |
| `4-1-3/` | Tarifordnung Kita Freihofstrasse (SRS 4.1-3) | 2 | as enacted, then each consolidated version: 1 August 2025 to 1 October 2026 |
| `4-2-1/` | Geschäftsordnung Schule (SRS 4.2-1) | 2 | as enacted, then each consolidated version: 1 December 2022 to 5 March 2024 |
| `4-2-2/` | Reglement über den Elternrat der Schule Oberrieden (SRS 4.2-2) | 1 | as enacted, 1 August 2022 |
| `4-2-3/` | Gebührentarif der Schule Oberrieden (SRS 4.2-3) | 2 | as enacted, then each consolidated version: 1 August 2021 to 1 February 2024 |
| `4-2-4/` | Reglement Schulzahnpflege (SRS 4.2-4) | 2 | as enacted, then each consolidated version: 1 August 2017 to 1 April 2024 |
| `4-2-5/` | Besoldungsreglement (SRS 4.2-5) | 1 | as enacted, 1 August 2022 |
| `4-5-1/` | Benützungsreglement Strandbad (SRS 4.5-1) | 1 | as enacted, 6 May 2014 |
| `4-7-1/` | Benutzungsordnung der Bibliothek Oberrieden (SRS 4.7-1) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 April 2024 |
| `5-1-1/` | Polizeiverordnung (SRS 5.1-1) | 1 | as enacted, 1 January 2012 |
| `5-1-2/` | Verordnung über das gemeinderechtliche Ordnungsbussenverfahren (OBV) mit zugehöriger Bussenliste (SRS 5.1-2) | 1 | as enacted, 1 January 2012 |
| `5-1-3-rvog/` | Reglement über die Videoüberwachung auf öffentlichem Grund (SRS 5.1-3) | 1 | as enacted, 1 September 2026 |
| `6-4-1/` | Gebührenverordnung (SRS 6.4-1) | 1 | as enacted, 1 January 2019 |
| `6-4-1-1/` | Gebührentarif (SRS 6.4-1.1) | 2 | oldest version available, then each consolidated version: 23 August 2022 to 1 July 2023 |
| `6-6-1/` | Gebührenreglement Gemeindeliegenschaften (SRS 6.6-1) | 1 | as enacted, 1 April 2020 |
| `6-6-2/` | Benützungsreglement für die Schützenstube (SRS 6.6-2) | 1 | as enacted, 22 January 1991 |
| `6-6-3/` | Benützungsreglement für die Räumlichkeiten des GAWO-Zentrums in der Liegenschaft Spielhofweg 12, 8942 Oberrieden (SRS 6.6-3) | 1 | as enacted, 30 March 2004 |
| `6-6-4/` | Benützungsreglement Villa Schönfels (SRS 6.6-4) | 1 | as enacted, 1 October 2002 |
| `7-1-1/` | Bau- und Zonenordnung (SRS 7.1-1) | 3 | as enacted, then each consolidated version: 26 April 2014 to 26 January 2026 |
| `7-4-3-1-wavo/` | Wasserverordnung (SRS 7.4.3-1) | 1 | as enacted, 1 July 2022 |
| `7-4-3-1-1/` | Ausführungsbestimmungen zur Wasserverordnung (SRS 7.4.3-1.1) | 1 | as enacted, 1 July 2022 |
| `7-4-3-1-2/` | Wasser- und Abwassergebühren (SRS 7.4.3-1.2) | 1 | as enacted, 1 January 2023 |
| `7-4-3-2-sevo/` | Siedlungsentwässerungsverordnung (SRS 7.4.3-2) | 1 | as enacted, 1 July 2022 |
| `7-4-3-2-1/` | Ausführungsbestimmungen zur Siedlungsentwässerungsverordnung (SRS 7.4.3-2.1) | 1 | as enacted, 1 July 2022 |
| `7-4-3-2-2-gebv-sevo/` | Verordnung über die Gebühren für Siedlungsentwässerungsanlagen (SRS 7.4.3-2.2) | 1 | as enacted, 1 October 2012 |
| `7-4-4-1-abfvo/` | Abfallverordnung (SRS 7.4.4-1) | 1 | as enacted, 1 July 2022 |
| `7-4-4-1-1/` | Ausführungsbestimmungen zur Abfallverordnung (SRS 7.4.4-1.1) | 1 | as enacted, 1 July 2022 |
| `7-7-1-vpog/` | Verordnung über das Parkieren auf öffentlichem Grund (SRS 7.7-1) | 1 | as enacted, 1 July 2026 |
| `7-7-1-1-avpog/` | Ausführungsbestimmungen zur Verordnung über das Parkieren auf öffentlichem Grund (SRS 7.7-1.1) | 1 | as enacted, 1 July 2026 |
| `8-2-1/` | Friedhof- und Bestattungsverordnung (SRS 8.2-1) | 1 | as enacted, 1 May 2023 |
| `8-7-1/` | Geschäftsreglement der Sozialbehörde (SRS 8.7-1) | 1 | as enacted, 1 February 2023 |
| `8-7-2-ko-sobe/` | Kompetenzordnung Sozialbehörde (SRS 8.7-2) | 2 | as enacted, then each consolidated version: 1 May 2024 to 1 September 2026 |
| `8-7-3-rl-mietzins-wsh/` | Mietzinsrichtlinie Wirtschaftliche Sozialhilfe (SRS 8.7-3) | 1 | as enacted, 1 April 2024 |
| `8-7-4-rl-mietzins-status-n/` | Mietzinsrichtlinien Status N (SRS 8.7-4) | 1 | as enacted, 1 April 2024 |
| `8-7-5-rl-asylsozialhilfe-nach-afv/` | Richtlinie Asylsozialhilfe nach Asylfürsorgeverordnung (AfV) (SRS 8.7-5) | 4 | as enacted, then each consolidated version: 1 April 2024 to 1 January 2027 |
| `8-7-6-vo-feb/` | Verordnung über die Betreuungszuschüsse für die familienergänzende Kinderbetreuung (SRS 8.7-6) | 1 | as enacted, 1 August 2025 |
| `8-7-7-reglement-zur-vo-feb/` | Reglement zur Verordnung über die Betreuungszuschüsse für die familienergänzende Betreuung (SRS 8.7-7) | 2 | as enacted, then each consolidated version: 1 August 2025 to 1 August 2026 |
| `9-5-1/` | Ladenschlussverordnung (SRS 9.5-1) | 1 | as enacted, 1 August 1995 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://oberrieden.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@oberrieden.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
