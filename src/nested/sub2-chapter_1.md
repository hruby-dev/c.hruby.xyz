# Překlad jazyka C

**Překladač (compiler)** je nástroj, který **převádí zdrojový kód** napsaný v jazyce C do nízkoúrovňového **strojového kódu** (binárního formátu), který je přímo vykonatelný na cílové architektuře. Výstupem kompilace je obvykle **spustitelný soubor** ve formátu specifickém pro daný operační systém (např. ELF na Linuxu, PE na Windows).

Proces překladu obvykle zahrnuje několik fází:

- **Lexikální analýza** – rozklad zdrojového kódu na tokeny.

- **Syntaktická a sémantická analýza** – ověření správnosti gramatiky a významu kódu.

- **Intermediate representation (IR)** – převod do meziformátu pro optimalizaci.

- **Optimalizace** – úprava IR pro efektivnější výsledný kód.

- **Generování cílového kódu** – převod do strojového kódu dané architektury.

- **Linkování** – propojení s knihovnami a vytvoření finálního spustitelného souboru.

Mezi nejčastěji používané překladače pro jazyk C patří:

**GCC (GNU Compiler Collection)** – robustní a široce podporovaný open-source překladač s rozsáhlými možnostmi ladění a optimalizace.

**Clang** – moderní překladač založený na infrastruktuře LLVM, oblíbený pro svou modulárnost, rychlost a detailní diagnostické výstupy.

Příklad překladu jednoduchého programu pomocí GCC:
```bash
gcc -o main main.c
```
Tento příkaz překládá `main.c` a výstupní binární soubor pojmenovává `main`.

Výsledný binární soubor lze následně spustit přímo na daném cílovém systému.

```bash
chmod +x main
./main
Hello World!
```