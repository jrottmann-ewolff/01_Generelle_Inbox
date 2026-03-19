---
Bereich: sap
tags:
  - tabelle
  - kunden
  - hierarchie
---
Pflege geschieht in der Transaktion [[vdh1n]] und Anzeige in [[vdh2]]

(https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-members/customer-hierarchy-in-sap-hana/ba-p/13570980)

# Anwendungsfälle

* Report der Aufträge und Rechnungen eines Kunden innerhalb einer Hierarchie darstellt, so könnte man eine *standard Reporting Hierarchie* im SD nutzen ?
* Preise abhängig von einer bestimmten Gruppe: *Kundengruppe in den Stammdaten* ist sinnvoller als eine Kundenhierarchie, sollten aber die Preise oder Rabatte global über eine Hierarchie laufen, so kann man die Kundenhierarchie nutzen
* Kunde <-> Partner ist wichtig für die Hierarchie
*

## Preise und Discounts

* Können in jedem Hierarchie Knoten gepflegt werden, alle niedrigeren Knoten erben von denen darüber
* Beispiele, die geerbt werden können: Sales Org, Distribution Channel, Division*