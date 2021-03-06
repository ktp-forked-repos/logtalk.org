---
layout: article
permalink: download.html
title: Download
aside:
  toc: true
---

**Latest stable version:** 3.23.0  
**Release date:** January 30, 2019

## Requirements

Logtalk runs on any operating-system with a standards compliant modern
Prolog compiler. The interface between Logtalk and a specific backend
Prolog compiler is accomplished using a small adapter file. The Logtalk
distribution includes adapter files for all supported Prolog compilers:

-   [B-Prolog 7.8 or later versions](http://www.picat-lang.org/bprolog/)
-   [CxProlog 0.98.1 or later versions](http://ctp.di.fct.unl.pt/~amd/cxprolog/)
-   [ECLiPSe 6.1\#143 or later versions](http://eclipseclp.org/)
-   [GNU Prolog 1.4.5 or later versions](http://www.gprolog.org/)
-   [JIProlog 4.1.6.1 or later versions](http://www.jiprolog.com/)
-   [Lean Prolog 4.5.7 or later versions](http://www.cse.unt.edu/~tarau/) *(experimental)*
-   [Qu-Prolog 9.7 or later versions](http://www.itee.uq.edu.au/~pjr/HomePages/QuPrologHome.html)
-   [Quintus Prolog 3.3\~3.5](https://quintus.sics.se) *(experimental)*
-   [SICStus Prolog 4.1.0 or later versions](https://sicstus.sics.se)
-   [SWI Prolog 6.6.0 or later versions](http://www.swi-prolog.org/)
-   [XSB 3.8.0 or later versions](http://xsb.sourceforge.net/)
-   [YAP 6.3.4 or later versions](https://www.dcc.fc.up.pt/~vsc/yap/)

Legacy Logtalk versions (2.x) provide support for some other Prolog
compilers, which are no longer supported due to lack of compliance with
official and de facto standards.

Be sure to install the Prolog systems that you want to use as backend
compilers before installing Logtalk.


## License

Logtalk is an open source programming language, distributed under the
[Apache License 2.0](https://github.com/LogtalkDotOrg/logtalk3/blob/master/LICENSE.txt).
The copyright notice and license applies to all files in this release
(including sources, documentation, and examples) unless otherwise
explicitly stated.


## Git repo

The Logtalk git repo is currently hosted at
[GitHub](http://github.com/LogtalkDotOrg/logtalk3).
Follow these [steps](running_developer_versions.html)
for running Logtalk development versions. See the
[release notes](https://github.com/LogtalkDotOrg/logtalk3/blob/master/RELEASE_NOTES.md)
for the latest changes.

You may keep up to date on development changes by subscribing to the Logtalk commits [RSS
feed](https://github.com/LogtalkDotOrg/logtalk3/commits/master.atom).


## Sources

> [`logtalk-3.23.0.tar.bz2`](files/logtalk-3.23.0.tar.bz2)  
> `10c127c676e7b88142ddf29543daf7075572203bd2010e48f6ea913fe018ead5` (SHA-256)

Includes the HTML versions of the Handbook and the APIs documentation.


## Installers

Be sure to read the
[`README.md`](https://github.com/LogtalkDotOrg/logtalk3/blob/master/README.md),
[`CUSTOMIZE.md`](https://github.com/LogtalkDotOrg/logtalk3/blob/master/CUSTOMIZE.md), and
[`QUICK_START.md`](https://github.com/LogtalkDotOrg/logtalk3/blob/master/QUICK_START.md)
files on the Logtalk user directory for important information, including
instructions on how to customize and run Logtalk. For Windows users,
this information is also available from the `Logtalk` program group in
the `Start Menu`.

The following installers are available for the latest version:


### macOS

Based on the [MacPorts](http://www.macports.org/) portfile. Installs
Logtalk on `/opt/local/share/` with integration scripts for supported
Prolog compilers on `/opt/local/bin`. Creates an `/Applications/Logtalk`
folder with links to the installed files.

> [`logtalk-3.23.0.pkg.zip`](files/logtalk-3.23.0.pkg.zip)  
> `64c137ce3f1ce2d29adaf3e77c3f1a14ecf35d0939fe355f3ec9ef4629ce8c57` (SHA-256)

A [MacPorts](http://www.macports.org/) portfile is also available. Users
may simply type the command `sudo port install logtalk` (or
`sudo port upgrade logtalk`) in order to install (or upgrade) Logtalk.
[Homebrew](http://mxcl.github.com/homebrew/) users may simply type the
command `brew install logtalk` (or `brew upgrade logtalk`) in order to
install (or upgrade) Logtalk. But do check first that the MacPorts
portfile and the Homebrew formula are up-to-date.


### Linux

Installs Logtalk on `/usr/local/share` with integration scripts for
supported Prolog compilers on `/usr/local/bin`. Package installation from
the command-line is recommended.

> [`logtalk-3.23.0-1.noarch.rpm`](files/logtalk-3.23.0-1.noarch.rpm)  
> `978a125bf66cb7c8c5af16de7a2577d21fc4169958ef46c446df34bfbe4a5b79` (SHA-256)


### Debian (e.g. Ubuntu)

Requires dpkg 1.15.0 or a later version. Installs Logtalk on
`/usr/share` with integration scripts for supported Prolog compilers on
`/usr/bin`. Package installation from the command-line is recommended.

> [`logtalk_3.23.0-1_all.deb`](files/logtalk_3.23.0-1_all.deb)  
> `0c80e85b90c7a366c785e392b4fe2a1dc8ce67b5cc1940e5f9a9d1878c1cbae9` (SHA-256)


### Windows

Be sure to install a [compatible](#requirements) Prolog compiler
**before** running the Logtalk installer. Creates a `Logtalk` program
group in the `Start Menu` with integration shortcuts for supported
Prolog compilers and shortcuts for the accessing the Logtalk
documentation. Can be used by both admin and non-admin users.

> [`logtalk-3.23.0.exe`](files/logtalk-3.23.0.exe)  
> `a15c9ac35391a3b16578f95317589532c4bd45304fcb2589fb74279e86265d6b` (SHA-256)


### SWI-Prolog pack

Logtalk is also available as a SWI-Prolog pack. The
[pack](http://www.swi-prolog.org/pack/list?p=logtalk) is handy for
*deployment* but not ideal for *development*, however, as the all the
files in the distribution are buried in a relatively deep sub-directory.
The pack can be easily installed typing the query `pack_install(logtalk)`
at the top-level. Also available as a manual download.

> [`logtalk-3.23.0.tgz`](files/swi-prolog/packs/logtalk-3.23.0.tgz)  
> `05438fe64ebb535fd7ee100cc23d4310bd60b5ee9df4c156a48fc86d068ef4b3` (SHA-256)


### Arch Linux package

Logtalk is also available as an Arch Linux
[package](https://aur.archlinux.org/packages/logtalk/) contributed by
Ebrahim Azarisooreh.


## Documentation

HTML, ePub, and PDF versions of the Handbook (includes a tutorial, the User Manual, the Reference Manual, and the FAQ).
Note that the HTML version is **included** in the source and binary packages.

> [`logtalk-manuals-3.23.0.tgz`](files/logtalk-manuals-3.23.0.tgz)  
> `3ba56dd6b6f98dc3f20b9b525af3cdb2b35e0d6af5628e16cdd60465bd952419` (SHA-256)


## Docker images

Nightly and stable Docker images are [available](https://hub.docker.com/u/logtalk/) using selected backend Prolog compilers.


## Older versions

Older releases are available [here](/files/) (but note that time stamps
do not match the release dates due to all the moving of these files
between servers along the years).


## Registration

Consider [registering](regform.html) if you become a Logtalk user.
