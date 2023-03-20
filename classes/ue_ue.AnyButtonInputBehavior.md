[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnyButtonInputBehavior

# Class: AnyButtonInputBehavior

[ue/ue](../modules/ue_ue.md).AnyButtonInputBehavior

## Hierarchy

- [`InputBehavior`](ue_ue.InputBehavior.md)

  ↳ **`AnyButtonInputBehavior`**

  ↳↳ [`ClickDragInputBehavior`](ue_ue.ClickDragInputBehavior.md)

  ↳↳ [`MeshSurfacePointToolMouseBehavior`](ue_ue.MeshSurfacePointToolMouseBehavior.md)

  ↳↳ [`MultiClickSequenceInputBehavior`](ue_ue.MultiClickSequenceInputBehavior.md)

  ↳↳ [`SingleClickInputBehavior`](ue_ue.SingleClickInputBehavior.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnyButtonInputBehavior.md#constructor)

### Properties

- [ButtonNumber](ue_ue.AnyButtonInputBehavior.md#buttonnumber)
- [\_\_tid\_AnyButtonInputBehavior\_\_](ue_ue.AnyButtonInputBehavior.md#__tid_anybuttoninputbehavior__)
- [\_\_tid\_InputBehavior\_\_](ue_ue.AnyButtonInputBehavior.md#__tid_inputbehavior__)
- [\_\_tid\_Object\_\_](ue_ue.AnyButtonInputBehavior.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnyButtonInputBehavior.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnyButtonInputBehavior.md#executeubergraph)
- [GetClass](ue_ue.AnyButtonInputBehavior.md#getclass)
- [GetName](ue_ue.AnyButtonInputBehavior.md#getname)
- [GetOuter](ue_ue.AnyButtonInputBehavior.md#getouter)
- [GetWorld](ue_ue.AnyButtonInputBehavior.md#getworld)
- [Find](ue_ue.AnyButtonInputBehavior.md#find)
- [Load](ue_ue.AnyButtonInputBehavior.md#load)
- [StaticClass](ue_ue.AnyButtonInputBehavior.md#staticclass)

## Constructors

### constructor

• **new AnyButtonInputBehavior**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InputBehavior](ue_ue.InputBehavior.md).[constructor](ue_ue.InputBehavior.md#constructor)

## Properties

### ButtonNumber

• **ButtonNumber**: `number`

___

### \_\_tid\_AnyButtonInputBehavior\_\_

• **\_\_tid\_AnyButtonInputBehavior\_\_**: `boolean`

___

### \_\_tid\_InputBehavior\_\_

• **\_\_tid\_InputBehavior\_\_**: `boolean`

#### Inherited from

[InputBehavior](ue_ue.InputBehavior.md).[__tid_InputBehavior__](ue_ue.InputBehavior.md#__tid_inputbehavior__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InputBehavior](ue_ue.InputBehavior.md).[__tid_Object__](ue_ue.InputBehavior.md#__tid_object__)

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

[InputBehavior](ue_ue.InputBehavior.md).[CreateDefaultSubobject](ue_ue.InputBehavior.md#createdefaultsubobject)

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

[InputBehavior](ue_ue.InputBehavior.md).[ExecuteUbergraph](ue_ue.InputBehavior.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InputBehavior](ue_ue.InputBehavior.md).[GetClass](ue_ue.InputBehavior.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InputBehavior](ue_ue.InputBehavior.md).[GetName](ue_ue.InputBehavior.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InputBehavior](ue_ue.InputBehavior.md).[GetOuter](ue_ue.InputBehavior.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InputBehavior](ue_ue.InputBehavior.md).[GetWorld](ue_ue.InputBehavior.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnyButtonInputBehavior`](ue_ue.AnyButtonInputBehavior.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnyButtonInputBehavior`](ue_ue.AnyButtonInputBehavior.md)

#### Overrides

[InputBehavior](ue_ue.InputBehavior.md).[Find](ue_ue.InputBehavior.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnyButtonInputBehavior`](ue_ue.AnyButtonInputBehavior.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnyButtonInputBehavior`](ue_ue.AnyButtonInputBehavior.md)

#### Overrides

[InputBehavior](ue_ue.InputBehavior.md).[Load](ue_ue.InputBehavior.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InputBehavior](ue_ue.InputBehavior.md).[StaticClass](ue_ue.InputBehavior.md#staticclass)
