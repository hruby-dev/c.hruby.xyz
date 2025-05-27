# Struktura programu

Každý příkaz v C obvykle končí středníkem **;** . Program se skládá z funkcí (základem programu je většinou main) a uvnitř funkcí píšeme jednotlivé příkazy.

```c
#include <stdio.h>

int main() {
    puts("Hello, world!");
    return 0;  // 0 značí úspěšné ukončení programu
}
```