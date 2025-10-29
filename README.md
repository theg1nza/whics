# whics
WHICS stands for **W**hitelist of **H**uman **I**nformation for **C**omputer **S**cience and is intended to be a whitelist containing only human-made and human-written articles.

## Why make WHICS?
In the last several years, the world at large was introduced to generative artifical intelligence models capable of seemingly intelligent output. However, that output is devoid is human flavour, debate, precision and accuracy.  
  
Since using those models has gotten very easy, many folks have taken to taking up top search results for a given query with generated content, and monetizing it with ads. On top of being very problematic from a creative standpoint, it (importantly!) robs the computer science community of real discussions and of soulful articles written by humans, both are which are paramount to breeding and fueling continued interest in the field. WHICS aims to give us back access to human knowledge.

## How to use WHICS?
WHICS is available under the GPLv3 license, which means you have to disclose its source code (or link to it, i.e. to this repo). WHICS is formatted into CSV (where the separator is the comma) and available in `whics.csv`.

## WHICS' design
#### Column design
The first line of `whics.csv` is the columns' titles. Here is a snippet of the file, in a table format:

| `id` | `name` | `url` | `description` | `tier` | `dateadded` | `datelastmodified` | `author` | `reason` |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | wikipedia | https://www.wikipedia.org/ | The free encyclopedia | 1 | 2025-10-29T14:48:34+00:00 | 2025-10-29T14:48:34+00:00 | theg1nza | |
