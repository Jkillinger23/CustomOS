docker build buildenv -t myos-buildenv

Linux or MacOS:		docker run --rm -it -v $pwd:/root/env myos-buildenv

Windows:		docker run --rm -it -v %cd%:/root/env myos-buildenv

Make sure you use command prompt when running

make build-x86_64
