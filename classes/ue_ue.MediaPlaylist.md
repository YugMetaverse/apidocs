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

#### Defined in

[ue/ue.d.ts:50123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50123)

## Properties

### Items

• **Items**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MediaSource`](ue_ue.MediaSource.md)\>

#### Defined in

[ue/ue.d.ts:50124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50124)

___

### \_\_tid\_MediaPlaylist\_\_

• **\_\_tid\_MediaPlaylist\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:50141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50141)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

## Methods

### Add

▸ **Add**(`MediaSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50125)

___

### AddFile

▸ **AddFile**(`FilePath`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FilePath` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50126)

___

### AddUrl

▸ **AddUrl**(`Url`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Url` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50127)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### Get

▸ **Get**(`Index`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

#### Defined in

[ue/ue.d.ts:50128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50128)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetNext

▸ **GetNext**(`InOutIndex`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOutIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

#### Defined in

[ue/ue.d.ts:50129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50129)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetPrevious

▸ **GetPrevious**(`InOutIndex`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOutIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

#### Defined in

[ue/ue.d.ts:50130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50130)

___

### GetRandom

▸ **GetRandom**(`OutIndex`): [`MediaSource`](ue_ue.MediaSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`MediaSource`](ue_ue.MediaSource.md)

#### Defined in

[ue/ue.d.ts:50131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50131)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:50132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50132)

___

### Num

▸ **Num**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:50133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50133)

___

### Remove

▸ **Remove**(`MediaSource`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MediaSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaSource`](ue_ue.MediaSource.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50134)

___

### RemoveAt

▸ **RemoveAt**(`Index`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:50135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50135)

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

#### Defined in

[ue/ue.d.ts:50136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50136)

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

#### Defined in

[ue/ue.d.ts:50138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50138)

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

#### Defined in

[ue/ue.d.ts:50139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50139)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:50137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50137)
