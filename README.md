# Általanos információk

## Csapatok összeállítása

A félév elején a kurzus hallgatóiból 2-3 fős csapatokat állítunk össze. Ennek megszervezése alapvetően a hallgatók feladata. Ezt
[Ennek a táblázatnak](https://docs.google.com/spreadsheets/d/1p0TsBbAVa2YAOYLpg4l1MPVzsMZLEM9Fl2YJtVPmkk4/edit#gid=0)
a segítségével lehet megtenni. Értelemszerűen a "csapat sorszáma" oszlopba kell beírni
a csapat sorszámát. A táblázatot később letisztázom és a kimaradó emberekből (ha
lesznek) véletlenszerűen állítok össze csapatokat.

## Verziókövetés

A csapatoknak a készülő kódot és a dokumentációt egy GitHub repositoryban kell
verziókövetve tárolniuk. Ehhez mindenkinek regisztrálnia kell a GitHubra és
a felhasználónevét be kell írnia a feljebb már említett [táblázatba](https://docs.google.com/spreadsheets/d/1p0TsBbAVa2YAOYLpg4l1MPVzsMZLEM9Fl2YJtVPmkk4/edit#gid=0).

Minden csapatnak létre fogok hozni egy repositoryt, aminek a linkje
például a következő lehet:
[https://github.com/OE-AMK-Projektmunka1-2022/PL2021B_20](https://github.com/OE-AMK-Projektmunka1-2022/PL2021B_20)

A GitHub használatát egy másik dokumentum tartalmazza.

### README.md

A repositoryban levő README.md fájl a projekt rövid összefoglalója.
Itt szerepelhet például:

 * A csapattagok névsora, Neptun kódja, esetleg elérhetősége
 * A projekt neve, elnevezése
 * A projektről néhány mondat, amiből képet kapunk arról, hogy mit csinál a csapat
 * A felhasznált technológiák, programnyelvek
 * Az előrehaladási napló (nagyobb mérföldkövek; mit csinált a csapat)

A README.md formátuma MarkDown, ami egy egyszerű szövegformázó (markup) nyelv.
Rövid leírás például [itt](https://www.markdownguide.org/basic-syntax/).

**A README.md naprakészen tartása elvárás a kurzus teljesítéséhez.**

### .gitignore

A .gitignore fájl arra való, hogy bizonyos fájlokat automatikusan figyelmen kívül
hagyjunk a verziókövetés során. Ezek például a projekt fordítása során létrejövő,
a forráskódból generált fájlok. Interneten számos példa lelhető fel ezzel kapcsolatban.
Egy kiindulási alap lehet például
[ez a gyűjtemény](https://github.com/github/gitignore).

**A .gitignore fájlnak az adott fejlesztőeszközhöz passzoló kitöltése elvárás
a kurzus teljesítéséhez.**

### Könyvtárstruktúra

A repositoryban külön könyvtárban kell elhelyezni a projekt forráskódját (és a
kapcsolódó egyéb fájlokat), a dokumentációt, illetve az egyéb állományokat.
Néhány példa:

 ** **src**: A projekthez tartozó forráskódok
 ** **firmware**: Az esetleges mikrovezérlős forráskódok
 ** **docs**: Dokumentációk
 ** **schematics**: Kapcsolási rajzok
 ** **screenshots**: Képernyőképek

**A kurzus során elvárás a tiszta könyvtárszerkezet használata.**

### Commitok

A változásokat commitok formájában lehet a verziókövetőbe feltölteni. Minden
commithoz szükséges kitölteni a "commit message"-et is. A feltöltéshez
csak végső esetben használjuk a "file upload" funkciót!

**A kurzus során elvárás, hogy legyen legalább 10 olyan hét, amikor ÉRDEMI
változás történik a repositoryban és ezt a commitok dátuma is tükrözi.**

**Szintén elvárás, hogy minden csapattag esetében legyen legalább 3-3 olyan hét,
amikor az adott csapattagnak ÉRDEMI commitja van.**

Érdemi commit lehet akár egy egyeztetésről szóló bejegyzés az előrehaladási
naplóban, vagy akár valamilyen, a projekthez kapcsolódó ötlet, vagy kísérlet nyoma
(fotó, rövid leírás stb) is.

# Témák

A következőkben néhány témajavaslat kerül felsorolásra. Ezek egy része konkrét,
de vannak általános, sokféle irányba elvihető ötletek is.

## Rubik kocka kirakását segítő program

## Imagine társasjáték online megvalósítása

## Travelin' társasjáték online megvalósítása

## Tangram társasjáték online megvalósítása


