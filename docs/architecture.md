# Architecture Overview

## Host Hardware

- `uname -a`: `Linux 446af9a50b43 6.12.13 #1 SMP Thu Mar 13 11:34:50 UTC 2025 x86_64 x86_64 x86_64 GNU/Linux`
- `lscpu`: `Architecture: x86_64`, `CPU(s): 5`, `Virtualization type: full`
- `psutil`: `cpu_count=5`, `memory=10663276544`

## Project Build Targets

The build configuration lists the architectures supported for headers and compiled kernels:

- `HEADER_ARCHS = PPC I386`
- `BUILD_ARCHS = PPC I386`

This indicates the system can be built for classic PowerPC and Intel i386 processors.
