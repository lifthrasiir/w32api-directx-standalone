# w32api-directx-standalone

Alternative DirectX headers for [MinGW](http://mingw.org/) w32api headers.

Originated from [Wine](http://www.winehq.org/) and
[MinGW-w64](http://sourceforge.net/projects/mingw-w64/) headers, this can be
used to override the existing DirectX headers included in the stock MinGW, for
example, by `-isystem` GCC option. Since w32api does not include some headers
like `d3dcompiler.h` this can be used to port MSVC projects to MinGW. Some
modifications have been made in order to keep the header files standalone, grep
`w32api-directx-standalone patch` for the details.

These header files are licensed under the GNU LGPL. The original README file can
be found at `readme.mingw-w64.txt`.

