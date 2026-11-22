# The Rogue Roadmap — Claude Code plugins

> [English](#english) · [Español](#español) · [Français](#français)

## English

Plugins and skills for Claude Code that I build while exploring AI agents in real software
development. Some are stable; others are still under construction. This repository holds the catalog;
each plugin lives in its own repository.

### Install

```text
/plugin marketplace add therogueroadmap/marketplace
/plugin install <plugin>@therogueroadmap
```

### Catalog

| Plugin | Status | Repository |
|---|---|---|
| `rogue-toolkit` | Stable | [therogueroadmap/rogue-toolkit](https://github.com/therogueroadmap/rogue-toolkit) |
| `rogue-workflow` | In progress | [therogueroadmap/rogue-workflow](https://github.com/therogueroadmap/rogue-workflow) |
| `multisession-dev-plugin` | In progress (needs `rogue-workflow`) | [therogueroadmap/multisession-dev-plugin](https://github.com/therogueroadmap/multisession-dev-plugin) |

### Mods

Mods change Claude's own interface (themes, backdrops, panels, commands). They live in their own
catalog, [therogueroadmap/rogue-mods](https://github.com/therogueroadmap/rogue-mods), where each
folder is a plugin you install on its own:

```text
/plugin marketplace add therogueroadmap/rogue-mods
/plugin install <mod>@rogue-mods
```

| Mod | Kind | Status |
|---|---|---|
| `rasenshuriken` | Theme | In progress |
| `sharingan` | Theme | In progress |
| `rogue-road` | Theme | Stable |

### Under construction

Repositories that are public but not in the catalog yet are listed on the
[organization page](https://github.com/therogueroadmap).

## Español

Plugins y skills para Claude Code que construyo mientras exploro agentes de IA en el desarrollo
de software real. Algunos son estables; otros siguen en construcción. Este repositorio contiene el
catálogo; cada plugin vive en su propio repositorio. La instalación y el catálogo están en la
sección en inglés.

## Français

Des plugins et des skills pour Claude Code que je construis en explorant les agents d'IA dans le
développement logiciel réel. Certains sont stables, d'autres sont encore en construction. Ce dépôt
contient le catalogue ; chaque plugin vit dans son propre dépôt. L'installation et le
catalogue sont dans la section anglaise.

## License

MIT
