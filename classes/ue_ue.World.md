[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / World

# Class: World

[ue/ue](../modules/ue_ue.md).World

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`World`**

## Table of contents

### Constructors

- [constructor](ue_ue.World.md#constructor)

### Properties

- [AISystem](ue_ue.World.md#aisystem)
- [ActiveGroupActors](ue_ue.World.md#activegroupactors)
- [AuthorityGameMode](ue_ue.World.md#authoritygamemode)
- [AvoidanceManager](ue_ue.World.md#avoidancemanager)
- [CanvasForDrawMaterialToRenderTarget](ue_ue.World.md#canvasfordrawmaterialtorendertarget)
- [CanvasForRenderingToTarget](ue_ue.World.md#canvasforrenderingtotarget)
- [ComponentsThatNeedEndOfFrameUpdate](ue_ue.World.md#componentsthatneedendofframeupdate)
- [ComponentsThatNeedEndOfFrameUpdate\_OnGameThread](ue_ue.World.md#componentsthatneedendofframeupdate_ongamethread)
- [CurrentLevel](ue_ue.World.md#currentlevel)
- [CurrentLevelPendingInvisibility](ue_ue.World.md#currentlevelpendinginvisibility)
- [CurrentLevelPendingVisibility](ue_ue.World.md#currentlevelpendingvisibility)
- [DefaultPhysicsVolume](ue_ue.World.md#defaultphysicsvolume)
- [DemoNetDriver](ue_ue.World.md#demonetdriver)
- [EditorViews](ue_ue.World.md#editorviews)
- [ExtraReferencedObjects](ue_ue.World.md#extrareferencedobjects)
- [ForegroundLineBatcher](ue_ue.World.md#foregroundlinebatcher)
- [GameState](ue_ue.World.md#gamestate)
- [Layers](ue_ue.World.md#layers)
- [LevelCollections](ue_ue.World.md#levelcollections)
- [LevelSequenceActors](ue_ue.World.md#levelsequenceactors)
- [Levels](ue_ue.World.md#levels)
- [LineBatcher](ue_ue.World.md#linebatcher)
- [MyParticleEventManager](ue_ue.World.md#myparticleeventmanager)
- [NavigationSystem](ue_ue.World.md#navigationsystem)
- [NetDriver](ue_ue.World.md#netdriver)
- [NetworkManager](ue_ue.World.md#networkmanager)
- [OwningGameInstance](ue_ue.World.md#owninggameinstance)
- [PSCPool](ue_ue.World.md#pscpool)
- [ParameterCollectionInstances](ue_ue.World.md#parametercollectioninstances)
- [PerModuleDataObjects](ue_ue.World.md#permoduledataobjects)
- [PersistentLevel](ue_ue.World.md#persistentlevel)
- [PersistentLineBatcher](ue_ue.World.md#persistentlinebatcher)
- [PhysicsCollisionHandler](ue_ue.World.md#physicscollisionhandler)
- [SelectedLevels](ue_ue.World.md#selectedlevels)
- [StreamingLevels](ue_ue.World.md#streaminglevels)
- [StreamingLevelsPrefix](ue_ue.World.md#streaminglevelsprefix)
- [StreamingLevelsToConsider](ue_ue.World.md#streaminglevelstoconsider)
- [ThumbnailInfo](ue_ue.World.md#thumbnailinfo)
- [WorldComposition](ue_ue.World.md#worldcomposition)
- [\_\_tid\_Object\_\_](ue_ue.World.md#__tid_object__)
- [\_\_tid\_World\_\_](ue_ue.World.md#__tid_world__)
- [bAreConstraintsDirty](ue_ue.World.md#bareconstraintsdirty)

### Methods

- [CreateDefaultSubobject](ue_ue.World.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.World.md#executeubergraph)
- [GetClass](ue_ue.World.md#getclass)
- [GetName](ue_ue.World.md#getname)
- [GetOuter](ue_ue.World.md#getouter)
- [GetWorld](ue_ue.World.md#getworld)
- [HandleTimelineScrubbed](ue_ue.World.md#handletimelinescrubbed)
- [K2\_GetWorldSettings](ue_ue.World.md#k2_getworldsettings)
- [SpawnActor](ue_ue.World.md#spawnactor)
- [Find](ue_ue.World.md#find)
- [Load](ue_ue.World.md#load)
- [StaticClass](ue_ue.World.md#staticclass)

## Constructors

### constructor

• **new World**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AISystem

• **AISystem**: [`AISystemBase`](ue_ue.AISystemBase.md)

___

### ActiveGroupActors

• **ActiveGroupActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### AuthorityGameMode

• **AuthorityGameMode**: [`GameModeBase`](ue_ue.GameModeBase.md)

___

### AvoidanceManager

• **AvoidanceManager**: [`AvoidanceManager`](ue_ue.AvoidanceManager.md)

___

### CanvasForDrawMaterialToRenderTarget

• **CanvasForDrawMaterialToRenderTarget**: [`Canvas`](ue_ue.Canvas.md)

___

### CanvasForRenderingToTarget

• **CanvasForRenderingToTarget**: [`Canvas`](ue_ue.Canvas.md)

___

### ComponentsThatNeedEndOfFrameUpdate

• **ComponentsThatNeedEndOfFrameUpdate**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

___

### ComponentsThatNeedEndOfFrameUpdate\_OnGameThread

• **ComponentsThatNeedEndOfFrameUpdate\_OnGameThread**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

___

### CurrentLevel

• **CurrentLevel**: [`Level`](ue_ue.Level.md)

___

### CurrentLevelPendingInvisibility

• **CurrentLevelPendingInvisibility**: [`Level`](ue_ue.Level.md)

___

### CurrentLevelPendingVisibility

• **CurrentLevelPendingVisibility**: [`Level`](ue_ue.Level.md)

___

### DefaultPhysicsVolume

• **DefaultPhysicsVolume**: [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

___

### DemoNetDriver

• **DemoNetDriver**: [`DemoNetDriver`](ue_ue.DemoNetDriver.md)

___

### EditorViews

• **EditorViews**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelViewportInfo`](ue_ue.LevelViewportInfo.md)\>

___

### ExtraReferencedObjects

• **ExtraReferencedObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### ForegroundLineBatcher

• **ForegroundLineBatcher**: [`LineBatchComponent`](ue_ue.LineBatchComponent.md)

___

### GameState

• **GameState**: [`GameStateBase`](ue_ue.GameStateBase.md)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Layer`](ue_ue.Layer.md)\>

___

### LevelCollections

• **LevelCollections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelCollection`](ue_ue.LevelCollection.md)\>

___

### LevelSequenceActors

• **LevelSequenceActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### Levels

• **Levels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Level`](ue_ue.Level.md)\>

___

### LineBatcher

• **LineBatcher**: [`LineBatchComponent`](ue_ue.LineBatchComponent.md)

___

### MyParticleEventManager

• **MyParticleEventManager**: [`ParticleEventManager`](ue_ue.ParticleEventManager.md)

___

### NavigationSystem

• **NavigationSystem**: [`NavigationSystemBase`](ue_ue.NavigationSystemBase.md)

___

### NetDriver

• **NetDriver**: [`NetDriver`](ue_ue.NetDriver.md)

___

### NetworkManager

• **NetworkManager**: [`GameNetworkManager`](ue_ue.GameNetworkManager.md)

___

### OwningGameInstance

• **OwningGameInstance**: [`GameInstance`](ue_ue.GameInstance.md)

___

### PSCPool

• **PSCPool**: [`WorldPSCPool`](ue_ue.WorldPSCPool.md)

___

### ParameterCollectionInstances

• **ParameterCollectionInstances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialParameterCollectionInstance`](ue_ue.MaterialParameterCollectionInstance.md)\>

___

### PerModuleDataObjects

• **PerModuleDataObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### PersistentLevel

• **PersistentLevel**: [`Level`](ue_ue.Level.md)

___

### PersistentLineBatcher

• **PersistentLineBatcher**: [`LineBatchComponent`](ue_ue.LineBatchComponent.md)

___

### PhysicsCollisionHandler

• **PhysicsCollisionHandler**: [`PhysicsCollisionHandler`](ue_ue.PhysicsCollisionHandler.md)

___

### SelectedLevels

• **SelectedLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Level`](ue_ue.Level.md)\>

___

### StreamingLevels

• **StreamingLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelStreaming`](ue_ue.LevelStreaming.md)\>

___

### StreamingLevelsPrefix

• **StreamingLevelsPrefix**: `string`

___

### StreamingLevelsToConsider

• **StreamingLevelsToConsider**: [`StreamingLevelsToConsider`](ue_ue.StreamingLevelsToConsider.md)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

___

### WorldComposition

• **WorldComposition**: [`WorldComposition`](ue_ue.WorldComposition.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_World\_\_

• **\_\_tid\_World\_\_**: `boolean`

___

### bAreConstraintsDirty

• **bAreConstraintsDirty**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### HandleTimelineScrubbed

▸ **HandleTimelineScrubbed**(): `void`

#### Returns

`void`

___

### K2\_GetWorldSettings

▸ **K2_GetWorldSettings**(): [`WorldSettings`](ue_ue.WorldSettings.md)

#### Returns

[`WorldSettings`](ue_ue.WorldSettings.md)

___

### SpawnActor

▸ **SpawnActor**(`Class`, `Transform`, `SpawnCollisionHandlingOverride`, `Owner`, `Instigator`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Transform` | [`Transform`](ue_ue_s.Transform.md) |
| `SpawnCollisionHandlingOverride` | [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md) |
| `Owner` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `Instigator` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`World`](ue_ue.World.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`World`](ue_ue.World.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`World`](ue_ue.World.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`World`](ue_ue.World.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
