[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MediaPlaylist

# Class: MediaPlaylist

[ue/ue](../modules/ue_ue.md).MediaPlaylist

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MediaPlaylist`**

## Table of contents

### Constructors

- [constructor](ue_ue.MediaPlaylist.md#constructor)

### Properties

- [Items](ue_ue.MediaPlaylist.md#items)
- [\_\_tid\_MediaPlaylist\_\_](ue_ue.MediaPlaylist.md#__tid_mediaplaylist__)
- [\_\_tid\_Object\_\_](ue_ue.MediaPlaylist.md#__tid_object__)

### Methods

- [Add](ue_ue.MediaPlaylist.md#add)
- [AddFile](ue_ue.MediaPlaylist.md#addfile)
- [AddUrl](ue_ue.MediaPlaylist.md#addurl)
- [CreateDefaultSubobject](ue_ue.MediaPlaylist.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MediaPlaylist.md#executeubergraph)
- [Get](ue_ue.MediaPlaylist.md#get)
- [GetClass](ue_ue.MediaPlaylist.md#getclass)
- [GetName](ue_ue.MediaPlaylist.md#getname)
- [GetNext](ue_ue.MediaPlaylist.md#getnext)
- [GetOuter](ue_ue.MediaPlaylist.md#getouter)
- [GetPrevious](ue_ue.MediaPlaylist.md#getprevious)
- [GetRandom](ue_ue.MediaPlaylist.md#getrandom)
- [GetWorld](ue_ue.MediaPlaylist.md#getworld)
- [Insert](ue_ue.MediaPlaylist.md#insert)
- [Num](ue_ue.MediaPlaylist.md#num)
- [Remove](ue_ue.MediaPlaylist.md#remove)
- [RemoveAt](ue_ue.MediaPlaylist.md#removeat)
- [Replace](ue_ue.MediaPlaylist.md#replace)
- [Find](ue_ue.MediaPlaylist.md#find)
- [Load](ue_ue.MediaPlaylist.md#load)
- [StaticClass](ue_ue.MediaPlaylist.md#staticclass)

## Constructors

### constructor

• **new MediaPlaylist**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Items

• **Items**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MediaSource`](ue_ue.MediaSource.md)\>

___

### \_\_tid\_MediaPlaylist\_\_

• **\_\_tid\_MediaPlaylist\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

## Methods

### Add

▸ **Add**(`MediaSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`boolean`

___

### AddFile

▸ **AddFile**(`FilePath`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FilePath` | `string` |

#### Returns

`boolean`

___

### AddUrl

▸ **AddUrl**(`Url`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Url` | `string` |

#### Returns

`boolean`

___

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

### Get

▸ **Get**(`Index`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

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

### GetNext

▸ **GetNext**(`InOutIndex`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOutIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetPrevious

▸ **GetPrevious**(`InOutIndex`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOutIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

___

### GetRandom

▸ **GetRandom**(`OutIndex`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Insert

▸ **Insert**(`MediaSource`, `Index`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |
| `Index` | `number` |

#### Returns

`void`

___

### Num

▸ **Num**(): `number`

#### Returns

`number`

___

### Remove

▸ **Remove**(`MediaSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`boolean`

___

### RemoveAt

▸ **RemoveAt**(`Index`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`boolean`

___

### Replace

▸ **Replace**(`Index`, `Replacement`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `Replacement` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MediaPlaylist`](ue_ue.MediaPlaylist.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MediaPlaylist`](ue_ue.MediaPlaylist.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MediaPlaylist`](ue_ue.MediaPlaylist.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MediaPlaylist`](ue_ue.MediaPlaylist.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
