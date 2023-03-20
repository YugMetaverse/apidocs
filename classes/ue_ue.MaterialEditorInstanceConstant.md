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

## Properties

### BasePropertyOverrides

• **BasePropertyOverrides**: [`MaterialInstanceBasePropertyOverrides`](ue_ue.MaterialInstanceBasePropertyOverrides.md)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassParameterizedMaterialSettings`](ue_ue.LightmassParameterizedMaterialSettings.md)

___

### ParameterGroups

• **ParameterGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorParameterGroup`](ue_ue.EditorParameterGroup.md)\>

___

### Parent

• **Parent**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

___

### RefractionDepthBias

• **RefractionDepthBias**: `number`

___

### SourceFunction

• **SourceFunction**: [`MaterialFunctionInstance`](ue_ue.MaterialFunctionInstance.md)

___

### SourceInstance

• **SourceInstance**: [`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)

___

### StoredBlendPreviews

• **StoredBlendPreviews**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\>

___

### StoredLayerPreviews

• **StoredLayerPreviews**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)\>

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

___

### VisibleExpressions

• **VisibleExpressions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialParameterInfo`](ue_ue.MaterialParameterInfo.md)\>

___

### \_\_tid\_MaterialEditorInstanceConstant\_\_

• **\_\_tid\_MaterialEditorInstanceConstant\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bIsFunctionInstanceDirty

• **bIsFunctionInstanceDirty**: `boolean`

___

### bIsFunctionPreviewMaterial

• **bIsFunctionPreviewMaterial**: `boolean`

___

### bOverrideBaseProperties

• **bOverrideBaseProperties**: `boolean`

___

### bOverrideSubsurfaceProfile

• **bOverrideSubsurfaceProfile**: `boolean`

___

### bUseOldStyleMICEditorGroups

• **bUseOldStyleMICEditorGroups**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
