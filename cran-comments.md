## Release with many extensions to plot functions, and some bug fixes.

----

## Test environments

* local Windows 10 install, R 4.0.2
* Ubuntu (on github actions, devel and release)
* macOS (on github actions, release)
* R-hub (devel and release)

----

## R CMD check results

There were no ERRORs or WARNINGs.

There were 2 NOTES:

  * checking CRAN incoming feasibility ... NOTE    

    Suggests or Enhances not in mainstream repositories: asreml

    - asreml is a commercial R package that is used as one of three alternatives for modeling data.

  * checking package dependencies ... NOTE  
    Package suggested but not available for checking: 'asreml'
    
    - asreml is a commercial R package that is used as one of three alternatives for      modeling data.

