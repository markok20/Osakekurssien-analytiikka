# osakekurssit
Osakekurssien aikasarjoja ja vertailua
Case-esimerkki aikasarja-analyysistä: osakekurssien historiavertailu

Osakekurssit tarjoavat hyvän aineiston aikasarja-analyysille, jonka avulla voidaan tehdä päätelmiä aikasarjan taustalla olevista mahdollisista satunnaisprosesseista. Mallin perusteella voidaan tehdä menneiden havaintojen avulla ennusteita jopa tulevista arvoista. Tyypillinen sovellus aikasarja-analyysista on osakkeen avauskurssin ennustaminen kurssin historialla.

Miten ja kuinka aikasarjoja voidaan kuvailla analytiikalla? Käytettävissäni oli data, joka alkoi tammikuun 2015 alusta joulukuuhun 2020 saakka. Aineisto sisälsi 1506 pörssipäivän tiedot. Keskityin kahteen teleoperaattoriin Teliaan ja Elisaan.

Kummankin yhtiön päätöskurssit näkyvät alla kahden arvoakselin viiva-asteikossa viimeisen viiden vuoden ajalta.

Seuraavaksi tarkastelin liukuvia keskiarvoja, joilla tasoitetaan yksittäisiin ajankohtiin liittyviä satunnaisia piikkejä. Teknisessä analyysissä aikasarjan ja liukuvien keskiarvojen leikkauskohtia käytetään osto- ja myyntisignaaleina. Katsotaan esimerkiksi Elisan päätöskurssin kehitystä vuosina 2015-2020 ja lisätään kuvioon 200 päivän liukuva keskiarvo.

Seuraavaksi tarkastelin miten osakkeiden muutosprosentit edellispäivästä ovat seuranneet toisiaan vuoden 2020 aikana.

Korreloivatko Telian ja Elisan kurssikäyrät toisiaan? Teleoperaattoreiden muutosprosentit korreloivat positiivisesti. Muutosprosenttien positiivinen korrelaatio näkyy hyvin hajontakaaviossa.

Liukuva korrelaatio kertoo miten muutosprosentit korreloivat eri aikoina.

Seuraavaksi tarkastelin volaliteettia, joka kuvaa osakkeeseen liittyvää riskiä. Tavallisimmin luku lasketaan päivätuottojen keskihajonnasta ja ilmoitetaan prosentteina vuodessa. Laskin volatiliteetin päivittäisten muutosprosenttien keskihajontana ja skaalasin sen vuositasolle kertomalla vuoden kaupantekopäivien lukumäärän neliöjuurella. Liukuva volatiliteetti kuvaa, miten se on muuttunut ajan kuluessa.

Lyhyesti kiteytettynä: aikasarja on havaintoyksiköstä tehtyjen mittausten muodostama aineisto. Havainnot ovat tavallisesti peräkkäisiä, ja mittaukset on tehty tasaisin aikavälein. Moniulotteinen aikasarja-aineisto koostuu usean havaintoyksikön mittauksista, jotka on yleensä tehty samoina ajankohtina. Aikasarja-aineiston edellytys on se, että se voi olla jatkuvaa tai diskreettiä.

Aikasarjojen perusteella voidaan tehdä menneiden havaintojen avulla ennusteita tulevista arvoista.
