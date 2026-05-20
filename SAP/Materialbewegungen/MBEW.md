---
Bereich: sap
tags:
	- sap
	- tabelle
	- material
	- bewertung
	- materialbewertung
	- stammdaten
---
## Beschreibung
* Stammdatentabelle zu den Bewertungsdaten von Materialien 
	* Ebene des Bewertungskreises (typischerweise *Werk*)
* Schnittstelle MM -> FI/CO

### Anwendungsfälle
* Materialpreise, Bestandsbewertung
* Produktionskosten, COGS
* Steuerung der Kontenfindung bei Warenbewegungen über die Bewertungsklasse (BKLAS)

## Felder
### Schlüsselfelder
|Feld|Beschreibung|
|---|---|
|**MATNR**|Materialnummer – eindeutige Identifikation des Materials|
|**BWKEY**|Bewertungskreis – in der Regel das Werk, in dem das Material bewertet wird|
|**BWTAR**|Bewertungsart – relevant bei Split Valuation (getrennte Bewertung), z. B. nach Herkunft oder Charge|

### Sonstige Felder
|Feld|Beschreibung|Nutzung|
|---|---|---|
|**VPRSV**|Preissteuerungskennzeichen|Standardpreis (**S**) oder GLD (**V**)|
|**STPRS**|Standardpreis|Der feste Bewertungspreis bei Preissteuerung „S".|
|**VERPR**|GLD Preis|Bei Preissteuerung „V". Bei jedem **Wareneingang automatisch neu berechnet**.|
|**PEINH**|Preiseinheit|z. B. Preis pro 1, 100 oder 1000 Stück|
|**BKLAS**|Bewertungsklasse|Steuert die automatische Kontenfindung (Sachkontenzuordnung) bei Warenbewegungen.|
|**LBKUM**|Gesamtbestand (bewertet)|Menge des bewerteten Bestands in der Basismengeneinheit.|
|**SALK3**|Gesamtwert des Bestands|Der Gesamtwert des bewerteten Bestands in Hauswährung.|
|**MLAST**|Preisermittlung (Material Ledger)|Kennzeichen, ob die Preisermittlung über Material Ledger oder klassisch erfolgt.|
|**BWTTY**|Bewertungskategorie|Gibt an, ob eine getrennte Bewertung (Split Valuation) aktiv ist (z. B. nach Charge oder Herkunft).|
|**STPRV**|Vorjahrespreis / vorheriger Preis|Der zuletzt gültige Preis vor der letzten Preisänderung.|
|**LAEPR**|Datum der letzten Preisänderung|Zeitstempel der letzten Preisanpassung.|

## Verknüpfte Tabellen
* [[MBEWH]]
* [[MARA]]
* [[MARC]]
* [[KEKO]]
## Transaktionen
* [[mm03]] Materialstamm anzeigen
