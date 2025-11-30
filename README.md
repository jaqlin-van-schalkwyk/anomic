ANOM
====

R code creating analysis-of-mean decision charts.

Changes from ANOM:
- Substantial refactoring, with goals of matching R ethos and limiting code repetition
    - S3 methods to separate by input class
    - Removed internal function and moved functionality into the general function
    - Slightly changed the structure of the wrapper function to limit instances of anomic_gen()
- Pass ellipsis parameter to ggplot, allowing full use of ggplot parameters
    - Added an internal function to 
- Checked for visual back-compatibility with the previous version
- Added tests using the testthat package, ensuring full test coverage


Use **remotes::install_github("jaqlin-van-schalkwyk/anomic")** to install this package
