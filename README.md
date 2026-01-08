# Claude Code Plugins

Personal Claude Code plugin marketplace - LSPs, commands, agents, and tools.

## Plugins

| Plugin | Description |
|--------|-------------|
| `conform-lsp` | Svelte/Chameleon pattern enforcement LSP |
| `svelte-stack` | Svelte development LSP stack (svelte, typescript, tailwind, eslint) |

## Installation

Add the marketplace:
```bash
claude plugin marketplace add angelsen/claude-code-plugins
```

Install plugins:
```bash
claude plugin install conform-lsp@angelsen-plugins
claude plugin install svelte-stack@angelsen-plugins
```

## Requirements

For `svelte-stack`, install LSP servers via pacman (Arch Linux):
```bash
sudo pacman -S svelte-language-server typescript-language-server tailwindcss-language-server eslint-language-server
```

## License

MIT
