# Prompt-Bibliothek-neuropaediatrischer-KI-Assistenz
Prompt-Bibliothek für neuropädiatrische KI-Assistenz: Vorlagen für Fallanalyse, Differenzialdiagnostik, Arztbriefe, Elterninformationen und administrative Texte – ausschließlich für ärztlichen Austausch, Fortbildung und reflektierte Anwendung.


# Neuropädiatrische KI-Prompt-Bibliothek

Diese Sammlung enthält Prompt-Vorlagen zur Unterstützung ärztlicher Anwender:innen in der Neuropädiatrie, Sozialpädiatrie und allgemeinen Pädiatrie.

Die Vorlagen sollen helfen, KI-Chatbots strukturierter, sicherer und nachvollziehbarer für typische ärztliche Arbeitsprozesse einzusetzen, zum Beispiel für:

- strukturierte Fallanalyse
- Differenzialdiagnostik
- Diagnostik- und Managementüberlegungen
- Erstellung von Arztbriefen aus Notizen
- Formulierung von Elterninformationen
- administrative Texte wie Stellungnahmen, Anträge, Gutachten oder Widersprüche

Die Sammlung dient dem fachlichen Austausch, der Fortbildung und der methodischen Weiterentwicklung ärztlicher KI-Nutzung. Sie ersetzt keine ärztliche Entscheidung, keine Leitlinie, keine lokale SOP und keine individuelle Prüfung des konkreten Falls.

---

## Zielgruppe

Diese Prompt-Bibliothek richtet sich primär an:

- Neuropädiater:innen
- Kinder- und Jugendärzt:innen
- Ärzt:innen in SPZ, Klinik, Ambulanz und Praxis
- ärztliche Weiterbildungsassistent:innen
- fachlich involvierte Personen im medizinischen Kontext

Die Prompts sind nicht als direkte Patienteninformation ohne ärztliche Einordnung gedacht.

---

## Inhalt

Die Prompts können einzeln verwendet oder als Grundlage für eigene lokale Vorlagen angepasst werden.

- [Universal-Prompt für neuropädiatrische Assistenz](Prompts/01-universal-prompt.md)
- [Differenzialdiagnostik in der Neuropädiatrie](Prompts/02-differenzialdiagnostik.md)
- [Arztbrief aus Notizen und Befunden](Prompts/03-arztbrief-aus-notizen.md)
- [Elterninformation in verständlicher Sprache](Prompts/04-elterninformation.md)
- [Administrative Tätigkeiten, Gutachten und Anträge](Prompts/05-administration-gutachten-antraege.md)
- [Verbesserte Langversion eines klinischen Assistenz-Prompts](Prompts/06-verbesserter-klinischer-assistenzprompt.md)
- [Kurze Schnell-Prompts für den Alltag](Prompts/07-schnell-prompts.md)
- [Standard-Eingabeformular für Fälle](Prompts/08-standard-eingabeformular.md)
- [Beste Einzelvorlage für den Alltag](Prompts/09-beste-einzelvorlage.md)
- [Selbst formulierter und gut befundener Prompt - Stand 05/25](Prompts/10-selbst-formulierter-prompt-stand-05-25.md)

⸻

Grundprinzipien

Die Vorlagen folgen folgenden Prinzipien:

1. Ärztliche Letztverantwortung bleibt immer beim Menschen.
    KI-Ausgaben sind Vorschläge, keine Diagnosen oder Behandlungsanweisungen.
2. Red Flags und zeitkritische Diagnosen sollen priorisiert werden.
    Besonders gefährliche, behandelbare oder dringliche Erkrankungen sollen aktiv berücksichtigt werden.
3. Differenzialdiagnostisches Denken soll breit und transparent erfolgen.
    Häufige, gefährliche, behandelbare und seltene Ursachen sollen getrennt betrachtet werden.
4. Unsicherheit muss sichtbar bleiben.
    Fehlende Informationen, widersprüchliche Angaben und nicht gesicherte Annahmen sollen klar markiert werden.
5. Quellen müssen überprüfbar sein.
    Leitlinien, Fachgesellschaften und peer-reviewte Literatur sollen bevorzugt werden. Quellen, Zitate, PMIDs, DOIs oder Links dürfen nicht erfunden werden.
6. Datenschutz hat Vorrang.
    Es dürfen keine personenbezogenen oder re-identifizierbaren Patientendaten in öffentliche oder nicht freigegebene KI-Systeme eingegeben werden.

⸻

## Anwendungshinweise

1. Keine identifizierenden Patientendaten eingeben

Eine praktische Schritt-für-Schritt-Anleitung zur Nutzung der Vorlagen in ChatGPT-Projekten findet sich hier:

- [ChatGPT-Projekt erstellen und Prompts als Hinweise hinterlegen](Anleitung/chatgpt-projekt-erstellen-und-prompts-hinterlegen.md)

Bitte keine Angaben verwenden, die eine Re-Identifikation ermöglichen könnten, insbesondere:

* Name
* Geburtsdatum
* genaue Adresse
* Telefonnummer
* Fallnummer
* Versicherungsnummer
* genaue Behandlungsdaten bei seltenen Konstellationen
* seltene Kombinationen aus Diagnose, Ort, Alter und Ereignisdatum
* Fotos, Videos oder Dokumente mit identifizierenden Merkmalen

Bei klinischen Fällen sollten Angaben soweit wie möglich abstrahiert werden.

Beispiel:
Nicht:
„Max M., geboren am 03.04.2018, aus Musterstadt, stellte sich am 12.01.2026 vor.“
Besser:
„6-jähriger Junge mit episodischen Bewusstseinsstörungen, Vorstellung in der Notaufnahme.“

2. KI-Ausgaben immer fachlich prüfen

KI-Systeme können:

* plausible, aber falsche Aussagen erzeugen
* Quellen erfinden
* Leitlinien falsch zusammenfassen
* Dosierungen oder Kontraindikationen übersehen
* lokale Standards nicht kennen
* seltene, aber relevante Diagnosen übersehen
* bei unvollständigen Angaben zu sicher formulieren

Daher müssen alle medizinischen Aussagen, insbesondere zu Diagnostik, Therapie, Dosierungen, Dringlichkeit und Entlassungsfähigkeit, ärztlich geprüft werden.

⸻

3. Therapieempfehlungen besonders kritisch prüfen

Vor jeder therapeutischen Anwendung müssen mindestens geprüft werden:

* Alter
* Gewicht
* Diagnosewahrscheinlichkeit
* klinische Dringlichkeit
* Komorbiditäten
* Organfunktionen
* Begleitmedikation
* Allergien
* Kontraindikationen
* lokale SOPs
* aktuelle Leitlinien
* verfügbare Arzneimittelinformationen

Die Prompts sollen KI-Systeme dazu anhalten, fehlende Angaben aktiv zu benennen. Sie ersetzen jedoch keine ärztliche Arzneimittelprüfung.

⸻

4. Quellenangaben verifizieren

Die Prompts fordern KI-Systeme auf, Quellen anzugeben. Trotzdem gilt:

* Jede Quelle muss überprüft werden.
* Wörtliche Zitate dürfen nur verwendet werden, wenn der genaue Quellentext tatsächlich eingesehen wurde.
* Leitlinienversionen und Aktualität müssen geprüft werden.
* PMIDs, DOIs und Links können falsch sein und müssen verifiziert werden.
* Lokale SOPs und hausinterne Standards haben im klinischen Alltag zusätzliche Relevanz.

⸻

5. Prompts lokal anpassen

Die Vorlagen sind generisch und sollten an lokale Anforderungen angepasst werden, zum Beispiel:

* klinikinterne SOPs
* verfügbare Diagnostik
* lokale Notfallpfade
* regionale Versorgungsstrukturen
* Formulierungsstandards für Arztbriefe
* Vorgaben der Klinik-IT
* Datenschutz- und KI-Richtlinien der jeweiligen Einrichtung

⸻

## Empfohlener Workflow

Klinische Fallanalyse

1. Fall anonymisiert strukturieren.
2. Universalprompt oder Differenzialdiagnostik-Prompt verwenden.
3. KI-Ausgabe auf Red Flags, Plausibilität und fehlende Informationen prüfen.
4. Diagnostik- und Therapieempfehlungen mit Leitlinien, SOPs und Fachwissen abgleichen.
5. Ergebnis nur als Entscheidungshilfe verwenden.

⸻

Arztbrief-Erstellung

1. Nur anonymisierte oder intern freigegebene Notizen verwenden.
2. Arztbrief-Prompt nutzen.
3. KI-Ausgabe sorgfältig prüfen.
4. Keine erfundenen Befunde, Diagnosen oder Empfehlungen übernehmen.
5. Endfassung ärztlich redigieren und verantworten.

⸻

Elterninformation

1. Medizinische Inhalte fachlich festlegen.
2. Elterninformations-Prompt nutzen.
3. Text auf Verständlichkeit, Ton und medizinische Genauigkeit prüfen.
4. Keine individualisierten Versprechen oder nicht gesicherte Prognosen übernehmen.
5. Schriftliche Information nur ergänzend zum ärztlichen Gespräch verwenden.

⸻

Administrative Texte

1. Ziel des Dokuments klären: Antrag, Gutachten, Stellungnahme, Widerspruch etc.
2. Diagnosen und Funktionsbeeinträchtigungen präzise angeben.
3. Administrativen Prompt verwenden.
4. Text auf Sachlichkeit, Nachvollziehbarkeit und Vollständigkeit prüfen.
5. Rechtliche oder sozialrechtliche Aussagen nur nach Prüfung übernehmen.

⸻

Grenzen der Sammlung

Diese Prompt-Bibliothek ist keine medizinische Leitlinie.

Sie ist außerdem kein:

* Medizinprodukt
* zertifiziertes Clinical-Decision-Support-System
* Ersatz für ärztliche Untersuchung
* Ersatz für Supervision
* Ersatz für lokale SOPs
* Ersatz für Leitlinienrecherche
* Ersatz für pharmakologische Prüfung
* Ersatz für Datenschutzprüfung
* Rechtsberatung

Die Qualität der KI-Ausgabe hängt wesentlich ab von:

* Qualität und Vollständigkeit der Eingabe
* verwendetem KI-System
* Aktualität des KI-Systems
* Zugriff auf Quellen
* Prompt-Kontext
* kritischer Prüfung durch ärztliche Anwender:innen

⸻

## Datenschutz und Vertraulichkeit

Bei der Nutzung von KI-Systemen im medizinischen Kontext müssen Datenschutz, ärztliche Schweigepflicht, lokale IT-Vorgaben und institutionelle Freigaben beachtet werden.

Diese Sammlung enthält keine Patientendaten und soll auch nicht mit echten Patientendaten befüllt werden.

Für öffentliche Beispiele sollten ausschließlich vollständig synthetische Fälle verwendet werden.

⸻

## Haftungsausschluss

Die Inhalte dieser Sammlung wurden mit dem Ziel erstellt, ärztliche Anwender:innen beim strukturierten Einsatz von KI-Chatbots zu unterstützen.

Trotz sorgfältiger Erstellung wird keine Gewähr übernommen für:

* medizinische Richtigkeit
* Vollständigkeit
* Aktualität
* Eignung für einen bestimmten klinischen Fall
* rechtliche oder sozialrechtliche Korrektheit
* Kompatibilität mit lokalen Standards
* Fehlerfreiheit der durch KI-Systeme erzeugten Antworten

Die Nutzung erfolgt eigenverantwortlich.

Alle medizinischen, diagnostischen, therapeutischen, organisatorischen und administrativen Entscheidungen müssen durch qualifizierte Fachpersonen geprüft und verantwortet werden.

Die Autor:innen dieser Sammlung übernehmen keine Haftung für Schäden, Fehlentscheidungen oder Nachteile, die aus der Nutzung, Veränderung oder Weitergabe der Prompts oder aus den Antworten von KI-Systemen entstehen.

⸻

## Mitarbeit und Feedback

Rückmeldungen, Verbesserungsvorschläge und fachliche Ergänzungen sind willkommen.

Besonders hilfreich sind Hinweise zu:

* unklaren Formulierungen
* fehlenden Sicherheitsaspekten
* besseren Prompt-Strukturen
* neuropädiatrischen Spezialfällen
* administrativen Anwendungsfällen
* Quellenstrategie
* Datenschutzaspekten
* praktischer Nutzbarkeit im Klinik- oder Praxisalltag

Bitte keine echten Patientendaten in Issues, Pull Requests, Kommentaren oder Beispielen veröffentlichen.

## Lizenz

Die Prompt-Vorlagen, Texte und Dokumentationsinhalte dieses Repositorys stehen, sofern nicht anders angegeben, unter der Creative Commons Attribution 4.0 International License (CC BY 4.0).

Sie dürfen geteilt, weitergegeben, verändert und angepasst werden, sofern eine angemessene Namensnennung erfolgt.

Falls zukünftig Code, Skripte oder Softwarebestandteile ergänzt werden, können diese gesondert unter einer geeigneten Softwarelizenz, z. B. GNU GPLv3 oder MIT License, veröffentlicht werden.
