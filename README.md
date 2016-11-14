# simple-breakpad-server

Simple collecting server for crash reports sent by
[google-breakpad](https://code.google.com/p/google-breakpad/).


## Features

* No requirement for setting up databases or web servers.
* Collecting crash reports with minidump files.
* Simple web interface for viewing translated crash reports.

## Run

* `npm install .`
* `grunt`
* Put your breakpad symbols under `pool/symbols/PRODUCT_NAME`
* `node lib/app.js`

## TODO

* endpoint to delete crash reports
* store minidumps in database
* add UI
* group and filter crash reports
* documentation
* download custom files
