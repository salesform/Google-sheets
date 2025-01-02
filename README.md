# Google-sheets
Google sheets App scriptek

# Használatuk

Nyisd meg a Google Sheets-t, majd kattints a Bővítmények > Apps Script menüpontra.
Illeszd be a kiválasztott kódot
Ments és futtasd. Add meg a szükséges engedélyeket és ha kell időzítsd

## HATALMAS rendelési adatok Google CSV exportja

1, Ha túl sok rendelésed van, akkor App sciptet kell használnod

2, Testreszabása:

  a, 3. sorban add meg a SalesForm szoftverből kapott URL címet

  b, Állíts be időzítést, az óra ikonra kattintva (trigger)

    - állíts be új aktiválót
    - Futtatandó funkció: importLargeCSV
    - Eseményforrás: idő alapú
    - Az időalapú aktiváló: napidőzítő
    - 02:00-03:00 legyen
    - MENTÉS

  c, A google sheets ben létrejön egy SalesForm munkalap és abba kerülnek bele az adatok


## Előfizetések és sima rendelések kezelése egy táblázatban

Ez akkor is működik, ha több SalesForm szoftvert használsz.

Egyszerre hoz létre 5 munkalapot.

- Sikeres rendelések: ide kerül minden sikeres rendelés
- Sikeres előfizetések: ide kerül minden sikeres előfizetés
- Sikertelen rendelése: mindenki aki nem tudott leadni rendelést (az is aki nem tudott előfizetni nálad)
- Lejárt előfizetések: Akik nem tudta vonni a SalesForm a havi díját, de nem momndták le (3 naponta újra próbáljuk)
- Törölt előfizetések: Akik lemondták az előfizetéseidet
