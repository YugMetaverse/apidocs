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

#### Defined in

[ue/ue.d.ts:21944](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21944)

## Properties

### \_\_tid\_AssetTools\_\_

• **\_\_tid\_AssetTools\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21964)

___

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

#### Defined in

[ue/ue.d.ts:8142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8142)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

#### Defined in

[ue/ue.d.ts:21945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21945)

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

#### Defined in

[ue/ue.d.ts:21946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21946)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:21947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21947)

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

#### Defined in

[ue/ue.d.ts:21948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21948)

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

#### Defined in

[ue/ue.d.ts:21949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21949)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

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

#### Defined in

[ue/ue.d.ts:21950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21950)

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

#### Defined in

[ue/ue.d.ts:21951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21951)

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

#### Defined in

[ue/ue.d.ts:21952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21952)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### ImportAssetTasks

▸ **ImportAssetTasks**(`ImportTasks`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImportTasks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetImportTask`](ue_ue.AssetImportTask.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21955)

___

### ImportAssetsAutomated

▸ **ImportAssetsAutomated**(`ImportData`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ImportData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)\> |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:21953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21953)

___

### ImportAssetsWithDialog

▸ **ImportAssetsWithDialog**(`DestinationPath`): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `DestinationPath` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:21954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21954)

___

### OpenEditorForAssets

▸ **OpenEditorForAssets**(`Assets`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Assets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21956)

___

### RenameAssets

▸ **RenameAssets**(`AssetsAndNames`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetsAndNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetRenameData`](ue_ue.AssetRenameData.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:21957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21957)

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

#### Defined in

[ue/ue.d.ts:21958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21958)

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

#### Defined in

[ue/ue.d.ts:21959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21959)

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

#### Defined in

[ue/ue.d.ts:21961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21961)

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

#### Defined in

[ue/ue.d.ts:21962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21962)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)

#### Defined in

[ue/ue.d.ts:21960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21960)