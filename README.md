# tilannekuva
Tietokannat ja web-ohjelmointi -kurssin harjoitustyö
## Sovelluksen tarkoitus
Sovelluksen tarkoituksena on luoda ympäristö henkilöiden ja porukoiden ryhmätöiden tai projektien tilannekuvien hallintaan. Käytännössä sovellukseen luodaan projekteja, jotka koostuvat aliprojekteista tai panoksista. Yksiköiden vaativa työpanos määritellään tapauskohtaisesti. Hyötynä sovelluksella saadaan dashboard-tyyppinen näkymä työstä, deadlineista ja eri käyttäjien panoksista.

## Sovelluksen toiminta
### Perustoiminta
Sovelluksen käytön perusflow on seuraava:
* Omistaja luo projektin, määrittelee sen sisältämät panokset, aliprojektit ja aikataulut
* Käyttäjät päivittävät panosten täyttymistä
* Käyttäjille näkyy avointen projektien tekemättömät panokset roolikohtaisesti
* Projektin valmistuttua se siirtyy käyttäjille valmiisiin projekteihin

### Roolit
Sovelluksessa on kolmen luokan käyttäjiä:
* Ylläpitäjä pystyy muokkaamaan kaikkia projekteja
* Omistaja omistaa luomansa projektin, ja pystyy hallinnoimaan siihen liittyviä käyttäjien panoksia
* Osallistuja pystyy syöttämään ja muokkaamaan hänelle sallittuja osakokonaisuuksia, sekä näkemään hänelle luvitetut projektit
