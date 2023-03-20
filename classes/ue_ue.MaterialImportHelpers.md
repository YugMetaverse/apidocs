[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialImportHelpers

# Class: MaterialImportHelpers

[ue/ue](../modules/ue_ue.md).MaterialImportHelpers

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MaterialImportHelpers`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialImportHelpers.md#constructor)

### Properties

- [\_\_tid\_MaterialImportHelpers\_\_](ue_ue.MaterialImportHelpers.md#__tid_materialimporthelpers__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialImportHelpers.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialImportHelpers.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialImportHelpers.md#executeubergraph)
- [GetClass](ue_ue.MaterialImportHelpers.md#getclass)
- [GetName](ue_ue.MaterialImportHelpers.md#getname)
- [GetOuter](ue_ue.MaterialImportHelpers.md#getouter)
- [GetWorld](ue_ue.MaterialImportHelpers.md#getworld)
- [Find](ue_ue.MaterialImportHelpers.md#find)
- [FindExistingMaterial](ue_ue.MaterialImportHelpers.md#findexistingmaterial)
- [FindExistingMaterialFromSearchLocation](ue_ue.MaterialImportHelpers.md#findexistingmaterialfromsearchlocation)
- [Load](ue_ue.MaterialImportHelpers.md#load)
- [StaticClass](ue_ue.MaterialImportHelpers.md#staticclass)

## Constructors

### constructor

• **new MaterialImportHelpers**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_MaterialImportHelpers\_\_

• **\_\_tid\_MaterialImportHelpers\_\_**: `boolean`

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialImportHelpers`](ue_ue.MaterialImportHelpers.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialImportHelpers`](ue_ue.MaterialImportHelpers.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### FindExistingMaterial

▸ `Static` **FindExistingMaterial**(`BasePath`, `MaterialFullName`, `bRecursivePaths`, `OutError`): [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BasePath` | `string` |
| `MaterialFullName` | `string` |
| `bRecursivePaths` | `boolean` |
| `OutError` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

[`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### FindExistingMaterialFromSearchLocation

▸ `Static` **FindExistingMaterialFromSearchLocation**(`MaterialFullName`, `BasePackagePath`, `SearchLocation`, `OutError`): [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialFullName` | `string` |
| `BasePackagePath` | `string` |
| `SearchLocation` | [`EMaterialSearchLocation`](../enums/ue_ue.EMaterialSearchLocation.md) |
| `OutError` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

[`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialImportHelpers`](ue_ue.MaterialImportHelpers.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialImportHelpers`](ue_ue.MaterialImportHelpers.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
