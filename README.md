Satorix jq buildpack
====================

Use [jq](https://stedolan.github.io/jq/) in a buildpack compatible app.

Requires
--------

64bit Linux

Usage
-----

Add the buildpack to a `.buildpacks` configuration in the root of the application directory to install `jq` for the application to utilize.

Configuration
-------------

* Defaults to 64-bit Linux binary jq version 1.5 for Heroku runtime
* `JQ_BIN_URL` set the source URL for the jq binary
* Expects a `*.zip` file with just the binary file inside