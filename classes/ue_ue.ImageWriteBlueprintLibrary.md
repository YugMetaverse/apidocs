[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ImageWriteBlueprintLibrary

# Class: ImageWriteBlueprintLibrary

[ue/ue](../modules/ue_ue.md).ImageWriteBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`ImageWriteBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.ImageWriteBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.ImageWriteBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_ImageWriteBlueprintLibrary\_\_](ue_ue.ImageWriteBlueprintLibrary.md#__tid_imagewriteblueprintlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.ImageWriteBlueprintLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ImageWriteBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ImageWriteBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.ImageWriteBlueprintLibrary.md#getclass)
- [GetName](ue_ue.ImageWriteBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.ImageWriteBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.ImageWriteBlueprintLibrary.md#getworld)
- [ExportToDisk](ue_ue.ImageWriteBlueprintLibrary.md#exporttodisk)
- [Find](ue_ue.ImageWriteBlueprintLibrary.md#find)
- [Load](ue_ue.ImageWriteBlueprintLibrary.md#load)
- [StaticClass](ue_ue.ImageWriteBlueprintLibrary.md#staticclass)

## Constructors

### constructor

• **new ImageWriteBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_ImageWriteBlueprintLibrary\_\_

• **\_\_tid\_ImageWriteBlueprintLibrary\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### ExportToDisk

▸ `Static` **ExportToDisk**(`Texture`, `Filename`, `Options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Texture` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |
| `Filename` | `string` |
| `Options` | [`ImageWriteOptions`](ue_ue.ImageWriteOptions.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ImageWriteBlueprintLibrary`](ue_ue.ImageWriteBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ImageWriteBlueprintLibrary`](ue_ue.ImageWriteBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ImageWriteBlueprintLibrary`](ue_ue.ImageWriteBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ImageWriteBlueprintLibrary`](ue_ue.ImageWriteBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
