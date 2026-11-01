# Steinhausen (city): law history in git

The municipal law of the municipality of Steinhausen (Gemeinde Steinhausen, canton of Zug, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Zug is in [lexifina/switzerland-zug-law](https://github.com/lexifina/switzerland-zug-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

51 acts with 68 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 2 | oldest version available, then each consolidated version: 5 January 2019 to 1 January 2027 |
| `1-6-1/` | Strategische Grundsätze 2024 bis 2027 – Digitalisierung (SRS 1.6-1) | 1 | as enacted, 1 October 2024 |
| `1-6-1-1/` | Pflichtenheft für die Baukommission (SRS 1.6.1-1) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `1-6-1-2/` | Pflichtenheft für die Energie- und Umweltkommission (SRS 1.6.1-2) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `1-6-1-3/` | Pflichtenheft für die Feuerwehrkommission (SRS 1.6.1-3) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `1-6-1-4/` | Pflichtenheft für die Finanzkommission (SRS 1.6.1-4) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `1-6-1-5/` | Pflichtenheft für die Grundstückgewinnsteuerkommission (SRS 1.6.1-5) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `1-6-1-6/` | Pflichtenheft für die Jugendbegleitgruppe (SRS 1.6.1-6) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `1-6-1-7/` | Pflichtenheft für das Stimmbüro (SRS 1.6.1-7) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 October 2026 |
| `1-6-1-8/` | Pflichtenheft für die Tiefbaukommission (SRS 1.6.1-8) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `1-6-1-9/` | Pflichtenheft für die Friedhofskommission (SRS 1.6.1-9) | 2 | as enacted, then each consolidated version: 1 October 2024 to 1 January 2027 |
| `1-6-5/` | Richtlinie über die Bestellung von ständigen Kommissionen (SRS 1.6-5) | 1 | one version (the oldest available), 1 October 2026 |
| `1-7-1/` | Personalreglement für die Behörden und die Mitarbeitenden (SRS 1.7-1) | 1 | as enacted, 1 January 2024 |
| `2-1-1/` | Richtlinie über die Gebühren im Beurkundungswesen (SRS 2.1-1) | 2 | oldest version available, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `4-1-1/` | Reglement über die familien- und schulergänzende Kinderbetreuung (SRS 4.1-1) | 1 | one version (the oldest available), 1 August 2017 |
| `4-1-1-1/` | Richtlinie über die familien- und schulergänzende Kinderbetreuung (SRS 4.1-1.1) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 September 2026 |
| `4-2-1/` | Reglement für die Benutzung von elektronischen Kommunikationsmittel, Internet und E-Mail an den Schulen (SRS 4.2-1) | 1 | as enacted, 1 January 2008 |
| `4-2-2/` | Reglement über den Schulzahnarzt-Dienst (SRS 4.2-2) | 1 | as enacted, 1 August 2021 |
| `4-2-2-1/` | Richtlinie zum Reglement über den Schulzahnarzt-Dienst (SRS 4.2-2.1) | 1 | as enacted, 1 August 2021 |
| `4-2-3/` | Schul- und Disziplinarordnung der Schule Steinhausen (SRS 4.2-3) | 1 | as enacted, 1 August 2025 |
| `4-3-1/` | Reglement der Musikschule (SRS 4.3-1) | 1 | as enacted, 1 August 2019 |
| `4-3-1-1/` | Richtlinie der Musikschule (SRS 4.3-1.1) | 1 | as enacted, 1 August 2019 |
| `4-7-1/` | Richtlinie für Ehrungen (SRS 4.7-1) | 1 | as enacted, 1 April 2020 |
| `4-7-2/` | Richtlinie über die Benützung der Bibliothek (SRS 4.7-2) | 1 | as enacted, 1 January 2025 |
| `4-8-1/` | Richtlinie zur Förderung der Vereine (SRS 4.8-1) | 2 | oldest version available, then each consolidated version: 28 October 2024 to 1 January 2026 |
| `5-3-1/` | Reglement Notorganisation (SRS 5.3-1) | 1 | as enacted, 12 August 2002 |
| `5-5-1/` | Feuerwehr-Reglement (SRS 5.5-1) | 1 | as enacted, 23 July 2010 |
| `5-5-1-1/` | Richtlinie zum Feuerwehrreglement (SRS 5.5-1.1) | 1 | one version (the oldest available), 1 January 2022 |
| `6-1-1/` | Finanzstrategie der Gemeinde Steinhausen für die Jahre 2021 bis 2028 (SRS 6.1-1) | 1 | as enacted, 21 September 2020 |
| `6-6-1/` | Richtlinie über die Benützung von öffentlichen Anlagen (SRS 6.6-1) | 1 | as enacted, 1 January 2021 |
| `6-6-2/` | Richtlinie über die Benützung und den Betrieb der Sportanlage Feldheim (SRS 6.6-2) | 1 | as enacted, 1 January 2018 |
| `6-6-3/` | Richtlinie über die Benützung und den Betrieb des Musikschulzentrums Sunnegrund 1 (SRS 6.6-3) | 1 | one version (the oldest available), 25 May 2020 |
| `6-6-4/` | Richtlinie über die Benützung und den Betrieb der Sportanlagen Eschfeld (SRS 6.6-4) | 1 | as enacted, 1 January 2018 |
| `6-6-5/` | Richtlinie über die Benützung und den Betrieb der Tennisanlage im Sunnegrund (SRS 6.6-5) | 1 | as enacted, 6 March 2018 |
| `6-6-10-ilb/` | Immobilienleitbild (SRS 6.6-10) | 1 | as enacted, 9 December 2024 |
| `7-1-1-bo/` | Bauordnung der Gemeinde Steinhausen (SRS 7.1-1) | 2 | as enacted, then each consolidated version: 20 September 2005 to 2 April 2026 |
| `7-1-2-parkr/` | Parkplatzreglement der Gemeinde Steinhausen (SRS 7.1-2) | 2 | as enacted, then each consolidated version: 14 February 1995 to 14 April 2026 |
| `7-1-3-gebuhrenordnung-zur-bauordnung/` | Richtlinie über die Baugebühren (SRS 7.1-3) | 1 | as enacted, 2 April 2026 |
| `7-3-1/` | Energieleitbild (SRS 7.3-1) | 1 | as enacted, 8 November 2021 |
| `7-3-2/` | Richtlinie zur Förderung von Massnahmen in den Bereichen Energie und Klima (SRS 7.3-2) | 1 | as enacted, 1 January 2025 |
| `7-3-3/` | Verordnung über die Lärmbekämpfung (SRS 7.3-3) | 1 | as enacted, 18 May 1971 |
| `7-4-3-1-ar/` | Abwasserreglement (SRS 7.4.3-1) | 1 | as enacted, 1 January 2025 |
| `7-4-3-1-1-var/` | Vollzugsverordnung zum Abwasserreglement (SRS 7.4.3-1.1) | 1 | as enacted, 1 January 2025 |
| `7-6-1-rstra/` | Strassenreglement der Gemeinde Steinhausen (SRS 7.6-1) | 2 | as enacted, then each consolidated version: 13 July 1999 to 14 April 2026 |
| `7-6-2/` | Reglement über das Reklamewesen (SRS 7.6-2) | 1 | as enacted, 24 October 2000 |
| `7-7-1/` | Verordnung über das nächtliche Dauerparkieren auf öffentlichem Grund (SRS 7.7-1) | 1 | as enacted, 1 January 2006 |
| `8-2-1/` | Bestattungs- und Friedhofreglement (SRS 8.2-1) | 1 | as enacted, 1 January 2025 |
| `8-2-1-1/` | Richtlinie zum Bestattungs- und Friedhofreglement (SRS 8.2-1.1) | 1 | as enacted, 1 January 2025 |
| `8-3-1/` | Reglement über das Halten von Hunden und die Erhebung der Hundesteuer (SRS 8.3-1) | 1 | as enacted, 1 January 1976 |
| `8-7-1/` | Richtlinie über die Vermietung von Alterswohnungen in der Zentrumsüberbauung Dreiklang (SRS 8.7-1) | 1 | one version (the oldest available), 13 March 2017 |
| `9-4-1/` | Richtlinie über die Erhebung der Beherbergungsabgabe (SRS 9.4-1) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 January 2027 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://steinhausen.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

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

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@steinhausen.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
