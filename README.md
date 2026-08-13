# k-lani-code-translator

```text
+-------------------------------------------------------------+
|           _  __        _         _     _   _  ___           |
|          | |/ /       | |       / \   | \ | ||_ _|          |
|          | ' /  _____ | |      / _ \  |  \| | | |           |
|          | . \ |_____|| |___  / ___ \ | |\  | | |           |
|          |_|\_\       |_____|/_/   \_\|_| \_||___|          |
|                                                             |
|                C O D E   T R A N S L A T O R                |
|                                                             |
|   UNKNOWN LANGUAGE >>> KNOWN LANGUAGE >>> "NOW I GET IT"    |
+-------------------------------------------------------------+
```

Quellcode in einer vertrauten Form lesen – direkt neben dem Original.
k-lani-code-translator öffnet eine oder mehrere synchronisierte Lesehilfen in
anderen Programmiersprachen oder als deutsche beziehungsweise englische
Erklärung.

[Ohne Installation im Browser ausprobieren](https://code-translator.k-lani.com/#demo):
Quelltext links live bearbeiten und die angepasste Lesehilfe rechts direkt
sehen. Die WebAssembly-Demo läuft lokal im Browser-Tab und lädt den
eingegebenen Code nicht hoch.

> Die Ausgabe ist eine Lesehilfe. Sie ist keine automatische Portierung und
> enthält keine Garantie auf Kompilierbarkeit oder identisches
> Laufzeitverhalten.

## Wo vertraute Syntax Zeit spart

- **Legacy-Systeme warten:** geerbten VB.NET-, C-, C++- oder anderen Code in
  einer Sprache lesen, die das heutige Team kennt.
- **Produktionsprobleme lösen:** Bedingungen, Datenänderungen und Rückgabepfade
  eines unbekannten Dienstes schneller nachvollziehen.
- **Verlorenes Wissen erschließen:** über Jahre gewachsene Geschäftslogik nach
  einem Entwickler-, Dienstleister- oder Eigentümerwechsel zugänglich machen.
- **Sprachübergreifend reviewen:** vorhandene Entwicklungserfahrung in einem
  polyglotten System einsetzen, ohne vorher jede Syntax zu beherrschen.
- **Migrationen vorbereiten:** kritische Module verstehen, bevor eine Anwendung
  umgeschrieben, ersetzt oder stillgelegt wird.
- **KI-generierten Code prüfen:** KI kann Code erzeugen. Die sichtbare Logik
  lässt sich dennoch in vertrauter Syntax beurteilen.

Die Lesehilfe automatisiert keine Migration, beweist keine Korrektheit und
ersetzt keine Kenntnisse der Quellsprache. Sie senkt die Syntaxbarriere, damit
erfahrene Entwickler mehr von der sichtbaren Logik verstehen und fundiertere
Entscheidungen treffen können.

## Unterstützte Sprachen

Python · TypeScript · C# · Java · C++ · C · PHP · Go · Rust · Kotlin · Ruby ·
Swift · VB.NET · Elixir · Zig · Erlang · JavaScript

Alle 17 Programmiersprachen können als Quelle und Leseziel gewählt werden.
**Deutsch** und **Englisch** stehen zusätzlich als erklärende Leseziele zur
Verfügung.

## Verwendung

1. Eine unterstützte Datei in VS Code öffnen.
2. Mit der rechten Maustaste in den Quellcode klicken.
3. **k-lani-code-translator → Lesehilfen öffnen** wählen.
4. Eine oder mehrere Ansichten auswählen, beispielsweise **C#** und
   **Englisch**.

Auswahl, Scrollposition und noch nicht gespeicherte Änderungen bleiben mit den
geöffneten Lesehilfen verbunden. Übersetzungslücken werden sichtbar markiert,
anstatt eine sichere Entsprechung vorzutäuschen.

[Ausführliche Bedienungsanleitung](erweiterung/ANLEITUNG.md)

## Installation

[Im Visual Studio Marketplace installieren](https://marketplace.visualstudio.com/items?itemName=k-lani.k-lani-code-translator)

Alternativ werden geprüfte plattformspezifische VSIX-Pakete unter
**GitHub Releases** angeboten. Lade dort die Datei für dein System und wähle in
VS Code unter **Extensions → … → Install from VSIX…** die Datei aus.

<!-- k-lani-downloads:start -->
[Alle Dateien und Prüfsummen des aktuellen Alpha-Releases](https://github.com/MarvKalani/k-lani-code-translator/releases/tag/v0.260813.5)

Direkte Downloads:

- [Linux x64](https://github.com/MarvKalani/k-lani-code-translator/releases/download/v0.260813.5/k-lani-code-translator-linux-x64.vsix)
- [Linux ARM64](https://github.com/MarvKalani/k-lani-code-translator/releases/download/v0.260813.5/k-lani-code-translator-linux-arm64.vsix)
- [Windows x64](https://github.com/MarvKalani/k-lani-code-translator/releases/download/v0.260813.5/k-lani-code-translator-win32-x64.vsix)
- [macOS Apple Silicon](https://github.com/MarvKalani/k-lani-code-translator/releases/download/v0.260813.5/k-lani-code-translator-darwin-arm64.vsix)
- [macOS Intel](https://github.com/MarvKalani/k-lani-code-translator/releases/download/v0.260813.5/k-lani-code-translator-darwin-x64.vsix)
<!-- k-lani-downloads:end -->

## Lokal und privat

- kein Hochladen des gelesenen Codes
- keine KI-Anfrage
- keine Telemetrie
- keine Passwort-, Wallet- oder Schlüsselbundabfrage

## Probleme und Wünsche

- [Übersetzungsproblem melden](https://github.com/MarvKalani/k-lani-code-translator/issues/new?template=translation.yml)
- [Technisches Problem melden](https://github.com/MarvKalani/k-lani-code-translator/issues/new?template=bug.yml)
- [Verbesserung vorschlagen](https://github.com/MarvKalani/k-lani-code-translator/issues/new?template=feature.yml)

Die Erweiterung kann einen kurzen, bearbeitbaren Problembericht erzeugen.
Werte lassen sich vor dem Kopieren maskieren; es wird nichts automatisch
versendet.

## Lizenz und Unterstützung

Private, lehrende, wissenschaftliche, gemeinnützige und Open-Source-Nutzung
ist unter der [PolyForm Noncommercial License 1.0.0](LICENSE.md) frei.
Kommerzielle Nutzung benötigt eine Lizenz.

[Website und kommerzielle Lizenz](https://code-translator.k-lani.com) ·
[Entwicklung über Ko-fi unterstützen](https://ko-fi.com/mkalani)

Mit deiner freiwilligen Unterstützung über Ko-fi hilfst du dabei, die
Übersetzungen, Hilfen und Sprachabdeckung kontinuierlich weiterzuentwickeln.
Die kommerzielle Nutzung wird separat über die passende Lizenz ermöglicht.
