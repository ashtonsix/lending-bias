Lending Bias Data
=================

Original data was obtained from the following sources:

* County census estimates (2015): [US Census Bureau](https://www2.census.gov/programs-surveys/popest/datasets/2010-2015/counties/asrh/)
* Loans / loan rejections (2015): [Lending Club](https://www.lendingclub.com/info/download-data.action)
* County to ZIP dictionary (2015): [US Department of Housing and Urban Development](https://www.huduser.gov/portal/datasets/usps_crosswalk.html)
* County map (2010): [WikiMedia Commons](https://commons.wikimedia.org/wiki/File:Usa_counties_large.svg)

The footer of `loans.csv` was removed manually (`skipfooter` is not supported by Pandas' C engine).

`stats.csv` (generated) is the subject of this analysis, see `stats.names.txt` for details.
