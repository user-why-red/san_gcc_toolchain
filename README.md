This is a GCC compiler toolchain that is built for kernel development. Builds are always made from the latest GCC(stable releases).

This toolchain targets the AArch32, AArch64, and x86_64 architectures. It is built with LTO and O3 optimizations to reduce compile times as much as possible. Note that this toolchain is not suitable for anything other than bare-metal development; it has not been built with support for any libc or userspace development in mind.

binutils is also included for convenience. SAN-GCC uses binutils source from the HEAD of the latest release branch, which allows us to have more upto date binutils compared to latest stable release as well as avoiding instability or breakage compared to bleeding edge binutils.