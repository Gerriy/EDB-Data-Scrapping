# EDB-Data-Scrapping
This repository assists data scrapping from HK EDB website

Target site (root site): https://www.edb.gov.hk/en/student-parents/sch-info/sch-search/schlist-by-district

**Usage:**
1. Run the notebook Parser.ipynb directly to obtain a school list in excel format

**Requirements:**
1. python3
2. requests
3. beautifulsoup4
4. pandas
5. openpyxl

**Issues:**
1. School duplication (due to duplicated records in source html as some school may have multiple campus sites)

**Planned Function:**
1. Recursive scrapping of 18 districts school list from the root site (DONE)
2. Filtering by School Type (exclusion of kindergarten, primary schools etc.) (DONE)
