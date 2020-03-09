# Käytännön Rauhankone, osa 2: Mitä voisimme rakentaa nyt?

Ensimmäisessä osassa käsittelimme koneälyä yleisesti. Nyt voimme hypätä suoraan Rauhankoneeseen.

Timo Honkela esittelee kirjassaan Rauhankone kolme eri konseptia. Jokainen niistä kuvailee tavan, jolla koneäly voisi parantaa ihmisten välistä kommunikaatiota.

Tarkoitusneuvottelevakone tunnistaa, kun ihmiset puhuvat samasta asiasta eri sanoin, ja opastaa keskustelijoita tunnistamaan merkityserot.
Tunnekone analysoi ihmisten puheesta heidän tunnetilojaan ja auttaa sitä kautta ihmisiä ymmärtämään paremmin niin itseään kuin toisiaan.
Miljoonan ihmisen kokous jakaa massakokoukset pienemmiksi yhdenaikaisiksi keskusteluiksi, joista kone hakee ja tiivistää suurten massojen osaamista ja mielipiteitä ymmärrettäväksi kokonaisuudeksi.

On kaksi asiaa, joista Honkela on kirjassaan erittäin selkeä. Ensinnäkin, Rauhankone ei ole mustalaatikko, joka tuodaan neuvottelupöytään, kun ratkotaan konflikteja. Ja toiseksi, mitään kolmesta konseptista ei voida rakentaa kokonaisuudessaan tämän päivän teknologioilla. Mutta kuinka pitkälle voisimme päästä juuri nyt?

## Merkitysneuvottelu

Merkitysneuvottelun idea tukee tensorianalyysiin. Tensorit ovat moniulotteisia taulukoita, jotka tässä tapauksessa sisältäisi konsepteja ja niiden välisiä yhteyksiä.

Merkitysneuvottelun käyttö yleisessä keskustelussa vaatisi tietoa keskustelijoista, heidän tietotaidostaan, kielestään ja mahdollisesti jopa arvoistaan. Näiden tietojen avulla koneen tulisi tulkita, miten yhden keskustelijan tapa puhua asiasta X eroaa toisen keskustelijan tavasta.

Tarvittava määrä tietoa ja laskentatehoa on yksinkertaisesti mahdotonta tänä päivänä. Mutta ehkäpä voisimme katsoa jotain rajattua tapausta? Kuten osassa 1 mainittiin, koneäly toimii parhaiten rajatuissa tapauksissa. Yksi tapa muuttaa lähestymistä on live-keskustelun sijasta käsitellä ennakkoon käytyä keskustelua.

Honkela kuvaa kirjassaan tutkimusta, jossa oli vertailtu, millaisia sanoja Yhdysvaltain demokraatit ja republikaanit puhuvat terveydestä. Kun tulkitaan tarpeeksi suurta määrää puheita, nähdään, että nämä kaksi puoluetta yhdistävät hyvin erilaisia ajatuksia ja termejä samoihin sanoihin.

Vaikka tällainen analyysi onkin melko kaukana yleisestä merkitysneuvottelusta, sillä voi olla käytännön sovelluksia. Ennen kaikkea politiikassa on tärkeää nähdä sanojen ja retoriikan taakse, jotta puolueiden todelliset erot tulevat esille.

## Tunneanalyysi

Tunneanalyysi on yhtä aikaa kaikista eniten ja vähiten valmis Rauhankoneen konsepteista. Tunneanalyysille (tai sentimenttianalyysille) on saatavilla lukuisia työkaluja, joiden päälle voisi helposti rakentaa käytännönsovelluksia. Hyödyllisiä kulmia sovelluksille on kuitenkin hankala löytää.

Saatavilla olevat palvelut hyödyntävät koneoppimista. Järjestelmille on tarjottu suuri määrä tekstiä, joka on merkitty tunnetiedolla. Tämän opetusdatan pohjalta järjestelmä osaa arvioida tunnetta tekstistä.

Tämä lähestyminen on kuitenkin kaikkea muuta kuin täydellinen. Tunnetilan arviointi tekstistä on haastavaa jopa ihmiselle. Tekstistä puuttuu kaikki non-verbaalinen kommunikaatio, kuten äänen rytmi ja sävy. Tämän takia esimerkiksi sarkasmin ja ironian tunnistaminen muuttuu mahdottomaksi.

Koneälyllä ei myöskään ole asiayhteyttä. Jos opetusdata on ollut liian yleistä, jotkin aiheet voivat yhdistyä algoritmin mielestä suoraan tiettyihin tunteisiin, vaikka teksti itsessään ei sitä indikoisikaan.

Otetaan esimerkiksi sana "sota". Yleisessä keskustelussa sota mainitaan yleensä surullisten tai turhautuneiden kommenttien yhteydessä. Jos analysoimme tekstiä, jossa puhutaan nimenomaan sodasta ja rauhasta, sana "sota" voi esiintyä myös toiveikkaassa tai iloisessa lauseessa. Koneäly todennäköisesti tulkitsisi lauseen surulliseksi tai turhautuneeksi pelkästään "sota" -sanan perusteella.

Tähän mennessä olemme kattaneet teknisiä rajoituksia. Mutta kun puhutaan tunteista, emme voi unohtaa ihmisten tuomia rajoituksia. Ihmiset eivät pidä siitä, että heidän tunteitaan nimetään. Kuvittele kone, joka kertoisi sinulle: "Näyttää siltä, että olet suuttumassa". Tämä tekisi sinusta todennäköisesti vihaisemman.

Kun Honkela puhuu tunneanalysistä, hän puhuu oppimisesta. Opimme itsestämme ja reaktioistamme sekä siitä, millaisia reaktioita aiheutamme muille. Rauhanteknologian kannalta tämä on tunneanalyysin tärkein sovelluskohta. Reflektiotyökaluna.

Reflektio ei ole helppoa kenellekään. Se pakottaa ihmisen kyseenalaistamaan omat tunteensa ja päätöksensä. Siinä kone neutraalina osapuolena voisi auttaa. Siihe, jopa nykyisiä palveluita voisi hyvinkin soveltaa.

## Miljoonan ihmisen kokous

Ajatuksena miljoonan ihmisen kokous on yksinkertainen. Poliittinen järjestelmämme pohjautuu harvojen ja valittujen mielipiteeseen. Jos ihmiset voisivat käydä keskusteluja pienissä ryhmissä, voisimme hyödyntää näitä keskusteluja kollektiivisen tiedon ja osaamisen keräämiseen.

Kone hakisi keskusteluista yhteisiä teemoja sekä mielipiteitä ja yrittäisi niiden pohjalta kerätä tiivistyksen keskustelusta. Kone voisi myös syöttää näitä tietoja takaisin keskusteluihin.

Kuinka mahdollinen tällainen idea on? Miljoonan ihmisen saaminen keskustelemaan samasta aiheesta on jo sinänsä haastavaa. Varsinkin, jos keskustelu tulisi käydä yhdellä ja samalla alustalla.

Kuulostaa vaikealta, mutta tätä tapahtuu joka päivä. Twitterin ja Facebookin eniten keskustellut aiheet keräävät miljoonia yhtäaikaisia keskusteluja ympäri maailman. Teknologia datan keräämiseen on siis olemassa.

Tarvitsemme tiedonlouhintaa, johon yleisesti viitataan myös suomeksi sen englanninkielisellä nimellä data mining. Se on yhdistelmä koneoppimista ja statistiikkaa, joiden avulla haetaan datamassoista tunnistettavia kaavoja.

Yksi esimerkki on etsiä keskustelumassoista eniten käytettyjä sanoja ja niiden yhteyksiä. Käsittelimme tensoreita merkitysneuvottelun yhteydessä. Puhumme jälleen aika samoista ideoista.

Sanojen ja niiden välisten yhteyksien kautta voisimme saada visualisoinnin, joka kertoo, mistä on keskusteltu. Tästä eteen päin tarvitaan ihmistä tekemään tarkempia tulkintoja keskustelun sisällöistä. Kone voi siis visualisoida keskustelua, muttei osaa muodostaa mielipiteitä tai ehdotuksia.

Toinen vaihtoehto olisi käyttää automaattista yhteenvetoa. Ongelmaksi muodostuisi kuitenkin todennäköisesti se, että sisältöä syntyy niin paljon, ettei kone kykenisi tiivistämään sitä järkevällä tavalla luettavaksi kokonaisuudeksi. Asiantuntija pystyisi todennäköisesti tulkitsemaan hyvin visualisoitua sisältöä tehokkaammin.


## Yhteenveto

Timo Honkela kuvaa kirjassaan utopian. Rauhankone voi hyvinkin toimia tulevaisuudessa, mutta koneiden liittäminen osaksi ihmisten välistä keskustelua sisältää myös merkittäviä riskejä.

Tämän päivän koneäly toimii parhaiten rajatuissa ongelmissa. Jos voimme määritellä kysymyksen tarpeeksi tarkasti, koneäly tuottaa hyviä tuloksia. Yleisessä tapauksessa, ihminen on vielä konetta etevämpi.
