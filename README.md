# hoangbexorg-plugins

Custom Claude Code plugins.

## Installation

Add this marketplace to your Claude Code settings:

```json
{
  "extraKnownMarketplaces": {
    "hoangbexorg-plugins": {
      "source": { "source": "github", "repo": "hoangbexorg/claude-plugins" }
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
