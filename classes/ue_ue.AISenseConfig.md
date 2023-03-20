[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AISenseConfig

# Class: AISenseConfig

[ue/ue](../modules/ue_ue.md).AISenseConfig

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AISenseConfig`**

  ↳↳ [`AISenseConfig_Blueprint`](ue_ue.AISenseConfig_Blueprint.md)

  ↳↳ [`AISenseConfig_Damage`](ue_ue.AISenseConfig_Damage.md)

  ↳↳ [`AISenseConfig_Hearing`](ue_ue.AISenseConfig_Hearing.md)

  ↳↳ [`AISenseConfig_Prediction`](ue_ue.AISenseConfig_Prediction.md)

  ↳↳ [`AISenseConfig_Sight`](ue_ue.AISenseConfig_Sight.md)

  ↳↳ [`AISenseConfig_Team`](ue_ue.AISenseConfig_Team.md)

  ↳↳ [`AISenseConfig_Touch`](ue_ue.AISenseConfig_Touch.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AISenseConfig.md#constructor)

### Properties

- [DebugColor](ue_ue.AISenseConfig.md#debugcolor)
- [MaxAge](ue_ue.AISenseConfig.md#maxage)
- [\_\_tid\_AISenseConfig\_\_](ue_ue.AISenseConfig.md#__tid_aisenseconfig__)
- [\_\_tid\_Object\_\_](ue_ue.AISenseConfig.md#__tid_object__)
- [bStartsEnabled](ue_ue.AISenseConfig.md#bstartsenabled)

### Methods

- [CreateDefaultSubobject](ue_ue.AISenseConfig.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AISenseConfig.md#executeubergraph)
- [GetClass](ue_ue.AISenseConfig.md#getclass)
- [GetName](ue_ue.AISenseConfig.md#getname)
- [GetOuter](ue_ue.AISenseConfig.md#getouter)
- [GetWorld](ue_ue.AISenseConfig.md#getworld)
- [Find](ue_ue.AISenseConfig.md#find)
- [Load](ue_ue.AISenseConfig.md#load)
- [StaticClass](ue_ue.AISenseConfig.md#staticclass)

## Constructors

### constructor

• **new AISenseConfig**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DebugColor

• **DebugColor**: [`Color`](ue_ue_s.Color.md)

___

### MaxAge

• **MaxAge**: `number`

___

### \_\_tid\_AISenseConfig\_\_

• **\_\_tid\_AISenseConfig\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bStartsEnabled

• **bStartsEnabled**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AISenseConfig`](ue_ue.AISenseConfig.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AISenseConfig`](ue_ue.AISenseConfig.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AISenseConfig`](ue_ue.AISenseConfig.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AISenseConfig`](ue_ue.AISenseConfig.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
