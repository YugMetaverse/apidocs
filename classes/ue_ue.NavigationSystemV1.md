[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavigationSystemV1

# Class: NavigationSystemV1

[ue/ue](../modules/ue_ue.md).NavigationSystemV1

## Hierarchy

- [`NavigationSystemBase`](ue_ue.NavigationSystemBase.md)

  ↳ **`NavigationSystemV1`**

## Table of contents

### Constructors

- [constructor](ue_ue.NavigationSystemV1.md#constructor)

### Properties

- [AbstractNavData](ue_ue.NavigationSystemV1.md#abstractnavdata)
- [ActiveTilesUpdateInterval](ue_ue.NavigationSystemV1.md#activetilesupdateinterval)
- [CrowdManagerClass](ue_ue.NavigationSystemV1.md#crowdmanagerclass)
- [DataGatheringMode](ue_ue.NavigationSystemV1.md#datagatheringmode)
- [DefaultAgentName](ue_ue.NavigationSystemV1.md#defaultagentname)
- [DirtyAreasUpdateFreq](ue_ue.NavigationSystemV1.md#dirtyareasupdatefreq)
- [MainNavData](ue_ue.NavigationSystemV1.md#mainnavdata)
- [NavDataRegistrationQueue](ue_ue.NavigationSystemV1.md#navdataregistrationqueue)
- [NavDataSet](ue_ue.NavigationSystemV1.md#navdataset)
- [OnNavDataRegisteredEvent](ue_ue.NavigationSystemV1.md#onnavdataregisteredevent)
- [OnNavigationGenerationFinishedDelegate](ue_ue.NavigationSystemV1.md#onnavigationgenerationfinisheddelegate)
- [OperationMode](ue_ue.NavigationSystemV1.md#operationmode)
- [SupportedAgents](ue_ue.NavigationSystemV1.md#supportedagents)
- [SupportedAgentsMask](ue_ue.NavigationSystemV1.md#supportedagentsmask)
- [\_\_tid\_NavigationSystemBase\_\_](ue_ue.NavigationSystemV1.md#__tid_navigationsystembase__)
- [\_\_tid\_NavigationSystemV1\_\_](ue_ue.NavigationSystemV1.md#__tid_navigationsystemv1__)
- [\_\_tid\_Object\_\_](ue_ue.NavigationSystemV1.md#__tid_object__)
- [bAllowClientSideNavigation](ue_ue.NavigationSystemV1.md#ballowclientsidenavigation)
- [bAutoCreateNavigationData](ue_ue.NavigationSystemV1.md#bautocreatenavigationdata)
- [bGenerateNavigationOnlyAroundNavigationInvokers](ue_ue.NavigationSystemV1.md#bgeneratenavigationonlyaroundnavigationinvokers)
- [bInitialBuildingLocked](ue_ue.NavigationSystemV1.md#binitialbuildinglocked)
- [bShouldDiscardSubLevelNavData](ue_ue.NavigationSystemV1.md#bshoulddiscardsublevelnavdata)
- [bSkipAgentHeightCheckWhenPickingNavData](ue_ue.NavigationSystemV1.md#bskipagentheightcheckwhenpickingnavdata)
- [bSpawnNavDataInNavBoundsLevel](ue_ue.NavigationSystemV1.md#bspawnnavdatainnavboundslevel)
- [bSupportRebuilding](ue_ue.NavigationSystemV1.md#bsupportrebuilding)
- [bTickWhilePaused](ue_ue.NavigationSystemV1.md#btickwhilepaused)

### Methods

- [CreateDefaultSubobject](ue_ue.NavigationSystemV1.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NavigationSystemV1.md#executeubergraph)
- [GetClass](ue_ue.NavigationSystemV1.md#getclass)
- [GetName](ue_ue.NavigationSystemV1.md#getname)
- [GetOuter](ue_ue.NavigationSystemV1.md#getouter)
- [GetWorld](ue_ue.NavigationSystemV1.md#getworld)
- [K2\_ReplaceAreaInOctreeData](ue_ue.NavigationSystemV1.md#k2_replaceareainoctreedata)
- [OnNavigationBoundsUpdated](ue_ue.NavigationSystemV1.md#onnavigationboundsupdated)
- [RegisterNavigationInvoker](ue_ue.NavigationSystemV1.md#registernavigationinvoker)
- [ResetMaxSimultaneousTileGenerationJobsCount](ue_ue.NavigationSystemV1.md#resetmaxsimultaneoustilegenerationjobscount)
- [SetGeometryGatheringMode](ue_ue.NavigationSystemV1.md#setgeometrygatheringmode)
- [SetMaxSimultaneousTileGenerationJobsCount](ue_ue.NavigationSystemV1.md#setmaxsimultaneoustilegenerationjobscount)
- [UnregisterNavigationInvoker](ue_ue.NavigationSystemV1.md#unregisternavigationinvoker)
- [Find](ue_ue.NavigationSystemV1.md#find)
- [FindPathToActorSynchronously](ue_ue.NavigationSystemV1.md#findpathtoactorsynchronously)
- [FindPathToLocationSynchronously](ue_ue.NavigationSystemV1.md#findpathtolocationsynchronously)
- [GetNavigationSystem](ue_ue.NavigationSystemV1.md#getnavigationsystem)
- [GetPathCost](ue_ue.NavigationSystemV1.md#getpathcost)
- [GetPathLength](ue_ue.NavigationSystemV1.md#getpathlength)
- [GetRandomPointInNavigableRadius](ue_ue.NavigationSystemV1.md#getrandompointinnavigableradius)
- [GetRandomReachablePointInRadius](ue_ue.NavigationSystemV1.md#getrandomreachablepointinradius)
- [IsNavigationBeingBuilt](ue_ue.NavigationSystemV1.md#isnavigationbeingbuilt)
- [IsNavigationBeingBuiltOrLocked](ue_ue.NavigationSystemV1.md#isnavigationbeingbuiltorlocked)
- [K2\_GetRandomLocationInNavigableRadius](ue_ue.NavigationSystemV1.md#k2_getrandomlocationinnavigableradius)
- [K2\_GetRandomPointInNavigableRadius](ue_ue.NavigationSystemV1.md#k2_getrandompointinnavigableradius)
- [K2\_GetRandomReachablePointInRadius](ue_ue.NavigationSystemV1.md#k2_getrandomreachablepointinradius)
- [K2\_ProjectPointToNavigation](ue_ue.NavigationSystemV1.md#k2_projectpointtonavigation)
- [Load](ue_ue.NavigationSystemV1.md#load)
- [NavigationRaycast](ue_ue.NavigationSystemV1.md#navigationraycast)
- [ProjectPointToNavigation](ue_ue.NavigationSystemV1.md#projectpointtonavigation)
- [SimpleMoveToActor](ue_ue.NavigationSystemV1.md#simplemovetoactor)
- [SimpleMoveToLocation](ue_ue.NavigationSystemV1.md#simplemovetolocation)
- [StaticClass](ue_ue.NavigationSystemV1.md#staticclass)

## Constructors

### constructor

• **new NavigationSystemV1**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[constructor](ue_ue.NavigationSystemBase.md#constructor)

## Properties

### AbstractNavData

• **AbstractNavData**: [`NavigationData`](ue_ue.NavigationData.md)

___

### ActiveTilesUpdateInterval

• **ActiveTilesUpdateInterval**: `number`

___

### CrowdManagerClass

• **CrowdManagerClass**: [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`CrowdManagerBase`](ue_ue.CrowdManagerBase.md)\>

___

### DataGatheringMode

• **DataGatheringMode**: [`ENavDataGatheringModeConfig`](../enums/ue_ue.ENavDataGatheringModeConfig.md)

___

### DefaultAgentName

• **DefaultAgentName**: `string`

___

### DirtyAreasUpdateFreq

• **DirtyAreasUpdateFreq**: `number`

___

### MainNavData

• **MainNavData**: [`NavigationData`](ue_ue.NavigationData.md)

___

### NavDataRegistrationQueue

• **NavDataRegistrationQueue**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavigationData`](ue_ue.NavigationData.md)\>

___

### NavDataSet

• **NavDataSet**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavigationData`](ue_ue.NavigationData.md)\>

___

### OnNavDataRegisteredEvent

• **OnNavDataRegisteredEvent**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NavData`: [`$Nullable`](../modules/puerts.md#$nullable)<[`NavigationData`](ue_ue.NavigationData.md)\>) => `void`\>

___

### OnNavigationGenerationFinishedDelegate

• **OnNavigationGenerationFinishedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NavData`: [`$Nullable`](../modules/puerts.md#$nullable)<[`NavigationData`](ue_ue.NavigationData.md)\>) => `void`\>

___

### OperationMode

• **OperationMode**: [`FNavigationSystemRunMode`](../enums/ue_ue.FNavigationSystemRunMode.md)

___

### SupportedAgents

• **SupportedAgents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavDataConfig`](ue_ue.NavDataConfig.md)\>

___

### SupportedAgentsMask

• **SupportedAgentsMask**: [`NavAgentSelector`](ue_ue.NavAgentSelector.md)

___

### \_\_tid\_NavigationSystemBase\_\_

• **\_\_tid\_NavigationSystemBase\_\_**: `boolean`

#### Inherited from

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[__tid_NavigationSystemBase__](ue_ue.NavigationSystemBase.md#__tid_navigationsystembase__)

___

### \_\_tid\_NavigationSystemV1\_\_

• **\_\_tid\_NavigationSystemV1\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[__tid_Object__](ue_ue.NavigationSystemBase.md#__tid_object__)

___

### bAllowClientSideNavigation

• **bAllowClientSideNavigation**: `boolean`

___

### bAutoCreateNavigationData

• **bAutoCreateNavigationData**: `boolean`

___

### bGenerateNavigationOnlyAroundNavigationInvokers

• **bGenerateNavigationOnlyAroundNavigationInvokers**: `boolean`

___

### bInitialBuildingLocked

• **bInitialBuildingLocked**: `boolean`

___

### bShouldDiscardSubLevelNavData

• **bShouldDiscardSubLevelNavData**: `boolean`

___

### bSkipAgentHeightCheckWhenPickingNavData

• **bSkipAgentHeightCheckWhenPickingNavData**: `boolean`

___

### bSpawnNavDataInNavBoundsLevel

• **bSpawnNavDataInNavBoundsLevel**: `boolean`

___

### bSupportRebuilding

• **bSupportRebuilding**: `boolean`

___

### bTickWhilePaused

• **bTickWhilePaused**: `boolean`

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[CreateDefaultSubobject](ue_ue.NavigationSystemBase.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[ExecuteUbergraph](ue_ue.NavigationSystemBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[GetClass](ue_ue.NavigationSystemBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[GetName](ue_ue.NavigationSystemBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[GetOuter](ue_ue.NavigationSystemBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[GetWorld](ue_ue.NavigationSystemBase.md#getworld)

___

### K2\_ReplaceAreaInOctreeData

▸ **K2_ReplaceAreaInOctreeData**(`Object`, `OldArea`, `NewArea`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `OldArea` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `NewArea` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`boolean`

___

### OnNavigationBoundsUpdated

▸ **OnNavigationBoundsUpdated**(`NavVolume`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NavVolume` | [`$Nullable`](../modules/puerts.md#$nullable)<[`NavMeshBoundsVolume`](ue_ue.NavMeshBoundsVolume.md)\> |

#### Returns

`void`

___

### RegisterNavigationInvoker

▸ **RegisterNavigationInvoker**(`Invoker`, `TileGenerationRadius?`, `TileRemovalRadius?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Invoker` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `TileGenerationRadius?` | `number` |
| `TileRemovalRadius?` | `number` |

#### Returns

`void`

___

### ResetMaxSimultaneousTileGenerationJobsCount

▸ **ResetMaxSimultaneousTileGenerationJobsCount**(): `void`

#### Returns

`void`

___

### SetGeometryGatheringMode

▸ **SetGeometryGatheringMode**(`NewMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMode` | [`ENavDataGatheringModeConfig`](../enums/ue_ue.ENavDataGatheringModeConfig.md) |

#### Returns

`void`

___

### SetMaxSimultaneousTileGenerationJobsCount

▸ **SetMaxSimultaneousTileGenerationJobsCount**(`MaxNumberOfJobs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaxNumberOfJobs` | `number` |

#### Returns

`void`

___

### UnregisterNavigationInvoker

▸ **UnregisterNavigationInvoker**(`Invoker`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Invoker` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavigationSystemV1`](ue_ue.NavigationSystemV1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavigationSystemV1`](ue_ue.NavigationSystemV1.md)

#### Overrides

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[Find](ue_ue.NavigationSystemBase.md#find)

___

### FindPathToActorSynchronously

▸ `Static` **FindPathToActorSynchronously**(`WorldContextObject`, `PathStart`, `GoalActor`, `TetherDistance?`, `PathfindingContext?`, `FilterClass?`): [`NavigationPath`](ue_ue.NavigationPath.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PathStart` | [`Vector`](ue_ue_s.Vector.md) |
| `GoalActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `TetherDistance?` | `number` |
| `PathfindingContext?` | [`Actor`](ue_ue.Actor.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |

#### Returns

[`NavigationPath`](ue_ue.NavigationPath.md)

___

### FindPathToLocationSynchronously

▸ `Static` **FindPathToLocationSynchronously**(`WorldContextObject`, `PathStart`, `PathEnd`, `PathfindingContext?`, `FilterClass?`): [`NavigationPath`](ue_ue.NavigationPath.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PathStart` | [`Vector`](ue_ue_s.Vector.md) |
| `PathEnd` | [`Vector`](ue_ue_s.Vector.md) |
| `PathfindingContext?` | [`Actor`](ue_ue.Actor.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |

#### Returns

[`NavigationPath`](ue_ue.NavigationPath.md)

___

### GetNavigationSystem

▸ `Static` **GetNavigationSystem**(`WorldContextObject`): [`NavigationSystemV1`](ue_ue.NavigationSystemV1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`NavigationSystemV1`](ue_ue.NavigationSystemV1.md)

___

### GetPathCost

▸ `Static` **GetPathCost**(`WorldContextObject`, `PathStart`, `PathEnd`, `PathCost`, `NavData?`, `FilterClass?`): [`ENavigationQueryResult`](../enums/ue_ue.ENavigationQueryResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PathStart` | [`Vector`](ue_ue_s.Vector.md) |
| `PathEnd` | [`Vector`](ue_ue_s.Vector.md) |
| `PathCost` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `NavData?` | [`NavigationData`](ue_ue.NavigationData.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |

#### Returns

[`ENavigationQueryResult`](../enums/ue_ue.ENavigationQueryResult.md)

___

### GetPathLength

▸ `Static` **GetPathLength**(`WorldContextObject`, `PathStart`, `PathEnd`, `PathLength`, `NavData?`, `FilterClass?`): [`ENavigationQueryResult`](../enums/ue_ue.ENavigationQueryResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PathStart` | [`Vector`](ue_ue_s.Vector.md) |
| `PathEnd` | [`Vector`](ue_ue_s.Vector.md) |
| `PathLength` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `NavData?` | [`NavigationData`](ue_ue.NavigationData.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |

#### Returns

[`ENavigationQueryResult`](../enums/ue_ue.ENavigationQueryResult.md)

___

### GetRandomPointInNavigableRadius

▸ `Static` **GetRandomPointInNavigableRadius**(`WorldContextObject`, `Origin`, `Radius`, `NavData?`, `FilterClass?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `Radius` | `number` |
| `NavData?` | [`NavigationData`](ue_ue.NavigationData.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetRandomReachablePointInRadius

▸ `Static` **GetRandomReachablePointInRadius**(`WorldContextObject`, `Origin`, `Radius`, `NavData?`, `FilterClass?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `Radius` | `number` |
| `NavData?` | [`NavigationData`](ue_ue.NavigationData.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### IsNavigationBeingBuilt

▸ `Static` **IsNavigationBeingBuilt**(`WorldContextObject`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

___

### IsNavigationBeingBuiltOrLocked

▸ `Static` **IsNavigationBeingBuiltOrLocked**(`WorldContextObject`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

___

### K2\_GetRandomLocationInNavigableRadius

▸ `Static` **K2_GetRandomLocationInNavigableRadius**(`WorldContextObject`, `Origin`, `RandomLocation`, `Radius`, `NavData?`, `FilterClass?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `RandomLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Radius` | `number` |
| `NavData?` | [`NavigationData`](ue_ue.NavigationData.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |

#### Returns

`boolean`

___

### K2\_GetRandomPointInNavigableRadius

▸ `Static` **K2_GetRandomPointInNavigableRadius**(`WorldContextObject`, `Origin`, `RandomLocation`, `Radius`, `NavData?`, `FilterClass?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `RandomLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Radius` | `number` |
| `NavData?` | [`NavigationData`](ue_ue.NavigationData.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |

#### Returns

`boolean`

___

### K2\_GetRandomReachablePointInRadius

▸ `Static` **K2_GetRandomReachablePointInRadius**(`WorldContextObject`, `Origin`, `RandomLocation`, `Radius`, `NavData?`, `FilterClass?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `RandomLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Radius` | `number` |
| `NavData?` | [`NavigationData`](ue_ue.NavigationData.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |

#### Returns

`boolean`

___

### K2\_ProjectPointToNavigation

▸ `Static` **K2_ProjectPointToNavigation**(`WorldContextObject`, `Point`, `ProjectedLocation`, `NavData`, `FilterClass`, `QueryExtent?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `ProjectedLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `NavData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`NavigationData`](ue_ue.NavigationData.md)\> |
| `FilterClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `QueryExtent?` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`NavigationSystemV1`](ue_ue.NavigationSystemV1.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavigationSystemV1`](ue_ue.NavigationSystemV1.md)

#### Overrides

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[Load](ue_ue.NavigationSystemBase.md#load)

___

### NavigationRaycast

▸ `Static` **NavigationRaycast**(`WorldContextObject`, `RayStart`, `RayEnd`, `HitLocation`, `FilterClass?`, `Querier?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `RayStart` | [`Vector`](ue_ue_s.Vector.md) |
| `RayEnd` | [`Vector`](ue_ue_s.Vector.md) |
| `HitLocation` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |
| `Querier?` | [`Controller`](ue_ue.Controller.md) |

#### Returns

`boolean`

___

### ProjectPointToNavigation

▸ `Static` **ProjectPointToNavigation**(`WorldContextObject`, `Point`, `NavData?`, `FilterClass?`, `QueryExtent?`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `NavData?` | [`NavigationData`](ue_ue.NavigationData.md) |
| `FilterClass?` | [`Class`](ue_ue.Class.md) |
| `QueryExtent?` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### SimpleMoveToActor

▸ `Static` **SimpleMoveToActor**(`Controller`, `Goal`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Controller` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `Goal` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### SimpleMoveToLocation

▸ `Static` **SimpleMoveToLocation**(`Controller`, `Goal`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Controller` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `Goal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavigationSystemBase](ue_ue.NavigationSystemBase.md).[StaticClass](ue_ue.NavigationSystemBase.md#staticclass)
