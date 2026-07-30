# Third-party notices

This repository vendors printing components that are not mine. They keep their
own licences and copyright, and are not covered by this project's LICENSE.

| Path | Component | Licence | Copyright |
|:--|:--|:--|:--|
| `newdir/pappl/` | PAPPL, the Printer Application Library | Apache-2.0 | Michael R Sweet; Apple Inc.; Easy Software Products |
| `newdir/Source/Screens/lprint/` | LPrint | Apache-2.0 | Michael R Sweet |

Both carry their full `LICENSE` and `NOTICE` files in place. Read those before
redistributing. Apache-2.0 requires that you keep the notices and state any
changes you make.

Upstream:

- PAPPL: https://github.com/michaelrsweet/pappl
- LPrint: https://github.com/michaelrsweet/lprint

The generated files under `newdir/JuceLibraryCode/` are Projucer output. JUCE
itself is not vendored here; building requires your own JUCE checkout under
whatever JUCE licence applies to you.
