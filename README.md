# MetaCortex-AAEE
MetaCortex - Adatalapú eseményelemzés beadandó

01_MetaCortex_AAEE_prep:
- adatok betöltése Dropboxról
    - adatok letöltése: CRSP - 2023. november 10. / SP500 - 2023. november 16. / FF3 - 2023. november 20.
- CRSP szűrve 'ordinary common share-ekre'
- NYSE, AMEX, NASDAQ
- Adattisztítás (negatív volumenek, 100%-nál nagyobb negatív hozamok törlése)
- Napi loghozamok képzése
- Dátum formázások

02_MetaCortex_AAEE_anal_linked:
- adatok betöltése Dropboxról
- SIC kód fordítótáblák próbálgatása, majd elvetése
- merge
- iparági csoportok képzése
- leíró táblák
- portfólióképzés, MM és FF3 futtatása loopban minden iparágra

03_sp500_chart:
- S&P 500 szeptemberi napi hozamok 20 évre - chart
