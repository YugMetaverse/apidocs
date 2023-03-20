[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundNodeRandom

# Class: SoundNodeRandom

[ue/ue](../modules/ue_ue.md).SoundNodeRandom

## Hierarchy

- [`SoundNode`](ue_ue.SoundNode.md)

  ↳ **`SoundNodeRandom`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundNodeRandom.md#constructor)

### Properties

- [ChildNodes](ue_ue.SoundNodeRandom.md#childnodes)
- [GraphNode](ue_ue.SoundNodeRandom.md#graphnode)
- [HasBeenUsed](ue_ue.SoundNodeRandom.md#hasbeenused)
- [NumRandomUsed](ue_ue.SoundNodeRandom.md#numrandomused)
- [PIEHiddenNodes](ue_ue.SoundNodeRandom.md#piehiddennodes)
- [PreselectAtLevelLoad](ue_ue.SoundNodeRandom.md#preselectatlevelload)
- [Weights](ue_ue.SoundNodeRandom.md#weights)
- [\_\_tid\_Object\_\_](ue_ue.SoundNodeRandom.md#__tid_object__)
- [\_\_tid\_SoundNodeRandom\_\_](ue_ue.SoundNodeRandom.md#__tid_soundnoderandom__)
- [\_\_tid\_SoundNode\_\_](ue_ue.SoundNodeRandom.md#__tid_soundnode__)
- [bRandomizeWithoutReplacement](ue_ue.SoundNodeRandom.md#brandomizewithoutreplacement)
- [bShouldExcludeFromBranchCulling](ue_ue.SoundNodeRandom.md#bshouldexcludefrombranchculling)
- [bSoundCueExcludedFromBranchCulling](ue_ue.SoundNodeRandom.md#bsoundcueexcludedfrombranchculling)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundNodeRandom.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundNodeRandom.md#executeubergraph)
- [GetClass](ue_ue.SoundNodeRandom.md#getclass)
- [GetName](ue_ue.SoundNodeRandom.md#getname)
- [GetOuter](ue_ue.SoundNodeRandom.md#getouter)
- [GetWorld](ue_ue.SoundNodeRandom.md#getworld)
- [Find](ue_ue.SoundNodeRandom.md#find)
- [Load](ue_ue.SoundNodeRandom.md#load)
- [StaticClass](ue_ue.SoundNodeRandom.md#staticclass)

## Constructors

### constructor

• **new SoundNodeRandom**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[constructor](ue_ue.SoundNode.md#constructor)

#### Defined in

[ue/ue.d.ts:61542](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61542)

## Properties

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[ChildNodes](ue_ue.SoundNode.md#childnodes)

#### Defined in

[ue/ue.d.ts:22398](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22398)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

#### Defined in

[ue/ue.d.ts:22399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22399)

___

### HasBeenUsed

• **HasBeenUsed**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

#### Defined in

[ue/ue.d.ts:61544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61544)

___

### NumRandomUsed

• **NumRandomUsed**: `number`

#### Defined in

[ue/ue.d.ts:61545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61545)

___

### PIEHiddenNodes

• **PIEHiddenNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:61550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61550)

___

### PreselectAtLevelLoad

• **PreselectAtLevelLoad**: `number`

#### Defined in

[ue/ue.d.ts:61546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61546)

___

### Weights

• **Weights**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:61543](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61543)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_Object__](ue_ue.SoundNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundNodeRandom\_\_

• **\_\_tid\_SoundNodeRandom\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61555)

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

#### Defined in

[ue/ue.d.ts:22404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22404)

___

### bRandomizeWithoutReplacement

• **bRandomizeWithoutReplacement**: `boolean`

#### Defined in

[ue/ue.d.ts:61549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61549)

___

### bShouldExcludeFromBranchCulling

• **bShouldExcludeFromBranchCulling**: `boolean`

#### Defined in

[ue/ue.d.ts:61547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61547)

___

### bSoundCueExcludedFromBranchCulling

• **bSoundCueExcludedFromBranchCulling**: `boolean`

#### Defined in

[ue/ue.d.ts:61548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61548)

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

[SoundNode](ue_ue.SoundNode.md).[CreateDefaultSubobject](ue_ue.SoundNode.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[SoundNode](ue_ue.SoundNode.md).[ExecuteUbergraph](ue_ue.SoundNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetClass](ue_ue.SoundNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetName](ue_ue.SoundNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetOuter](ue_ue.SoundNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetWorld](ue_ue.SoundNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundNodeRandom`](ue_ue.SoundNodeRandom.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundNodeRandom`](ue_ue.SoundNodeRandom.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Find](ue_ue.SoundNode.md#find)

#### Defined in

[ue/ue.d.ts:61552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61552)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundNodeRandom`](ue_ue.SoundNodeRandom.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundNodeRandom`](ue_ue.SoundNodeRandom.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Load](ue_ue.SoundNode.md#load)

#### Defined in

[ue/ue.d.ts:61553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61553)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:61551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61551)
