# CSLuokkaharjoituksia

Esimerkkejä ja harjoituksia C# luokista ja olioista.

## Luokkien periytyminen

Luoka voi periä toiselta luokalta kentti ja metodeja. Luokkaa, jonka ominaisuuksia peritään (inheritance) kutsutaan yliluokaksi (superclass, parent class) ja periävää luokkaa aliluokaksi (subclass, child class).
Perimisen keskeinen idea on se, että määriteltyjä ominaisuuksia (kenttiä) ja metodeja ei tarvitse enää määritellä aliluokassa, riittää että kerrotaan niiden periytyvän yliluokasta. Yliluokalla ja aliluokalla voi olla saman
nimisiä metodeja, jotka toimivat eri tavalla. Tätä kutsutaan metodien ylikirjoittamiseksi (method overload). Aiemissa versioissa aliluokassa määritelty metodi, joka on kirjotettu eri tavalla kuin ylilluokassa syrjäytti aliluokan saman nimisen metodin. Uusimmat kääntäjät eivät kuitenkaan toimi näin Aliluokan metodi on määritelty syrjäyttäväksi (overide). Toinen vaihtoehto on käyttää aluokan metodeja määrityksessä `new` -komentoa yliluokan metodin syrjäyttämiseksi. Jos `new` jätetään pois aliluokka syrjäyttää edelleen yliluokan (toisin kuin dokumentaatiossa lukee). Seuraavassa esimerkissä on kolme luokka: yliluokka lemmikinomistajalle ja sekä kaksi aliluokkaa kissanomistajalle ja koiranomistajalle.


