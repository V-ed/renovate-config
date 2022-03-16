# renovate-config

Shared [Renovate Dependency Management](https://docs.renovatebot.com/config-presets/) configurations for my projects.

## Usage

`.github/renovate.json`

```jsonc
{
  "extends": ["github>V-ed/renovate-config"]
  // Optional Overrides
}
```

## Usage in libraries

`.github/renovate.json`

```jsonc
{
  "extends": ["github>V-ed/renovate-config:lib"]
  // Optional Overrides
}
```
