# W3C WebDriver Specification

This repository contains the W3C specification
for the browser automation standard known as _WebDriver_.
The main repository is at https://github.com/w3c/webdriver.

## Building

The `webdriver-spec.html` is generated by executing:

    make

The numbers at the start of each file corresponds to sections in the spec
and will be included in the final document in that order.

## Validation

To validate the specification you need to first set up
a number of dependencies on your system:

  * Selenium Python package (https://pypi.python.org/pypi/selenium),
    which on PyPI is available as `selenium`

  * linkchecker (https://dvcs.w3.org/hg/link-checker/),
    which on Debian/Ubuntu is available
    as the `w3c-linkchecker` package

  * An implemenation of Java 1.6 or newer

  * curl (http://curl.haxx.se/),
    on Debian/Ubuntu this is available as the `curl` package

All of these programs must be available on your `PATH`
for validation to succeed.