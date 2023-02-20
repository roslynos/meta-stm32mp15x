# Yocto/OE meta layer for RoslynOS

This layer provides BSP support for the [stm32mp15x](https://wiki.st.com/stm32mpu/wiki/Category:STM32MP15x) containing custom recipes, classes, configuration, etc. Layer relies on OpenEmbedded/Yocto build system and depends on:

```
[OECORE]
URI: git://git.yoctoproject.org/poky
layers: meta
branch: same dedicated branch as meta-stm32mp15x

[OECORE]
URI: git://git.openembedded.org/meta-openembedded
layers: meta
branch: same dedicated branch as meta-stm32mp15x
```

Please see https://github.com/roslynos/stm32-oss for further information.

## Licenses

An image is made of many components and it’s hard to describe the full details of all the licenses that are in use. When building the system from sources with OpenEmbedded, you are responsible for understanding the licenses used by each package.