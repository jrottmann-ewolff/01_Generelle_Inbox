---
Bereich: sap
tags:
  - tabelle
  - profitcenter
  - lines
  - zeilen
---

## Felder

* RCLNT *MANDT* - Client
* GL_SIRID *OBJNR* - NUMC18! gibt die Zeile an. Als Index geeignet
* RLDNR - Leger [[T881]]
* RYEAR *GJAHR* - Fiscal Year
* RTCUR *WAERS* - Transaktionswährung [[TCURC]]
* RUNIT *MEINS* - Mengeneinheit
* DRCRK *SHKZG* - Debit/Credit Indicator
* DOCCT - Document Type

	| Belegtyp | Beschreibung |
	| --- | --- |
	| A | Belege mit vergebener Belegnummer der Empfängerapplikation|
	| * | Beliebiger Beleg-Typ |
	| B | Belege aus der Buchhaltung |
	| C | Belege aus der Währungsumrechnung |
	| K | Belege aus dem CO |
	| G | Belege aus dem FI-SL für globale Buchungen |
	| L | Belege aus dem FI-SL für lokale Buchungen |
	| T | Stornobelege aus dem FI-SL für globale Buchungen |
	| U | Stornobelege aus dem FI-SL für lokale Buchungen |
	
* DOCNR *BELNR* - Document Number of Accounting Document
* DOCLN - Document line
* RBUKRS *BUKRS* - Company Code
* RPRCTR *PRCTR* - Profit Center [[CEPC]]
* [[T856]]
* RHOART - Art des Herkunftsobjektes

	| Herkunft | Beschreibung |
	| --- | --- |
	| 01 | Profit Center |
	| 02 | Kostenstelle |
	| 03 | Gemeinkostenauftrag |
	| 04 | Fertigungsauftrag |
	| 05 | Faktura |
	| 06 | Kundenauftrag |
	| ... | ... |
* FFAREA - Funktionsbereich
  ![[Pasted image 20250923152751.png]]
* RACCT - Sachkonto
* ACTIV - Betriebswirtschaftlicher Vorgang
* SBUKRS - Sendender Buchungskreis
* SPRCTR - Sendender Profitcenter
* REFDOCNR
* REFRYEAR
* REFDOCLN
* REFDOCCT
* REFACTIV
* AWTYP
* AWORG
* 
