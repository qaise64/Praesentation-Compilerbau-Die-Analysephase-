# Praesentation: Compilerbau (Die Analysephase)

Hallo! Diese Praesentation habe ich im Oktober 2025 (zusammen mit einem Kommilitonen) fuer unser Seminar + Projekt 'Compilerbau' an der Hochschule Niederrhein gehalten.

## Worum ging es?

Ein Compiler ist eine komplexe Maschine. Diese Praesentation taucht tief in die "Analysephase" ein – also den Teil, der unseren menschlichen Code versteht und auf logische Korrektheit prueft, bevor er ueberhaupt in Maschinencode uebersetzt wird.

Wir schauen uns den Weg vom reinen Text bis zur "bedeutungsvollen Struktur" an.

### Was ich in der Praesentation beleuchte:

* **Der Weg vom Code zum Baum:** Was ist der Unterschied zwischen einem 'Concrete Syntax Tree' (CST), der nur die Grammatik abbildet, und einem 'Abstract Syntax Tree' (AST), der die logische Struktur darstellt?
* **Das 'Gehirn' des Compilers:** Wie funktioniert eine Symboltabelle, um alle Variablen, Funktionen und ihre Geltungsbereiche (Scopes) zu verwalten?
* **Logik-Pruefung:** Wie der Prozess der Typpruefung (Type Checking) funktioniert und semantische Fehler findet (z.B. wenn man versucht, einen `string` und einen `int` zu addieren).
