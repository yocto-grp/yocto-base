# yocto-base

#### Usage

```
source ./setup-environment machine-name build-dir target
```

现在`DISTRO` `MACHINE` 必须说明。


#### genericx86-64

```
DISTRO=poky MACHINE=genericx86-64 source ./setup-environment build/poky-genericx86-64 core-image-base && meta-toolchain
DISTRO=poky MACHINE=genericx86-64 source ./setup-environment build/poky-genericx86-64 core-image-sato && meta-toolchain

```


