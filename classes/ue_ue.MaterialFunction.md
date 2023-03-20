[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialFunction

# Class: MaterialFunction

[ue/ue](../modules/ue_ue.md).MaterialFunction

## Hierarchy

- [`MaterialFunctionInterface`](ue_ue.MaterialFunctionInterface.md)

  ↳ **`MaterialFunction`**

  ↳↳ [`MaterialFunctionMaterialLayer`](ue_ue.MaterialFunctionMaterialLayer.md)

  ↳↳ [`MaterialFunctionMaterialLayerBlend`](ue_ue.MaterialFunctionMaterialLayerBlend.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialFunction.md#constructor)

### Properties

- [CombinedInputTypes](ue_ue.MaterialFunction.md#combinedinputtypes)
- [CombinedOutputTypes](ue_ue.MaterialFunction.md#combinedoutputtypes)
- [Description](ue_ue.MaterialFunction.md#description)
- [FunctionEditorComments](ue_ue.MaterialFunction.md#functioneditorcomments)
- [FunctionExpressions](ue_ue.MaterialFunction.md#functionexpressions)
- [LibraryCategories](ue_ue.MaterialFunction.md#librarycategories)
- [LibraryCategoriesText](ue_ue.MaterialFunction.md#librarycategoriestext)
- [MaterialFunctionUsage](ue_ue.MaterialFunction.md#materialfunctionusage)
- [ParentFunction](ue_ue.MaterialFunction.md#parentfunction)
- [PreviewMaterial](ue_ue.MaterialFunction.md#previewmaterial)
- [StateId](ue_ue.MaterialFunction.md#stateid)
- [ThumbnailInfo](ue_ue.MaterialFunction.md#thumbnailinfo)
- [\_\_tid\_MaterialFunctionInterface\_\_](ue_ue.MaterialFunction.md#__tid_materialfunctioninterface__)
- [\_\_tid\_MaterialFunction\_\_](ue_ue.MaterialFunction.md#__tid_materialfunction__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialFunction.md#__tid_object__)
- [bExposeToLibrary](ue_ue.MaterialFunction.md#bexposetolibrary)
- [bPrefixParameterNames](ue_ue.MaterialFunction.md#bprefixparameternames)
- [bReentrantFlag](ue_ue.MaterialFunction.md#breentrantflag)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialFunction.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialFunction.md#executeubergraph)
- [GetClass](ue_ue.MaterialFunction.md#getclass)
- [GetName](ue_ue.MaterialFunction.md#getname)
- [GetOuter](ue_ue.MaterialFunction.md#getouter)
- [GetWorld](ue_ue.MaterialFunction.md#getworld)
- [Find](ue_ue.MaterialFunction.md#find)
- [Load](ue_ue.MaterialFunction.md#load)
- [StaticClass](ue_ue.MaterialFunction.md#staticclass)

## Constructors

### constructor

• **new MaterialFunction**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[constructor](ue_ue.MaterialFunctionInterface.md#constructor)

## Properties

### CombinedInputTypes

• **CombinedInputTypes**: `number`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[CombinedInputTypes](ue_ue.MaterialFunctionInterface.md#combinedinputtypes)

___

### CombinedOutputTypes

• **CombinedOutputTypes**: `number`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[CombinedOutputTypes](ue_ue.MaterialFunctionInterface.md#combinedoutputtypes)

___

### Description

• **Description**: `string`

___

### FunctionEditorComments

• **FunctionEditorComments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpressionComment`](ue_ue.MaterialExpressionComment.md)\>

___

### FunctionExpressions

• **FunctionExpressions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpression`](ue_ue.MaterialExpression.md)\>

___

### LibraryCategories

• **LibraryCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### LibraryCategoriesText

• **LibraryCategoriesText**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### MaterialFunctionUsage

• **MaterialFunctionUsage**: [`EMaterialFunctionUsage`](../enums/ue_ue.EMaterialFunctionUsage.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[MaterialFunctionUsage](ue_ue.MaterialFunctionInterface.md#materialfunctionusage)

___

### ParentFunction

• **ParentFunction**: [`MaterialFunction`](ue_ue.MaterialFunction.md)

___

### PreviewMaterial

• **PreviewMaterial**: [`Material`](ue_ue.Material.md)

___

### StateId

• **StateId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[StateId](ue_ue.MaterialFunctionInterface.md#stateid)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[ThumbnailInfo](ue_ue.MaterialFunctionInterface.md#thumbnailinfo)

___

### \_\_tid\_MaterialFunctionInterface\_\_

• **\_\_tid\_MaterialFunctionInterface\_\_**: `boolean`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[__tid_MaterialFunctionInterface__](ue_ue.MaterialFunctionInterface.md#__tid_materialfunctioninterface__)

___

### \_\_tid\_MaterialFunction\_\_

• **\_\_tid\_MaterialFunction\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[__tid_Object__](ue_ue.MaterialFunctionInterface.md#__tid_object__)

___

### bExposeToLibrary

• **bExposeToLibrary**: `boolean`

___

### bPrefixParameterNames

• **bPrefixParameterNames**: `boolean`

___

### bReentrantFlag

• **bReentrantFlag**: `boolean`

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

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[CreateDefaultSubobject](ue_ue.MaterialFunctionInterface.md#createdefaultsubobject)

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

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[ExecuteUbergraph](ue_ue.MaterialFunctionInterface.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[GetClass](ue_ue.MaterialFunctionInterface.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[GetName](ue_ue.MaterialFunctionInterface.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[GetOuter](ue_ue.MaterialFunctionInterface.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[GetWorld](ue_ue.MaterialFunctionInterface.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Overrides

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[Find](ue_ue.MaterialFunctionInterface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Overrides

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[Load](ue_ue.MaterialFunctionInterface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[StaticClass](ue_ue.MaterialFunctionInterface.md#staticclass)
