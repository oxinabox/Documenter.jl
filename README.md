
# Documenter

*A documentation generator for Julia.*

| **Documentation**                                                               | **Build Status**                                                                                |
|:-------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------:|
| [![][docs-stable-img]][docs-stable-url] [![][docs-latest-img]][docs-latest-url] | [![][travis-img]][travis-url] [![][appveyor-img]][appveyor-url] [![][codecov-img]][codecov-url] |


## Installation

The package can be installed with Julias package manager:

```julia
julia> import Pkg

julia> Pkg.add("Documenter")
```

## Documentation

- [**STABLE**][docs-stable-url] &mdash; **most recently tagged version of the documentation.**
- [**LATEST**][docs-latest-url] &mdash; *in-development version of the documentation.*

## Project Status

The package is tested against Julia `0.7`, `1.0` and *current* `1.1-dev` on Linux, OS X, and Windows.

Support for Julia `0.4`, `0.5` and `0.6` has been dropped in the latest version, but older versions of Documenter may still work with those Julia versions (the `0.8`, `0.11` and `0.19` branches for Julia versions `0.4`, `0.5` and `0.6`, respectively).

## Questions and Contributions

Usage questions can be posted on the [Julia Discourse forum][discourse-tag-url] under the `documenter` tag, and/or in the [JuliaDocs Gitter chat room][gitter-url].

Contributions are very welcome, as are feature requests and suggestions. Please open an [issue][issues-url] if you encounter any problems. The [contributing page][contrib-url] has a few guidelines that should be followed when opening pull requests and contributing code.

[contrib-url]: https://juliadocs.github.io/Documenter.jl/latest/man/contributing/
[discourse-tag-url]: https://discourse.julialang.org/tags/documenter
[gitter-url]: https://gitter.im/juliadocs/users

[docs-latest-img]: https://img.shields.io/badge/docs-latest-blue.svg
[docs-latest-url]: https://juliadocs.github.io/Documenter.jl/latest

[docs-stable-img]: https://img.shields.io/badge/docs-stable-blue.svg
[docs-stable-url]: https://juliadocs.github.io/Documenter.jl/stable

[travis-img]: https://travis-ci.org/JuliaDocs/Documenter.jl.svg?branch=master
[travis-url]: https://travis-ci.org/JuliaDocs/Documenter.jl

[appveyor-img]: https://ci.appveyor.com/api/projects/status/xx7nimfpnl1r4gx0?svg=true
[appveyor-url]: https://ci.appveyor.com/project/JuliaDocs/documenter-jl

[codecov-img]: https://codecov.io/gh/JuliaDocs/Documenter.jl/branch/master/graph/badge.svg
[codecov-url]: https://codecov.io/gh/JuliaDocs/Documenter.jl

[issues-url]: https://github.com/JuliaDocs/Documenter.jl/issues
