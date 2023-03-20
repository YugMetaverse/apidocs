[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / HierarchicalLODSettings

# Class: HierarchicalLODSettings

[ue/ue](../modules/ue_ue.md).HierarchicalLODSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`HierarchicalLODSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.HierarchicalLODSettings.md#constructor)

### Properties

- [BaseMaterial](ue_ue.HierarchicalLODSettings.md#basematerial)
- [DefaultSetup](ue_ue.HierarchicalLODSettings.md#defaultsetup)
- [DirectoriesForHLODCommandlet](ue_ue.HierarchicalLODSettings.md#directoriesforhlodcommandlet)
- [MapsToBuild](ue_ue.HierarchicalLODSettings.md#mapstobuild)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.HierarchicalLODSettings.md#__tid_developersettings__)
- [\_\_tid\_HierarchicalLODSettings\_\_](ue_ue.HierarchicalLODSettings.md#__tid_hierarchicallodsettings__)
- [\_\_tid\_Object\_\_](ue_ue.HierarchicalLODSettings.md#__tid_object__)
- [bDeleteHLODAssets](ue_ue.HierarchicalLODSettings.md#bdeletehlodassets)
- [bForceSettingsInAllMaps](ue_ue.HierarchicalLODSettings.md#bforcesettingsinallmaps)
- [bInvalidateHLODClusters](ue_ue.HierarchicalLODSettings.md#binvalidatehlodclusters)

### Methods

- [CreateDefaultSubobject](ue_ue.HierarchicalLODSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.HierarchicalLODSettings.md#executeubergraph)
- [GetClass](ue_ue.HierarchicalLODSettings.md#getclass)
- [GetName](ue_ue.HierarchicalLODSettings.md#getname)
- [GetOuter](ue_ue.HierarchicalLODSettings.md#getouter)
- [GetWorld](ue_ue.HierarchicalLODSettings.md#getworld)
- [Find](ue_ue.HierarchicalLODSettings.md#find)
- [Load](ue_ue.HierarchicalLODSettings.md#load)
- [StaticClass](ue_ue.HierarchicalLODSettings.md#staticclass)

## Constructors

### constructor

• **new HierarchicalLODSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### BaseMaterial

• **BaseMaterial**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

___

### DefaultSetup

• **DefaultSetup**: [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`HierarchicalLODSetup`](ue_ue.HierarchicalLODSetup.md)\>

___

### DirectoriesForHLODCommandlet

• **DirectoriesForHLODCommandlet**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### MapsToBuild

• **MapsToBuild**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FilePath`](ue_ue.FilePath.md)\>

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_HierarchicalLODSettings\_\_

• **\_\_tid\_HierarchicalLODSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### bDeleteHLODAssets

• **bDeleteHLODAssets**: `boolean`

___

### bForceSettingsInAllMaps

• **bForceSettingsInAllMaps**: `boolean`

___

### bInvalidateHLODClusters

• **bInvalidateHLODClusters**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`HierarchicalLODSettings`](ue_ue.HierarchicalLODSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`HierarchicalLODSettings`](ue_ue.HierarchicalLODSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`HierarchicalLODSettings`](ue_ue.HierarchicalLODSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`HierarchicalLODSettings`](ue_ue.HierarchicalLODSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
