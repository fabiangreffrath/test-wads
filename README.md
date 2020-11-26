# test-wads
This repository holds a collection of small self-contained WAD files contributed by the Doom community to test the proper function of certain features of Doom source ports.

WAD file | Description | Author | Source
--- | --- | --- | ---
512x512.wad | The engine renders well textures 512px wide, but not taller than 256px. Example map updated for few additional segments: Bottom (bot),  Middle (mid), Top (top), Masked middle texture (mask). | @JNechaevsky | https://github.com/fabiangreffrath/crispy-doom/issues/162
longtex2.wad | ﻿The wall with the torch is a texture that's 666px long but made of patches 512px long. The﻿ wall that says 666 is a texture that's 1024px long but made of patches﻿ that are 666px﻿ long. The wall that says 1024 is﻿ a patch/texture that is 1024px﻿﻿ long,﻿ you see the end of the texture﻿﻿. | @kitchen-ace | https://www.doomworld.com/forum/topic/112333-this-is-woof-232-oct-19-2020-updated-winmbf/?do=findComment&comment=2143327
transparent_textures.wad | Transparent textures used as an upper or lower texture, or on a 1-sided wall as a mid texture, produce visual glitches from undefined results. | @kitchen-ace | https://github.com/fabiangreffrath/crispy-doom/issues/23

Unless otherwise noted, all files are copyrighted by their respective authors and licensed under the terms of [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/).
