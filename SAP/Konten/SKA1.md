---
Bereich: sap
tags:
	- sachkonto
	- tabelle
	- stammdaten
---

Hier sind die Stammdaten der Sachkonten eingetragen. die Pflege passiert über die Transaktion [[fs00 (oder 03?)]].

## Wichtige Felder

|Feld|Bedeutung|
|---|---|
|`KTOPL`|Kontenplan|
|`SAKNR`|Sachkontonummer|
|`BILKT`|Konzernkontonummer|
|`XBILK`|Kennzeichen: Konto ist Bestandskonto?|
|`GVTYP`|Erfolgskontentyp|
|`KTOKS`| Kontengruppe der Sachkonten (KW: OPKT -> Sachkonto OP-geführt, SAKO -> Sachkonto allgemein)|
|`FUNC_AREA`|Funktionsbereich|

Weitere Stammdaten der Sachkonten sind buchungskreisabhängig und finden sich in der [[SKB1]].