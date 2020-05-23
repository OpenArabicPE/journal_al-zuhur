---
title: "Readme: Journal *al-Zuhūr"
author: Till Grallert
date: 2019-10-22
---

# An open, collaborative, and scholarly digital edition of Anṭūn al-Jumayyil's monthly journal *al-Zuhūr* (Cairo, 1910--1913)

[![GitHub release](https://img.shields.io/github/release/openarabicpe/journal_al-zuhur.svg)](https://github.com/openarabicpe/journal_al-zuhur/releases)
<!-- DOI needs updating once released -->
<!-- [![DOI](https://zenodo.org/badge/52619834.svg)](https://zenodo.org/badge/latestdoi/52619834) -->

This digital edition of Anṭūn al-Jumayyil's monthly journal *al-Zuhūr* (Cairo, 1910--1913) is part of and follows the principles of [Open Arabic Periodical Editions (OpenArabicPE)](https://openarabicpe.github.io) that were originally developped in the context of [Digital Muqtabas](https://github.com/tillgrallert/digital-muqtabas). The full text of this edition has been transcribed by the anonymous transcribers at [*al-maktaba al-shamela*](http://shamela.ws/index.php/book/36534). Digital facsimiles are available from [*arshīf al-majallāt ...*][sakhrit]<!--  (formerly archive.sakhrit.co) --> and in high-resolution from the [University of Bonn](http://digitale-sammlungen.ulb.uni-bonn.de/urn/urn:nbn:de:hbz:5:1-90222), which also serves through IIIF.

It appeared that the page breaks from *al-maktaba al-shamela* correspond to the printed copy. We have therefore added the relevant mark-up for page beginnings (`<pb ed="print" n="123"/>`) and an `<facsimile>` element containing links to the digital facsimiles at [*arshīf al-majallāt*][sakhrit]. The boilerplate view, therefore, displays both facsimiles and the digital text.

If you just want to browse the edition in a more human-readable view, start [here](https://openarabicpe.github.io/journal_al-zuhur/tei/oclc_1034545644-i_1.TEIP5.xml). All bibliographic metadata will soon be available as part of [OpenArabicPE's public Zotero group](https://www.zotero.org/groups/904125/openarabicpe/items/).


# notes
## to do

1. mark up articles in sections:[^1]
    - **done** في حدائق العرب
        + note: this did not work reliably (e.g. 2(5)), or I did assume that there was only a single article in this section
    - **done** في جنائن الغرب
    - أزهار وأشواك
    - في رياض الشعر
    - ثمرات المطابع
        + articles commence with a short string followed by a hyphen in the first paragraph
2. mark-up toponyms in bylines
3. heads: multi-line heads are currently commonly only catching the first line


[sakhrit]: http://archive.alsharekh.org/newmagazineYears/40
[^1]: there are some sections which only have a single article per issue