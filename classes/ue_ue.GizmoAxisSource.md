[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GizmoAxisSource

# Class: GizmoAxisSource

[ue/ue](../modules/ue_ue.md).GizmoAxisSource

## Hierarchy

- [`Interface`](ue_ue.Interface.md)

  ↳ **`GizmoAxisSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.GizmoAxisSource.md#constructor)

### Properties

- [\_\_tid\_GizmoAxisSource\_\_](ue_ue.GizmoAxisSource.md#__tid_gizmoaxissource__)
- [\_\_tid\_Interface\_\_](ue_ue.GizmoAxisSource.md#__tid_interface__)
- [\_\_tid\_Object\_\_](ue_ue.GizmoAxisSource.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GizmoAxisSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GizmoAxisSource.md#executeubergraph)
- [GetClass](ue_ue.GizmoAxisSource.md#getclass)
- [GetDirection](ue_ue.GizmoAxisSource.md#getdirection)
- [GetName](ue_ue.GizmoAxisSource.md#getname)
- [GetOrigin](ue_ue.GizmoAxisSource.md#getorigin)
- [GetOuter](ue_ue.GizmoAxisSource.md#getouter)
- [GetTangentVectors](ue_ue.GizmoAxisSource.md#gettangentvectors)
- [GetWorld](ue_ue.GizmoAxisSource.md#getworld)
- [HasTangentVectors](ue_ue.GizmoAxisSource.md#hastangentvectors)
- [Find](ue_ue.GizmoAxisSource.md#find)
- [Load](ue_ue.GizmoAxisSource.md#load)
- [StaticClass](ue_ue.GizmoAxisSource.md#staticclass)

## Constructors

### constructor

• **new GizmoAxisSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Interface](ue_ue.Interface.md).[constructor](ue_ue.Interface.md#constructor)

## Properties

### \_\_tid\_GizmoAxisSource\_\_

• **\_\_tid\_GizmoAxisSource\_\_**: `boolean`

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

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

___

### GetDirection

▸ **GetDirection**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

___

### GetOrigin

▸ **GetOrigin**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

___

### GetTangentVectors

▸ **GetTangentVectors**(`TangentXOut`, `TangentYOut`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TangentXOut` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `TangentYOut` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

___

### HasTangentVectors

▸ **HasTangentVectors**(): `boolean`

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GizmoAxisSource`](ue_ue.GizmoAxisSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GizmoAxisSource`](ue_ue.GizmoAxisSource.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Find](ue_ue.Interface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GizmoAxisSource`](ue_ue.GizmoAxisSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GizmoAxisSource`](ue_ue.GizmoAxisSource.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Load](ue_ue.Interface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)
