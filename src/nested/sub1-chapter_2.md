# Datové typy

Programovací jazyk C patří mezi staticky typované jazyky, což znamená, že datový typ každé proměnné je explicitně deklarován v době překladu, nikoliv dynamicky určován za běhu programu. Změna typu proměnné v průběhu jejího životního cyklu není v jazyce C přípustná bez explicitní konverze, což dále podtrhuje důraz na přesnost návrhu datových struktur a algoritmů již ve fázi vývoje.

Základní datové typy jazyka C jsou definované v přiložené tabulce:
| Datový typ | Velikost (bajty) | Popis                          |
|------------|------------------|--------------------------------|
| `char`     | 1                | Znak (ASCII), často i malý integer |
| `int`      | 4                | Celé číslo, rozsah závislý na systému |
| `float`    | 4                | Jednoduchá přesnost, desetinné číslo |
| `double`   | 8                | Dvojnásobná přesnost, větší rozsah než `float` |
| `short`    | 2                | Menší rozsah než `int`              |
| `long`     | 4 nebo 8         | Větší rozsah než `int`              |
| `long long`| 8                | Ještě větší rozsah pro celé číslo   |
| `void`     | 0                | Označuje „žádný typ“, používá se např. u funkcí bez návratové hodnoty |