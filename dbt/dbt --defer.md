---
Bereich: dbt
tags:
  - development
  - dbt
---
# Workflow

## resource-type
* seed
* snapshot
* model
* test

## Selektoren
```
--select state:modified

```

## defer
### Kompiliere den "prod" Code
```shell
> dbt compile --target-path target_prod -t prod
```

### Nutze den kompilierten "prod" code
```shell
> dbt run --defer --state target_prod --favor-state
```

Hier kann man die üblichen [[dbt --select|Selektoren]] nutzen.

### `build` nur für die geänderten Modelle und alle abhängigen
```shell
> git checkout master  
> dbt compile --target-path taret_prod -t prod
# dbt-defer-compile  als shortcut
> git - 
# zurück zum ursprünglichen Modell
> dbt build --resource-type seed snapshot model --defer --state target_prod --favor-state --select state:modified+,+<zielmodell>
```