# goatCLI changelog

## v0.2.1

* CHANGED: internal changes on how output formatters work
* CHANGED: output filters are now used for probes, anchors and measurements too
* CHANGED: adapt code to goatAPI v0.2.1 async results

## v0.2.0

* NEW: support for downloading results of a measurement
  * with start time, stop time and probe filters
  * with option to get "latest" only
* NEW: support for processing results from an already downloaded file
* NEW: preliminary support for output processors
  * some, most: basic properties of the results
  * native: a native-looking output (i.e. similar to ping, traceroute, ...)
  * dnsstat: a simple DNS result summariser
* CHANGED: minor verbose output format changes
* CHANGED: output for "some" and "most" moved here from goatAPI

## v0.1.0

* support listing probes, anchors, measurements with virtually all filtering options
* support counting items, retrieveing all matching ones or just a specific one by ID
* support for a (primitive) configuration file (~/.config/goat.ini) and command line flags
* support for "list_measurements" API key via the config file
