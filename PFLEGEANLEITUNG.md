# Pflegeanleitung – Digitaler Quellentresor

Stand: 7. November 2026

## Ziel
Das gedruckte Buch bleibt eine stabile Ausgabe; die GitHub-Pages-Website ergänzt bei Bedarf Quellen und notwendige Berichtigungen. Keine Zusage regelmäßiger Updates. Kein Tracking, keine Anmeldung und keine externe Datenbank erforderlich.

## Wo steht was?
- `index.html`: seniorenfreundliche Startseite. Nur selten ändern.
- `quellen.html`: bestehende kapitelweise Buchanmerkungen und Prüfvermerke. Nummerierungen und Textbezüge nur mit Manuskriptabgleich ändern.
- `ergaenzungen.html`: **hier** neue Belege, Ergänzungen, offene Prüfungen und das Änderungsprotokoll fortschreiben.
- `README.md`: allgemeine Orientierung; diese Pflegeanleitung ist nur für Redaktion/Autoren gedacht.

## Einfacher Redaktionsablauf
1. Neuen Fund zunächst **intern prüfen**, nicht sofort veröffentlichen.
2. Titel, Autor, Veröffentlichungsdatum, Original-URL und Abruf-/Prüfdatum festhalten.
3. Exakte Behauptung vom Kommentar/der Deutung trennen. Primärquelle möglichst vorziehen; Gegenbelege und Interessenkonflikte prüfen.
4. Mit `quellen.html` und `ergaenzungen.html` auf Dubletten prüfen. Kapitelbezug und Evidenz-Ampel festhalten: Grün = gesichert; Gelb = plausibel; Orange = vorläufig/kontextabhängig; Rot = unbelegt.
5. Entscheiden: A) bloßer Quellenhinweis, B) wichtige Vertiefung, C) belegte Korrektur. Nur C ausdrücklich als **Berichtigung** kennzeichnen.
6. Nach Freigabe den neuen Eintrag in `ergaenzungen.html` anlegen; Original und ggf. unabhängige Quelle verlinken.
7. Änderungsprotokoll mit Datum, Anlass, Kapitel, URL und Prüfergebnis aktualisieren; Links testen.
8. Änderung auf der GitHub-Pages-Website prüfen. Bei einer tatsächlichen Kindle-Änderung KDP-Vorgaben separat prüfen: Das Website-Update aktualisiert keine gekauften E-Books.

## Datenvorlage (für den internen Entwurf)
- Datum der Aufnahme:
- Titel / Autor / Veröffentlichungsdatum:
- Originalquelle und URL:
- Unabhängige Bestätigung / Gegenbeleg:
- Konkrete belegbare Aussage:
- Grenzen / Interessenkonflikte:
- Buchkapitel / Anmerkungsnummer:
- Evidenz-Ampel und Begründung:
- Typ: Quellenhinweis / Vertiefung / Berichtigung / offen
- Freigabe:
- Änderungseintrag und Linkprüfung:

## Änderungen in GitHub
Repository `schwobablitz/eugen-lore-ki-` → Datei `ergaenzungen.html` → Stiftsymbol (Edit) → kleine Ergänzung machen → „Commit changes“. Vor größeren Änderungen erst eine Kopie bzw. einen eigenen Branch verwenden. Keine bestehenden Kapitelnummern stillschweigend umschreiben. Veränderungen sind über GitHub-Commits nachvollziehbar.

**Wichtig:** Die Ampelfarbe gilt immer der präzise bezeichneten Aussage, nicht pauschal der gesamten Quelle.
