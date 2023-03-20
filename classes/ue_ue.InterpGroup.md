[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpGroup

# Class: InterpGroup

[ue/ue](../modules/ue_ue.md).InterpGroup

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InterpGroup`**

  ↳↳ [`InterpGroupDirector`](ue_ue.InterpGroupDirector.md)

  ↳↳ [`InterpGroupCamera`](ue_ue.InterpGroupCamera.md)

## Table of contents

### Constructors

- [constructor](ue_ue.InterpGroup.md#constructor)

### Properties

- [GroupColor](ue_ue.InterpGroup.md#groupcolor)
- [GroupName](ue_ue.InterpGroup.md#groupname)
- [InterpTracks](ue_ue.InterpGroup.md#interptracks)
- [\_\_tid\_InterpGroup\_\_](ue_ue.InterpGroup.md#__tid_interpgroup__)
- [\_\_tid\_Object\_\_](ue_ue.InterpGroup.md#__tid_object__)
- [bCollapsed](ue_ue.InterpGroup.md#bcollapsed)
- [bIsFolder](ue_ue.InterpGroup.md#bisfolder)
- [bIsParented](ue_ue.InterpGroup.md#bisparented)
- [bIsSelected](ue_ue.InterpGroup.md#bisselected)
- [bVisible](ue_ue.InterpGroup.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpGroup.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpGroup.md#executeubergraph)
- [GetClass](ue_ue.InterpGroup.md#getclass)
- [GetName](ue_ue.InterpGroup.md#getname)
- [GetOuter](ue_ue.InterpGroup.md#getouter)
- [GetWorld](ue_ue.InterpGroup.md#getworld)
- [Find](ue_ue.InterpGroup.md#find)
- [Load](ue_ue.InterpGroup.md#load)
- [StaticClass](ue_ue.InterpGroup.md#staticclass)

## Constructors

### constructor

• **new InterpGroup**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### GroupColor

• **GroupColor**: [`Color`](ue_ue_s.Color.md)

___

### GroupName

• **GroupName**: `string`

___

### InterpTracks

• **InterpTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

___

### \_\_tid\_InterpGroup\_\_

• **\_\_tid\_InterpGroup\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bCollapsed

• **bCollapsed**: `boolean`

___

### bIsFolder

• **bIsFolder**: `boolean`

___

### bIsParented

• **bIsParented**: `boolean`

___

### bIsSelected

• **bIsSelected**: `boolean`

___

### bVisible

• **bVisible**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpGroup`](ue_ue.InterpGroup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpGroup`](ue_ue.InterpGroup.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpGroup`](ue_ue.InterpGroup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpGroup`](ue_ue.InterpGroup.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
