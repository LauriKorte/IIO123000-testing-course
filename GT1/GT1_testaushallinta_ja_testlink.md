### Harjoitus:  Testaushallintatyökalun asennus


### Tehtäväkuvaus:

Ryhmätyön tehtävän on perehtyä perinteiseen testauksen hallintatyökaluun ja sen perustoiminnallisuuksiin. 

Kurssin tutustumiskohteena on suosittu Open Source-työkalu nimeltä Testlink.

Ryhmä pystyttää oman koneen käyttäen Linux-virtuaalikonetta. Kone voi sijaita koulun labrakoneilla tai voitte käyttää luoda virtuaalikoneen omalle työasemalle.

*Tarvittavan virtuaalikoneen speksit*

* Ubuntu 14.x-> Server/Desktop
* 16GB levy
* 2-4 GB muisti
* Php5 + MySQL + Apache

HUOM! Jos teet virtuaalikoneen kurssin aikaan, niin kannattaa säilyttää image-tiedosto, koska siitä voi käyttää pohjana myöhemmin harjoituksessa [GT2](https://github.com/JAMK-IT/IIO123000-testing-course/tree/master/GT2). 


Mitä pitää tehdä:

* Ryhmä tekee päätöksen minne kone asennetaan. (Ehdotus Digital Ocean/Amazon github packin voimalla) 
* Ryhmä asentaa Testlink 1.9.14 (source forgesta) työkalun pyörimään omalle virtuaalikoneelle (valinnan mukaan)
* Tämän instanssin avulla on tarkoitus sotkea rauhassa ja säätää
* Jokainen ryhmän jäsen siirtää ryhmän omaan testlink-instanssiin aiemmin suunniteltuja testitapauksia käyttäen Testlinkin export/import-toimintoa. testitapauksia löytyy tämän tehtävän kansiosta.

Käydään ryhmässä läpi seuraavat toiminnot:

* Uuden testitapauksen luonti tuotteelle
* Luodaan uusi "Test Suite", joka vastaa testisuunnitelmaa
* Lisätään testisuunnitelmaan uusia testitapauksia
* Määritellään testikohteen versio numero "build"
* Muokata ja tehdään uusia versioita testitapauksista 
* Tuotetaan testisuunnitelmasta word/pdf versio
* 

*HUOM! Tehtävän aikana tehdyt työvaiheet dokumentoidaan esim. wiki sivun muotoon. Tämä dokumentti pitää olla saatavilla luovutuksen yhteydessä*

Huomioita / ideoita:

Henkilökohtaisessa tehtävässä [PT1](https://github.com/JAMK-IT/IIO123000-testing-course/tree/master/PT1) tuotettuja testejä voi myös käyttää runkona ja niiden avulla tutustutaan export/import toimintoon. 


![](http://i.imgur.com/Ic7cHFi.png)




### Lähteet ja linkit

* http://testlink.org/
* http://google.com

### Tavoite:

Opiskelija tutustuu perinteiseen testaushallintaan ja tunnistaa siihen liittyviä peruskäsitteitä.
Testitapaus, testisuunnitelma, testauskierros ja raportointi


### Arviointi:

Ryhmä esittelee toimivan ratkaisun ja syntyneen dokumentaation ohjaajalle

Hyväksytty/Hylätty
