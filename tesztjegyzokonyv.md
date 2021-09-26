Tesztek Google Chrome böngészőn
=======================

Böngésző verzió: Chrome 93

Operációs rendszer: Windows 10

Tesztek Mozilla Firefox böngészőn
=======================

Böngésző verzió: Firefox 92.0.1

Operációs rendszer: Windows 10

Tesztek Brave böngészőn
=======================

Böngésző verzió: Brave 93.1.29.81

Operációs rendszer: Windows 10

Tesztek Opera GX böngészőn
=======================

Böngésző verzió: Opera GX 92

Operációs rendszer: Windows 10

Tesztek Microsoft Edge böngészőn
=======================

Böngésző verzió: Microsoft Edge 93.0.961.52

Operációs rendszer: Windows 10

1\. Todo kategória hozzáadása
-----------------------

Elvárt viselkedés: Az új kategória gombra kattintás után megjelenik egy dialógus doboz, ahol megadhatjuk a kategória nevét.
A mentés gombra kattintva megjelenik egy új kategória a megadott névvel.

Tényleges viselkedés: Az új kategória oszlopa sikeresen létrejött, a megadott névvel. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adott kategória hozzáadásra került az új kategória gombot használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: A todo kategória sikeresen létrejött a megadott névvel. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés: Az új kategória hozzáadásra került a megadott névvel. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: A todo kategória kártya sikeresen létrejött megfelelő névvel, a megfelelő (Új kategória) gombot használva. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.

2\. Todo feladat hozzáadása listához
--------------------------

Elvárt viselkedés: Az egyes kategóriák oszlopának alján elhelyezkedő új feladat gombra kattintva megjelenik egy dialógus doboz,
ahol megadhatjuk az új feladat adatait. A mentés gombra kattintva megjelenik az új feladat, a megfelelő oszlop alján.

Tényleges viselkedés: Az új feladatkártya létrejött a kiválasztott oszlopban, a megadott adatokkal. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adott feladat hozzáadásra került az új feladat gombot használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: A Todo feladatot a rendszer a megadott adatokkal felvette. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés: Az új kártya létrejött a megfelelő oszlopban a megfelelő adatokkal. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: Az új Todo feladatot sikeresen hozzáadtam az adott kártyához a megfelelő (Új feladat) gomb használatával, minden adat kitölthető, hozzáadható, és megjeleníthető. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.

3\. Todo kategória törlése
--------------------------

Elvárt viselkedés: A kategória táblák jobb felső sarkában lévő X mezőre kattintva, egy dialógus doboz felnyílása után dönthetünk, hogy biztosan törölni akarjuk-e a kategóriát, ha az OK-ra nyomunk törlődnie kell, ha a Mégse-re, akkor marad az eredeti állapot.

Tényleges viselkedés: A kategória törlése az OK gomb nyomása után megtörténik, mégse gombbal visszavonható. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adott kategória törlésre került a piros X-et használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: Sikerült a kategóriákat törölnöm az X-re kattintva. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés: Az X gombra való kattintással sikeresen törlődött a megfelelő kategória. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: Sikeresen törölhetőek a kategória kártyák az X, majd a dialóguson az OK mező megnyomásával, a Mégse lenyomásánál maradt az eredeti állapot. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.

4\. Todo feladat törlése
--------------------------

Elvárt viselkedés: A kategória táblákban a feladatok alján lévő Feladat törlése mezőre kattintva, egy dialógus doboz felnyílása után dönthetünk, hogy biztosan törölni akarjuk-e az adott feladatot, ha az OK-ra nyomunk törlődnie kell, ha a Mégse-re, akkor marad az eredeti állapot.

Tényleges viselkedés: A feladat törlése az OK gomb nyomása után megtörténik, mégse gombbal visszavonható. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adott feladat törlésre került a törlés mezőt használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: Sikerült törölni a hozzáadott feladatokat a feladat törlése gombra kattintva. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés: A feladat sikeresen törlődött a ”Feladat törlése” gomb használatával. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: Egy adott feladat sikeresen törölhető a Feladat törlése mezőre kattintva, majd a dialóguson az OK mező megnyomásával, a Mégse lenyomásánál marad az eredeti állapot. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.

5\. Todo listák és feladatok perzisztenciája
--------------------------------------------

Elvárt viselkedés: A kategória táblák alatti mentés és betöltés gombra kattintva, az adott állást el tudjuk menteni illetve elő tudjuk hívni a teendőinket a localStorage-ból.

Tényleges viselkedés: A betöltés gombra nyomva a legutóbb kimentett állapot helyreáll. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az állások mentésre illetve betöltésre kerültek a mentés és betöltés gombot használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: A tesztelés során azt tapasztaltam, hogy a todo listák megmaradnak a mentés után, az újratöltést követően. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés: Az állások mentése majd betöltése megtörténtek a megfelelő gombok használatával. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: A mentés, majd a betöltés gomb lenyomásával a felvett listák és feladatok sikeresen megmaradnak az oldalon, és az oldal is lefrissül. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.

6\. Todo kategórianév módosítása
--------------------------------------------

Elvárt viselkedés: A különféle táblákban lévő fejlécre kattintva tudjuk módosítani a teendőinket.

Tényleges viselkedés: A kategória fejlécében a nevet átírva a módosítás megtörténik. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Kijelölésük után a fejlécek módosításra kerültek. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: A fejlécre kattintva a teszt során, sikerült a kategórianevet módosítanom. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés: A kategória nevét sikeresen módosításra került. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: Minden megjelenített TODO tábla fejléce bármennyiszer átnevezhető. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.

7\. Todo feladat adatainak módosítása
---------------------------

Elvárt viselkedés: Egy feladat kártyáján lévő módosítás gombra kattintva megjelenik egy dialógus doboz,
ahol átírhatjuk a feladat adatait. A mentés gombra kattintva a feladat adatai a beírtakra változnak, mégse
gombra kattintva a korábbi állapotban maradnak.

Tényleges viselkedés: A feladat adatainak módosítása a mentésre nyomva megfelelően végbe megy, a mégse gombra kattintva a korábbi adatok megmaradnak. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adatok módosításra kerültek a módosítás gombot használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: A módosítás gombra kattintva sikerült a feladat adatainak megváltoztatása a mentés gombbal. A mégsem gomb megnyomásakor nem történik változás. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés: Az adatok sikeresen módosításra kerültek és a mégse gomb használatával nem kerültek módosításra az adatok. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: A Mod gombra kattintva sikeresen megjelenik a dialógus doboz, ahol valóban át lehet írni a feladatok adatait, majd menteni, vagy a Mégse gombbal hagyni az eredeti állapotot. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.

8\. Todo feladatok mozgatása kategóriák között
---------------------------

Elvárt viselkedés: A feladatok drag and drop módszerrel mozgathatóak a kategóriák között. Egy feladatot másik kategóriába
húzva a feladat átkerül az új kategória oszlopába.

Tényleges viselkedés: A feladatok áthúzhatóak másik kategóriába, megjelenítésük azonnal frissül. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: A feladatok megfelelően mozgathatóak kategóriák között. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: A feladatokat sikerült az egérrel áthúznom egyik táblából a másikba. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés: A feladatok sikeresen mozgathatók a feladatok között. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: A feladatok az egér használatával sikeresen áthelyezhetőek egyik táblából a másikba. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.

9\. Todo feladatok átrendezése egy kategórián belül
---------------------------------------------------

Elvárt viselkedés: Egy adott kategórián belül az egér letartásával képesek vagyunk az adott feladatainkat átrendezni.

Tényleges viselkedés: A feladat kártyáját egy másik feladatra húzva áthelyezhetjük a cél feladat elé vagy mögé. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: A feladatok megfelelően mozgathatóak egy kategórián belül. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: Sikerült a feladatok átrendezése, az egérgomb nyomvatartásával és a feladat egy másikra húzásával. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés: Az egér használatával a feladatok sikeresen átrendezhetők a kategóriákon belül. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: Egy adott feladatot (kategórián belül) az egér nyomvatartásával egy másik feladat elé, vagy mögé húzva áthelyezhetjük a tetszőleges helyre. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.


10\. Todo stílus ellenőrzése
---------------------------------------------------

Elvárt viselkedés: Elegáns, de egyben egyszerű/letisztult stílust várunk el: egyszerű szürke háttér, törtfehér táblákkal, fekete szegéllyel és betűtíszínnel, Times New Roman betűtípust alkalmazva.

Tényleges viselkedés: Az oldal megjelenése megfelel a kikötéseknek. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: A megjelenítés megfelelően jelenik meg a felhasználó számára. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

Tényleges viselkedés: Az oldal megjelenése az elvártnak megfelelő. Tesztelve: Opera GX-ben Kiss Marcell által.

Tényleges viselkedés:A weboldal kinézete az elvártaknak megfelel. Tesztelve: Brave-ben Balázs Bence által.

Tényleges viselkedés: Az oldal az elvárásoknak teljesen megfelelően jelenik meg. Tesztelve: Microsoft Edge-ben Hernádi Mihály által.

