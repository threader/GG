This are the C++ includes i use and work well with C++ programs as openredalert.
this contain the libstdc++ Version from GCC 4.3.2 and includes.

But this can also work on GCC 3.4.0(i use with openredalert) and i think other compiler versions.
To get it working with other compilers you must create a dir in include/c++ of the compiler you have and copy the content of 4.3.2 dir to it.

Note: use this trick at your own risk, it can maybe get problems to use newer versions on older compilers.
I use the older compiler to see if the gcc 4 give faster or slower code.

It is known that gcc4.3.2 give not always faster exectuables, but many programs get faster as 3.4 and of course 2.95.
It is always good to have both compilers installed.Also newer programs need newer compilers.  