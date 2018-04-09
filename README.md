# splash v0.0.3

A reusable splash screen for TIC-80 games.  `splash_ugly.moon` works
but is horrible. `splash_trigs.moon` is slightly less horrible, but
still not ideal.  `splash.moon` implements it in an actually reusable
way.

`splash()` returns `true` when finished, so it can be called like
this:

    if splash!
    	print "GAME CODE GOES HERE",100,100,3

Licensed under the [GPLv3](https://www.gnu.org/licenses/gpl-3.0.md).
