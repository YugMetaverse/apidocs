[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MediaSource

# Class: MediaSource

[ue/ue](../modules/ue_ue.md).MediaSource

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MediaSource`**

  ↳↳ [`BaseMediaSource`](ue_ue.BaseMediaSource.md)

  ↳↳ [`PlatformMediaSource`](ue_ue.PlatformMediaSource.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MediaSource.md#constructor)

### Properties

- [\_\_tid\_MediaSource\_\_](ue_ue.MediaSource.md#__tid_mediasource__)
- [\_\_tid\_Object\_\_](ue_ue.MediaSource.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MediaSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MediaSource.md#executeubergraph)
- [GetClass](ue_ue.MediaSource.md#getclass)
- [GetName](ue_ue.MediaSource.md#getname)
- [GetOuter](ue_ue.MediaSource.md#getouter)
- [GetUrl](ue_ue.MediaSource.md#geturl)
- [GetWorld](ue_ue.MediaSource.md#getworld)
- [SetMediaOptionBool](ue_ue.MediaSource.md#setmediaoptionbool)
- [SetMediaOptionFloat](ue_ue.MediaSource.md#setmediaoptionfloat)
- [SetMediaOptionInt64](ue_ue.MediaSource.md#setmediaoptionint64)
- [SetMediaOptionString](ue_ue.MediaSource.md#setmediaoptionstring)
- [Validate](ue_ue.MediaSource.md#validate)
- [Find](ue_ue.MediaSource.md#find)
- [Load](ue_ue.MediaSource.md#load)
- [StaticClass](ue_ue.MediaSource.md#staticclass)

## Constructors

### constructor

• **new MediaSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_MediaSource\_\_

• **\_\_tid\_MediaSource\_\_**: `boolean`

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

### GetUrl

▸ **GetUrl**(): `string`

#### Returns

`string`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### SetMediaOptionBool

▸ **SetMediaOptionBool**(`Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | `string` |
| `Value` | `boolean` |

#### Returns

`void`

___

### SetMediaOptionFloat

▸ **SetMediaOptionFloat**(`Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | `string` |
| `Value` | `number` |

#### Returns

`void`

___

### SetMediaOptionInt64

▸ **SetMediaOptionInt64**(`Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | `string` |
| `Value` | `bigint` |

#### Returns

`void`

___

### SetMediaOptionString

▸ **SetMediaOptionString**(`Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Key` | `string` |
| `Value` | `string` |

#### Returns

`void`

___

### Validate

▸ **Validate**(): `boolean`

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
