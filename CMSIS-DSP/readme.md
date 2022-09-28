This folder contains **Source**, **Include** and **PrivateInclude** folders from https://github.com/ARM-software/CMSIS-DSP repo, rev. post-1.14.0 (633b528, 2022-09-28)  
Complete repo cannot be included due to external dependencies and because it requires Make/CMake to build.  
In addition, some C files include other C files, which causes `multiple definition of ...` errors when linking.  
See https://github.com/ARM-software/CMSIS-DSP/issues/50