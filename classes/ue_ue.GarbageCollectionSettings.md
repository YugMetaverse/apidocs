[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GarbageCollectionSettings

# Class: GarbageCollectionSettings

[ue/ue](../modules/ue_ue.md).GarbageCollectionSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`GarbageCollectionSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.GarbageCollectionSettings.md#constructor)

### Properties

- [ActorClusteringEnabled](ue_ue.GarbageCollectionSettings.md#actorclusteringenabled)
- [AllowParallelGC](ue_ue.GarbageCollectionSettings.md#allowparallelgc)
- [BlueprintClusteringEnabled](ue_ue.GarbageCollectionSettings.md#blueprintclusteringenabled)
- [CreateGCClusters](ue_ue.GarbageCollectionSettings.md#creategcclusters)
- [FlushStreamingOnGC](ue_ue.GarbageCollectionSettings.md#flushstreamingongc)
- [IncrementalBeginDestroyEnabled](ue_ue.GarbageCollectionSettings.md#incrementalbegindestroyenabled)
- [MaxObjectsInEditor](ue_ue.GarbageCollectionSettings.md#maxobjectsineditor)
- [MaxObjectsInGame](ue_ue.GarbageCollectionSettings.md#maxobjectsingame)
- [MaxObjectsNotConsideredByGC](ue_ue.GarbageCollectionSettings.md#maxobjectsnotconsideredbygc)
- [MinGCClusterSize](ue_ue.GarbageCollectionSettings.md#mingcclustersize)
- [MultithreadedDestructionEnabled](ue_ue.GarbageCollectionSettings.md#multithreadeddestructionenabled)
- [NumRetriesBeforeForcingGC](ue_ue.GarbageCollectionSettings.md#numretriesbeforeforcinggc)
- [SizeOfPermanentObjectPool](ue_ue.GarbageCollectionSettings.md#sizeofpermanentobjectpool)
- [TimeBetweenPurgingPendingKillObjects](ue_ue.GarbageCollectionSettings.md#timebetweenpurgingpendingkillobjects)
- [UseDisregardForGCOnDedicatedServers](ue_ue.GarbageCollectionSettings.md#usedisregardforgcondedicatedservers)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.GarbageCollectionSettings.md#__tid_developersettings__)
- [\_\_tid\_GarbageCollectionSettings\_\_](ue_ue.GarbageCollectionSettings.md#__tid_garbagecollectionsettings__)
- [\_\_tid\_Object\_\_](ue_ue.GarbageCollectionSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GarbageCollectionSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GarbageCollectionSettings.md#executeubergraph)
- [GetClass](ue_ue.GarbageCollectionSettings.md#getclass)
- [GetName](ue_ue.GarbageCollectionSettings.md#getname)
- [GetOuter](ue_ue.GarbageCollectionSettings.md#getouter)
- [GetWorld](ue_ue.GarbageCollectionSettings.md#getworld)
- [Find](ue_ue.GarbageCollectionSettings.md#find)
- [Load](ue_ue.GarbageCollectionSettings.md#load)
- [StaticClass](ue_ue.GarbageCollectionSettings.md#staticclass)

## Constructors

### constructor

• **new GarbageCollectionSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

#### Defined in

[ue/ue.d.ts:37284](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37284)

## Properties

### ActorClusteringEnabled

• **ActorClusteringEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:37291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37291)

___

### AllowParallelGC

• **AllowParallelGC**: `boolean`

#### Defined in

[ue/ue.d.ts:37287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37287)

___

### BlueprintClusteringEnabled

• **BlueprintClusteringEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:37292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37292)

___

### CreateGCClusters

• **CreateGCClusters**: `boolean`

#### Defined in

[ue/ue.d.ts:37290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37290)

___

### FlushStreamingOnGC

• **FlushStreamingOnGC**: `boolean`

#### Defined in

[ue/ue.d.ts:37286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37286)

___

### IncrementalBeginDestroyEnabled

• **IncrementalBeginDestroyEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:37288](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37288)

___

### MaxObjectsInEditor

• **MaxObjectsInEditor**: `number`

#### Defined in

[ue/ue.d.ts:37299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37299)

___

### MaxObjectsInGame

• **MaxObjectsInGame**: `number`

#### Defined in

[ue/ue.d.ts:37298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37298)

___

### MaxObjectsNotConsideredByGC

• **MaxObjectsNotConsideredByGC**: `number`

#### Defined in

[ue/ue.d.ts:37296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37296)

___

### MinGCClusterSize

• **MinGCClusterSize**: `number`

#### Defined in

[ue/ue.d.ts:37294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37294)

___

### MultithreadedDestructionEnabled

• **MultithreadedDestructionEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:37289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37289)

___

### NumRetriesBeforeForcingGC

• **NumRetriesBeforeForcingGC**: `number`

#### Defined in

[ue/ue.d.ts:37295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37295)

___

### SizeOfPermanentObjectPool

• **SizeOfPermanentObjectPool**: `number`

#### Defined in

[ue/ue.d.ts:37297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37297)

___

### TimeBetweenPurgingPendingKillObjects

• **TimeBetweenPurgingPendingKillObjects**: `number`

#### Defined in

[ue/ue.d.ts:37285](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37285)

___

### UseDisregardForGCOnDedicatedServers

• **UseDisregardForGCOnDedicatedServers**: `boolean`

#### Defined in

[ue/ue.d.ts:37293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37293)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

#### Defined in

[ue/ue.d.ts:16950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16950)

___

### \_\_tid\_GarbageCollectionSettings\_\_

• **\_\_tid\_GarbageCollectionSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:37304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37304)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GarbageCollectionSettings`](ue_ue.GarbageCollectionSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GarbageCollectionSettings`](ue_ue.GarbageCollectionSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

#### Defined in

[ue/ue.d.ts:37301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37301)

___

### Load

▸ `Static` **Load**(`InName`): [`GarbageCollectionSettings`](ue_ue.GarbageCollectionSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GarbageCollectionSettings`](ue_ue.GarbageCollectionSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

#### Defined in

[ue/ue.d.ts:37302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37302)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:37300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37300)
