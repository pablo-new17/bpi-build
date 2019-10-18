# bpi-build

  This is a docker system environment which is run ubuntu 12.04, for bpi source code compile.

#筆記
  dockerfile 裡面，同時安裝了
    gcc-arm-linux-gnueabihf
    g++-arm-linux-gnueabihf 
    gcc-arm-linux-gnueabi
    g++-arm-linux-gnueabi
  因為，Allwinner 的 uboot 需要用 soft float去編譯。
