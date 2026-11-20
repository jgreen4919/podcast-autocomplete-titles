# Podcast title lists for survey autocomplete

These are English-language podcast titles, one per line, best-ranked first. They are used to suggest titles in a survey's open-ended podcast questions.

- `titles_tier1.txt` has about 400k titles and is loaded first.
- `titles_tier2.txt` has about 270k long-tail titles and is loaded afterward.

Titles come from the [Podcast Index](https://podcastindex.org) public data dump of 2026-11-14. Starting with `v2`, they also include a curated research list of about 7,600 shows, some under older or alternate names. Podcast Index's [terms of service](https://github.com/Podcastindex-org/terms-of-service) permit redistributing that dump. Titles appear as their feeds publish them.

Pinned versions are served through jsDelivr:

```
https://cdn.jsdelivr.net/gh/jgreen4919/podcast-autocomplete-titles@v2/titles_tier1.txt
https://cdn.jsdelivr.net/gh/jgreen4919/podcast-autocomplete-titles@v2/titles_tier2.txt
```
