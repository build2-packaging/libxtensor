# libxtensor

Build2 package for [xtensor](https://github.com/xtensor-stack/xtensor.git) - a C++ library meant for numerical analysis with multi-dimensional array expressions.

This package exports `lib{xtensor}` target as a header-only binless lib and provides `config.libxtensor.usexsimd ?= false` as a config option, to optionally download and build [xsimd](https://github.com/build2-packaging/libxsimd.git).
