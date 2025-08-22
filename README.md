# dracor-data-model
Revision of existing data model for DraCor - description/disclaimer

On behalf of @lehkost, I am reviewing the data model for the DraCor project, which has been operating successfully for many years. Numerous countries have contributed their national drama corpora. https://dracor.org/
A new release of the schema/ODD applicable to all drama corpora was last published in July 2025. https://github.com/dracor-org/dracor-schema

In the issues posted here, I discuss, from an outsider's perspective, striking aspects in randomly selected dramas and the ODD, including documentation. I compare them with the current TEI standard and, where possible, also draw on solutions found in the DTA.
This is intended to provide the project with information on where the current TEI standard may take a different approach, where there are other best practice solutions, and thus serve as a basis for discussion within the project. 
I am currently unable to judge which of these proposed changes are sensible, necessary, or feasible. In some cases, I am also not yet aware of the reasons behind certain markup decisions. 
These are all just suggestions and questions, not actual criticism of the solutions that have already been found and proven to work well.


## Arbeitsplan

- [x] Bestehendes ODD einspielen - Doku https://dracor.org/doc/odd
- [x] Beispieltexte für Basisschema auswählen und hochladen: z.B. einfach willkürlich aus gerdracor, engdracor
- [x] Beispieltexte für besondere Bestände auswählen und hochladen.  z.B. Einakter? Der zerbrochene Krug

IST
Metainformationen/Dateistruktur
- [x] Vorgehen Metainformationen abgleichen ODD-Doku gerdracor, engdracor, dutchdracor vs. TEI Guidelines + DTABF, Befunde zur Diskussion in Issues stellen vgl. label https://github.com/textloop/dracor-data-model/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22teiHeader%2Fmeta%20information%22, hier besonders https://github.com/textloop/dracor-data-model/issues?q=is%3Aissue%20state%3Aopen%20label%3Ato-be-discussed  
- [ ] Bereits existierende Issues durchgehen vgl. https://github.com/dracor-org/dracor-schema/issues/71

Sammlung Untersuchungsgegenstände
 - [ ] Issue anlegen: in wenigen Fällen (z.B. Agamemnon) trägt `<person>` @ana um auf Wikidata hinzuweisen. Gegenvorschlag @ref? (Aus Meeting mit FF
 21.08.2025)
 - [ ] gerdracor: CastList auf Ebene von Akt eigentlich von TEI aus nicht zulässig. Ggf. als Beispiel für chaining von dracor.odd.       
       
Schemakonformtität IST Zustand Dateien
- [ ] Standard conformity according to TEI all (WIP) #13
- [ ] Standard conformity according to aktuellem dracor Schema 

Dramentagging
- [ ] Abgleich allgemein mit TEI-Kapitel https://www.tei-c.org/release/doc/tei-p5-doc/en/html/DR.html
- [ ] Abgleich mit weiterem Projekt? Könnt ihr ihr da etwas nennen, das ich noch mit in die Betrachtungen einbeziehen sollte?

ODD/Schema/QM
- [ ] IST-Zustand Projekt ODD Restriktionen ausloten
- [ ] Neustart mit Roma für Dramen: ODD erzeugen und abgleichen mit Projekt-ODD, chining?
- [ ] Identifikation von Mindestelementen und Werten (es geht um Vorgabe für neue Projekte wie vorgegangen werden kann)
- [ ] restriktivere Gestaltung durch weitere Schematron-contraints (Das aktuelle Schema ist bereits produktiv, es soll möglichst wenig geändert und so allgemein bleiben, damit alle es nutzen können)

- [ ] Spezialbestände
- [ ] weitere spezialisierte Bestände mit in die Betrachtung aufnehmen
- [ ] ggf. vom Basisschema aus chainen


