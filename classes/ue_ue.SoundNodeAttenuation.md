[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundNodeAttenuation

# Class: SoundNodeAttenuation

[ue/ue](../modules/ue_ue.md).SoundNodeAttenuation

## Hierarchy

- [`SoundNode`](ue_ue.SoundNode.md)

  ↳ **`SoundNodeAttenuation`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundNodeAttenuation.md#constructor)

### Properties

- [AttenuationOverrides](ue_ue.SoundNodeAttenuation.md#attenuationoverrides)
- [AttenuationSettings](ue_ue.SoundNodeAttenuation.md#attenuationsettings)
- [ChildNodes](ue_ue.SoundNodeAttenuation.md#childnodes)
- [GraphNode](ue_ue.SoundNodeAttenuation.md#graphnode)
- [\_\_tid\_Object\_\_](ue_ue.SoundNodeAttenuation.md#__tid_object__)
- [\_\_tid\_SoundNodeAttenuation\_\_](ue_ue.SoundNodeAttenuation.md#__tid_soundnodeattenuation__)
- [\_\_tid\_SoundNode\_\_](ue_ue.SoundNodeAttenuation.md#__tid_soundnode__)
- [bOverrideAttenuation](ue_ue.SoundNodeAttenuation.md#boverrideattenuation)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundNodeAttenuation.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundNodeAttenuation.md#executeubergraph)
- [GetClass](ue_ue.SoundNodeAttenuation.md#getclass)
- [GetName](ue_ue.SoundNodeAttenuation.md#getname)
- [GetOuter](ue_ue.SoundNodeAttenuation.md#getouter)
- [GetWorld](ue_ue.SoundNodeAttenuation.md#getworld)
- [Find](ue_ue.SoundNodeAttenuation.md#find)
- [Load](ue_ue.SoundNodeAttenuation.md#load)
- [StaticClass](ue_ue.SoundNodeAttenuation.md#staticclass)

## Constructors

### constructor

• **new SoundNodeAttenuation**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[constructor](ue_ue.SoundNode.md#constructor)

#### Defined in

[ue/ue.d.ts:61294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61294)

## Properties

### AttenuationOverrides

• **AttenuationOverrides**: [`SoundAttenuationSettings`](ue_ue.SoundAttenuationSettings.md)

#### Defined in

[ue/ue.d.ts:61296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61296)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Defined in

[ue/ue.d.ts:61295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61295)

___

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[ChildNodes](ue_ue.SoundNode.md#childnodes)

#### Defined in

[ue/ue.d.ts:22398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22398)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

#### Defined in

[ue/ue.d.ts:22399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22399)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_Object__](ue_ue.SoundNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundNodeAttenuation\_\_

• **\_\_tid\_SoundNodeAttenuation\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61302)

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

#### Defined in

[ue/ue.d.ts:22404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22404)

___

### bOverrideAttenuation

• **bOverrideAttenuation**: `boolean`

#### Defined in

[ue/ue.d.ts:61297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61297)

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

[SoundNode](ue_ue.SoundNode.md).[ExecuteUbergraph](ue_ue.SoundNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetClass](ue_ue.SoundNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetName](ue_ue.SoundNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetOuter](ue_ue.SoundNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetWorld](ue_ue.SoundNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundNodeAttenuation`](ue_ue.SoundNodeAttenuation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundNodeAttenuation`](ue_ue.SoundNodeAttenuation.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Find](ue_ue.SoundNode.md#find)

#### Defined in

[ue/ue.d.ts:61299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61299)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundNodeAttenuation`](ue_ue.SoundNodeAttenuation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundNodeAttenuation`](ue_ue.SoundNodeAttenuation.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Load](ue_ue.SoundNode.md#load)

#### Defined in

[ue/ue.d.ts:61300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61300)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:61298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61298)
