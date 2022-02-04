---
title: "Readme: Journal *al-Zuhūr*"
author: Till Grallert
date: 2022-02-05
ORCID: orcid.org/0000-0002-5739-8094
---

<!-- DOI needs updating once released -->
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3580606.svg)](https://doi.org/10.5281/zenodo.3580606)
[![GitHub release](https://img.shields.io/github/release/openarabicpe/journal_al-zuhur.svg)](https://github.com/openarabicpe/journal_al-zuhur/releases)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/openarabicpe/journal_al-zuhur/graphs/commit-activity)
![Commit activity](https://img.shields.io/github/commit-activity/m/openarabicpe/journal_al-zuhur)
![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/openarabicpe/journal_al-zuhur/latest)
![GitHub last commit](https://img.shields.io/github/last-commit/openarabicpe/journal_al-zuhur)
![GitHub contributors](https://img.shields.io/github/contributors/openarabicpe/journal_al-zuhur)

# An open, collaborative, and scholarly digital edition of Anṭūn al-Jumayyil's monthly journal *al-Zuhūr* (Cairo, 1910--1913)


This digital edition of Anṭūn al-Jumayyil's monthly journal *al-Zuhūr* (Cairo, 1910--1913) is part of and follows the principles of [Open Arabic Periodical Editions (OpenArabicPE)](https://openarabicpe.github.io) that were originally developped in the context of [Digital Muqtabas](https://github.com/openarabicpe/journal_al-muqtabas). The full text of this edition has been transcribed by the anonymous transcribers at [*al-maktaba al-shamela*](http://shamela.ws/index.php/book/36534). The transcription and our edition comprises 40 issues but only 39 issues from vol.1(1) until vol.4(8) could be found in material copies and digital facsimiles. The introduction from the Dār Ṣādir reprint, upon which this transcription is most likely based, does not comment on this discrepancy.
Digital facsimiles are available from the following sources:

- [*arshīf al-majallāt ...*][sakhrit]<!--  (formerly archive.sakhrit.co) --> and
- in high-resolution from the [University of Bonn][bonn], which also serves through IIIF.
    + vol.s 1--4 from the University of Tübingen
    + The problem with Bonn's implementation is that images are not consecutively numbered. One has to look up the link to each image in the IIIF manifest and cannot compute them.
    + The second problem is that page numbers are not part of the IIIF manifest.
        * vol. 1: <https://digitale-sammlungen.ulb.uni-bonn.de/i3f/v20/4900431/manifest>
        * vol. 2: <https://digitale-sammlungen.ulb.uni-bonn.de/i3f/v20/4900432/manifest>
        * vol. 3: <https://digitale-sammlungen.ulb.uni-bonn.de/i3f/v20/4900433/manifest>
        * vol. 4: <https://digitale-sammlungen.ulb.uni-bonn.de/i3f/v20/4900434/manifest>
- Hathitrust: [Reprint! catalogued as published by al-Hayʾah al-Miṣrīyah al-ʻĀmmah lil-Kitāb, 1997-2000](https://catalog.hathitrust.org/Record/100162849)
    + [Harvard](https://catalog.hathitrust.org/Record/100162849): complete
    + [Ohio State University](https://catalog.hathitrust.org/Record/100162849): complete
    + [Cornell University](https://catalog.hathitrust.org/Record/100162849): complete
    + [University of California](https://catalog.hathitrust.org/Record/102460641): complete
- Hathitrust: original
    + [Princeton](https://catalog.hathitrust.org/Record/009012438): vol. 3

It appeared that the page breaks from *al-maktaba al-shamela* correspond to the printed copy. We have therefore added the relevant mark-up for page beginnings (`<pb ed="print" n="123"/>`) and an `<facsimile>` element containing links to the digital facsimiles at [*arshīf al-majallāt*][sakhrit] and [Translatio Bonn][bonn]. The boilerplate view, therefore, displays facsimiles and the digital text.

If you just want to browse the edition in a more human-readable view, start [here](https://openarabicpe.github.io/journal_al-zuhur/tei/oclc_1034545644-i_1.TEIP5.xml). All bibliographic metadata is available as part of [OpenArabicPE's public Zotero group](https://www.zotero.org/groups/904125/openarabicpe/items/).


# notes
## to do

1. mark up articles in sections:[^1]
    - **done** في حدائق العرب
        + note: this did not work reliably (e.g. 2(5), 2(1)), or I did assume that there was only a single article in this section
    - **done** في جنائن الغرب
    - أزهار وأشواك
    - في رياض الشعر
    - ثمرات المطابع
        + articles commence with a short string followed by a hyphen in the first paragraph
2. mark-up toponyms in bylines
3. heads: multi-line heads are currently commonly only catching the first line
4. **done** mastheads
5. mark-up bibliographic references in the section "ثمرات المطابع"


[sakhrit]: http://archive.alsharekh.org/newmagazineYears/40
[bonn]: http://nbn-resolving.de/urn:nbn:de:hbz:5:1-90222

[^1]: there are some sections which only have a single article per issue