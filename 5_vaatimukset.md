## Vaatimukset 

* Kuvaile tänne funktionaaliset ja ei-funktionaaliset vaatimukset
* Funktionaaliset vaatimukset
1. Kävijämäärät saadaan ruokalan WLAN tukipisteen keräämien sijaintitietojen perusteella
1. Kävijämäärien tulee päivittyä etusivulle 30 sek välein
2. Kävijämäärädiagrammi tunneittain päivittyy tunnin välein
3. Kävijämäärädiagrammi 5vrk ajalta päivittyy vuorokauden vaihtuessa
4. Kävijämäärät tunneittain ilmaistaan viivadiagrammin avulla
5. Kävijämäärät 5 vrk ajalta ilmaistaan palkkidiagrammilla
6. UniCafen ruokalistojen tulee päivittyä viikoittain tai heti muutosten ilmetessä
7. Sovelluksen päivitykset näkyvät ilmoituksena käyttäjälle
8. Ilmoitukset voi ottaa pois käytöstä Asetukset -välilehdestä rastittamalla pois Näytä ilmoitukset
9. Kielen voi muuttaa Asetukset -välilehden kohdasta language, valintoina suomi tai englanti
10. Etusivulla näkyvä still-kuva muuttuu tämän hetkisten kävijöiden mukaan.
Kun Kävijöitä nyt -luku on 30 tai vähemmän, etusivun kuva on tyhjästä ruokalasta
Kun Kävijöitä nyt -luku on 31-70, etusivun kuva on ruokalasta, joka on puolillaan ihmisiä
Kun Kävijöitä nyt -luku 71 tai enemmän, etusivun kuva on ruuhkaisesta ruokalasta.
Kävijät nyt- ja Kävijämäärä tänään -luvut ilmoitetaan kokonaislukuina
Ruokalistan ruokia pystyy arvostelemaan tähdin (1-5) sekä antamalla kommentin (korkeintaan 160 merkkiä pitkä)
Tähtiarvostelujen keskiarvo ja arvostelujen lukumäärä näkyvät ruokalistassa ruokalajin alla.
Ruokalajin alla, tähtiarvostelujen jälkeen on Kommentit-linkki, jota klikkaamalla saa näkyviin käyttäjien tekemät kommentit
Käyttäjä voi arvostella ja kommentoida vain sen hetkisen päivän ruokia sekä jättää vain yhden kommentin/arvostelun per ruokalaji.
Käyttäjä voi lisätä oman tähtiarvostelun ja kommentin painamalla Arvostele- nappia ruokalistan ruokalajin vierestä.
Käyttäjä lisää haluamalleen ruualle tähdet (1-5) viidestä tähden kuvasta jotka muuttuvat valittuina keltaisiksi ja käyttäjä voi halutessaan lisätä lyhyen kommentin (kork. 160 merkkiä) ruuasta kommentti laatikkoon
Kommentit ja arvostelut päivittyvät 60 sekunnin välein
Kävijähistoriaa pystyy selamaan Kävijähistoria-välilehden pudotusvalikosta valitsemalla haluamansa päivämäärän, jolloin diagrammit vaihtuvat kyseisen päivän diagrammeiksi
Kävijähistoriaa pystyy selaamaan kuusi kuukautta taaksepäin selaushetkestä
Painettaessa Palaa-nappia käyttäjä pääsee aina etusivulle
Ladatessaan sovelluksen, käyttäjä syöttää ensimmäiseksi haluamansa nimimerkin (maksimipituus 15 merkkiä, vain kirjaimet ja numerot sallittu) Nimimerkki-kenttään
Nimimerkki näkyy käyttäjän tekemissä kommenteissa
Nimimerkin voi vaihtaa niin montaa kertaa kuin käyttäjä haluaa Asetukset-välilehden kohdasta “Vaihda nimimerkki”
Käyttäjän arvostelut näkyvät ainoastaan sen kampuksen käyttäjille jossa kommentoija kommentointihetkellä on
Sovelluksen tulee tunnistaa WiFi signaalin avulla millä kampuksella käyttäjä sillä hetkellä on ja antaa kyseisen kampuksen ruokalatiedot
Käyttäjän ollessa kampuksen ulkopuolella, hän voi valita minkä kampuksen tietoja haluaa tarkastella yläreunan valitse kampus linkistä, jolloin tulee pudotusvalikko kaikista kampuksista
Käyttäjän ollessa kampuksella, yläreunassa lukee kampuksen nimi, ja tätä painamalla pääsee valitsemaan muitakin kampuksia tarkasteltaviksi
Nimimerkin asettamisen jälkeen sovellus kysyy käyttäjältä haluaako hän siirtyä ohjeet -sivulle vai suoraan käyttämään sovellusta
Käyttäjä voi sulkea sovelluksen painamalla Sulje -nappia
Sovelluksen kaatuessa se lähettää ilmoituksen ylläpitoon
Ei-funktionaaliset-vaatimukset:
Sovellusta tulee pystyä käyttämään yhtäaikaa 17 000 käyttäjää
Sovelluksen tulee toimia Android-, Windows-, sekä iOS -käyttöjärjestelmillä
Sovellus ei kerää muuta tietoa käyttäjästä kuin sijainnin, sekä nimimerkin ja mahdolliset kommenttit, sekä arvostelut
odotusaika linkkien latautumiselle saa olla korkeintaan 1 sekuntti
Sovellusta käytetään mobiililaitteella joten jokaiseen linkkiin riittää yksi kosketus aktivoimaan linkki
Kännyköille oma versio käyttöliittymästä
Tableteille oma versio käyttöliittymästä
Samalla kampuksella voi yhtäaikaa kommentoida ja arvostella 100 käyttäjää
Käyttäjän tulisi oppia sovelluksen käyttö 10 minuutissa
Sovelluksen pystyy lataamaan ilmaiseksi Google Play-, Marketplace-, Windows Kauppa- ja App Store-sovelluskaupoista
Sovelluksen käynnistämiseen kuluva aika saa olla korkeintaan 3 sekuntia
Sovelluksen kaatuessa, sovellus käynnistää itsensä uudelleen 5 sekunnin kuluessa
Toimintavarmuus tulee olla vähintään 90%
Sovellus jää toimimaan laitteen taustatehtäviin, jos sitä ei erikseen suljeta
  * Tarkentavat käyttötapauksia
* Ei-funktionaaliset vaatimukset
  * Esim käytettävyyteen, tietoturvaan, tehokkuuteen, skaalautuvuuteen, hintaan ja prosessimalliin liittyvät vaatimukset
* **Muista esittää vaatimukset jäljitettävässä muodossa, yksiselitteisesti**
* Keskeinen tapa (erityisesti ei-funktionaalisiin vaatimuksiin) yksiselitteisille kuvauksille on vaatimusten **mitattavuus** (software metrics)
