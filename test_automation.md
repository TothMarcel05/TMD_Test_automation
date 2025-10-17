# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

## A tesztelés alapjai:
#### Mi a tesztelés célja? Mi nem az?
– A tesztelés célja a hibák és hiányosságok megtalálása, a minőség javítása és a kockázatok csökkentése.

#### Mi a kapcsolat a tesztelés és a hibamegelőzés között?
– A jó tesztelés nemcsak hibákat talál, hanem segít megelőzni is őket azáltal, hogy visszajelzést ad a fejlesztés korai szakaszaiban.


#### Miért fontos, hogy a tesztelők függetlenek legyenek a fejlesztőktől?
– A független tesztelők objektívebbek, mert nem ők írták a kódot, így több hibát deríthetnek fel.

#### Mi a veszélye annak, ha a fejlesztő maga teszteli a saját kódját?
– Hajlamos lehet kihagyni hibákat, mert ugyanúgy gondolkodik, mint amikor írta a kódot (vakfolthatás). Több másik ember szemszögét nem képes hatékonyan felvenni

#### Mik a tesztelési alapelvek?
– Kimerítő tesztelés lehetetlen, Hibafürt, Növényvédő szer-paradoxon, A tesztelés bizonyítja, hogy a szoftverben vannak hibák, Hiba hiánya, Korai teszt a szoftverfolyamatban, A tesztelés kontextustól függ.


#### Mit jelent az „alapvető tesztelési elv”, hogy „a kimerítő tesztelés lehetetlen”?
– Nem lehet minden lehetséges bemenetet és kombinációt letesztelni, ezért a tesztelés fókuszált és kockázatalapú kell legyen.


#### Mit jelent az „alapvető tesztelési elv”, hogy „a hibák halmozódnak”?
– A hibák nem véletlenszerűen oszlanak el, általában egy alkalmazás bizonyos részeiben több hiba koncentrálódik.

#### Mit jelent az „alapvető tesztelési elv”, hogy „a tesztelés a kontextustól függ”?
– A tesztelés módszere változik a cél, iparág vagy termék szerint.



## 2. Tesztelés a szoftverfejlesztés életciklusán át
#### Mik a tesztszintek, és mi a különbség köztük?
– Egységteszt, integrációs teszt, rendszerteszt, felhasználói elfogadási teszt – különböző szintű komponenseket és funkcionalitást vizsgálnak.

#### Miért nem érdemes mindig ugyanazokat a teszteseteket futtatni (regressziós torzítás)?
– Idővel a tesztek „hozzászoknak” a kódhoz, nem derítik fel az új hibákat → szükség van frissítésre és új tesztekre.

#### Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
– A kód legkisebb egységeit (függvény, metódus) teszteli elszigetelten. Általában a fejlesztők írják.

#### Mi a különbség a verifikáció és a validáció között?
– Verifikáció: megfelel-e a specifikációnak.
– Validáció: megfelel-e a felhasználói igénynek.

#### Mik a tesztelési típusok, és mi a különbség köztük?
– Funkcionális (mit csinál a rendszer?)
– Nem-funkcionális (milyen jól csinálja?)
– Változásteszt (regresszió)

#### Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
– Fehér doboz: a belső kódot ismerve tesztel.
– Fekete doboz: csak a bemenet–kimenetet vizsgálja.
– Szürke doboz: részleges rálátással tesztel.

#### Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
– Rendszerteszt: teljes rendszer technikai ellenőrzése.
– UAT: üzleti felhasználók ellenőrzik, hogy megfelel-e az igényeknek.

#### Mi a különbség a statikus és dinamikus tesztelés között?
– Statikus: kód futtatása nélkül. 
– Dinamikus: futtatással keresi a hibákat.
