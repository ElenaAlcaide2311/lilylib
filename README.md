oll-lib
-------

This folder contains the LilyPond library within the **`openLilyLib`** family of resources.

---

To use it you should make the current folder available to LilyPond, either by adding it to your PATH or by supplying it to LilyPond as an include dir.

Then use  
`\include "oll-lib/full.ily"`  
to activate the full library, or  
`\include "oll-lib/XXX.ily"`  
to only use partial libs.

`oll-includes/`  
contains material that can individually be included, such as engravers, score blocks or style sheets.

`examples/`  
contains working examples, "best practice" etc.

`templates/`  
aren't usually included but used by copying its content.
They often work together with the "examples"