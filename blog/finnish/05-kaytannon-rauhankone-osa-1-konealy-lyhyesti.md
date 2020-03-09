# Käytännön Rauhankone, osa 1: Koneälyä, lyhyesti.

Futuricen Rauhankone-hanke on tutkinut tekoälyä ja rauhaa eri kulmista. Rauhankoneen isä, professori Timo Honkela, on kuvaillut konseptiaan tulevaisuuden teknologiaksi. Joksikin, mitä ei tänä päivänä voida rakentaa. Me halusimme kuitenkin ymmärtää, kuinka lähelle voisimme päästä tämän päivän teknologialla.

Tämä blogiteksti on jaettu kahteen osaan. Tässä ensimmäisessä osassa käymme läpi lyhyesti koneälyn perusteet. Toisessa osassa syvennymme lähemmin Honkelan konsepteihin, ja arvioimme, mitä niistä voisimme toteuttaa.

## Mitä koneäly on?

Koneäly (engl. artificial intelligence, AI) tarkoittaa koneiden tekemiä dataan perustuvia autonomisia päätöksiä. Data voi olla peräisin toisesta tietojärjestelmästä, ihmiskäyttäjältä tai sensoreilta, jotka tarkkailevat koneen fyysistä ympäristöä.

Usein ihmiset viittaavat koneälyyn algoritmeina, ja sanasta onkin muodostunut lähes synonyymi koneälylle. Mutta kaikki algoritmit eivät ole älykkäitä. Yleisesti ottaen algoritmi on vain perättäisiä ohjeita.

Kokeile: Käden heiluttaminen algoritmina.

1. Nosta kätesi
1. Siirrä kättä vasemmalle
1. Siirrä kättä oikealle
1. Toista kohdasta 2

Ollakseen älykäs, algoritmin pitää olla muutakin kuin samanlaisena toistuvat ohjeet. Algoritmin tulee tulkita ympäristöään, eli dataa, ja valita toimintansa sen perusteella.

Koneälyä voi lähestyä kahdella tapaa. Joko asettamalla sääntöjä, joiden mukaan tulkinta tehdään, tai opettamalla algoritmi aiemmin mitatun datan perusteella. Jälkimmäistä tapaa kutsutaan koneoppimiseksi (engl. mahcine learning, ML).

Jos esimerkiksi haluaisimme luoda järjestelmän, joka ennustaa lapsen silmien värin, voimme määritellä yksinkertaisen säännön: Jos molemmilla vanhemmilla on siniset silmät, lapsella on todennäköisesti myös siniset silmät. Muissa tapauksissa lapsella on todennäköisesti ruskeat silmät. (Toim. huom. Totuus ei ole aivan näin yksinkertainen.)

Jos taas käyttäisimme koneoppimista, tarvitsisimme joukon esimerkkejä vanhempien ja heidän lastensa silmien väreistä. Näiden esimerkkien pohjalta laskettaisiin todennäköisyydet lasten silmien värille perustuen vanhempien silmien väriin.

## Lähestymistavan valinta

Molemmissa lähestymistavoissa on hyvät ja huonot puolensa. Jotkin ilmiöt ovat niin monimutkaisia, että niiden kuvaileminen pelkillä säännöillä on äärimmäisen vaikeaa tai mahdotonta. Puhuttu kieli on hyvä esimerkki tällaisesta ilmiöstä. Siksi luonnollisen kielen käsittely (engl. natural language processing, NLP) käyttääkin yleensä koneoppimista.

Toisaalta, koneoppiminen on kaikkea muuta kuin täydellistä. Tulokset ovat parhaimillaankin vain yhtä hyviä kuin opetusdata. Onko dataa riittävästi? Onko datassa jokin systemaattinen virhe? Mitä sensitiivisempää dataa järjestelmä käyttää, sitä tärkeämpää näiden kysymysten esittäminen on.

Otetaan esimerkiksi pankkijärjestelmä, joka määrittelee, myönnetäänkö hakijalle laina vai ei. Järjestelmä opetetaan aiemmilla lainapäätöksillä. Jos pankki on historiassaan myöntänyt lainoja harvemmin jollain tietyllä postinumeroalueella, algoritmi ei osaa tulkita, mistä ero johtuu. Se tekisi oletuksen, että postinumero on lainan kannalta olennainen tieto ja hylkäisi uudet hakemukset pelkän postinumeron perusteella.

Tällaiset vääristymät eivät ole ollenkaan harvinaisia koneoppimisjärjestelmissä.

Järjestelmien rakentajat vastaavat siitä, ettei tällaisia vääristymiä synny. Kun puhutaan rauhanteknologiasta, on äärimmäisen tärkeää, ettei ihmisiä jaotella epäoikeudenmukaisesti. Huono opetusdata voi johtaa tilanteeseen, jossa uusi järjestelmä vähentää rauhaa sen lisäämisen sijaan.

Koneälyn kaksi lähestymistapaa voidaan myös yhdistää. Sensitiivisen datan käsittelyyn voidaan valita sääntöpohjainen järjestelmän, joka yhdistetään epäsensitiivistä dataa tai monimutkaista ilmiötä kuvaavaan koneoppimisjärjestelmään. Lopputulos voi hyvin olla parempi kuin se, että käytettäisiin vain yhtä järjestelmää tai lähestymistapaa.

## Esitä tarkkoja kysymyksiä, saadaksesi tuloksia

Koneälyutopiat voivat antaa ihmisille kuvan siitä, että koneäly olisi jo todella lähellä ihmisten älykkyyttä. Tämä on kaukana totuudesta. Tosiasassa koneäly toimii parhaiten (tai pelkästään) hyvin rajatuissa tehtävissä.

Koneet eivät toimi kuin ihmiset. Ihmisen aivot ovat erikoistuneet konsepteihin, jotka liittyvät toisiinsa. Koneet eivät ymmärrä konsepteja lainkaan. Koneet näkevät datapisteitä, kuten lukuja, kirjaimia tai lauseita. Kone voi tulkita datapisteiden yhteyksiä, muttei ymmärrä miksi yhteydet syntyvät.

Kun koneälyjärjestelmälle annetaan tarpeeksi dataa, se voi vastata kysymyksiin kuten "Tyttö on kuningattarelle sama kuin mikä on kuninkaalle?" Järjestelmän pitäisi löytää yhteys datasta ja vastata "Poika on kuninkaalle sama kuin tyttö on kuningattarelle". Kone kuitenkin näkee vain sanoja, joita käytetään samalla tavalla. Ihminen puolestaan yhdistää sanat sukupuolen ja yhteiskunnallisen aseman perusteella.


Rauhankoneen kannalta on tärkeää ymmärtää, että koneälyyn on erilaisia lähestymistapoja, että koneäly pärjää parhaiten rajatuissa ympäristöissä, ja että koneen on helpompi nähdä tiedossa yksityiskohtia kuin kuvailla dataa yleisesti. Osassa 2 syvennymme tarkemmin Rauhankoneeseen, ja siihen, miten koneälyn teoria näyttäisi käytännössä.
