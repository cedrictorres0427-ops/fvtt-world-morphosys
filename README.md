# Morphosys

Monde Foundry VTT `morphosys`, système `metamorphosys`.

## Installation

Dans Foundry : **Mondes** → **Installer** → coller ce lien dans « URL du manifeste » :

```
https://github.com/cedrictorres0427-ops/fvtt-world-morphosys/releases/latest/download/world.json
```

## Publier une nouvelle version

1. Augmenter `version` dans `world.json` et remplacer la version dans `download`.
2. Commit, puis tag `v<version>` poussé sur GitHub : l'action « Release » construit le zip et la release.
