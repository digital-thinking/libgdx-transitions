# libgdx-transitions
==================================

This library uses framebuffers for screen transitions in libgdx  like, alpha-fading, color-fading, sliding and slicing. The Game class has been extended to FadingGame, which applies transitions, when setScreen is called. Allows callbacks on start and end of the transitions.

Installation
------------
1. Make libGDX running on your system
2. Download  the [jar](https://github.com/iXeption/libgdx-transitions/releases/download/release/libgdx-transitions-0.0.1.jar)
3. Add gradle dependency

Or just use the source.

Usage
------------
You can take a look at the [TestCase](https://github.com/iXeption/libgdx-transitions/wiki) to see how it works. You can just replace GdxTest with ApplicationListener and start it from your libgdx project.

If you are using the libgdx Game class you can do the following:

1. Replace your Game class with FadingGame.
2. Create transistions 
3. Use setTransition to set the current transition
4. The next time setScreen is called the transition is executed
5. Use TransitionLsteners


License
------------
Apache 2 License

Contact
------------
Ask me:
github@ixeption.de