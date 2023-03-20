[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LandscapeImportLayer

# Class: LandscapeImportLayer

[ue/ue](../modules/ue_ue.md).LandscapeImportLayer

## Hierarchy

- [`LandscapeImportLayerInfo`](ue_ue.LandscapeImportLayerInfo.md)

  ↳ **`LandscapeImportLayer`**

## Table of contents

### Constructors

- [constructor](ue_ue.LandscapeImportLayer.md#constructor)

### Properties

- [ErrorMessage](ue_ue.LandscapeImportLayer.md#errormessage)
- [ImportResult](ue_ue.LandscapeImportLayer.md#importresult)
- [LayerInfo](ue_ue.LandscapeImportLayer.md#layerinfo)
- [LayerName](ue_ue.LandscapeImportLayer.md#layername)
- [SourceFilePath](ue_ue.LandscapeImportLayer.md#sourcefilepath)
- [ThumbnailMIC](ue_ue.LandscapeImportLayer.md#thumbnailmic)
- [\_\_tid\_LandscapeImportLayer\_\_](ue_ue.LandscapeImportLayer.md#__tid_landscapeimportlayer__)

### Methods

- [StaticClass](ue_ue.LandscapeImportLayer.md#staticclass)
- [StaticStruct](ue_ue.LandscapeImportLayer.md#staticstruct)

## Constructors

### constructor

• **new LandscapeImportLayer**()

#### Overrides

[LandscapeImportLayerInfo](ue_ue.LandscapeImportLayerInfo.md).[constructor](ue_ue.LandscapeImportLayerInfo.md#constructor)

• **new LandscapeImportLayer**(`ThumbnailMIC`, `ImportResult`, `ErrorMessage`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ThumbnailMIC` | [`LandscapeMaterialInstanceConstant`](ue_ue.LandscapeMaterialInstanceConstant.md) |
| `ImportResult` | [`ELandscapeImportResult`](../enums/ue_ue.ELandscapeImportResult.md) |
| `ErrorMessage` | `string` |

#### Overrides

[LandscapeImportLayerInfo](ue_ue.LandscapeImportLayerInfo.md).[constructor](ue_ue.LandscapeImportLayerInfo.md#constructor)

## Properties

### ErrorMessage

• **ErrorMessage**: `string`

___

### ImportResult

• **ImportResult**: [`ELandscapeImportResult`](../enums/ue_ue.ELandscapeImportResult.md)

___

### LayerInfo

• **LayerInfo**: [`LandscapeLayerInfoObject`](ue_ue.LandscapeLayerInfoObject.md)

#### Inherited from

[LandscapeImportLayerInfo](ue_ue.LandscapeImportLayerInfo.md).[LayerInfo](ue_ue.LandscapeImportLayerInfo.md#layerinfo)

___

### LayerName

• **LayerName**: `string`

#### Inherited from

[LandscapeImportLayerInfo](ue_ue.LandscapeImportLayerInfo.md).[LayerName](ue_ue.LandscapeImportLayerInfo.md#layername)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[LandscapeImportLayerInfo](ue_ue.LandscapeImportLayerInfo.md).[SourceFilePath](ue_ue.LandscapeImportLayerInfo.md#sourcefilepath)

___

### ThumbnailMIC

• **ThumbnailMIC**: [`LandscapeMaterialInstanceConstant`](ue_ue.LandscapeMaterialInstanceConstant.md)

___

### \_\_tid\_LandscapeImportLayer\_\_

• `Private` **\_\_tid\_LandscapeImportLayer\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[LandscapeImportLayerInfo](ue_ue.LandscapeImportLayerInfo.md).[StaticClass](ue_ue.LandscapeImportLayerInfo.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[LandscapeImportLayerInfo](ue_ue.LandscapeImportLayerInfo.md).[StaticStruct](ue_ue.LandscapeImportLayerInfo.md#staticstruct)
