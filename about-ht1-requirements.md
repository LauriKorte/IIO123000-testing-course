# Tarkista seuraavat!

Käykää ryhmissä läpi alla oleva palaute ja tehkää tarvittaessa korjauksia HT1-palautukseenne! Tämä koskee aika monia teistä! Palauttakaa korjattu versio HT1-palautuslaatikoon! HUOM! tuo alkuperäinen henkilökohtainen palautuskansio ei ole enää käytössä. Siinä ei voi antaa kommentteja!! 
MEIKSIN MOKA! TV:Narsu


*Lisäsin esimerkin testisuunnitelmasta PDF-muodossa tämä sivun loppuun. Tutkikaa sitä!*


# Huomioita liittyen HT1 palautuksiin!


  * Selkeyttäkää tuottaamanne testaussuunnitelmaa! Nyt useissa  on aika paljon epämääräistä "saissea" mukana :) 
  * Lukekaa tarvittaessa ristiin tekemiänne testitapauksia? Ymmärtääkö kaveri mitä pitää tehdä?
  * Poistakaa turhat "roska"-otsikot. esim. Testlink-roska dokumentin alussa on turhaa.
  * Tuotetun sivun voi editoida kuntoon Wordilla. (Testitapaukset voi aina exportoida myöhemmin uudestaan) 
  * Tee siistitty etulehti ja lyhyt johdatus aiheeseen (Osa on hoitanut tämän jo hyvin!)
  * Koko alkuosan voi kirjoittaa esim. Wordilla ja sitten lisätä loppuun testitapaus kokoelman

Testeistä!

  * Tarkistakaa vielä kerran mitä testissänne yritätte tehdä? Osassa testeistä ei ollu oikein selkeää tavoitetta!
  * Käyttäkää apuna testlinkin "step" kenttiä! Älkää turhaan yrittäkö pistää niitä askelia kuvauskenttään!
  * Testeissä kannattaa huomioida muitakin asioita, kuin pelkästään perustoiminnallisuus (ks. alla).
  * Jos määrittelet toiminnallisen testin, niin kirjaa sen osaksi hyviä tarkistuskohteita. 
  * Tee aina tarvittaessa uusia testejä!
  * Testissä voidaan käyttää apuvälineitä esim. BUG-MAGNET työkalu Chromelle.   
  * Kirjaa testin osaksi esim. tarkistuslista, joihin kannattaa kiinnittää huomiota testin aikana

Alla olevassa Contriboard-testisuunnitelma esimerkissä on "hyviäkin" -testitapauksia tutkikaa sieltä esimerkkejä!


##Testitapauksen laajentaminen Esim. 

###Äkkiseltään helpon kuuloinen testi: 

  * TESTI: Testaa toimiiko palvelusta uloskirjatuminen, eli logout?
  * Step 1 Paina "logout"-nappulaa    
  * Step 2 Tarkista että ruudulla näkyy "Bye Bye"-viesti
  * KRITEERI: PASS "Bye Bye"-viesti näkyy, Muuten FAIL

###Tähän voisi lisätä muutaman lisätarkistuksen.... 

  * Mitä jos käyttäjä on kirjatunut usealla clientillä ja painaa logout yhdessä niistä ?
  * Mitä tapahtuu, jos verkkoyhteys katkeaa (tai muodostetaan uudestaan) ennen logout tilannetta
  * Jos painaa "back" jatkuuko istunto?

### Tuloksena voi olla testit

  * TESTI: Testaa toimiiko palvelu uloskirjatuminen, eli logout?
  * Step 1 Paina logout nappulaa
  * Step 2 Tarkista että ruudulla näkyy "Bye Bye"-viesti    
  * HUOMIOI: Kirjautuminen tapahtunut samaan aikaan useammalla clientillä. Tarkista myös huonon verkon vaihdon jälkeen (WLAN->3G)

  * KRITEERI: "Bye Bye"-viesti näkyy -> PASS, Muuten FAIL

### Määritellään lisäksi myös uusi testi

  * TESTI: Testaa toimiiko palvelu vielä uloskirjatumisenkin jälkeen
  * Step 1 Paina logout
  * Step 2 Paina Back
  * Step 3 Kokeile avata "kauppanäkymä"
  * HUOMIOI: Tarkasta sama useammalla clientillä
  * KRITEERI: PASS -> jos käyttäjä joutuu login ikkunaan, Muuten FAIL


Eli miettikää laajemmin mitä testataan!!! ja tehkää tarvittaessa uusia testitapauksia...

### Toinen Testiesimerkki:

  * TESTI: "Tarkista löytyvätkö kaupat lähialueelta painamalla "etsi lähikauppa"-nappulaa"
  Step 1: Avaa kauppakartta
  Step 1: Paina karttapohjalla näkyvää "hae lähikauppa"-nappulaa ja katso, että kaupat löytyvät"

### Voisi olla aiheellista tehdä tarkistuksia esim. seuraavista asioista?

  * Mitkä kaupat pitäisi ehkä löytää? Mikä on hyväksytty tulos ?
  * Mitä tapahtuu jos GPS / sijaintitieto ei ole käytössä?
  * Mitä tapahtuu jos GPS kytketään vahingossa pois/päälle haun aikana
  * Mitä tapahtuu jos GPS ei saa sijaintitietoa 


# MASTER TEST PLAN JA TESTISUUNNITELMA 

Tein esimerkin, jota mukaellen HT1-palautus pitäsi olla aika kuosissa.

[TÄSSÄ Contriboard-palvelun yleisuunnitelma + testit yhdessä PDF:ssä](https://drive.google.com/folderview?id=0B-hPgXTXfK9EQXNfQ1NhSTRUcTg&usp=sharing)

  * GitHub wiki-muotoinen Master Test Plan löytyy täältä:  https://github.com/N4SJAMK/teamboard-meta/wiki/master-test-plan

  * Testlinkistä voi exportoida testisuunnitelman HTML-muodossa täältä http://stc2015.n4sjamk.org/testlink/lnl.php?apikey=e60c2bff79c49f08d87f617b45708c4c54ab4988d8c32d5eaeb009694c1d86e3&tproject_id=9725&tplan_id=10363&type=test_plan

Projekti voi löytyy [testlinkistä:](http://stc2015.n4sjamk.org/testlink) nimellä "DMT:Demo MPT and Tests"



