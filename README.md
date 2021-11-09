# expak (.PAKZ support)
This is a hastily hacked together version of expak,
that adds a special case for the .PAKZ variant that
can be found in some [Zeebo](https://en.wikipedia.org/wiki/Zeebo) 
games. All it does is add the sufix ".lzma" to every 
extracted file, so that it can then be uncompressed
using [7-Zip](https://www.7-zip.org/).

To reiterate: There is no built-in LZMA decompression
here, this is a quick workaround I made for personal
use.

---

**Check out the [original README](readme.rst) for
more info.**