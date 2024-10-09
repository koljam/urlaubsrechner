# Flexibler Urlaubsrechner

Dieser Urlaubsrechner ist ein einfaches, aber leistungsfähiges Tool zur Berechnung des Urlaubsanspruchs bei wechselnden Arbeitszeiten im Laufe des Jahres. Er ist besonders nützlich für Teilzeitbeschäftigte oder Personen mit flexiblen Arbeitszeitmodellen.

## Funktionen

- Eingabe des Basis-Urlaubsanspruchs für eine 5-Tage-Woche
- Hinzufügen beliebig vieler Zeitblöcke mit unterschiedlichen Arbeitszeiten
- Automatische Berechnung des anteiligen Urlaubsanspruchs für jeden Block
- Berechnung des Gesamturlaubsanspruchs unter Berücksichtigung aller Zeitblöcke

## Live-Demo

Sie können eine Live-Demo des Urlaubsrechners hier finden: [https://koljam.github.io/urlaubsrechner/](https://koljam.github.io/urlaubsrechner/)

## Anleitung zur Benutzung

1. **Urlaubsanspruch eingeben**: 
   Geben Sie im ersten Feld Ihren jährlichen Urlaubsanspruch bei einer 5-Tage-Woche ein. Dies ist üblicherweise der im Arbeitsvertrag festgelegte Urlaubsanspruch.

2. **Zeitblöcke hinzufügen**:
   - Klicken Sie auf den Button "Block hinzufügen", um einen neuen Zeitblock zu erstellen.
   - Für jeden Block geben Sie die Start-Kalenderwoche und die Anzahl der Arbeitstage pro Woche ein.
   - Sie können beliebig viele Blöcke hinzufügen, um Änderungen in Ihren Arbeitszeiten über das Jahr hinweg abzubilden.

3. **Ergebnisse ablesen**:
   - Der Rechner zeigt für jeden Block den anteiligen Urlaubsanspruch an.
   - Am Ende sehen Sie den Gesamturlaubsanspruch für das Jahr, der alle Blöcke berücksichtigt.

## Beispiel

Angenommen, Sie haben einen Basis-Urlaubsanspruch von 30 Tagen bei einer 5-Tage-Woche und folgende Arbeitszeitänderungen im Jahr:

- Von KW 1 bis KW 26: 5 Arbeitstage pro Woche
- Von KW 27 bis KW 39: 3 Arbeitstage pro Woche
- Von KW 40 bis KW 52: 4 Arbeitstage pro Woche

Geben Sie diese Informationen in den Rechner ein, und er wird Ihren genauen Urlaubsanspruch unter Berücksichtigung dieser Änderungen berechnen.

## Technische Details

Der Urlaubsrechner ist eine einzelne HTML-Datei, die JavaScript zur Berechnung verwendet. Er nutzt Tailwind CSS für das Styling und ist vollständig clientseitig, sodass keine serverseitige Verarbeitung erforderlich ist.

## Beitragen

Wenn Sie Verbesserungsvorschläge haben oder Fehler finden, erstellen Sie bitte ein Issue oder einen Pull Request in diesem Repository. Wir freuen uns über Ihre Beiträge!

## Lizenz

Dieses Projekt ist unter der MIT-Lizenz veröffentlicht. Siehe die [LICENSE](LICENSE) Datei für Details.
