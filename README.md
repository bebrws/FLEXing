# My ( bebrws ) changes

I added a blacklist of processes NOT to inject into. There is a file, "/var/root/flexconfig.txt", that is line seperated.
If the bundle identifier contains a string from a line in that file then it won't load.

If you build this locally just overwrite the dylib at:
/Library/MobileSubstrate/DynamicLibraries/FLEXing.dylib

Maybe I'll make a deb and repo and stuff..


# FLEXing

FLEXing is a basic tweak to activate the FLEX explorer via Activator or long pressing on the status bar (depending on your iOS version you will want to use the appropriate version from the releases tab).

### Isn't this the same thing as FLEXible?

Well, yes, but FLEXible 1) isn't open source, and 2) forces you turn it on on a per-application basis and deal with re-opening the explorer every time you start or return to an application unless you want to turn it back off.

For someone like me who uses FLEX all the time in the apps I also use all the time, it's a little more than annoying to turn it on every time I want to use it or to have it pop up every time I open the app.

# License

BSD for my code and for FLEX itself.
