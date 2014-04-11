# Metalsmith Dev

Simple development helpers for [Metalsmith][1].

## Install

	npm install metalsmith-dev

## Example

	var dev = require("metalsmith-dev");

	dev.watch(metalsmith);
	dev.serve(metalsmith);

## API

### watch(metalsmith, paths)

Watches the Metalsmith source folder for changes and rebuilds.

Arguments:

* metalsmith: An instance of Metalsmith
* paths: A string or array of strings to be watched along with the source folder.

### serve(metalsmith, port)

Statically serves the Metalsmith destination folder.

Arguments:

* metalsmith: An instance of Metalsmith
* port: Port from which to serve site, defaults to 8080

[1]: http://www.metalsmith.io/
