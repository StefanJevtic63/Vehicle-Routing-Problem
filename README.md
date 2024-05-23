# Vehicle Routing Problem With Time Windows

# Uvod

Vehicle Routing Problem (skraćeno VRP) je termin koji se koristi za probleme uspostavljanja ruta sa skup vozila na osnovu jednog ili više skladišta i mušterija do kojih treba da se izvrši dostava dobara. <br>
Ovo je veliki problem u distribuciji i logistici i danas, a prvi put je opisan 1959. godine, od strane Danciga i Ramsera. <br>
Može se posmatrati kao generalizacijom problema putujućeg trgovca, gde se najčešće vrši minimizacija pređenog puta, a u današnje vreme vrši se i minimizacija potrošnje goriva ili vremena. <br>
Bavićemo se varijantom problema gde se optimizuje ukupno proteklo vreme za svaku rutu. <br>

# Definicija problema

Nalazimo se u proizvoljnom gradu u čijem je centru depo odakle sva vozila započinju i završavaju obilazak mušterija. <br>
Skup vozila se tretira kao homogen - vozila su identična sa zadatim kapacitetom. <br>
Svaku mušteriju karakteriše količina traženih proizvoda kao i vremenski interval prijema dobara tj.
svako vozilo mora posetiti mušteriju pre isteka zadatog intervala, a u slučaju ranijeg dolaska mora sačekati. <br>
Cena svake rute ekvivalenta je vremenu potrebnom da se ona obiđe uz dodatna uračunata zadržavanja kod mušterija. <br>
Vreme puta između dve mušterije računamo preko njihovog euklidoskog rastojanja. <br>
Ovo je NP težak problem nad kojim smo primenili nekoliko optimizacionih algoritama sa ciljem poboljšanja proteklog vremena za svaku rutu.

# Iskorišćeni algoritmi

Kao glavni optimizacioni algortiam upotrebili smo Genetski algoritam, nad kojim smo koristili sledeće operacije: <br>
 - Selekcija: Random Selection, Tournament Selection, Roulette Selection, Rang Selection <br>
 - Ukrštanje: Order Crossover, Partially Mapped Crossover, Best Route Better Adjustment Crossover <br>
 - Mutacija preko: Swap Mutation, Invert Mutation, Shaking mutation <br>

# Korišćeni skup podataka

- [R101](http://web.cba.neu.edu/~msolomon/r101.htm)

# Uputstvo za pokretanje

- Pozicionirati se u željeni direktorijum
- git clone git@github.com:AnjaCvetkovic25/vehicle-routing-problem.git

# Autori

[Anja Cvetković](https://github.com/AnjaCvetkovic25/)   
[Stefan Jevtić](https://github.com/StefanJevtic63)
