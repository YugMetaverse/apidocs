[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameplayTaskResource

# Class: GameplayTaskResource

[ue/ue](../modules/ue_ue.md).GameplayTaskResource

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GameplayTaskResource`**

  ↳↳ [`AIResource_Logic`](ue_ue.AIResource_Logic.md)

  ↳↳ [`AIResource_Movement`](ue_ue.AIResource_Movement.md)

## Table of contents

### Constructors

- [constructor](ue_ue.GameplayTaskResource.md#constructor)

### Properties

- [AutoResourceID](ue_ue.GameplayTaskResource.md#autoresourceid)
- [ManualResourceID](ue_ue.GameplayTaskResource.md#manualresourceid)
- [\_\_tid\_GameplayTaskResource\_\_](ue_ue.GameplayTaskResource.md#__tid_gameplaytaskresource__)
- [\_\_tid\_Object\_\_](ue_ue.GameplayTaskResource.md#__tid_object__)
- [bManuallySetID](ue_ue.GameplayTaskResource.md#bmanuallysetid)

### Methods

- [CreateDefaultSubobject](ue_ue.GameplayTaskResource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GameplayTaskResource.md#executeubergraph)
- [GetClass](ue_ue.GameplayTaskResource.md#getclass)
- [GetName](ue_ue.GameplayTaskResource.md#getname)
- [GetOuter](ue_ue.GameplayTaskResource.md#getouter)
- [GetWorld](ue_ue.GameplayTaskResource.md#getworld)
- [Find](ue_ue.GameplayTaskResource.md#find)
- [Load](ue_ue.GameplayTaskResource.md#load)
- [StaticClass](ue_ue.GameplayTaskResource.md#staticclass)

## Constructors

### constructor

• **new GameplayTaskResource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AutoResourceID

• **AutoResourceID**: `number`

___

### ManualResourceID

• **ManualResourceID**: `number`

___

### \_\_tid\_GameplayTaskResource\_\_

• **\_\_tid\_GameplayTaskResource\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bManuallySetID

• **bManuallySetID**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameplayTaskResource`](ue_ue.GameplayTaskResource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameplayTaskResource`](ue_ue.GameplayTaskResource.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameplayTaskResource`](ue_ue.GameplayTaskResource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameplayTaskResource`](ue_ue.GameplayTaskResource.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
