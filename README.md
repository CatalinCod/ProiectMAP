# ProiectMAP
ConvertToRoman
   Documentatie:

- Acesta este un cod care realizeaza crearea si rularea unui cod in limbajul C++ intr-un container Docker
- Codul este un convertor din cifre arabe in cifre romane.

- Structura Codului
Funcții Principale
convertToRoman(int num):

Descriere: Realizează conversia unui număr în echivalentul său în cifre romane.
Parametri:
num - Numărul natural care trebuie convertit.
main():

Descriere: Punctul de intrare în program. Primește input-ul de la utilizator și afișează rezultatele.
Variabile:
numar - Numărul natural introdus de utilizator.


Secvență de Execuție
Citirea Input-ului:

Utilizatorul este invitat să introducă un număr natural.
Verificarea Intervalului:

Se verifică dacă numărul introdus se află în intervalul [1, 3999].
Conversia și Afișarea Rezultatului:

Dacă numărul este în interval, programul apelează funcția convertToRoman și afișează rezultatul.

Platforma destinata pentru containere docker este linux insa acest cod este introdus pe Windows cu ajutorul unor extensei
Avem nevoie sa facem downland la extensiile : C++/C si Dev Docker Containers in VScode.
Avem nevoie ca aplicatia docker desktop sa fie pornita downland:https://www.docker.com/products/docker-desktop/
In VScode deschidem terminaul unde creem imaginea docker pentru codul nostru 



docker build -t linux-cpp-dev



Dupa care putem sa vedem imaginea creata cu comanda 


docker images

Odata ce vedem imaginea creata putem sa dam run cu comanda 




docker run -it --rm -v `pwd`:/work linux-cpp-dev



Putem vedea in aplicatia docker desktop ca s-a creat containerul nostru si codul este in el.

Acum putem sa testam codul.
