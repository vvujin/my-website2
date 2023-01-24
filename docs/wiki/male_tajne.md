# Male tajne

## Update firmware-a na HP masinama

Firmware koji se downloduje sa HP sajta ima eksteniziju scexe, predstavlja self ekstrakt i automatik start setup

	./CP023884.scexe --unpack=/tmp
Ako je firmware za 32 bitni linux onda je potrebno uraditi sledece da bi mogao da se uradi update
Ovakva greska se javlja kada se startuje xxx.scexe na 64bit linuxu

	root@it:/home/it/Desktop# ./CP023884.scexe
	
	./CP023884.scexe: 153: ./CP023884.scexe: ./CP023884.scexe: 158: ./CP023884.scexe: popd: not found
	
	pushd: not found
	
	./hpsetup: 2: ./hpsetup: ./ccissflash: not found
1. ako je ubuntu  potrebno je instalirati 32bit dependencies

	dpkg --add-architecture i386
	
	apt-get update
	
	apt-get install libstdc++6:i386
	
	
## PuTTY sessions sa Vujinovog kompa

Skinuti fajl 

Otpakovati fajl a zatim duplim klikom na otpakovani fajl ubaciti u lokalni registry.

Pokrenuti putty

## Fizički Serveri

Na Avala-02 fizičkom serveru javlja se greška na Hyper-V-Worker Servisu, EventID=18560

15.10.2018
Server je stavljen u Maintance Mode, restartovan i u BIOS-u HP Power Profile je postavljen na Maximum Performance

![Ilo](/img/eventid18560.png)


Napomena:
pratiti da li je ovim uspelo da se otkloni greska

## windows

U Group policy u polisu wsusWin2016 koja se odnosi na podešavanje windows update-a za servere sa win2016,
ubačeno je podešavanje koje disebluje MapsBroker service.

