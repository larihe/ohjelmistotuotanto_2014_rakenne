## Käyttötapaukset


 - Järjestelmän loppukäyttäjiä on pääsääntöisesti oppilaat, mutta lisäksi myös henkilökunta ja vierailijat.

 ![käyttötapauskaavio](http://users.metropolia.fi/~ilkkapel/Ojl/UseCase%20Diagram022.jpg)
   - Initial state: Käyttäjä painaa Start searching
   - Normal flow: Napin painamisen jälkeen järjestelmä paikantaa itsensä
   - End state: Käyttäjä näkee, missä kohtaa on koulua ja näkee läheiset tilat
  - Normaalikulku voi häiriintyä muutamilla puhelinmalleilla, joissa on vanhempi WLAN-tekniikka joka ei tue paikallisia signaaleja
  - Normaali kulku voi mennä pieleen, kun järjestelmä ei löydäkkään kohdetta.
  - Vaihtoehtoinen kulku on esimerkiksi tilanne, kun paikannus löytää oikean luokan, mutta ei näytä luokkatunnusta.
