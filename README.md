# renovate-config

> Common renovate configuration used by [@kloud-cnf](https://github.com/kloud-cnf) projects

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [Usage](#usage)
- [Resources](#resources)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

---

## Usage

[Organization level preset](https://docs.renovatebot.com/config-presets/#organization-level-presets)
```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["local>kloud-cnf/renovate-config"]
}
```

Use outwith organization

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>kloud-cnf/renovate-config"]
}
```

---

## Resources
- [Renovate > Configuration Schema](https://docs.renovatebot.com/configuration-options/)
- [Renovate > Config Presets](https://docs.renovatebot.com/config-presets/)
