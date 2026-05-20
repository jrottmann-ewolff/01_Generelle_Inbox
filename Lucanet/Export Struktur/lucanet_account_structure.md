---
Bereich: lucanet
tags:
 - lucanet
 - dwh
 - export
 - tabelle
 - konten
 - hierarchie
---

## Beschreibung
Konto -> Kontentyp und Hierarchie

## Felder und Zusammenhang

* [[lucanet_workspace|workspace_id]] (GuV vs Bilanz)
* **report_element_id**
* **account_name** (Text des Kontos)
* **source_account_id** (vor allem bei renamings?)
* **child_index** ???
* **period_type** (Duration vs. Instant vs. InstantCarryForward)
* **balance_type** (Credit vs. Debit)
* **transaction_type_category_id** (1510 vs. 1520 vs. 1530 vs. 1540)
* **is_formula**
* **is_total_line**
* **is_time_series**
* **is_separator**
* **general_ledger_account**
* **account_level_N_id** / **account_level_N** / **account_level_N_ci**
	* Level 1: Bilanz vs GuV
	* Level 2-6: 
		* Bilanz: Aktiva/Passiva danach übrige ebenen
		* GuV: Knoteneben 1-4
