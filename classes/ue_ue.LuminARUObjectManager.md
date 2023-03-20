[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LuminARUObjectManager

# Class: LuminARUObjectManager

[ue/ue](../modules/ue_ue.md).LuminARUObjectManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LuminARUObjectManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.LuminARUObjectManager.md#constructor)

### Properties

- [AllAnchors](ue_ue.LuminARUObjectManager.md#allanchors)
- [\_\_tid\_LuminARUObjectManager\_\_](ue_ue.LuminARUObjectManager.md#__tid_luminaruobjectmanager__)
- [\_\_tid\_Object\_\_](ue_ue.LuminARUObjectManager.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LuminARUObjectManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LuminARUObjectManager.md#executeubergraph)
- [GetClass](ue_ue.LuminARUObjectManager.md#getclass)
- [GetName](ue_ue.LuminARUObjectManager.md#getname)
- [GetOuter](ue_ue.LuminARUObjectManager.md#getouter)
- [GetWorld](ue_ue.LuminARUObjectManager.md#getworld)
- [Find](ue_ue.LuminARUObjectManager.md#find)
- [Load](ue_ue.LuminARUObjectManager.md#load)
- [StaticClass](ue_ue.LuminARUObjectManager.md#staticclass)

## Constructors

### constructor

• **new LuminARUObjectManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AllAnchors

• **AllAnchors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ARPin`](ue_ue.ARPin.md)\>

___

### \_\_tid\_LuminARUObjectManager\_\_

• **\_\_tid\_LuminARUObjectManager\_\_**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LuminARUObjectManager`](ue_ue.LuminARUObjectManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LuminARUObjectManager`](ue_ue.LuminARUObjectManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LuminARUObjectManager`](ue_ue.LuminARUObjectManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LuminARUObjectManager`](ue_ue.LuminARUObjectManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
