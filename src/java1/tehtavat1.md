#1. Tehtävät#

Ensimmäisen tapaamiskerran tehtävät.

##Lämmittelyt##

Tee nämä tehtävät ensin

###Kokonaislukuja###

Luo luokka, jolla on yksi metodi. Metodi osaa tulostaa kaikki kokonaisluvut 0 - 1000, joiden neliöjuuri on kokonaisluku.

###Muuttujia###

Luo tekstitiedosto (esim muuttujia.txt) ja vastaa:

Miten esittelisit (tyyppi ja nimi) muuttujat seuraavia tilanteita varten. Anna myös esimerkki miten sijoittaisit muuttujalle jonkin arvon. Vastauksen voit palauttaa Java-tiedostonakin.

+ Työmatkan pituus polkupyörällä
+ Suoritettujen opintopisteiden määrä 
+ Koko tutkinnon laajuus opintopisteissä
+ Tehtyjen demojen lukumäärä 
+ Kirjan ensimmäinen kirjain
+ Sadan metrin juoksun voittajan aika.

Arvostele seuraavat muuttujien tyypit ja nimet. Ovatko syntaktisesti oikein? Entä ovatko hyviä valintoja:

+ int mansikanKiloHinta;
+ double first,second,final;
+ char omaNimi;
+ double metriMm;
+ double tuntejaVuorokaudessa;
+ real nopeus;
+ double AuringonEtaisyys;
+ int kuukaudenKeskiLampo:
+ int kissoja,2_kanaa,kolmeKoiraa;
+ int i,j,l,I;

###Merkkijonoja###

OSA I

1. Luo luokka Merkkijono
Tutki String-luokan dokumentaatiota ja tee sen avulla seuraavat tehtävät:

2. Luo pääohjelmassa merkkijono "Aasin silta alla auringon maan taivaan pääkallon"
3. Luo metodi, joka muuttaa joka toisen kirjaimen isoksi ja ottaa sen talteen uuteen muuttujaan ja palauttaa sen metodin kutsujalle
4. Luo pääohjelmassa tarvittavat oliot ja testaa 

Pähkinä: miksi String-olioiden ankara käsittely voi aiheuttaa turhaa muistinkäyttöä?

OSA II

Lyhykäidyysessään: luo luokka, jonka metodi osaa parsia merkkijonoista erilleen kaikki välimerkillä erotetut sanat ja palauttaa ne lista-oliona.

###Toistorakenteita###

1. Tee luokka, jolla on metodi, joka osaa tulostaa parametrina annetun pituuden verran Fibonaccin lukujonoa. Tämä metodi tekee homman while-toistorakenteella
2. Tee toinen metodi, joka tekee saman tempun, mutta for-rakenteella 

##Hello World##

Muuta HelloWorld.java siten, että

1. Muuta luokka HelloWorld ei-staattiseksi
2. Luo luokalle metodi yellToWorld, joka ottaa parametrina vastaan nimen ja huutaa sen maailmalle (esim. "Hello World it's Ari here!")
3. Luo staattisessa pääohjelmassa yksi HelloWorld-olio
4. Kutsu olion yellToWorld metodia omalla nimelläsi

##Simple Graphics##

1. Luo luokalle SimpleGraphics metodit, joka osaa piirtää yhden viivan. Metodille annetaan parametrina ikkuna, johon piirretään ja viivan koordinaatit
2. Luo myös metodi, joka kutsuu edellistä viivan piirtoa ja tekee automaattisesti neliön parametreina syötettyihin koordinaatteihin
3. Luo staattisessa pääohjelmassa ikkuna
4. Luo SimpleGraphics olio ja viskaa sen avulla ikkunaan 150 kappaletta neliöitä satunnaisiin koordinaatteihin

##Olioportaat##

Voit nasauttaa koko höskän olioiksi tai käyttää vielä tässä tehtävässä staattisia aliohjelmia

###Porras ylös###

Toteuta metodi, joka piirtää portaan ylös

###Porras alas###

Toteuta metodi, joka piirtää portaan ylös

###Portaat toimimaan###

Pistä luokka Portaat toimimaan, kuten pääohjelman kommenteissa sanotaan..

Esimerkiksi piirraPortaat(window,0,0,5) syntyvä kuva on seuraavan näköinen:

```

          _ (5,5)
        _| |_
      _|     |_
     |         |

```





