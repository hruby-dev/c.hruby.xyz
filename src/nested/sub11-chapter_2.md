# Reprezentace řetězců
Na rozdíl od moderních programovacích jazyků, které poskytují integrovaný datový typ string, jazyk C neobsahuje nativní typ pro reprezentaci textových řetězců. Řetězec (string) je v jazyce C realizován jako pole znaků typu char, zakončené nulovým znakem ('\0', tzv. null terminátor), který označuje konec řetězce.

Zde je přiložený příklad řetězce jehož obsah je `"Hello World!"`:
```c
char pozdrav[] = "Hello World!";
```
Tento zápis je ekvivalentní:
```c
char pozdrav[] = {'H', 'e', 'l', 'l', 'o', '', 'W' 'o', 'r', 'l', 'd', '!', '\0'};
```