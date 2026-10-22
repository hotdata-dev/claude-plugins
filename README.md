# Hotdata plugins for Claude Code

```
/plugin marketplace add hotdata-dev/claude-plugins
/plugin install hotdata-cli@hotdata
/plugin install hotdata-tabular-memory@hotdata
```

| Plugin | What it does |
|---|---|
| [`hotdata-cli`](https://github.com/hotdata-dev/hotdata-cli) | Teaches Claude the `hotdata` CLI. Checks for the CLI at session start and offers to install it if missing. |
| [`hotdata-tabular-memory`](https://github.com/hotdata-dev/hotdata-tabular-memory) | Makes Hotdata the default database for data too big for context. One database per project, shared definitions, results kept on the server. Adds the `hd` command, a session-start orientation hook and a large-file read guard. |

Each plugin lives in its own repository; this repo only lists them.
