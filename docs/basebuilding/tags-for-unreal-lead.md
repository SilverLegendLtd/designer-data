# Proposed Gameplay Tags for the Unreal lead

Generated from `design/data/sources/BaseBuildingTags.json` (game-design). The leaf names are our proposal: please review. Stat Tags come from `Attribute.json` and are not listed. New namespaces to confirm: `BB.Upgrade.*`, `BB.Buff.*`, `BB.Passive.*`, `BB.Mood.*`, `BB.Area.*`, `BB.Requirement.*`, `BB.Phase.*`, `BB.WorkType.*`, `BB.Layout.Kind.*`, `Inventory.Resource.*`, `Inventory.Item.*`. `BB.Building.Size.*` already exists (our `Large` is your `Big`).

## Building

```ini
GameplayTagList=(Tag="BB.Building.SmallPowerGenerator",DevComment="Small Power Generator")
GameplayTagList=(Tag="BB.Building.MediumPowerGenerator",DevComment="Medium Power Generator")
GameplayTagList=(Tag="BB.Building.LargePowerGenerator",DevComment="Large Power Generator")
GameplayTagList=(Tag="BB.Building.Garden",DevComment="Garden")
GameplayTagList=(Tag="BB.Building.Bar",DevComment="Bar")
GameplayTagList=(Tag="BB.Building.Library",DevComment="Library")
GameplayTagList=(Tag="BB.Building.HobbyWorkshop",DevComment="Hobby Workshop")
GameplayTagList=(Tag="BB.Building.Sauna",DevComment="Sauna")
GameplayTagList=(Tag="BB.Building.ShootingClub",DevComment="Shooting Club")
```

## Station

```ini
GameplayTagList=(Tag="BB.Station.MedicalStation",DevComment="Medical Station")
GameplayTagList=(Tag="BB.Station.GuardStation",DevComment="Guard Station")
GameplayTagList=(Tag="BB.Station.FoodStation",DevComment="Food Station")
GameplayTagList=(Tag="BB.Station.MechanicalStation",DevComment="Mechanical Station")
GameplayTagList=(Tag="BB.Station.ResearchStation",DevComment="Research Station")
GameplayTagList=(Tag="BB.Station.CommunicationStation",DevComment="Communication Station")
```

## Upgrade

```ini
GameplayTagList=(Tag="BB.Upgrade.ExpertMedicalStation",DevComment="Expert Medical Station")
GameplayTagList=(Tag="BB.Upgrade.MedicalStationInfectedTreatmentUpgrade",DevComment="Medical Station Infected Treatment Upgrade")
GameplayTagList=(Tag="BB.Upgrade.MedicalStationWoundTreatmentUpgrade",DevComment="Medical Station Wound Treatment Upgrade")
GameplayTagList=(Tag="BB.Upgrade.ExpertGuardStation",DevComment="Expert Guard Station")
GameplayTagList=(Tag="BB.Upgrade.GuardStationAmmunitionUpgrade",DevComment="Guard Station Ammunition Upgrade")
GameplayTagList=(Tag="BB.Upgrade.GuardStationGuardingUpgrade",DevComment="Guard Station Guarding Upgrade")
GameplayTagList=(Tag="BB.Upgrade.ExpertFoodStation",DevComment="Expert Food Station")
GameplayTagList=(Tag="BB.Upgrade.FoodStationCombatFoodUpgrade",DevComment="Food Station Combat Food Upgrade")
GameplayTagList=(Tag="BB.Upgrade.FoodStationExpeditionFoodUpgrade",DevComment="Food Station Expedition Food Upgrade")
GameplayTagList=(Tag="BB.Upgrade.ExpertMechanicalStation",DevComment="Expert Mechanical Station")
GameplayTagList=(Tag="BB.Upgrade.MechanicalStationTechCraftingUpgrade",DevComment="Mechanical Station Tech Crafting Upgrade")
GameplayTagList=(Tag="BB.Upgrade.MechanicalStationNatureCraftingUpgrade",DevComment="Mechanical Station Nature Crafting Upgrade")
GameplayTagList=(Tag="BB.Upgrade.ExpertResearchStation",DevComment="Expert Research Station")
GameplayTagList=(Tag="BB.Upgrade.ResearchStationInfectedUpgrade",DevComment="Research Station Infected Upgrade")
GameplayTagList=(Tag="BB.Upgrade.ResearchStationAlienUpgrade",DevComment="Research Station Alien Upgrade")
GameplayTagList=(Tag="BB.Upgrade.CommunicationStationRadioUpgrade",DevComment="Communication Station Radio Upgrade")
GameplayTagList=(Tag="BB.Upgrade.CommunicationStationTradingUpgrade",DevComment="Communication Station Trading Upgrade")
GameplayTagList=(Tag="BB.Upgrade.CommunicationStationScoutingUpgrade",DevComment="Communication Station Scouting Upgrade")
```

## Job

```ini
GameplayTagList=(Tag="BB.Job.MedicalStation.ReceiveTreatment",DevComment="Medical Station / Receive Treatment")
GameplayTagList=(Tag="BB.Job.MedicalStation.TreatNegativePhysicalTrait",DevComment="Medical Station / Treat Negative Physical Trait")
GameplayTagList=(Tag="BB.Job.MedicalStation.TreatWounds",DevComment="Medical Station / Treat Wounds")
GameplayTagList=(Tag="BB.Job.ExpertMedicalStation.ReceiveTreatment",DevComment="Expert Medical Station / Receive Treatment")
GameplayTagList=(Tag="BB.Job.ExpertMedicalStation.TreatNegativePhysicalTrait",DevComment="Expert Medical Station / Treat Negative Physical Trait")
GameplayTagList=(Tag="BB.Job.ExpertMedicalStation.TreatWounds",DevComment="Expert Medical Station / Treat Wounds")
GameplayTagList=(Tag="BB.Job.ExpertMedicalStation.TreatNegativeMentalTrait",DevComment="Expert Medical Station / Treat Negative Mental Trait")
GameplayTagList=(Tag="BB.Job.MedicalStationInfectedTreatmentUpgrade.ReceiveTreatment",DevComment="Medical Station Infected Treatment Upgrade / Receive Treatment")
GameplayTagList=(Tag="BB.Job.MedicalStationInfectedTreatmentUpgrade.TreatNanobotInfection",DevComment="Medical Station Infected Treatment Upgrade / Treat Nanobot Infection")
GameplayTagList=(Tag="BB.Job.MedicalStationWoundTreatmentUpgrade.TreatWounds",DevComment="Medical Station Wound Treatment Upgrade / Treat Wounds")
GameplayTagList=(Tag="BB.Job.GuardStation.Guard",DevComment="Guard Station / Guard")
GameplayTagList=(Tag="BB.Job.ExpertGuardStation.Guard",DevComment="Expert Guard Station / Guard")
GameplayTagList=(Tag="BB.Job.ExpertGuardStation.StudyWeapon",DevComment="Expert Guard Station / Study Weapon")
GameplayTagList=(Tag="BB.Job.ExpertGuardStation.CraftAmmunition",DevComment="Expert Guard Station / Craft Ammunition")
GameplayTagList=(Tag="BB.Job.GuardStationAmmunitionUpgrade.CraftAmmunition",DevComment="Guard Station Ammunition Upgrade / Craft Ammunition")
GameplayTagList=(Tag="BB.Job.GuardStationGuardingUpgrade.Guard",DevComment="Guard Station Guarding Upgrade / Guard")
GameplayTagList=(Tag="BB.Job.FoodStation.CookFood",DevComment="Food Station / Cook Food")
GameplayTagList=(Tag="BB.Job.FoodStation.PrepareExpeditionFood",DevComment="Food Station / Prepare Expedition Food")
GameplayTagList=(Tag="BB.Job.FoodStation.StudyPlant",DevComment="Food Station / Study Plant")
GameplayTagList=(Tag="BB.Job.MechanicalStation.CraftMechanicalItem",DevComment="Mechanical Station / Craft Mechanical Item")
GameplayTagList=(Tag="BB.Job.MechanicalStation.RecycleItem",DevComment="Mechanical Station / Recycle Item")
GameplayTagList=(Tag="BB.Job.ResearchStation.CreateResearchPoints",DevComment="Research Station / Create Research points")
GameplayTagList=(Tag="BB.Job.ResearchStation.ResearchSpend",DevComment="Research Station / (research spend)")
GameplayTagList=(Tag="BB.Job.ExpertResearchStation.CreateResearchPoints",DevComment="Expert Research Station / Create Research points")
GameplayTagList=(Tag="BB.Job.ResearchStationInfectedUpgrade.ResearchSpend",DevComment="Research Station Infected Upgrade / (research spend)")
GameplayTagList=(Tag="BB.Job.ResearchStationAlienUpgrade.ResearchSpend",DevComment="Research Station Alien Upgrade / (research spend)")
GameplayTagList=(Tag="BB.Job.CommunicationStation.Trade",DevComment="Communication Station / Trade")
GameplayTagList=(Tag="BB.Job.CommunicationStation.TradeMission",DevComment="Communication Station / Trade Mission")
GameplayTagList=(Tag="BB.Job.CommunicationStationRadioUpgrade.CallSurvivors",DevComment="Communication Station Radio Upgrade / Call Survivors")
GameplayTagList=(Tag="BB.Job.CommunicationStationRadioUpgrade.CallTraders",DevComment="Communication Station Radio Upgrade / Call Traders")
GameplayTagList=(Tag="BB.Job.CommunicationStationTradingUpgrade.CallTraders",DevComment="Communication Station Trading Upgrade / Call Traders")
GameplayTagList=(Tag="BB.Job.CommunicationStationTradingUpgrade.Trade",DevComment="Communication Station Trading Upgrade / Trade")
GameplayTagList=(Tag="BB.Job.CommunicationStationTradingUpgrade.TradeMission",DevComment="Communication Station Trading Upgrade / Trade Mission")
GameplayTagList=(Tag="BB.Job.CommunicationStationScoutingUpgrade.Scout",DevComment="Communication Station Scouting Upgrade / Scout")
GameplayTagList=(Tag="BB.Job.ExpertGuardStation.HighDamageAmmunition",DevComment="Expert Guard Station / High Damage Ammunition")
GameplayTagList=(Tag="BB.Job.CommunicationStation.BaseCoordination",DevComment="Communication Station / Base Coordination")
GameplayTagList=(Tag="BB.Job.CommunicationStationRadioUpgrade.BaseCoordination",DevComment="Communication Station Radio Upgrade / Base Coordination")
GameplayTagList=(Tag="BB.Job.ExpertFoodStation.GrowBeans",DevComment="Expert Food Station / Grow Beans")
GameplayTagList=(Tag="BB.Job.ExpertMechanicalStation.MaintainMachinery",DevComment="Expert Mechanical Station / Maintain Machinery")
GameplayTagList=(Tag="BB.Job.ExpertMedicalStation.UpkeepHealthProtocols",DevComment="Expert Medical Station / Upkeep Health Protocols")
GameplayTagList=(Tag="BB.Job.FoodStation.GrowPotatoes",DevComment="Food Station / Grow Potatoes")
GameplayTagList=(Tag="BB.Job.MechanicalStation.MaintainMachinery",DevComment="Mechanical Station / Maintain Machinery")
GameplayTagList=(Tag="BB.Job.MechanicalStation.ExpandBase",DevComment="Mechanical Station / Expand Base")
GameplayTagList=(Tag="BB.Job.MedicalStation.UpkeepHealthProtocols",DevComment="Medical Station / Upkeep Health Protocols")
```

## Research

```ini
GameplayTagList=(Tag="BB.Research.ExpertGuardStation",DevComment="Expert Guard Station")
GameplayTagList=(Tag="BB.Research.Ammunition",DevComment="Ammunition")
GameplayTagList=(Tag="BB.Research.Guarding",DevComment="Guarding")
GameplayTagList=(Tag="BB.Research.AdvancedAmmunition",DevComment="Advanced Ammunition")
GameplayTagList=(Tag="BB.Research.AdvancedGuarding",DevComment="Advanced Guarding")
GameplayTagList=(Tag="BB.Research.HeavyWeapons",DevComment="Heavy Weapons")
GameplayTagList=(Tag="BB.Research.DefensiveTurrets",DevComment="Defensive Turrets")
GameplayTagList=(Tag="BB.Research.EnhancedBaseSafety",DevComment="Enhanced Base Safety")
GameplayTagList=(Tag="BB.Research.HighlyAdvancedFirearms",DevComment="Highly Advanced Firearms")
GameplayTagList=(Tag="BB.Research.CriticalDamage",DevComment="Critical Damage")
GameplayTagList=(Tag="BB.Research.ExpeditionHunting",DevComment="Expedition Hunting")
GameplayTagList=(Tag="BB.Research.ExpertMedicalStation",DevComment="Expert Medical Station")
GameplayTagList=(Tag="BB.Research.WoundTreatment",DevComment="Wound Treatment")
GameplayTagList=(Tag="BB.Research.InfectedTreatment",DevComment="Infected Treatment")
GameplayTagList=(Tag="BB.Research.AdvancedWoundTreatment",DevComment="Advanced Wound Treatment")
GameplayTagList=(Tag="BB.Research.AdvancedInfectedTreatment",DevComment="Advanced Infected Treatment")
GameplayTagList=(Tag="BB.Research.Autopsies",DevComment="Autopsies")
GameplayTagList=(Tag="BB.Research.EnhancedSurvivorWellBeing",DevComment="Enhanced Survivor Well-Being")
GameplayTagList=(Tag="BB.Research.MentalResilienceTraining",DevComment="Mental Resilience Training")
GameplayTagList=(Tag="BB.Research.HealthKits",DevComment="Health Kits")
GameplayTagList=(Tag="BB.Research.SabotageEnemyFoodSupply",DevComment="Sabotage Enemy Food Supply")
GameplayTagList=(Tag="BB.Research.HigherComfortFromFood",DevComment="Higher Comfort from Food")
GameplayTagList=(Tag="BB.Research.BetterExpeditionLoot",DevComment="Better Expedition Loot")
GameplayTagList=(Tag="BB.Research.AdvancedCombatFood",DevComment="Advanced Combat Food")
GameplayTagList=(Tag="BB.Research.AdvancedExpeditionFood",DevComment="Advanced Expedition Food")
GameplayTagList=(Tag="BB.Research.CombatFood",DevComment="Combat Food")
GameplayTagList=(Tag="BB.Research.ExpeditionFood",DevComment="Expedition Food")
GameplayTagList=(Tag="BB.Research.ExpertFoodStation",DevComment="Expert Food Station")
GameplayTagList=(Tag="BB.Research.ExpertResearchStation",DevComment="Expert Research Station")
GameplayTagList=(Tag="BB.Research.InfectedResearch",DevComment="Infected Research")
GameplayTagList=(Tag="BB.Research.AlienResearch",DevComment="Alien Research")
GameplayTagList=(Tag="BB.Research.AdvancedInfectedResearch",DevComment="Advanced Infected Research")
GameplayTagList=(Tag="BB.Research.AdvancedAlienResearch",DevComment="Advanced Alien Research")
GameplayTagList=(Tag="BB.Research.HumanSuitableNanobots",DevComment="Human-Suitable Nanobots")
GameplayTagList=(Tag="BB.Research.MoreChoicesFromAlienArtefacts",DevComment="More Choices from Alien Artefacts")
GameplayTagList=(Tag="BB.Research.BetterResearchOutcomes",DevComment="Better Research Outcomes")
GameplayTagList=(Tag="BB.Research.ResearchRobots",DevComment="Research Robots")
GameplayTagList=(Tag="BB.Research.AlienCommunications",DevComment="Alien Communications")
GameplayTagList=(Tag="BB.Research.NanobotPharmaceuticals",DevComment="Nanobot Pharmaceuticals")
GameplayTagList=(Tag="BB.Research.PsycheReprogramming",DevComment="Psyche Reprogramming")
GameplayTagList=(Tag="BB.Research.Distilling",DevComment="Distilling")
GameplayTagList=(Tag="BB.Research.RenewableEnergySources",DevComment="Renewable Energy Sources")
GameplayTagList=(Tag="BB.Research.BetterCraftingOutcomes",DevComment="Better Crafting Outcomes")
GameplayTagList=(Tag="BB.Research.HighQualityGear",DevComment="High Quality Gear")
GameplayTagList=(Tag="BB.Research.AdvancedNatureCrafting",DevComment="Advanced Nature Crafting")
GameplayTagList=(Tag="BB.Research.AdvancedTechCrafting",DevComment="Advanced Tech Crafting")
GameplayTagList=(Tag="BB.Research.NatureCrafting",DevComment="Nature Crafting")
GameplayTagList=(Tag="BB.Research.TechCrafting",DevComment="Tech Crafting")
GameplayTagList=(Tag="BB.Research.ExpertMechanicalStation",DevComment="Expert Mechanical Station")
GameplayTagList=(Tag="BB.Research.RadioStation",DevComment="Radio Station")
GameplayTagList=(Tag="BB.Research.Trading",DevComment="Trading")
GameplayTagList=(Tag="BB.Research.Scouting",DevComment="Scouting")
GameplayTagList=(Tag="BB.Research.AdvancedTrading",DevComment="Advanced Trading")
GameplayTagList=(Tag="BB.Research.AdvancedScouting",DevComment="Advanced Scouting")
GameplayTagList=(Tag="BB.Research.BetterTraderGoods",DevComment="Better Trader Goods")
GameplayTagList=(Tag="BB.Research.CommunityCohesion",DevComment="Community Cohesion")
GameplayTagList=(Tag="BB.Research.HigherDiscoveryOfPointsOfInterest",DevComment="Higher Discovery of Points of Interest")
GameplayTagList=(Tag="BB.Research.HighlyAdvancedCommunication",DevComment="Highly Advanced Communication")
GameplayTagList=(Tag="BB.Research.Optics",DevComment="Optics")
```

## Resource

```ini
GameplayTagList=(Tag="Inventory.Resource.Metal",DevComment="Metal")
GameplayTagList=(Tag="Inventory.Resource.Wires",DevComment="Wires")
GameplayTagList=(Tag="Inventory.Resource.Plastic",DevComment="Plastic")
GameplayTagList=(Tag="Inventory.Resource.Fuel",DevComment="Fuel")
GameplayTagList=(Tag="Inventory.Resource.Food",DevComment="Food")
```

## Item

```ini
GameplayTagList=(Tag="Inventory.Item.HighDamageAmmunition",DevComment="High Damage Ammunition")
GameplayTagList=(Tag="Inventory.Item.Potatoes",DevComment="Potatoes")
GameplayTagList=(Tag="Inventory.Item.Mushrooms",DevComment="Mushrooms")
GameplayTagList=(Tag="Inventory.Item.Beans",DevComment="Beans")
GameplayTagList=(Tag="Inventory.Item.CannedFood",DevComment="Canned Food")
GameplayTagList=(Tag="Inventory.Item.DriedMeat",DevComment="Dried Meat")
GameplayTagList=(Tag="Inventory.Item.FlourSack",DevComment="Flour Sack")
GameplayTagList=(Tag="Inventory.Item.RationPack",DevComment="Ration Pack")
GameplayTagList=(Tag="Inventory.Item.FreshMeat",DevComment="Fresh Meat")
GameplayTagList=(Tag="Inventory.Item.AlienFruit",DevComment="Alien Fruit")
```

## Buff

```ini
GameplayTagList=(Tag="BB.Buff.WellBeing",DevComment="Well-Being")
GameplayTagList=(Tag="BB.Buff.Safety",DevComment="Safety")
GameplayTagList=(Tag="BB.Buff.Survival",DevComment="Survival")
GameplayTagList=(Tag="BB.Buff.Tech",DevComment="Tech")
GameplayTagList=(Tag="BB.Buff.Science",DevComment="Science")
GameplayTagList=(Tag="BB.Buff.Unity",DevComment="Unity")
```

## Passive

```ini
GameplayTagList=(Tag="BB.Passive.HigherComfortFromFood",DevComment="Higher Comfort From Food")
GameplayTagList=(Tag="BB.Passive.CommunicationBonuses",DevComment="Communication Bonuses")
GameplayTagList=(Tag="BB.Passive.MentalResiliencePassiveBonus",DevComment="Mental Resilience Passive Bonus")
```

## Mood

```ini
GameplayTagList=(Tag="BB.Mood.Arousal",DevComment="arousal")
GameplayTagList=(Tag="BB.Mood.Valence",DevComment="valence")
```

## Area

```ini
GameplayTagList=(Tag="BB.Area.SmallBuildingSlot",DevComment="Small Building Slot")
GameplayTagList=(Tag="BB.Area.MediumBuildingSlot",DevComment="Medium Building Slot")
GameplayTagList=(Tag="BB.Area.LargeBuildingSlot",DevComment="Large Building Slot")
GameplayTagList=(Tag="BB.Area.WorkStation",DevComment="Work Station")
```

## Requirement

```ini
GameplayTagList=(Tag="BB.Requirement.Patient",DevComment="Patient")
GameplayTagList=(Tag="BB.Requirement.ResearchableWeapon",DevComment="Researchable Weapon")
GameplayTagList=(Tag="BB.Requirement.Resources",DevComment="Resources")
GameplayTagList=(Tag="BB.Requirement.PlantForStudying",DevComment="Plant for Studying")
GameplayTagList=(Tag="BB.Requirement.Item",DevComment="Item")
GameplayTagList=(Tag="BB.Requirement.TraderPresent",DevComment="A trader present in the community")
GameplayTagList=(Tag="BB.Requirement.Food",DevComment="Food")
```

## Phase

```ini
GameplayTagList=(Tag="BB.Phase.Start",DevComment="start")
GameplayTagList=(Tag="BB.Phase.Finish",DevComment="finish")
```

## WorkType

```ini
GameplayTagList=(Tag="BB.WorkType.Basic",DevComment="Basic")
GameplayTagList=(Tag="BB.WorkType.Crafting",DevComment="Crafting")
GameplayTagList=(Tag="BB.WorkType.Research",DevComment="Research")
GameplayTagList=(Tag="BB.WorkType.ResearchItem",DevComment="ResearchItem")
```

## LayoutKind

```ini
GameplayTagList=(Tag="BB.Layout.Kind.Slot",DevComment="Slot")
GameplayTagList=(Tag="BB.Layout.Kind.Yard",DevComment="Yard")
GameplayTagList=(Tag="BB.Layout.Kind.Gate",DevComment="Gate")
GameplayTagList=(Tag="BB.Layout.Kind.Leisure",DevComment="Leisure")
GameplayTagList=(Tag="BB.Layout.Kind.Dormitory",DevComment="Dormitory")
GameplayTagList=(Tag="BB.Layout.Kind.Sleep",DevComment="Sleep")
GameplayTagList=(Tag="BB.Layout.Kind.Wander",DevComment="Wander")
GameplayTagList=(Tag="BB.Layout.Kind.Mess",DevComment="Mess")
GameplayTagList=(Tag="BB.Layout.Kind.Seat",DevComment="Seat")
```

## LayoutSize

```ini
GameplayTagList=(Tag="BB.Building.Size.Small",DevComment="Small")
GameplayTagList=(Tag="BB.Building.Size.Medium",DevComment="Medium")
GameplayTagList=(Tag="BB.Building.Size.Big",DevComment="Large")
```

## ResearchPool

```ini
GameplayTagList=(Tag="BB.ResearchPool.Basic",DevComment="Basic")
```

## Activity

```ini
GameplayTagList=(Tag="BB.Activity.Idle",DevComment="Idle")
GameplayTagList=(Tag="BB.Activity.Work",DevComment="Work")
GameplayTagList=(Tag="BB.Activity.Leisure",DevComment="Leisure")
GameplayTagList=(Tag="BB.Activity.Sleep",DevComment="Sleep")
GameplayTagList=(Tag="BB.Activity.Eat",DevComment="Eat")
```

## ActivityPhase

```ini
GameplayTagList=(Tag="BB.ActivityPhase.Find",DevComment="Find")
GameplayTagList=(Tag="BB.ActivityPhase.Move",DevComment="Move")
GameplayTagList=(Tag="BB.ActivityPhase.Do",DevComment="Do")
```

## Leisure

```ini
GameplayTagList=(Tag="BB.Leisure.Bar.Drink",DevComment="Bar / Drink")
GameplayTagList=(Tag="BB.Leisure.Bar.Speech",DevComment="Bar / Speech")
GameplayTagList=(Tag="BB.Leisure.Bar.TopicalDiscussion",DevComment="Bar / Topical Discussion")
GameplayTagList=(Tag="BB.Leisure.Bar.RealConversation",DevComment="Bar / Real Conversation")
GameplayTagList=(Tag="BB.Leisure.Library.JoinOthersInReading",DevComment="Library / Join Others in Reading")
GameplayTagList=(Tag="BB.Leisure.Library.PresentFindings",DevComment="Library / Present Findings")
GameplayTagList=(Tag="BB.Leisure.Library.Study",DevComment="Library / Study")
GameplayTagList=(Tag="BB.Leisure.Library.SearchArchives",DevComment="Library / Search Archives")
GameplayTagList=(Tag="BB.Leisure.HobbyWorkshop.CommunalSalvageRun",DevComment="Hobby Workshop / Communal Salvage Run")
GameplayTagList=(Tag="BB.Leisure.HobbyWorkshop.FreeformTinkering",DevComment="Hobby Workshop / Freeform Tinkering")
GameplayTagList=(Tag="BB.Leisure.HobbyWorkshop.IdentifyRareFind",DevComment="Hobby Workshop / Identify Rare Find")
GameplayTagList=(Tag="BB.Leisure.HobbyWorkshop.MakeKeepsake",DevComment="Hobby Workshop / Make Keepsake")
GameplayTagList=(Tag="BB.Leisure.Garden.OrganizeEvent",DevComment="Garden / Organize Event")
GameplayTagList=(Tag="BB.Leisure.Garden.TendGarden",DevComment="Garden / Tend Garden")
GameplayTagList=(Tag="BB.Leisure.Garden.PhysicalTraining",DevComment="Garden / Physical Training")
GameplayTagList=(Tag="BB.Leisure.Garden.DabbleWithRememberedPlants",DevComment="Garden / Dabble with Remembered Plants")
GameplayTagList=(Tag="BB.Leisure.Sauna.Socialize",DevComment="Sauna / Socialize")
GameplayTagList=(Tag="BB.Leisure.Sauna.IntenseExercise",DevComment="Sauna / Intense Exercise")
GameplayTagList=(Tag="BB.Leisure.Sauna.Meditation",DevComment="Sauna / Meditation")
GameplayTagList=(Tag="BB.Leisure.Sauna.QuietReflection",DevComment="Sauna / Quiet Reflection")
GameplayTagList=(Tag="BB.Leisure.ShootingClub.LearnGuardingSelfDefense",DevComment="Shooting Club / Learn Guarding & Self-Defense")
GameplayTagList=(Tag="BB.Leisure.ShootingClub.TargetPractice",DevComment="Shooting Club / Target Practice")
GameplayTagList=(Tag="BB.Leisure.ShootingClub.TacticalDrills",DevComment="Shooting Club / Tactical Drills")
GameplayTagList=(Tag="BB.Leisure.ShootingClub.FiresideWarStorySwap",DevComment="Shooting Club / Fireside War-Story Swap")
GameplayTagList=(Tag="BB.Leisure.Base.Wandering",DevComment="Base / Wandering")
GameplayTagList=(Tag="BB.Leisure.Base.TidyingUp",DevComment="Base / Tidying Up")
GameplayTagList=(Tag="BB.Leisure.Base.CheckOnNeighbors",DevComment="Base / Check on Neighbors")
GameplayTagList=(Tag="BB.Leisure.Base.PlayGames",DevComment="Base / Play Games")
GameplayTagList=(Tag="BB.Leisure.Base.SolvePuzzles",DevComment="Base / Solve Puzzles")
GameplayTagList=(Tag="BB.Leisure.Base.WriteJournal",DevComment="Base / Write Journal")
GameplayTagList=(Tag="BB.Leisure.Base.Rest",DevComment="Base / Rest")
```

## Setting

```ini
GameplayTagList=(Tag="BB.Setting.ConditionWindowDays",DevComment="Condition window (days)")
GameplayTagList=(Tag="BB.Setting.ConditionWeighted",DevComment="Weighted condition")
GameplayTagList=(Tag="BB.Setting.CrewUpkeep",DevComment="Crew upkeep")
GameplayTagList=(Tag="BB.Setting.ResearchNodesPerPoint",DevComment="Research nodes per Science point")
GameplayTagList=(Tag="BB.Setting.UnityDecayPerCharacter",DevComment="Unity decay (per character)")
GameplayTagList=(Tag="BB.Setting.BuildingsPerPoint",DevComment="Buildings per Tech / Safety point")
GameplayTagList=(Tag="BB.Setting.StartingSurvivalBank",DevComment="Starting Survival bank")
GameplayTagList=(Tag="BB.Setting.BandLowBelow",DevComment="Low below")
GameplayTagList=(Tag="BB.Setting.BandHighFrom",DevComment="High from")
GameplayTagList=(Tag="BB.Setting.BandNormalFrom",DevComment="Normal from")
GameplayTagList=(Tag="BB.Setting.MorningPhase",DevComment="Morning phase")
GameplayTagList=(Tag="BB.Setting.NightEventChance",DevComment="Night event chance (%)")
GameplayTagList=(Tag="BB.Setting.HarshestEventSeverity",DevComment="Harshest event severity")
```

## SettingsTab

```ini
GameplayTagList=(Tag="BB.SettingsTab.BaseBuilding",DevComment="Base Building")
GameplayTagList=(Tag="BB.SettingsTab.Dialogue",DevComment="Dialogue")
```

## Drain

```ini
GameplayTagList=(Tag="BB.Drain.CrewUpkeep",DevComment="Crew upkeep")
GameplayTagList=(Tag="BB.Drain.MachineWear",DevComment="Machine wear")
GameplayTagList=(Tag="BB.Drain.PerimeterWatch",DevComment="Perimeter watch")
GameplayTagList=(Tag="BB.Drain.KnowledgeUpkeep",DevComment="Knowledge upkeep")
GameplayTagList=(Tag="BB.Drain.UnityDecay",DevComment="Unity decay")
```

## Band

```ini
GameplayTagList=(Tag="BB.Band.Low",DevComment="Low")
GameplayTagList=(Tag="BB.Band.Normal",DevComment="Normal")
GameplayTagList=(Tag="BB.Band.High",DevComment="High")
GameplayTagList=(Tag="BB.Band.Weak",DevComment="Weak")
```

## ItemCategory

```ini
GameplayTagList=(Tag="Inventory.Category.Food",DevComment="Food")
```

## Effect

```ini
GameplayTagList=(Tag="GameplayEffect.BaseBuilding.Hungry",DevComment="Hungry")
GameplayTagList=(Tag="GameplayEffect.BaseBuilding.Starving",DevComment="Starving")
GameplayTagList=(Tag="GameplayEffect.BaseBuilding.AteRawFood",DevComment="Ate Raw Food")
GameplayTagList=(Tag="GameplayEffect.BaseBuilding.Sick",DevComment="Sick")
GameplayTagList=(Tag="GameplayEffect.BaseBuilding.Unmotivated",DevComment="Unmotivated")
GameplayTagList=(Tag="GameplayEffect.BaseBuilding.Checked",DevComment="Checked")
```

## Meal

```ini
GameplayTagList=(Tag="BB.Meal.Lunch",DevComment="Lunch")
GameplayTagList=(Tag="BB.Meal.Dinner",DevComment="Dinner")
```

## Event

```ini
GameplayTagList=(Tag="BB.Event.FeverInTheNight",DevComment="FeverInTheNight")
GameplayTagList=(Tag="BB.Event.CleanBillOfHealth",DevComment="CleanBillOfHealth")
GameplayTagList=(Tag="BB.Event.HarshWords",DevComment="HarshWords")
GameplayTagList=(Tag="BB.Event.StoriesByTheFire",DevComment="StoriesByTheFire")
GameplayTagList=(Tag="BB.Event.MovementAtTheFence",DevComment="MovementAtTheFence")
GameplayTagList=(Tag="BB.Event.QuietWatch",DevComment="QuietWatch")
GameplayTagList=(Tag="BB.Event.EmptyStomachs",DevComment="EmptyStomachs")
GameplayTagList=(Tag="BB.Event.MidnightFeast",DevComment="MidnightFeast")
GameplayTagList=(Tag="BB.Event.GeneratorStutter",DevComment="GeneratorStutter")
GameplayTagList=(Tag="BB.Event.TinkerersNight",DevComment="TinkerersNight")
GameplayTagList=(Tag="BB.Event.LostNotes",DevComment="LostNotes")
GameplayTagList=(Tag="BB.Event.SleeplessInsight",DevComment="SleeplessInsight")
GameplayTagList=(Tag="BB.Event.BadDream",DevComment="BadDream")
GameplayTagList=(Tag="BB.Event.LosingHeart",DevComment="LosingHeart")
GameplayTagList=(Tag="BB.Event.KnockAtTheGate",DevComment="KnockAtTheGate")
GameplayTagList=(Tag="BB.Event.VoiceOnTheRadio",DevComment="VoiceOnTheRadio")
GameplayTagList=(Tag="BB.Event.NightThief",DevComment="NightThief")
GameplayTagList=(Tag="BB.Event.SomethingBigOutside",DevComment="SomethingBigOutside")
```

## EventBeat

```ini
GameplayTagList=(Tag="BB.EventBeat.Night",DevComment="Night")
GameplayTagList=(Tag="BB.EventBeat.Day",DevComment="Day")
```

## EventSubject

```ini
GameplayTagList=(Tag="BB.EventSubject.RandomWorker",DevComment="Random worker")
GameplayTagList=(Tag="BB.EventSubject.RandomCharacter",DevComment="Random character")
GameplayTagList=(Tag="BB.EventSubject.TwoCharacters",DevComment="Two characters")
GameplayTagList=(Tag="BB.EventSubject.GuardOnDuty",DevComment="Guard on duty")
GameplayTagList=(Tag="BB.EventSubject.BestSkill",DevComment="Best skill")
GameplayTagList=(Tag="BB.EventSubject.RandomResearcher",DevComment="Random researcher")
GameplayTagList=(Tag="BB.EventSubject.MostDistressed",DevComment="Most distressed")
GameplayTagList=(Tag="BB.EventSubject.ThatCharacter",DevComment="That character")
GameplayTagList=(Tag="BB.EventSubject.Stranger",DevComment="Stranger")
```

## Severity

```ini
GameplayTagList=(Tag="BB.Severity.Flavour",DevComment="Flavour")
GameplayTagList=(Tag="BB.Severity.Setback",DevComment="Setback")
GameplayTagList=(Tag="BB.Severity.Harsh",DevComment="Harsh")
```
