[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BaseMediaSource

# Class: BaseMediaSource

[ue/ue](../modules/ue_ue.md).BaseMediaSource

## Hierarchy

- [`MediaSource`](ue_ue.MediaSource.md)

  ↳ **`BaseMediaSource`**

  ↳↳ [`FileMediaSource`](ue_ue.FileMediaSource.md)

  ↳↳ [`ImgMediaSource`](ue_ue.ImgMediaSource.md)

  ↳↳ [`StreamMediaSource`](ue_ue.StreamMediaSource.md)

  ↳↳ [`TimeSynchronizableMediaSource`](ue_ue.TimeSynchronizableMediaSource.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BaseMediaSource.md#constructor)

### Properties

- [PlatformPlayerNames](ue_ue.BaseMediaSource.md#platformplayernames)
- [PlayerName](ue_ue.BaseMediaSource.md#playername)
- [\_\_tid\_BaseMediaSource\_\_](ue_ue.BaseMediaSource.md#__tid_basemediasource__)
- [\_\_tid\_MediaSource\_\_](ue_ue.BaseMediaSource.md#__tid_mediasource__)
- [\_\_tid\_Object\_\_](ue_ue.BaseMediaSource.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BaseMediaSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BaseMediaSource.md#executeubergraph)
- [GetClass](ue_ue.BaseMediaSource.md#getclass)
- [GetName](ue_ue.BaseMediaSource.md#getname)
- [GetOuter](ue_ue.BaseMediaSource.md#getouter)
- [GetUrl](ue_ue.BaseMediaSource.md#geturl)
- [GetWorld](ue_ue.BaseMediaSource.md#getworld)
- [SetMediaOptionBool](ue_ue.BaseMediaSource.md#setmediaoptionbool)
- [SetMediaOptionFloat](ue_ue.BaseMediaSource.md#setmediaoptionfloat)
- [SetMediaOptionInt64](ue_ue.BaseMediaSource.md#setmediaoptionint64)
- [SetMediaOptionString](ue_ue.BaseMediaSource.md#setmediaoptionstring)
- [Validate](ue_ue.BaseMediaSource.md#validate)
- [Find](ue_ue.BaseMediaSource.md#find)
- [Load](ue_ue.BaseMediaSource.md#load)
- [StaticClass](ue_ue.BaseMediaSource.md#staticclass)

## Constructors

### constructor

• **new BaseMediaSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MediaSource](ue_ue.MediaSource.md).[constructor](ue_ue.MediaSource.md#constructor)

## Properties

### PlatformPlayerNames

• **PlatformPlayerNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

___

### PlayerName

• **PlayerName**: `string`

___

### \_\_tid\_BaseMediaSource\_\_

• **\_\_tid\_BaseMediaSource\_\_**: `boolean`

___

### \_\_tid\_MediaSource\_\_

• **\_\_tid\_MediaSource\_\_**: `boolean`

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[__tid_MediaSource__](ue_ue.MediaSource.md#__tid_mediasource__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[__tid_Object__](ue_ue.MediaSource.md#__tid_object__)

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

[MediaSource](ue_ue.MediaSource.md).[CreateDefaultSubobject](ue_ue.MediaSource.md#createdefaultsubobject)

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

[MediaSource](ue_ue.MediaSource.md).[ExecuteUbergraph](ue_ue.MediaSource.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[GetClass](ue_ue.MediaSource.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[GetName](ue_ue.MediaSource.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[GetOuter](ue_ue.MediaSource.md#getouter)

___

### GetUrl

▸ **GetUrl**(): `string`

#### Returns

`string`

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[GetUrl](ue_ue.MediaSource.md#geturl)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[GetWorld](ue_ue.MediaSource.md#getworld)

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

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[SetMediaOptionBool](ue_ue.MediaSource.md#setmediaoptionbool)

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

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[SetMediaOptionFloat](ue_ue.MediaSource.md#setmediaoptionfloat)

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

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[SetMediaOptionInt64](ue_ue.MediaSource.md#setmediaoptionint64)

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

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[SetMediaOptionString](ue_ue.MediaSource.md#setmediaoptionstring)

___

### Validate

▸ **Validate**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MediaSource](ue_ue.MediaSource.md).[Validate](ue_ue.MediaSource.md#validate)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BaseMediaSource`](ue_ue.BaseMediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BaseMediaSource`](ue_ue.BaseMediaSource.md)

#### Overrides

[MediaSource](ue_ue.MediaSource.md).[Find](ue_ue.MediaSource.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BaseMediaSource`](ue_ue.BaseMediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BaseMediaSource`](ue_ue.BaseMediaSource.md)

#### Overrides

[MediaSource](ue_ue.MediaSource.md).[Load](ue_ue.MediaSource.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MediaSource](ue_ue.MediaSource.md).[StaticClass](ue_ue.MediaSource.md#staticclass)
