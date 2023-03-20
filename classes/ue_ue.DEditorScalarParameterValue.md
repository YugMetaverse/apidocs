[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DEditorScalarParameterValue

# Class: DEditorScalarParameterValue

[ue/ue](../modules/ue_ue.md).DEditorScalarParameterValue

## Hierarchy

- [`DEditorParameterValue`](ue_ue.DEditorParameterValue.md)

  ↳ **`DEditorScalarParameterValue`**

## Table of contents

### Constructors

- [constructor](ue_ue.DEditorScalarParameterValue.md#constructor)

### Properties

- [AtlasData](ue_ue.DEditorScalarParameterValue.md#atlasdata)
- [ExpressionId](ue_ue.DEditorScalarParameterValue.md#expressionid)
- [ParameterInfo](ue_ue.DEditorScalarParameterValue.md#parameterinfo)
- [ParameterValue](ue_ue.DEditorScalarParameterValue.md#parametervalue)
- [SortPriority](ue_ue.DEditorScalarParameterValue.md#sortpriority)
- [\_\_tid\_DEditorParameterValue\_\_](ue_ue.DEditorScalarParameterValue.md#__tid_deditorparametervalue__)
- [\_\_tid\_DEditorScalarParameterValue\_\_](ue_ue.DEditorScalarParameterValue.md#__tid_deditorscalarparametervalue__)
- [\_\_tid\_Object\_\_](ue_ue.DEditorScalarParameterValue.md#__tid_object__)
- [bOverride](ue_ue.DEditorScalarParameterValue.md#boverride)

### Methods

- [CreateDefaultSubobject](ue_ue.DEditorScalarParameterValue.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DEditorScalarParameterValue.md#executeubergraph)
- [GetClass](ue_ue.DEditorScalarParameterValue.md#getclass)
- [GetName](ue_ue.DEditorScalarParameterValue.md#getname)
- [GetOuter](ue_ue.DEditorScalarParameterValue.md#getouter)
- [GetWorld](ue_ue.DEditorScalarParameterValue.md#getworld)
- [Find](ue_ue.DEditorScalarParameterValue.md#find)
- [Load](ue_ue.DEditorScalarParameterValue.md#load)
- [StaticClass](ue_ue.DEditorScalarParameterValue.md#staticclass)

## Constructors

### constructor

• **new DEditorScalarParameterValue**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[constructor](ue_ue.DEditorParameterValue.md#constructor)

## Properties

### AtlasData

• **AtlasData**: [`ScalarParameterAtlasData`](ue_ue.ScalarParameterAtlasData.md)

___

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

• **ParameterValue**: `number`

___

### SortPriority

• **SortPriority**: `number`

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[SortPriority](ue_ue.DEditorParameterValue.md#sortpriority)

___

### \_\_tid\_DEditorParameterValue\_\_

• **\_\_tid\_DEditorParameterValue\_\_**: `boolean`

#### Inherited from

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[__tid_DEditorParameterValue__](ue_ue.DEditorParameterValue.md#__tid_deditorparametervalue__)

___

### \_\_tid\_DEditorScalarParameterValue\_\_

• **\_\_tid\_DEditorScalarParameterValue\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DEditorScalarParameterValue`](ue_ue.DEditorScalarParameterValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DEditorScalarParameterValue`](ue_ue.DEditorScalarParameterValue.md)

#### Overrides

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[Find](ue_ue.DEditorParameterValue.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DEditorScalarParameterValue`](ue_ue.DEditorScalarParameterValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DEditorScalarParameterValue`](ue_ue.DEditorScalarParameterValue.md)

#### Overrides

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[Load](ue_ue.DEditorParameterValue.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DEditorParameterValue](ue_ue.DEditorParameterValue.md).[StaticClass](ue_ue.DEditorParameterValue.md#staticclass)
