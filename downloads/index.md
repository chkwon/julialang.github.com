---
layout: default
title:  Julia Downloads
---

# Current Release (v0.4.6)

We provide several ways for you to run Julia:

* In the terminal using the built-in Julia command line.
* The [Juno](http://www.junolab.org) integrated development environment (IDE).
* In the browser on [JuliaBox.com](https://www.juliabox.com) with Jupyter notebooks. No installation is required -- just point your browser there, login and start computing.

Plotting capabilities are provided by external packages such as
[PyPlot.jl](https://github.com/stevengj/PyPlot.jl) and [Gadfly.jl](http://gadflyjl.org). 
A package which integrates most of Julia's plotting backends into one convenient and 
well-documented API is [Plots.jl](https://github.com/tbreloff/Plots.jl). Look at the 
[plotting instructions](plotting.html) to install a plotting package. If you are using 
JuliaBox, all of these plotting packages are pre-installed.

## Julia (command line version)
<table class="downloads"><tbody>
<tr>
    <th> Windows Self-Extracting Archive (.exe) </th>
    <td colspan="3"> <a href="https://s3.amazonaws.com/julialang/bin/winnt/x86/0.4/julia-0.4.6-win32.exe">32-bit</a> </td>
    <td colspan="3"> <a href="https://s3.amazonaws.com/julialang/bin/winnt/x64/0.4/julia-0.4.6-win64.exe">64-bit</a> </td>
</tr>
<tr>
    <th> Mac OS X Package (.dmg) </th>
    <td colspan="6"> <a href="https://s3.amazonaws.com/julialang/bin/osx/x64/0.4/julia-0.4.6-osx10.7+.dmg">10.7+ 64-bit</a> </td>
</tr>
<tr>
    <th> Generic Linux binaries </th>
    <td colspan="3"> <a href="https://julialang.s3.amazonaws.com/bin/linux/x86/0.4/julia-0.4.6-linux-i686.tar.gz">32-bit</a> (<a href="https://julialang.s3.amazonaws.com/bin/linux/x86/0.4/julia-0.4.6-linux-i686.tar.gz.asc">GPG</a>)</td>
    <td colspan="3"> <a href="https://julialang.s3.amazonaws.com/bin/linux/x64/0.4/julia-0.4.6-linux-x86_64.tar.gz">64-bit</a> (<a href="https://julialang.s3.amazonaws.com/bin/linux/x64/0.4/julia-0.4.6-linux-x86_64.tar.gz.asc">GPG</a>)</td>
</tr>
<tr>
    <th> Fedora/RHEL/CentOS/SL packages (.rpm) </th>
    <td colspan="6"> <a href="https://copr.fedoraproject.org/coprs/nalimilan/julia/">32/64-bit</a> </td>
</tr>
<tr>
    <th> Source </th>
    <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v0.4.6/julia-0.4.6.tar.gz">Tarball</a> (<a href="https://github.com/JuliaLang/julia/releases/download/v0.4.6/julia-0.4.6.tar.gz.asc">GPG</a>) </td>
    <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v0.4.6/julia-0.4.6-full.tar.gz">Tarball with dependencies</a><br> (<a href="https://github.com/JuliaLang/julia/releases/download/v0.4.6/julia-0.4.6-full.tar.gz.asc">GPG</a>) </td>
    <td colspan="2"> <a href="https://github.com/JuliaLang/julia/tree/release-0.4">GitHub</a> </td>
</tr>
</tbody></table>

Please see [platform](platform.html) specific instructions if you have
trouble installing Julia.  Checksums for this release are available in both [MD5](https://s3.amazonaws.com/julialang/bin/checksums/julia-0.4.6.md5) and [SHA256](https://s3.amazonaws.com/julialang/bin/checksums/julia-0.4.6.sha256) format.

If the provided download files do not work for you, please [file an
issue in the Julia project](https://github.com/JuliaLang/julia/issues). It is strongly
recommended that you download the v0.4.x binaries to try out Julia,
unless you are working with code that was developed specifically for a
previous release.


## Juno IDE

Please see the [Juno website](http://junolab.org) for setup instructions, and [the discussion forum](http://discuss.junolab.org) for any questions or issues.

# Older Releases

Older releases of Julia for all platforms are available on the [Older releases page](http://julialang.org/downloads/oldreleases.html).

For Julia 0.3, only critical bugfixes are being supported. Releases older than 0.3 are now unmaintained.

# Release Candidates (v0.5.0-rc2)

We are currently testing release candidates for the next version of Julia. Please see
[platform](platform.html) specific instructions if you have trouble installing Julia.
Checksums for this release are available in both
[MD5](https://s3.amazonaws.com/julialang/bin/checksums/julia-0.5.0-rc2.md5)
and [SHA256](https://s3.amazonaws.com/julialang/bin/checksums/julia-0.5.0-rc2.sha256) format.
Download the release candidate here, and please report any issues to the
[issue tracker](https://github.com/JuliaLang/julia/issues) on GitHub.
Full tarballs contain all dependencies bundled within the tarball alongside Julia,
allowing for easy install in environments without network access. The standard
tarball is much smaller in size, but will download dependency tarballs on demand.

## Julia (command line version)
<table class="downloads"><tbody>
<tr>
    <th> Windows Self-Extracting Archive (.exe) </th>
    <td colspan="3"> <a href="https://s3.amazonaws.com/julialang/bin/winnt/x86/0.5/julia-0.5-latest-win32.exe">32-bit</a> </td>
    <td colspan="3"> <a href="https://s3.amazonaws.com/julialang/bin/winnt/x64/0.5/julia-0.5-latest-win64.exe">64-bit</a> </td>
</tr>
<tr>
    <th> Mac OS X Package (.dmg) </th>
    <td colspan="6"> <a href="https://s3.amazonaws.com/julialang/bin/osx/x64/0.5/julia-0.5-latest-osx10.7+.dmg">10.7+ 64-bit</a> </td>
</tr>
<tr>
    <th> Generic Linux binaries </th>
    <td colspan="3"> <a href="https://julialang.s3.amazonaws.com/bin/linux/x86/0.5/julia-0.5-latest-linux-i686.tar.gz">32-bit</a> (<a href="https://julialang.s3.amazonaws.com/bin/linux/x86/0.5/julia-0.5.0-rc2-linux-i686.tar.gz.asc">GPG</a>)</td>
    <td colspan="3"> <a href="https://julialang.s3.amazonaws.com/bin/linux/x64/0.5/julia-0.5.0-rc2-linux-x86_64.tar.gz">64-bit</a> (<a href="https://julialang.s3.amazonaws.com/bin/linux/x64/0.5/julia-0.5.0-rc2-linux-x86_64.tar.gz.asc">GPG</a>)</td>
</tr>
<tr>
    <th> Source </th>
    <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v0.5.0-rc2/julia-0.5.0-rc2.tar.gz">Tarball</a> (<a href="https://github.com/JuliaLang/julia/releases/download/v0.5.0-rc2/julia-0.5.0-rc2.tar.gz.asc">GPG</a>) </td>
    <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v0.5.0-rc2/julia-0.5.0-rc2-full.tar.gz">Tarball with dependencies</a> (<a href="https://github.com/JuliaLang/julia/releases/download/v0.5.0-rc2/julia-0.5.0-rc2-full.tar.gz.asc">GPG</a>) </td>
    <td colspan="2"> <a href="https://github.com/JuliaLang/julia/tree/release-0.5">GitHub</a> </td>
</tr>
</tbody></table>

# Nightly builds

These are bleeding-edge binaries of the latest version of Julia under
development, which you can use to get a preview of the latest work.  However,
because Julia is under heavy development, you may be unlucky and get a
build with a serious bug, or one which breaks existing packages.  Most users
are advised to use the latest official release version of Julia, above.

<table class="downloads"><tbody>
<tr>
    <th> Windows Self-Extracting Archive (.exe) </th>
    <td> <a href="https://status.julialang.org/download/win32">32-bit</a> </td>
    <td colspan="2"> <a href="https://status.julialang.org/download/win64">64-bit</a> </td>
</tr>
<tr>
    <th> Mac OS X Package (.dmg) </th>
    <td colspan="3"> <a href="https://status.julialang.org/download/osx10.7+">10.7+ 64-bit</a> </td>
</tr>
<tr>
    <th> Generic Linux binaries </th>
    <td> <a href="https://status.julialang.org/download/linux-i686">32-bit (X86)</a> </td>
    <td> <a href="https://status.julialang.org/download/linux-x86_64">64-bit (X86)</a> </td>
    <td> <a href="https://status.julialang.org/download/linux-arm">32-bit (ARM)</a> </td>
</tr>
<tr>
    <th> Fedora/RHEL/CentOS/SL packages (.rpm) </th>
    <td colspan="3"> <a href="https://copr.fedoraproject.org/coprs/nalimilan/julia-nightlies/">32/64-bit</a> </td>
</tr>
<tr>
    <th> Source </th>
    <td colspan="3"> <a href="https://github.com/JuliaLang/julia">GitHub</a> </td>
</tr>
</tbody></table>

---

# Download verification
All Julia binary releases are cryptographically secured using the traditional methods on each
operating system platform.  OS X and Windows releases are codesigned by certificates that are
verified by the operating system before installation.  Generic Linux tarballs and source tarballs
are signed via GPG using [this key](../juliareleases.asc).  Ubuntu and Fedora/RHEL/CentOS/SL
releases are signed by their own keys that are verified by the package managers when installing.
