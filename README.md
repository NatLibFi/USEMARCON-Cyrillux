# BookWhere-konversio (RDA)

KUVAUS

Pääasiassa Melinda-kirjastoille suunnattu USEMARCON-konversiosääntö esimerkiksi BookWhere-ohjelmalla ulkomaisista tietokannoista poimittujen **kyrillisten** bibliografisten MARC 21 -tietueiden muuntamiseen kotimaisten luettelointikäytäntöjen mukaisiksi. Konversio mm. poistaa turhia kenttiä, suomentaa tekijän funktiot sekä asettaa tai kääntää RDA-kuvailuohjeiden mukaiset 336-, 337- ja 338-kentät.

Konversio perustuu yleiseen poimintaluetteloitavien tietueiden konversioon (ns.
[BookWhere-konversio (RDA)](https://github.com/NatLibFi/USEMARCON-BOOKWHERE-RDA).

Lisätietoja USEMARCON-ohjelmasta löytyy MARC 21-formaatin [wikistä](https://www.kiwi.fi/display/Marc21/USEMARCON).

KEHITYS

Konversio on kehitysvaiheessa ja siihen on tulossa paljon muutoksia ja
korjauksia (ks. Issues-välilehti).

KÄYTTÖ

Konversio on käytössä Melindassa käytettävän [Cyrillux-translitterointiohjelman](https://cyrillux.melinda.kansalliskirjasto.fi/) taustalla. Konversio ajetaan ennen translitterointia tietueille, jotka ladataan ohjelmaan paikalliselta päätteeltä. Konversio tekee tietueille esikäsittelyn ennen merkistön muuntamista.

PALAUTE

marc-posti (at) helsinki.fi

=================

DESCRIPTION

A USEMARCON rule for Finnish libraries for processing cyrillic MARC 21 records from foreign databases.
