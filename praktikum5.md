5.1 a. Minimaal õigused faili lugemiseks on r ehk read ning x et directoryile ligipääseda.
5.1 b. Minimaal õigused on wx ehk write ning x et directoryile ligipääseda.

5.2 Kuna shell script faili jaoks on vaja ka read ehk r õigusi. Õiged õigused oleks chmod a=rx fail

5.3 Failide turvalisuse ja õiguste pärast, teeb koostöö paindlikuks ja turvalisemaks.

5.4 

5.5

5.6 Jah setuid võib madaldada turvalisust, näiteks saab õigusi suurendada pahatahtlikel põhjustel ning on pääs kõrgendatud õigustega protsessidele.

5.7 Peeter, failiomanik, Opetaja, kataloogi omanik, root-kasutaja, üldadministraatori kasutaja

5.8

5.9 Ainult root kasutaja saab eemaldada +i atribuudi ning seejärel faili muuta. 
sudo chattr -i testfail-2
sudo rm testfail-2
