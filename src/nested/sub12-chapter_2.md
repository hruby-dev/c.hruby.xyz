# Podepsané a nepodepsané celočíselné typy
Celočíselné datové typy v jazyce C lze rozdělit na podepsané (signed) a nepodepsané (unsigned) podle toho, zda umožňují reprezentaci záporných hodnot. Výchozí chování datového typu int je obvykle signed, což znamená, že jeho binární reprezentace využívá jeden bit pro znaménko a zbývající bity pro velikost čísla.

| Typ                | Velikost (bajty) | Rozsah                         |
|--------------------|------------------|--------------------------------|
| `signed char`       | `1`             | −128 až 127                    |
| `unsigned char`      | `1`          | 0 až 255                       |
| `signed short`       |`2`        | −32 768 až 32 767              |
| `unsigned short`     | `2`            | 0 až 65 535                    |
| `signed int`         |`4`          | −2 147 483 648 až 2 147 483 647|
| `unsigned int`       | `4`         | 0 až 4 294 967 295             |
| `signed long`        |`4/8`        | dle architektury               |
| `unsigned long`      | `4/8`          | dle architektury               |
| `signed long long`   |`8`              | −9 223 372 036 854 775 808 až +9 223 372 036 854 775 807 |
| `unsigned long long` | `8`              | 0 až 18 446 744 073 709 551 615|