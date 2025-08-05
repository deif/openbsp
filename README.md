# openbsp
repo init https://github.com/deif/openbsp.git

repo sync

. layers/openembedded-core/oe-init-build-env 

bitbake core-image-minimal
