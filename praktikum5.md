5.1 a. Minimaal õigused faili lugemiseks on r ehk read ning x et directoryile ligipääseda.
5.1 b. Minimaal õigused on wx ehk write ning x et directoryile ligipääseda.

5.2 Kuna shell script faili jaoks on vaja ka read ehk r õigusi. Õiged õigused oleks chmod a=rx fail

5.3 Failide turvalisuse ja õiguste pärast, teeb koostöö paindlikuks ja turvalisemaks.

5.4 ![image](https://github.com/user-attachments/assets/a1623349-1ebe-4dd3-8215-e27ec6a5f53e)
![image](https://github.com/user-attachments/assets/0f9288a0-9126-4fea-a8fd-0c1af7fc7e59)


5.5![image](https://github.com/user-attachments/assets/f0174826-40b1-47fa-ab82-28bdc0afac1e)


5.6 Jah setuid võib madaldada turvalisust, näiteks saab õigusi suurendada pahatahtlikel põhjustel ning on pääs kõrgendatud õigustega protsessidele.

5.7 Peeter, failiomanik, Opetaja, kataloogi omanik, root-kasutaja, üldadministraatori kasutaja

5.8
![image](https://github.com/user-attachments/assets/c67c6a1d-df72-4cd8-b03f-9ea235dfb1fe)
![image](https://github.com/user-attachments/assets/a23d9160-1ab3-4198-82ae-31f4321865af)
![image](https://github.com/user-attachments/assets/6bae5092-3366-48cb-b611-8e5b5b7627fc)
Oli võimalik muuta faili sisu!

5.9 Ainult root kasutaja saab eemaldada +i atribuudi ning seejärel faili muuta. 
sudo chattr -i testfail-2
sudo rm testfail-2
