# Kulturdaten an der Staatsbibliothek zu Berlin (SBB)

Die Generierung von Kulturdaten durch die Digitalisierung von Sammlungen ermöglicht den Einsatz neuer Methoden zur Erforschung des kulturen Erbes. Im Sinne des [_Collections-as-Data_](https://zenodo.org/records/8342171)-Paradigmas ermöglichen daten-getriebene Methoden etablierte Erkenntnisse zu überprüfen und neues Wissen zu schaffen. Wissen kann in neue Zusammenhänge gesetzt und mit Daten anderer Sammlungen und Dienste verknüpft werden. Fragen zum Umgang mit Daten z.B. aus ethischen und ökologischen Perspektiven sowie zu Deutungshoheit sind dabei wichtige Aspekte, um historische Praktiken kritisch zu reflektieren und das digitale Kulturerbe offen und verantwortungsbewusst zu gestalten.

### TUTORIALS UND DOKUMENTATION

[OAI-Schnittstellen Request, Antwort, Herunterladen der Daten](https://lab.sbb.berlin/oai-schnittstellen-mit-python/)
Dieses Tutorial bietet Beispiele für Abfragen über die OAI-Schnittstelle mit Python. Es behandelt exemplarische Anfragen an die OAI-PMH-Schnittstelle der Staatsbibliothek zu Berlin - PK. Darüber hinaus wird das Herunterladen der Daten und das Speichern in einer CSV-Datei erläutert.

---

Die Sammlungen der Staatsbibliothek zu Berlin stehen über verschiedene Zugänge als Daten zur Verfügung:

### OFFENE SCHNITTSTELLEN

#### OAI-PMH - Die Schnittstelle der [Digitalisierten Sammlungen](https://digital.staatsbibliothek-berlin.de/#!) der SBB
Basis-URL: [https://oai.sbb.berlin](https://oai.sbb.berlin/)

Abfragebeispiel in den Digitalisierten Sammlungen der SBB um Metadaten der digitalisierten Objekte aus der Sammlung Historische Drucke zu erhalten:

    https://oai.sbb.berlin?verb=ListRecords&set=historische.drucke&metadataPrefix=oai_dc

Video-Tutorial: [Abfrage der OAI-PMH Schnittstelle](https://youtu.be/uY1sbKyKzj0)

Dokumentation: [https://lab.sbb.berlin/dc](https://lab.sbb.berlin/dc/)

**Lizenz:** Die Metadaten, Volltexte und Digitalisate der [Digitalisierten Sammlungen](https://digital.staatsbibliothek-berlin.de/#!) der SBB sind mit einer Public Domain Mark 1.0 Lizenz ausgezeichnet.

---

#### SRU - Search and Retrieve - Die Schnittstelle des Katalogs der SBB
Abfrage bibliografischer Daten (Metadaten) 

Basis-URL: http://sru.k10plus.de/opac-de-1

Abfragebeispiel um bibliografische Daten aus dem Katalog der Staatsbibliothek  zu Berlin ```(opac-de-1)```zu Publikationen mit den Begriffen ```"swift+taylor"``` im Titel ```(xtit)```:

    https://sru.k10plus.de/opac-de-1?version=1.1&operation=searchRetrieve&query=pica.xtit=swift+taylor&maximumRecords=300&recordSchema=dc

Dokumentation: [https://lab.sbb.berlin/bibliographische-daten-aus-dem-stabikat](https://lab.sbb.berlin/bibliographische-daten-aus-dem-stabikat/)

---

### KURATIERTE DATENSETS

#### Stabi Lab

Das Stabi Lab stellt kuratierte Datensets bereit:
[https://lab.sbb.berlin/datadumps](https://lab.sbb.berlin/datadumps/)

#### Zenodo

Die SBB publiziert kuratierte Datensets auf der offenen Platform Zenodo: [https://zenodo.org/communities/stabi](https://zenodo.org/communities/stabi)

#### HuggingFace

HuggingFace richtet sich besonders an die Machine Learning-Community. Neben Modellen veröffentlich die SBB hier ebenfalls Datensets:
[https://huggingface.co/SBB/datasets](https://huggingface.co/SBB/datasets)
