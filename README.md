# CensusScout

https://github.com/dannguyen/censusscout

preliminary notes 

Basically, a lite version of Census Explorer that features:

- Convenient flat-file CSVs and sqlite downloads
- Original csv files from data.census.gov
- helpful lookup tables, e.g. fips
- Topojsons
- Vital statistics

Geolevels of:
- Nation
- Region
- Division
- State
- County
- Congressional District
- CSA
- MSA

AC5 ranges:

- 2006-2010
- 2007-2011
- 2008-2012
- 2009-2013
- 2010-2014
- 2011-2015
- 2012-2016
- 2013-2017
- 2014-2018

Comparisons:

2013 vs 2018


# Documentation

https://www.census.gov/programs-surveys/acs/guidance/comparing-acs-data.html


# Manifest

DP02 Selected Social Chars https://data.census.gov/cedsci/table?q=DP02&hidePreview=false&tid=ACSDP1Y2018.DP02&vintage=2018
DP03 Selected Economic Char https://data.census.gov/cedsci/table?q=DP&tid=ACSDP1Y2018.DP03&hidePreview=false&vintage=2018
DP04 Selected Housing https://data.census.gov/cedsci/table?q=DP&tid=ACSDP5Y2018.DP04&hidePreview=false&vintage=2018
DP05 Demographics
https://data.census.gov/cedsci/table?q=DP&tid=ACSDP5Y2018.DP05&hidePreview=false&vintage=2018


# Examples urls/endpoints

Just nation, divisions, and regions selected:

https://data.census.gov/cedsci/table?q=DP&tid=ACSDP5Y2010.DP05&hidePreview=true&vintage=2018&g=0100000US_0200000US2,1,3,4_0300000US3,6,2,8,1,9,5,4,7


All 20 regions, acs52010:



dp05:
https://data.census.gov/cedsci/table?tid=ACSDP5Y2010.DP05&g=0100000US,.04000.001,.050000,.50011,.160000,.310000,.330000_0200000US2,1,3,4_0300000US3,6,2,8,1,9,5,4,7&hidePreview=true
