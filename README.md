# Alter Web

Build Flutter déployé sur [alter.visialis.fr](https://alter.visialis.fr) via GitHub Pages.

> Ce dépôt contient uniquement les artefacts de build de l'interface web d'Alter. Le code source est dans [VISIALIS/phoenix_0](https://github.com/VISIALIS/phoenix_0).

## Écosystème Alter

Alter est un analyseur d'adresses EVM multi-réseaux, disponible sur 5 interfaces :

| # | Interface | Type | Accès |
|---|-----------|------|-------|
| 1 | alter-mcp | Serveur MCP | `brew install alter-mcp` |
| 2 | alter-cli | CLI | `brew install alter-cli` |
| 3 | Alter Web | Application web | [alter.visialis.fr](https://alter.visialis.fr) |
| 4 | Alter Desktop | macOS / Windows / Linux | `brew install --cask alter` |
| 5 | Alter Mobile | iOS / Android | App Store / Google Play |

## Quick Start

Ouvrir l'application web :

```
https://alter.visialis.fr
```

Exemple d'utilisation en CLI (équivalent headless) :

```bash
brew install alter-cli
alter-cli classify 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2
```

## Documentation

- Source : [VISIALIS/phoenix_0](https://github.com/VISIALIS/phoenix_0)
- Formule Homebrew : [VISIALIS/homebrew-alter](https://github.com/VISIALIS/homebrew-alter)
- Politique de confidentialité : [alter.visialis.fr/privacy.html](https://alter.visialis.fr/privacy.html)

## Déploiement

Ce dépôt est mis à jour automatiquement par la CD pipeline du repo `phoenix_0` à chaque release. Les commits directs ici ne sont pas recommandés — éditer la source dans `phoenix_0` et laisser la CD régénérer le build.
