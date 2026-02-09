# bit-agora

Personal plugin marketplace for Claude Code by [@fperezsorrosal](https://github.com/francisco-perez-sorrosal).

## Install

```bash
claude plugin marketplace add francisco-perez-sorrosal/bit-agora
```

Then install any plugin:

```bash
claude plugin install stockpile
claude plugin install i-am
```

## Available Plugins

| Plugin | Description | Repo |
| ------ | ----------- | ---- |
| [stockpile](https://github.com/francisco-perez-sorrosal/stockpile) | Investment research — ticker lookup, stock clustering, market data caching | `francisco-perez-sorrosal/stockpile` |
| [i-am](https://github.com/francisco-perez-sorrosal/ai-assistants) | Context engineering — skills, agents, rules, and commands | `francisco-perez-sorrosal/ai-assistants` |

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
