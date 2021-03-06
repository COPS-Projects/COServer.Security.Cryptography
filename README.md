Overview
--------

COServer.Security.Cryptography is a library exposing the TQ Digitial's asymmetric cipher that is used by Conquer Online 2.0 servers (pre-5018).

The library is developed in C++, with an translation layer in C++/CLI.

License
-------

The library is released under a BSD 2-clause license.

Features
--------

+ Fast native implementation of the cipher
  - Optimized implementations for Intel CPUs. (SSE/SSE2, AVX/AVX2)
  - Automatic detection of the best implementation to use.
+ .NET compatible interface (C++/CLI)

Supported systems
-----------------

The library has been tested on the following platforms:
- Windows 7 Professional (SP1)
  + x86, x86_64

However, the emulator should work without any modification on any Windows systems supporting the MSVC 2013 redistributable and the .NET Framework v4.0.

N.B. This library was built using Visual Studio 2013 and the .NET Framework v4.0.