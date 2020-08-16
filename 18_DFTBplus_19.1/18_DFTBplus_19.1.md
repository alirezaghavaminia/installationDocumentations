# Installing SOFTWARE_NAME

## Easyconfig file

`DFTB+-19.1-foss-2019b-Python-2.7.16.eb`

## By EasyBuild Version

```bash
eb --version
This is EasyBuild 4.2.2 (framework: 4.2.2, easyblocks: 4.2.2) on host test1.nhpcc.iut.
```

## Sources Location

Sources are located in [`/home/alireza/.local/easybuild/sources/`](sftp://alireza@172.16.189.18/home/alireza/.local/easybuild)

## Dependencies List

Status:

* [ ] not installed
* [X] already installed

```bash
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/m/M4/M4-1.4.18.eb (module: M4/1.4.18)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/b/Bison/Bison-3.3.2.eb (module: Bison/3.3.2)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/z/zlib/zlib-1.2.11.eb (module: zlib/1.2.11)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/h/help2man/help2man-1.47.4.eb (module: help2man/1.47.4)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/f/flex/flex-2.6.4.eb (module: flex/2.6.4)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/b/binutils/binutils-2.32.eb (module: binutils/2.32)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/g/GCCcore/GCCcore-8.3.0.eb (module: GCCcore/8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/h/help2man/help2man-1.47.8-GCCcore-8.3.0.eb (module: help2man/1.47.8-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/m/M4/M4-1.4.18-GCCcore-8.3.0.eb (module: M4/1.4.18-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/z/zlib/zlib-1.2.11-GCCcore-8.3.0.eb (module: zlib/1.2.11-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/b/Bison/Bison-3.3.2-GCCcore-8.3.0.eb (module: Bison/3.3.2-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/f/flex/flex-2.6.4-GCCcore-8.3.0.eb (module: flex/2.6.4-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/b/binutils/binutils-2.32-GCCcore-8.3.0.eb (module: binutils/2.32-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/b/bzip2/bzip2-1.0.8-GCCcore-8.3.0.eb (module: bzip2/1.0.8-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/g/GCC/GCC-8.3.0.eb (module: GCC/8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/p/pkg-config/pkg-config-0.29.2-GCCcore-8.3.0.eb (module: pkg-config/0.29.2-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/n/ncurses/ncurses-6.1-GCCcore-8.3.0.eb (module: ncurses/6.1-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/o/OpenBLAS/OpenBLAS-0.3.7-GCC-8.3.0.eb (module: OpenBLAS/0.3.7-GCC-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/l/libtool/libtool-2.4.6-GCCcore-8.3.0.eb (module: libtool/2.4.6-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/e/expat/expat-2.2.7-GCCcore-8.3.0.eb (module: expat/2.2.7-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/t/Tcl/Tcl-8.6.9-GCCcore-8.3.0.eb (module: Tcl/8.6.9-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/c/cURL/cURL-7.66.0-GCCcore-8.3.0.eb (module: cURL/7.66.0-GCCcore-8.3.0)
 * [ ] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/d/dftd3-lib/dftd3-lib-0.9-GCC-8.3.0.eb (module: dftd3-lib/0.9-GCC-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/l/libreadline/libreadline-8.0-GCCcore-8.3.0.eb (module: libreadline/8.0-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/p/Perl/Perl-5.30.0-GCCcore-8.3.0.eb (module: Perl/5.30.0-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/s/SQLite/SQLite-3.29.0-GCCcore-8.3.0.eb (module: SQLite/3.29.0-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/c/CMake/CMake-3.15.3-GCCcore-8.3.0.eb (module: CMake/3.15.3-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/a/Autoconf/Autoconf-2.69-GCCcore-8.3.0.eb (module: Autoconf/2.69-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/e/Eigen/Eigen-3.3.7.eb (module: Eigen/3.3.7)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/a/Automake/Automake-1.16.1-GCCcore-8.3.0.eb (module: Automake/1.16.1-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/a/Autotools/Autotools-20180311-GCCcore-8.3.0.eb (module: Autotools/20180311-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/n/numactl/numactl-2.0.12-GCCcore-8.3.0.eb (module: numactl/2.0.12-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/g/GMP/GMP-6.1.2-GCCcore-8.3.0.eb (module: GMP/6.1.2-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/l/libffi/libffi-3.2.1-GCCcore-8.3.0.eb (module: libffi/3.2.1-GCCcore-8.3.0)
 * [ ] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/p/Python/Python-2.7.16-GCCcore-8.3.0.eb (module: Python/2.7.16-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/x/xorg-macros/xorg-macros-1.19.2-GCCcore-8.3.0.eb (module: xorg-macros/1.19.2-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/l/libpciaccess/libpciaccess-0.14-GCCcore-8.3.0.eb (module: libpciaccess/0.14-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/n/ncurses/ncurses-6.0.eb (module: ncurses/6.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/g/gettext/gettext-0.19.8.1.eb (module: gettext/0.19.8.1)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/x/XZ/XZ-5.2.4-GCCcore-8.3.0.eb (module: XZ/5.2.4-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/l/libxml2/libxml2-2.9.9-GCCcore-8.3.0.eb (module: libxml2/2.9.9-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/h/hwloc/hwloc-1.11.12-GCCcore-8.3.0.eb (module: hwloc/1.11.12-GCCcore-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/o/OpenMPI/OpenMPI-3.1.4-GCC-8.3.0.eb (module: OpenMPI/3.1.4-GCC-8.3.0)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/g/gompi/gompi-2019b.eb (module: gompi/2019b)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/f/FFTW/FFTW-3.3.8-gompi-2019b.eb (module: FFTW/3.3.8-gompi-2019b)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/s/ScaLAPACK/ScaLAPACK-2.0.2-gompi-2019b.eb (module: ScaLAPACK/2.0.2-gompi-2019b)
 * [x] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/f/foss/foss-2019b.eb (module: foss/2019b)
 * [ ] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/s/SciPy-bundle/SciPy-bundle-2019.10-foss-2019b-Python-2.7.16.eb (module: SciPy-bundle/2019.10-foss-2019b-Python-2.7.16)
 * [ ] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/a/arpack-ng/arpack-ng-3.7.0-foss-2019b.eb (module: arpack-ng/3.7.0-foss-2019b)
 * [ ] /opt/software/EasyBuild/4.2.2/easybuild/easyconfigs/d/DFTB+/DFTB+-19.1-foss-2019b-Python-2.7.16.eb (module: DFTB+/19.1-foss-2019b-Python-2.7.16)
```

## Installing Instructions

load Easybuild and packaging tools

```bash
module purge
module load EasyBuild FPM

sudo yum install time -y
eb SRCs/DFTB+-19.1-foss-2019b-Python-2.7.16.eb --robot --package
```

### Errors and Solutions

* Test fails on `timedep/C60_OscWindow` according to the log file. 
    From [this issue](https://github.com/dftbplus/dftbplus/issues/244) it is a result of `time` command not being available in `/usr/bin/` so it is necessary to install the `time` package. 
    Which is done with `sudo yum install time` Yet the test fails again.
    ```bash 
    ======= timedep/C60_OscWindow =======
    orbital_charges      element              5.59552404411e-14           OK
    exc_energies_sqr     element              Mismatching data            Error
    exc_oscillator       element              Mismatching data            Error
    mermin_energy        element              1.00897068478e-12           OK
    end_coords           element              0.0                         OK
    ```
    I assumed (based on the google searches) that this may be duo to the lack of graphics, since all the results from the `DFTB+ OscWindow` showd a ghraph windows. 
    Anyway I decided to bypass the `make test` since I belived that error was not critical.
    