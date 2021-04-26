# 2UŽDUOTIS

# V0.1 skirta 2021.02.20

[v0.1](https://github.com/Sasnauskaite/2uzduotis/releases/tag/V0.1)Programa klausia studentų vardų ir pavardžių, pažymių už namų darbus ir už egzaminą bei išveda studento vardą, pavardę ir galutinį pažymį (vidurkį arba medianą) į ekraną. Programa leodžia vartotojui įvesti pažymius pačiam arba juos sugeneruoja, ji taip pat veikia kai pažymių už namų darbus skaičius nėra žinomas. (main.cpp yra versija su masyvais, o vector.cpp yra versija su vektoriais.)

# V0.2 skirta 2021.03.06

[v0.2](https://github.com/Sasnauskaite/2uzduotis/releases/tag/v0.2) yra v0.1 papildymas. Nuo šios versijos programa (vartotojui pasirinkus) gali skaityti duomenis iš *(pavadinimas)*.txt failo (jo pavadinimą reikia įrašyti 25 kodo eilutėje). Programa taip pat išrikiuoja studentus pagal jų pavardes. (Programa yra pavadinta ``vec.cpp``)

# V0.3 skirta 2021.03.06

[v0.3](https://github.com/Sasnauskaite/2uzduotis/releases/tag/v0.3) yra v0.1 ir v0.2 papildymas. Nuo šios versijos programa yra išskirstyta į antrasštinius failus. 
Taip pat nuo šios versijos naudoju išimčių valdymą (angl. exeption handling).

Jeigu keisite duomenų failo pavadinimą, jį keisti reikia `func.h` failo 27 eilutėje.

*Programa yra 3 failuose `v03.cpp`, `func.cpp` ir `func.h`*

# V0.4 skirta 2021.03.20

[v0.2](https://github.com/Sasnauskaite/2uzduotis/releases/tag/v0.4) yra v0.3 papildymas. Nuo šios versijos programa pati gali sukurti šabloninį studentų failą, tuomet jį perskaito, apskaičiavusi galutinį balą išskirsto studentus į ,,mokslinčius" ir ,,nuskriaustuosius" ir išveda informaciją į failus su atitinkamais pavadinimais, taip pat programa apskaičiuoja, kiek ms ji užtrunka atlikdama užduotis (kurdama failą, jį skaitydama, išskirstydama studentus pagal galutinį balą bei išvesdama į atitinkamus failus).

**Tyrimas:**
![image](https://user-images.githubusercontent.com/78842487/116078575-76519100-a69f-11eb-877d-d75fec6db840.png)

Programa su 1000000 failų dirbo labai ilgai (daugiau nei 15min iki kol sustabdžiau ją), todėl rūšiavimo ir išvedimo apskaičiuoti nepavyko.

*Programa yra 3 failuose `v04.cpp`, `funcc.cpp` ir `func2.h`*

# Paleidimo instrukcija
Programą geriausia pasileisti terminale (aš naudoju visual studio code) su šiomis komandomis:

Pirma sukompiliuoti naudojant komandą: 

V0.1-> `g++ main.cpp -o test` (masyvų versijai) arba `g++ vector.cpp -o test` (vektorių versijai)

V0.2-> `g++ vec.cpp -o test`

V0.3-> `g++ v03.cpp -o test` (norint, kad veiktų ši versija jums reikia turėti ir kitus šiai programai reikalingus failus (t.y. func.cpp ir func.h)).

V0.4-> `g++ v04.cpp -o test` (norint, kad veiktų ši versija jums reikia turėti ir kitus šiai programai reikalingus failus (t.y. funcc.cpp ir func2.h)).

Po to tereikia paleisti su komanda: `./test`

Tada programa pradeda veikti ir jums belieka atsakyti į jos užduodamus klausimus (atsakyti reikia t="taip" arba n="ne).
