## Test environments
* Local Windows installation, R 3.6.1
* Ubuntu 16.04 via travis-ci, R 3.5.3 & R 3.6.1 & R-devel
* Win-builder (devel and release)

## R CMD check results
There were no ERRORs, WARNINGs or NOTEs.

## Additional notes
Only change is removal of one function (get_rugby()), which has broken due to problems with the website it was scraping.
