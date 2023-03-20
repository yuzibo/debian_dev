This is an experimental patch.

# usgae

## 1. Download source code 

Sure, ensure to download firefox [110.0.1-1](https://deb.debian.org/debian/pool/main/f/firefox/firefox_110.0.1-1.dsc) 
from Debian or `apt source firefox`.

## 2. Patching the patch

Mainly to modify config options within `debian/rules` and `debian/browser.mozconfig.in`
files.

At last build the package with sbuild or git buildpackage.

# binary package

[firefox 110.0.0-1 binary package](https://drive.google.com/drive/folders/1h2MHtkCEM5s0BlYRKTX2bBXz9s6PqiY4?usp=sharing)

# next plan

Next time the patch will be rebased on 111 and tidy it again to make sure it works/effects on rv64.
So maintainer of the Debian package will merge it.
