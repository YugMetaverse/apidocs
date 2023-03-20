[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TimeSynchronizableMediaSource

# Class: TimeSynchronizableMediaSource

[ue/ue](../modules/ue_ue.md).TimeSynchronizableMediaSource

## Hierarchy

- [`BaseMediaSource`](ue_ue.BaseMediaSource.md)

  ↳ **`TimeSynchronizableMediaSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.TimeSynchronizableMediaSource.md#constructor)

### Properties

- [FrameDelay](ue_ue.TimeSynchronizableMediaSource.md#framedelay)
- [PlatformPlayerNames](ue_ue.TimeSynchronizableMediaSource.md#platformplayernames)
- [PlayerName](ue_ue.TimeSynchronizableMediaSource.md#playername)
- [TimeDelay](ue_ue.TimeSynchronizableMediaSource.md#timedelay)
- [\_\_tid\_BaseMediaSource\_\_](ue_ue.TimeSynchronizableMediaSource.md#__tid_basemediasource__)
- [\_\_tid\_MediaSource\_\_](ue_ue.TimeSynchronizableMediaSource.md#__tid_mediasource__)
- [\_\_tid\_Object\_\_](ue_ue.TimeSynchronizableMediaSource.md#__tid_object__)
- [\_\_tid\_TimeSynchronizableMediaSource\_\_](ue_ue.TimeSynchronizableMediaSource.md#__tid_timesynchronizablemediasource__)
- [bUseTimeSynchronization](ue_ue.TimeSynchronizableMediaSource.md#busetimesynchronization)

### Methods

- [CreateDefaultSubobject](ue_ue.TimeSynchronizableMediaSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TimeSynchronizableMediaSource.md#executeubergraph)
- [GetClass](ue_ue.TimeSynchronizableMediaSource.md#getclass)
- [GetName](ue_ue.TimeSynchronizableMediaSource.md#getname)
- [GetOuter](ue_ue.TimeSynchronizableMediaSource.md#getouter)
- [GetUrl](ue_ue.TimeSynchronizableMediaSource.md#geturl)
- [GetWorld](ue_ue.TimeSynchronizableMediaSource.md#getworld)
- [SetMediaOptionBool](ue_ue.TimeSynchronizableMediaSource.md#setmediaoptionbool)
- [SetMediaOptionFloat](ue_ue.TimeSynchronizableMediaSource.md#setmediaoptionfloat)
- [SetMediaOptionInt64](ue_ue.TimeSynchronizableMediaSource.md#setmediaoptionint64)
- [SetMediaOptionString](ue_ue.TimeSynchronizableMediaSource.md#setmediaoptionstring)
- [Validate](ue_ue.TimeSynchronizableMediaSource.md#validate)
- [Find](ue_ue.TimeSynchronizableMediaSource.md#find)
- [Load](ue_ue.TimeSynchronizableMediaSource.md#load)
- [StaticClass](ue_ue.TimeSynchronizableMediaSource.md#staticclass)

## Constructors

### constructor

• **new TimeSynchronizableMediaSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BaseMediaSource](ue_ue.BaseMediaSource.md).[constructor](ue_ue.BaseMediaSource.md#constructor)

#### Defined in

[ue/ue.d.ts:63688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63688)

## Properties

### FrameDelay

• **FrameDelay**: `number`

#### Defined in

[ue/ue.d.ts:63690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63690)

___

### PlatformPlayerNames

• **PlatformPlayerNames**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[PlatformPlayerNames](ue_ue.BaseMediaSource.md#platformplayernames)

#### Defined in

[ue/ue.d.ts:23507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23507)

___

### PlayerName

• **PlayerName**: `string`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[PlayerName](ue_ue.BaseMediaSource.md#playername)

#### Defined in

[ue/ue.d.ts:23508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23508)

___

### TimeDelay

• **TimeDelay**: `number`

#### Defined in

[ue/ue.d.ts:63691](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63691)

___

### \_\_tid\_BaseMediaSource\_\_

• **\_\_tid\_BaseMediaSource\_\_**: `boolean`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[__tid_BaseMediaSource__](ue_ue.BaseMediaSource.md#__tid_basemediasource__)

#### Defined in

[ue/ue.d.ts:23513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23513)

___

### \_\_tid\_MediaSource\_\_

• **\_\_tid\_MediaSource\_\_**: `boolean`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[__tid_MediaSource__](ue_ue.BaseMediaSource.md#__tid_mediasource__)

#### Defined in

[ue/ue.d.ts:23502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23502)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[__tid_Object__](ue_ue.BaseMediaSource.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_TimeSynchronizableMediaSource\_\_

• **\_\_tid\_TimeSynchronizableMediaSource\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63696](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63696)

___

### bUseTimeSynchronization

• **bUseTimeSynchronization**: `boolean`

#### Defined in

[ue/ue.d.ts:63689](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63689)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetClass](ue_ue.BaseMediaSource.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetName](ue_ue.BaseMediaSource.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetOuter](ue_ue.BaseMediaSource.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetUrl

▸ **GetUrl**(): `string`

#### Returns

`string`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetUrl](ue_ue.BaseMediaSource.md#geturl)

#### Defined in

[ue/ue.d.ts:23492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23492)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[GetWorld](ue_ue.BaseMediaSource.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:23493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23493)

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

#### Defined in

[ue/ue.d.ts:23494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23494)

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

#### Defined in

[ue/ue.d.ts:23495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23495)

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

#### Defined in

[ue/ue.d.ts:23496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23496)

___

### Validate

▸ **Validate**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[BaseMediaSource](ue_ue.BaseMediaSource.md).[Validate](ue_ue.BaseMediaSource.md#validate)

#### Defined in

[ue/ue.d.ts:23497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23497)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TimeSynchronizableMediaSource`](ue_ue.TimeSynchronizableMediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TimeSynchronizableMediaSource`](ue_ue.TimeSynchronizableMediaSource.md)

#### Overrides

[BaseMediaSource](ue_ue.BaseMediaSource.md).[Find](ue_ue.BaseMediaSource.md#find)

#### Defined in

[ue/ue.d.ts:63693](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63693)

___

### Load

▸ `Static` **Load**(`InName`): [`TimeSynchronizableMediaSource`](ue_ue.TimeSynchronizableMediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TimeSynchronizableMediaSource`](ue_ue.TimeSynchronizableMediaSource.md)

#### Overrides

[BaseMediaSource](ue_ue.BaseMediaSource.md).[Load](ue_ue.BaseMediaSource.md#load)

#### Defined in

[ue/ue.d.ts:63694](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63694)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BaseMediaSource](ue_ue.BaseMediaSource.md).[StaticClass](ue_ue.BaseMediaSource.md#staticclass)

#### Defined in

[ue/ue.d.ts:63692](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63692)
