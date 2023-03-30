# Download source code
(salsa)[git@salsa.debian.org:mozilla-team/thunderbird.git]

Ensure the HEAD commit is ad3ed5ac3fe9f8e909f1f5.

# Patch

In fact, the patch can be applied after any version debian/1%110.0.

# build package
```
gbp buildpackage   --git-builder=sbuild  --arch=riscv64 -c sid-riscv64-sbuild --no-clean-source --source --no-run-lintian  --git-export-dir=../build-area/ --git-ignore-new  --verbose
```

# binary packages

[here](https://drive.google.com/drive/folders/1klWvrjq-geMFAWIXTas6lPz8e8_7Eavo?usp=share_link)

# obs

The package can be built on [obs](https://build.tarsier-infra.com/package/show/home:vimer:debian_riscv64/thunderbird-110) also.
