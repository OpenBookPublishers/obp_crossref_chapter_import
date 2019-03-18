# OBP Crossref chapter import
[![Build Status](https://travis-ci.org/OpenBookPublishers/obp_crossref_chapter_import.svg?branch=master)](https://travis-ci.org/OpenBookPublishers/obp_crossref_chapter_import) [![Release](https://img.shields.io/github/release/OpenBookPublishers/obp_crossref_chapter_import.svg?colorB=58839b)](https://github.com/OpenBookPublishers/obp_crossref_chapter_import/releases) [![License](https://img.shields.io/github/license/OpenBookPublishers/obp_crossref_chapter_import.svg?colorB=ff0000)](https://github.com/OpenBookPublishers/obp_crossref_chapter_import/blob/master/LICENSE)

Find missing chapters and/or chapter identifiers in Crossref and submit new findings to the identifier translation service.

## Run via crontab
```
0 13,21 * * * docker run --rm --name "chapter_importer" --env-file /path/to/config.env openbookpublishers/obp_crossref_chapter_import
```
