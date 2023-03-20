[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialFunctionInstance

# Class: MaterialFunctionInstance

[ue/ue](../modules/ue_ue.md).MaterialFunctionInstance

## Hierarchy

- [`MaterialFunctionInterface`](ue_ue.MaterialFunctionInterface.md)

  ↳ **`MaterialFunctionInstance`**

  ↳↳ [`MaterialFunctionMaterialLayerBlendInstance`](ue_ue.MaterialFunctionMaterialLayerBlendInstance.md)

  ↳↳ [`MaterialFunctionMaterialLayerInstance`](ue_ue.MaterialFunctionMaterialLayerInstance.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialFunctionInstance.md#constructor)

### Properties

- [Base](ue_ue.MaterialFunctionInstance.md#base)
- [CombinedInputTypes](ue_ue.MaterialFunctionInstance.md#combinedinputtypes)
- [CombinedOutputTypes](ue_ue.MaterialFunctionInstance.md#combinedoutputtypes)
- [FontParameterValues](ue_ue.MaterialFunctionInstance.md#fontparametervalues)
- [MaterialFunctionUsage](ue_ue.MaterialFunctionInstance.md#materialfunctionusage)
- [Parent](ue_ue.MaterialFunctionInstance.md#parent)
- [PreviewMaterial](ue_ue.MaterialFunctionInstance.md#previewmaterial)
- [RuntimeVirtualTextureParameterValues](ue_ue.MaterialFunctionInstance.md#runtimevirtualtextureparametervalues)
- [ScalarParameterValues](ue_ue.MaterialFunctionInstance.md#scalarparametervalues)
- [StateId](ue_ue.MaterialFunctionInstance.md#stateid)
- [StaticComponentMaskParameterValues](ue_ue.MaterialFunctionInstance.md#staticcomponentmaskparametervalues)
- [StaticSwitchParameterValues](ue_ue.MaterialFunctionInstance.md#staticswitchparametervalues)
- [TextureParameterValues](ue_ue.MaterialFunctionInstance.md#textureparametervalues)
- [ThumbnailInfo](ue_ue.MaterialFunctionInstance.md#thumbnailinfo)
- [VectorParameterValues](ue_ue.MaterialFunctionInstance.md#vectorparametervalues)
- [\_\_tid\_MaterialFunctionInstance\_\_](ue_ue.MaterialFunctionInstance.md#__tid_materialfunctioninstance__)
- [\_\_tid\_MaterialFunctionInterface\_\_](ue_ue.MaterialFunctionInstance.md#__tid_materialfunctioninterface__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialFunctionInstance.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialFunctionInstance.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialFunctionInstance.md#executeubergraph)
- [GetClass](ue_ue.MaterialFunctionInstance.md#getclass)
- [GetName](ue_ue.MaterialFunctionInstance.md#getname)
- [GetOuter](ue_ue.MaterialFunctionInstance.md#getouter)
- [GetWorld](ue_ue.MaterialFunctionInstance.md#getworld)
- [Find](ue_ue.MaterialFunctionInstance.md#find)
- [Load](ue_ue.MaterialFunctionInstance.md#load)
- [StaticClass](ue_ue.MaterialFunctionInstance.md#staticclass)

## Constructors

### constructor

• **new MaterialFunctionInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[constructor](ue_ue.MaterialFunctionInterface.md#constructor)

#### Defined in

[ue/ue.d.ts:47332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47332)

## Properties

### Base

• **Base**: [`MaterialFunctionInterface`](ue_ue.MaterialFunctionInterface.md)

#### Defined in

[ue/ue.d.ts:47334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47334)

___

### CombinedInputTypes

• **CombinedInputTypes**: `number`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[CombinedInputTypes](ue_ue.MaterialFunctionInterface.md#combinedinputtypes)

#### Defined in

[ue/ue.d.ts:1095](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1095)

___

### CombinedOutputTypes

• **CombinedOutputTypes**: `number`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[CombinedOutputTypes](ue_ue.MaterialFunctionInterface.md#combinedoutputtypes)

#### Defined in

[ue/ue.d.ts:1096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1096)

___

### FontParameterValues

• **FontParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FontParameterValue`](ue_ue.FontParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:47338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47338)

___

### MaterialFunctionUsage

• **MaterialFunctionUsage**: [`EMaterialFunctionUsage`](../enums/ue_ue.EMaterialFunctionUsage.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[MaterialFunctionUsage](ue_ue.MaterialFunctionInterface.md#materialfunctionusage)

#### Defined in

[ue/ue.d.ts:1094](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1094)

___

### Parent

• **Parent**: [`MaterialFunctionInterface`](ue_ue.MaterialFunctionInterface.md)

#### Defined in

[ue/ue.d.ts:47333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47333)

___

### PreviewMaterial

• **PreviewMaterial**: [`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)

#### Defined in

[ue/ue.d.ts:47342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47342)

___

### RuntimeVirtualTextureParameterValues

• **RuntimeVirtualTextureParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTextureParameterValue`](ue_ue.RuntimeVirtualTextureParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:47341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47341)

___

### ScalarParameterValues

• **ScalarParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ScalarParameterValue`](ue_ue.ScalarParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:47335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47335)

___

### StateId

• **StateId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[StateId](ue_ue.MaterialFunctionInterface.md#stateid)

#### Defined in

[ue/ue.d.ts:1093](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1093)

___

### StaticComponentMaskParameterValues

• **StaticComponentMaskParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticComponentMaskParameter`](ue_ue.StaticComponentMaskParameter.md)\>

#### Defined in

[ue/ue.d.ts:47340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47340)

___

### StaticSwitchParameterValues

• **StaticSwitchParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticSwitchParameter`](ue_ue.StaticSwitchParameter.md)\>

#### Defined in

[ue/ue.d.ts:47339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47339)

___

### TextureParameterValues

• **TextureParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureParameterValue`](ue_ue.TextureParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:47337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47337)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[ThumbnailInfo](ue_ue.MaterialFunctionInterface.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:1097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1097)

___

### VectorParameterValues

• **VectorParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VectorParameterValue`](ue_ue.VectorParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:47336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47336)

___

### \_\_tid\_MaterialFunctionInstance\_\_

• **\_\_tid\_MaterialFunctionInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:47347](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47347)

___

### \_\_tid\_MaterialFunctionInterface\_\_

• **\_\_tid\_MaterialFunctionInterface\_\_**: `boolean`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[__tid_MaterialFunctionInterface__](ue_ue.MaterialFunctionInterface.md#__tid_materialfunctioninterface__)

#### Defined in

[ue/ue.d.ts:1102](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1102)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[__tid_Object__](ue_ue.MaterialFunctionInterface.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[GetClass](ue_ue.MaterialFunctionInterface.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[GetName](ue_ue.MaterialFunctionInterface.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[GetOuter](ue_ue.MaterialFunctionInterface.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[GetWorld](ue_ue.MaterialFunctionInterface.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialFunctionInstance`](ue_ue.MaterialFunctionInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialFunctionInstance`](ue_ue.MaterialFunctionInstance.md)

#### Overrides

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[Find](ue_ue.MaterialFunctionInterface.md#find)

#### Defined in

[ue/ue.d.ts:47344](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47344)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialFunctionInstance`](ue_ue.MaterialFunctionInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialFunctionInstance`](ue_ue.MaterialFunctionInstance.md)

#### Overrides

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[Load](ue_ue.MaterialFunctionInterface.md#load)

#### Defined in

[ue/ue.d.ts:47345](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47345)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialFunctionInterface](ue_ue.MaterialFunctionInterface.md).[StaticClass](ue_ue.MaterialFunctionInterface.md#staticclass)

#### Defined in

[ue/ue.d.ts:47343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47343)
