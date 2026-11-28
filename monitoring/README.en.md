<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Steinhausen only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 08:30 UTC, Steinhausen: systematic collection (steinhausen.tlex.ch): 18 addresses read; 0 added, 0 changed, 0 removed; no change; 2 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Steinhausen: systematic collection (steinhausen.tlex.ch)](https://steinhausen.tlex.ch/) | `<act>/` | daily | 2026-11-28 08:30 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 08:29](checks/2026-11.md#ch-lexwork-steinhausen-city-20261128t082957z) | lexwork-steinhausen-city | 18 | 0 | 0 | 0 | 2 (0) | no change | — |
| [2026-11-28 07:11](checks/2026-11.md#ch-lexwork-steinhausen-city-20261128t071122z) | lexwork-steinhausen-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-28 06:42](checks/2026-11.md#ch-lexwork-steinhausen-city-20261128t064204z) | lexwork-steinhausen-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-27 07:07](checks/2026-11.md#ch-lexwork-steinhausen-city-20261127t070731z) | lexwork-steinhausen-city | 17 | 0 | 0 | 0 | 2 (0) | no change | — |
| [2026-11-26 07:13](checks/2026-11.md#ch-lexwork-steinhausen-city-20261126t071303z) | lexwork-steinhausen-city | 16 | 0 | 0 | 0 | 2 (0) | no change | — |
| [2026-11-25 08:21](checks/2026-11.md#ch-lexwork-steinhausen-city-20261125t082132z) | lexwork-steinhausen-city | 22 | 0 | 0 | 0 | 4 (0) | no change | — |
| [2026-11-24 12:48](checks/2026-11.md#ch-lexwork-steinhausen-city-20261124t124829z) | lexwork-steinhausen-city | 25 | 2 | 0 | 0 | 9 (0) | changes found | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
