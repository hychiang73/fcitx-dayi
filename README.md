# fcitx-dayi
Install Chinese input Dayi with fcitx, which can be appied to ubuntu 16.04

# Instruction

* Install all necessary packages

`$ sudo apt-get install cmake fcitx-libs-dev fcitx-tools fcitx-table`

* Clone this repo to get dayi resources

* Create a folder to prepare installation

`$ mkdir build`

`$ cmake . -DCMAKE_INSTALL_PREFIX=/usr`

* To write the following content at the top in `tables/CMakeLists.txt`

`$ vim tables/CMakeLists.txt`

* Install

`$ sudo make install`

