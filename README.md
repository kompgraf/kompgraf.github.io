#  DE IK Komputergrafika 18/19/1

## A gyakorlatok helye, ideje

| Időpont                | Terem      |
|------------------------|------------|
| **hétfő, 14:00-16:00** | **IK-103** |
| **kedd, 16:00-18:00**  | **IK-207** |

## A gyakorlatvezetőről

Sziasztok! Bagossy Attila vagyok, harmadik féléves PTI MSc. hallgató. 

Ha kérdésetek, ötletetek, javaslatotok van, bátran írjatok e-mailt a következő címre:

> bagossyattila@outlook.com

Amennyiben olyan felvetéssel, problémával rendelkeztek, mely a tárgyat felvevő többi hallgatót is érinti, válasszátok inkább a Piazzát (részletek lentebb)!

## A félév tervezett rendje

### Gyakorlati tematika a hétfői csoport számára

| Időpont               | A gyakorlat témája                                | Megjegyzés                                                          |
|-----------------------|---------------------------------------------------|---------------------------------------------------------------------|
| 2018. szeptember 10.  | Görbék megadási módja, Lagrange-interpoláció.     |                                                                     |
| 2018. szeptember 17.  | Hermite-ív, Hermite Spline, Hatékony kiértékelés  |                                                                     |
| 2018. szeptember 24.  | Bézier-görbe                                      |                                                                     |
| 2018. október 01.     | Cardinal Spline                                   |                                                                     |
| 2018. október 08.     | B-Spline                                          | 1. HF                                                               |
| 2018. október 15.     | NURBS                                             | 2. HF                                                               |
| 2018. november 05.    | Bézier-felület, NURBS-felület                     | 3. HF                                                               |
| 2018. november 12.    | Subdivision görbék                                | 4. HF                                                               |
| 2018. november 19.    | **1. védés** (1-2-3. HF)                          | Utolsó effektív commit: **2018. november 18. 08:00**                |
| 2018. november 26.    | A Half Edge adatszerkezet                         |                                                                     |
| 2018. december 03.    | Primál és duál subdivision felületek              | 5. HF                                                               |
| 2018. december 10.    | Felületek, görbék és GUI                          |                                                                     |
| 2018. december 17.    | **2. védés/1. pótvédés** (4-5. HF)                | Vizsgaidőszak, Utolsó effektív commit: **2019. december 16. 08:00** |
| 2019. január          | **2. pótvédés**                                   | Vizsgaidőszak                                                       |

### Gyakorlati tematika a keddi csoport számára


| Időpont               | A gyakorlat témája                                | Megjegyzés                                                          |
|-----------------------|---------------------------------------------------|---------------------------------------------------------------------|
| 2018. szeptember 18.  | Görbék megadási módja, Lagrange-interpoláció.     |                                                                     |
| 2018. szeptember 25.  | Hermite-ív, Hermite Spline, Hatékony kiértékelés  |                                                                     |
| 2018. október 02.     | Bézier-görbe                                      |                                                                     |
| 2018. október 09.     | Cardinal Spline                                   |                                                                     |
| 2018. október 16.     | B-Spline, NURBS                                   | 1-2. HF                                                             |
| 2018. november 06.    | Bézier-felület, NURBS-felület                     | 3. HF                                                               |
| 2018. november 13.    | Subdivision görbék                                | 4. HF                                                               |
| 2018. november 20.    | **1. védés** (1-2-3. HF)                          | Utolsó effektív commit: **2018. november 19. 08:00**                |
| 2018. november 27.    | A Half Edge adatszerkezet                         |                                                                     |
| 2018. december 04.    | Primál és duál subdivision felületek              | 5. HF                                                               |
| 2018. december 11.    | Felületek, görbék és GUI                          |                                                                     |
| 2018. december 17.    | **2. védés/1. pótvédés** (4-5. HF)                | Vizsgaidőszak, Utolsó effektív commit: **2019. december 16. 08:00** |
| 2019. január          | **2. pótvédés**                                   | Vizsgaidőszak                                                       |

### Számonkérések
  
A gyakorlaton megszerzett tudás számonkérése programvédések formájában történik. A félév során két védésre fog sor kerülni, az első védésen az 1-2-3. házi feladatok, a második védésen a 4-5. házi feladatok bemutatása lehetséges.

A pótvédésen lehetőség van a normál védésen nem elfogadott vagy nem bemutatott programok megvédésére.

A programvédések menete a következő:

  1. A hallgató elkészíti a házi feladatot, és a kódot rendszeresen feltölti a számára az adott feladathoz létrehozott GitHub repositoryba.
  1. A gyakorlatvezető a védést megelőzően, az *utolsó effektív commit* időpontja előtti utolsó feltöltött commitnak megfelelő állapotban megvizsgálja a repository tartalmát. Ez magában foglalja a csalások kiszűrését is.
  1. A védésen a hallgató megmutatja futás közben a programot, majd pedig a gyakorlatvezető kérdéseire adott válaszokon keresztül elmagyarázza a program működését.

### Házi feladatok implementációjával kapcsolatos általános követelmények

A házi feladatok implementálásához kizárólag C/C++ használható. Ezeknek azonban bármely szabványos verziója elfogadott, így akár az előkészítés alatt álló C++20 is használható.

A standard könyvtáron felül kizárólag a GLUT/GLFW könyvtárak használhatóak, valamint az előző féléves *Bevezetés a számítógépi grafikába* tárgyhoz kiadott matematikai fejlécállomány.

Programvédésen **csak** olyan forráskód mutatható be, melyet a hallgató feltöltött a megfelelő házi feladathoz számára létrehozott GitHub repositoryba!

## Hasznos linkek, információk

### Piazza

Ebben az évben is rendelkezik a tárgy Piazza csoporttal, ahol akár névvel, akár anonim módon feltehetők a tárggyal kapcsolatos kérdések:

  * [Piazza Class](piazza.com/unideb.hu/fall2018/indv602k5/home)

Az egyetlen - de rendkívül fontos - kritérium, hogy a kérdések **nem** tartalmazhatnak forráskódot. Képernyőképek azonban szabadon csatolhatóak.

### IDE, debugger

A házi feladatok fejlesztése tetszőleges eszközzel történhet. Azonban a kényelmes és gyors fejlesztést elősegítendő, ajánlott valamilyen IDE használata. Windowson kiváló választás a [Visual Studio Community](https://www.visualstudio.com/vs/community/), Linuxon (de akár Windowson is) pedig a [CLion](https://www.jetbrains.com/clion/). Utóbbihoz rendelkezésre áll hallgatói licenc, mely magában foglalja a többi JetBrains terméket is.

A feladatok implementálása során sokszor találhatjátok magatokat olyan helyzetben, hogy bár úgy gondoljátok, helyesen programoztátok le a feladatot, a látvány mégsem kielégítő. Ilyen esetben remekül használhatóak az IDE-k által biztosított debuggolási lehetőségek, azaz a breakpointok, feltételes breakpointok, watchok és további eszközök. Használjátok ezeket bátran, sok időt és fáradságot takaríthattok meg velük!