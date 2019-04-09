
For Ubuntu:
==========

Install dependencies:

```
sudo apt update && apt upgrade -y && apt install -y git build-essential cmake make libuv1-dev libmicrohttpd-dev uuid-dev libboost-all-dev
```


Libraries needed : boost >=1.58

How to compile this :
```
git clone https://github.com/hummingbirdwhocode/Laniakey.git laniakey
cd laniakey
mkdir build
cd build
cmake -D STATIC=ON -D CMAKE_BUILD_TYPE=RELEASE ..
PORTABLE=1 make
```

For Windows:
==========

Dependencies: MSVC 2013 or later, CMake 3.14 or later, and Boost >=1.58.

You may download them from:

http://www.microsoft.com/

http://www.cmake.org/

http://www.boost.org/

