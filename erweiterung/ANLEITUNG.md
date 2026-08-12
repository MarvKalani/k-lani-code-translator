# Bedienungsanleitung

## Lesehilfen öffnen

1. Öffne eine unterstützte Quelldatei.
2. Klicke mit der rechten Maustaste in den Quellcode.
3. Öffne **k-lani-code-translator**.
4. Wähle **Lesehilfen öffnen**.
5. Markiere eine oder mehrere Zielansichten, beispielsweise **C#** und
   **Englisch**.

Weitere Ansichten lassen sich später über dasselbe Kontextmenü ergänzen.
Auswahl und Scrollposition bleiben zwischen Original und Lesehilfen verbunden.

## Hinweise vollständig einschalten

Wähle im Kontextmenü
**k-lani-code-translator → Alle Hilfen einschalten (Vollständig)**.
Damit werden zusätzliche Übersetzungshinweise und die optionale
Problemanalyse aktiviert. Das normale VS-Code-Fenster **Probleme** wird
geöffnet; Meldungen der Erweiterung sind dort an der Quelle `k-lani`
erkennbar.

Unter **Hilfen konfigurieren…** können Übersetzungshinweise und Problemanalyse
einzeln abgestuft werden. Die Analyse markiert mögliche Risiken, verändert
aber weder Original noch Leseausgabe.

## Deutsch und Englisch

Neben den Programmiersprachen stehen **Deutsch** und **Englisch** als
erklärende Leseziele bereit. Sie beschreiben den sichtbaren Ablauf in
Alltagssprache und können gemeinsam mit einer Programmiersprache geöffnet
werden.

## Problembericht vorbereiten

1. Öffne die Lesehilfe, in der das Problem sichtbar wird.
2. Wähle im Kontextmenü **Editierbaren Problembericht erstellen**.
3. Prüfe Quell- und Zielausschnitt sowie Diagnose.
4. Maskiere auf Wunsch String- und Zahlenwerte.
5. Ergänze das erwartete Ergebnis und kopiere erst anschließend den Bericht.

Der Bericht enthält nur einen begrenzten Ausschnitt und kann vollständig
bearbeitet werden. Die Erweiterung sendet nichts automatisch.

## Live Debugger

Der Live Debugger ergänzt eine normale VS-Code-Debugsitzung um eine weitere
sprachliche Ansicht. Er verwendet den bereits gewählten Debugger und ersetzt
nicht dessen Laufzeit, Haltepunkte oder Edit-and-Continue-Fähigkeiten.

## Grenzen der Lesehilfe

Die Ausgabe unterstützt beim Verstehen. Sie ist keine Garantie für
Kompilierbarkeit, vollständige Semantik oder identisches Laufzeitverhalten.
Externe Bibliotheken, nicht sichtbare Typinformationen und Sprachmerkmale ohne
direkte Entsprechung können angenähert oder deutlich markiert werden.

[Zurück zur Projektseite](../README.md) ·
[Übersetzungsproblem melden](https://github.com/MarvKalani/k-lani-code-translator/issues/new?template=translation.yml)
