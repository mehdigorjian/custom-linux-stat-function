# custom-linux-stat-function
Custom Linux stat() function
Custom version of the command line program Linux stat, which simply calls the stat() system call on a given file or directory. (eg. print out file size, number of blocks allocated, reference (link) count, and etc.)

`// COMPILATION: gcc custom_stat.cpp -o custom_stat -lstdc++` \
`//         RUN: ./custom_stat FILE.EXTENTION`
