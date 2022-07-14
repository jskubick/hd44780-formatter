# hd44780-formatter
Makes it easy to implement things like marquees and "condensed decimal" values on character LCDs

This will eventually be an Arduino library, but for now I'm doing its development as a submodule of a Windows
app that runs an emulated HD44780 to make it easier to debug.  I'm doing it as a separate repo used as a submodule
of the Windows project to keep everything that's Windows-specific segregated away from the "pure" library itself.

To play with it now, go to https://github.com/jskubick/vrEmuLcd4win
