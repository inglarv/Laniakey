
Usage
===

For Ubuntu
==========

Install dependencies:

```
apt update && apt upgrade -y && apt install -y git build-essential cmake make libuv1-dev libmicrohttpd-dev uuid-dev libboost-all-dev
```

Libraries needed : boost >=1.58

How to compile this :
```
$ git clone https://github.com/hummingbirdwhocode/Laniakey.git laniakey
$ cd laniakey
$ mkdir build
$ cd build
$ cmake -D STATIC=ON -D CMAKE_BUILD_TYPE=RELEASE ..
$ PORTABLE=1 make
```
