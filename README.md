# meta-raspberrypi4-realsense-r200

## Dependencies

* Download `git clone -b zeus git://git.yoctoproject.org/poky`
* Download `git clone -b zeus git://git.openembedded.org/meta-openembedded`
* Download `git clone -b zeus https://github.com/net-attack/meta-intel-realsense.git`
* Download `git clone -b zeus git://git.yoctoproject.org/meta-raspberrypi`


## Bitbake

* Run `. poky/oe-init-build-env`
* Copy `cp ../conf/*.conf conf/`
* Run `bitbake core-image-minimal`
