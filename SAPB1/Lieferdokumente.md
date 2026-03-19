---
Bereich: b1
tags:
  - tabellen
  - lieferung
---

Zusammenhang [[ODLN]] <-> [[DLN1]]

```SQL
SELECT
	*
FROM `DEV_channel_subsidiary_sapb1.cleaned_odln` AS odln
LEFT JOIN `DEV_channel_subsidiary_sapb1.cleaned_dln1` AS dln1
	USING (docentry, db_id)
WHERE
	TRUE
	AND odln.db_id = 30
	AND odln.posting_date >= '2026-01-01'
```
