---
layout: post
title: The Suśruta Project - 2025 Annual Report on Technical Infrastructure
author: Dominik Wujastyk and Claude AI
date: 2026-08-24
description: annual report
tags: SuśrutaProject annual_report
---

_Prepared from the public record of the GitHub organization [sushrutaproject1](https://github.com/sushrutaproject1), the project website [sushrutaproject1.github.io](https://sushrutaproject1.github.io/), Zenodo, and the INDOLOGY mailing list. Covers activity from January 1 to December 31, 2025. Compiled by Claude AI._

## Overview

2025 was a transition year for the Suśruta Project. It marked the formal close of "The Suśruta Project 1.0" (2020–2024) — the SSHRC-funded study of the palm-leaf manuscript MS Kathmandu KL 699 (878 CE) and related witnesses of the _Suśrutasaṃhitā_ — and the launch of its successor, "The Compendium of Suśruta in Time and Space: Mapping a Medical Tradition" (2025–2029). Both phases are led by Dominik Wujastyk (University of Alberta).

## Major achievements

**New five-year grant secured.** SSHRC awarded Insight Grant 435-2025-0604, funding "Mapping a Medical Tradition" from 2025 through 2029, based at the University of Alberta. This is the project's principal 2025 milestone: it converts the completed Phase 1 diplomatic transcription work into a funded program of critical editions, translations, and comparative study of the text's transmission across South Asia, China, and Southeast Asia. The successor project maintains its own site and GitHub presence at sushrutaproject2.github.io.

**Phase 1 edition brought to completion and re-archived.** On May 15, 2025 the _Sushrutasamhita_Saktumiva1_ repository (the critical edition and its apparatus) reached release v.6.1, "Completed IIIF pointers for all witnesses" — every manuscript witness in the edition now links live to its IIIF facsimile images. A companion release on May 8, 2025 triggered Zenodo archiving of the repository for long-term preservation. Separately, an earlier edition state (v.4.3, the completed meta-editing of the Sūtrasthāna) was re-archived on Zenodo on April 9, 2025 (DOI 10.5281/zenodo.15184815), noting eleven pull requests of translation and structural work behind that release.

**Web infrastructure consolidated.** In a message to the INDOLOGY list dated December 16, 2025, Wujastyk announced the reorganization of the project's online presence: legacy content moved to sushrutaproject1.github.io (with a further simplification to sushrutaproject.github.io completed in early 2026), the old sushrutaproject.org domain now redirects to the new site, and the successor project's material lives separately at sushrutaproject2.github.io. This tidied up several years of accumulated web infrastructure into a clear two-phase structure.

**Continued editing and translation.** Commit activity through the year shows steady, hands-on philological work rather than large batch imports: individual _adhyāya_ (chapter) files were revised piece by piece — for example passages in Nidānasthāna, Cikitsāsthāna 4.4, and chapters such as 2.1, 3.1, 5.1, 5.8, and 6.65 — interspersed with translation-PDF regenerations, typo fixes, and footnotes (e.g., on the philosophical schools referenced in the text). A concentrated run of this work in early-to-mid December 2025 (at least 39 commits between December 4 and 22) followed what commit messages describe as project seminars and editing sessions. Collaborator Deepro Chakraborty contributed a cleanup of the Nidānasthāna text, merged via pull request #327 on December 20. Routine XML regeneration was handled by an automated "Wujastyk Bot" process rather than by hand.

**Groundwork for a new presentation platform.** A new repository, _Sushrutasamhita_Saktumiva2_, was created to present the same critical edition through "Saktumiva 2.0," an updated version of the project's custom manuscript-collation viewer — the beginning of a migration away from the original Saktumiva 1.0 interface.

## Releases in 2025

| Date                             | Repository                 | Tag   | Note                                                         |
| -------------------------------- | -------------------------- | ----- | ------------------------------------------------------------ |
| May 8, 2025                      | Sushrutasamhita_Saktumiva1 | 6.1   | Release to trigger Zenodo archiving                          |
| May 15, 2025                     | Sushrutasamhita_Saktumiva1 | v.6.1 | IIIF pointers completed for all manuscript witnesses         |
| Apr 9, 2025 (Zenodo record date) | Sushrutasamhita_Saktumiva1 | v.4.3 | Re-archived on Zenodo; 11 PRs of translation/structural work |

## Repositories active during the year

The sushrutaproject1 organization currently comprises five public repositories: _Sushrutasamhita_Saktumiva1_ (the main critical edition, TEI XML/TeX), the new _Sushrutasamhita_Saktumiva2_ (edition on the updated platform), _[sushrutaproject1.github.io](https://sushrutaproject1.github.io)_ (the project website), and a _.github_ profile repository. All of the recorded 2025 activity above falls within the first two.

## A note on the data

This report draws on what GitHub's public pages and unauthenticated API allow without login credentials. Release, Zenodo, and mailing-list dates are exact. Commit figures, however, are drawn from spot samples (a full quarter and a three-week December window) rather than a complete year-long count, because GitHub's unauthenticated API rate limit was reached repeatedly during research and search/date-filtered pages are blocked to automated fetches by GitHub's own robots.txt. The one complete quarter that could be checked (April–June 2025) recorded 20 commits. Issue and pull-request history for 2025 could not be reliably retrieved for the same reason; PR #327 (merged December 20, 2025) is the one confirmed by name. A GitHub-authenticated review — for instance by connecting a personal access token, or by reviewing the repositories' Insights pages directly in a browser — would allow a complete count.

## Outlook

With Phase 1 archived and consolidated, 2026 activity is likely to concentrate on the newly funded Mapping a Medical Tradition project (sushrutaproject2) and on finishing the migration of the edition to the Saktumiva 2.0 platform.

## Sources

- [sushrutaproject1.github.io](https://sushrutaproject1.github.io/) — project website
- [sushrutaproject2.github.io](https://sushrutaproject2.github.io/) — successor project website
- [github.com/sushrutaproject1](https://github.com/sushrutaproject1) — GitHub organization
- [github.com/sushrutaproject1/Sushrutasamhita_Saktumiva1](https://github.com/sushrutaproject1/Sushrutasamhita_Saktumiva1) — critical edition repository and releases
- [github.com/sushrutaproject1/Sushrutasamhita_Saktumiva2](https://github.com/sushrutaproject1/Sushrutasamhita_Saktumiva2) — Saktumiva 2.0 repository
- [Zenodo record 10.5281/zenodo.15184815](https://zenodo.org/records/15184815) — v.4.3 archive
- [INDOLOGY mailing list, Dec 16, 2025](http://www.mail-archive.com/indology@list.indology.info/msg06131.html) — website restructuring announcement
