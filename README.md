# service.xeeve
Libreelec Package for [xteve](https://github.com/xteve-project/xTeVe)


## Compile:

    `PROJECT=RPi DEVICE=RPi4 ARCH=arm IMAGE_SUFFIX=buchclub ADDITIONAL_PACKAGES="docker ffmpeg tvheadend42 xeeve" make`



## embedded addons

* Best way: Add Packages to `distributions/LibreELEC/options`
 
----

# additional packages to install:
# Space separated list is supported,
# e.g. ADDITIONAL_PACKAGES="PACKAGE1 PACKAGE2"
  ADDITIONAL_PACKAGES=""

-------------


* Open file `packages/addons/browser/chrome/package.mk` and change  `PKG_IS_ADDON="yes"` to `PKG_IS_ADDON="embedded"`


