# Game design data (generated from Google Sheets)

Do not edit generated files. They are written by `python tools/import_data.py` (game-design repo,
`tools/` = SilverLegendLtd/designer-data-tools) from the sheet exports in Drive `Design/exports/`.

All data lives under `Bronze/`; paths below are relative to it.

| Path | What | Edited by hand? |
|---|---|---|
| `Attribute.json` | stat Tag registry, designed with the Unreal lead | yes (until it has a sheet) |
| `Sources/` | inputs with no sheet yet: `BaseBuildingTags.json` (Tag registry), `Base_Layout.csv`, `Starting_Resources.csv`, `Leisure Activity Movement.csv`, and the dialogue CSVs (`Dialogue Topics List - MasterList.csv`, `Gameplay Effects for Dialogue System - *.csv`; the DialogueGenerator reads them from here). All CSVs live in this folder. | yes (until they have a sheet) |
| `BaseBuilding/*.json`, `BaseBuilding/Schemas/` | base-building tables (Buildings, Upgrades, Work, ResearchTree, LeisureActivities, StartingResources, BaseLayout, StatTags, TagRegistry) | no |
| `BaseBuilding/Station.json` | station Tag list (feeds `Config/Tags/Station.ini`) | yes (until it has a sheet) |
| `BaseBuilding/Legacy/` | `WorkRecipes.json`, `ResearchRecipes.json`: the runtime recipe rows behind `DT_BronzeWorks`; replaced by `Work.json` / `ResearchTree.json` when the C++ moves to the new model | yes |
| `Character/Background*.json` | Background Data sheet (life paths) | no |
| `Character/Faction.json`, `Trait.json`, `MoodValue.json`, `MoodSegment.json`, `MBTI_Type.json`, `MBTI_Dimension.json` | character reference data. Tags have no `Character.` prefix and rows have no `SetByCallerTag` (code derives `SetByCaller.` + `Tag`). `MoodSegment`: the 12 mood segments (angle, length, description) | yes (until they have a sheet) |
| `Dialogue/Topic_BronzeBase.json` | the BronzeBase topic list | yes |
| `GameplayEffect/GameplayEffect_{Background,Belief,MBTI,MBTIType,Mood}.json` | written by the DialogueGenerator (`update_design_data.py`) from the dialogue effect CSVs in `Sources/`; do not edit | no |
| `GameplayEffect/GameplayEffect.json`, `GameplayEffect_Dialogue.json`, `GameplayEffect_Neutral.json` | dialogue effect definitions with no CSV (`_Dialogue` is a placeholder; its skills come from `Attribute.json`) | yes |
| `Docs/BaseBuilding/*.md` | generated Tag registry docs | no |

GreyGame reads this folder in place (it is the `GreyGame/DesignerData` submodule); other consumers copy files (see `tools/consumers.json`). `import_data.py --check` reports drift.
