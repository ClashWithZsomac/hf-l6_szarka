**Házi feladat 2**

Csapattagok Neptun kóddal:
- Szarka Zsombor Zsolt (EV6KUK)

Bemutató videó URL: [videó]()

**Plusz pontot érő technológiák**
(Amit elkészítettetek, azt X-eljétek be!)

- [ ] 3p: IValueConverter
- [ ] 5p: ICommand
- [ ] 5p: StaticResource használata
- [ ] 8p: Fájl megnyitása, elmentése
- [ ] 5p: Linq2Xml használata
- [ ] 5p: Canvas és Shape használata
- [ ] 8p: Regex használat nem triviális feladatra
- [ ] 10p: Legalább 20% unit teszt lefedettség
- [ ] 8p: Heterogén listához adatkötés (DataTemplateSelector)
- [ ] 5p: MVVM architektúra (legalább 3 modell és 3 view model osztállyal)
- [ ] 5p: Többszálúság: Task és async-await használata.

Olyan plusz pontok, amiket nem fed le a tananyag
- [ ] 8p: Behaviour használata
- [ ] 8p: Animációk használata
- [ ] 5p: Style használata. Az 5 pont saját definiált stílusra vonatkozik, ami legalább 2 propertyt beállít. Előre gyártott stílus használata 1p.
- [ ] 5p: OpenCvSharp használata

A hivatalos teljes lista a Moodle alatt olvasható.

**Megjegyzések az elkészült megoldáshoz**
# Étterem rendeléskezelő rendszer

## A program célja:
A program célja, hogy egy felhasználói felületet biztosítson a végfelszolgáló számára, valaminthogy  rendeléseket tudjon felvenni,
amelyeket továbbít a konyhának. A rendeléseket a konyhában meg tudja jeleníteni, ahol jelezik, hogy elkészült, vagy rosszabbik esetben visszaküldhetik
,hogy nem tudják elkészíteni (pl.: nincs készleten a megfelelő hozzávaló).

## A program működése:
### Felszolgáló:
Első indításkor a felhasználó megadhatja az étteremhez adatait (asztalok száma, stb...).
Ezután betöltődik a menü, ahol az aktuálisan kiválaszott asztal rendeléseit lehet megnézni.
Itt lehet új rendeléseket hozzáadni minden asztalhoz, illetve számlázni is. Lehet foglalásokat hozzáadni ezen felül.
Az admin felületen keresztül lehet szerkeszteni a korábban hozzáadott ételeket, hozzáadni új ételt, új asztalt valamint feltölteni a készletet.

### Konyha:
Megjeleníti a rendeléseket, amiket kijelölve
- "elkészült"-nek lehet jelezni,
- "nem készíthető el"-nek lehet jelezni.

**A videó újrahasznosíthatósága**

A házi feladat videót oktatási célokra újrahasznosíthatjuk? (Későbbi évfolyamoknak bemutatás, vágott anyagban felhasználás.)
- [ ] Igen, a szerzők megjelölésével
- [X] Igen, névtelenül
- [ ] Nem

**Ellenőrzési lista**
- A pull request címe utal a tartalomra. Pl. HF2
- A pull requestben csak azok a változások szerepelnek, amiket a megoldás során te hajtottál végre. A bin és obj könyvtár tartalma ugye nincsen benne?
- A forráskódban nincsennek kikommentezett kódrészletek.
- Reviewernek megadtad a Neptun szerinti kurzusod laborvezetőjét, és csak 1 reviewert adtál meg.
