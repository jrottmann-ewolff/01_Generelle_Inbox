---
Bereich: sap, theobald
tags:
  - daten
  - ssis
  - theobald
  - sap
  - transfer
---

# TL;DR

Wir nutzen Queries um Daten effizient aus dem SAP abzuziehen, in dem wir in **Infosets** den Join von Tabellen erstellen, so dass Tabellen, die eigentlich keinen Index haben, der für einen inkrementellen Load geeignet ist, mit Tabellen verknüpft werden, die einen Index oder Zeitstempel haben.

# Beschreibung

## SAP Seite

Erzeuge in der [[sq03]] eine Benutzergruppe und füge Benutzer hinzu. In der [[sq02]] wird anschließend das Infoset definiert und zum Schluss erstellt man in der [[sq01]] die eigentliche Query.

## SSIS / Theobald

Benutze den **Extract Query** Baustein. Wähle dabei die passende Benutzergruppe und Query aus.

# Konkret bei uns

## AW

Benutzergruppe `ZDWH` **DWH Export**.
