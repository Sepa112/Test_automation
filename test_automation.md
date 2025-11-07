# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

## A tesztelés alapjai:
#### Mi a tesztelés célja? Mi nem az?
 A tesztelés célja a hibák korai felderítése, a termék minőségének és megbízhatóságának növelése, valamint annak biztosítása, hogy a rendszer vagy alkalmazás megfeleljen a követelményeknek.Nem a hibátlan szoftver garantálása, hanem a hibák felderítése

#### Mi a kapcsolat a tesztelés és a hibamegelőzés között?
 A hibamegelőzés a proaktív megközelítést jelenti, míg a tesztelés inkább reaktív, mivel a hibák keresésére és azok kijavítására irányul. A két folyamat egymást kiegészítve segít biztosítani a végtermék minőségét.

#### Miért fontos, hogy a tesztelők függetlenek legyenek a fejlesztőktől?
 A tesztelők függetlensége biztosítja, hogy a tesztelés objektív, átlátható és hatékony legyen, és hogy a lehető legtöbb hibát és problémát felfedezzék a fejlesztési folyamat végén. Azáltal, hogy a tesztelők friss szemmel és külső megközelítéssel dolgoznak, nemcsak a hibák könnyebben észlelhetők, hanem a termék minősége is jelentősen javulhat.

#### Mi a veszélye annak, ha a fejlesztő maga teszteli a saját kódját?
Ha a fejlesztő teszteli a saját kódját, az számos problémát és veszélyt hozhat magával, beleértve a hibák elkerülését, a torzított értékelést és a tesztelési folyamat hiányosságait.

#### Mik a tesztelési alapelvek?
https://hu.itpedia.nl/2017/09/11/7-software-test-principes/

#### Mit jelent az „alapvető tesztelési elv”, hogy „a kimerítő tesztelés lehetetlen”?
Az „a kimerítő tesztelés lehetetlen” elv azt jelenti, hogy a tesztelési folyamatok nem tudják lefedni az összes lehetséges bemeneti és működési kombinációt egy komplex rendszer esetén. Ehelyett a tesztelők a legkritikusabb, legvalószínűbb vagy legkockázatosabb helyzetekre összpontosítanak, hogy hatékonyan biztosítsák a rendszer minőségét és megbízhatóságát.

#### Mit jelent az „alapvető tesztelési elv”, hogy „a hibák halmozódnak”?
Az „alapvető tesztelési elv, hogy a hibák halmozódnak” azt jelenti, hogy a szoftverhibák nem egyenletesen oszlanak el a rendszerben, hanem hajlamosak csoportosan, bizonyos részeken felhalmozódni.

#### Mit jelent az „alapvető tesztelési elv”, hogy „a tesztelés a kontextustól függ”?
Az „alapvető tesztelési elv, hogy a tesztelés a kontextustól függ” azt jelenti, hogy nincs egyetlen, minden helyzetre megfelelő tesztelési módszer vagy megközelítés.



## 2. Tesztelés a szoftverfejlesztés életciklusán át
#### Mik a tesztszintek, és mi a különbség köztük?
A tesztszintek a szoftverfejlesztés életciklusának különböző pontjain végzett tesztelési fázisokat jelentik.
Mindegyik szint más célt, fókuszt és felelősséget kap, és együtt biztosítják, hogy a rendszer egészében jól működjön. A négy fő tesztszint: Egységteszt;Integrációs teszt; Rendszerteszt;Elfogadási teszt

#### Miért nem érdemes mindig ugyanazokat a teszteseteket futtatni (regressziós torzítás)?
Ha mindig ugyanazokat a teszteseteket futtatjuk, akkor egy idő után már nem találunk új hibákat.

#### Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
Az egyes kódrészek (függvények, osztályok, modulok) helyes működésének ellenőrzése. Fejlesztők a felelősek az egységtesztek írásáért

#### Mi a különbség a verifikáció és a validáció között?
A verifikáció azt ellenőrzi, hogy a szoftvert a specifikációnak megfelelően fejlesztették-e, azaz helyesen csináltuk-e a dolgokat.
A validáció azt vizsgálja, hogy a szoftver valóban megfelel-e a felhasználó igényeinek, azaz a dolgok jól működnek-e a felhasználó számára.

#### Mik a tesztelési típusok, és mi a különbség köztük?
A tesztelési típusok a szoftver különböző szempontok szerinti vizsgálatát jelentik, és segítenek abban, hogy a szoftver hibamentes, megbízható és felhasználóbarát legyen. (funkcionális és nem funkcionális tesztelés.)
A funkcionális: Ellenőrzi, hogy a szoftver megfelel-e a követelményeknek és a specifikációnak.
A nem funkcionális: Ellenőrzi, hogy a szoftver hogyan teljesít, nem a funkciókat.

#### Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
A fehér doboz tesztelés a kódot és a belső logikát vizsgálja, a fekete doboz tesztelés a külső, funkcionális viselkedést ellenőrzi, míg a szürke doboz tesztelés a kettő ötvözete, ahol a tesztelő részleges belső információk birtokában végez teszteket. 

#### Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
A rendszertesztelés arra fókuszál, hogy a szoftver technikai szempontból megfelel-e a követelményeknek, míg a felhasználói elfogadási tesztelés azt ellenőrzi, hogy a kész rendszer megfelel-e a végfelhasználó üzleti igényeinek és követelményeinek a kiadás előtti utolsó szakaszban. A rendszertesztelést a tesztelők és fejlesztők végzik, míg az UAT-t a végfelhasználók. 

#### Mi a különbség a statikus és dinamikus tesztelés között?
A statikus tesztelés a szoftver kódjának és dokumentációjának futtatás nélküli vizsgálatát jelenti, például áttekintéssel és elemzéssel, míg a dinamikus tesztelés a kód futtatásával és viselkedésének tesztelésével foglalkozik. 


### Szoftverfejlesztési és tesztelési modellek(vízesés, V-modell, agilis modell)
#### Vízeés
A vízesés tesztelési modell egy szoftverfejlesztési megközelítés, ahol a tesztelés az egyes fázisok, mint a követelmények meghatározása, tervezés, megvalósítás és üzemeltetés, sorrendben, egymás utáni egymásra épülő lépésekben történik. Ez egy strukturált és lineáris módszer, amely jól működik jól definiált, kevéssé változó követelményekkel rendelkező projekteknél, de rugalmatlan, és a módosítások költségesek lehetnek. A tesztelés mindig az előző fázisok sikeres befejezése után történik, és a projekt végén egy átfogó ellenőrzést foglal magában. 
<img src="https://www.szinergia.hu/wp-content/uploads/vizeses.png" alt="image" width="300" height="220">

#### V-modell
A V-modell egy szoftverfejlesztési és rendszermérnöki modell, amely a fejlesztési és a tesztelési fázisokat V-alakban kapcsolja össze, a bal oldali ágon a fejlesztéssel, a jobb oldalon pedig a teszteléssel. Lényege, hogy minden fejlesztési lépéshez egy azzal párhuzamos tesztelési szint tartozik, így a tesztelési feladatok már a projekt elején elkezdődnek. Ez csökkenti a hibák felfedésének késedelmi kockázatát, és biztosítja, hogy a rendszer minden követelménynek megfeleljen. 
<img src="https://rockkid777.github.io/pti-msc-2015-zv/s01/img/v_model.png" alt="image" width="300" height="220">

### Agilis modell
Az agilis tesztelési modell a szoftverfejlesztés agilis megközelítéséhez illeszkedő, iteratív tesztelési megközelítés, ahol a tesztelés a fejlesztéssel párhuzamosan, szorosan együttműködve zajlik. Ez ellentétben áll a hagyományos, sorozatos (waterfall) modellel, amelyben a tesztelés csak a fejlesztés befejezése után történik. Az agilis tesztelés kulcselemei az együttműködés, a rugalmasság és a folyamatos visszajelzés. 
<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" alt="image" width="300" height="220">

### TDD és a BDD modell
A TDD (Tesztvezérelt Fejlesztés) és a BDD (Viselkedésvezérelt Fejlesztés) olyan szoftverfejlesztési modellek, amelyek a tesztelést hangsúlyozzák a kód írása előtt. A TDD elsősorban egységteszteken keresztül működik, amelyek a kódegységek működését ellenőrzik. A BDD a TDD-re építve az egységteszteket a rendszer egészének viselkedésére fókuszáló, közérthető nyelven megfogalmazott tesztekre bővíti ki, amelyeket a fejlesztők, tesztelők és üzleti szereplők együtt írnak meg. 
<img src="https://static.wixstatic.com/media/166140_5a3460960fcb426c9e4302268a30746e~mv2.png/v1/fill/w_722,h_542,al_c,q_90,usm_0.66_1.00_0.01,enc_auto/166140_5a3460960fcb426c9e4302268a30746e~mv2.png" alt="image" width="300" height="220">