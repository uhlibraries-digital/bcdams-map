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

__Notes__
- In legacy data, you may see the natual language date "approximately 1920-1930." In EDTF, the "approximately" applies to the year directly following that word, so in this example, 1920 is considered approximate and 1930 is considered a known date. In EDTF, it would be expressed as 1920~/1930. To indicate that the entire range is approximate, you must indicate that each year is approximate, e.g. 1940~/1950~ which means "approximately 1940-approximately 1950." 


### Preservation Guidelines
