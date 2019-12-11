# kendryte_standalone
use kendryte_standalone_sdk from https://github.com/kendryte/kendryte-standalone-sdk; Can read guide from https://github.com/kendryte/kendryte-doc-standalone-programming-guide
If you want to start a new project, for instance, hello_world, you only need to:
mkdir build && cd build
cmake .. -DPROJ=<ProjectName> -DTOOLCHAIN=/opt/riscv-toolchain/bin && make
You should download the toolchain from https://kendryte.com/downloads/
