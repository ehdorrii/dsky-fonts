# dsky-fonts
Fonts for creating authentic-looking DSKY emulation

The DSKY ("display and keyboard") was the user interface to the Apollo Guidance Computer (AGC). I've worked hard to create an authentic-looking DSKY emulation, and one of the tough parts was getting a font that looked right. I spent years (on and off) trying to find a font that matched the markings on the keytops and annunciator displays, and came up empty-handed.

In 2018 and 2019 Ron Burkey (creator of "Virtual AGC" -- see https://www.ibiblio.org/apollo/) spent a goodly chunk of time at the NARA (National Archives and Records Administration) Southwest Regional Center scanning engineering drawings for the AGC (see https://www.ibiblio.org/apollo/QuestForInfo.html), and one of the drawings for the DSKY included the the note "Markings ... shall be Gorton Normal". Aha!

I'd never heard of "Gorton", and searching for a font of that name uncovered the fact that it was *not*, in fact, a font. It turns out that "back in the day", before computers were used to create all imaginable graphics, there were mechanical means of doing lettering. "Gorton" was a company that made engraving machines, which were kind of like pantographs. They provided various "stencils" or patterns for engraving lettering (this was often used on aircraft instrument panels -- see the link?), and one of these was called "Gorton Normal". So this wasn't as fancy as a font -- it was just a pattern that was traced. The "weight" was simply the size of the engraving tool that was used, and there was no variation in the strokes.

Researching Gorton, I found some catalogs that had been scanned, plus a photo of a set of stencils. From these I was able to use Font Forge to create a set of splines, and from that to create a pair of font files: Gorton Normal as used on the DSKY keycaps, and Gorton "Condensed" as used on the annuciator display.

I've also included a quite accurate reproduction of the digital part of the display, which I've named "Zerlina" after the Luminary test build named by Don Eyles.
