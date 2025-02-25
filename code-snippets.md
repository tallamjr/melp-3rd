# Code

<!-- mtoc-start -->

* [Page 18](#page-18)
  * [Page 26](#page-26)

<!-- mtoc-end -->

### Page 18

```bash
sudo apt update
sudo apt install autoconf automake bison bzip2 cmake \
    flex g++ gawk gcc gettext git gperf help2man libncurses5-dev \
    libstdc++6 libtool libtool-bin make patch python3-dev rsync \
    texinfo unzip wget xz-utils
```

### Page 26

```bash
git clone https://github.com/crosstool-ng/crosstool-ng.git
cd crosstool-ng
git checkout crosstool-ng-1.24.0
./bootstrap
./configure --prefix=${PWD}
make
make install
```
