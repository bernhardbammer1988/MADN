# Projekt: MADN - Mensch ärgere dich nicht

## Ausgangssituation

Wir sollen ein Softwareprojekt planen und umsetzen um die Planung eines Projekts und Nutzung unserer Projektmanagement Tools zu üben. Die dabei gewonnene Erfahrung soll uns für unsere künftige Diplomarbeit unterstützen.

---

## Projektziele

Ein Brettspiel auf Basis von "Mensch ärgere dich nicht" soll erstellt werden, das folgende Kriterien erfüllt:

- Lokales Spiel mit mehreren Spielern
- Lokales Spiel mit KI-Gegnern
- Multiplayerspiele über Netzwerk (Client zu Client Verbindung, ohne dedizierten Server)
- Savegame Management (Spiel laden/speichern)
- Unterschiedliche Anzahl Spieler
- Verschiedene Spielpläne
- Events auf Spezialfelder (ähnlich wie Monopoly)
- Würfel Events (Ein Würfel der nicht nur 1-6 Augen hat, sondern Events auslöst)

## Nicht-Ziele

- Spiel darf normalen Netzwerkverkehr nicht unnötig stören.
- Spiel darf lokale Ressourcen nicht so stark ausnutzen, dass es die Benutzung des PCs einschränkt.
- Spiel darf nicht zu lange dauern. (Events und Spezialwürfel dürfen das Spielende nicht zu lange hinaus zögern)

---

## Projektinhalte

- Elemente für den Aufbau des Spielbretts bestimmen (unterschiedliche Spielbretter berücksichtigen!)
- Spielbrett erstellen (inklusive Anzeigen, z.B. aktiver Spieler)
- Spieler Steuerung erstellen
- Spielelogik/Ablauf programmieren
- KI Gegner erstellen
- Auswahlmenü (Anzahl Spieler, KI/Mensch, etc.)
- Current State import/export (Für Savegame und Netzwerk Synchronisation)
- Events für Spezailfelder und Würfel bestimmen
- Events implementieren
- Spiel speichern und laden implementieren
- Menü und Logik anpassen um unterschiedliche Spieleranzahl zu unterstützen
- Map Auswahl hinzufügen
- Laden von unterschiedlichen Maps ermöglichen
- Spielablauf mit Animationen verbessern

---

## Kritische Erfolgsfaktoren

- Ein Spiel muss mit mehreren Spielern lokal spielbar bis zum Ende sein.

## Termine

- Projektende: **genaues Datum unbekannt**

---

## Kosten

- Es sollen durch dieses Projekt keine zusätzlichen Kosten entstehen. 

Verwendete Werkzeuge: PC mit Visual Studio, GIT und Internetzugang.

Verwendete Technologien: C#, WPF

---

## Projektorganisation

| **Projektauftraggeber**   | **Projektleiter**                 |
| :------------------------ | :-------------------------------- |
| David Klewein             | Christoph Rechtlehner             |
| **Projektteammitglieder** | **Punktuelle Projektmitarbeiter** |
| Bammer Bernhard           |                                   |
| Qi Tong Zheng             |                                   |
| Christoph Rechtlehner     |                                   |
