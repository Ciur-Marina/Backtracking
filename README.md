# Backtracking
spargerea unui cifru din n cifre https://repl.it/@CiurMarina/Bactraking#main.c
# Scopul proiectul dat: 
Se presupune că există o funcție care primește ca parametru o combinație de n cifre luate câte c elemente și returnează toate combinările posibile.
## Metoda backtracking este recomandată în cazul problemelor care îndeplinesc simultan următoarele condiții:
1.soluția lor poate fi pusă sub forma unui vector S=(x1,x2, ...,xn)
2.fiecare element al soluției xi poate să ia valori intr-o mulțime Ai
3.mulțimile A1, A2 .. An sunt mulțimi finite, iar elementele lor se considera că se afla într-o relație de ordine bine stabilită;
4.A1, A2,..., An  pot coincide;
5.nu se dispune de o altă metodă de rezolvare, mai rapidă.
Este o tehnică de programare aplicabilă algoritmilor care oferă mai multe soluții și are ca rezultat obținerea tuturor soluțiilor problemei. Fiecare soluție se memoreaza într-o structură de date de tip stivă implementată cu ajutorul unui vector. Deci fiecare soluție poate fi pusă sub forma unui vector.
# Rezultatele algoritmului :
![baktr](https://user-images.githubusercontent.com/75802856/102916777-c5d34680-448c-11eb-9a9a-270e895c059a.jpg)
# Concluzie:
Această metodă este foarte folositoare în cazurile când problema are mai multe soluții. Pentru a înțelege această metodă am creat un program în C care determină toate combinările posibile ale oricărei mulțimi. Această metodă se bazează pe principiul întoarcerii, după cum și se traduce, de accea metoda parcurge toată mulțimea și verifică fiecare element până la sfârșit pentru ca soluția să fie validă. Apoi, metoda se întoarce la începutul mulțimii, căutând alte soluții valide.

