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

## Properties

### AppliedGuid

• **AppliedGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### PreviouslyAppliedModifier

• **PreviouslyAppliedModifier**: [`AnimationModifier`](ue_ue.AnimationModifier.md)

___

### RevisionGuid

• **RevisionGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### StoredNativeRevision

• **StoredNativeRevision**: `number`

___

### \_\_tid\_AnimationModifier\_\_

• **\_\_tid\_AnimationModifier\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### OnApply

▸ **OnApply**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

___

### OnRevert

▸ **OnRevert**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
