# test-repo

| Name | Dependent | Status |
| ---- | ---- | :----: |
| binutils | None | [![build-binutils](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-binutils.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-binutils.yml) |
| gdb | None | [![build-gdb](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-gdb.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-gdb.yml) |
| vita-toolchain | libelf, zlib, libzip, libyaml | [![build-vita-toolchain](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-toolchian.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-toolchian.yml) |
| vita-headers | vita-toolchain, binutils | [![build-vita-headers](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-vita-headers.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-vita-headers.yml) |
| np-gcc (newlib + pthread + gcc) | gmp, mpfr, mpc, isl, libelf (binutils, vita-headers) | [![build-np-gcc](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-np-gcc.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-np-gcc.yml) |
| samples | None | - |
| vdpm | None | - |
| vita-makepkg | None | - |
