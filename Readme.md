Primitives
=========

Primitives is a lightweight drop-in replacement for the geometric primitives rendering functions in SDL2_gfx

I had some difficultly getting the dynamic library version working on Windows in Visual C++ 2012, and I realised that the actual functions I needed were neatly contained mostly in SDL2_gfxPrimitives.c, so I stripped out the font rendering functions that were causing me difficulty and removed any decorators declaring functions for a dynamic library.

- Jonathan Powell - jpowell at jpowell dot co dot uk

Version
-

0.1

Installation
--------------

Just drop the two files into your C++ project and #include "Primitives.h" in any file where you want to use the SDL2_gfx primitive rendering functions.


Original License
-




SDL2_gfxPrimitives.c: graphics primitives for SDL2 renderers

Copyright (C) 2012  Andreas Schiffler

This software is provided 'as-is', without any express or implied
warranty. In no event will the authors be held liable for any damages
arising from the use of this software.

Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:

1. The origin of this software must not be misrepresented; you must not
claim that you wrote the original software. If you use this software
in a product, an acknowledgment in the product documentation would be
appreciated but is not required.

2. Altered source versions must be plainly marked as such, and must not be
misrepresented as being the original software.

3. This notice may not be removed or altered from any source
distribution.

Andreas Schiffler -- aschiffler at ferzkopp dot net