First of all, some words straight from the [BrickSync website](http://www.bricksync.net/):

*BrickSync is a piece of software meant to run on a LEGO seller's computer to synchronize inventories between the [BrickLink](http://www.bricklink.com/) and [BrickOwl](http://www.brickowl.com/) marketplaces, with many feature beyond this. All incoming orders (and backups) are stored as [BrickStore/BrickStock](http://brickstock.patrickbrans.com/) compatible BSX files, and the software can merge in new inventory (or update prices, and so on) from files in that same BSX format.*

*BrickSync is free, open source and donation supported. Since the version 1.7.1, the source code was made public and no registration is needed.*


*The source code is released under a very permissible license, you can do pretty much whatever you want with this source code and altered versions.*

*More precisely, here's the relevant legalese:*

> Copyright (c) 2014-2019 Alexis Naveros.
>
> This software is provided 'as-is', without any express or implied
warranty. In no event will the authors be held liable for any damages
arising from the use of this software.
>
> Permission is granted to anyone to use this software for any purpose,
including commercial applications, and to alter it and redistribute it
freely, subject to the following restrictions:
>
> 1. The origin of this software must not be misrepresented; you must not
claim that you wrote the original software. If you use this software
in a product, an acknowledgment in the product documentation would be
appreciated but is not required.
2. Altered source versions must be plainly marked as such, and must not be
misrepresented as being the original software.
3. This notice may not be removed or altered from any source distribution.


*The source code is written in C with GNUisms, therefore it will compile with GCC, mingw64, Clang or the Intel Compiler. The only dependency is OpenSSL for socket encryption. The source code includes a build-win64 subdirectory with headers and DLLs for OpenSSL on Windows; the code therefore will build with a plain freshly installed mingw64 (select x86-64 as target when installing mingw64, not i686).*

---

Testament to Alexis' work, since its last update sometime in 2019, BrickSync has been running happily without any major issues. Then new colours were introduced and changes to the BrickSync code became necessary.

Community members have started providing fixes and unofficial builds are shared through forum posts. This is an attempt to gather all of those small fixes in one place and at least maintain a public version of the latest codebase and make sure that the work of those members does not get lost.

In time, the latest builds may also be distributed from here.  

---

LEGO, the LEGO logo are trademarks of The LEGO Group of companies.
