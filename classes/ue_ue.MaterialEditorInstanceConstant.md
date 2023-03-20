[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialEditorInstanceConstant

# Class: MaterialEditorInstanceConstant

[ue/ue](../modules/ue_ue.md).MaterialEditorInstanceConstant

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MaterialEditorInstanceConstant`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialEditorInstanceConstant.md#constructor)

### Properties

- [BasePropertyOverrides](ue_ue.MaterialEditorInstanceConstant.md#basepropertyoverrides)
- [LightmassSettings](ue_ue.MaterialEditorInstanceConstant.md#lightmasssettings)
- [ParameterGroups](ue_ue.MaterialEditorInstanceConstant.md#parametergroups)
- [Parent](ue_ue.MaterialEditorInstanceConstant.md#parent)
- [PhysMaterial](ue_ue.MaterialEditorInstanceConstant.md#physmaterial)
- [RefractionDepthBias](ue_ue.MaterialEditorInstanceConstant.md#refractiondepthbias)
- [SourceFunction](ue_ue.MaterialEditorInstanceConstant.md#sourcefunction)
- [SourceInstance](ue_ue.MaterialEditorInstanceConstant.md#sourceinstance)
- [StoredBlendPreviews](ue_ue.MaterialEditorInstanceConstant.md#storedblendpreviews)
- [StoredLayerPreviews](ue_ue.MaterialEditorInstanceConstant.md#storedlayerpreviews)
- [SubsurfaceProfile](ue_ue.MaterialEditorInstanceConstant.md#subsurfaceprofile)
- [VisibleExpressions](ue_ue.MaterialEditorInstanceConstant.md#visibleexpressions)
- [\_\_tid\_MaterialEditorInstanceConstant\_\_](ue_ue.MaterialEditorInstanceConstant.md#__tid_materialeditorinstanceconstant__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialEditorInstanceConstant.md#__tid_object__)
- [bIsFunctionInstanceDirty](ue_ue.MaterialEditorInstanceConstant.md#bisfunctioninstancedirty)
- [bIsFunctionPreviewMaterial](ue_ue.MaterialEditorInstanceConstant.md#bisfunctionpreviewmaterial)
- [bOverrideBaseProperties](ue_ue.MaterialEditorInstanceConstant.md#boverridebaseproperties)
- [bOverrideSubsurfaceProfile](ue_ue.MaterialEditorInstanceConstant.md#boverridesubsurfaceprofile)
- [bUseOldStyleMICEditorGroups](ue_ue.MaterialEditorInstanceConstant.md#buseoldstylemiceditorgroups)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialEditorInstanceConstant.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialEditorInstanceConstant.md#executeubergraph)
- [GetClass](ue_ue.MaterialEditorInstanceConstant.md#getclass)
- [GetName](ue_ue.MaterialEditorInstanceConstant.md#getname)
- [GetOuter](ue_ue.MaterialEditorInstanceConstant.md#getouter)
- [GetWorld](ue_ue.MaterialEditorInstanceConstant.md#getworld)
- [Find](ue_ue.MaterialEditorInstanceConstant.md#find)
- [Load](ue_ue.MaterialEditorInstanceConstant.md#load)
- [StaticClass](ue_ue.MaterialEditorInstanceConstant.md#staticclass)

## Constructors

### constructor

• **new MaterialEditorInstanceConstant**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:47402](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47402)

## Properties

### BasePropertyOverrides

• **BasePropertyOverrides**: [`MaterialInstanceBasePropertyOverrides`](ue_ue.MaterialInstanceBasePropertyOverrides.md)

#### Defined in

[ue/ue.d.ts:47412](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47412)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassParameterizedMaterialSettings`](ue_ue.LightmassParameterizedMaterialSettings.md)

#### Defined in

[ue/ue.d.ts:47416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47416)

___

### ParameterGroups

• **ParameterGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorParameterGroup`](ue_ue.EditorParameterGroup.md)\>

#### Defined in

[ue/ue.d.ts:47405](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47405)

___

### Parent

• **Parent**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:47404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47404)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Defined in

[ue/ue.d.ts:47403](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47403)

___

### RefractionDepthBias

• **RefractionDepthBias**: `number`

#### Defined in

[ue/ue.d.ts:47406](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47406)

___

### SourceFunction

• **SourceFunction**: [`MaterialFunctionInstance`](ue_ue.MaterialFunctionInstance.md)

#### Defined in

[ue/ue.d.ts:47414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47414)

___

### SourceInstance

• **SourceInstance**: [`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)

#### Defined in

[ue/ue.d.ts:47413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47413)

___

### StoredBlendPreviews

• **StoredBlendPreviews**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\>

#### Defined in

[ue/ue.d.ts:47419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47419)

___

### StoredLayerPreviews

• **StoredLayerPreviews**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\>

#### Defined in

[ue/ue.d.ts:47418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47418)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

#### Defined in

[ue/ue.d.ts:47407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47407)

___

### VisibleExpressions

• **VisibleExpressions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialParameterInfo`](ue_ue.MaterialParameterInfo.md)\>

#### Defined in

[ue/ue.d.ts:47415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47415)

___

### \_\_tid\_MaterialEditorInstanceConstant\_\_

• **\_\_tid\_MaterialEditorInstanceConstant\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:47424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47424)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIsFunctionInstanceDirty

• **bIsFunctionInstanceDirty**: `boolean`

#### Defined in

[ue/ue.d.ts:47411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47411)

___

### bIsFunctionPreviewMaterial

• **bIsFunctionPreviewMaterial**: `boolean`

#### Defined in

[ue/ue.d.ts:47410](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47410)

___

### bOverrideBaseProperties

• **bOverrideBaseProperties**: `boolean`

#### Defined in

[ue/ue.d.ts:47409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47409)

___

### bOverrideSubsurfaceProfile

• **bOverrideSubsurfaceProfile**: `boolean`

#### Defined in

[ue/ue.d.ts:47408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47408)

___

### bUseOldStyleMICEditorGroups

• **bUseOldStyleMICEditorGroups**: `boolean`

#### Defined in

[ue/ue.d.ts:47417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47417)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialEditorInstanceConstant`](ue_ue.MaterialEditorInstanceConstant.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialEditorInstanceConstant`](ue_ue.MaterialEditorInstanceConstant.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:47421](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47421)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialEditorInstanceConstant`](ue_ue.MaterialEditorInstanceConstant.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialEditorInstanceConstant`](ue_ue.MaterialEditorInstanceConstant.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:47422](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47422)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:47420](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47420)
