# THIS IS AN ARMv7 Build of cpuminer, should be compatible with any armv7/lollipop or later phone. 

#Getting Started
This is a command line utility. You need a terminal emulator. Try com.termux or similar. There may be even x64 binaries from builds further up the tree. This branch adds a v7a build. Only tested for/on allium for garlicoin. Most everything else should work but there is no guarantee nor any support. There are no donations, original credits left alone.

Run ./cpuminer7.null --help for command line. All normal options available.
##Installation
1. Get https://play.google.com/store/apps/details?id=com.termux&hl=en or other terminal emulator of choice.
2. wget https://github.com/says0methings/miners/blob/master/cpuminer7.null
3. chmod 755 cpuminer7.null
4. ./cpuminer7.null --help

All cpuminer command line options should work. The 64bit binary if needed, is https://github.com/says0methings/miners/tree/master/cpuminer/android_arm64 and needs both cpuminer and the shared libraries and a command to export library path before invocation

1. export LD_LIBRARY_PATH=.:$LD_LIBRARY_PATH
2. ./cpuminer --help

## Issues
Only allium is a little tested algorithm. You may see bus error crashes. Or worse. This is a work in progress by pure accident. 
