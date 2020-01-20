# Időpontok
Script táborok időpontjainak kiosztásához.

## Használat

1. Másold egy új könyvtárba az *idopontok.py* script-et
2. Tedd mellé az *input.csv*-t, amiben ennek a félévnek az adatai vannak, ilyen formátumban: https://docs.google.com/spreadsheets/d/1grnVwJCeQ-mE9ODeCkMsE1DeeorzgoiblZys7PKBupE/edit#gid=0 (Felül a hiányzók táblázata van, alul ugyanilyen sorrendben a táborok kizárt időpontjai helyén x-ek. A teljesen esélytelen hétvégéket (pl. őszi szünet) ki is lehet venni a táblázatból. Vesszővel elválasztott CSV formátumban kell letölteni.)
3. Futtasd a `python idopontok.py` parancsot.
4. A kimenet a *lehetosegek.csv* fájlba lesz írva, amit könnyű táblázatba importálni.

## Problémák
Python 2.7-ben van írva, egyszer átírtam Python3-ra (2019-H1/idopontok3.py), de még sikeres futtatása nem volt, valami karakterkódolási hibaüzenet van a csv olvasásakor.
