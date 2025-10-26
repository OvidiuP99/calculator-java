# Teste Black Box - Calculator

| Test | Expresie        | Rezultat așteptat | Rezultat obținut | Observații                       |
|------|-----------------|-----------------|-----------------|---------------------------------|
| 1    | 2+2             | 4               | 4               | OK                               |
| 2    | 5-3             | 2               | 2               | OK                               |
| 3    | 3*4             | 12              | 12              | OK                               |
| 4    | 12/4            | 3               | 3               | OK                               |
| 5    | 2+3*4           | 14              | 14              | Respectă prioritatea operatorilor |
| 6    | (2+3)*4         | 20              | 20              | Paranteze calculate corect      |
| 7    | 10/0            | Eroare          | Exception       | Trebuie tratat divide by zero   |
| 8    | 2++3            | Eroare          | Crash / Exception | Input invalid, se poate adăuga validare |
| 9    | -5+3            | -2              | -2              | Numere negative sunt suportate  |
| 10   |  2 + 3          | 5               | 5               | Spațiile sunt ignorate          |
