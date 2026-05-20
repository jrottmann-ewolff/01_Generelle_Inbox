---
Bereich: python
tags:
	- virtual
	- environment
---
# Howto

## Prerequisites
1. Install pipx
2. Install poetry
   ```bash
   > pipx install poetry
   ```

## Nutzen in einem Projekt

### Neues Projekt
1. Neues Projekt erstellen
   ```bash
   > poetry new new_project
   ```
2. Die `pyproject.toml` ist wesentlich
   z. B. die Einschränkung der Python-Version
   ```
   [project]
   requires-python = ">=3.13"
   ```
### Bestehendes Projekt
1. Installieren
   ```bash
   > poetry install
   ```
