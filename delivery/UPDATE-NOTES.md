Ghuraba zeigt verfügbare Android-Updates direkt in der App an. In den Einstellungen kannst du auch selbst nach Updates suchen.

Supabase und GitHub sind produktiv verbunden. Kontositzungen bleiben über App-Neustarts erhalten; auf Android kann auch ein Kontotresor mit dem geschützten Geräteschlüssel automatisch geöffnet werden. Die E-Mail-Bestätigung unterstützt den Supabase-Standardlink sowie später eine eigene Code-Vorlage.

APK herunterladen, öffnen und das Update in Android bestätigen. Die vorhandene App nicht deinstallieren. Die Paket-ID und der Signaturschlüssel bleiben gleich, damit bestehende Daten bei einem regulären Update erhalten bleiben.

# Ghuraba 0.1.12

- Unter Gebete gibt es einen Ghusl-Tracker. Nach „Ghusl erforderlich“ erinnert Android alle 30 Minuten, auch wenn die App geschlossen ist. „Ghusl erledigt“ beendet die Erinnerungen.
- Der Tracker speichert seinen Zustand und Startzeitpunkt im verschlüsselten Tresor und synchronisiert sie über das Konto. Benachrichtigungsberechtigung und Zustellung gelten pro Gerät; Android kann im Energiesparmodus verzögern.
- Das Journal zeigt alle Gedanken, Dankbarkeitsantworten und datierten Tagesrückblicke direkt an, einschließlich Antworten aus dem Tagesplan. Eine Datumsauswahl ist zum Lesen nicht mehr nötig.
- Jeder Eintrag zeigt Wochentag und vollständiges Datum. Suche und Kategorien schließen die früheren Antworten ein; bestehende Einträge bleiben erhalten.

# Ghuraba 0.1.11

- Wochenziele können jetzt als fehlgeschlagen markiert werden. Ein ehrlicher Grund ist verpflichtend und bleibt im Wochen- und Tagesrückblick sichtbar.
- Beim Scheitern stoppt die tägliche Erinnerung des Wochenfokus. Das Ziel kann weiterhin später erledigt werden.
- Für die beharrlichen Gebetserinnerungen lässt sich der Abstand nach Gebetsbeginn zwischen 10 und 60 Minuten wählen, zum Beispiel alle 15 oder 25 Minuten.
- Fehlschlagsgründe und Erinnerungsabstand gehören zum verschlüsselten Tresor und werden über Supabase zwischen angemeldeten Geräten synchronisiert. Die lokale Android-Benachrichtigungsplanung wird auf jedem Gerät aktualisiert.

# Ghuraba 0.1.10

- Offene Dailys von gestern können am folgenden Tag über den kompakten Hinweis „Gestern nachtragen“ geöffnet und abgehakt werden.
- Am Montag lassen sich auch offene Wochenziele der gerade beendeten Woche nachtragen.
- Das ursprüngliche Aufgaben- oder Wochendatum bleibt erhalten. Zusätzlich speichert der verschlüsselte Tresor den tatsächlichen Tag des Nachtragens und zeigt ihn in Aufgabe und Rückblick an.
- Nachgetragene Erledigungen werden wie alle anderen Tresordaten über Supabase zwischen angemeldeten Geräten synchronisiert.

# Ghuraba 0.1.9

- Auf Heute gibt es jetzt einen kompakten Wochenfokus. Zu Beginn jeder Woche lassen sich mehrere Ziele mit einem kurzen Plan festhalten und einzeln abhaken.
- Genau ein Ziel kann als großes Hauptziel markiert werden. Nur dieses Ziel darf einmal täglich zu einer frei gewählten Uhrzeit erinnern; am Sonntag oder nach dem Abhaken enden die Erinnerungen.
- Wochenziele bleiben im 7-, 30- und 90-Tage-Rückblick sichtbar. Sie gehören zum verschlüsselten Tresor und werden über Supabase zwischen Geräten synchronisiert.
- Bestehende Tresore bleiben kompatibel. Die Android-Benachrichtigungsberechtigung und die lokale Planung gelten weiterhin pro Gerät.

# Ghuraba 0.1.8

- Dailys können zur eingetragenen Uhrzeit eine lokale Android-Benachrichtigung senden.
- Dailys können als fehlgeschlagen markiert werden. Ein Grund ist verpflichtend und bleibt im datierten Rückblick sichtbar.
- Jede Gewohnheit kann zu einer eigenen Uhrzeit eine ermutigende tägliche Erinnerung senden. Abgehakte Tage werden beim Neuplanen ausgelassen.
- Die neuen Einstellungen und Fehlschlagsgründe gehören zum verschlüsselten Tresor und werden über Supabase zwischen Geräten synchronisiert. Die Android-Benachrichtigungsberechtigung gilt weiterhin pro Gerät.

# Ghuraba 0.1.7

- Neue Gebetsbegleitung: zehn Minuten vor dem Gebet und danach alle zehn Minuten bis zum Eintrag.
- Eigener Schalter für die beharrlichen Gebetserinnerungen.
- Neue Ghuraba-Sektion mit Sahih Muslim 145 und passenden Quranstellen zu Standhaftigkeit, Bemühen, guten Taten, Wahrheit und Geduld.
