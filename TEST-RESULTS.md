#  TEST-RESULTS

##  Testare Black-Box — Aplicația Calculator

| Nr. | Expresie testată | Rezultat așteptat | Rezultat obținut | Observație |
|:---:|:----------------|:----------------|:----------------|:------------|
| 1 | `4+5` | 9 | 9 | Corect — operație simplă de adunare |
| 2 | `10+5*4+3` | 33 | 33 | Corect — respectă prioritatea operatorilor |
| 3 | `(2+3)*4` | 20 | 20 | Corect — test cu paranteze |
| 4 | `5.5+2.3` | 7.8 | 7.8 | Corect — valori zecimale acceptate |
| 5 | `a+5` | Eroare | Eroare: input invalid | Corect — detectează operand nenumeric |
| 6 | `4#2` | Eroare | Eroare: operator necunoscut | Corect — operator invalid |
| 7 | `3/0` | Eroare | Eroare: împărțire la zero | Corect — gestionare excepție |

---

##  Concluzii testare

- Programul procesează corect expresii aritmetice valide, inclusiv cu **paranteze** și **numere zecimale**.  
- Erorile de intrare (caractere nenumerice, operatori necunoscuți, împărțire la zero) sunt identificate corespunzător.  
- Totuși, se pot adăuga mesaje de eroare mai descriptive pentru utilizator.  
- Recomandare: includerea testelor automate (JUnit) pentru validarea continuă a metodei Calculate().






