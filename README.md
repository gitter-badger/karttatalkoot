# Karttatalkoot

[![Join the chat at https://gitter.im/latutilanne/karttatalkoot](https://badges.gitter.im/latutilanne/karttatalkoot.svg)](https://gitter.im/latutilanne/karttatalkoot?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Tämä projekti sisältää web-sovelluksen, jonka avulla voidaan linkittää
[OpenStreetMap](http://www.openstreetmap.org/#map=15/60.2715/25.1379&layers=D):stä
saatavat latu-urat sekä muut hiihtämistä edistävästä meta-tiedot
[kartta.latutilanne.fi](http://kartta.latutilanne.fi) latutietoihin.

[![Build-status](https://img.shields.io/travis/latutilanne/karttatalkoot/master.svg?style=flat-square)](https://travis-ci.org/latutilanne/karttatalkoot/branches/)
[![Kehittäjien chat](https://img.shields.io/gitter/room/nwjs/nw.js.svg?style=flat-square)](https://gitter.im/latutilanne)

## Osallistuminen

Kaikki apu otetaan vastaan! Huomioithan, että avun ei tarvitse olla ohjelmointia:
**myös käyttöliittymäsuunnittelua ja grafiikkaa tarvitaan**. Liity kehittäjien keskusteluun
**[Gitterissä](https://gitter.im/latutilanne)**!

Mikäli halaut osallistua tämän projektin kehitykseen, voit tehdä sen
pull requestin avulla. Mikäli haluat luoda uuden ominaisuuden, luo siitä 
ensiksi issue **[trackeriin](https://github.com/latutilanne/karttatalkoot/issues)**
ja varmista, että kehitystiimi hyväksyy ominaisuuden. Vasta tämän jälkeen
kannattaa aloittaa ominaisuuden toteutus (ettei tule turhaa työtä).

Bugikorjauksille ei tarvitse hyväksyttää issueita.

### Ennen pull requestin lähettämistä

Varmista että testit menevät läpi ja dokumentaatiot ovat päivitettynä
(mikäli jotain muuttunut).


## Devaus

### Ympäristön pystytys

    git clone git@github.com:latutilanne/karttatalkoot.git
    cd karttatalkoot && npm i
    npm run watch
    open http://localhost:3000    # osx 

### Testien ajaminen

    npm test 
    
    
## Lisenssi

MIT
