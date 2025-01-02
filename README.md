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
