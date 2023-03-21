This is a patch to support riscv64 on Debian riscv64.

# usage

Ensure to download firefox 111.0-* from [debian tracker](https://tracker.debian.org/pkg/firefox).
You can download it with $(apt source firefox).

# patching

You can modify the config options on `debian/rules` or `debian/browser.mozconfig.in` by hand one by one.

# Plan

Unfortunately, The firefox has not been built on real riscv64 hardware. But I hopefully
Debian firefox maintainer can merge it at least. 
