# service.xeeve
Libreelec Package for [xteve](https://github.com/xteve-project/xTeVe)


## Compile:

    `git clone https://github.com/LibreELEC/LibreELEC.tv && cd LibreElec.tv && git checkout libreelec-9.2`
    
    `PROJECT=RPi DEVICE=RPi4 ARCH=arm IMAGE_SUFFIX=buchclub ADDITIONAL_PACKAGES="docker ffmpeg tvheadend42 xeeve" make`



## embedded addons

1. Best way: Add Packages to `distributions/LibreELEC/options`

2. Open file `packages/addons/browser/chrome/package.mk` and change  `PKG_IS_ADDON="yes"` to `PKG_IS_ADDON="embedded"`


