[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialEditorPreviewParameters

# Class: MaterialEditorPreviewParameters

[ue/ue](../modules/ue_ue.md).MaterialEditorPreviewParameters

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MaterialEditorPreviewParameters`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialEditorPreviewParameters.md#constructor)

### Properties

- [OriginalFunction](ue_ue.MaterialEditorPreviewParameters.md#originalfunction)
- [OriginalMaterial](ue_ue.MaterialEditorPreviewParameters.md#originalmaterial)
- [ParameterGroups](ue_ue.MaterialEditorPreviewParameters.md#parametergroups)
- [PreviewMaterial](ue_ue.MaterialEditorPreviewParameters.md#previewmaterial)
- [\_\_tid\_MaterialEditorPreviewParameters\_\_](ue_ue.MaterialEditorPreviewParameters.md#__tid_materialeditorpreviewparameters__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialEditorPreviewParameters.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialEditorPreviewParameters.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialEditorPreviewParameters.md#executeubergraph)
- [GetClass](ue_ue.MaterialEditorPreviewParameters.md#getclass)
- [GetName](ue_ue.MaterialEditorPreviewParameters.md#getname)
- [GetOuter](ue_ue.MaterialEditorPreviewParameters.md#getouter)
- [GetWorld](ue_ue.MaterialEditorPreviewParameters.md#getworld)
- [Find](ue_ue.MaterialEditorPreviewParameters.md#find)
- [Load](ue_ue.MaterialEditorPreviewParameters.md#load)
- [StaticClass](ue_ue.MaterialEditorPreviewParameters.md#staticclass)

## Constructors

### constructor

• **new MaterialEditorPreviewParameters**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### OriginalFunction

• **OriginalFunction**: [`MaterialFunction`](ue_ue.MaterialFunction.md)

___

### OriginalMaterial

• **OriginalMaterial**: [`Material`](ue_ue.Material.md)

___

### ParameterGroups

• **ParameterGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorParameterGroup`](ue_ue.EditorParameterGroup.md)\>

___

### PreviewMaterial

• **PreviewMaterial**: [`Material`](ue_ue.Material.md)

___

### \_\_tid\_MaterialEditorPreviewParameters\_\_

• **\_\_tid\_MaterialEditorPreviewParameters\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialEditorPreviewParameters`](ue_ue.MaterialEditorPreviewParameters.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialEditorPreviewParameters`](ue_ue.MaterialEditorPreviewParameters.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialEditorPreviewParameters`](ue_ue.MaterialEditorPreviewParameters.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialEditorPreviewParameters`](ue_ue.MaterialEditorPreviewParameters.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
