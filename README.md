# CPython 2.7 (Deprecated)

This repository is fork of CPython 2.7 with a few cherry-picked patches to make
CPython 2.7 compilable on Ubuntu 24.04.

Note: This repository is not actively maintained. I created this repository
only to unblock my PyPy bootstrapping work. This should not be used in
production.

## Download

```
git clone https://github.com/loganchien/cpython27-deprecated -b release_27
```


## Acknowledge

Most patches are cherry-picked from Ubuntu
[python2.7_2.7.18-13ubuntu1.1.diff.gz](https://packages.ubuntu.com/jammy/python2.7).
Special thanks to their efforts. But, I don't cherry-pick all patches because
I want to use `python2.7 -mpip install PACKAGE_NAME` to install Python
packages.
