###  Testausjärjestelmän asentaminen ja käyttöönotto

Ryhmä 

Tarvittavat komponentit:

  * Testlink 1.9.x
  * JIRA 6.x 
  * Ubuntu 14.04 server

Ratkaistava ongelma:

Tutustukaa tehtävän lopussa oleviin kuvauksiin Contriboard -palvelun palaute/vianhallintaketjusta (Feedback & error management process). Ohjaaja antaa lisätietoja tarvittaessa. Tutustukaa JIRA -työkaluun ja miettikää miten sen avulla voisi kehittää em. prosessia. Kuvitelkaa, että Contriboard kehityksessä on > 15 henkilöä. Eli vianhallinnalle on todellinen tarve. 

  * Käyttäjäpalaute
  * Contriboard -yhteisön tekemät vikaraportit 
  * Tuotekehitystiimin sisäiset vikaraportit

Tarkastelukohteita, joihin on tehtävän palautuksessa kyettävä vastaamaan:

  * Mitä ongelmia huomaatte nykyisessä GitHub -mallissa?
  * Mitä aiemmin käytettyjä palveluita voidaan poistaa ?
  * Miten voidaan hoitaa toisin asiakaspalautteen kerääminen (Voidaanko esim. User Voice korvata?)
  * Miten komponentti kohtainen vianhallinta muuttuu ? (Contriboard -palvelu koostuu useammasta palvelukomponentista, kuten api,io,client ja db)
  * Miten voimme yksinkertaistaa vianhallintaa käyttäen JIRA:a ?
  * Jos vikaraportti tulee käyttäjäpalauteen muodossa (User Voice), niin miten vianhallinnan avuulla ohjataan korjaus oikeaan komponenttiin ? Miten tämä käytännössä onnistuu?
  * JIRA Agile & Kanban taulun hyödyntäminen ?
  * Tee JIRAan raportti, jolla voidaan osoittaa helposti vikaantunein komponentti ? 

Oletuksia:

  * Jokaisella komponentilla on oma vastuullinen kehittäjänsä. 
  * Kehitysryhmä soveltaa ketterää kehitystä (Kanban) työn organisoinnissa
  * Hyväksyntätestausryhmä (Acceptance Testing) on opiskelija joukko, jotka käyttävät Testlink -työvälinettä oman työnsä apuna.  
  * Yksittäisen vikaraportin (issue) ei tarvitse linkittyä kooditasolle asti! Tavoite on siis ymmärtää miten JIRA voisi soveltaa vianhallinnassa.


Mitä pitää tehdä?

Ryhmä asentaa JIRA 6.x vikakannan ja Testlink 1.9.x testaushallintatyökalun ryhmän EWOK-palvelimelle
JIRA -työkalun lisenssinä käytetään 1kk evaluaatiolisenssiä. 

  * https://www.atlassian.com/software/jira 
  * https://www.atlassian.com/pt/software/jira/download?b=j 
  * Testlink kantaan tuodaan (Import-toiminto) aiemmin suunnitellut testitapaukset [XML tiedosto löytyy täältä](https://drive.google.com/file/d/0B-hPgXTXfK9ER3NlMFV5aENzaGM/view?usp=sharing). 
  * Testlink integroidaan JIRAn kanssa käyttäen TL:n "Issue Tracker Integration"-toimintoa. JIRAan pitää aktivoida tätä ennen "SOAP/API"-integraatiorajapinta
  * Testlink "Issue Tracker Integration"-ominaisuus tarvitsee XML-muotoisen konfiguraatiotiedoston: [Esimerkki configuraatio löytyy täältä]()



### Nykyinen vianhallintaketju


Asiakkaan palaute ja sen siirtäminen github issueksi

![]( https://www.lucidchart.com/publicSegments/view/54e1eca2-5418-4b3e-a447-03930a009737/image.png)
Tutkikaa näiden pohjalta miten Contriboard-tuotteen github issuet on hallittu.

Issuen kohdistaminen eri komponenteille (Repository)

![](https://www.lucidchart.com/publicSegments/view/54e46062-6640-4973-a19e-350e0a00d44e/image.png)

Kuten ehkä huomataan github ei taivu helposti laajemman tuotteen vianhallintaan. Tuotteen koostuessa useista komponenteista ei vianhallintaprosessin pyörittäminen ole yksinkertaista. Tässä [arkkitehtuuri-kuvaus, josta löytyvät tärkeimmät Contriboard-komponentit](https://github.com/N4SJAMK/teamboard-meta/wiki/about-architecture)



## Palautettava tulos:

  * JIRA instanssi esitellään virtuaalikoneena. JIRAan on luotu Contriboard tuotteelle vianhallinta ratkaisu  
  * Vikakantaan on syötetty esimerkejä vikaraporteista, joita on siirretty eri komponenttien välillä.  
  * Uusi vianhallintaprosessi (Workflow) on dokumentoitu kuva muotoon
  * Ryhmä esittelee asennetut ohjelmistot toimivana kokonaisuutena 
  * Ryhmä kykenee osoittamaan tehdyt muutokset 

## Palautustilanne: Tuotos tarkistetaan tunnilla

Arviointi: Hyväksytty / Hylätty
