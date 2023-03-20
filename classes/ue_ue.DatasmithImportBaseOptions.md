[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithImportBaseOptions

# Class: DatasmithImportBaseOptions

[ue/ue](../modules/ue_ue.md).DatasmithImportBaseOptions

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithImportBaseOptions.md#constructor)

### Properties

- [AssetOptions](ue_ue.DatasmithImportBaseOptions.md#assetoptions)
- [SceneHandling](ue_ue.DatasmithImportBaseOptions.md#scenehandling)
- [StaticMeshOptions](ue_ue.DatasmithImportBaseOptions.md#staticmeshoptions)
- [\_\_tid\_DatasmithImportBaseOptions\_\_](ue_ue.DatasmithImportBaseOptions.md#__tid_datasmithimportbaseoptions__)
- [bIncludeAnimation](ue_ue.DatasmithImportBaseOptions.md#bincludeanimation)
- [bIncludeCamera](ue_ue.DatasmithImportBaseOptions.md#bincludecamera)
- [bIncludeGeometry](ue_ue.DatasmithImportBaseOptions.md#bincludegeometry)
- [bIncludeLight](ue_ue.DatasmithImportBaseOptions.md#bincludelight)
- [bIncludeMaterial](ue_ue.DatasmithImportBaseOptions.md#bincludematerial)

### Methods

- [StaticClass](ue_ue.DatasmithImportBaseOptions.md#staticclass)
- [StaticStruct](ue_ue.DatasmithImportBaseOptions.md#staticstruct)

## Constructors

### constructor

• **new DatasmithImportBaseOptions**()

• **new DatasmithImportBaseOptions**(`SceneHandling`, `bIncludeGeometry`, `bIncludeMaterial`, `bIncludeLight`, `bIncludeCamera`, `bIncludeAnimation`, `AssetOptions`, `StaticMeshOptions`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SceneHandling` | [`EDatasmithImportScene`](../enums/ue_ue.EDatasmithImportScene.md) |
| `bIncludeGeometry` | `boolean` |
| `bIncludeMaterial` | `boolean` |
| `bIncludeLight` | `boolean` |
| `bIncludeCamera` | `boolean` |
| `bIncludeAnimation` | `boolean` |
| `AssetOptions` | [`DatasmithAssetImportOptions`](ue_ue.DatasmithAssetImportOptions.md) |
| `StaticMeshOptions` | [`DatasmithStaticMeshImportOptions`](ue_ue.DatasmithStaticMeshImportOptions.md) |

## Properties

### AssetOptions

• **AssetOptions**: [`DatasmithAssetImportOptions`](ue_ue.DatasmithAssetImportOptions.md)

___

### SceneHandling

• **SceneHandling**: [`EDatasmithImportScene`](../enums/ue_ue.EDatasmithImportScene.md)

___

### StaticMeshOptions

• **StaticMeshOptions**: [`DatasmithStaticMeshImportOptions`](ue_ue.DatasmithStaticMeshImportOptions.md)

___

### \_\_tid\_DatasmithImportBaseOptions\_\_

• `Private` **\_\_tid\_DatasmithImportBaseOptions\_\_**: `boolean`

___

### bIncludeAnimation

• **bIncludeAnimation**: `boolean`

___

### bIncludeCamera

• **bIncludeCamera**: `boolean`

___

### bIncludeGeometry

• **bIncludeGeometry**: `boolean`

___

### bIncludeLight

• **bIncludeLight**: `boolean`

___

### bIncludeMaterial

• **bIncludeMaterial**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
