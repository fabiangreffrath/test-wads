# test-wads
This repository holds a collection of small self-contained WAD files contributed by the Doom community to test the proper function of certain features of Doom source ports.

WAD file | Description | Author | Source
--- | --- | --- | ---
512x512.wad | The engine renders well textures 512px wide, but not taller than 256px. Example map updated for few additional segments: Bottom (bot),  Middle (mid), Top (top), Masked middle texture (mask). | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/162
bmaps*.wad, brighttan.wad | Testing maps for brightmaps. They should be loaded depending of the game (Doom 1, 2 or TNT), because different games have/using slightly different names and textures. Also added few sprites, glowing sectors and upper/lower segmented walls. | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/246
deadoof.wad | Oof sound by dead player (player should kill himself with rocket launcher). | @JNechaevsky | https://github.com/fabiangreffrath/test-wads/issues/1#issuecomment-733140322
fakecontrast.wad | Fake contrast checking, "Mickey Mouse ears" with different curve distances. | @JNechaevsky | https://github.com/fabiangreffrath/test-wads/issues/1#issuecomment-733140322
intercepts.wad | Just a pile of sprites in one place, as well as bunch of lines. Try to shoot through pile of 148 imps and BLOCKMAP will stop working. | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/227
longtex2.wad | ﻿The wall with the torch is a texture that's 666px long but made of patches 512px long. The﻿ wall that says 666 is a texture that's 1024px long but made of patches﻿ that are 666px﻿ long. The wall that says 1024 is﻿ a patch/texture that is 1024px﻿﻿ long,﻿ you see the end of the texture﻿﻿. | @kitchen-ace | https://www.doomworld.com/forum/topic/112333-this-is-woof-232-oct-19-2020-updated-winmbf/?do=findComment&comment=2143327
longwall.wad | Long wall wobble. | @JNechaevsky | https://github.com/fabiangreffrath/test-wads/issues/1#issuecomment-733140322
medusa.wad | Medusa (careful! it silently crashes Chocolate Doom, DOS executable survives). | @JNechaevsky | https://github.com/fabiangreffrath/test-wads/issues/1#issuecomment-733140322
odddoor.wad | Dead player beneath the door is able to see level's "out of bounds". | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/257#issuecomment-359877982
switches3.wad | Checking texture changing with various applied textures to the top/middle/bottom (note: will have to be loaded with `-merge` in Choco). | @JNechaevsky, @jeffdoggett | https://github.com/fabiangreffrath/test-wads/issues/1#issuecomment-733140322
teapot16.wad | Demo map and teapot with 16 rotations (also with indication of angle and sprite name). | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/152#issuecomment-280902515
transparent_textures.wad | Transparent textures used as an upper or lower texture, or on a 1-sided wall as a mid texture, produce visual glitches from undefined results. | @kitchen-ace | https://github.com/fabiangreffrath/crispy-doom/issues/23
tutti.wad | Tutti-Frutti effect (but have you seen it's effect on sprites?) | @JNechaevsky | https://github.com/fabiangreffrath/test-wads/issues/1#issuecomment-733140322
visplanes1.wad | `R_CheckPlane: no more visplanes` error. Just slightly rotate camera left/right. | @JNechaevsky | https://github.com/fabiangreffrath/test-wads/issues/1#issuecomment-736735709

Unless otherwise noted, all files are copyrighted by their respective authors and licensed under the terms of [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/).
