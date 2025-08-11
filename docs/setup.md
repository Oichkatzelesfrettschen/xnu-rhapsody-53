# System Setup

- `uname -a`: `Linux 80e58b15ead0 6.12.13 #1 SMP Thu Mar 13 11:34:50 UTC 2025 x86_64 x86_64 x86_64 GNU/Linux`
- `dpkg --print-architecture`: `amd64`
- Packages installed via `apt-get`: `cloc`, `doxygen`, `graphviz`, `pandoc`

Additional hardware details gathered for reproducibility:

- `lscpu`: `Architecture: x86_64`, `CPU(s): 5`, `Virtualization type: full`
- `psutil.cpu_count()`: `5`
- `psutil.virtual_memory().total`: `10663276544`

These packages provide code analysis, documentation generation, graph rendering, and document conversion capabilities.
