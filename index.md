---
layout: default
---
[xde-theme-circuits -- read me first file.  2014-09-12]: #

xde-theme-circuits
===============

Package `xde-theme-circuits-1.1.4` was released under CCPL:cc-by-nc-nd-3.0
license 2014-09-12.

This is a theme and a set of backgrounds for the _XDE (X Desktop
Environment)_ that provides a set of backgrounds on
an Electronic Circuit theme.
This theme uses the Squared-blue style from the [`xde-styles`][11]
package.

The source for `xde-theme-circuits` is hosted on [GitHub][1].


Release
-------

This is the `xde-theme-circuits-1.1.4` package, released 2014-09-12.
This release, and the latest version, can be obtained from [GitHub][1],
using a command such as:

    $> git clone https://github.com/bbidulock/xde-theme-circuits.git

Please see the [RELEASE][3] and [NEWS][4] files for release notes and
history of user visible changes for the current version, and the
[ChangeLog][5] file for a more detailed history of implementation
changes.  The [TODO][6] file lists features not yet implemented and
other outstanding items.

Please see the [INSTALL][8] file for installation instructions.

When working from `git(1)`, please use this file.  An abbreviated
installation procedure that works for most applications appears below.

This release is published under CCPL:cc-by-nc-nd-3.0 (primarily because
the base styles used to develop these styles were licensed under this
license).
Please see the license in the file [COPYING][10].


Quick Start
-----------

The quickest and easiest way to get `xde-theme-circuits` up and
running is to run the following commands:

    $> git clone https://github.com/bbidulock/xde-theme-circuits.git
    $> cd xde-theme-circuits
    $> ./autogen.sh
    $> ./configure
    $> make
    $> make DESTDIR="$pkgdir" install

This will configure, compile and install `xde-theme-circuits` the
quickest.  For those who like to spend the extra 15 seconds reading
`./configure --help`, some compile time options can be turned on and off
before the build.

For general information on GNU's `./configure`, see the file
[INSTALL][8].


Prerequisites
-------------

This package needs the [`xde-styles`][11] package to be useful and also
requires the `xde-setbg(1)` program from the [`xde-ctools`][12] package.


Issues
------

Report issues on GitHub [here][2].


Samples
-------

Following is a sample screenshot of the theme taken under the [ADWM][13]
window manager:

![adwm.jpg](scrot/adwm.jpg "Wallpaper #1")

Following are the five wallpapers included in the theme:

![gerber2.jpg](images/gerber2.jpg "Wallpaper #1")
![4portoc48.jpg](images/4portoc48.jpg "Wallpaper #2")
![8portcard-pcie.jpg](images/8portcard-pcie.jpg "Wallpaper #3")
![gerber.jpg](images/gerber.jpg "Wallpaper #4")
![optics.jpg](images/optics.jpg "Wallpaper #5")



[1]: https://github.com/bbidulock/xde-theme-circuits
[2]: https://github.com/bbidulock/xde-theme-circuits/issues
[3]: https://github.com/bbidulock/xde-theme-circuits/blob/master/RELEASE
[4]: https://github.com/bbidulock/xde-theme-circuits/blob/master/NEWS
[5]: https://github.com/bbidulock/xde-theme-circuits/blob/master/ChangeLog
[6]: https://github.com/bbidulock/xde-theme-circuits/blob/master/TODO
[7]: https://github.com/bbidulock/xde-theme-circuits/blob/master/COMPLIANCE
[8]: https://github.com/bbidulock/xde-theme-circuits/blob/master/INSTALL
[9]: https://github.com/bbidulock/xde-theme-circuits/blob/master/LICENSE
[10]: https://github.com/bbidulock/xde-theme-circuits/blob/master/COPYING
[11]: https://github.com/bbidulock/xde-styles
[12]: https://github.com/bbidulock/xde-ctools
[13]: https://bbidulock.github.io/adwm

[ vim: set ft=markdown sw=4 tw=72 nocin nosi fo+=tcqlorn spell: ]: #
