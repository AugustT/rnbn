# rnbn
------

[![Build Status](https://api.travis-ci.org/ropensci/rnbn.png)](https://travis-ci.org/ropensci/rnbn)
[![Build status](https://ci.appveyor.com/api/projects/status/hcu0r1oaiamkvq1r?svg=true)](https://ci.appveyor.com/project/sckott/rnbn)
[![Project Status: Unsupported – The project has reached a stable, usable state but the author(s) have ceased all work on it. A new maintainer may be desired.](http://www.repostatus.org/badges/latest/unsupported.svg)](http://www.repostatus.org/#unsupported)

DECOMISSIONING
==============

The NBN gateway services which rnbn uses are being stopped in March 2017. At this time rnbn will stop working. We hope to eventually replace rnbn with another r-package that will use the new NBN servies being launched.

For updates on the new package or to contribute plese find more details at: https://github.com/BiologicalRecordsCentre/NBN4R

The details below are kept for archival purposes.

### Installation
----------------

You can install the CRAN version of rnbn by using install.packages:

    install.packages('rnbn')

To install the development version of `rnbn`, it's easiest to use the `devtools` package:

    # install.packages("devtools")
    # NOTE: If you have not installed devtools before you may need to restart you R
    # session before installing to avoid problems

    library(devtools)
    install_github("ropensci/rnbn")

    library(rnbn)

If you have difficulties installing `rnbn` using this method try updating your version of R to the most up-to-date version available. If you still have problems please contact us or use [the issues page](https://github.com/ropensci/rnbn/issues).

### How to use the package
--------------------------

A good starting point is the vignette, once you have installed and loaded the package use the following command to open the vignette.

    vignette('rnbn_vignette')

Once you have read the vignette, the help files for each function should guide you the rest of the way. If you have any questions just get in touch via email or using the [issues page](https://github.com/ropensci/rnbn/issues?state=open).

## Meta

* Please [report any issues or bugs](https://github.com/ropensci/rnbn/issues).
* License: MIT
* Get citation information for `rnbn` in R doing `citation(package = 'rnbn')`

[![ropensci](http://ropensci.org/public_images/github_footer.png)](http://ropensci.org)
