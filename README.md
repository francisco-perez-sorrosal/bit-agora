# bit-agora

Personal plugin marketplace for Claude Code by [@fperezsorrosal](https://github.com/francisco-perez-sorrosal).

## Install

```bash
claude plugin marketplace add francisco-perez-sorrosal/bit-agora
```

Then install any plugin `claude plugin install <plugin-name>`:

```bash
claude plugin install i-am
claude plugin install cv
claude plugin install stockpile
```

## Available Plugins

| Plugin | Description | Repo |
| ------ | ----------- | ---- |
| [i-am](https://github.com/francisco-perez-sorrosal/praxion) | My vision of operationalizing spec-driven development and context engineering (through skills, agents, rules, and commands) into a reliable, context-aware agentic execution environment. | `francisco-perez-sorrosal/praxion` |
| [cv](https://github.com/francisco-perez-sorrosal/cv-forge/tree/main/plugins/cv) | CV/Résumé (remote MCP + analysis/tailoring skills) | `francisco-perez-sorrosal/cv-forge` (`plugins/cv`) |
| [cv-forge](https://github.com/francisco-perez-sorrosal/cv-forge/tree/main/plugins/cv-forge) | CV maintainer tools (edit via PR, publish, deploy) | `francisco-perez-sorrosal/cv-forge` (`plugins/cv-forge`) |
| [stockpile](https://github.com/francisco-perez-sorrosal/stockpile) | Investment research — ticker lookup, stock clustering, market data caching | `francisco-perez-sorrosal/stockpile` |


## Managing

```bash
# List installed plugins
claude plugin list

# Update a plugin
claude plugin update stockpile

# Update marketplace catalog
claude plugin marketplace update bit-agora

# Remove marketplace
claude plugin marketplace remove bit-agora
```
