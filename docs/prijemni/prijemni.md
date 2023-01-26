## Prijemni ispit za upis

ovde bi trebalo da ispišemo sve aktivnosti koje obavlja Računski centar u vezi Prijemnog ispita za upisa na osnovne akademske studije, a bilo bi dobro da to uradimo i za Upis na Master

  1.Sajt upis.fon.bg.ac.rs
1.[Prijava za probni prijemni](/doku.php?id=probni)  (Sajt probni-prijemni.fon.bg.ac.rs)
1.Prijava na konkurs i Prijem dokumenatacije
1.Prijemni ispit
1.Unos testova i Bodovanje testova
1.Upis kandidata

**Web sajt prijemnog**

Računski centar hostuje i održava sajtove za UPIS na FON. Internet adresa sajta je [https://upis.fon.bg.ac.rs](https://upis.fon.bg.ac.rs) .

Aplikacije je podignuta kao WordPress multisite i sadrži ukupno *5* različitih web sajtova:

  *[https://upis.fon.bg.ac.rs/](https://upis.fon.bg.ac.rs/) - Sajt sa informacijama o fakultetu i linkovima ka sajtovima za različite nivoe studija.
  *[https://upis.fon.bg.ac.rs/oas/](https://upis.fon.bg.ac.rs/oas/) - Sajt upisa za osnovne akademske studije
  *[https://upis.fon.bg.ac.rs/sas/](https://upis.fon.bg.ac.rs/sas/) - Sajt upisa za specijalističke akademske studije
  *[https://upis.fon.bg.ac.rs/mas/](https://upis.fon.bg.ac.rs/mas/) - Sajt upisa za master akademske studije
  *[https://upis.fon.bg.ac.rs/das/](https://upis.fon.bg.ac.rs/das/) - Sajt upisa za doktorske akademske studije

Osnovne karakteristike servera:

  *Operativni sistem: Ubuntu 16.04.
  *CPU: 2 core
  *RAM: 4 GB
  *Storage: 40 GB
  *Adresa VM: 10.10.10.88
  *Adrese na LB: 147.91.134.81, 10.10.10.85
  *Hostname: upis-wp
  *DNS name: upis.fon.bg.ac.rs
  *SSL Sertifikat ističe 15/06/2021 i definisan je na LB.

Korisnici koji imaju SSH pristup VM:

  *Goran Militarov (psy)
  *Vladimir Vujin (vujin)

Korisnici koji imaju pristup Wordpress portalu:
| ID | usename    | displayName                  | userEmail                         | userRegistered     
| 24 | aleksandra | Aleksandra Vojvodić           | aleksandra.vojvodic@fon.bg.ac.rs   | 2021-03-12 10:18:31 
| 12 | dragana    | Факултет организационих наука | dragana.ivanovic@fon.bg.ac.rs      | 2019-06-05 13:03:03 
| 20 | ivan       | ivan                          | ivan.aleksic@fon.bg.ac.rs          | 2019-10-11 19:40:34 
| 16 | okanovic   | okanovic                      | milan.okanovic@fon.bg.ac.rs        | 2019-08-02 12:19:59 
| 4  | psy        | Факултет организационих наука | goran.militarov@fon.bg.ac.rs       | 2019-06-04 21:40:10 

Pristup administratorskom panelu je dozvoljen sa sledećih adresa:

  *10.10.70.208
  *10.10.10.253
  *10.91.254.0/24
  *10.91.90.0/24
  *192.168.168.0/24
  *10.91.34.0/24

**Ovde opisati gde se i kako hostuje i kako se održava sajt i ko je zadužen za ažuriranje sadržaja**

**Prijava na konkurs**

Za potrebe evidencije i prijema dokumentacije kandidata formira se nekoliko komisija. Za svaku komisiju Računski centar treba da obezbedi računar, štampač… kao i da omogući bezbednu konekciju računara sa bazom…

Uobičajeno je da se komisije rasporedjuju po učionicama 104, 105,…

Šta je potrebno instalirati na računarima za komisije, koji štampač i kako ga povezati.

Na koji nacin komisije pristupaju bazi za unos da li preko browser-a ili preko neke aplikacije

Šta je potrebno uraditi da se računarska mreža za upis izoluje od ostatka fakulteta.

Da li se od kandidata prikupljaju informacije o broju mobilnog telefona i mail adrese za potrebe komunikacije sa kandidatom? Da li je potrebna saglasnost kandidata da te informacije koristimo samo za komunikaciju? 

**Prijemni ispit**
Ko kaci informacije za prijemni

Da li se informacije za upis i prijemni objavljuju samo na sajtu upisa ili i na sajtu fakulteta kao prethodnih godina

SMS servis, ko salje, kada se salju(da li za sve liste, da li polaganje prijemnog, broj ostvarenih bodova, preliminarne liste…)

Gde matematicari stampaju testove(bilo je u C401), koliko stampaca im treba, treba li im racunar ili laptop ili to rade sa njihovih.

**Unos testova**

Za unos testova kandidata koristi se Markov program, koji se zasniva na skeniranju a zatim prepoznavanju datih odgovora kandidata.

Da li je potrebno pripremiti server na kojem će se izvršavati program za prepoznavanje? Koje su karakteristike servera (jednog ili vise) potrebne? Potreban je detaljan opis okruzenja koje treba pripremiti

Da li se skeneranje vrsi u C401 zbog pripreme mreze. Verovatno trebaju da budu na istom Vlanu gde i aplikacija tj baza

Za potrebe skeniranja potrebno je pripremiti jedan ili više (u zavisnosti od broja komisija za skeniranje) računara, skenera i štampača. 

**Upis kandidata**

Za potrebe upisa kandidata formira se nekoliko komisija. Za svaku komisiju Računski centar treba da obezbedi računar, štampač… kao i da omogući bezbednu konekciju računara sa bazom…

Uobičajeno je da se komisije rasporedjuju po učionicama 104, 105,…

Šta je potrebno instalirati na računarima za komisije, koji štampač i kako ga povezati.

Šta je potrebno uraditi da se računarska mreža za upis izoluje od ostatka fakulteta.

