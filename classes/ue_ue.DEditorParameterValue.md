[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DEditorParameterValue

# Class: DEditorParameterValue

[ue/ue](../modules/ue_ue.md).DEditorParameterValue

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DEditorParameterValue`**

  ↳↳ [`DEditorFontParameterValue`](ue_ue.DEditorFontParameterValue.md)

  ↳↳ [`DEditorMaterialLayersParameterValue`](ue_ue.DEditorMaterialLayersParameterValue.md)

  ↳↳ [`DEditorRuntimeVirtualTextureParameterValue`](ue_ue.DEditorRuntimeVirtualTextureParameterValue.md)

  ↳↳ [`DEditorScalarParameterValue`](ue_ue.DEditorScalarParameterValue.md)

  ↳↳ [`DEditorStaticComponentMaskParameterValue`](ue_ue.DEditorStaticComponentMaskParameterValue.md)

  ↳↳ [`DEditorStaticSwitchParameterValue`](ue_ue.DEditorStaticSwitchParameterValue.md)

  ↳↳ [`DEditorTextureParameterValue`](ue_ue.DEditorTextureParameterValue.md)

  ↳↳ [`DEditorVectorParameterValue`](ue_ue.DEditorVectorParameterValue.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DEditorParameterValue.md#constructor)

### Properties

- [ExpressionId](ue_ue.DEditorParameterValue.md#expressionid)
- [ParameterInfo](ue_ue.DEditorParameterValue.md#parameterinfo)
- [SortPriority](ue_ue.DEditorParameterValue.md#sortpriority)
- [\_\_tid\_DEditorParameterValue\_\_](ue_ue.DEditorParameterValue.md#__tid_deditorparametervalue__)
- [\_\_tid\_Object\_\_](ue_ue.DEditorParameterValue.md#__tid_object__)
- [bOverride](ue_ue.DEditorParameterValue.md#boverride)

### Methods

- [CreateDefaultSubobject](ue_ue.DEditorParameterValue.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DEditorParameterValue.md#executeubergraph)
- [GetClass](ue_ue.DEditorParameterValue.md#getclass)
- [GetName](ue_ue.DEditorParameterValue.md#getname)
- [GetOuter](ue_ue.DEditorParameterValue.md#getouter)
- [GetWorld](ue_ue.DEditorParameterValue.md#getworld)
- [Find](ue_ue.DEditorParameterValue.md#find)
- [Load](ue_ue.DEditorParameterValue.md#load)
- [StaticClass](ue_ue.DEditorParameterValue.md#staticclass)

## Constructors

### constructor

• **new DEditorParameterValue**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:30373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30373)

## Properties

### ExpressionId

• **ExpressionId**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:30376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30376)

___

### ParameterInfo

• **ParameterInfo**: [`MaterialParameterInfo`](ue_ue.MaterialParameterInfo.md)

#### Defined in

[ue/ue.d.ts:30375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30375)

___

### SortPriority

• **SortPriority**: `number`

#### Defined in

[ue/ue.d.ts:30377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30377)

___

### \_\_tid\_DEditorParameterValue\_\_

• **\_\_tid\_DEditorParameterValue\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30382)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bOverride

• **bOverride**: `boolean`

#### Defined in

[ue/ue.d.ts:30374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30374)

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

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DEditorParameterValue`](ue_ue.DEditorParameterValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DEditorParameterValue`](ue_ue.DEditorParameterValue.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:30379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30379)

___

### Load

▸ `Static` **Load**(`InName`): [`DEditorParameterValue`](ue_ue.DEditorParameterValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DEditorParameterValue`](ue_ue.DEditorParameterValue.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:30380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30380)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:30378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30378)
