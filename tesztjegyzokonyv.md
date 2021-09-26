Tesztek Google Chrome böngészőn
=======================

Böngésző verzió: Chrome 93

Operációs rendszer: Windows 10

Tesztek Mozilla Firefox böngészőn
=======================

Böngésző verzió: Firefox 92.0.1

Operációs rendszer: Windows 10

1\. Todo kategória hozzáadása
-----------------------

Elvárt viselkedés: Az új kategória gombra kattintás után megjelenik egy dialógus doboz, ahol megadhatjuk a kategória nevét.
A mentés gombra kattintva megjelenik egy új kategória a megadott névvel.

Tényleges viselkedés: Az új kategória oszlopa sikeresen létrejött, a megadott névvel. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adott kategória hozzáadásra került az új kategória gombot használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

2\. Todo feladat hozzáadása listához
--------------------------

Elvárt viselkedés: Az egyes kategóriák oszlopának alján elhelyezkedő új feladat gombra kattintva megjelenik egy dialógus doboz,
ahol megadhatjuk az új feladat adatait. A mentés gombra kattintva megjelenik az új feladat, a megfelelő oszlop alján.

Tényleges viselkedés: Az új feladatkártya létrejött a kiválasztott oszlopban, a megadott adatokkal. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adott feladat hozzáadásra került az új feladat gombot használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

3\. Todo kategória törlése
--------------------------

Elvárt viselkedés: A kategória táblák jobb felső sarkában lévő X mezőre kattintva, egy dialógus doboz felnyílása után dönthetünk, hogy biztosan törölni akarjuk-e a kategóriát, ha az OK-ra nyomunk törlődnie kell, ha a Mégse-re, akkor marad az eredeti állapot.

Tényleges viselkedés: A kategória törlése az OK gomb nyomása után megtörténik, mégse gombbal visszavonható. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adott kategória törlésre került a piros X-et használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

4\. Todo feladat törlése
--------------------------

Elvárt viselkedés: A kategória táblákban a feladatok alján lévő Feladat törlése mezőre kattintva, egy dialógus doboz felnyílása után dönthetünk, hogy biztosan törölni akarjuk-e az adott feladatot, ha az OK-ra nyomunk törlődnie kell, ha a Mégse-re, akkor marad az eredeti állapot.

Tényleges viselkedés: A feladat törlése az OK gomb nyomása után megtörténik, mégse gombbal visszavonható. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adott feladat törlésre került a törlés mezőt használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

5\. Todo listák és feladatok perzisztenciája
--------------------------------------------

Elvárt viselkedés: A kategória táblák alatti mentés és betöltés gombra kattintva, az adott állást el tudjuk menteni illetve elő tudjuk hívni a teendőinket a localStorage-ból.

Tényleges viselkedés: A betöltés gombra nyomva a legutóbb kimentett állapot helyreáll. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az állások mentésre illetve betöltésre kerültek a mentés és betöltés gombot használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

6\. Todo kategórianév módosítása
--------------------------------------------

Elvárt viselkedés: A különféle táblákban lévő fejlécre kattintva tudjuk módosítani a teendőinket.

Tényleges viselkedés: A kategória fejlécében a nevet átírva a módosítás megtörténik. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Kijelölésük után a fejlécek módosításra kerültek. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

7\. Todo feladat adatainak módosítása
---------------------------

Elvárt viselkedés: Egy feladat kártyáján lévő módosítás gombra kattintva megjelenik egy dialógus doboz,
ahol átírhatjuk a feladat adatait. A mentés gombra kattintva a feladat adatai a beírtakra változnak, mégse
gombra kattintva a korábbi állapotban maradnak.

Tényleges viselkedés: A feladat adatainak módosítása a mentésre nyomva megfelelően végbe megy, a mégse gombra kattintva a korábbi adatok megmaradnak. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: Az adatok módosításra kerültek a módosítás gombot használva. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

8\. Todo feladatok mozgatása kategóriák között
---------------------------

Elvárt viselkedés: A feladatok drag and drop módszerrel mozgathatóak a kategóriák között. Egy feladatot másik kategóriába
húzva a feladat átkerül az új kategória oszlopába.

Tényleges viselkedés: A feladatok áthúzhatóak másik kategóriába, megjelenítésük azonnal frissül. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: A feladatok megfelelően mozgathatóak kategóriák között. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.

9\. Todo feladatok átrendezése egy kategórián belül
---------------------------------------------------

Elvárt viselkedés: Egy adott kategórián belül az egér letartásával képesek vagyunk az adott feladatainkat átrendezni.

Tényleges viselkedés: A feladat kártyáját egy másik feladatra húzva áthelyezhetjük a cél feladat elé vagy mögé. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: A feladatok megfelelően mozgathatóak egy kategórián belül. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.


10\. Todo stílus ellenőrzése
---------------------------------------------------

Elvárt viselkedés: Elegáns, de egyben egyszerű/letisztult stílust várunk el: egyszerű szürke háttér, törtfehér táblákkal, fekete szegéllyel és betűtíszínnel, Times New Roman betűtípust alkalmazva.

Tényleges viselkedés: Az oldal megjelenése megfelel a kikötéseknek. Tesztelve: Google Chrome-ban Osztós Zsombor által.

Tényleges viselkedés: A megjelenítés megfelelően jelenik meg a felhasználó számára. Tesztelve: Mozilla Firefox-ban Szilágyi Mihály által.
