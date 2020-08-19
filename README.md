# DOCCS COVID-19 Testing Data

Contents

* `reports.csv` contains info from each DOCCS COVID-19 testing report. The columns `TESTED`, `POSITIVE`, `NEGATIVE`, and `PENDING` contain counts of all tests conducted by the corresponding `DATE` in each `FACILITY` and their results. The numbers in the `DECEASED` and `RECOVERED` columns are included in the count for `POSITIVE`.
	* For example, this file shows that as of `2020-07-25`, DOCCS has seen 604 COVID-19 positives.
* `changes.csv` documents how counts in `reports.csv` changed between reports, indicated by `START` and `END` dates.
	* For example, this file shows that between `2020-07-22` and `2020-07-23`, Green Haven reported a death from COVID-19.
	* The folder `pdf` contains all daily reports by DOCCS that were used to create `changes.csv` AND `reports.csv`.

Data Notes

* DOCCS first reported facility-specific testing data on April 20, 2020.
* All data comes from reports by [NY DOCCS](https://doccs.ny.gov/doccs-covid-19-report).
* [DOCCS](https://doccs.ny.gov/doccs-covid-19-report) reports that "incarcerated individuals are tested when exhibiting symptoms and after a medical evaluation is conducted" or as deemed necessary by state and local health officials.
* In July, [3,922 tests](https://auburnpub.com/news/local/govt-and-politics/cuomo-small-percentage-of-older-ny-prison-inmates-test-positive-for-covid-19/article_66e96029-e6e9-5b66-8d2a-698b6e860201.html) were conducted on all incarcerated people 55 and older.
* No data was published between July 8th and July 22nd. New data [was released](https://auburnpub.com/news/local/govt-and-politics/cuomo-small-percentage-of-older-ny-prison-inmates-test-positive-for-covid-19/article_66e96029-e6e9-5b66-8d2a-698b6e860201.html) on July 23rd after criticism from the Release Aging People in Prison Campaign.
