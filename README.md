# lmeSplines
 lmeSplines R package (Version: 1.1-10) downloaded from CRAN on April 10, 2022.
 
Copied from  https://cran.r-project.org/web/checks/check_results_lmeSplines.html
Check Details
Version: 1.1-10
Check: DESCRIPTION meta-information
Result: NOTE
    Malformed Title field: should not end in a period.
    Malformed Description field: should contain one or more complete sentences.
Flavors: r-devel-linux-x86_64-debian-clang, r-devel-linux-x86_64-debian-gcc, r-devel-linux-x86_64-fedora-clang, r-devel-linux-x86_64-fedora-gcc, r-devel-windows-x86_64-new-UL, r-patched-linux-x86_64, r-release-linux-x86_64, r-release-macos-arm64, r-release-macos-x86_64, r-release-windows-ix86+x86_64, r-oldrel-macos-x86_64, r-oldrel-windows-ix86+x86_64

Version: 1.1-10
Check: dependencies in R code
Result: NOTE
    Package in Depends field not imported from: 'nlme'
     These packages need to be imported from (in the NAMESPACE file)
     for when this namespace is loaded but not attached.
Flavors: r-devel-linux-x86_64-debian-clang, r-devel-linux-x86_64-debian-gcc, r-devel-linux-x86_64-fedora-clang, r-devel-linux-x86_64-fedora-gcc, r-devel-windows-x86_64-new-UL, r-patched-linux-x86_64, r-release-linux-x86_64, r-release-macos-arm64, r-release-macos-x86_64, r-release-windows-ix86+x86_64, r-oldrel-macos-x86_64, r-oldrel-windows-ix86+x86_64

Version: 1.1-10
Check: R code for possible problems
Result: NOTE
    approx.Z : <anonymous>: no visible global function definition for
     'approx'
    smspline: no visible global function definition for 'model.frame'
    Undefined global functions or variables:
     approx model.frame
    Consider adding
     importFrom("stats", "approx", "model.frame")
    to your NAMESPACE file.
Flavors: r-devel-linux-x86_64-debian-clang, r-devel-linux-x86_64-debian-gcc, r-devel-linux-x86_64-fedora-clang, r-devel-linux-x86_64-fedora-gcc, r-devel-windows-x86_64-new-UL, r-patched-linux-x86_64, r-release-linux-x86_64, r-release-macos-arm64, r-release-macos-x86_64, r-release-windows-ix86+x86_64, r-oldrel-macos-x86_64, r-oldrel-windows-ix86+x86_64
