## Harjoitus:  Testaushallinan ja vikatietokannan integraatio

### Tehtäväkuvaus:

#1

Ryhmätyön tavoitteena ottaa oletuksena käyttöön [JIRA-Cloud](https://www.atlassian.com/try)-palvelu, jota käytetään harjoituksen aikana vikatietokantana (Defect Database).  JIRA Could-palvelu integroidaan kiinni ryhmän omaan Testlink-työkaluun. Tämä tapahtuu käyttäen apun ko. palvelun rajapintaa. 

Ryhmät voivat kokeilla omaa palvelua "Trial"-moodissa tai käyttää kurssin aikana toimivaa palvelua osoitteessa: https://iio123000.atlassian.net/ Tunnukset saa ohjaajalta

Tärkeää integraatiosta:

* Testlink palvelimella pitää olla asennettuna php5-curl kirjasto! Muuten REST rajapinta ei toimi!
* Itse järjestelmä JIRAN ja Testlink-ohjelmiston välillä luodaan Testlinkin "Issue Tracker Management"-ominaisuuden avulla. Tänä ominaisuuden avulla liitetään vikaraportointi "saumattomaksi" osaksi testiraportointia. 

[Youtube tehtäväanto](https://www.youtube.com/watch?v=XX1oiuCnehY)


![](http://i.imgur.com/6aFA684.png)


HUOM! Tehtävän aikana tehdyt työvaiheet dokumentoidaan esim. wiki sivun muotoon. Tämä dokumentti pitää olla saatavilla luovutuksen yhteydessä

* [Miksi jira?](https://www.atlassian.com/gartner)

### Vianhallintaprosessi ymmärtäminen

*JIRAn vianhallintaprosessi*

![](https://confluence.atlassian.com/jira060/files/370705000/370508797/1/1336008107402/system-workflow.png)

*BUGZILLANn vianhallintaprosessi*

¡[](https://www.bugzilla.org/docs/4.0/en/images/bzLifecycle.png)


### Lähteet ja linkit

* [JIRA-ohjeet Guru99](http://www.guru99.com/jira-tutorial-a-complete-guide-for-beginners.html)
* http://testlink.org/
* Kannattaa kokeilla myös http://Bugzilla.org ja http://Mantis.org
* [http://Jira ](https://www.atlassian.com/software/jira)
* [Muut vaihtoehdot integraatioille](https://github.com/TestLinkOpenSourceTRMS/testlink-code/tree/testlink_1_9/lib/issuetrackerintegration)


### Tavoite:

Testlink-työkalu on integroitu yhteen ryhmän valitseman vikatietokannan kanssa
Opiskelija ymmärtää mitä tarkoitetaan jäljitettävyydellä (Traceability) suoritetun testitapauksen ja vikaraportin välillä


### Arviointi:

Ryhmä valmistautuu ajamaan seuraavaan hyväksyntätestin:

-Uusien käyttäjien luominen JIRAan
-Projektin luominen
-Komponenttien luominen
-Issue-import (vanhasta projektista)
-Issuen jakaminen eri tiimin jäsenille (Assign)
-Käytetyn Work flow esittely ja sen läpikäynti (Work Flow)
-Testitapauksien ja JIRA issuen linkittäminen 


Ratkaisu esitellään opettajalle  

Hyväksytty/Hylätty
