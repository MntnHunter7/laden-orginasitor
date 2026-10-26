# Salon-Vorrat

Kleine App für den Friseursalon, um **Vorrat und Einkauf** im Blick zu behalten:
Produkte anlegen → Verbrauch buchen → App meldet, wenn nachbestellt werden muss → Einkaufsliste → nach dem Einkauf abhaken (Bestand wird automatisch aufgefüllt).

Läuft komplett **im Browser, offline, ohne Installation und ohne Konto**. Alle Daten bleiben auf dem Gerät.

---


## Auf dem iPhone (empfohlen)

Wichtig: Die Daten liegen lokal im Browser des jeweiligen Geräts (iPhone ist Vorratsverwalter, kein zentraler Server). Deshalb regelmäßig **Backup speichern** („Mehr“ → Backup speichern) und am Tablet/PC per „Backup laden“ einspielen. Teilen geht über AirDrop, Dateien-App, WhatsApp, Mail …


---

## Bedienung in Kurzform

| Was | Wie |
|---|---|
| Produkt anlegen | „Produkte“ → „+ Neu“ (oder der runde + Knopf) |
| Felder | **Name**, **Kategorie**, **Einheit**, **Aktuell vorhanden**, **Nachbestellen ab** (= Mindestbestand). Unter „Weitere Einstellungen“: Warnung schon früher starten, **Preis pro Einheit**, Notiz |
| Verbrauch buchen | Auf der Produktkarte „− Verbrauch“ → Menge → fertig (Restbestand wird automatisch berechnet). Schnellwahl-Knöpfe +1/+2/+5/+10 usw. |
| Wareneingang | „+ Eingang“ – Menge, die dazugekommen ist |
| Bestand korrigieren | Produkt bearbeiten → „Aktuell vorhanden“ ändern (wird im Verlauf protokolliert) |
| Warnung | Sobald Bestand ≤ Mindestbestand (oder ≤ „Warnung schon ab“) erscheint das Produkt unter „Übersicht“ ganz oben |
| Einkaufsliste | In der Warnung „🛒 Auf Liste“ (Vorschlagsmenge lässt sich auf der Liste anpassen) oder „Alle auf Liste“ |
| Nach dem Einkauf | In der Einkaufsliste das Kästchen antippen → Menge wird automatisch in den Bestand gebucht |
| Rückgängig | Toast „↺ Rückgängig“ direkt nach dem Buchen, oder im „Verlauf“ bei jedem Eintrag |
| Reichweite | Auf der Produktkarte „▾“ → durchschnittlicher Verbrauch + „reicht noch ca. X Tage“ |
| Später melden | ⏰ bei einer Warnung → 7 Tage ausblenden (nächster Verbrauch aktiviert sie wieder) |
| Lagerwert | Aus vorhandener Menge × Preis pro Einheit, auf der Übersicht |

## Backup

- **Backup speichern**: JSON-Datei mit allem (Produkte, Verlauf, Einkaufsliste, Einstellungen).
- **Backup laden**: auf einem anderen Gerät/neuem Browser den Stand einspielen.
- **Verbrauch als Tabelle (CSV)**: für Excel/LibreOffice/Google Tabellen.
- ⚠️ Vor „Browserdaten löschen“, „Alle Daten löschen“ oder Handywechsel unbedingt ein Backup machen.

## Hinweise

- Ein **geringer Bestand** ist kein Fehler: Wird etwas mehr verbraucht als eingetragen, kann der Bestand kurz ins Minus gehen – das zeigt, dass man nachbestellen muss. Er wird beim Einkauf wieder aufgefüllt.
- „Reichweite“/„Bald handlungsbedarf“ ist eine **Schätzung** aus dem bisherigen Verbrauch und wird mit der Zeit genauer.
- Die App fragt den Browser nach dem Speicher; wenn man im **Privatmodus** surft, werden Daten nicht dauerhaft gespeichert.
