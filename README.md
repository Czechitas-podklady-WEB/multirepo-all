# multirepo-all
Repository obsahující odkazy na všechna repository se šablonami, cvičeními a projekty pro DA Web.

Toto repository obsahuje submoduly podle jednotlivých sekcí (či dlouhodobých kurzů), které teprve obsahují odkazy na jednotlivá repository.

## Kurzy

Odkazovaná repository používají kurzy Czechitas:
* [Digitální akademie: Web](https://kodim.cz/czechitas/daweb/)
* [JavaScript 1](https://kodim.cz/czechitas/js1/)
* [JavaScript 2](https://kodim.cz/czechitas/js2/)
* [React 1](https://kodim.cz/czechitas/react1/)

## Způsob použití

### Klonování

Naklonování všech repository odkazovaných v tomto repository (rekurzivně, tj. mělo by naklonovat všechna repository potřebná pro DA Web):

```sh
git clone --recurse git@github.com:Czechitas-podklady-WEB/multirepo-all.git
```

### Aktualizace

Aktualizace všech submodulů (rekurzivní aktualizace – aktualizuje i submoduly submodulů):

```sh
 git submodule update --remote --recursive
```
