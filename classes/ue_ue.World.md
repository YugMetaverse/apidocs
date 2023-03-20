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

#### Defined in

[ue/ue.d.ts:10286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10286)

## Properties

### AISystem

• **AISystem**: [`AISystemBase`](ue_ue.AISystemBase.md)

#### Defined in

[ue/ue.d.ts:10312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10312)

___

### ActiveGroupActors

• **ActiveGroupActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:10288](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10288)

___

### AuthorityGameMode

• **AuthorityGameMode**: [`GameModeBase`](ue_ue.GameModeBase.md)

#### Defined in

[ue/ue.d.ts:10310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10310)

___

### AvoidanceManager

• **AvoidanceManager**: [`AvoidanceManager`](ue_ue.AvoidanceManager.md)

#### Defined in

[ue/ue.d.ts:10313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10313)

___

### CanvasForDrawMaterialToRenderTarget

• **CanvasForDrawMaterialToRenderTarget**: [`Canvas`](ue_ue.Canvas.md)

#### Defined in

[ue/ue.d.ts:10320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10320)

___

### CanvasForRenderingToTarget

• **CanvasForRenderingToTarget**: [`Canvas`](ue_ue.Canvas.md)

#### Defined in

[ue/ue.d.ts:10319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10319)

___

### ComponentsThatNeedEndOfFrameUpdate

• **ComponentsThatNeedEndOfFrameUpdate**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Defined in

[ue/ue.d.ts:10322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10322)

___

### ComponentsThatNeedEndOfFrameUpdate\_OnGameThread

• **ComponentsThatNeedEndOfFrameUpdate\_OnGameThread**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActorComponent`](ue_ue.ActorComponent.md)\>

#### Defined in

[ue/ue.d.ts:10323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10323)

___

### CurrentLevel

• **CurrentLevel**: [`Level`](ue_ue.Level.md)

#### Defined in

[ue/ue.d.ts:10316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10316)

___

### CurrentLevelPendingInvisibility

• **CurrentLevelPendingInvisibility**: [`Level`](ue_ue.Level.md)

#### Defined in

[ue/ue.d.ts:10304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10304)

___

### CurrentLevelPendingVisibility

• **CurrentLevelPendingVisibility**: [`Level`](ue_ue.Level.md)

#### Defined in

[ue/ue.d.ts:10303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10303)

___

### DefaultPhysicsVolume

• **DefaultPhysicsVolume**: [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Defined in

[ue/ue.d.ts:10307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10307)

___

### DemoNetDriver

• **DemoNetDriver**: [`DemoNetDriver`](ue_ue.DemoNetDriver.md)

#### Defined in

[ue/ue.d.ts:10305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10305)

___

### EditorViews

• **EditorViews**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelViewportInfo`](ue_ue.LevelViewportInfo.md)\>

#### Defined in

[ue/ue.d.ts:10321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10321)

___

### ExtraReferencedObjects

• **ExtraReferencedObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:10297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10297)

___

### ForegroundLineBatcher

• **ForegroundLineBatcher**: [`LineBatchComponent`](ue_ue.LineBatchComponent.md)

#### Defined in

[ue/ue.d.ts:10294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10294)

___

### GameState

• **GameState**: [`GameStateBase`](ue_ue.GameStateBase.md)

#### Defined in

[ue/ue.d.ts:10311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10311)

___

### Layers

• **Layers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Layer`](ue_ue.Layer.md)\>

#### Defined in

[ue/ue.d.ts:10287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10287)

___

### LevelCollections

• **LevelCollections**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelCollection`](ue_ue.LevelCollection.md)\>

#### Defined in

[ue/ue.d.ts:10315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10315)

___

### LevelSequenceActors

• **LevelSequenceActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:10299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10299)

___

### Levels

• **Levels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Level`](ue_ue.Level.md)\>

#### Defined in

[ue/ue.d.ts:10314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10314)

___

### LineBatcher

• **LineBatcher**: [`LineBatchComponent`](ue_ue.LineBatchComponent.md)

#### Defined in

[ue/ue.d.ts:10292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10292)

___

### MyParticleEventManager

• **MyParticleEventManager**: [`ParticleEventManager`](ue_ue.ParticleEventManager.md)

#### Defined in

[ue/ue.d.ts:10306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10306)

___

### NavigationSystem

• **NavigationSystem**: [`NavigationSystemBase`](ue_ue.NavigationSystemBase.md)

#### Defined in

[ue/ue.d.ts:10309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10309)

___

### NetDriver

• **NetDriver**: [`NetDriver`](ue_ue.NetDriver.md)

#### Defined in

[ue/ue.d.ts:10291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10291)

___

### NetworkManager

• **NetworkManager**: [`GameNetworkManager`](ue_ue.GameNetworkManager.md)

#### Defined in

[ue/ue.d.ts:10295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10295)

___

### OwningGameInstance

• **OwningGameInstance**: [`GameInstance`](ue_ue.GameInstance.md)

#### Defined in

[ue/ue.d.ts:10317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10317)

___

### PSCPool

• **PSCPool**: [`WorldPSCPool`](ue_ue.WorldPSCPool.md)

#### Defined in

[ue/ue.d.ts:10326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10326)

___

### ParameterCollectionInstances

• **ParameterCollectionInstances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialParameterCollectionInstance`](ue_ue.MaterialParameterCollectionInstance.md)\>

#### Defined in

[ue/ue.d.ts:10318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10318)

___

### PerModuleDataObjects

• **PerModuleDataObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:10298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10298)

___

### PersistentLevel

• **PersistentLevel**: [`Level`](ue_ue.Level.md)

#### Defined in

[ue/ue.d.ts:10290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10290)

___

### PersistentLineBatcher

• **PersistentLineBatcher**: [`LineBatchComponent`](ue_ue.LineBatchComponent.md)

#### Defined in

[ue/ue.d.ts:10293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10293)

___

### PhysicsCollisionHandler

• **PhysicsCollisionHandler**: [`PhysicsCollisionHandler`](ue_ue.PhysicsCollisionHandler.md)

#### Defined in

[ue/ue.d.ts:10296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10296)

___

### SelectedLevels

• **SelectedLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Level`](ue_ue.Level.md)\>

#### Defined in

[ue/ue.d.ts:10324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10324)

___

### StreamingLevels

• **StreamingLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LevelStreaming`](ue_ue.LevelStreaming.md)\>

#### Defined in

[ue/ue.d.ts:10300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10300)

___

### StreamingLevelsPrefix

• **StreamingLevelsPrefix**: `string`

#### Defined in

[ue/ue.d.ts:10302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10302)

___

### StreamingLevelsToConsider

• **StreamingLevelsToConsider**: [`StreamingLevelsToConsider`](ue_ue.StreamingLevelsToConsider.md)

#### Defined in

[ue/ue.d.ts:10301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10301)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Defined in

[ue/ue.d.ts:10289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10289)

___

### WorldComposition

• **WorldComposition**: [`WorldComposition`](ue_ue.WorldComposition.md)

#### Defined in

[ue/ue.d.ts:10325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10325)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_World\_\_

• **\_\_tid\_World\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10334)

___

### bAreConstraintsDirty

• **bAreConstraintsDirty**: `boolean`

#### Defined in

[ue/ue.d.ts:10308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10308)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HandleTimelineScrubbed

▸ **HandleTimelineScrubbed**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:10327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10327)

___

### K2\_GetWorldSettings

▸ **K2_GetWorldSettings**(): [`WorldSettings`](ue_ue.WorldSettings.md)

#### Returns

[`WorldSettings`](ue_ue.WorldSettings.md)

#### Defined in

[ue/ue.d.ts:10328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10328)

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

#### Defined in

[ue/ue.d.ts:10329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10329)

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

#### Defined in

[ue/ue.d.ts:10331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10331)

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

#### Defined in

[ue/ue.d.ts:10332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10332)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:10330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10330)
