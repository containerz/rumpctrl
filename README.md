[![Build Status](https://travis-ci.org/rumpkernel/rumprun.png?branch=master)](https://travis-ci.org/rumpkernel/rumprun)

Rumprun facilitates compiling and running userspace programs against rump
kernels.  It is especially useful for the configuration of rump kernels.
This repository provides both the rumprun framework and a selection of
familiar utilities such as `ifconfig`, `mount`, `sysctl`, and more.

Quickstart, run the following commands:

````
./buildnb.sh
. ./rumpremote.sh
rumpremote_listcmds
````

This will fetch and build dependencies and list available rumprun commands.

See [the wiki](http://wiki.rumpkernel.org/Repo:-rumprun) for more
information and instructions.
