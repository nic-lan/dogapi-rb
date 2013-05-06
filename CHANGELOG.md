Changes
=======

# 1.8.0 / 2013-07-16
* Add an API for interacting with Screenboards

# 1.7.1 / 2013-06-23
* Add an API for inviting users
* Add an API for taking graph snapshots
* Fix bug in capistrano integration with logging of nil (thanks [@arielo][])

# 1.7.0
* Not released.

# 1.6.0 / 2013-02-19
* Support for setting `source` type when submitting host tags

# 1.5.2 / 2013-02-13
* Fix a bug in hashing the Event object when the instance variables are symbols.

# 1.5.0 / 2012-11-06
* Alerting API

# 1.4.3
* Fix bug with capistrano integration for capistrano 2.13.5 (thanks [@ansel1][])

# 1.4.2
* Added missing dashboards endpoint.

# 1.4.1
* Fixed searching for events with tags.

# 1.4.0
* Added support for the dashboard, search and comment API endpoints.

# 1.3.6
* Small fix for capistrano integration

# 1.3.4
* Various bug fixes (event.to_hash, md5 import, capistrano lambda roles)

# 1.3.3
* Bug fix for submitting counters

# 1.3.2
* Support an aggregation key to aggregate events together

# 1.3.1
* Metrics can be counters, rather than just gauges (thanks to [@treeder][])
* Metrics can be tagged.

# 1.3.0
* Capistrano integration. See https://github.com/DataDog/dogapi-rb/tree/master/lib/capistrano

# 1.2.x
* You can now manage host tags
* You can now get event details and query the stream in addition to posting events
* Functionality relating to events with a duration has been deprecated
* The underlying clients have been updated to use Datadog's new public HTTP API[https://github.com/DataDog/dogapi/wiki]

# 1.1.x
* You do not need to use environment variables anymore to use the client.

<!--- The following link definition list is generated by PimpMyChangelog --->
[@ansel1]: https://github.com/ansel1
[@arielo]: https://github.com/arielo
[@treeder]: https://github.com/treeder