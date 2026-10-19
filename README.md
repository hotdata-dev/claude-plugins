# Hotdata plugins for Claude Code

```
/plugin marketplace add hotdata-dev/claude-plugins
/plugin install hotdata-cli@hotdata
/plugin install hotdata-tabular-memory@hotdata
```

| Plugin | What it does |
|---|---|
| [`hotdata-cli`](https://github.com/hotdata-dev/hotdata-cli) | Teaches Claude the `hotdata` CLI. Checks for the CLI at session start and offers to install it if missing. |
| [`hotdata-tabular-memory`](https://github.com/hotdata-dev/hotdata-tabular-memory) | Gives agents one Hotdata database per project as shared memory: load large files with `hd load` instead of reading them into context, share definitions, and keep results on the server. Needs the `hotdata` CLI. |

Each plugin lives in its own repository; this repo only lists them.
