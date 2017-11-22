# stress-ng

[`stress`](http://manpages.ubuntu.com/manpages/xenial/man1/stress-ng.1.html) in a Debian container.

## Run

Any paramaters will be passed to the `stress` command

    docker run deployable/stress -c 2

Help is the default output

    docker run deployable/stress


## Build

To build locally use the `make.sh` script

    ./make.sh build

