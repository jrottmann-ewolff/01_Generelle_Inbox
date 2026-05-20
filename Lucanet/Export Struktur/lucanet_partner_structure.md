---
Bereich: lucanet
tags:
 - lucanet
 - dwh
 - export
 - tabelle
 - partner
 - hierarchie
---

## Beschreibung
Konto -> Kontentyp und Hierarchie

## Felder und Zusammenhang
* **partner_id** - Link zu [[lucanet_facts]]
* **partner_name** 
        child_index,
        is_default_partner,
        partner_level_1_id,
        partner_level_1,
        partner_level_1_ci,
        partner_level_2_id,
        partner_level_2,
        partner_level_2_ci,
* **partner_level_3_id**, **partner_level_3**, **partner_level_3_ci** liefern keine neuen Infos
