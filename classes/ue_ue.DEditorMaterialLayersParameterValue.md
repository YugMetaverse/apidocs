[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DEditorMaterialLayersParameterValue

# Class: DEditorMaterialLayersParameterValue

[ue/ue](../modules/ue_ue.md).DEditorMaterialLayersParameterValue

## Hierarchy

- [`DEditorParameterValue`](ue_ue.DEditorParameterValue.md)

  ↳ **`DEditorMaterialLayersParameterValue`**

## Table of contents

### Constructors

- [constructor](ue_ue.DEditorMaterialLayersParameterValue.md#constructor)

### Properties

- [ExpressionId](ue_ue.DEditorMaterialLayersParameterValue.md#expressionid)
- [ParameterInfo](ue_ue.DEditorMaterialLayersParameterValue.md#parameterinfo)
- [ParameterValue](ue_ue.DEditorMaterialLayersParameterValue.md#parametervalue)
- [SortPriority](ue_ue.DEditorMaterialLayersParameterValue.md#sortpriority)
- [\_\_tid\_DEditorMaterialLayersParameterValue\_\_](ue_ue.DEditorMaterialLayersParameterValue.md#__tid_deditormateriallayersparametervalue__)
- [\_\_tid\_DEditorParameterValue\_\_](ue_ue.DEditorMaterialLayersParameterValue.md#__tid_deditorparametervalue__)
- [\_\_tid\_Object\_\_](ue_ue.DEditorMaterialLayersParameterValue.md#__tid_object__)
- [bOverride](ue_ue.DEditorMaterialLayersParameterValue.md#boverride)

### Methods

- [CreateDefaultSubobject](ue_ue.DEditorMaterialLayersParameterValue.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DEditorMaterialLayersParameterValue.md#executeubergraph)
- [GetClass](ue_ue.DEditorMaterialLayersParameterValue.md#getclass)
- [GetName](ue_ue.DEditorMaterialLayersParameterValue.md#getname)
- [GetOuter](ue_ue.DEditorMaterialLayersParameterValue.md#getouter)
- [GetWorld](ue_ue.DEditorMaterialLayersParameterValue.md#getworld)
- [Find](ue_ue.DEditorMaterialLayersParameterValue.md#find)
- [Load](ue_ue.DEditorMaterialLayersParameterValue.md#load)
- [StaticClass](ue_ue.DEditorMaterialLayersParameterValue.md#staticclass)

## Constructors

### constructor

• **new DEditorMaterialLayersParameterValue**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[constructor](ue_ue.DEditorParameterValue.md#constructor)

## Properties

### ExpressionId

• **ExpressionId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[ExpressionId](ue_ue.DEditorParameterValue.md#expressionid)

___

### ParameterInfo

• **ParameterInfo**: [`MaterialParameterInfo`](ue_ue.MaterialParameterInfo.md)

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[ParameterInfo](ue_ue.DEditorParameterValue.md#parameterinfo)

___

### ParameterValue

• **ParameterValue**: [`MaterialLayersFunctions`](ue_ue.MaterialLayersFunctions.md)

___

### SortPriority

• **SortPriority**: `number`

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[SortPriority](ue_ue.DEditorParameterValue.md#sortpriority)

___

### \_\_tid\_DEditorMaterialLayersParameterValue\_\_

• **\_\_tid\_DEditorMaterialLayersParameterValue\_\_**: `boolean`

___

### \_\_tid\_DEditorParameterValue\_\_

• **\_\_tid\_DEditorParameterValue\_\_**: `boolean`

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[__tid_DEditorParameterValue__](ue_ue.DEditorParameterValue.md#__tid_deditorparametervalue__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[__tid_Object__](ue_ue.DEditorParameterValue.md#__tid_object__)

___

### bOverride

• **bOverride**: `boolean`

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[bOverride](ue_ue.DEditorParameterValue.md#boverride)

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

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[CreateDefaultSubobject](ue_ue.DEditorParameterValue.md#createdefaultsubobject)

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

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[ExecuteUbergraph](ue_ue.DEditorParameterValue.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[GetClass](ue_ue.DEditorParameterValue.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[GetName](ue_ue.DEditorParameterValue.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[GetOuter](ue_ue.DEditorParameterValue.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[GetWorld](ue_ue.DEditorParameterValue.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DEditorMaterialLayersParameterValue`](ue_ue.DEditorMaterialLayersParameterValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DEditorMaterialLayersParameterValue`](ue_ue.DEditorMaterialLayersParameterValue.md)

#### Overrides

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[Find](ue_ue.DEditorParameterValue.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DEditorMaterialLayersParameterValue`](ue_ue.DEditorMaterialLayersParameterValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DEditorMaterialLayersParameterValue`](ue_ue.DEditorMaterialLayersParameterValue.md)

#### Overrides

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[Load](ue_ue.DEditorParameterValue.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[StaticClass](ue_ue.DEditorParameterValue.md#staticclass)
