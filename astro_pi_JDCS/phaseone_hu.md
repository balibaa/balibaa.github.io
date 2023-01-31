# 1. forduló - a beadott ötlet

## Szabályozott környezetek összehasonlítása

A cél a Nemzeközi Űrállomáson 3 órán keresztül szenzor adatokat gyűjteni, kielemezni az ingadozásokat, minimum és maximum értékeket és átlagokat. Meghatározható-e egy minimum minta érték a különböző szenzorokra, amivel egy jó becsült átlag megadható? A hőmérséklet, nyomás és páratartalom esetében alacsony ingadozás várható. A giroszkóp és a mágmeses szenzoror várhatóan megjósolható értékeket adnak. A gyorsulásmérő értékeit valószínűleg befolyásolják majd az űrhajósok (előre megjósolhatatlan) cselekedetei.

A 3 óra alatt terv szerint több mint 10.000 szenzor érték rögzíthető 1 másodperces intervallumokkal.

**A rögzített értékek összehasonlítása:**

* teljes kísérlet (minden egy másodperces minta értéke)
* 5 percenként egy érték
* 1 percenként egy érték
* 1 másodpercenként egy érték
* néhány rövid, de "amilyen sokat csak lehet" minta, függően a személyzet közelségétől (személyez közel) vagy "nincs személyzet a közelben" részeiről a kísérletnek. Arra számítunk, hogy található egy "ideális" minta gyakoriság a különböző szenzorokhoz, ami ugyanazt az átlagot mutatná, mit a teljes kísérlet értékeinek átlaga. Így növelhető lenne jövőbeli kíérletek hatékonysága.

A PIR és a szín-, és fényérzékeő szenzorokat használva **megpróbáljuk beazonosítani az űrhajósokat** és összefüggést keresünk a hőmérséklet és a gyorsulásmérő értékei között (erre számítunk). Ellenőrizzük, hogy kimutatható-e változás egyéb szenzorok értékeire, amelyek a személyzet közelségével magyarázhatók. A kamera segítségével (valószínűleg a tökröződő fény alapján) megpróbáljuk megerősíteni, hogy ki az űrhajós (a Coral AI gyorsító használatával). Különböző személyek közelsége esetén másféle képet jelenítenénk meg a led kijelzőn.

**Különböző led képek megjelenítése** a különböző felismert személyzet közelsége esetén. Ellenőrizzük, hogy vibráló, villogó  képek esetén tovább maradnak-e a kijelző közelében? (Ez törölhető, természetesen nem akarjuk az űrhajósok figyelmét elvonni. Az elmélet az, hogy talán (tovább) figyelnek a képernyőre, ha kiszámíthatatlanul villog, mikor közelítenek hozzá.)

Miután a véglegesített kísérlet lefut az ISS-en, **ugyanaz a kísérlet lefutnat a Földön**, a gyerekek által választott "szabályozott környezetekben". Az ötlet az, hogy ugyanaz a kísérlet fusson le, ugyanazokkal az elvárásokkal (kivéve a Föld megkerülését természetesen), és a végén hasonlítsuk össze az eredményeket. Melyik környezet stabilabb? Hol voltak a részvevők tovább a PI közelében?

**Ötletek, ahol úgy gondoljuk, a kísérletet meg lehetne ismételni:**

* iskolában
* kisállatkereskedésben
* cserkésztáborban
* vonatúton
* könyvtárban
* parkban
* éjjel, a teraszon (macska kölcsönhatásra számítunk :)
* otthon, a konyhában (a gyerekek testvérek)

## Adatok

**Szenzor adatok rendszeres időközönként:** (1 másodpercenként javasoljuk, 10000 ciklusra számítunk a kísérlet során)

**Szenzor adatok maximális mintavételezési sebességgel:** rövid időtartamok legalább 20 alkalommal kölcsönhatásra (személyzet közelsége) és 20 alkalommal, mikor nincs kölcsönhatás (csendes időszakok).

**Az azonosított személyzet összehasonlítása a szenzos ér kamera adatokkal:** a visszavert fény elemzése apalján, amikor mozgás érzékelése történik. (Kérem szóljanak, ha ez lehetetlen, jó ötletnek tűnik, de a hardwer talán nem teszi lehetővé.)

**+1. Ugyanezek az adatok a megismételt "földi" kísérletekből:** Az elemzés a végén talán csak az ISS adataira koncentrál majd, de a végső cél a különböző környezetekben előforduló kilengések és az "ideális mintavételezési gyakoriság" összehasonlítása lenne.

## Gépi tanulás használata

Terv szerint megpróbálnánk a különböző személyeket a visszavert fény (ruha színe valószínűleg) és a hőmérséklet különbségei alapján azonosítani.
