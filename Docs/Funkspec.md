1\. Áttekintés
==============
Prioritást élvez a hozzáférhetőség illetve az egyszerűség. Nagyon fontos az, hogy egyértelmű legyen a használata, felhasználóbarát legyen.
Törekszünk egy olyan design kialakítására, amely önmagától értetődő, különösebb dokumentáció használatot ne igényeljen az alkalmazás.

Elképzelésünk szerint nem tervezünk mikrotranzakciókat beleépíteni a szoftverünkbe, továbbá ez nem egy kalendáriumnak készül.

2\. Jelenlegi helyzet
=====================
A megrendelő szeretné, hogy könnyen, gördülékenyen tudja kezelni mindennapjait, egy megfelelő napirend tervező lista használatával. Ehhez egy interneten keresztül működő weboldalon található teendő listát rendelt meg. A weboldal amit létrehozunk **minden látogató igényét ki kell, hogy elégítse** azáltal, hogy XXI. századi technológiát alkalmazva el kell érni, hogy a **Hálózaton keresztül működjön**, és itt **bárki** feljegyezhesse az előtte álló, vagy akár a kész feladatokat, **ingyenes** táblák használatával, teendőikhez időpontokat rendelve, ezzel **lecserélve elődjét: a papírt**. Valamint a megrendelő igényei szerint segítenie kell a **környezetvédő** szervezetek munkáját a papírlapok és műanyag tollak elhagyásával, mindezek mellett nagyszerű fiatalos designt alkalmazva.
A megrendelő eddig csak papír alapú teendő listát használt, viszont látva a lehetőséget a **környezetbarát**, **gyors** és **egyszerűen hordozható** megoldásra, nálunk keresett számára megfelelő szolgáltatást.

3\. Követelménylista
====================
| ID | Leírás |
|----| ------ |
|K01| A feladatok jellemzésére lehetőség lesz mozgatható kártyák segítségével, amelyeken megadható lesz a feladat neve, és opcionálisan a személy vagy személyek akik a feladatot elvégzik majd. A kártyákon szintén megadható a feladatvégzés tervezett dátuma és időtartama.|
|K02| A munkastádiumok oszlopokként jelennek meg a weboldalon, az egyes oszlopokba mozgatható lesz bármelyik feladatot jelölő kártya. A kártyák a munkastádiumok között drag and drop módszerrel áthelyezhetőek lesznek. |
|K03| A létrehozott munkavégzési stádiomokat jelölő oszlopokban lehetőség lesz új feladatkártyák hozzáadására. A már létező kártyákra kattintva lehetőség lesz az azokon szereplő adatok módosítására, és a kártya törlésére.|
|K04| A munkavégzési stádiumokat jelölő oszlopoktól jobbra lesz egy gomb, amellyel új oszlopot lehet létrehozni. Az oszlopok fejlécén megadható a név. Az oszlopok sorrendje megváltoztatható lesz. A fejlécre kattintva lehetőség lesz az átnevezésre, és oszlop törlésére is.|
   
   

4\. Jelenlegi üzleti folyamatok modellje
===============================
- Papír alapú teendőlisták használata
> Elavult, nehezen hordozható\
> Nagy mennyiségű papírhulladék\
> Könnyen károsodó adatok (égés, ázás, elvesztés)
- A szöveg számítógépre történő bevitele helyett tollat és ceruzát használnak
> Gyakori az elmosódás, adathibásodás\
> Kényelmetlen és lassú folyamat\
> Óriási műanyaghulladék\
> Bonyolultan szerkeszthető
- Drága, fizetős alkalmazások alkalmazása
- Mobiltelefonos jegyzettömb használat
- Számítógépes txt használat

   
5\. Igényelt üzleti folyamatok modellje
==============================
- Online elérhető, ingyenes rendszer kialakítása\
-- Webes megjelenés
- Átlátható design kialakítása a weboldalon\
-- Táblák/munkakör kártyák alkalmazása -> Szabadon hozzáadható és elnevezhető címsorú táblák alkalmazása\
-- A feladatok kártyákon való elhelyezhetősége -> Gépeléses bevitel\
-- Címsorok alkalmazása a táblák tetején -> Szabadon elnevezhető és módosítható nevű címsorok\
--A megrendelő igénye a jól átlátható design, ennek érdekében sok segítséget nyújthat, hogy a feladatok mellé felvehető legyen a végzés időpontja és dátuma is
- Elegáns design kialakítása\
-- Letisztult , sima, de elegáns színű háttér-> szürke háttér, tört fehér táblák, fekete szegély\
-- Egyszerű betűtípus és betűszín alkalmazása -> egyszerű fekete betűszín és Times New Roman betűtípus alkalmazása
- A weboldalon lévő adatok szerkeszthetővé tétele/Könnyű szerkeszthetőség\
-- A már felvett feladatok nevének szerkeszthetősége\
-- A már nem kívánatos feladatok törölhetősége\
-- A feladatok táblák közötti felcserélhetősége -> A már nem kívánt feladatokat egy tetszőleges táblába is át lehessen helyezni, vagy akár onnan vissza is (pl.: archiváltak tábla)

6\. Képernyő terv
=================
![ Képernyőterv kép betöltése sikertelen](./kepernyoterv.png)

7\. Forgatókönyv
================

Szereplők: Futási időben 2 szereplő figyelhető meg. Az első szereplő maga a futó alkalmazás (weben/Androidon/iOS-en). Az alkalmazást elindítva megjelenik egy üres kezelőfelület egy oszlopok felvétele gombbal a bal oldalon. Ezután a felhasználó rákattinthat a gombra és elkezdheti az oszlopom felvételét és elnevezését. A felvehető oszlopok számában nem lesz korlátozva a felhasználó. Ezekután a felhasználó elkezdheti a feladatkártyák hozzáadását a már elkészített oszlopokhoz. Miután a kártyák hozzáadásra kerültek azok módosítását is megkezdheti a felhasználó. Adhat hozzá tulajdonságokat, dátumot és időintervallumot. Miután a felhasználó haladást ért el a felvett feladatával tovább mozgathatja egy másik oszlopba.

8\. Funkció - követelmény megfeleltetés
=======================================

A követelmények azokra felhasználói esetekre lettek felállítva amikor egy felhasználó rendszerezni szeretné valamilyen rendszer szerint a teendőit. Ennek a legegyszerűbb esete amikor a programot használó személy az alapján szeretné rendszerezni teendőit, hogy mit csinált már meg. Ez esetben a felhasználó létre tud hozni 3 oszlopot, ami a feladat állapota szerint van elnevezve. Az első oszlopba be tudja írni a felhasználó, hogy mi az, amit meg szeretne csinálni és azt, hogy mikor. A második oszlopban a felhasználó nyomon tudja követni az éppen folyamatban lévő feladatait és az utolsó oszlopba tudja gyűjteni azokat a dolgokat, amikkel már végzett. A felhasználó hozzá tud írni a feladataihoz tulajdonságokat, amik számára fontosak azzal kapcsolatban. Ugyanígy képes a felhasználó dátumok hozzárendelésére a feladatokhoz, hogy tudja, hogy mikor tervezte az elvégezni és képes időintervallumok hozzárendelésére is hogy lássa azt hogy mi mennyi időbe telt.
   
9\.  Fogalomszótár
===============


HTML: A HTML (angolul: HyperText Markup Language=hiperszöveges jelölőnyelv) egy leíró nyelv, melyet weboldalak készítéséhez fejlesztettek ki, és mára már internetes szabvánnyá vált a W3C (World Wide Web Consortium) támogatásával.

Forrás: https://hu.wikipedia.org/wiki/HTML

A CSS (Cascading Style Sheets, magyarul: lépcsőzetes stíluslapok) a számítástechnikában egy stílusleíró nyelv, mely a HTML vagy XHTML típusú strukturált dokumentumok megjelenését írja le. Ezenkívül használható bármilyen XML alapú dokumentum stílusának leírására is, mint például az SVG, XUL stb.

A CSS specifikációját a World Wide Web Consortium felügyeli.

Forrás: https://hu.wikipedia.org/wiki/Cascading_Style_Sheets

A JavaScript programozási nyelv egy objektumorientált, prototípus-alapú szkriptnyelv, amelyet weboldalakon elterjedten használnak.

Forrás: https://hu.wikipedia.org/wiki/JavaScript

Cross-Platform: A platformfüggetlenség vagy többplatformosság, illetve multi-platform fogalma olyan számítógépes programokra, operációs rendszerekre, programozási nyelvekre vagy más számítógépes szoftverekre és implementációikra vonatkozik, amelyek több számítógépes platformon képesek működni.

Forrás: https://hu.wikipedia.org/wiki/Platformf%C3%BCggetlens%C3%A9g

Reszponzív weboldal: A reszponzív weboldal (RWD) egy olyan megközelítéssel tervezett weboldal, amelynek a célja az, hogy optimális megjelenést biztosítson - könnyű olvashatóság, egyszerű navigáció a lehető legkevesebb átméretezéssel és görgetéssel - a legkülönfélébb eszközökön.

Forrás: https://hu.wikipedia.org/wiki/Reszponz%C3%ADv_weboldal
