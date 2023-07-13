# test-repo

| Name | Dependent | Status |
| ---- | ---- | :----: |
| binutils | None | [![build-binutils](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-binutils.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-binutils.yml) |
| gdb | None | [![build-gdb](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build_gdb.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build_gdb.yml) |
| vita-toolchain | libelf, zlib, libzip, libyaml | [![build-vita-toolchain](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-toolchian.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-toolchian.yml) |
| vita-headers | vita-toolchain, binutils | [![build-vita-headers](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-vita-headers.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-vita-headers.yml) |
| gcc-base | None | - |
| newlib | binutils, gcc-base, vita-headers | [![build-newlib](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-newlib.yml/badge.svg)](https://github.com/Princess-of-Sleeping/test-repo/actions/workflows/build-newlib.yml) |
| pthread-embedded | binutils, gcc-base, vita-headers, newlib | - |
| gcc-complete | newlib, gmp, mpfr, mpc, isl, libelf | - |
| gcc-final | gmp, mpfr, mpc, isl, libelf | - |
| samples | None | - |
| vdpm | None | - |
| vita-makepkg | None | - |
