---
layout: page
title: Joind.in API Documentation
---

# Languages

It is possible to fetch a read-only list of languages, or a single language

## Language Format

~~~~
languages:
    4:
        name: Espanol
        code: es
        uri: http://api.dev.joind.in/v2.1/languages/6
        verbose_uri: http://api.dev.joind.in/v2.1/languages/6?verbose=yes
meta:
    count: 1
    total: 1
    this_page: http://api.dev.joind.in/v2.1/languages?start=0&resultsperpage=20
~~~~

## Talk Comment Verbose Format

Is exactly the same as the ordinary format.

## Language Data Fields

The fields available for talk comments:

*  ``code``: Language shortcode (non-standard)
*  ``name``: Name, e.g. "Polish"

## Talk Comment Hypermedia

*  ``uri``: Where to find this individual record
*  ``verbose_uri``: Where to find a more detailed representation of this record
