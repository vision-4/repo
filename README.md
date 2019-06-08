# Repo

This is v1s10n_4's repo used to host cydia packages 

## Install package
```sh
cd repo
cp $PACKAGE_PATH ./debs
dpkg-scanpackages -m ./debs > Packages
rm Packages.bz2
bzip2 Packages
```
