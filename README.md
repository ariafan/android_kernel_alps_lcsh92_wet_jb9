android_kernel_alps_lcsh92_wet_jb9
==================================

Kernel for the Xiaomi Redmi Note (WCDMA)
WHAT IS THIS?
Linux Kernel source code for the device bq Aquaris E6

BUILD INSTRUCTIONS?
Specific sources are separated by branches and each version is tagged with it's corresponding number. First, you should clone the project:

$ git clone git@github.com:bq/aquaris-E6.git
After it, choose the version you would like to build:

$ cd aquaris-E6/
$ git checkout 1.1.0_20140908-0900
Finally, build the kernel:

$ ./makeMtk -t bulma n k
