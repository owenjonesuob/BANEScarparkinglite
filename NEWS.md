BANEScarparkinglite has retired (2020-04-13)
========================================

It's been a blast, but all good things must come to an end.

See README.md for more details.




BANEScarparkinglite v0.1.3 (Release date: 2019-08-05)
=====================================================

Bugfixes:

* Bath Hacked datastore API endpoint updated

Deletions:

* Bath Rugby's website seems to be having some trouble displaying information about results from past seasons - so `get_rugby` has been removed until something can be done about it...




BANEScarparkinglite v0.1.2 (Release date: 2018-06-30)
=====================================================

Deletions:

* Changes to the Wunderground website have left `get_daily_weather` floundering - it has been removed until a suitable alternative can be found!





BANEScarparkinglite v0.1.1 (Release date: 2018-01-20)
=====================================================

Additions:

* `get_daily_weather` now creates a weather table for any given date range (no longer limited to retrieving 398 records in one go...) and the format of this table is nicer than before (better column names etc.)
* Added code tests for all main functionality (and added `covr` reporting to Travis)
* Added NEWS file to keep track of changes

Bugfixes:

* Minor usability improvements for several functions





BANEScarparkinglite v0.1.0 (Release date: 2017-08-27)
=====================================================

Additions:

* Initial release; all functionality of main BANEScarparking package, without the attached datasets
* Travis CI is being used to check the build
