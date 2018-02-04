#  DE IK Komputergrafika 17/18/2

## A gyakorlatok helye, ideje

| Időpont                | Terem      |
|------------------------|------------|
| **hétfő, 16:00-18:00** | **IK-206** |
| **kedd, 10:00-12:00**  | **IK-206** |

## A gyakorlatvezetőről

Sziasztok! Bagossy Attila vagyok, második féléves PTI MSc. hallgató. Már harmadik alkalommal nyílik lehetőségem Komputergrafika gyakorlatot vezetni, így már viszonylagos rutinnal rendelkezem e tárgyat illetően.

Ha kérdésetek, ötletetek, javaslatotok van, bátran írjatok e-mailt a következő címre:

> bagossyattila@outlook.com

Amennyiben olyan felvetéssel, problémával rendelkeztek, mely a tárgyat felvevő többi hallgatót is érinti, válasszátok inkább a Piazzát (részletek lentebb)!

## A félév tervezett rendje

### Gyakorlati tematika

| Időpont               | A gyakorlat témája                       | Megjegyzés |
|-----------------------|------------------------------------------|------------|
| 2018. február 5.      | Bevezetés, ismerkedés, Hermite-görbe     | |
| 2018. február 12.     | Bézier-görbe                             | |
| 2018. február 19.     | Cardinal Spline, Kochanek-Bartels Spline | |
| 2018. február 26.     | B-Spline                                 | [1. HF](http://nbviewer.jupyter.org/github/kompgraf/course-material/blob/master/notebooks/hf-01-zart-b-spline/hf-01-zart-b-spline.ipynb) |
| 2018. március 5.      | NURBS                                    | [2. HF](http://nbviewer.jupyter.org/github/kompgraf/course-material/blob/master/notebooks/hf-02-nurbs/hf-02-nurbs.ipynb) |
| 2018. március 12.     | Bézier-felület, NURBS felület            | [3. HF](http://nbviewer.jupyter.org/github/kompgraf/course-material/blob/master/notebooks/hf-03-bezier-felulet/hf-03-bezier-felulet.ipynb) |
| 2018. március 19.     | Subdivision görbék                       | [4. HF](http://nbviewer.jupyter.org/github/kompgraf/course-material/blob/master/notebooks/hf-04-subdivision-gorbe/hf-04-subdivision-gorbe.ipynb) |
| 2018. március 26./27. | **1. védés** (1-2-3. HF)                 | Utolsó effektív commit: **2018. március 25./26. 08:00** |
| 2018. április 9.      | A Half Edge adatszerkezet                | |
| 2018. április 16.     | Primál subdivision felületek             | [5. HF](http://nbviewer.jupyter.org/github/kompgraf/course-material/blob/master/notebooks/hf-05-loop-subdivision/hf-05-loop-subdivision.ipynb) |
| 2018. április 23.     | Duál subdivision felületek               | |
| 2018. május 7./8.     | **2. védés/1. pótvédés** (4-5. HF)       | Utolsó effektív commit: **2018. május 6./7. 08:00** |
| 2018. május 14.       | **2. pótvédés**                          | Vizsgaidőszak |

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

  * [Piazza Class](https://piazza.com/class/jd0lyizj4eutc)

Az egyetlen - de rendkívül fontos - kritérium, hogy a kérdések **nem** tartalmazhatnak forráskódot. Képernyőképek azonban szabadon csatolhatóak.

### Gyakorlati anyagok és házi feladat kiírások

A gyakorlatokon használt notebookok és a házi feladat kiírások elérhetőek a következő címen:

  * http://nbviewer.jupyter.org/github/kompgraf/course-material/tree/master/notebooks/

### IDE, debugger

A házi feladatok fejlesztése tetszőleges eszközzel történhet. Azonban a kényelmes és gyors fejlesztést elősegítendő, ajánlott valamilyen IDE használata. Windowson kiváló választás a [Visual Studio Community](https://www.visualstudio.com/vs/community/), Linuxon (de akár Windowson is) pedig a [CLion](https://www.jetbrains.com/clion/). Utóbbihoz rendelkezésre áll hallgatói licensz, mely magában foglalja a többi JetBrains terméket is.

A feladatok implementálása során sokszor találhatjátok magatokat olyan helyzetben, hogy bár úgy gondoljátok, helyesen programoztátok le a feladatot, a látvány mégsem kielégítő. Ilyen esetben remekül használhatóak az IDE-k által biztosított debuggolási lehetőségek, azaz a breakpointok, feltételes breakpointok, watchok és további eszközök. Használjátok ezeket bátran, sok időt és fáradságot takaríthattok meg velük!