
[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active) [![Build Status](https://travis-ci.org/timtrice/HURDAT.svg?branch=develop)](https://travis-ci.org/timtrice/HURDAT) [![codecov](https://codecov.io/gh/timtrice/HURDAT/branch/develop/graph/badge.svg)](https://codecov.io/gh/timtrice/HURDAT)

------------------------------------------------------------------------

[![minimal R version](https://img.shields.io/badge/R%3E%3D-3.4.0-6666ff.svg)](https://cran.r-project.org/) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/HURDAT)](https://cran.r-project.org/package=HURDAT) [![packageversion](https://img.shields.io/badge/Package%20version-0.1.0-orange.svg?style=flat-square)](commits/develop)

------------------------------------------------------------------------

[![Last-changedate](https://img.shields.io/badge/last%20change-2017--05--14-yellowgreen.svg)](/commits/develop)

HURDAT
======

This R package currently aims to reorganize the NOAA HURDAT2 dataset for Atlantic, East Pacific and Central Pacific-basin tropical cyclones and present it in a cleaner format.

The Atlantic basin dataset covers all cyclones that have developed in the Atlantic Ocean. The eastern Pacific datasets cover cyclones in the Pacifc from the United States/Mexico coastlines to -140°W where the cyclone entered what is referred to as the central Pacific basin. The central Pacific basin extends westward to -180°W.

Getting Started
---------------

Please view the vignette 'hurdat':

``` r
vignette("hurdat", package = "HURDAT")
```

### Prerequisites

`HURDAT` does require an active internet connection as data is extracted from online archives.

The following R packages are also currently used for data processing:

-   dplyr (&gt;= 0.4.3)

### Installing

`HURDAT` is currently only available in GitHub. It can be installed using the `devtools` package:

``` r
devtools::install_github("timtrice/HURDAT")
```

Built With
----------

-   [R 3.4.0](https://www.r-project.org/) - The R Project for Statistical Computing

Contributing
------------

Please read [CONTRIBUTING.md](https://gist.github.com/timtrice/f2a4c2a020c87669178dad27e73bfce1) for details on our code of conduct, and the process for submitting pull requests to us.

Versioning
----------

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/timtrice/HURDAT/tags).

Authors
-------

-   **Tim Trice** - *Initial work* - [timtrice](https://github.com/timtrice)

See also the list of [contributors](https://github.com/timtrice/HURDAT/contributors) who participated in this project.

License
-------

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

Acknowledgments
---------------

-   None yet :(
