# expak (.PAKZ support)
This is a hastily hacked together version of expak,
that adds a special case for the .PAKZ variant that
can be found in some [Zeebo](https://en.wikipedia.org/wiki/Zeebo) 
games. All it does is add the sufix ``.lzma`` to every 
extracted file, so that it can then be uncompressed
using [7-Zip](https://www.7-zip.org/).

To reiterate: There is no built-in LZMA decompression
here, this is a quick workaround I made for personal
use.

**Check out the [original README](README.rst) for
more info.**

## Zeebo titles that use .PAKZ
- 276153 - Quake II
- 276809 - Zeebo Extreme Rolimã
- 277285 - Zeebo Extreme Corrida Aérea
- 277727 - Zeebo Extreme Baja
- 278285 - Zeebo Extreme Bóia Cross
- 277534 - Zeebo Sports Tênis
- 278212 - Zeebo Sports Vôlei
- 278283 - Zeebo Extreme Jetboard
- 278738 - Zeebo Sports Queimada
- 279159 - Zeebo Sports Peteca
- 279380 - Zeebo F.C. Foot Camp
- 279382 - Zeeboids
- 280386 - Alice no País das Maravilhas
- 280634 - Turma da Mônica em: Vamos Brincar Vol. 1
- 280647 - Zeebo F.C. Super League
