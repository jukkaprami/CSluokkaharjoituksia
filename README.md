# CSLuokkaharjoituksia

Esimerkkejä ja harjoituksia C# luokista ja olioista.

## Luokkien periytyminen

Luoka voi periä toiselta luokalta kentti ja metodeja. Luokkaa, jonka ominaisuuksia peritään (inheritance) kutsutaan yliluokaksi (superclass, parent class) ja periävää luokkaa aliluokaksi (subclass, child class).
Perimisen keskeinen idea on se, että määriteltyjä ominaisuuksia (kenttiä) ja metodeja ei tarvitse enää määritellä aliluokassa, riittää että kerrotaan niiden periytyvän yliluokasta. Yliluokalla ja aliluokalla voi olla saman
nimisiä metodeja, jotka toimivat eri tavalla. Tätä kutsutaan metodien ylikirjoittamiseksi (method overload). Jos aliluokalla metodi on kirjoitettu eri tavalla kuin yliluokassa, yliluokan määritys syrjäytyy.
