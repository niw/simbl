Unofficial SIMBL repository
===========================

This is a copied, exported repository from original one [hosted on Google Code](https://code.google.com/p/simbl/).
Also see [SIMBL web size](http://www.culater.net/software/SIMBL/SIMBL.php).

Changes
-------

``master`` branch contains a few changes to make it works with current OS X and Xcode.

Build
-----

Use xcodebuild to get ``SIMBL.osax``, then open ``pkg/SIMBL.pmdoc`` by PackageMaker to build pkg file.

    xcodebuild -project SIMBL.xcodeproj

You can still download PackageMaker from [Apple's download page](https://developer.apple.com/downloads/) as a part of *Auxiliary Tools fro Xcode - Late July 2012*.

License
-------

[GNU GPL v2](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
