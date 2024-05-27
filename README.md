# Java Gradle License Scan Example

## Acknowledgments to the plugin author

All functionality-wise credits go to [github.com: jk1/Gradle-License-Report](https://github.com/jk1/Gradle-License-Report).
This repository does only provide an example on how to use the plugin.

---

This repository holds a basic example for scanning a gradle project for licenses that can't be used in proprietary
projects.

> **DISCLAIMER: THIS IS NOT LEGAL ADVICE NOR DOES THIS LIST CLAIM TO BE EXHAUSTIVE.**
>
> **FEEL FREE TO OPEN A PULL REQUEST TO SUBMIT ADDITIONAL LICENSES THAT DO NOT REQUIRE TO DISCLOSE
SOURCE CODE.**

## Executing the scan

You can execute the license scan by executing `gradle checkLicense` on the command line.

A report is generated under `${projectDir}/build/reports/dependency-license/index.html` which can be opened with any
browser.

## Usage/Examples

Try adding the commented out projects and see the `checkLicense` task failing. Also have a look on the report.