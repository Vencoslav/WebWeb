# Konvence pro názvy

---

Jazyk: čeština/angličtina 

## Členové týmu: 

 * Jarotek Petr 
 * Doležal Václav 

## Konvence pojmenování: 

 * Čísla v názvech (databáze, tabulky, sloupce a názvy klíčů) budou v jednotném čísle. 
 * Výjimka: Tabulka migrations je v množném čísle (automaticky generovaná, nelze změnit z důvodů funkčnosti). 
 * Víceslovné názvy: Používejte snake_case (každé slovo odděleno podtržítkem "_" ). 
 * Všechno malými písmeny. 

## Konvence pojmenování v Kódu: 

 * Obecná pravidla (česky, jednotné i množné číslo podle potřeby)
 * Metody: camelCase (např. loadDomovskaStranka, getKnizkyAutoru)

---

## Struktura MVC

### Controllery

* PascalCase | Formát: [Controller][View]
* Příklad: ControllerDomovskáStránka
  
### Viewčka

* PascalCase | Formát: [View][Controller]
* Příklad: ViewDomovskaStranka
  
### Knihovny 

* PascalCase | Formát: [Library][Controller NEBO View]
* Příklad: LibraryDomovskaStranka
  
### Modely

* PascalCase | Formát: [Model][Table]
* Příklad: ModelKniha, ModelKnihaAutor
  
### Migrace

* PascalCase | Formát: [Migration][Table]
* Příklad: MigratioKniha, MigrationKnihaAutor
  
### Seedery

* PascalCase | Formát: [Seeder][Table]
* Příklad: SeederKniha, SeederKnihaAutor
* Výjimka: SeederDatabase (soubor, který spouští všechny seedery, nesedí na formát [Seeder][Table])

---

## Assets a šablony

* Složka assets a soubory template a layout jsou malými písmeny
