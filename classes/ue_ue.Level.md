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

#### Defined in

[ue/ue.d.ts:9207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9207)

## Properties

### ActorCluster

• **ActorCluster**: [`LevelActorContainer`](ue_ue.LevelActorContainer.md)

#### Defined in

[ue/ue.d.ts:9211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9211)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Defined in

[ue/ue.d.ts:9236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9236)

___

### DestroyedReplicatedStaticActors

• **DestroyedReplicatedStaticActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ReplicatedStaticActorDestructionInfo`](ue_ue.ReplicatedStaticActorDestructionInfo.md)\>

#### Defined in

[ue/ue.d.ts:9237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9237)

___

### LevelBuildDataId

• **LevelBuildDataId**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:9224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9224)

___

### LevelColor

• **LevelColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:9233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9233)

___

### LevelScriptActor

• **LevelScriptActor**: [`LevelScriptActor`](ue_ue.LevelScriptActor.md)

#### Defined in

[ue/ue.d.ts:9216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9216)

___

### LevelScriptBlueprint

• **LevelScriptBlueprint**: [`LevelScriptBlueprint`](ue_ue.LevelScriptBlueprint.md)

#### Defined in

[ue/ue.d.ts:9212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9212)

___

### LevelSimplification

• **LevelSimplification**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`LevelSimplificationDetails`](ue_ue.LevelSimplificationDetails.md)\>

#### Defined in

[ue/ue.d.ts:9232](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9232)

___

### LightBuildLevelOffset

• **LightBuildLevelOffset**: [`IntVector`](ue_ue_s.IntVector.md)

#### Defined in

[ue/ue.d.ts:9226](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9226)

___

### LightmapTotalSize

• **LightmapTotalSize**: `number`

#### Defined in

[ue/ue.d.ts:9220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9220)

___

### MapBuildData

• **MapBuildData**: [`MapBuildDataRegistry`](ue_ue.MapBuildDataRegistry.md)

#### Defined in

[ue/ue.d.ts:9225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9225)

___

### Model

• **Model**: [`Model`](ue_ue.Model.md)

#### Defined in

[ue/ue.d.ts:9209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9209)

___

### ModelComponents

• **ModelComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ModelComponent`](ue_ue.ModelComponent.md)\>

#### Defined in

[ue/ue.d.ts:9210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9210)

___

### NavDataChunks

• **NavDataChunks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavigationDataChunk`](ue_ue.NavigationDataChunk.md)\>

#### Defined in

[ue/ue.d.ts:9219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9219)

___

### NavListEnd

• **NavListEnd**: [`NavigationObjectBase`](ue_ue.NavigationObjectBase.md)

#### Defined in

[ue/ue.d.ts:9218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9218)

___

### NavListStart

• **NavListStart**: [`NavigationObjectBase`](ue_ue.NavigationObjectBase.md)

#### Defined in

[ue/ue.d.ts:9217](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9217)

___

### NumTextureStreamingDirtyResources

• **NumTextureStreamingDirtyResources**: `number`

#### Defined in

[ue/ue.d.ts:9215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9215)

___

### NumTextureStreamingUnbuiltComponents

• **NumTextureStreamingUnbuiltComponents**: `number`

#### Defined in

[ue/ue.d.ts:9214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9214)

___

### OwningWorld

• **OwningWorld**: [`World`](ue_ue.World.md)

#### Defined in

[ue/ue.d.ts:9208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9208)

___

### ShadowmapTotalSize

• **ShadowmapTotalSize**: `number`

#### Defined in

[ue/ue.d.ts:9221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9221)

___

### StaticNavigableGeometry

• **StaticNavigableGeometry**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:9222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9222)

___

### StreamingTextureGuids

• **StreamingTextureGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Defined in

[ue/ue.d.ts:9223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9223)

___

### TextureStreamingResourceGuids

• **TextureStreamingResourceGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Defined in

[ue/ue.d.ts:9213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9213)

___

### WorldSettings

• **WorldSettings**: [`WorldSettings`](ue_ue.WorldSettings.md)

#### Defined in

[ue/ue.d.ts:9235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9235)

___

### \_\_tid\_Level\_\_

• **\_\_tid\_Level\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9242)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIsLightingScenario

• **bIsLightingScenario**: `boolean`

#### Defined in

[ue/ue.d.ts:9227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9227)

___

### bIsVisible

• **bIsVisible**: `boolean`

#### Defined in

[ue/ue.d.ts:9230](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9230)

___

### bLevelOkayForPlacementWhileCheckedIn

• **bLevelOkayForPlacementWhileCheckedIn**: `boolean`

#### Defined in

[ue/ue.d.ts:9234](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9234)

___

### bLocked

• **bLocked**: `boolean`

#### Defined in

[ue/ue.d.ts:9231](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9231)

___

### bStaticComponentsRegisteredInStreamingManager

• **bStaticComponentsRegisteredInStreamingManager**: `boolean`

#### Defined in

[ue/ue.d.ts:9229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9229)

___

### bTextureStreamingRotationChanged

• **bTextureStreamingRotationChanged**: `boolean`

#### Defined in

[ue/ue.d.ts:9228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9228)

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

#### Defined in

[ue/ue.d.ts:9239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9239)

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

#### Defined in

[ue/ue.d.ts:9240](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9240)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:9238](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9238)
