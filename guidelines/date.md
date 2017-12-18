---
layout: template1
title: Date
data: date
comments: false
---

{% include guidelines.md %}

**DPLA MAP v4 Usage:** Date value as supplied by Data Provider.

### Access Guidelines

Enter the date of creation at the most specific level available.

Enter the date in [Extended Date/Time Format](http://www.loc.gov/standards/datetime/iso-tc154-wg5_n0039_iso_wd_8601-2_2016-02-16.pdf). Only enter valid EDTF dates.

__EXAMPLES__

EDTF | Natural language
------|---------
1975-01-07  | January 7, 1975
1945? | 1945?
1981~ | approximately 1981
1981% | approximately 1981?
1940~/1950~ | approximately 1940-approximately 1950 (see note below)
1975-23 | Fall 1975
197X | 1970s
19XX | 1900s
1981/1985 | 1981-1985
[1888, 1889, 1891] | 1888, 1889 or 1891
{1888, 1889, 1891} | 1888, 1889 and 1891

Early, late, and mid dates

Where Y's represent the century or decade:

Dates | EDTF | Natural language | Example
------|------|-----------------|---------
Early __century__ | YY00~/YY30~ | approximately YY00-approximately YY30 | Early 18th century = 1700~/1730~ = approximately 1700-approximately 1730
Mid-century | YY30~/YY70~ | approximately YY30-approximately YY70 | Mid 19th century = 1830~/1870~ = approximately 1830-approximately 1870
Late century | YY70~/YY99~ | approximately YY70-approximately YY99 | Late 20th century = 1970~/1999~ = approximately 1970-approximately 1999
Early __decade__ | YYY0~/YYY3~ | approximately YYY0-approximately YYY3 | Early 1940s = 1940~/1943~ = approximately 1940-approximately 1943
Mid-decade | YYY3~/YYY7~ | approximately YYY3-approximately YYY7 | Mid 1950s = 1953~/1957~ = approximately 1943-approximately 1947
Late decade | YYY7~/YYY9~ | approximately YYY7-approximately YYY9 | Early 1940s = 1940~/1943~ = approximately 1947-approximately 1949

__Notes__
- In legacy data, you may see the natual language date "approximately 1920-1930." In EDTF, the "approximately" applies to the year directly following that word, so in this example, 1920 is considered approximate and 1930 is considered a known date. In EDTF, it would be expressed as 1920~/1930. To indicate that the entire range is approximate, you must indicate that each year is approximate, e.g. 1940~/1950~ which means "approximately 1940-approximately 1950."


### Preservation Guidelines
