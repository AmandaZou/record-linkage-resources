# record-linkage-resources
Resources for tackling record linkage / deduplication / data matching / entity matching problems

_Note: If you're looking for file deduplication software, you're in the wrong place! This page focuses on deduplicating datasets._

_Also note: Nor is this page is not about deduplication software used in backup and storage._

Record linkage attempts to identify duplicate records in messy data. It is a thorny problem faced by a variety of disciplines dealing with real-world entities (most often people).

## Background

### Documents
- Wikipedia pages on [Record Linkage](https://en.wikipedia.org/wiki/Record_linkage) and [Data Deduplication](https://en.wikipedia.org/wiki/Data_deduplication)
- Overview slideshttps://www.umiacs.umd.edu/~getoor/Tutorials/ER_VLDB2012.pdf
- [Dedupe]'s explanation of how their software works: https://dedupe.io/developers/library/en/latest/How-it-works.html

### Talks
- Peter Christen, Record Linkage lectures at ADRC-Scotland: [1](https://www.youtube.com/watch?v=DyGonV7A_EY) [2](https://www.youtube.com/watch?v=dcNTvYDdun0) [3](https://www.youtube.com/watch?v=HAKW5tHVCmw) [4](https://www.youtube.com/watch?v=4Iv5axrAWqQ) (2015)
- Mike Mull, The Art and Science of Data Matching: https://www.youtube.com/watch?v=Y-nYEOgq3YE (2015)
- Rhydwyn Mcguire, Join for real life: https://www.youtube.com/watch?v=cEcVIjyHfiQ (2013)
- Andrew Rowe, Big Data Deduplication and Data Matching using Python: https://www.youtube.com/watch?v=Z6mlvrYEYnk (2013)

### Books
- Peter Christen, _Data Matching_: http://www.springer.com/us/book/9783642311635
- Thomas N. Herzog, Fritz J. Scheuren and William E. Winkler, _Data Quality and Record Linkage Techniques_: http://www.springer.com/us/book/9780387695020

## Free software
(last updated, stars)

### Python
- Dedupe: https://github.com/dedupeio/dedupe (2017, 1,413)
- RLTK: https://github.com/usc-isi-i2/rltk/ (2017, 13)
- Febrl: https://sourceforge.net/projects/febrl/ (2013)

### Java
- Duke: https://github.com/larsga/Duke (2016, 469)
- JedAI: https://github.com/scify/JedAIToolkit (2017, 12)
- LSHDB: https://github.com/dimkar121/LSHDB (2017, 9)
- FRIL: http://fril.sourceforge.net/ (2011) (Windows binary available)

### R
- RecordLinkage: https://r-forge.r-project.org/projects/recordlinkage/ https://cran.r-project.org/web/packages/RecordLinkage/index.html
- fastLink: https://github.com/kosukeimai/fastLink

### Other
- OpenRecLink: http://reclink.sourceforge.net/ (2016)
  - C++ with GUI
- Registry Plus™ Link Plus: https://www.cdc.gov/cancer/npcr/tools/registryplus/lp_tech_info.htm (2007)

## Commercial software and solutions
- Data Ladder DataMatch: https://dataladder.com/
- Reifier: http://nubetech.co/
- Dedupe: https://dedupe.io/ (freemium frontend for [Dedupe](https://github.com/dedupeio/dedupe) Python library)
- WinPure Clean and Match: http://www.winpure.com/cleanmatch.html

### For SAS
- (free but requires SAS) The Link King: http://www.the-link-king.com/

## Data Cleaning

### Name Parsers

#### Python
- probablepeople: https://github.com/datamade/probablepeople (2017, 204)
python nameparser library (but purely syntax based)
- Name Parser: https://github.com/derek73/python-nameparser (2017, 232)

#### JavaScript
- parse-full-name: https://github.com/dschnelldavis/parse-full-name (2017, 18)

## Papers
- US Census Bureau research
- [Learnable Similarity Functions and their Application to Record Linkage and Clustering](http://www.cs.utexas.edu/%7Eml/papers/marlin-dissertation-06.pdf) ([via](https://github.com/dedupeio/dedupe))
- [https://www.microsoft.com/en-us/research/publication/improving-entity-resolution-with-global-constraints/ ([via](https://dedupe.io/developers/library/en/latest/Bibliography.html))
- https://arxiv.org/abs/1312.4645 ([via](https://dedupe.io/developers/library/en/latest/Bibliography.html))
- http://people.cs.umass.edu/~mwick/MikeWeb/Publications_files/wick09entity.pdf ([via](https://dedupe.io/developers/library/en/latest/Bibliography.html))
- http://homes.cs.washington.edu/~pedrod/papers/mrdm04.pdf ([via](https://dedupe.io/developers/library/en/latest/Bibliography.html))

## Organizations
- US Census Burea Center for Statistical Research and Methodolgy - Record Linkage: https://www.census.gov/srd/csrm/RecordLinkage.html
- Stanford Entity Resolution Framework: http://infolab.stanford.edu/serf/
- ANU Data Mining and Matching Group https://dmm.anu.edu.au/ https://web.archive.org/web/20160515215747/datamining.anu.edu.au/projects/linkage.html (Archive.org link)

## Misc
- DuDe (framework for comparing record linkage results): https://hpi.de/naumann/projects/data-quality-and-cleansing/dude-duplicate-detection.html
- Datasets to use for evaluating deduplication software: https://hpi.de/naumann/projects/repeatability/datasets.html
- https://www2.vrdc.cornell.edu/news/3/20050420-Record%20Linkage%20Software.pdf

## To Do
- list compatible data sources for software (CSV, SQL DB, JSON, data frame, etc...)
- GUI or not?
- list algorithms and techniques for softare (deterministic, probabalistic, graph, etc...)
- update
