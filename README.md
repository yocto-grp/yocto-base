# yocto-base

#### Usage

```
source ./setup-environment machine-name build-dir target

```


现在`DISTRO` `MACHINE` 必须说明。
新添加distro，machine时，需要在`conf`, `locals` 中加入相应的文件， 文件名是有规范的。

conf文件名： `bblayers.conf.${DISTRO}-${MACHINE}`
locals文件名： `local.conf.${DISTRO}-${MACHINE}`


#### genericx86-64

```
DISTRO=poky MACHINE=genericx86-64 source ./setup-environment build/poky-genericx86-64 core-image-base && meta-toolchain
DISTRO=poky MACHINE=genericx86-64 source ./setup-environment build/poky-genericx86-64 core-image-sato && meta-toolchain

```

#### bananpi

```
DISTRO=monkey MACHINE=bpi source ./setup-environment build/bpi bpi-image-xfce && meta-toolchain

```


