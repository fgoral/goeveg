# goeveg 0.5.1
- fixes in references and value tags

# goeveg 0.5.0
- removal of functions synsort() and syntable() due to unsolved incompatibilities

# goeveg 0.4.4
- Added lwd argument to ordiselect

# goeveg 0.4.3
- Added xlim & ylim arguments to racurve
- Added na.rm argument to ordiselect

# goeveg 0.4.2
- Small fixes, fixed package dependencies
- Spell checking

# goeveg 0.4.1
- Added new functions for calculation and sorting of synoptic tables: syntable() and synsort()

# goeveg 0.3.3
- Fixes in documentation

# goeveg 0.3.2
- Merged specresponses()/specresponse() into one single function specresponse()
- Better selection method of polynomial GLMs and GAMs in specresponse()

# goeveg 0.3.1

- Fixed use of external functions (gam, rdist)
- max. of 3 polynomials in automatic GLM selection of specresponse()

# goeveg 0.3.0

- Fixed and renewed function specresponse()/specresponses(): now works also with NMDS, includes zero values and is based on presence/absence data (logistic regression). Instead of cubic smoothing splines the function now uses GLMs/GAMs.

# goeveg 0.2.0

- Added functionality to use frequencies in racurve()
- Added functionality to label species in racurve()
- New (invisible) output in racurve()
- Package checked and tested on OS X

# goeveg 0.1.6

- First CRAN release
