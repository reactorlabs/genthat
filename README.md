> This is old version. Proper genthat can be found here: [https://github.com/PRL-PRG/genthat](https://github.com/PRL-PRG/genthat).

genthat - test case generation for R
=====

[![Build Status](https://travis-ci.org/reactorlabs/genthat.svg?branch=master)](https://travis-ci.org/reactorlabs/genthat) 
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/reactorlabs/genthat?branch=master&svg=true)](https://ci.appveyor.com/project/reactorlabs/genthat)
[![Coverage Status](http://codecov.io/github/reactorlabs/genthat/coverage.svg?branch=master)](http://codecov.io/github/reactorlabs/genthat?branch=master) 
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/genthat)](http://cran.r-project.org/package=genthat)

*genthat* is a framework for unit tests generation from source code and for test execution, and filtering of test cases based on C code coverage using `gcov` and R code coverage using `covr`.

# Installation
Even thought the development of the package started sometime ago it is still rather experimental and no available from CRAN release yet. However, that is one of the near future plans to have a stable version and release it through CRAN.

It can be installed easily using the `devtools` package:

```r
library(devtools)
install_github('reactorlabs/genthat')
```

Or download the sources and build manually. If you're running R on Windows, you need to install Rtools.

Usage
-----

See the provided vignettes (basic usage and manual usage) for information on how to use genthat with your packages, or code. 
