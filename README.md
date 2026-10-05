# Game design data (generated from Google Sheets)

Do not edit generated files. They are written by `python tools/import_data.py` (game-design repo,
`tools/` = SilverLegendLtd/designer-data-tools) from the sheet exports in Drive `Design/exports/`.

| Path | What | Edited by hand? |
|---|---|---|
| `Attribute.json` | stat Tag registry, designed with the Unreal lead | yes (until it has a sheet) |
| `sources/` | inputs with no sheet yet: `BaseBuildingTags.json` (Tag registry), `Base_Layout.csv`, `Starting_Resources.csv`, `Leisure Activity Movement.csv` | yes (until they have a sheet) |
| `basebuilding/*.json`, `basebuilding/schemas/` | base-building tables (Buildings, Upgrades, Work, ResearchTree, LeisureActivities, StartingResources, BaseLayout, StatTags, TagRegistry) | no |
| `character/Background*.json` | Background Data sheet (life paths) | no |
| `docs/basebuilding/*.md` | generated Tag registry docs | no |

Consumers copy these files (see `tools/consumers.json`); `import_data.py --check` reports drift.
