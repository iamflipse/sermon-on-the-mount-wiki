# About and Sources

## What is here

- **The Bible text:** all 111 verses of Matthew 5–7 (48 + 34 + 29), in two public-domain translations, published in full.
- **The commentary:** 27 passage pages written as summaries, key ideas, questions and short quotes (each under about 30 words) from Jordan B. Peterson's lecture series on the Sermon on the Mount. The full lecture transcript is **not** published here.

## Translations

| Translation | Edition | Source | Licence |
|---|---|---|---|
| King James Version (KJV) | Standardised text of 1769, as distributed by eBible.org (Crosswire Bible Society) | <https://ebible.org/Scriptures/eng-kjv_vpl.zip> (file `eng-kjv_vpl.txt`, eBible.org edition dated 2026-11-09) | Public domain outside the United Kingdom. In the UK the KJV is under Crown letters patent; Cambridge University Press, Oxford University Press and Collins hold printing rights there. |
| World English Bible (WEB) | 2020 stable text | <https://ebible.org/Scriptures/eng-web_vpl.zip> (file `eng-web_vpl.txt`) | Public domain. "World English Bible" is a trademark of eBible.org; the text here is unchanged. |

Both were downloaded on 2026-11-11 in eBible.org's verse-per-line format, which contains the Bible text only (no notes, headings or paragraph marks). Verse counts were checked: Matthew 5 has 48 verses, Matthew 6 has 34 and Matthew 7 has 29 in both files, 111 in total.

Presentation choices: the KJV marks words the translators supplied for sense in brackets; they are shown here in *italics*, as printed KJV Bibles do. The KJV paragraph mark (¶) is dropped. The WEB text is reproduced exactly, including its quotation marks. Verses marked † are not read aloud in the lecture (see the [verse map](verse-map.md)).

## The lecture

- **Speaker:** Jordan B. Peterson, lecture series on the Sermon on the Mount, delivered over four days (Day 1: Matthew 5:1–16; Day 2: 5:17–48; Day 3: Matthew 6; Day 4: Matthew 7). Peterson reads from the King James Version.
- **Transcript:** a private transcript of about 80,845 words, kept in a local study wiki (`~/wikis/sermon-on-the-mount/`, file `source/sermon_full.txt`). That wiki splits the transcript into 50 contiguous sections in lecture order, each with a summary, key ideas, exact quotes with word positions, and questions. Its coverage audit confirms the 50 sections cover every word with no gaps or overlaps.
- **How this wiki was made from it:** the 50 sections were merged into 27 passage pages that follow the sermon's verse order. Four sections (19, 20, 31, 34) cross a passage boundary and are split between two pages. The "Peterson's reading" text on each page is a new plain-language summary; key ideas and questions come from the section notes; quotes are copied exactly from the transcript and limited to short excerpts. Word positions ("about word N") count words from the start of the transcript and are approximate.
- **Gaps:** five verses are never read aloud or discussed on their own: 5:9, 5:12, 5:45, 7:8 and 7:18. See the [verse map](verse-map.md).

## Caveats

The commentary is a reader's summary of a lecture, not Peterson's own words except inside quotation marks. It reflects his interpretation of the text, which is psychological rather than doctrinal. For his full argument, go to the lectures themselves.

## Build

This site is built with [mdBook](https://rust-lang.github.io/mdBook/) and served from the `gh-pages` branch of [iamflipse/sermon-on-the-mount-wiki](https://github.com/iamflipse/sermon-on-the-mount-wiki).
