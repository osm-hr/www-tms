# www-tms
https://tms.osm-hr.org/ web page

U web folderu su tms arhive i osnovna karta za njihov pregled.

Postojeći tms slojevi: ustopo, orbview opc

##USTOPO

Topografske karte US Defence

Postavljanje u editore: potrebno je ručno upisati TMS adresu u željeni editor.
Pomak: Karte su topografske, i pomaci znaju biti i do 50 metara., ponegdje i više. Koristiti ako nema drugih podloga.
Source tag: "source=U.S. Defense Mapping Agency"

U JOSMu
Kliknuti na Edit > Preferences... > WMS TMS > + (Plus dolje desno) > TMS
Menu name= U.S. Defense osm-hr
TMS URL= https://tms.osm-hr.org/ustopo/{zoom}/{x}/{y}.png

U Potlatchu:
Kliknuti na Background > Edit...
I napraviti novi upis:
Name= U.S. Defense osm-hr
URL= https://tms.osm-hr.org/ustopo/$z/$x/$y.png

##OrbView3

Postavljanje u editore: potrebno je ručno upisati TMS adresu u željeni editor.
Pomak: Oko 10 metara, najviše 20. Obavezno provjeriti prije korištenja.
Source tag: "source=Orbview3"

U JOSMu
Kliknuti na Edit > Preferences... > WMS TMS > + (Plus dolje desno) > TMS
Menu name= Orbview
TMS URL= https://tms.osm-hr.org/orbview/{zoom}/{x}/{-y}.png

U Potlatchu:
Kliknuti na Background > Edit...
I napraviti novi upis:
Name= Orbview
URL= https://tms.osm-hr.org/orbview/$z/$x/$-y.png

U ID editoru:
Kliknuti na postavke pozadine (kratica b)
Kliknuti na Podesivo
Upisati https://tms.osm-hr.org/orbview/{z}/{x}/{-y}.png

##OPC

Prikaz svih postojećih lokacija OrbView3 satelitskih snimki.