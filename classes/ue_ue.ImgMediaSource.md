[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ImgMediaSource

# Class: ImgMediaSource

[ue/ue](../modules/ue_ue.md).ImgMediaSource

## Hierarchy

- [`BaseMediaSource`](ue_ue.BaseMediaSource.md)

  ↳ **`ImgMediaSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.ImgMediaSource.md#constructor)

### Properties

- [FrameRateOverride](ue_ue.ImgMediaSource.md#framerateoverride)
- [PlatformPlayerNames](ue_ue.ImgMediaSource.md#platformplayernames)
- [PlayerName](ue_ue.ImgMediaSource.md#playername)
- [ProxyOverride](ue_ue.ImgMediaSource.md#proxyoverride)
- [SequencePath](ue_ue.ImgMediaSource.md#sequencepath)
- [\_\_tid\_BaseMediaSource\_\_](ue_ue.ImgMediaSource.md#__tid_basemediasource__)
- [\_\_tid\_ImgMediaSource\_\_](ue_ue.ImgMediaSource.md#__tid_imgmediasource__)
- [\_\_tid\_MediaSource\_\_](ue_ue.ImgMediaSource.md#__tid_mediasource__)
- [\_\_tid\_Object\_\_](ue_ue.ImgMediaSource.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ImgMediaSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ImgMediaSource.md#executeubergraph)
- [GetClass](ue_ue.ImgMediaSource.md#getclass)
- [GetName](ue_ue.ImgMediaSource.md#getname)
- [GetOuter](ue_ue.ImgMediaSource.md#getouter)
- [GetProxies](ue_ue.ImgMediaSource.md#getproxies)
- [GetSequencePath](ue_ue.ImgMediaSource.md#getsequencepath)
- [GetUrl](ue_ue.ImgMediaSource.md#geturl)
- [GetWorld](ue_ue.ImgMediaSource.md#getworld)
- [SetMediaOptionBool](ue_ue.ImgMediaSource.md#setmediaoptionbool)
- [SetMediaOptionFloat](ue_ue.ImgMediaSource.md#setmediaoptionfloat)
- [SetMediaOptionInt64](ue_ue.ImgMediaSource.md#setmediaoptionint64)
- [SetMediaOptionString](ue_ue.ImgMediaSource.md#setmediaoptionstring)
- [SetSequencePath](ue_ue.ImgMediaSource.md#setsequencepath)
- [Validate](ue_ue.ImgMediaSource.md#validate)
- [Find](ue_ue.ImgMediaSource.md#find)
- [Load](ue_ue.ImgMediaSource.md#load)
- [StaticClass](ue_ue.ImgMediaSource.md#staticclass)

## Constructors

### constructor

• **new ImgMediaSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BaseMediaSource](ue_ue.BaseMediaSource.md).[constructor](ue_ue.BaseMediaSource.md#constructor)

## Properties

### FrameRateOverride

• **FrameRateOverride**: [`FrameRate`](ue_ue.FrameRate.md)

___

### PlatformPlayerNames

• **PlatformPlayerNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[PlatformPlayerNames](ue_ue.BaseMediaSource.md#platformplayernames)

___

### PlayerName

• **PlayerName**: `string`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[PlayerName](ue_ue.BaseMediaSource.md#playername)

___

### ProxyOverride

• **ProxyOverride**: `string`

___

### SequencePath

• **SequencePath**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### \_\_tid\_BaseMediaSource\_\_

• **\_\_tid\_BaseMediaSource\_\_**: `boolean`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[__tid_BaseMediaSource__](ue_ue.BaseMediaSource.md#__tid_basemediasource__)

___

### \_\_tid\_ImgMediaSource\_\_

• **\_\_tid\_ImgMediaSource\_\_**: `boolean`

___

### \_\_tid\_MediaSource\_\_

• **\_\_tid\_MediaSource\_\_**: `boolean`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[__tid_MediaSource__](ue_ue.BaseMediaSource.md#__tid_mediasource__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[__tid_Object__](ue_ue.BaseMediaSource.md#__tid_object__)

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

[BaseMediaSource](ue_ue.BaseMediaSource.md).[CreateDefaultSubobject](ue_ue.BaseMediaSource.md#createdefaultsubobject)

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

[BaseMediaSource](ue_ue.BaseMediaSource.md).[ExecuteUbergraph](ue_ue.BaseMediaSource.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetClass](ue_ue.BaseMediaSource.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetName](ue_ue.BaseMediaSource.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetOuter](ue_ue.BaseMediaSource.md#getouter)

___

### GetProxies

▸ **GetProxies**(`OutProxies`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutProxies` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

___

### GetSequencePath

▸ **GetSequencePath**(): `string`

#### Returns

`string`

___

### GetUrl

▸ **GetUrl**(): `string`

#### Returns

`string`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetUrl](ue_ue.BaseMediaSource.md#geturl)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetWorld](ue_ue.BaseMediaSource.md#getworld)

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

[BaseMediaSource](ue_ue.BaseMediaSource.md).[SetMediaOptionBool](ue_ue.BaseMediaSource.md#setmediaoptionbool)

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

[BaseMediaSource](ue_ue.BaseMediaSource.md).[SetMediaOptionFloat](ue_ue.BaseMediaSource.md#setmediaoptionfloat)

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

[BaseMediaSource](ue_ue.BaseMediaSource.md).[SetMediaOptionInt64](ue_ue.BaseMediaSource.md#setmediaoptionint64)

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

[BaseMediaSource](ue_ue.BaseMediaSource.md).[SetMediaOptionString](ue_ue.BaseMediaSource.md#setmediaoptionstring)

___

### SetSequencePath

▸ **SetSequencePath**(`Path`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Path` | `string` |

#### Returns

`void`

___

### Validate

▸ **Validate**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[Validate](ue_ue.BaseMediaSource.md#validate)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ImgMediaSource`](ue_ue.ImgMediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ImgMediaSource`](ue_ue.ImgMediaSource.md)

#### Overrides

[BaseMediaSource](ue_ue.BaseMediaSource.md).[Find](ue_ue.BaseMediaSource.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ImgMediaSource`](ue_ue.ImgMediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ImgMediaSource`](ue_ue.ImgMediaSource.md)

#### Overrides

[BaseMediaSource](ue_ue.BaseMediaSource.md).[Load](ue_ue.BaseMediaSource.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BaseMediaSource](ue_ue.BaseMediaSource.md).[StaticClass](ue_ue.BaseMediaSource.md#staticclass)
