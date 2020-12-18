QPDF for Alpine linux
=====================

This repository contains the current release of [QPDF](https://github.com/qpdf/qpdf) built
for Alpine linux.

The built binaries are tested against our Alpine base images:

- [Alpine 3.7](https://github.com/gmitirol/alpine37)
- [Alpine 3.8](https://github.com/gmitirol/alpine38)
- [Alpine 3.9](https://github.com/gmitirol/alpine39)
- [Alpine 3.10](https://github.com/gmitirol/alpine310)
- [Alpine 3.11](https://github.com/gmitirol/alpine311)
- [Alpine 3.12](https://github.com/gmitirol/alpine312)

Installation
------------

* Install the required dependencies `libjpeg` and `libstdc++`

  `apk add libjpeg libstdc++`

* Download the latest binary release (or a specific release version)

  `wget https://github.com/gmitirol/qpdf-alpine/releases/latest/download/qpdf-bin-amd64.tgz`

* Extract the binaries (by using the root directory as target, they are installed in `/usr/bin`.)

  `tar xzf qpdf-bin-amd64.tgz -C /`
