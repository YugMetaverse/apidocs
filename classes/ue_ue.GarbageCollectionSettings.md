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

## Properties

### ActorClusteringEnabled

• **ActorClusteringEnabled**: `boolean`

___

### AllowParallelGC

• **AllowParallelGC**: `boolean`

___

### BlueprintClusteringEnabled

• **BlueprintClusteringEnabled**: `boolean`

___

### CreateGCClusters

• **CreateGCClusters**: `boolean`

___

### FlushStreamingOnGC

• **FlushStreamingOnGC**: `boolean`

___

### IncrementalBeginDestroyEnabled

• **IncrementalBeginDestroyEnabled**: `boolean`

___

### MaxObjectsInEditor

• **MaxObjectsInEditor**: `number`

___

### MaxObjectsInGame

• **MaxObjectsInGame**: `number`

___

### MaxObjectsNotConsideredByGC

• **MaxObjectsNotConsideredByGC**: `number`

___

### MinGCClusterSize

• **MinGCClusterSize**: `number`

___

### MultithreadedDestructionEnabled

• **MultithreadedDestructionEnabled**: `boolean`

___

### NumRetriesBeforeForcingGC

• **NumRetriesBeforeForcingGC**: `number`

___

### SizeOfPermanentObjectPool

• **SizeOfPermanentObjectPool**: `number`

___

### TimeBetweenPurgingPendingKillObjects

• **TimeBetweenPurgingPendingKillObjects**: `number`

___

### UseDisregardForGCOnDedicatedServers

• **UseDisregardForGCOnDedicatedServers**: `boolean`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_GarbageCollectionSettings\_\_

• **\_\_tid\_GarbageCollectionSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
