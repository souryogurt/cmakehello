cmakehello
==========

cmakehello is the template of C project that follows modern practices.

[![Build Status](https://travis-ci.org/souryogurt/cmakehello.svg?branch=master)](https://travis-ci.org/souryogurt/cmakehello)
[![Quality Status](https://sonarcloud.io/api/project_badges/measure?project=souryogurt_cmakehello&metric=alert_status)](https://sonarcloud.io/dashboard?id=souryogurt_cmakehello)

Features
--------

- Uses modern cmake
- Has travis CI pipeline for build, test, coverage and sonar analyzing
- Supports packaging as source tarball, RPM and DEB
- Has install target

Installation
------------

Install cmakehello from sources, by running:

```sh
apt install gcc cmake
git clone https://github.com/souryogurt/cmakehello.git
cd cmakehello
mkdir build && cd build
cmake ../
cmake --build .
cmake --build . --target install
```

Contribute
----------
- Read [How to submit an issue or feature request into tracker](https://github.com/souryogurt/cmakehello/wiki/How-to-submit-an-issue-or-feature-request)
- Issue Tracker: https://github.com/souryogurt/cmakehello/issues
- Source Code: https://github.com/souryogurt/cmakehello

Support
-------

If you are having issues, please let me know.
* Egor Artemov <egor.artemov@gmail.com>
