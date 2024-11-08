> devtools::check()
══ Documenting ════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════
ℹ Updating forestdynR documentation
ℹ Loading forestdynR

══ Building ═══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════
Setting env vars:
• CFLAGS    : -Wall -pedantic -fdiagnostics-color=always
• CXXFLAGS  : -Wall -pedantic -fdiagnostics-color=always
• CXX11FLAGS: -Wall -pedantic -fdiagnostics-color=always
• CXX14FLAGS: -Wall -pedantic -fdiagnostics-color=always
• CXX17FLAGS: -Wall -pedantic -fdiagnostics-color=always
• CXX20FLAGS: -Wall -pedantic -fdiagnostics-color=always
── R CMD build ────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
✔  checking for file ‘/home/optimus-prime/Workspace/R/forestdynR/DESCRIPTION’
─  preparing ‘forestdynR’:
✔  checking DESCRIPTION meta-information
─  installing the package to build vignettes
✔  creating vignettes (12.3s)
─  checking for LF line-endings in source and make files and shell scripts (369ms)
─  checking for empty or unneeded directories
─  building ‘forestdynR_0.0.1.tar.gz’
   
══ Checking ═══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════
Setting env vars:
• _R_CHECK_CRAN_INCOMING_USE_ASPELL_           : TRUE
• _R_CHECK_CRAN_INCOMING_REMOTE_               : FALSE
• _R_CHECK_CRAN_INCOMING_                      : FALSE
• _R_CHECK_FORCE_SUGGESTS_                     : FALSE
• _R_CHECK_PACKAGES_USED_IGNORE_UNUSED_IMPORTS_: FALSE
• NOT_CRAN                                     : true
── R CMD check ────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
─  using log directory ‘/tmp/RtmpRd4kqd/file8b6f59f3f4fc/forestdynR.Rcheck’
─  using R version 4.4.2 (2024-10-31)
─  using platform: x86_64-pc-linux-gnu
─  R was compiled by
       gcc (Ubuntu 13.2.0-23ubuntu4) 13.2.0
       GNU Fortran (Ubuntu 13.2.0-23ubuntu4) 13.2.0
─  running under: Ubuntu 24.04.1 LTS
─  using session charset: UTF-8
─  using options ‘--no-manual --as-cran’
✔  checking for file ‘forestdynR/DESCRIPTION’
─  checking extension type ... Package
─  this is package ‘forestdynR’ version ‘0.0.1’
─  package encoding: UTF-8
✔  checking package namespace information
✔  checking package dependencies (809ms)
✔  checking if this is a source package ...
✔  checking if there is a namespace
✔  checking for executable files ...
✔  checking for hidden files and directories
✔  checking for portable file names
✔  checking for sufficient/correct file permissions
✔  checking whether package ‘forestdynR’ can be installed (9.4s)
✔  checking installed package size ...
✔  checking package directory ...
✔  checking for future file timestamps (1.3s)
✔  checking ‘build’ directory ...
✔  checking DESCRIPTION meta-information ...
✔  checking top-level files
✔  checking for left-over files
✔  checking index information ...
─  checking package subdirectories ...Warning: program compiled against libxml 210 using older 209 (479ms)
    OK
✔  checking code files for non-ASCII characters ...
✔  checking R files for syntax errors ...
✔  checking whether the package can be loaded (2.8s)
✔  checking whether the package can be loaded with stated dependencies (2.9s)
✔  checking whether the package can be unloaded cleanly (2.8s)
✔  checking whether the namespace can be loaded with stated dependencies (2.9s)
✔  checking whether the namespace can be unloaded cleanly (2.8s)
✔  checking loading without being on the library search path (3.1s)
✔  checking dependencies in R code (6.2s)
✔  checking S3 generic/method consistency (3.2s)
✔  checking replacement functions (2.9s)
✔  checking foreign function calls (3.1s)
─  checking R code for possible problems ... [12s/13s] OK (13s)
✔  checking Rd files ...
✔  checking Rd metadata ...
✔  checking Rd line widths ...
✔  checking Rd cross-references ...
✔  checking for missing documentation entries (3s)
✔  checking for code/documentation mismatches (9.1s)
✔  checking Rd \usage sections (3s)
✔  checking Rd contents ...
✔  checking for unstated dependencies in examples ...
✔  checking contents of ‘data’ directory ...
✔  checking data for non-ASCII characters ...
✔  checking LazyData
✔  checking data for ASCII and uncompressed saves ...
✔  checking installed files from ‘inst/doc’ ...
✔  checking files in ‘vignettes’ ...
✔  checking examples (7.4s)
✔  checking for unstated dependencies in ‘tests’ ...
─  checking tests ...
✔  Running ‘testthat.R’ (3.3s)
✔  checking for unstated dependencies in vignettes ...
✔  checking package vignettes ...
✔  checking re-building of vignette outputs (3.5s)
✔  checking for non-standard things in the check directory ...
✔  checking for detritus in the temp directory
   
   
── R CMD check results ────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────── forestdynR 0.0.1 ────
Duration: 1m 29.9s

0 errors ✔ | 0 warnings ✔ | 0 notes ✔
