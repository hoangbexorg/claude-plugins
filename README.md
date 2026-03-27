# ogngnaoh-plugins

Custom Claude Code plugins.

## Installation

Add this marketplace to your Claude Code settings:

```json
{
  "extraKnownMarketplaces": {
    "ogngnaoh-plugins": {
      "source": { "source": "github", "repo": "ogngnaoh/claude-plugins" }
    }
  }
}
```

Then install any plugin:

```
/plugin install plugin-scout
```

## Plugins

| Plugin | Description |
|--------|-------------|
| **plugin-scout** | Browse all configured Claude Code marketplaces and recommend plugins for your workflow |
