Vmesno poročilo


Podatki:

Za pridobivanje podatkov smo uporabili spletne strani, ki so namenjene za hranjenje statistik in informacij. Glavna stran, ki smo jo uporabili je bila Eurostat, s kjer smo pridobili 9 CVS datotek in Worldeconomics kjer smo pridobili še eno.

Pridobljeni podatki so indesk enakovrednosti med spoloma, Tedenske delovne ure, infacija, brezposelnost, migracije, emigracije, najnižja postavka, delovne ure, BDP in procent oseb ki obupajo nad šolanjem.

Podatki so večinoma ločeni na države in leta, ko so bile mere opravljene. Mere se delijo na povprečje, procentualno na populacijo in samo prešteti elementi (npr. število oseb).
 

Problemi:

Prvi problemi na katere smo naleteli, so bili te, da nekatere države niso imele vrednosti, pri čemer smo morali zamenjati vse »neveljavne« vrednosti z številom 0.  

Drugi problemi, ki so se pojavili so bili te, da so bile v podatkih države, ki niso iz EU. Ker smo se odločili delati poizvedbe samo za EU smo morali pregledati vse datoteke in odstraniti neveljavne države.

Tretji in največji problem ki se pojavlja pa je, da nimajo vse datoteke iste letnice, kar postavi problem, da ne bo možno ustvariti povezave med določenimi elementi, kar pomeni, da ne bo možno prikazati določenih povezav med podatki. To se lahko popravi tako, da naredimo »navidezne« podatke (predvidevamo kakšni bi bili za manjkajoča leta) od prejšnjih naborov in jih uporabimo, čeprav ne bo pravilno ali natančno.


Glavne ugotovitve:

Veliko podatkov ni dopolnjenih, čeprav je vir podatkov kredibilna spletna stran namenjena za hranjenje in zbiranje teh podatkov. 

Urejanje podatkov je bilo tudi precej časovno potratno, saj je bilo treba ročno določiti dovoljene države in nato urediti vsako datoteko posebej in izbrisati nepotrebne vrstice in tudi urejanje neveljavnih elementov in jih spreminjati na 0.

Izvedene analize:

Analize, ki smo jih do sedaj izvedli so bile samo čiščenje/odstranjevanje nepotrebnih podatkov in urejanje neveljavnih oziroma manjkajočih podatkov. Poleg tega smo tudi združili nekatere stolpce, ki so bili razdeljeni na več delov (2022/1, 2022/2).
 
Najzanimivejši rezultati:
	Rezultati, ki smo jih vizualizirali so vsi precej zanimivi vendar naj-zanimivejši so naslednji:
-	Slovenija ima največji indeks enakovrednosti med spoloma, ki je skoraj 100%

 ![slika](https://github.com/DerpStepo/PR24BKRMKPMSJSV/assets/104684069/f123ba27-60a3-4f28-8a36-192c5be6a20b)

-	Največ emigracij se dogaja v Nemčiji in Španiji
-	Luxemburg ima največji BDP izmed evropskih držav in za precej veliko.

 ![slika](https://github.com/DerpStepo/PR24BKRMKPMSJSV/assets/104684069/528180ad-8fbb-4287-bae3-20ba95055962)

-	Inflacije so bile največje v letu 2022, v nekaterih državah tudi 5x več kor predhodnje leto.

 ![slika](https://github.com/DerpStepo/PR24BKRMKPMSJSV/assets/104684069/6311b74d-1401-4935-bdd4-e8d2d4fe50ae)

-	Skoraj vse države imajo približno isto delovnih ur na teden
 
![slika](https://github.com/DerpStepo/PR24BKRMKPMSJSV/assets/104684069/e1612d73-c252-4a30-b3d1-bfe66d059476)
