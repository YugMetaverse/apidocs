[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LightingBuildInfo

# Class: LightingBuildInfo

[ue/ue](../modules/ue_ue.md).LightingBuildInfo

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LightingBuildInfo`**

## Table of contents

### Constructors

- [constructor](ue_ue.LightingBuildInfo.md#constructor)

### Properties

- [LevelName](ue_ue.LightingBuildInfo.md#levelname)
- [LightingTime](ue_ue.LightingBuildInfo.md#lightingtime)
- [Object](ue_ue.LightingBuildInfo.md#object)
- [TotalTexelMemory](ue_ue.LightingBuildInfo.md#totaltexelmemory)
- [UnmappedTexelsMemory](ue_ue.LightingBuildInfo.md#unmappedtexelsmemory)
- [UnmappedTexelsPercentage](ue_ue.LightingBuildInfo.md#unmappedtexelspercentage)
- [\_\_tid\_LightingBuildInfo\_\_](ue_ue.LightingBuildInfo.md#__tid_lightingbuildinfo__)
- [\_\_tid\_Object\_\_](ue_ue.LightingBuildInfo.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LightingBuildInfo.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LightingBuildInfo.md#executeubergraph)
- [GetClass](ue_ue.LightingBuildInfo.md#getclass)
- [GetName](ue_ue.LightingBuildInfo.md#getname)
- [GetOuter](ue_ue.LightingBuildInfo.md#getouter)
- [GetWorld](ue_ue.LightingBuildInfo.md#getworld)
- [Find](ue_ue.LightingBuildInfo.md#find)
- [Load](ue_ue.LightingBuildInfo.md#load)
- [StaticClass](ue_ue.LightingBuildInfo.md#staticclass)

## Constructors

### constructor

• **new LightingBuildInfo**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### LevelName

• **LevelName**: `string`

___

### LightingTime

• **LightingTime**: `number`

___

### Object

• **Object**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### TotalTexelMemory

• **TotalTexelMemory**: `number`

___

### UnmappedTexelsMemory

• **UnmappedTexelsMemory**: `number`

___

### UnmappedTexelsPercentage

• **UnmappedTexelsPercentage**: `number`

___

### \_\_tid\_LightingBuildInfo\_\_

• **\_\_tid\_LightingBuildInfo\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LightingBuildInfo`](ue_ue.LightingBuildInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LightingBuildInfo`](ue_ue.LightingBuildInfo.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LightingBuildInfo`](ue_ue.LightingBuildInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LightingBuildInfo`](ue_ue.LightingBuildInfo.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
