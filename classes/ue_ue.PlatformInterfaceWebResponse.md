[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PlatformInterfaceWebResponse

# Class: PlatformInterfaceWebResponse

[ue/ue](../modules/ue_ue.md).PlatformInterfaceWebResponse

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PlatformInterfaceWebResponse`**

## Table of contents

### Constructors

- [constructor](ue_ue.PlatformInterfaceWebResponse.md#constructor)

### Properties

- [BinaryResponse](ue_ue.PlatformInterfaceWebResponse.md#binaryresponse)
- [OriginalURL](ue_ue.PlatformInterfaceWebResponse.md#originalurl)
- [ResponseCode](ue_ue.PlatformInterfaceWebResponse.md#responsecode)
- [StringResponse](ue_ue.PlatformInterfaceWebResponse.md#stringresponse)
- [Tag](ue_ue.PlatformInterfaceWebResponse.md#tag)
- [\_\_tid\_Object\_\_](ue_ue.PlatformInterfaceWebResponse.md#__tid_object__)
- [\_\_tid\_PlatformInterfaceWebResponse\_\_](ue_ue.PlatformInterfaceWebResponse.md#__tid_platforminterfacewebresponse__)

### Methods

- [CreateDefaultSubobject](ue_ue.PlatformInterfaceWebResponse.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PlatformInterfaceWebResponse.md#executeubergraph)
- [GetClass](ue_ue.PlatformInterfaceWebResponse.md#getclass)
- [GetHeader](ue_ue.PlatformInterfaceWebResponse.md#getheader)
- [GetHeaderValue](ue_ue.PlatformInterfaceWebResponse.md#getheadervalue)
- [GetName](ue_ue.PlatformInterfaceWebResponse.md#getname)
- [GetNumHeaders](ue_ue.PlatformInterfaceWebResponse.md#getnumheaders)
- [GetOuter](ue_ue.PlatformInterfaceWebResponse.md#getouter)
- [GetWorld](ue_ue.PlatformInterfaceWebResponse.md#getworld)
- [Find](ue_ue.PlatformInterfaceWebResponse.md#find)
- [Load](ue_ue.PlatformInterfaceWebResponse.md#load)
- [StaticClass](ue_ue.PlatformInterfaceWebResponse.md#staticclass)

## Constructors

### constructor

• **new PlatformInterfaceWebResponse**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BinaryResponse

• **BinaryResponse**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### OriginalURL

• **OriginalURL**: `string`

___

### ResponseCode

• **ResponseCode**: `number`

___

### StringResponse

• **StringResponse**: `string`

___

### Tag

• **Tag**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PlatformInterfaceWebResponse\_\_

• **\_\_tid\_PlatformInterfaceWebResponse\_\_**: `boolean`

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

### GetHeader

▸ **GetHeader**(`HeaderIndex`, `Header`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `HeaderIndex` | `number` |
| `Header` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `Value` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

___

### GetHeaderValue

▸ **GetHeaderValue**(`HeaderName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `HeaderName` | `string` |

#### Returns

`string`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetNumHeaders

▸ **GetNumHeaders**(): `number`

#### Returns

`number`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PlatformInterfaceWebResponse`](ue_ue.PlatformInterfaceWebResponse.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PlatformInterfaceWebResponse`](ue_ue.PlatformInterfaceWebResponse.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PlatformInterfaceWebResponse`](ue_ue.PlatformInterfaceWebResponse.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PlatformInterfaceWebResponse`](ue_ue.PlatformInterfaceWebResponse.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
