# free5gc-compose-ulcl

## Description
ULCL Configuration for free5gc-compose v3.1.1

## How to apply the patch file?
```
$ git clone https://github.com/ianchen0119/free5gc-compose-ulcl.git
$ cd free5gc-compose-ulcl
$ cp 0001-update-ulcl-example-for-free5gc-v3.1.1.patch ../free5gc-compose/0001-update-ulcl-example-for-free5gc-v3.1.1.patch
$ cd ../free5gc-compose
$ cd free5gc-compose
$ git am -k -3 --reject < 0001-update-ulcl-example-for-free5gc-v3.1.1.patch
```
