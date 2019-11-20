# ADLINK Lec IMX6 yocto configuration

This repository contains the yocto configuration. It manages the files:
- build/bblayers.conf
- build/local.conf

And prepare the environment for the build.

## Configure yocto

The setup-environment script generate the build directory.

```bash
$ MACHINE=imx6lec-1 DISTRO=core-image-minimal source setup-environment ./build
```
