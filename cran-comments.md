## Test environments
* Local Windows installation, R 3.4.3
* Ubuntu 14.04 via travis-ci, R 3.4.4 & R 3.5.0
* Win-builder (devel and release)

## R CMD check results
There were no ERRORs, WARNINGs or NOTEs. 

## Additional notes
Only change is removal of one function (get_daily_weather()), which has broken due to changes which have been made to the website it was scraping.
