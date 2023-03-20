[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationModifier

# Class: AnimationModifier

[ue/ue](../modules/ue_ue.md).AnimationModifier

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimationModifier`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationModifier.md#constructor)

### Properties

- [AppliedGuid](ue_ue.AnimationModifier.md#appliedguid)
- [PreviouslyAppliedModifier](ue_ue.AnimationModifier.md#previouslyappliedmodifier)
- [RevisionGuid](ue_ue.AnimationModifier.md#revisionguid)
- [StoredNativeRevision](ue_ue.AnimationModifier.md#storednativerevision)
- [\_\_tid\_AnimationModifier\_\_](ue_ue.AnimationModifier.md#__tid_animationmodifier__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationModifier.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationModifier.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationModifier.md#executeubergraph)
- [GetClass](ue_ue.AnimationModifier.md#getclass)
- [GetName](ue_ue.AnimationModifier.md#getname)
- [GetOuter](ue_ue.AnimationModifier.md#getouter)
- [GetWorld](ue_ue.AnimationModifier.md#getworld)
- [OnApply](ue_ue.AnimationModifier.md#onapply)
- [OnRevert](ue_ue.AnimationModifier.md#onrevert)
- [Find](ue_ue.AnimationModifier.md#find)
- [Load](ue_ue.AnimationModifier.md#load)
- [StaticClass](ue_ue.AnimationModifier.md#staticclass)

## Constructors

### constructor

• **new AnimationModifier**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:16920](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16920)

## Properties

### AppliedGuid

• **AppliedGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:16922](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16922)

___

### PreviouslyAppliedModifier

• **PreviouslyAppliedModifier**: [`AnimationModifier`](ue_ue.AnimationModifier.md)

#### Defined in

[ue/ue.d.ts:16924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16924)

___

### RevisionGuid

• **RevisionGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:16921](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16921)

___

### StoredNativeRevision

• **StoredNativeRevision**: `number`

#### Defined in

[ue/ue.d.ts:16923](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16923)

___

### \_\_tid\_AnimationModifier\_\_

• **\_\_tid\_AnimationModifier\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16931)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### OnApply

▸ **OnApply**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16925)

___

### OnRevert

▸ **OnRevert**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16926)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationModifier`](ue_ue.AnimationModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationModifier`](ue_ue.AnimationModifier.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:16928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16928)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationModifier`](ue_ue.AnimationModifier.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationModifier`](ue_ue.AnimationModifier.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:16929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16929)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:16927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16927)
