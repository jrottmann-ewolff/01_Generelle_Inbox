---
Bereich: Tools
tags:
  - ki
  - editor
---

## Fußnoten und Externe Links

## MCP Clients
{
  "mcpServers": {
    "dbt": {
      "command": "uvx dbt-mcp",
      "env": {
        "DBT_PROJECT_DIR": ".",
        "DBT_PATH": ".venv/bin/dbt",
        "DISABLE_DBT_CLI": "false",
        "DISABLE_SEMANTIC_LAYER": "true",
        "DISABLE_DISCOVERY": "true",
        "DISABLE_REMOTE": "true"
      }
    },
    "bigquery": {
      "command": "~/bigquery_mcp_toolbox/toolbox",
      "args": ["--prebuilt","bigquery","--stdio"],
      "env": {
        "BIGQUERY_PROJECT": "cogent-spirit-218208"
      }
    }
  }
}

