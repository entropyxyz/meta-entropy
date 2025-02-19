# meta-entropy-tss

Yocto layer with recipe for entropy-tss

This repo is currently **work-in-progress**

Currently this copies in a pre-built binary rather than compiling it within Yocto.

To check measurement value, you can use the version endpoint:

Eg: 
```
$ curl 34.147.25.103:3001/version
```

It has an init script for the simple tiny-init system used by poky-tiny.

Instructions for building are in [entropyxyz/yocto-build](https://github.com/entropyxyz/yocto-build)
