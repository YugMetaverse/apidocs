[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PEClassMetaData

# Class: PEClassMetaData

[ue/ue](../modules/ue_ue.md).PEClassMetaData

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PEClassMetaData`**

## Table of contents

### Constructors

- [constructor](ue_ue.PEClassMetaData.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.PEClassMetaData.md#__tid_object__)
- [\_\_tid\_PEClassMetaData\_\_](ue_ue.PEClassMetaData.md#__tid_peclassmetadata__)

### Methods

- [AddAutoCollapseCategory](ue_ue.PEClassMetaData.md#addautocollapsecategory)
- [AddAutoExpandCategory](ue_ue.PEClassMetaData.md#addautoexpandcategory)
- [AddClassGroup](ue_ue.PEClassMetaData.md#addclassgroup)
- [AddDontAutoCollapseCategory](ue_ue.PEClassMetaData.md#adddontautocollapsecategory)
- [AddHideCategory](ue_ue.PEClassMetaData.md#addhidecategory)
- [AddHideFunction](ue_ue.PEClassMetaData.md#addhidefunction)
- [AddShowCategory](ue_ue.PEClassMetaData.md#addshowcategory)
- [AddShowFunction](ue_ue.PEClassMetaData.md#addshowfunction)
- [AddShowSubCategory](ue_ue.PEClassMetaData.md#addshowsubcategory)
- [AddSparseDataType](ue_ue.PEClassMetaData.md#addsparsedatatype)
- [CreateDefaultSubobject](ue_ue.PEClassMetaData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PEClassMetaData.md#executeubergraph)
- [GetClass](ue_ue.PEClassMetaData.md#getclass)
- [GetName](ue_ue.PEClassMetaData.md#getname)
- [GetOuter](ue_ue.PEClassMetaData.md#getouter)
- [GetWorld](ue_ue.PEClassMetaData.md#getworld)
- [SetClassFlags](ue_ue.PEClassMetaData.md#setclassflags)
- [SetClassWithIn](ue_ue.PEClassMetaData.md#setclasswithin)
- [SetConfig](ue_ue.PEClassMetaData.md#setconfig)
- [SetMetaData](ue_ue.PEClassMetaData.md#setmetadata)
- [Find](ue_ue.PEClassMetaData.md#find)
- [Load](ue_ue.PEClassMetaData.md#load)
- [StaticClass](ue_ue.PEClassMetaData.md#staticclass)

## Constructors

### constructor

• **new PEClassMetaData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PEClassMetaData\_\_

• **\_\_tid\_PEClassMetaData\_\_**: `boolean`

## Methods

### AddAutoCollapseCategory

▸ **AddAutoCollapseCategory**(`InCategory`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCategory` | `string` |

#### Returns

`void`

___

### AddAutoExpandCategory

▸ **AddAutoExpandCategory**(`InCategory`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCategory` | `string` |

#### Returns

`void`

___

### AddClassGroup

▸ **AddClassGroup**(`InGroupName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InGroupName` | `string` |

#### Returns

`void`

___

### AddDontAutoCollapseCategory

▸ **AddDontAutoCollapseCategory**(`InCategory`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCategory` | `string` |

#### Returns

`void`

___

### AddHideCategory

▸ **AddHideCategory**(`InCategory`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCategory` | `string` |

#### Returns

`void`

___

### AddHideFunction

▸ **AddHideFunction**(`InFunctionName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFunctionName` | `string` |

#### Returns

`void`

___

### AddShowCategory

▸ **AddShowCategory**(`InCategory`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCategory` | `string` |

#### Returns

`void`

___

### AddShowFunction

▸ **AddShowFunction**(`InFunctionName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFunctionName` | `string` |

#### Returns

`void`

___

### AddShowSubCategory

▸ **AddShowSubCategory**(`InCategory`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCategory` | `string` |

#### Returns

`void`

___

### AddSparseDataType

▸ **AddSparseDataType**(`InType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InType` | `string` |

#### Returns

`void`

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

### SetClassFlags

▸ **SetClassFlags**(`InFlags`, `bInPlaceable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFlags` | `number` |
| `bInPlaceable` | `boolean` |

#### Returns

`void`

___

### SetClassWithIn

▸ **SetClassWithIn**(`InClassName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InClassName` | `string` |

#### Returns

`void`

___

### SetConfig

▸ **SetConfig**(`InConfigName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InConfigName` | `string` |

#### Returns

`void`

___

### SetMetaData

▸ **SetMetaData**(`InName`, `InValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `InValue` | `string` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PEClassMetaData`](ue_ue.PEClassMetaData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PEClassMetaData`](ue_ue.PEClassMetaData.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PEClassMetaData`](ue_ue.PEClassMetaData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PEClassMetaData`](ue_ue.PEClassMetaData.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
