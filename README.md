# OpenWrt woa7 Packages
my OpenWrt Project packages

## Description

my OpenWrt Packages: for Head (Development branch)

## License

See [LICENSE](LICENSE) file.

## Usage

Add the following line to feeds.conf or feeds.conf.default.
```
src-git node https://github.com/nxhack/openwrt-woa7-packages.git
```

Run
```
./scripts/feeds update woa7
rm ./package/feeds/packages/woa7
rm ./package/feeds/packages/woa7-*
./scripts/feeds install -a -p woa7
make defconfig
```

## Request to add a package is welcome
If you want a new module (native module) that requires a precompiled binary, ***please open the issue.***

## Note
If you want to use with 19.07, see [openwrt-19.07 branch](https://github.com/woa7/openwrt-woa7-packages/tree/openwrt-19.07) (***End of life***) (***MIPS FPU EMULATOR support***)

If you want to use with 21.02, see [openwrt-21.02 branch](https://github.com/woa7/openwrt-woa7-packages/tree/openwrt-21.02) (***Old stable series***)

If you want to use with 22.03, see [openwrt-22.03 branch](https://github.com/woa7/openwrt-woa7-packages/tree/openwrt-22.03) (***Current stable series***)

## Package Guidelines

See [CONTRIBUTING.md](https://github.com/openwrt/packages/blob/master/CONTRIBUTING.md) file.
