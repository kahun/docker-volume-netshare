# Changelog

## 0.38

* [nfscache] Added timeout to mount command. Default value 40 seconds. To define custom seconds "-t \d+"

## 0.37

* Add NFSCACHE driver
* Add support in NFSCACHE driver to create /tmp/<uuid> directories to run kerberos in docker as user
* Add parameter lazyumount to pass --lazy to the umount command in NFSCACHE driver
* Fix mount grep for similar mounts names
