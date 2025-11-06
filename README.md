# Praesentation: Compilerbau (Die Analysephase)

Hallo! Diese Praesentation habe ich im Oktober 2025 (zusammen mit einem Kommilitonen) fuer unser Modul 'Compilerbau' an der Hochschule Niederrhein gehalten.

[**Hier geht's direkt zur vollstaendigen Praesentation (PDF) – sie oeffnet im Browser.**](./Compilerbau.pdf)

## Worum ging es?

Diese Praesentation behandelt die "Analysephase" eines Compilers – also den Teil, der menschlichen Code versteht und auf logische Korrektheit prueft, bevor er in Maschinencode uebersetzt wird.

Sie zeigt den Weg vom reinen Text bis zur "bedeutungsvollen Struktur".

### Behandelte Themen:

* **Der Weg vom Code zum Baum:** Der Unterschied zwischen einem 'Concrete Syntax Tree' (CST), der nur die Grammatik abbildet, und einem 'Abstract Syntax Tree' (AST), der die logische Struktur darstellt.
* **Die Symboltabelle:** Die Funktion der Symboltabelle als "Gedaechtnis" des Compilers fuer Variablen, Funktionen und ihre Geltungsbereiche (Scopes).
* **Logik-Pruefung:** Der Prozess der Typpruefung (Type Checking) und wie semantische Fehler gefunden werden (z.B. `string + int`).
