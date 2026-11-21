# @archgate/renovate-config

Extends [`BarretoTech/renovate-config`](https://github.com/BarretoTech/renovate-config), the shared Renovate preset of the Barreto Tech enterprise, without changes. Repositories in `archgate` that extend `local>archgate/renovate-config` get exactly the enterprise rules.

Rules are edited in `BarretoTech/renovate-config`, never here. New repositories extend that preset directly:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["local>BarretoTech/renovate-config"]
}
```
