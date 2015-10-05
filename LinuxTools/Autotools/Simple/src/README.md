src
===

Source code directory for the project.

Contents
--------
1. `x.f90`: main Fortran program that must be build using  the
    module `a_mod.f90`.
1. `y.f90`: main Fortran program that must be build using  the
    module `b_mod.f90`.
1. `a_mod.f90`: module to build `x.f90` with.
1. `b_mod.f90`: module to build `y.f90` with.
1. `Makefile.am`: the automake file from which the `Makefile.in`  file will
    be generated by autotools, the latter being used as a template for the
    actual `Makefile` that is created when `configure` is run.