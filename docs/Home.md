**Crossfilter** is a JavaScript library for exploring large multivariate datasets in the browser. Crossfilter supports extremely fast (<30ms) interaction with coordinated views, even with datasets containing a million or more records; we built it to power analytics for Square Register, allowing merchants to slice and dice their payment history fluidly.

Since most interactions only involve a single dimension, and then only small adjustments are made to the filter values, incremental filtering and reducing is significantly faster than starting from scratch. Crossfilter uses sorted indexes (and a few bit-twiddling hacks) to make this possible, dramatically increasing the perfor­mance of live histograms and top-K lists. Crossfilter is available under the [Apache License](/square/crossfilter/blob/master/LICENSE).

## Status

Crossfilter is **not under active development, maintenance or support by Square**, or its original author Mike Bostock, or the current contributors (Jason Davies, Tom Carden). We still welcome genuine bug-fixes and PRs but consider the current API and feature-set (~1.3.12) essentially complete.

A new [Crossfilter Organization](https://github.com/crossfilter) has been created on Github and is home to an [actively maintained fork of Crossfilter](https://github.com/crossfilter/crossfilter). This version is already used by popular library [DC.js](https://dc-js.github.io/dc.js/) and the contributors are working on improved APIs and performance improvements for current Javascript VMs. There are no plans to merge or publish new versions under the original Square repository or npm package.

## Resources

* [Introduction](http://square.github.com/crossfilter/)
* [API Reference](/square/crossfilter/wiki/API-Reference)
* [Release Notes](/square/crossfilter/releases)
* [Support](http://stackoverflow.com/questions/tagged/crossfilter)

## Contributing

Want to add support for a new backend or visualization? We'd love for you to participate in the development of Crossfilter. Before we can accept your pull request, please sign our [Individual Contributor License Agreement][1]. It's a short form that covers our bases and makes sure you're eligible to contribute. Thank you!

  [1]: https://spreadsheets.google.com/spreadsheet/viewform?formkey=dDViT2xzUHAwRkI3X3k5Z0lQM091OGc6MQ&ndplr=1