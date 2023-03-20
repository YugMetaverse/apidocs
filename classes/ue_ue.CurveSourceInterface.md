[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CurveSourceInterface

# Class: CurveSourceInterface

[ue/ue](../modules/ue_ue.md).CurveSourceInterface

## Hierarchy

- [`Interface`](ue_ue.Interface.md)

  ↳ **`CurveSourceInterface`**

## Table of contents

### Constructors

- [constructor](ue_ue.CurveSourceInterface.md#constructor)

### Properties

- [\_\_tid\_CurveSourceInterface\_\_](ue_ue.CurveSourceInterface.md#__tid_curvesourceinterface__)
- [\_\_tid\_Interface\_\_](ue_ue.CurveSourceInterface.md#__tid_interface__)
- [\_\_tid\_Object\_\_](ue_ue.CurveSourceInterface.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.CurveSourceInterface.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CurveSourceInterface.md#executeubergraph)
- [GetBindingName](ue_ue.CurveSourceInterface.md#getbindingname)
- [GetClass](ue_ue.CurveSourceInterface.md#getclass)
- [GetCurveValue](ue_ue.CurveSourceInterface.md#getcurvevalue)
- [GetCurves](ue_ue.CurveSourceInterface.md#getcurves)
- [GetName](ue_ue.CurveSourceInterface.md#getname)
- [GetOuter](ue_ue.CurveSourceInterface.md#getouter)
- [GetWorld](ue_ue.CurveSourceInterface.md#getworld)
- [Find](ue_ue.CurveSourceInterface.md#find)
- [Load](ue_ue.CurveSourceInterface.md#load)
- [StaticClass](ue_ue.CurveSourceInterface.md#staticclass)

## Constructors

### constructor

• **new CurveSourceInterface**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Interface](ue_ue.Interface.md).[constructor](ue_ue.Interface.md#constructor)

## Properties

### \_\_tid\_CurveSourceInterface\_\_

• **\_\_tid\_CurveSourceInterface\_\_**: `boolean`

___

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

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

[Interface](ue_ue.Interface.md).[CreateDefaultSubobject](ue_ue.Interface.md#createdefaultsubobject)

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

[Interface](ue_ue.Interface.md).[ExecuteUbergraph](ue_ue.Interface.md#executeubergraph)

___

### GetBindingName

▸ **GetBindingName**(): `string`

#### Returns

`string`

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

___

### GetCurveValue

▸ **GetCurveValue**(`CurveName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CurveName` | `string` |

#### Returns

`number`

___

### GetCurves

▸ **GetCurves**(`OutValues`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutValues` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedCurveValue`](ue_ue.NamedCurveValue.md)\>\> |

#### Returns

`void`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CurveSourceInterface`](ue_ue.CurveSourceInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CurveSourceInterface`](ue_ue.CurveSourceInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Find](ue_ue.Interface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CurveSourceInterface`](ue_ue.CurveSourceInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CurveSourceInterface`](ue_ue.CurveSourceInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Load](ue_ue.Interface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)
