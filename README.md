# renovate-config

Shared [Renovate Dependency Management](https://docs.renovatebot.com/config-presets/) configurations for my projects.

## Usage

`.github/renovate.json`

```json
{
  "extends": ["github>V-ed/renovate-config"]
  // Optionnal Overrides
}
```

## Usage in libraries

`.github/renovate.json`

```json
{
  "extends": ["github>V-ed/renovate-config:lib"]
  // Optionnal Overrides
}
```
