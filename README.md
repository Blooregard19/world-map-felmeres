# world-map-felmeres

Interaktív térképes megjelenítés

Az országok kódjai:
https://en.wikipedia.org/wiki/ISO_3166-1_numeric

Fő segédlet:
https://gis.stackexchange.com/questions/70511/d3-for-maps-at-what-stage-to-bring-in-data-to-the-geo

További példák:
http://bl.ocks.org/jasondavies/4188334
https://bl.ocks.org/mbostock/4180634
https://bl.ocks.org/mbostock/5912673

Zoomolás:
https://bl.ocks.org/mbostock/4699541
https://bl.ocks.org/mbostock/2206590
http://bl.ocks.org/d3noob/5189284

Tesztüzem:
https://rawgit.com/Blooregard19/world-map-felmeres/master/index2.html

Egyéb források:
http://datamaps.github.io/
http://www.tnoda.com/blog/2013-12-07

SVG-ben blokkok mozgatása (előre kiszámolt helyeken lehetnek a blokkok, csak mindegyikhez a megfelelő kezdési pontot kell hozzárendelni)
blokkokhoz lehet-e feliratot és png képet rendelni
http://bl.ocks.org/bycoffe/21061661b1450a4db92a

Egyéb térképes infók:
https://stackoverflow.com/questions/40245081/d3-append-copy-of-g-element-on-click-to-separate-div
http://bl.ocks.org/eesur/4e0a69d57d3bfc8a82c2
https://bl.ocks.org/syntagmatic/0613ee9324e989a6fb6b
https://stackoverflow.com/questions/40329667/d3-js-markers-dont-display-on-map
http://www.ewelinawoloszyn.com/mymap/d3_projection03.html
http://bl.ocks.org/emeeks/f8c0220c54ec8347ea95
http://bl.ocks.org/madelfio/7094945

Zoom példa v4-ben:
https://bl.ocks.org/mbostock/b783fbb2e673561d214e09c7fb5cedee

- a térképre kellene összehasonlító funkció, amikor az adott országnál jobbak, rosszabbak szerint színez
- a térképre kellene egy országválasztó, amivel adott országra lehet zoomolni
- a térképet nem kellene engedni egy bizonyos zoomout alá, kb akkor kellene megállítani, amikor a széle eléri az svg szélét
- térképnél a kiválasztott országot követően lehetne összehasonlítást kérni az országról
- térképnél az évválasztáskor a köröket és számokat le kell cserélni, ha nagyítás van
- nyelvválasztás zászlókkal
- térképnél összehasonlítás alapján színezze az országokat
- minimum, maximum értékek alapján is színezhessen a térképen
- térképre jelmagyarázat kell
- https://stackoverflow.com/questions/25015262/how-to-correctly-update-the-text-value-of-an-input-element-in-a-d3-js-transition
- https://stackoverflow.com/questions/32008125/using-javascript-to-change-website-language
- https://bl.ocks.org/mbostock/4183330
- térképnél még lehetne, hogy a kör és szám kettősére egy újabb átlátszó kört rakni és az kapja a title-t, így mindig ki lennének írva az adatok (esetleg bővebb infoboxot ír ki)
- a térkép json-jét bővíteni lehetne Sao Tome-val és Comoros-szal
- másfajta tooltip: https://github.com/tietyk/D3/blob/master/Prototype/part8-9.html
- https://bl.ocks.org/fabiovalse/b9224bfd64ca96c47f8cdcb57b35b8e2
