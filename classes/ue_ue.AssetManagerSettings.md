[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetManagerSettings

# Class: AssetManagerSettings

[ue/ue](../modules/ue_ue.md).AssetManagerSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`AssetManagerSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetManagerSettings.md#constructor)

### Properties

- [AssetPathRedirects](ue_ue.AssetManagerSettings.md#assetpathredirects)
- [CustomPrimaryAssetRules](ue_ue.AssetManagerSettings.md#customprimaryassetrules)
- [DirectoriesToExclude](ue_ue.AssetManagerSettings.md#directoriestoexclude)
- [MetaDataTagsForAssetRegistry](ue_ue.AssetManagerSettings.md#metadatatagsforassetregistry)
- [PrimaryAssetIdRedirects](ue_ue.AssetManagerSettings.md#primaryassetidredirects)
- [PrimaryAssetRules](ue_ue.AssetManagerSettings.md#primaryassetrules)
- [PrimaryAssetTypeRedirects](ue_ue.AssetManagerSettings.md#primaryassettyperedirects)
- [PrimaryAssetTypesToScan](ue_ue.AssetManagerSettings.md#primaryassettypestoscan)
- [\_\_tid\_AssetManagerSettings\_\_](ue_ue.AssetManagerSettings.md#__tid_assetmanagersettings__)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.AssetManagerSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.AssetManagerSettings.md#__tid_object__)
- [bOnlyCookProductionAssets](ue_ue.AssetManagerSettings.md#bonlycookproductionassets)
- [bShouldAcquireMissingChunksOnLoad](ue_ue.AssetManagerSettings.md#bshouldacquiremissingchunksonload)
- [bShouldGuessTypeAndNameInEditor](ue_ue.AssetManagerSettings.md#bshouldguesstypeandnameineditor)
- [bShouldManagerDetermineTypeAndName](ue_ue.AssetManagerSettings.md#bshouldmanagerdeterminetypeandname)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetManagerSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetManagerSettings.md#executeubergraph)
- [GetClass](ue_ue.AssetManagerSettings.md#getclass)
- [GetName](ue_ue.AssetManagerSettings.md#getname)
- [GetOuter](ue_ue.AssetManagerSettings.md#getouter)
- [GetWorld](ue_ue.AssetManagerSettings.md#getworld)
- [Find](ue_ue.AssetManagerSettings.md#find)
- [Load](ue_ue.AssetManagerSettings.md#load)
- [StaticClass](ue_ue.AssetManagerSettings.md#staticclass)

## Constructors

### constructor

• **new AssetManagerSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### AssetPathRedirects

• **AssetPathRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetManagerRedirect`](ue_ue.AssetManagerRedirect.md)\>

___

### CustomPrimaryAssetRules

• **CustomPrimaryAssetRules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimaryAssetRulesCustomOverride`](ue_ue.PrimaryAssetRulesCustomOverride.md)\>

___

### DirectoriesToExclude

• **DirectoriesToExclude**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### MetaDataTagsForAssetRegistry

• **MetaDataTagsForAssetRegistry**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

___

### PrimaryAssetIdRedirects

• **PrimaryAssetIdRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetManagerRedirect`](ue_ue.AssetManagerRedirect.md)\>

___

### PrimaryAssetRules

• **PrimaryAssetRules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimaryAssetRulesOverride`](ue_ue.PrimaryAssetRulesOverride.md)\>

___

### PrimaryAssetTypeRedirects

• **PrimaryAssetTypeRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetManagerRedirect`](ue_ue.AssetManagerRedirect.md)\>

___

### PrimaryAssetTypesToScan

• **PrimaryAssetTypesToScan**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimaryAssetTypeInfo`](ue_ue.PrimaryAssetTypeInfo.md)\>

___

### \_\_tid\_AssetManagerSettings\_\_

• **\_\_tid\_AssetManagerSettings\_\_**: `boolean`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### bOnlyCookProductionAssets

• **bOnlyCookProductionAssets**: `boolean`

___

### bShouldAcquireMissingChunksOnLoad

• **bShouldAcquireMissingChunksOnLoad**: `boolean`

___

### bShouldGuessTypeAndNameInEditor

• **bShouldGuessTypeAndNameInEditor**: `boolean`

___

### bShouldManagerDetermineTypeAndName

• **bShouldManagerDetermineTypeAndName**: `boolean`

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetManagerSettings`](ue_ue.AssetManagerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetManagerSettings`](ue_ue.AssetManagerSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetManagerSettings`](ue_ue.AssetManagerSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetManagerSettings`](ue_ue.AssetManagerSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
