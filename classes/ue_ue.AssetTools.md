[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetTools

# Class: AssetTools

[ue/ue](../modules/ue_ue.md).AssetTools

## Hierarchy

- [`Interface`](ue_ue.Interface.md)

  ↳ **`AssetTools`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetTools.md#constructor)

### Properties

- [\_\_tid\_AssetTools\_\_](ue_ue.AssetTools.md#__tid_assettools__)
- [\_\_tid\_Interface\_\_](ue_ue.AssetTools.md#__tid_interface__)
- [\_\_tid\_Object\_\_](ue_ue.AssetTools.md#__tid_object__)

### Methods

- [CreateAsset](ue_ue.AssetTools.md#createasset)
- [CreateAssetWithDialog](ue_ue.AssetTools.md#createassetwithdialog)
- [CreateDefaultSubobject](ue_ue.AssetTools.md#createdefaultsubobject)
- [CreateUniqueAssetName](ue_ue.AssetTools.md#createuniqueassetname)
- [DuplicateAsset](ue_ue.AssetTools.md#duplicateasset)
- [DuplicateAssetWithDialog](ue_ue.AssetTools.md#duplicateassetwithdialog)
- [ExecuteUbergraph](ue_ue.AssetTools.md#executeubergraph)
- [ExportAssets](ue_ue.AssetTools.md#exportassets)
- [ExportAssetsWithDialog](ue_ue.AssetTools.md#exportassetswithdialog)
- [FindSoftReferencesToObject](ue_ue.AssetTools.md#findsoftreferencestoobject)
- [GetClass](ue_ue.AssetTools.md#getclass)
- [GetName](ue_ue.AssetTools.md#getname)
- [GetOuter](ue_ue.AssetTools.md#getouter)
- [GetWorld](ue_ue.AssetTools.md#getworld)
- [ImportAssetTasks](ue_ue.AssetTools.md#importassettasks)
- [ImportAssetsAutomated](ue_ue.AssetTools.md#importassetsautomated)
- [ImportAssetsWithDialog](ue_ue.AssetTools.md#importassetswithdialog)
- [OpenEditorForAssets](ue_ue.AssetTools.md#openeditorforassets)
- [RenameAssets](ue_ue.AssetTools.md#renameassets)
- [RenameAssetsWithDialog](ue_ue.AssetTools.md#renameassetswithdialog)
- [RenameReferencingSoftObjectPaths](ue_ue.AssetTools.md#renamereferencingsoftobjectpaths)
- [Find](ue_ue.AssetTools.md#find)
- [Load](ue_ue.AssetTools.md#load)
- [StaticClass](ue_ue.AssetTools.md#staticclass)

## Constructors

### constructor

• **new AssetTools**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Interface](ue_ue.Interface.md).[constructor](ue_ue.Interface.md#constructor)

## Properties

### \_\_tid\_AssetTools\_\_

• **\_\_tid\_AssetTools\_\_**: `boolean`

___

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

## Methods

### CreateAsset

▸ **CreateAsset**(`AssetName`, `PackagePath`, `AssetClass`, `Factory`, `CallingContext?`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetName` | `string` |
| `PackagePath` | `string` |
| `AssetClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Factory` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Factory`](ue_ue.Factory.md)\> |
| `CallingContext?` | `string` |

#### Returns

[`Object`](ue_ue.Object.md)

___

### CreateAssetWithDialog

▸ **CreateAssetWithDialog**(`AssetName`, `PackagePath`, `AssetClass`, `Factory`, `CallingContext?`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetName` | `string` |
| `PackagePath` | `string` |
| `AssetClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Factory` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Factory`](ue_ue.Factory.md)\> |
| `CallingContext?` | `string` |

#### Returns

[`Object`](ue_ue.Object.md)

___

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

[Interface](ue_ue.Interface.md).[CreateDefaultSubobject](ue_ue.Interface.md#createdefaultsubobject)

___

### CreateUniqueAssetName

▸ **CreateUniqueAssetName**(`InBasePackageName`, `InSuffix`, `OutPackageName`, `OutAssetName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBasePackageName` | `string` |
| `InSuffix` | `string` |
| `OutPackageName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `OutAssetName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

___

### DuplicateAsset

▸ **DuplicateAsset**(`AssetName`, `PackagePath`, `OriginalObject`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetName` | `string` |
| `PackagePath` | `string` |
| `OriginalObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

___

### DuplicateAssetWithDialog

▸ **DuplicateAssetWithDialog**(`AssetName`, `PackagePath`, `OriginalObject`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetName` | `string` |
| `PackagePath` | `string` |
| `OriginalObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

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

[Interface](ue_ue.Interface.md).[ExecuteUbergraph](ue_ue.Interface.md#executeubergraph)

___

### ExportAssets

▸ **ExportAssets**(`AssetsToExport`, `ExportPath`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetsToExport` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `ExportPath` | `string` |

#### Returns

`void`

___

### ExportAssetsWithDialog

▸ **ExportAssetsWithDialog**(`AssetsToExport`, `bPromptForIndividualFilenames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetsToExport` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bPromptForIndividualFilenames` | `boolean` |

#### Returns

`void`

___

### FindSoftReferencesToObject

▸ **FindSoftReferencesToObject**(`TargetObject`, `ReferencingObjects`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetObject` | [`SoftObjectPath`](ue_ue.SoftObjectPath.md) |
| `ReferencingObjects` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>\> |

#### Returns

`void`

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

___

### ImportAssetTasks

▸ **ImportAssetTasks**(`ImportTasks`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImportTasks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetImportTask`](ue_ue.AssetImportTask.md)\> |

#### Returns

`void`

___

### ImportAssetsAutomated

▸ **ImportAssetsAutomated**(`ImportData`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImportData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### ImportAssetsWithDialog

▸ **ImportAssetsWithDialog**(`DestinationPath`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `DestinationPath` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### OpenEditorForAssets

▸ **OpenEditorForAssets**(`Assets`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Assets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### RenameAssets

▸ **RenameAssets**(`AssetsAndNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetsAndNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetRenameData`](ue_ue.AssetRenameData.md)\> |

#### Returns

`boolean`

___

### RenameAssetsWithDialog

▸ **RenameAssetsWithDialog**(`AssetsAndNames`, `bAutoCheckout?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetsAndNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetRenameData`](ue_ue.AssetRenameData.md)\> |
| `bAutoCheckout?` | `boolean` |

#### Returns

`void`

___

### RenameReferencingSoftObjectPaths

▸ **RenameReferencingSoftObjectPaths**(`PackagesToCheck`, `AssetRedirectorMap`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackagesToCheck` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Package`](ue_ue.Package.md)\> |
| `AssetRedirectorMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md), [`SoftObjectPath`](ue_ue.SoftObjectPath.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetTools`](ue_ue.AssetTools.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetTools`](ue_ue.AssetTools.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Find](ue_ue.Interface.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetTools`](ue_ue.AssetTools.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetTools`](ue_ue.AssetTools.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Load](ue_ue.Interface.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)
