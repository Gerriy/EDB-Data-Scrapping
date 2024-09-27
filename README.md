# EDB-Data-Scrapping
This repository assists data scrapping from HK EDB website

Target site (root site): https://www.edb.gov.hk/en/student-parents/sch-info/sch-search/schlist-by-district

Usage:
Run the notebook Parser.py directly to obtain a school list in excel format

Requirements:
python3
requests
beautifulsoup4
pandas
openpyxl

Issues:
To be tested

Planned Function:
1. Recursive scrapping of 18 districts school list from the root site
2. Filtering by School Type (exclusion of kindergarten, primary schools etc.)
