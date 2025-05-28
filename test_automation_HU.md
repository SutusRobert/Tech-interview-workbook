# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?

Célja: A szoftver hibáinak felfedezése és annak biztosítása, hogy megfeleljen a specifikációknak.
Nem célja: A tervezés vagy fejlesztés helyettesítése, illetve a hibák teljes eltüntetése.



#### ✅ Mik a tesztelési alapelvek?

esztelés minden szinten szükséges.

Hibák minél előbb való felfedezése.

Fokozatos tesztelés.

Szisztematikus tesztelési folyamat.

Tesztelés nem garantálja a hibamentességet.

#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?

Egységtesztelés: A kód legkisebb egységeit teszteli (pl. függvények, metódusok).
Felelős: Általában a fejlesztők.

#### ✅ Mik a tesztszintek, és mi a különbség köztük?

Egységteszt: Egy komponens tesztelése.

Integrációs teszt: Különböző komponensek együttműködése.

Rendszerteszt: A teljes rendszer működése.

Elfogadási teszt: A végfelhasználók tesztelése.

#### ✅ Mi a különbség a verifikáció és a validáció között?

Verifikáció: A rendszer megfelel a specifikációnak.

Validáció: A rendszer megfelel a felhasználói igényeknek.

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?

Funkcionális: A rendszer funkcionalitásának tesztelése.

Nem funkcionális: Teljesítmény, biztonság stb. tesztelése.

Regressziós: Az új kód nem rontja el a régit.

Füstteszt: Alapvető funkciók tesztelése.

UAT: Végfelhasználói tesztelés.



#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?

Fehér doboz: A tesztelő ismeri a kódot.

Szürke doboz: Részleges ismeret a kódról.

Fekete doboz: A tesztelő nem ismeri a kódot.



#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?

UAT: Végfelhasználók végzik, hogy megfelel-e az üzleti igényeknek.

Rendszerteszt: A fejlesztők ellenőrzik a teljes rendszer működését.



#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!

Regressziós tesztelés: A teszt célja annak biztosítása, hogy az új fejlesztések ne rontsák el a régi funkciókat.

Füsttesztelés: Alapvető funkciók gyors tesztelése, hogy biztosítsuk, hogy a rendszer stabil, és nem tartalmaz kritikus hibákat.

Újratesztelés: Egy korábban javított hibát újra tesztelnek, hogy megbizonyosodjanak arról, hogy valóban megoldódott.



#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?

Mi a különbség a statikus és dinamikus tesztelés között?
Statikus tesztelés: A kód elemzése futtatás nélkül (pl. kódelemzés, dokumentáció átnézése).

Dinamikus tesztelés: A kód tényleges futtatása és viselkedésének tesztelése.

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!

V-modell: A fejlesztés és tesztelés szoros párhuzamos fázisokban történik. A tesztelés már a tervezés során elkezdődik.

Vízesés modell: A fejlesztés lineáris, a tesztelés csak a fejlesztés befejezése után kezdődik.

Agile: A tesztelés folyamatosan és iteratívan történik a fejlesztéssel párhuzamosan, gyors visszajelzésekkel.




<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">





## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?

Hiba reprodukálása: Próbáld meg reprodukálni a hibát.

Hiba diagnosztizálása: Elemezd a hiba okát (logok, kód ellenőrzése).

Javítás: A hibát kijavítani.

Tesztelés: Ellenőrizd, hogy a javítás működik, és nem okozott új hibát.

Jelentés: Hibajelentés írása a csapat számára.

#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!

Hibajelentés: A hiba leírása, lépésről lépésre, hogyan lehet reprodukálni a hibát.

Tesztjelentés: A végrehajtott tesztelés eredményei, beleértve a tesztelt funkciókat, a teszt környezetet és a tesztelés során talált hibákat.

Funkcionális tesztjelentés: Az alapvető funkciók tesztelésének eredményei.

Teljesítmény tesztjelentés: A rendszer teljesítményét mérő tesztelés eredményei.



#### ✅ Mit tartalmaz egy hibajelentés?
Hiba leírása: Mit tapasztaltunk?

Környezet: Milyen környezetben jelentkezett a hiba (pl. OS, verzió).

Lépések a hiba reprodukálásához: Hogyan lehet előidézni a hibát?

Várható eredmény: Mi volt a várt viselkedés?

Megjegyzések és képernyőképek: Bármilyen további információ, ami segíthet a hiba megértésében.

#### ✅ Hogyan rangsorolnál egy hibát?

Kritikus: A hiba megakadályozza a rendszer működését.

Magas: Jelentős hatással van a rendszer működésére, de nem akadályozza meg teljesen.

Közepes: A hiba nem befolyásolja kritikus funkciókat, de javítani kell.

Alacsony: Kis hatású hiba, nem sürgős.




## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?
Érdemes automatizálni:

Regressziós tesztek

Újratesztelések

Nagy mennyiségű adatot igénylő tesztek

Nem érdemes automatizálni:

Alkalmanként végzett tesztek (pl. egyedi hibák tesztelése)

Gyakran változó funkciók tesztelése



#### ✅ Írj le egy jó automatizált tesztet!
Cél: Ellenőrizni, hogy a felhasználó sikeresen belép a rendszerbe a helyes adatokkal.

Lépések:

Nyisd meg a belépési oldalt.

Töltsd ki a felhasználónevet és jelszót.

Kattints a "Bejelentkezés" gombra.

Ellenőrizd, hogy sikeres bejelentkezés történt.

Várható eredmény: A felhasználó belép a rendszerbe.



#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?


Selenium: Egy eszközkészlet webes alkalmazások automatizált tesztelésére.

Selenium IDE: A Selenium grafikus felhasználói felület, ami lehetővé teszi a tesztek rögzítését és lejátszását.

Selenium WebDriver: A Selenium egyik komponense, amely programozott módon vezérli a böngészőt.


#### ✅ Hogyan lehet azonosítani a webes elemeket?

ID: Egyedi azonosítóval rendelkező elem.

Név (Name): Az elem neve.

XPath: Az elem pontos helye a dokumentumban.

CSS Selector: A CSS alapú elemek azonosítása.

#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!

Várakozás: Használhatunk explicit várakozást (WebDriverWait) vagy implicit várakozást.

Lehetséges hibák:

Elem nem található: Az elem nem létezik, vagy hibás az azonosító.

Időzítés: Az oldal nem töltődött be időben.

Aszinkron működés: Az oldal frissül, miközben a teszt fut.

#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!

POM (Page Object Model): Módszer, ahol minden oldal egy külön osztály, ami elválasztja az UI-t a tesztlogikától.

Keyword Driven Testing: A teszteseteket kulcsszavak segítségével írjuk le, amelyeket tesztelő szoftver értelmez.

#### ✅ Mi a különbség a TDD és BDD között?
TDD (Test-Driven Development): A kódot teszt alapú megközelítéssel fejlesztik, először a tesztet írják, majd a kódot, hogy azt teljesítse.

BDD (Behavior-Driven Development): A fejlesztést a rendszer viselkedésére alapozva végzik, a teszteket üzleti nyelven írják.



#### ✅ Mi az API tesztelés és miért hasznos?
API tesztelés: Az alkalmazások közötti kommunikációt teszteli, biztosítva, hogy a különböző rendszerek megfelelően működnek együtt.

Miért hasznos?: Gyors, hatékony tesztelést tesz lehetővé anélkül, hogy a teljes UI-t tesztelnénk.



#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
Adatvezérelt tesztelés: A tesztelés különböző adatokat használ ugyanazon teszteset végrehajtásához.

Miért hasznos?: Növeli a tesztek hatékonyságát és lefedettségét anélkül, hogy új teszteseteket kellene írni.

#### ✅Mi a különbség a CI és CD között?
CI (Continuous Integration): Gyakori kódösszevonás, automatikus build és tesztelés.

CD (Continuous Delivery/Deployment): A kód automatikus szállítása tesztelésre vagy akár éles rendszerbe.



#### ✅ Írj le egy Continuous Delivery folyamatot!
Kód módosítása a fejlesztő által

Push a verziókezelőbe (pl. Git)

Automatikus build és teszt

Staging környezetbe deploy

Manuális jóváhagyással éles deploy



#### ✅ Hasonlítsd össze két népszerű CI rendszert, ezek közül az egyik legyen a Jenkins!
Jellemző	    Jenkins	                    GitHub Actions
Telepítés	    Lokálisan vagy szerveren	Felhőalapú (GitHub-on belül)
Konfiguráció	XML vagy Jenkinsfile        YAML fájl a repo-ban
Bővíthetőség	Nagyon sok plugin	        Jó integráció GitHub-bal
Használat	    Összetett, de rugalmas	    Egyszerűbb, gyorsabb indulás


#### ✅ Mi a Docker és miért hasznos?

Mi az: Platform független konténerizációs technológia.

Miért hasznos: Ugyanaz a környezet fejlesztéshez és futtatáshoz, könnyű skálázás, gyors telepítés.








