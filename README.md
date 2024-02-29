# os
checking for an ANSI C-conforming const... yes
checking for off_t... yes
checking size of int... 4
checking size of long... 4
checking for ANSI C header files... (cached) yes
checking build system type... x86_64-w64-mingw32
checking host system type... x86_64-w64-mingw32
checking target system type... riscv64-unknown-elf
checking for decimal floating point... configure: WARNING: decimal float is not supported for this target, ignored
dpd
checking whether byte ordering is bigendian... no
checking for CET support... no
configure: updating cache ./config.cache
configure: creating ./config.status
config.status: creating Makefile
config.status: creating config.h
config.status: executing gstdint.h commands
make[2]: Entering directory '/d/trainning/proj/tools/riscv-gnu-toolchain/build-gcc-newlib-stage1/libdecnumber'
source='../.././gcc/libdecnumber/decNumber.c' object='decNumber.o' libtool=no gcc  -I../.././gcc/libdecnumber -I.  -g -O2   -W -Wall -Wwrite-strings -Wstrict-prototypes -Wmissing-prototypes -Wold-style-definition -Wmissing-format-attribute -Wcast-qual -pedantic -Wno-long-long  -fno-lto -I../.././gcc/libdecnumber -I.    -c ../.././gcc/libdecnumber/decNumber.c
source='../.././gcc/libdecnumber/decContext.c' object='decContext.o' libtool=no gcc  -I../.././gcc/libdecnumber -I.  -g -O2   -W -Wall -Wwrite-strings -Wstrict-prototypes -Wmissing-prototypes -Wold-style-definition -Wmissing-format-attribute -Wcast-qual -pedantic -Wno-long-long  -fno-lto -I../.././gcc/libdecnumber -I.    -c ../.././gcc/libdecnumber/decContext.c
source='../.././gcc/libdecnumber/dpd/decimal32.c' object='decimal32.o' libtool=no gcc  -I../.././gcc/libdecnumber -I.  -g -O2   -W -Wall -Wwrite-strings -Wstrict-prototypes -Wmissing-prototypes -Wold-style-definition -Wmissing-format-attribute -Wcast-qual -pedantic -Wno-long-long  -fno-lto -I../.././gcc/libdecnumber -I.    -c ../.././gcc/libdecnumber/dpd/decimal32.c
      0 [main] make 21599 dofork: child -1 - CreateProcessW failed for 'C:\msys64\usr\bin\make.exe', errno 13
         make[2]: *** [Makefile:135: decimal32.o] Error 127
make[2]: Leaving directory '/d/trainning/proj/tools/riscv-gnu-toolchain/build-gcc-newlib-stage1/libdecnumber'
make[1]: *** [Makefile:8066: all-libdecnumber] Error 2
make[1]: Leaving directory '/d/trainning/proj/tools/riscv-gnu-toolchain/build-gcc-newlib-stage1'
make: *** [Makefile:604: stamps/build-gcc-newlib-stage1] Error 2
