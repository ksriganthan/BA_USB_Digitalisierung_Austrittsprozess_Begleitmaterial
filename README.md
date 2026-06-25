# Begleitmaterial zur Bachelorarbeit

**Digitalisierung des Austrittsprozesses am Universitätsspital Basel**

Bachelorarbeit BSc Wirtschaftsinformatik, FHNW – Hochschule für Wirtschaft
Verfasser: Kapischan Sriganthan · Betreuung: Dr. Felix Härer · 2026

Dieses Repository enthält das digitale Begleitmaterial zur Bachelorarbeit. Es umfasst die maschinenlesbaren BPMN-2.0-Quelldateien der validierten IST-Prozessmodelle, deren bildliche Exporte sowie die im Projektverlauf eingesetzten Präsentationen. Die textlichen Anhänge (Stakeholder-Analyse, Interviewleitfäden, Workshop-Protokoll, Issue Register) befinden sich vollständig im Anhang der Arbeit.

## Inhalt

### `bpmn-modelle/`

Validierte IST-Prozessmodelle des Austrittsprozesses je Austrittstyp (BPMN 2.0, modelliert mit Camunda Modeler). Die Modelle sind die massgebliche Grundlage der IST-Analyse (Kapitel 6).

| Datei | Austrittstyp | Bereich |
|---|---|---|
| `01_Kuendigung-Aufloesung_AuW.bpmn` | Kündigung / Auflösungsvereinbarung | Aus- und Weiterbildung (AuW) |
| `02_Vertragsablauf_AuW.bpmn` | Vertragsablauf (Einzelarbeitsvertrag) | Aus- und Weiterbildung (AuW) |
| `03_Kuendigung-MA_USB-Fonds.bpmn` | Kündigung durch Mitarbeitende | USB / Fonds (Drittmittel) |
| `04_KuendigungAG-Aufloesung_USB-Fonds.bpmn` | Kündigung durch Arbeitgeber / Auflösungsvereinbarung | USB / Fonds (Drittmittel) |
| `05_Vertragsablauf_USB-Fonds.bpmn` | Vertragsablauf | USB / Fonds (Drittmittel) |
| `06_Pensionierung_USB-Fonds.bpmn` | Ordentliche / frühzeitige Pensionierung | USB / Fonds (Drittmittel) |

Die `.bpmn`-Dateien lassen sich mit jedem BPMN-2.0-Werkzeug öffnen (empfohlen: [Camunda Modeler](https://camunda.com/download/modeler/), kostenfrei). Zur reinen Ansicht ohne Installation eignet sich [bpmn.io](https://demo.bpmn.io).

### `bpmn-bilder/`

Bildexporte (PNG/PDF) der sechs Modelle für die schnelle Ansicht ohne BPMN-Werkzeug. Dateibenennung analog zu `bpmn-modelle/`.

### `praesentationen/`

Im Projektverlauf eingesetzte Foliensätze:

- Kick-off-Präsentation (Projektinitialisierung)
- IST-Workshop-Präsentation (Validierung IST-Konzept und Identifikation der Pain Points)
- Zwischenpräsentation

## Zitation

Sriganthan, K. (2026). *Begleitmaterial zur Bachelorarbeit: Digitalisierung des Austrittsprozesses am Universitätsspital Basel* [Datensatz]. GitHub. [URL des Repositorys](https://github.com/ksriganthan/BA_USB_Digitalisierung_Austrittsprozess_Begleitmaterial.git).

## Lizenz / Hinweis

Die Inhalte dienen ausschliesslich der Nachvollziehbarkeit der Bachelorarbeit. Sie enthalten keine personenbezogenen Daten und keine vertraulichen Patientendaten. Interne Dokumente des Universitätsspitals Basel sind nur insoweit enthalten, als sie für die wissenschaftliche Nachvollziehbarkeit erforderlich und freigegeben sind.
