Ghuraba zeigt verfügbare Android-Updates direkt in der App an. In den Einstellungen kannst du auch selbst nach Updates suchen.

Supabase und GitHub sind produktiv verbunden. Kontositzungen bleiben über App-Neustarts erhalten; auf Android kann auch ein Kontotresor mit dem geschützten Geräteschlüssel automatisch geöffnet werden. Die E-Mail-Bestätigung unterstützt den Supabase-Standardlink sowie später eine eigene Code-Vorlage.

APK herunterladen, öffnen und das Update in Android bestätigen. Die vorhandene App nicht deinstallieren. Die Paket-ID und der Signaturschlüssel bleiben gleich, damit bestehende Daten bei einem regulären Update erhalten bleiben.

# Ghuraba 0.1.22

- Wiederkehrende Fokuspläne nach dem Vorbild der bereitgestellten Opal-Bilder: „Study Time“, „Abendruhe“ und „Zeit im Grünen“ als anpassbare Vorlagen, Bildkarten, kompakter Dialog, feste Start-/Endzeiten und wählbare Wochentage.
- Jeder Plan hat seine eigene App-Auswahl. Die Regeln werden auf Android gespeichert und gelten auch bei geschlossener Ghuraba-App mit aktivierter Bedienungshilfe. Pläne können bearbeitet, pausiert und gelöscht werden; Zeitfenster über Mitternacht gehören zum Starttag.
- Normale Pausen haben 20 Sekunden Wartezeit, strengere Pläne 60 Sekunden. Die sofortige Notfallfreigabe und freie System-/Telefonfunktionen bleiben erhalten. Bei überlappenden Regeln bleiben Apps gesperrt, solange mindestens eine passende Regel aktiv ist.
- Optionale wöchentliche Hinweise fünf Minuten vorher und zum Start, unabhängig vom einmaligen Fokus-Timer. Android kann Benachrichtigungen verzögern. Nach einer Zeitzonenänderung Ghuraba öffnen, damit auch die geplanten Erinnerungen neu angelegt werden; Sperrregeln verwenden die aktuelle Geräte-Zeitzone.
- Pläne sind gerätelokal, nicht Teil des verschlüsselten Kontotresors. Ein Browser zeigt die Vorschau; tatsächliche Sperren benötigen die Android-App.

# Ghuraba 0.1.21

- Beim tatsächlichen Erscheinen des Sperrfensters vibriert das Handy dreimal kräftig (insgesamt etwa 1,2 Sekunden, ohne Wiederholungsschleife). Unter „App-Schutz“ lässt sich die Vibration ausschalten; die Einstellung bleibt auf diesem Gerät gespeichert.
- Eine Sperransicht kann frühestens nach 15 Sekunden erneut vibrieren. Beim Schließen wird die laufende Vibration abgebrochen. Geräte ohne Vibrationsmotor oder abgelehnte Vibration beeinträchtigen die App-Sperre nicht. Die tatsächliche Stärke wird durch Hardware und Android-Einstellungen begrenzt.

# Ghuraba 0.1.20

- Neue Gestaltung in Anthrazit, Moosgrün und warmen Naturtönen, mit leichteren Übergängen, seitlich wischbaren Fokus-Vorlagen und einem echten Timer-Fortschrittsring. Die Startseite verlinkt direkt zum Fokus und zeigt den tatsächlichen Tagesfortschritt.
- Sperrlogik korrigiert: Die Zeitprüfung läuft auch auf nicht ausgewählten Apps und Systemoberflächen weiter. Tastaturfenster ersetzen nicht mehr die erkannte App. Zusätzlich werden Paketnamen aus Fokus- und Klickereignissen verarbeitet, ohne Bildschirmtexte, Eingaben oder Accessibility-Nodes auszulesen.
- Ein einminütiger Sperrtest öffnet eine ausgewählte App. Während einer laufenden Sitzung prüft er die bestehende Sperre, ohne deren Ende zu verändern. Diagnose zeigt getrennt empfangene App-Ereignisse und tatsächlich aufgebaute Sperransichten; eine Berechtigung allein bestätigt keine funktionierende Sperre.
- Android-Emulatortest als zusätzliche Freigabeprüfung: echte Test-App, Sperrfenster, Notfallpause, Fortsetzen, freie Systemeinstellungen und geplanter Start. Ein Emulator ersetzt keinen Praxistest auf Samsung/One UI.

# Ghuraba 0.1.19

- Neuer Android-Einrichtungscheck unter „Fokus & App-Schutz“: zeigt getrennt die Android-Berechtigung, die tatsächliche Verbindung des Bedienungshilfendienstes, die App-Benachrichtigungsfreigabe und den Fokus-Kanal. Nach Rückkehr aus Android und über „Erneut prüfen“ wird neu abgefragt.
- Die zusätzliche Berechtigung für exakte Alarme wird nicht mehr angefordert, da alle Ghuraba-Erinnerungen bereits bewusst ungenau geplant werden. Das reduziert Berechtigungen, ändert aber keine Play-Protect-Einstufung.
- Eine eingeschaltete Bedienungshilfe ohne verbundenen Dienst wird nicht als einsatzbereiter App-Schutz bestätigt. Fokuszeiten lassen sich dann noch nicht starten. Fehler beim Erstellen der Sperransicht werden gesondert angezeigt.
- Eine Testmeldung kann angefordert werden. Planung und von Android gemeldete Veröffentlichung werden ausdrücklich getrennt; Energiesparen, Nicht-stören und Samsung-Schlaflisten können die Sichtbarkeit weiterhin beeinflussen.
- Hilfen unterscheiden eingeschränkte Einstellungen, Samsung Auto Blocker und Play Protect. Der Check liest keine Play-Protect-Bewertung aus und hebt keine Sicherheitswarnungen auf. Bei einer Schädlichkeitswarnung bleibt die Empfehlung: Sperre nicht umgehen, Meldung prüfen und gegebenenfalls Google um Überprüfung bitten.

# Ghuraba 0.1.18

- Fokuszeiten können mit einer Startuhrzeit für heute oder morgen geplant werden. Vorher beginnt keine Fokus-Sperre; der Gebetsmodus bleibt unabhängig davon aktiv. Vor dem Start kann die Planung abgesagt werden.
- Zwei dezente Fokusmeldungen: fünf Minuten vor einer geplanten Sitzung (bei ausreichendem Vorlauf) und zum Start mit der Dauer. Sofort gestartete Sitzungen erhalten nur die Startmeldung. Persönliche Absichten und App-Namen erscheinen nicht auf dem Sperrbildschirm.
- Abgesagte oder vorzeitig beendete Sitzungen entfernen ihre geplanten Fokusmeldungen. Beim erneuten Öffnen einer laufenden Sitzung wird keine weitere Startmeldung ausgelöst. Die Benachrichtigungsberechtigung ist unabhängig vom App-Schutz; Android kann die Zustellung verzögern.

# Ghuraba 0.1.17

- Neuer Bereich „Fokus & App-Schutz“ auf Heute und unter Einstellungen. Wähle Apps auf deinem Android-Gerät, eine Absicht und eine Fokuszeit von 1 bis 480 Minuten. Ruhige Naturkarten, ein klarer Countdown und eine sanfte Atemanimation begleiten die Bedienung.
- Der freiwillige Android-Bedienungshilfendienst sperrt ausgewählte Apps auch bei geschlossener Ghuraba-Oberfläche. Er erkennt nur App-Paketnamen und liest keine Bildschirminhalte oder Eingaben. Ohne selbst aktivierten Dienst gibt es keine App-Sperre.
- Optionaler Gebetsmodus: Sperre ab Gebetsbeginn bis zum Eintrag „gebetet“ oder „pausiert“. Beim nächsten Gebet beginnt ein neues Zeitfenster. Der Offline-Plan reicht 30 Tage und wird beim Öffnen aktualisiert. Nach Standort-/Zeitzonenänderung Ghuraba öffnen und die Zeiten prüfen.
- Normale Unterbrechungen: 20 Sekunden innehalten, anschließend 5 Minuten freigeben oder Fokuszeit beenden. Notfälle: jederzeit sofort 10 Minuten freigeben, ohne Begrenzung der Anzahl. Laufende Fokuszeiten werden durch eine Freigabe nicht verlängert.
- Telefon, Notruf, Systemeinstellungen und Ghuraba bleiben zugänglich; der Dienst kann jederzeit in Android deaktiviert werden. App-Auswahl, Freigaben und die letzten 30 Timer-Sitzungen bleiben auf diesem Gerät und werden nicht mit dem Tresor synchronisiert. Fokuszeiten bezeichnen Timer-Laufzeit, keine gemessene Konzentration oder Bildschirmzeit.

# Ghuraba 0.1.16

- Abgehakte Ghusl-Waschungen werden mit Datum gespeichert. Der Tracker zeigt die Gesamtzahl; im Rückblick zählt eine eigene Karte die Waschungen im gewählten Zeitraum (7, 30 oder 90 Tage). Der Tagesverlauf zeigt die einzelnen Erledigungen.
- Mehrere Waschungen am selben Tag zählen einzeln. Die Historie bleibt im verschlüsselten Tresor und wird mit dem Konto synchronisiert.
- Die zuletzt gespeicherte Waschung aus älteren Versionen wird übernommen. Weitere frühere Waschungen sind nicht rekonstruierbar, weil ältere Versionen nur die letzte Erledigung gespeichert haben.

# Ghuraba 0.1.15

- Die obere Leiste auf dem Handy hat mehr Abstand: Logo und Aktionen stehen in einer eigenen Zeile, der Speicher- und Synchronisierungsstatus darunter. Auch längere Statusmeldungen haben Platz.

# Ghuraba 0.1.14

- Screenshots und Bildschirmaufnahmen sind in der Android-App jetzt erlaubt.

# Ghuraba 0.1.13

- Beim Aktivieren des Ghusl-Trackers wird nach dem Anlass gefragt. Eigene Entscheidungen können mit einer kurzen Reflexion und einem nächsten guten Schritt festgehalten werden. Natürliche oder eheliche Anlässe werden nicht als persönliches Scheitern behandelt; intime Details müssen nicht angegeben werden.
- Die Reflexion kann bei aktivem Tracker angesehen und bearbeitet werden, ohne den Erinnerungsrhythmus neu zu starten.
- Zwei abwechselnde Ghusl-Erinnerungen fordern freundlich zum Handeln auf: etwa zehn Minuten für Ghusl einplanen, Ablenkung beiseitelegen und zum Gebet zurückkehren. Der Abstand bleibt 30 Minuten bis zum Abhaken.
- Persönliche Antworten bleiben im verschlüsselten Tresor und erscheinen nie im Benachrichtigungstext. Bestehende Ghusl-Einträge bleiben kompatibel.

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
