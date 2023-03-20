[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Level

# Class: Level

[ue/ue](../modules/ue_ue.md).Level

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Level`**

## Table of contents

### Constructors

- [constructor](ue_ue.Level.md#constructor)

### Properties

- [ActorCluster](ue_ue.Level.md#actorcluster)
- [AssetUserData](ue_ue.Level.md#assetuserdata)
- [DestroyedReplicatedStaticActors](ue_ue.Level.md#destroyedreplicatedstaticactors)
- [LevelBuildDataId](ue_ue.Level.md#levelbuilddataid)
- [LevelColor](ue_ue.Level.md#levelcolor)
- [LevelScriptActor](ue_ue.Level.md#levelscriptactor)
- [LevelScriptBlueprint](ue_ue.Level.md#levelscriptblueprint)
- [LevelSimplification](ue_ue.Level.md#levelsimplification)
- [LightBuildLevelOffset](ue_ue.Level.md#lightbuildleveloffset)
- [LightmapTotalSize](ue_ue.Level.md#lightmaptotalsize)
- [MapBuildData](ue_ue.Level.md#mapbuilddata)
- [Model](ue_ue.Level.md#model)
- [ModelComponents](ue_ue.Level.md#modelcomponents)
- [NavDataChunks](ue_ue.Level.md#navdatachunks)
- [NavListEnd](ue_ue.Level.md#navlistend)
- [NavListStart](ue_ue.Level.md#navliststart)
- [NumTextureStreamingDirtyResources](ue_ue.Level.md#numtexturestreamingdirtyresources)
- [NumTextureStreamingUnbuiltComponents](ue_ue.Level.md#numtexturestreamingunbuiltcomponents)
- [OwningWorld](ue_ue.Level.md#owningworld)
- [ShadowmapTotalSize](ue_ue.Level.md#shadowmaptotalsize)
- [StaticNavigableGeometry](ue_ue.Level.md#staticnavigablegeometry)
- [StreamingTextureGuids](ue_ue.Level.md#streamingtextureguids)
- [TextureStreamingResourceGuids](ue_ue.Level.md#texturestreamingresourceguids)
- [WorldSettings](ue_ue.Level.md#worldsettings)
- [\_\_tid\_Level\_\_](ue_ue.Level.md#__tid_level__)
- [\_\_tid\_Object\_\_](ue_ue.Level.md#__tid_object__)
- [bIsLightingScenario](ue_ue.Level.md#bislightingscenario)
- [bIsVisible](ue_ue.Level.md#bisvisible)
- [bLevelOkayForPlacementWhileCheckedIn](ue_ue.Level.md#blevelokayforplacementwhilecheckedin)
- [bLocked](ue_ue.Level.md#blocked)
- [bStaticComponentsRegisteredInStreamingManager](ue_ue.Level.md#bstaticcomponentsregisteredinstreamingmanager)
- [bTextureStreamingRotationChanged](ue_ue.Level.md#btexturestreamingrotationchanged)

### Methods

- [CreateDefaultSubobject](ue_ue.Level.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Level.md#executeubergraph)
- [GetClass](ue_ue.Level.md#getclass)
- [GetName](ue_ue.Level.md#getname)
- [GetOuter](ue_ue.Level.md#getouter)
- [GetWorld](ue_ue.Level.md#getworld)
- [Find](ue_ue.Level.md#find)
- [Load](ue_ue.Level.md#load)
- [StaticClass](ue_ue.Level.md#staticclass)

## Constructors

### constructor

• **new Level**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ActorCluster

• **ActorCluster**: [`LevelActorContainer`](ue_ue.LevelActorContainer.md)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

___

### DestroyedReplicatedStaticActors

• **DestroyedReplicatedStaticActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ReplicatedStaticActorDestructionInfo`](ue_ue.ReplicatedStaticActorDestructionInfo.md)\>

___

### LevelBuildDataId

• **LevelBuildDataId**: [`Guid`](ue_ue_s.Guid.md)

___

### LevelColor

• **LevelColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### LevelScriptActor

• **LevelScriptActor**: [`LevelScriptActor`](ue_ue.LevelScriptActor.md)

___

### LevelScriptBlueprint

• **LevelScriptBlueprint**: [`LevelScriptBlueprint`](ue_ue.LevelScriptBlueprint.md)

___

### LevelSimplification

• **LevelSimplification**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`LevelSimplificationDetails`](ue_ue.LevelSimplificationDetails.md)\>

___

### LightBuildLevelOffset

• **LightBuildLevelOffset**: [`IntVector`](ue_ue_s.IntVector.md)

___

### LightmapTotalSize

• **LightmapTotalSize**: `number`

___

### MapBuildData

• **MapBuildData**: [`MapBuildDataRegistry`](ue_ue.MapBuildDataRegistry.md)

___

### Model

• **Model**: [`Model`](ue_ue.Model.md)

___

### ModelComponents

• **ModelComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ModelComponent`](ue_ue.ModelComponent.md)\>

___

### NavDataChunks

• **NavDataChunks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavigationDataChunk`](ue_ue.NavigationDataChunk.md)\>

___

### NavListEnd

• **NavListEnd**: [`NavigationObjectBase`](ue_ue.NavigationObjectBase.md)

___

### NavListStart

• **NavListStart**: [`NavigationObjectBase`](ue_ue.NavigationObjectBase.md)

___

### NumTextureStreamingDirtyResources

• **NumTextureStreamingDirtyResources**: `number`

___

### NumTextureStreamingUnbuiltComponents

• **NumTextureStreamingUnbuiltComponents**: `number`

___

### OwningWorld

• **OwningWorld**: [`World`](ue_ue.World.md)

___

### ShadowmapTotalSize

• **ShadowmapTotalSize**: `number`

___

### StaticNavigableGeometry

• **StaticNavigableGeometry**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### StreamingTextureGuids

• **StreamingTextureGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

___

### TextureStreamingResourceGuids

• **TextureStreamingResourceGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

___

### WorldSettings

• **WorldSettings**: [`WorldSettings`](ue_ue.WorldSettings.md)

___

### \_\_tid\_Level\_\_

• **\_\_tid\_Level\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bIsLightingScenario

• **bIsLightingScenario**: `boolean`

___

### bIsVisible

• **bIsVisible**: `boolean`

___

### bLevelOkayForPlacementWhileCheckedIn

• **bLevelOkayForPlacementWhileCheckedIn**: `boolean`

___

### bLocked

• **bLocked**: `boolean`

___

### bStaticComponentsRegisteredInStreamingManager

• **bStaticComponentsRegisteredInStreamingManager**: `boolean`

___

### bTextureStreamingRotationChanged

• **bTextureStreamingRotationChanged**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Level`](ue_ue.Level.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Level`](ue_ue.Level.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Level`](ue_ue.Level.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Level`](ue_ue.Level.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
