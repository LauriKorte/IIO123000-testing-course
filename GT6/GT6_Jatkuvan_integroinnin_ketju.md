### Harjoitus: Continuous Integration using Jenkins and XUnit framework

Viime viikolla tehtiin yksinkertaiset yksikkötestit Basket-sovellukseen pythonilla.
Tällä kertaa haluamme pystyttää Jenkins build-serverin palvelimellemme, joka hakee uusimmat muutokset gitistä suorittaen testit ja tekee buildin.

### Tehtäväkuvaus:

Ryhmä asentaa CI ympäristön käyttäen GitHubia ja Jenkinsiä

Jenkins palvelin pystytetään JAMK:in labranet koneelle. Jenkins palvelimeen luodaan "jobi" jotka osaa noutaa koodin Github-repositoriosta tietyin väliajoin, ajaa testit ja jos ne menee läpi niin suorittaa buildin. Jenkins asennetaan ryhmän kesken ja jokainen ryhmä luo sinne oman jobinsa.

Tehtävä tehdään ryhmäkohtaisesti ryhmän omalle palvelimelle. Kaikkien tulee ymmärtää kuinka Jenkins toimii.


### Lähteet ja linkit

* [Pieni ohjedokkari](https://github.com/JAMK-IT/IIO123000-testing-course/wiki/GT6-ohjedokkari)
* https://jenkins.io/
* http://nose.readthedocs.io/en/latest/


### Tavoite:

* Oppia Jenkinsin (tai vastaavan build serverin) merkitys ja käyttö
* Saada tehtyä jobi joka:
 * Hakee koodin automaattisesti gitistä jollakin aikavälillä
 * Ajaa läpi yksikkötestit, generoi xunit-mallisen testituloksen ja käsittelee sen
* Tehtävässä opitaan myös testidokumentin generointi xUnit-mallin mukaisesti, sekä asentelemaan sovelluksia palvelimelle

### Arviointi:

Ryhmä esittelee ympäristönsä ja näyttää että jobi hakee gitistä uusimman lähdekoodin, ajaa testit ja suorittaa buildin mikäli virheitä ei tule.
Arvosana on joko hyväksytty tai hylätty.

Palautustilanne: Tarkistetaan tunnilla / sähköposti
