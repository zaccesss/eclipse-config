# Workflows

| Workflow | Runs on | What it does |
| --- | --- | --- |
| [`config-lint.yml`](config-lint.yml) | Push to `main`, every pull request | Checks every `prefs/` line is a `#` note or `key=value` with no key repeated. Checks the key binding XML parses with all 15 bindings. Shellchecks `apply.sh`, checks every `plugins.txt` line, runs `apply.sh` twice on a throwaway workspace to prove every key lands and the second run changes nothing, then parses `apply.ps1` with PowerShell |
| [`markdownlint.yml`](markdownlint.yml) | Push to `main`, every pull request | Lints every markdown file against [`.markdownlint.json`](../../.markdownlint.json) |

Both are also runnable manually via `workflow_dispatch` from the Actions tab.
