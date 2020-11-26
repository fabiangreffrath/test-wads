# test-wads
This repository holds a collection of small self-contained WAD files contributed by the Doom community to test the proper function of certain features of Doom source ports.

WAD file | Description | Author | Source
--- | --- | --- | ---
512x512.wad | The engine renders well textures 512px wide, but not taller than 256px. Example map updated for few additional segments: Bottom (bot),  Middle (mid), Top (top), Masked middle texture (mask). | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/162
bmaps*.wad, brighttan.wad | Testing maps for brightmaps. They should be loaded depending of the game (Doom 1, 2 or TNT), because different games have/using slightly different names and textures. Also added few sprites, glowing sectors and upper/lower segmented walls. | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/246
fakecont.wad | Test map with the "Mickey Mouse ears" to demonstrate the effect of fake contrast, extended with an area of abstract structures and segments. | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/commit/ec6a9cda5468efff3848b814f571d59f8b1cd54d#commitcomment-28530713
longtex2.wad | ﻿The wall with the torch is a texture that's 666px long but made of patches 512px long. The﻿ wall that says 666 is a texture that's 1024px long but made of patches﻿ that are 666px﻿ long. The wall that says 1024 is﻿ a patch/texture that is 1024px﻿﻿ long,﻿ you see the end of the texture﻿﻿. | @kitchen-ace | https://www.doomworld.com/forum/topic/112333-this-is-woof-232-oct-19-2020-updated-winmbf/?do=findComment&comment=2143327
odddoor.wad | Dead player beneath the door is able to see level's "out of bounds". | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/257#issuecomment-359877982
switches3.wad | Upper texture is preventing switch animation. | @JNechaevsky, @jeffdoggett | https://github.com/JNechaevsky/russian-doom/issues/55#issuecomment-376272193
teapot16.wad | Demo map and teapot with 16 rotations (also with indication of angle and sprite name). | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/152#issuecomment-280902515
transparent_textures.wad | Transparent textures used as an upper or lower texture, or on a 1-sided wall as a mid texture, produce visual glitches from undefined results. | @kitchen-ace | https://github.com/fabiangreffrath/crispy-doom/issues/23

Unless otherwise noted, all files are copyrighted by their respective authors and licensed under the terms of [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/).
