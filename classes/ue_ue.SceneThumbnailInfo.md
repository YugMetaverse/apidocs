[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SceneThumbnailInfo

# Class: SceneThumbnailInfo

[ue/ue](../modules/ue_ue.md).SceneThumbnailInfo

## Hierarchy

- [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

  ↳ **`SceneThumbnailInfo`**

  ↳↳ [`SceneThumbnailInfoWithPrimitive`](ue_ue.SceneThumbnailInfoWithPrimitive.md)

  ↳↳ [`WorldThumbnailInfo`](ue_ue.WorldThumbnailInfo.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SceneThumbnailInfo.md#constructor)

### Properties

- [OrbitPitch](ue_ue.SceneThumbnailInfo.md#orbitpitch)
- [OrbitYaw](ue_ue.SceneThumbnailInfo.md#orbityaw)
- [OrbitZoom](ue_ue.SceneThumbnailInfo.md#orbitzoom)
- [\_\_tid\_Object\_\_](ue_ue.SceneThumbnailInfo.md#__tid_object__)
- [\_\_tid\_SceneThumbnailInfo\_\_](ue_ue.SceneThumbnailInfo.md#__tid_scenethumbnailinfo__)
- [\_\_tid\_ThumbnailInfo\_\_](ue_ue.SceneThumbnailInfo.md#__tid_thumbnailinfo__)

### Methods

- [CreateDefaultSubobject](ue_ue.SceneThumbnailInfo.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SceneThumbnailInfo.md#executeubergraph)
- [GetClass](ue_ue.SceneThumbnailInfo.md#getclass)
- [GetName](ue_ue.SceneThumbnailInfo.md#getname)
- [GetOuter](ue_ue.SceneThumbnailInfo.md#getouter)
- [GetWorld](ue_ue.SceneThumbnailInfo.md#getworld)
- [Find](ue_ue.SceneThumbnailInfo.md#find)
- [Load](ue_ue.SceneThumbnailInfo.md#load)
- [StaticClass](ue_ue.SceneThumbnailInfo.md#staticclass)

## Constructors

### constructor

• **new SceneThumbnailInfo**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[constructor](ue_ue.ThumbnailInfo.md#constructor)

## Properties

### OrbitPitch

• **OrbitPitch**: `number`

___

### OrbitYaw

• **OrbitYaw**: `number`

___

### OrbitZoom

• **OrbitZoom**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[__tid_Object__](ue_ue.ThumbnailInfo.md#__tid_object__)

___

### \_\_tid\_SceneThumbnailInfo\_\_

• **\_\_tid\_SceneThumbnailInfo\_\_**: `boolean`

___

### \_\_tid\_ThumbnailInfo\_\_

• **\_\_tid\_ThumbnailInfo\_\_**: `boolean`

#### Inherited from

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[__tid_ThumbnailInfo__](ue_ue.ThumbnailInfo.md#__tid_thumbnailinfo__)

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

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[CreateDefaultSubobject](ue_ue.ThumbnailInfo.md#createdefaultsubobject)

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

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[ExecuteUbergraph](ue_ue.ThumbnailInfo.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[GetClass](ue_ue.ThumbnailInfo.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[GetName](ue_ue.ThumbnailInfo.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[GetOuter](ue_ue.ThumbnailInfo.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[GetWorld](ue_ue.ThumbnailInfo.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SceneThumbnailInfo`](ue_ue.SceneThumbnailInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SceneThumbnailInfo`](ue_ue.SceneThumbnailInfo.md)

#### Overrides

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[Find](ue_ue.ThumbnailInfo.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SceneThumbnailInfo`](ue_ue.SceneThumbnailInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SceneThumbnailInfo`](ue_ue.SceneThumbnailInfo.md)

#### Overrides

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[Load](ue_ue.ThumbnailInfo.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ThumbnailInfo](ue_ue.ThumbnailInfo.md).[StaticClass](ue_ue.ThumbnailInfo.md#staticclass)
