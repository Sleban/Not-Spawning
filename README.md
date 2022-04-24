# Not-Spawning

Loaded file (Scenario) is from version 1.3.3200 rev726, we are running version 1.3.3326 rev562.
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.ScribeMetaHeaderUtility:LoadGameDataHeader (Verse.ScribeMetaHeaderUtility/ScribeHeaderMode,bool)
Verse.GameDataSaveLoader:TryLoadScenario (string,RimWorld.ScenarioCategory,RimWorld.Scenario&)
RimWorld.ScenarioFiles:RecacheData ()
RimWorld.ScenarioLister:RecacheData ()
RimWorld.ScenarioLister:RecacheIfDirty ()
RimWorld.ScenarioLister/<ScenariosInCategory>d__2:MoveNext ()
System.Linq.Enumerable:TryGetFirst<RimWorld.Scenario> (System.Collections.Generic.IEnumerable`1<RimWorld.Scenario>,bool&)
System.Linq.Enumerable:FirstOrDefault<RimWorld.Scenario> (System.Collections.Generic.IEnumerable`1<RimWorld.Scenario>)
RimWorld.Page_SelectScenario:EnsureValidSelection ()
(wrapper dynamic-method) RimWorld.Page_SelectScenario:RimWorld.Page_SelectScenario.PreOpen_Patch1 (RimWorld.Page_SelectScenario)
Verse.WindowStack:Add (Verse.Window)
RimWorld.MainMenuDrawer/<>c:<DoMainMenuControls>b__17_11 ()
Verse.ListableOption:DrawOption (UnityEngine.Vector2,single)
Verse.OptionListingUtility:DrawOptionListing (UnityEngine.Rect,System.Collections.Generic.List`1<Verse.ListableOption>)
(wrapper dynamic-method) RimWorld.MainMenuDrawer:RimWorld.MainMenuDrawer.DoMainMenuControls_Patch0 (UnityEngine.Rect,bool)
RimWorld.MainMenuDrawer:MainMenuOnGUI ()
Verse.UIRoot_Entry:DoMainMenu ()
Verse.UIRoot_Entry:UIRootOnGUI ()
(wrapper dynamic-method) Verse.Root:Verse.Root.OnGUI_Patch1 (Verse.Root)

Achtung v3.4.4.0 Info: To make Achtung log some performance info, create an empty 'AchtungPerformance.txt' file in same directory as Player.log
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
AchtungMod.World_FinalizeInit_Patch:Prefix ()
(wrapper dynamic-method) RimWorld.Planet.World:RimWorld.Planet.World.FinalizeInit_Patch1 (RimWorld.Planet.World)
RimWorld.Planet.WorldGenerator:GenerateWorld (single,string,RimWorld.Planet.OverallRainfall,RimWorld.Planet.OverallTemperature,RimWorld.Planet.OverallPopulation,System.Collections.Generic.Dictionary`2<RimWorld.FactionDef, int>)
RimWorld.Page_CreateWorldParams:<CanDoNext>b__17_0 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Null raceFilter detected - Recreating
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionFC:FinalizeInit ()
RimWorld.Planet.WorldComponentUtility:FinalizeInit (RimWorld.Planet.World)
(wrapper dynamic-method) RimWorld.Planet.World:RimWorld.Planet.World.FinalizeInit_Patch1 (RimWorld.Planet.World)
RimWorld.Planet.WorldGenerator:GenerateWorld (single,string,RimWorld.Planet.OverallRainfall,RimWorld.Planet.OverallTemperature,RimWorld.Planet.OverallPopulation,System.Collections.Generic.Dictionary`2<RimWorld.FactionDef, int>)
RimWorld.Page_CreateWorldParams:<CanDoNext>b__17_0 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

[Prepare Carefully] Could not find hairSettings field for Human
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderPawnLayers:InitializePawnLayers (Verse.ThingDef,Verse.Gender)
EdB.PrepareCarefully.ProviderPawnLayers:GetLayersForPawn (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Thing_Human876 of type Verse.Pawn. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFEAncients.Ability_Thought curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<Verse.Pawn> (string)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string)
Verse.Scribe_References:Look<Verse.Pawn> (Verse.Pawn&,string,bool)
VFECore.Abilities.Ability:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Ability_VFEA_Empathy_Thing_Human876 of type VFECore.Abilities.Ability. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Verb_CastAbility(null) curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<VFECore.Abilities.Ability> (string)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string)
Verse.Scribe_References:Look<VFECore.Abilities.Ability> (VFECore.Abilities.Ability&,string,bool)
VFECore.Abilities.Verb_CastAbility:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Thing_Human890 of type Verse.Pawn. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFEAncients.Ability curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<Verse.Pawn> (string)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string)
Verse.Scribe_References:Look<Verse.Pawn> (Verse.Pawn&,string,bool)
VFECore.Abilities.Ability:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Ability_VFEA_Invisibility_Thing_Human890 of type VFECore.Abilities.Ability. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Verb_CastAbility(null) curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<VFECore.Abilities.Ability> (string)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string)
Verse.Scribe_References:Look<VFECore.Abilities.Ability> (VFECore.Abilities.Ability&,string,bool)
VFECore.Abilities.Verb_CastAbility:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Loaded equipment database with 406 material(s)
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
EdB.PrepareCarefully.Logger:Message (string)
EdB.PrepareCarefully.EquipmentDatabase:ProcessStuff ()
EdB.PrepareCarefully.EquipmentDatabase:LoadFrame ()
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Loaded equipment database with 2217 item(s)
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
EdB.PrepareCarefully.Logger:Message (string)
EdB.PrepareCarefully.EquipmentDatabase:ProcessThings ()
EdB.PrepareCarefully.EquipmentDatabase:LoadFrame ()
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

QualityBuilder added property to '0' things
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
QualityBuilder.ModInitializerComponent:FixedUpdate ()

Initializing new game with mods:
  - brrainz.harmony
  - Ludeon.RimWorld
  - Ludeon.RimWorld.Ideology
  - Ludeon.RimWorld.Royalty
  - ccl.patchoperation.highlander
  - UnlimitedHugs.HugsLib
  - spdskatr.projectrimfactory
  - Fluffy.ModManager
  - UnlimitedHugs.AllowTool
  - VouLT.BetterPawnControl
  - hatti.cleaningarea
  - erdelf.HumanoidAlienRaces
  - UnlimitedHugs.DefensivePositions
  - Dubwise.DubsMintMenus
  - jecrell.jecstools
  - Dubwise.DubsBadHygiene
  - EdB.PrepareCarefully.UnofficialPatch
  - Uuugggg.EverybodyGetsOne
  - rimfridge.kv.rw
  - trinity.RuntimeGCupdated
  - targhetti.ShowDrafteesWeapon
  - OskarPotocki.VanillaFactionsExpanded.Core
  - OskarPotocki.VFE.Pirates
  - VanillaExpanded.VFEFarming
  - VanillaExpanded.VFECore
  - VanillaExpanded.VCookE
  - VanillaExpanded.VMemesE
  - tammybee.whereismyweapon
  - ReGrowth.BOTR.Core
  - VanillaExpanded.VFESecurity
  - com.yayo.combat3
  - Burusutazu.ImpassableFences
  - tikubonn.DontBlockDoor
  - KamiKatze.MaterialFilter
  - erdelf.MinifyEverything
  - weilbyte.nopowerwires
  - JBloodthorn.NoLazyDoctors
  - fed1sPlay.PawnTargetFix
  - hatti.qualitybuilder
  - Scherub.realisticrooms
  - Haplo.Miscellaneous.Core
  - automatic.recipeicons
  - Uuugggg.ReplaceStuff
  - roolo.RunAndGun
  - roolo.SearchAndDestroy
  - dhultgren.smarterconstruction
  - TradingControl.Common.Core
  - Fisi.UndergroundWires
  - VanillaExpanded.VARME
  - Fluffy.WorkTab
  - avilmask.GrazingLands
  - brrainz.achtung
  - Fluffy.MedicalTab
  - VSE.PerryPersistent
  - VanillaExpanded.VFEPower
  - automatic.autolinks
  - falconne.BWM
  - notfood.SeedsPlease
  - Dubwise.Rimefeller
  - dismarzero.VGP.VGPVegetableGarden
  - falconne.AFF
  - arl85.AnimalsAgeFilter
  - Haplo.Miscellaneous.Robots
  - Owlchemist.CleanPathfinding
  - dracoix.doormat.r12a
  - jecrell.doorsexpanded
  - VanillaExpanded.VWEC
  - InsertKey.ItemListSelector
  - notfood.MendAndRecycle
  - PeteTimesSix.SimpleSidearms
  - impassablemapmaker.kv.rw
  - Indeed.StackXXL
  - LWM.DeepStorage
  - hobtook.tradeui
  - pyrce.mass.graves
  - O.inf.reinforce
  - PeteTimesSix.CompactHediffs
  - FrozenSnowFox.FilthVanishesWithRainAndTime
  - newcolonist.largefactionbases
  - Mehni.PickUpAndHaul
  - denev.SmartTurretCovering
  - VanillaExpanded.VCookEStews
  - VanillaExpanded.VEE
  - Prolle.Glitterworld.Medicine
  - Ogliss.TheWhiteCrayon.Quarry
  - neceros.ceilinglights
  - Murmur.WallLight
  - velc.TrapDisable
  - Karthas.EngravedWalls
  - nep.smallerlandingpads
  - Aoba.WarCasket
  - dismarzero.VGP.VGPGardenMedicine
  - whooooooooooo.SmoothWalls
  - cucumpear.embrasures
  - Atlas.AndroidTiers
  - CarnySenpai.EnableOversizedWeapons
  - avilmask.CommonSense
  - Fluffy.Blueprints
  - ADE.pulseTurrets.Mod
  - Fluffy.DesirePaths
  - saloid.DynamicEconomy
  - Saakra.Empire
  - Cliffyq.FootTrafficHeatmap
  - Aoba.Fortress.Industrial
  - m00nl1ght.GeologicalLandforms
  - roolo.giddyupcore
  - roolo.giddyupcaravan
  - roolo.giddyuprideandroll
  - JPT.HumanResources
  - Alaestor.MiscRobots.PlusPlus
  - Haplo.Miscellaneous.TurretBaseAndObjects
  - telardo.NoLaggyBed
  - hobtook.mortaraccuracy
  - spdskatr.projectrimfactory.drones
  - PRF.Materials
  - ratys.rtfuse
  - Owlchemist.SmartFarming
  - nephlite.orbitaltradecolumn
  - VanillaExpanded.VFEA
  - VanillaExpanded.VWEL
  - Dra.YayoCombatWarcaskets
  - Sk.WeaponMastery
  - VanillaExpanded.Ideo.RelicsAndArtifacts
  - VanillaExpanded.VFEProduction
  - VinaLx.ResearchPalForked
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

TrafficHeatmap ctor -225222656
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
TrafficHeatmap.FootTrafficHeatmap:.ctor (Verse.Map)
System.Reflection.MonoCMethod:InternalInvoke (object,object[])
System.Reflection.MonoCMethod:DoInvoke (object,System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo)
System.Reflection.MonoCMethod:Invoke (System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo)
System.RuntimeType:CreateInstanceImpl (System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo,object[],System.Threading.StackCrawlMark&)
System.Activator:CreateInstance (System.Type,System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo,object[])
System.Activator:CreateInstance (System.Type,object[])
Verse.Map:FillComponents ()
(wrapper dynamic-method) Verse.Map:Verse.Map.ConstructComponents_Patch1 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

[HumanResources] Found 0 weapons, 0 starting techs from the scenario and 17 from the player faction.
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
HumanResources.UnlockManager:RegisterStartingResources ()
HumanResources.UnlockManager:NewGameStarted ()
HumanResources.ModBaseHumanResources:MapComponentsInitializing (Verse.Map)
HugsLib.HugsLibController:OnMapComponentsConstructed (Verse.Map)
HugsLib.Patches.Map_ConstructComponents_Patch:MapComponentsInitHook (Verse.Map)
(wrapper dynamic-method) Verse.Map:Verse.Map.ConstructComponents_Patch1 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Can't enable CompPowerTrader(parent=VFEA_WallLamp55602 at=(96, 0, 118))
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:TryTurnOnImmediately (RimWorld.CompPowerTrader,Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:EnsurePowerUsersConnected (Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:PostMapGenerate (Verse.Map)
RimWorld.Scenario:PostMapGenerate (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

ShallowReservoirSeed == 0 Regenerating seeds
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
Rimefeller.MapComponent_Rimefeller:FinalizeInit ()
Verse.MapComponentUtility:FinalizeInit (Verse.Map)
(wrapper dynamic-method) Verse.Map:Verse.Map.FinalizeInit_Patch2 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

TrafficHeatmap FinalizeInit -225222656
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
TrafficHeatmap.FootTrafficHeatmap:FinalizeInit ()
Verse.MapComponentUtility:FinalizeInit (Verse.Map)
(wrapper dynamic-method) Verse.Map:Verse.Map.FinalizeInit_Patch2 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Updating Empire to Latest Version
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Resetting faction leaders
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.SoS2HarmonyPatches:ResetFactionLeaders (bool)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Empire - Testing for traits with no tie
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Empire - Testing for invalid capital map
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:MessagePlayerAboutConfigErrors (FactionColonies.FactionFC)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Empire - Testing for update change
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Loaded file (Scenario) is from version 1.3.3200 rev726, we are running version 1.3.3326 rev562.
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.ScribeMetaHeaderUtility:LoadGameDataHeader (Verse.ScribeMetaHeaderUtility/ScribeHeaderMode,bool)
Verse.GameDataSaveLoader:TryLoadScenario (string,RimWorld.ScenarioCategory,RimWorld.Scenario&)
RimWorld.ScenarioFiles:RecacheData ()
RimWorld.ScenarioLister:RecacheData ()
RimWorld.ScenarioLister:RecacheIfDirty ()
RimWorld.ScenarioLister/<ScenariosInCategory>d__2:MoveNext ()
System.Linq.Enumerable:TryGetFirst<RimWorld.Scenario> (System.Collections.Generic.IEnumerable`1<RimWorld.Scenario>,bool&)
System.Linq.Enumerable:FirstOrDefault<RimWorld.Scenario> (System.Collections.Generic.IEnumerable`1<RimWorld.Scenario>)
RimWorld.Page_SelectScenario:EnsureValidSelection ()
(wrapper dynamic-method) RimWorld.Page_SelectScenario:RimWorld.Page_SelectScenario.PreOpen_Patch1 (RimWorld.Page_SelectScenario)
Verse.WindowStack:Add (Verse.Window)
RimWorld.MainMenuDrawer/<>c:<DoMainMenuControls>b__17_11 ()
Verse.ListableOption:DrawOption (UnityEngine.Vector2,single)
Verse.OptionListingUtility:DrawOptionListing (UnityEngine.Rect,System.Collections.Generic.List`1<Verse.ListableOption>)
(wrapper dynamic-method) RimWorld.MainMenuDrawer:RimWorld.MainMenuDrawer.DoMainMenuControls_Patch0 (UnityEngine.Rect,bool)
RimWorld.MainMenuDrawer:MainMenuOnGUI ()
Verse.UIRoot_Entry:DoMainMenu ()
Verse.UIRoot_Entry:UIRootOnGUI ()
(wrapper dynamic-method) Verse.Root:Verse.Root.OnGUI_Patch1 (Verse.Root)

Failed to generate a unique precept name: Third Triumvir at 50% uniqueness
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
RimWorld.Precept:GenerateNewName ()
RimWorld.Precept:RegenerateName ()
RimWorld.Precept_Role:Init (RimWorld.Ideo,RimWorld.FactionDef)
RimWorld.Precept_RoleSingle:Init (RimWorld.Ideo,RimWorld.FactionDef)
RimWorld.IdeoFoundation/<>c__DisplayClass37_0:<InitPrecepts>g__AddAndInitPrecepts|0 ()
(wrapper dynamic-method) RimWorld.IdeoFoundation:RimWorld.IdeoFoundation.InitPrecepts_Patch1 (RimWorld.IdeoFoundation,RimWorld.IdeoGenerationParms,System.Collections.Generic.List`1<RimWorld.Precept>)
RimWorld.IdeoFoundation:RandomizePrecepts (bool,RimWorld.IdeoGenerationParms)
RimWorld.IdeoFoundation_Deity:Init (RimWorld.IdeoGenerationParms)
RimWorld.IdeoGenerator:GenerateIdeo (RimWorld.IdeoGenerationParms)
RimWorld.FactionIdeosTracker:ChooseOrGenerateIdeo (RimWorld.IdeoGenerationParms)
RimWorld.FactionGenerator:NewGeneratedFaction (RimWorld.FactionGeneratorParms)
(wrapper dynamic-method) RimWorld.FactionGenerator:RimWorld.FactionGenerator.GenerateFactionsIntoWorld_Patch1 (System.Collections.Generic.Dictionary`2<RimWorld.FactionDef, int>)
RimWorld.Planet.WorldGenStep_Factions:GenerateFresh (string)
RimWorld.Planet.WorldGenerator:GenerateWorld (single,string,RimWorld.Planet.OverallRainfall,RimWorld.Planet.OverallTemperature,RimWorld.Planet.OverallPopulation,System.Collections.Generic.Dictionary`2<RimWorld.FactionDef, int>)
RimWorld.Page_CreateWorldParams:<CanDoNext>b__17_0 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Achtung v3.4.4.0 Info: To make Achtung log some performance info, create an empty 'AchtungPerformance.txt' file in same directory as Player.log
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
AchtungMod.World_FinalizeInit_Patch:Prefix ()
(wrapper dynamic-method) RimWorld.Planet.World:RimWorld.Planet.World.FinalizeInit_Patch1 (RimWorld.Planet.World)
RimWorld.Planet.WorldGenerator:GenerateWorld (single,string,RimWorld.Planet.OverallRainfall,RimWorld.Planet.OverallTemperature,RimWorld.Planet.OverallPopulation,System.Collections.Generic.Dictionary`2<RimWorld.FactionDef, int>)
RimWorld.Page_CreateWorldParams:<CanDoNext>b__17_0 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Null raceFilter detected - Recreating
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionFC:FinalizeInit ()
RimWorld.Planet.WorldComponentUtility:FinalizeInit (RimWorld.Planet.World)
(wrapper dynamic-method) RimWorld.Planet.World:RimWorld.Planet.World.FinalizeInit_Patch1 (RimWorld.Planet.World)
RimWorld.Planet.WorldGenerator:GenerateWorld (single,string,RimWorld.Planet.OverallRainfall,RimWorld.Planet.OverallTemperature,RimWorld.Planet.OverallPopulation,System.Collections.Generic.Dictionary`2<RimWorld.FactionDef, int>)
RimWorld.Page_CreateWorldParams:<CanDoNext>b__17_0 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

[Prepare Carefully] Could not find hairSettings field for Human
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderPawnLayers:InitializePawnLayers (Verse.ThingDef,Verse.Gender)
EdB.PrepareCarefully.ProviderPawnLayers:GetLayersForPawn (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Thing_Human613 of type Verse.Pawn. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFEAncients.Ability_Animal curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<Verse.Pawn> (string)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string)
Verse.Scribe_References:Look<Verse.Pawn> (Verse.Pawn&,string,bool)
VFECore.Abilities.Ability:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Ability_VFEA_AnimalSpeech_Thing_Human613 of type VFECore.Abilities.Ability. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Verb_CastAbility(null) curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<VFECore.Abilities.Ability> (string)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string)
Verse.Scribe_References:Look<VFECore.Abilities.Ability> (VFECore.Abilities.Ability&,string,bool)
VFECore.Abilities.Verb_CastAbility:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Thing_Human641 of type Verse.Pawn. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFEAncients.Ability_Thought curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<Verse.Pawn> (string)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string)
Verse.Scribe_References:Look<Verse.Pawn> (Verse.Pawn&,string,bool)
VFECore.Abilities.Ability:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Ability_VFEA_Empathy_Thing_Human641 of type VFECore.Abilities.Ability. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Verb_CastAbility(null) curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<VFECore.Abilities.Ability> (string)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string)
Verse.Scribe_References:Look<VFECore.Abilities.Ability> (VFECore.Abilities.Ability&,string,bool)
VFECore.Abilities.Verb_CastAbility:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Thing_Human673 of type Verse.Pawn. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Ability_ShootProjectile curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<Verse.Pawn> (string)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string)
Verse.Scribe_References:Look<Verse.Pawn> (Verse.Pawn&,string,bool)
VFECore.Abilities.Ability:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Ability_VFEA_LaserEyes_Thing_Human673 of type VFECore.Abilities.Ability. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Verb_CastAbility(null) curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<VFECore.Abilities.Ability> (string)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string)
Verse.Scribe_References:Look<VFECore.Abilities.Ability> (VFECore.Abilities.Ability&,string,bool)
VFECore.Abilities.Verb_CastAbility:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.RelationshipManager:CreateNewTemporaryPawn (Verse.Gender)
EdB.PrepareCarefully.RelationshipManager:.ctor (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:InitializeRelationshipManager (System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.RelationshipManager:CreateNewTemporaryPawn (Verse.Gender)
EdB.PrepareCarefully.RelationshipManager:.ctor (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:InitializeRelationshipManager (System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.RelationshipManager:CreateNewTemporaryPawn (Verse.Gender)
EdB.PrepareCarefully.RelationshipManager:.ctor (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:InitializeRelationshipManager (System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.RelationshipManager:CreateNewTemporaryPawn (Verse.Gender)
EdB.PrepareCarefully.RelationshipManager:.ctor (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:InitializeRelationshipManager (System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Loaded equipment database with 406 material(s)
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
EdB.PrepareCarefully.Logger:Message (string)
EdB.PrepareCarefully.EquipmentDatabase:ProcessStuff ()
EdB.PrepareCarefully.EquipmentDatabase:LoadFrame ()
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Loaded equipment database with 2217 item(s)
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
EdB.PrepareCarefully.Logger:Message (string)
EdB.PrepareCarefully.EquipmentDatabase:ProcessThings ()
EdB.PrepareCarefully.EquipmentDatabase:LoadFrame ()
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:CopyAppearance (Verse.Pawn)
EdB.PrepareCarefully.ControllerPawns:RandomizeAppearance ()
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:CopyAppearance (Verse.Pawn)
EdB.PrepareCarefully.ControllerPawns:RandomizeAppearance ()
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

QualityBuilder added property to '0' things
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
QualityBuilder.ModInitializerComponent:FixedUpdate ()

Initializing new game with mods:
  - brrainz.harmony
  - Ludeon.RimWorld
  - Ludeon.RimWorld.Ideology
  - Ludeon.RimWorld.Royalty
  - ccl.patchoperation.highlander
  - UnlimitedHugs.HugsLib
  - spdskatr.projectrimfactory
  - Fluffy.ModManager
  - UnlimitedHugs.AllowTool
  - VouLT.BetterPawnControl
  - hatti.cleaningarea
  - erdelf.HumanoidAlienRaces
  - UnlimitedHugs.DefensivePositions
  - Dubwise.DubsMintMenus
  - jecrell.jecstools
  - Dubwise.DubsBadHygiene
  - EdB.PrepareCarefully.UnofficialPatch
  - Uuugggg.EverybodyGetsOne
  - rimfridge.kv.rw
  - trinity.RuntimeGCupdated
  - targhetti.ShowDrafteesWeapon
  - OskarPotocki.VanillaFactionsExpanded.Core
  - OskarPotocki.VFE.Pirates
  - VanillaExpanded.VFEFarming
  - VanillaExpanded.VFECore
  - VanillaExpanded.VCookE
  - VanillaExpanded.VMemesE
  - tammybee.whereismyweapon
  - ReGrowth.BOTR.Core
  - VanillaExpanded.VFESecurity
  - com.yayo.combat3
  - Burusutazu.ImpassableFences
  - tikubonn.DontBlockDoor
  - KamiKatze.MaterialFilter
  - erdelf.MinifyEverything
  - weilbyte.nopowerwires
  - JBloodthorn.NoLazyDoctors
  - fed1sPlay.PawnTargetFix
  - hatti.qualitybuilder
  - Scherub.realisticrooms
  - Haplo.Miscellaneous.Core
  - automatic.recipeicons
  - Uuugggg.ReplaceStuff
  - roolo.RunAndGun
  - roolo.SearchAndDestroy
  - dhultgren.smarterconstruction
  - TradingControl.Common.Core
  - Fisi.UndergroundWires
  - VanillaExpanded.VARME
  - Fluffy.WorkTab
  - avilmask.GrazingLands
  - brrainz.achtung
  - Fluffy.MedicalTab
  - VSE.PerryPersistent
  - VanillaExpanded.VFEPower
  - automatic.autolinks
  - falconne.BWM
  - notfood.SeedsPlease
  - Dubwise.Rimefeller
  - dismarzero.VGP.VGPVegetableGarden
  - falconne.AFF
  - arl85.AnimalsAgeFilter
  - Haplo.Miscellaneous.Robots
  - Owlchemist.CleanPathfinding
  - dracoix.doormat.r12a
  - jecrell.doorsexpanded
  - VanillaExpanded.VWEC
  - InsertKey.ItemListSelector
  - notfood.MendAndRecycle
  - PeteTimesSix.SimpleSidearms
  - impassablemapmaker.kv.rw
  - Indeed.StackXXL
  - LWM.DeepStorage
  - hobtook.tradeui
  - pyrce.mass.graves
  - O.inf.reinforce
  - PeteTimesSix.CompactHediffs
  - FrozenSnowFox.FilthVanishesWithRainAndTime
  - newcolonist.largefactionbases
  - Mehni.PickUpAndHaul
  - denev.SmartTurretCovering
  - VanillaExpanded.VCookEStews
  - VanillaExpanded.VEE
  - Prolle.Glitterworld.Medicine
  - Ogliss.TheWhiteCrayon.Quarry
  - neceros.ceilinglights
  - Murmur.WallLight
  - velc.TrapDisable
  - Karthas.EngravedWalls
  - nep.smallerlandingpads
  - Aoba.WarCasket
  - dismarzero.VGP.VGPGardenMedicine
  - whooooooooooo.SmoothWalls
  - cucumpear.embrasures
  - Atlas.AndroidTiers
  - CarnySenpai.EnableOversizedWeapons
  - avilmask.CommonSense
  - Fluffy.Blueprints
  - ADE.pulseTurrets.Mod
  - Fluffy.DesirePaths
  - saloid.DynamicEconomy
  - Saakra.Empire
  - Cliffyq.FootTrafficHeatmap
  - Aoba.Fortress.Industrial
  - m00nl1ght.GeologicalLandforms
  - roolo.giddyupcore
  - roolo.giddyupcaravan
  - roolo.giddyuprideandroll
  - JPT.HumanResources
  - Alaestor.MiscRobots.PlusPlus
  - Haplo.Miscellaneous.TurretBaseAndObjects
  - telardo.NoLaggyBed
  - hobtook.mortaraccuracy
  - spdskatr.projectrimfactory.drones
  - PRF.Materials
  - ratys.rtfuse
  - Owlchemist.SmartFarming
  - nephlite.orbitaltradecolumn
  - VanillaExpanded.VFEA
  - VanillaExpanded.VWEL
  - Dra.YayoCombatWarcaskets
  - Sk.WeaponMastery
  - VanillaExpanded.Ideo.RelicsAndArtifacts
  - VanillaExpanded.VFEProduction
  - VinaLx.ResearchPalForked
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

TrafficHeatmap ctor 1728050176
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
TrafficHeatmap.FootTrafficHeatmap:.ctor (Verse.Map)
System.Reflection.MonoCMethod:InternalInvoke (object,object[])
System.Reflection.MonoCMethod:DoInvoke (object,System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo)
System.Reflection.MonoCMethod:Invoke (System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo)
System.RuntimeType:CreateInstanceImpl (System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo,object[],System.Threading.StackCrawlMark&)
System.Activator:CreateInstance (System.Type,System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo,object[])
System.Activator:CreateInstance (System.Type,object[])
Verse.Map:FillComponents ()
(wrapper dynamic-method) Verse.Map:Verse.Map.ConstructComponents_Patch1 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

[HumanResources] Found 1 weapons, 0 starting techs from the scenario and 17 from the player faction.
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
HumanResources.UnlockManager:RegisterStartingResources ()
HumanResources.UnlockManager:NewGameStarted ()
HumanResources.ModBaseHumanResources:MapComponentsInitializing (Verse.Map)
HugsLib.HugsLibController:OnMapComponentsConstructed (Verse.Map)
HugsLib.Patches.Map_ConstructComponents_Patch:MapComponentsInitHook (Verse.Map)
(wrapper dynamic-method) Verse.Map:Verse.Map.ConstructComponents_Patch1 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Can't enable CompPowerTrader(parent=VFEA_Turret_AncientPointDefense62896 at=(164, 0, 141))
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:TryTurnOnImmediately (RimWorld.CompPowerTrader,Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:EnsurePowerUsersConnected (Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:PostMapGenerate (Verse.Map)
RimWorld.Scenario:PostMapGenerate (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Can't enable CompPowerTrader(parent=VFEA_AncientHydroponicFarm63746 at=(124, 0, 163))
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:TryTurnOnImmediately (RimWorld.CompPowerTrader,Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:EnsurePowerUsersConnected (Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:PostMapGenerate (Verse.Map)
RimWorld.Scenario:PostMapGenerate (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Can't enable CompPowerTrader(parent=VFEA_AncientHydroponicFarm63747 at=(128, 0, 163))
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:TryTurnOnImmediately (RimWorld.CompPowerTrader,Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:EnsurePowerUsersConnected (Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:PostMapGenerate (Verse.Map)
RimWorld.Scenario:PostMapGenerate (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Can't enable CompPowerTrader(parent=VFEA_AncientHydroponicFarm63832 at=(124, 0, 166))
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:TryTurnOnImmediately (RimWorld.CompPowerTrader,Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:EnsurePowerUsersConnected (Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:PostMapGenerate (Verse.Map)
RimWorld.Scenario:PostMapGenerate (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Can't enable CompPowerTrader(parent=VFEA_AncientHydroponicFarm63833 at=(128, 0, 166))
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:TryTurnOnImmediately (RimWorld.CompPowerTrader,Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:EnsurePowerUsersConnected (Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:PostMapGenerate (Verse.Map)
RimWorld.Scenario:PostMapGenerate (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

ShallowReservoirSeed == 0 Regenerating seeds
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
Rimefeller.MapComponent_Rimefeller:FinalizeInit ()
Verse.MapComponentUtility:FinalizeInit (Verse.Map)
(wrapper dynamic-method) Verse.Map:Verse.Map.FinalizeInit_Patch2 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

TrafficHeatmap FinalizeInit 1728050176
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
TrafficHeatmap.FootTrafficHeatmap:FinalizeInit ()
Verse.MapComponentUtility:FinalizeInit (Verse.Map)
(wrapper dynamic-method) Verse.Map:Verse.Map.FinalizeInit_Patch2 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Updating Empire to Latest Version
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Resetting faction leaders
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.SoS2HarmonyPatches:ResetFactionLeaders (bool)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Empire - Testing for traits with no tie
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Empire - Testing for invalid capital map
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:MessagePlayerAboutConfigErrors (FactionColonies.FactionFC)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Empire - Testing for update change
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Loaded file (Scenario) is from version 1.3.3200 rev726, we are running version 1.3.3326 rev562.
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.ScribeMetaHeaderUtility:LoadGameDataHeader (Verse.ScribeMetaHeaderUtility/ScribeHeaderMode,bool)
Verse.GameDataSaveLoader:TryLoadScenario (string,RimWorld.ScenarioCategory,RimWorld.Scenario&)
RimWorld.ScenarioFiles:RecacheData ()
RimWorld.ScenarioLister:RecacheData ()
RimWorld.ScenarioLister:RecacheIfDirty ()
RimWorld.ScenarioLister/<ScenariosInCategory>d__2:MoveNext ()
System.Linq.Enumerable:TryGetFirst<RimWorld.Scenario> (System.Collections.Generic.IEnumerable`1<RimWorld.Scenario>,bool&)
System.Linq.Enumerable:FirstOrDefault<RimWorld.Scenario> (System.Collections.Generic.IEnumerable`1<RimWorld.Scenario>)
RimWorld.Page_SelectScenario:EnsureValidSelection ()
(wrapper dynamic-method) RimWorld.Page_SelectScenario:RimWorld.Page_SelectScenario.PreOpen_Patch1 (RimWorld.Page_SelectScenario)
Verse.WindowStack:Add (Verse.Window)
RimWorld.MainMenuDrawer/<>c:<DoMainMenuControls>b__17_11 ()
Verse.ListableOption:DrawOption (UnityEngine.Vector2,single)
Verse.OptionListingUtility:DrawOptionListing (UnityEngine.Rect,System.Collections.Generic.List`1<Verse.ListableOption>)
(wrapper dynamic-method) RimWorld.MainMenuDrawer:RimWorld.MainMenuDrawer.DoMainMenuControls_Patch0 (UnityEngine.Rect,bool)
RimWorld.MainMenuDrawer:MainMenuOnGUI ()
Verse.UIRoot_Entry:DoMainMenu ()
Verse.UIRoot_Entry:UIRootOnGUI ()
(wrapper dynamic-method) Verse.Root:Verse.Root.OnGUI_Patch1 (Verse.Root)

Achtung v3.4.4.0 Info: To make Achtung log some performance info, create an empty 'AchtungPerformance.txt' file in same directory as Player.log
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
AchtungMod.World_FinalizeInit_Patch:Prefix ()
(wrapper dynamic-method) RimWorld.Planet.World:RimWorld.Planet.World.FinalizeInit_Patch1 (RimWorld.Planet.World)
RimWorld.Planet.WorldGenerator:GenerateWorld (single,string,RimWorld.Planet.OverallRainfall,RimWorld.Planet.OverallTemperature,RimWorld.Planet.OverallPopulation,System.Collections.Generic.Dictionary`2<RimWorld.FactionDef, int>)
RimWorld.Page_CreateWorldParams:<CanDoNext>b__17_0 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Null raceFilter detected - Recreating
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionFC:FinalizeInit ()
RimWorld.Planet.WorldComponentUtility:FinalizeInit (RimWorld.Planet.World)
(wrapper dynamic-method) RimWorld.Planet.World:RimWorld.Planet.World.FinalizeInit_Patch1 (RimWorld.Planet.World)
RimWorld.Planet.WorldGenerator:GenerateWorld (single,string,RimWorld.Planet.OverallRainfall,RimWorld.Planet.OverallTemperature,RimWorld.Planet.OverallPopulation,System.Collections.Generic.Dictionary`2<RimWorld.FactionDef, int>)
RimWorld.Page_CreateWorldParams:<CanDoNext>b__17_0 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

[Prepare Carefully] Could not find hairSettings field for Human
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderPawnLayers:InitializePawnLayers (Verse.ThingDef,Verse.Gender)
EdB.PrepareCarefully.ProviderPawnLayers:GetLayersForPawn (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Thing_Human370 of type Verse.Pawn. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFEAncients.Ability_Heal curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<Verse.Pawn> (string)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string)
Verse.Scribe_References:Look<Verse.Pawn> (Verse.Pawn&,string,bool)
VFECore.Abilities.Ability:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Ability_VFEA_Heal_Thing_Human370 of type VFECore.Abilities.Ability. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Verb_CastAbility(null) curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<VFECore.Abilities.Ability> (string)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string)
Verse.Scribe_References:Look<VFECore.Abilities.Ability> (VFECore.Abilities.Ability&,string,bool)
VFECore.Abilities.Verb_CastAbility:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Thing_Human376 of type Verse.Pawn. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Ability_ShootProjectile curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<Verse.Pawn> (string)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string)
Verse.Scribe_References:Look<Verse.Pawn> (Verse.Pawn&,string,bool)
VFECore.Abilities.Ability:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Ability_VFEA_FireBreath_Thing_Human376 of type VFECore.Abilities.Ability. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Verb_CastAbility(null) curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<VFECore.Abilities.Ability> (string)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string)
Verse.Scribe_References:Look<VFECore.Abilities.Ability> (VFECore.Abilities.Ability&,string,bool)
VFECore.Abilities.Verb_CastAbility:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Could not add hediff {VFEA_PlasteelClaw} to the pawn because no recipe adds it to the body part {Hand}
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.CustomPawn:InitializeInjuriesAndImplantsFromPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Thing_Human411 of type Verse.Pawn. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Ability_Barrier curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<Verse.Pawn> (string)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<Verse.Pawn> (string)
Verse.Scribe_References:Look<Verse.Pawn> (Verse.Pawn&,string,bool)
VFECore.Abilities.Ability:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

Could not resolve reference to object with loadID Ability_VFEA_Overshield_Thing_Human411 of type VFECore.Abilities.Ability. Was it compressed away, destroyed, had no ID number, or not saved/loaded right? curParent=VFECore.Abilities.Verb_CastAbility(null) curPathRelToParent=
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
Verse.LoadedObjectDirectory:ObjectWithLoadID<VFECore.Abilities.Ability> (string)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string,Verse.IExposable)
Verse.CrossRefHandler:TakeResolvedRef<VFECore.Abilities.Ability> (string)
Verse.Scribe_References:Look<VFECore.Abilities.Ability> (VFECore.Abilities.Ability&,string,bool)
VFECore.Abilities.Verb_CastAbility:ExposeData ()
EdB.PrepareCarefully.UtilityCopy:ResolveAllCrossReferences ()
EdB.PrepareCarefully.UtilityCopy:FinalizeLoading ()
EdB.PrepareCarefully.UtilityCopy:DeserializeExposable<EdB.PrepareCarefully.PawnCompsLoader> (string,object[])
EdB.PrepareCarefully.ExtensionsPawn:CopyPawnComps (Verse.Pawn,Verse.Pawn)
EdB.PrepareCarefully.ExtensionsPawn:Copy (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Could not add hediff {VFEA_PlasteelClaw} to the pawn because no recipe adds it to the body part {Hand}
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.CustomPawn:InitializeInjuriesAndImplantsFromPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PrepareCarefully:InitializePawns ()
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.RelationshipManager:CreateParentChildPawnsForStartingPawns (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.RelationshipManager:InitializeRelationshipsForStartingPawns (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.RelationshipManager:.ctor (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:InitializeRelationshipManager (System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.RelationshipManager:CreateParentChildPawnsForStartingPawns (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.RelationshipManager:InitializeRelationshipsForStartingPawns (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.RelationshipManager:.ctor (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:InitializeRelationshipManager (System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.RelationshipManager:CreateNewTemporaryPawn (Verse.Gender)
EdB.PrepareCarefully.RelationshipManager:.ctor (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:InitializeRelationshipManager (System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.RelationshipManager:CreateNewTemporaryPawn (Verse.Gender)
EdB.PrepareCarefully.RelationshipManager:.ctor (System.Collections.Generic.List`1<Verse.Pawn>,System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:InitializeRelationshipManager (System.Collections.Generic.List`1<EdB.PrepareCarefully.CustomPawn>)
EdB.PrepareCarefully.PrepareCarefully:Initialize ()
EdB.PrepareCarefully.HarmonyPatches.PrepareCarefullyButtonPatch:Postfix (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect&)
(wrapper dynamic-method) RimWorld.Page_ConfigureStartingPawns:RimWorld.Page_ConfigureStartingPawns.DoWindowContents_Patch1 (RimWorld.Page_ConfigureStartingPawns,UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Loaded equipment database with 406 material(s)
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
EdB.PrepareCarefully.Logger:Message (string)
EdB.PrepareCarefully.EquipmentDatabase:ProcessStuff ()
EdB.PrepareCarefully.EquipmentDatabase:LoadFrame ()
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Loaded equipment database with 2217 item(s)
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
EdB.PrepareCarefully.Logger:Message (string)
EdB.PrepareCarefully.EquipmentDatabase:ProcessThings ()
EdB.PrepareCarefully.EquipmentDatabase:LoadFrame ()
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.CustomPawn:InitializeWithPawn (Verse.Pawn)
EdB.PrepareCarefully.CustomPawn:.ctor (Verse.Pawn)
EdB.PrepareCarefully.PawnLoaderV5:ConvertSaveRecordToPawn (EdB.PrepareCarefully.SaveRecordPawnV5)
EdB.PrepareCarefully.PresetLoaderV5:Load (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.PresetLoader:LoadFromFile (EdB.PrepareCarefully.PrepareCarefully,string)
EdB.PrepareCarefully.Controller:LoadPreset (string)
EdB.PrepareCarefully.Page_PrepareCarefully:<DrawPresetButtons>b__36_0 (string)
EdB.PrepareCarefully.Dialog_LoadPreset:DoMapEntryInteraction (string)
EdB.PrepareCarefully.Dialog_Preset:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Could not find hairSettings field for Android1Tier
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Could not find hairSettings field for Android2Tier
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Could not find hairSettings field for Android3Tier
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Could not find hairSettings field for Android4Tier
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Could not find hairSettings field for Android5Tier
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Could not find hairSettings field for M7Mech
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Could not find hairSettings field for M8Mech
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderAlienRaces:GetFieldValue (Verse.ThingDef,object,string,bool)
EdB.PrepareCarefully.ProviderAlienRaces:InitializeAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderAlienRaces:GetAlienRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.ProviderApparel:LayerForApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:AddApparel (EdB.PrepareCarefully.OptionsApparel,Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: Middle_A
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.ProviderApparel:LayerForApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:AddApparel (EdB.PrepareCarefully.OptionsApparel,Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

[Prepare Carefully] Cannot find matching layer for apparel.  Last layer: EyeCover
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Warning (string)
EdB.PrepareCarefully.Logger:Warning (string)
EdB.PrepareCarefully.ProviderPawnLayers:FindLayerForApparel (RimWorld.ApparelProperties)
EdB.PrepareCarefully.ProviderApparel:LayerForApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:AddApparel (EdB.PrepareCarefully.OptionsApparel,Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:InitializeHumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:get_HumanlikeApparel ()
EdB.PrepareCarefully.ProviderApparel:InitializeApparel (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (Verse.ThingDef)
EdB.PrepareCarefully.ProviderApparel:GetApparelForRace (EdB.PrepareCarefully.CustomPawn)
EdB.PrepareCarefully.PanelAppearance:DrawPanelContent (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.PanelBase:Draw (EdB.PrepareCarefully.State)
EdB.PrepareCarefully.TabViewPawns:Draw (EdB.PrepareCarefully.State,UnityEngine.Rect)
EdB.PrepareCarefully.Page_PrepareCarefully:DoWindowContents (UnityEngine.Rect)
Verse.Window:InnerWindowOnGUI (int)
UnityEngine.GUI:CallWindowDelegate (UnityEngine.GUI/WindowFunction,int,int,UnityEngine.GUISkin,int,single,single,UnityEngine.GUIStyle)

QualityBuilder added property to '0' things
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
QualityBuilder.ModInitializerComponent:FixedUpdate ()

Initializing new game with mods:
  - brrainz.harmony
  - Ludeon.RimWorld
  - Ludeon.RimWorld.Ideology
  - Ludeon.RimWorld.Royalty
  - ccl.patchoperation.highlander
  - UnlimitedHugs.HugsLib
  - spdskatr.projectrimfactory
  - Fluffy.ModManager
  - UnlimitedHugs.AllowTool
  - VouLT.BetterPawnControl
  - hatti.cleaningarea
  - erdelf.HumanoidAlienRaces
  - UnlimitedHugs.DefensivePositions
  - Dubwise.DubsMintMenus
  - jecrell.jecstools
  - Dubwise.DubsBadHygiene
  - EdB.PrepareCarefully.UnofficialPatch
  - Uuugggg.EverybodyGetsOne
  - rimfridge.kv.rw
  - trinity.RuntimeGCupdated
  - targhetti.ShowDrafteesWeapon
  - OskarPotocki.VanillaFactionsExpanded.Core
  - OskarPotocki.VFE.Pirates
  - VanillaExpanded.VFEFarming
  - VanillaExpanded.VFECore
  - VanillaExpanded.VCookE
  - VanillaExpanded.VMemesE
  - tammybee.whereismyweapon
  - ReGrowth.BOTR.Core
  - VanillaExpanded.VFESecurity
  - com.yayo.combat3
  - Burusutazu.ImpassableFences
  - tikubonn.DontBlockDoor
  - KamiKatze.MaterialFilter
  - erdelf.MinifyEverything
  - weilbyte.nopowerwires
  - JBloodthorn.NoLazyDoctors
  - fed1sPlay.PawnTargetFix
  - hatti.qualitybuilder
  - Scherub.realisticrooms
  - Haplo.Miscellaneous.Core
  - automatic.recipeicons
  - Uuugggg.ReplaceStuff
  - roolo.RunAndGun
  - roolo.SearchAndDestroy
  - dhultgren.smarterconstruction
  - TradingControl.Common.Core
  - Fisi.UndergroundWires
  - VanillaExpanded.VARME
  - Fluffy.WorkTab
  - avilmask.GrazingLands
  - brrainz.achtung
  - Fluffy.MedicalTab
  - VSE.PerryPersistent
  - VanillaExpanded.VFEPower
  - automatic.autolinks
  - falconne.BWM
  - notfood.SeedsPlease
  - Dubwise.Rimefeller
  - dismarzero.VGP.VGPVegetableGarden
  - falconne.AFF
  - arl85.AnimalsAgeFilter
  - Haplo.Miscellaneous.Robots
  - Owlchemist.CleanPathfinding
  - dracoix.doormat.r12a
  - jecrell.doorsexpanded
  - VanillaExpanded.VWEC
  - InsertKey.ItemListSelector
  - notfood.MendAndRecycle
  - PeteTimesSix.SimpleSidearms
  - impassablemapmaker.kv.rw
  - Indeed.StackXXL
  - LWM.DeepStorage
  - hobtook.tradeui
  - pyrce.mass.graves
  - O.inf.reinforce
  - PeteTimesSix.CompactHediffs
  - FrozenSnowFox.FilthVanishesWithRainAndTime
  - newcolonist.largefactionbases
  - Mehni.PickUpAndHaul
  - denev.SmartTurretCovering
  - VanillaExpanded.VCookEStews
  - VanillaExpanded.VEE
  - Prolle.Glitterworld.Medicine
  - Ogliss.TheWhiteCrayon.Quarry
  - neceros.ceilinglights
  - Murmur.WallLight
  - velc.TrapDisable
  - Karthas.EngravedWalls
  - nep.smallerlandingpads
  - Aoba.WarCasket
  - dismarzero.VGP.VGPGardenMedicine
  - whooooooooooo.SmoothWalls
  - cucumpear.embrasures
  - Atlas.AndroidTiers
  - CarnySenpai.EnableOversizedWeapons
  - avilmask.CommonSense
  - Fluffy.Blueprints
  - ADE.pulseTurrets.Mod
  - Fluffy.DesirePaths
  - saloid.DynamicEconomy
  - Saakra.Empire
  - Cliffyq.FootTrafficHeatmap
  - Aoba.Fortress.Industrial
  - m00nl1ght.GeologicalLandforms
  - roolo.giddyupcore
  - roolo.giddyupcaravan
  - roolo.giddyuprideandroll
  - JPT.HumanResources
  - Alaestor.MiscRobots.PlusPlus
  - Haplo.Miscellaneous.TurretBaseAndObjects
  - telardo.NoLaggyBed
  - hobtook.mortaraccuracy
  - spdskatr.projectrimfactory.drones
  - PRF.Materials
  - ratys.rtfuse
  - Owlchemist.SmartFarming
  - nephlite.orbitaltradecolumn
  - VanillaExpanded.VFEA
  - VanillaExpanded.VWEL
  - Dra.YayoCombatWarcaskets
  - Sk.WeaponMastery
  - VanillaExpanded.Ideo.RelicsAndArtifacts
  - VanillaExpanded.VFEProduction
  - VinaLx.ResearchPalForked
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

TrafficHeatmap ctor 1388326912
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
TrafficHeatmap.FootTrafficHeatmap:.ctor (Verse.Map)
System.Reflection.MonoCMethod:InternalInvoke (object,object[])
System.Reflection.MonoCMethod:DoInvoke (object,System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo)
System.Reflection.MonoCMethod:Invoke (System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo)
System.RuntimeType:CreateInstanceImpl (System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo,object[],System.Threading.StackCrawlMark&)
System.Activator:CreateInstance (System.Type,System.Reflection.BindingFlags,System.Reflection.Binder,object[],System.Globalization.CultureInfo,object[])
System.Activator:CreateInstance (System.Type,object[])
Verse.Map:FillComponents ()
(wrapper dynamic-method) Verse.Map:Verse.Map.ConstructComponents_Patch1 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

[HumanResources] Found 1 weapons, 0 starting techs from the scenario and 17 from the player faction.
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
HumanResources.UnlockManager:RegisterStartingResources ()
HumanResources.UnlockManager:NewGameStarted ()
HumanResources.ModBaseHumanResources:MapComponentsInitializing (Verse.Map)
HugsLib.HugsLibController:OnMapComponentsConstructed (Verse.Map)
HugsLib.Patches.Map_ConstructComponents_Patch:MapComponentsInitHook (Verse.Map)
(wrapper dynamic-method) Verse.Map:Verse.Map.ConstructComponents_Patch1 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Can't enable CompPowerTrader(parent=VFEA_Turret_AncientPointDefense64390 at=(95, 0, 132))
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:TryTurnOnImmediately (RimWorld.CompPowerTrader,Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:EnsurePowerUsersConnected (Verse.Map)
VFEAncients.ScenPart_ReconnectAllPowerBuildings:PostMapGenerate (Verse.Map)
RimWorld.Scenario:PostMapGenerate (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

ShallowReservoirSeed == 0 Regenerating seeds
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
Rimefeller.MapComponent_Rimefeller:FinalizeInit ()
Verse.MapComponentUtility:FinalizeInit (Verse.Map)
(wrapper dynamic-method) Verse.Map:Verse.Map.FinalizeInit_Patch2 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

TrafficHeatmap FinalizeInit 1388326912
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
TrafficHeatmap.FootTrafficHeatmap:FinalizeInit ()
Verse.MapComponentUtility:FinalizeInit (Verse.Map)
(wrapper dynamic-method) Verse.Map:Verse.Map.FinalizeInit_Patch2 (Verse.Map)
(wrapper dynamic-method) Verse.MapGenerator:Verse.MapGenerator.GenerateMap_Patch4 (Verse.IntVec3,RimWorld.Planet.MapParent,Verse.MapGeneratorDef,System.Collections.Generic.IEnumerable`1<Verse.GenStepWithParams>,System.Action`1<Verse.Map>)
(wrapper dynamic-method) Verse.Game:Verse.Game.InitNewGame_Patch2 (Verse.Game)
Verse.Root_Play/<>c:<Start>b__1_2 ()
Verse.LongEventHandler:RunEventFromAnotherThread (System.Action)
Verse.LongEventHandler/<>c:<UpdateCurrentAsynchronousEvent>b__27_0 ()
System.Threading.ThreadHelper:ThreadStart_Context (object)
System.Threading.ExecutionContext:RunInternal (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object,bool)
System.Threading.ExecutionContext:Run (System.Threading.ExecutionContext,System.Threading.ContextCallback,object)
System.Threading.ThreadHelper:ThreadStart ()

Updating Empire to Latest Version
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Resetting faction leaders
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.SoS2HarmonyPatches:ResetFactionLeaders (bool)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Empire - Testing for traits with no tie
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Empire - Testing for invalid capital map
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:MessagePlayerAboutConfigErrors (FactionColonies.FactionFC)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()

Empire - Testing for update change
UnityEngine.StackTraceUtility:ExtractStackTrace ()
Verse.Log:Message (string)
FactionColonies.FactionColonies:UpdateChanges ()
FactionColonies.FactionFC:WorldComponentTick ()
RimWorld.Planet.WorldComponentUtility:WorldComponentTick (RimWorld.Planet.World)
RimWorld.Planet.World:WorldTick ()
(wrapper dynamic-method) Verse.TickManager:Verse.TickManager.DoSingleTick_Patch2 (Verse.TickManager)
Verse.TickManager:TickManagerUpdate ()
Verse.Game:UpdatePlay ()
Verse.Root_Play:Update ()
