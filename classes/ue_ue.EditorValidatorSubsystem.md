[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorValidatorSubsystem

# Class: EditorValidatorSubsystem

[ue/ue](../modules/ue_ue.md).EditorValidatorSubsystem

## Hierarchy

- [`EditorSubsystem`](ue_ue.EditorSubsystem.md)

  ↳ **`EditorValidatorSubsystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorValidatorSubsystem.md#constructor)

### Properties

- [ExcludedDirectories](ue_ue.EditorValidatorSubsystem.md#excludeddirectories)
- [Validators](ue_ue.EditorValidatorSubsystem.md#validators)
- [\_\_tid\_DynamicSubsystem\_\_](ue_ue.EditorValidatorSubsystem.md#__tid_dynamicsubsystem__)
- [\_\_tid\_EditorSubsystem\_\_](ue_ue.EditorValidatorSubsystem.md#__tid_editorsubsystem__)
- [\_\_tid\_EditorValidatorSubsystem\_\_](ue_ue.EditorValidatorSubsystem.md#__tid_editorvalidatorsubsystem__)
- [\_\_tid\_Object\_\_](ue_ue.EditorValidatorSubsystem.md#__tid_object__)
- [\_\_tid\_Subsystem\_\_](ue_ue.EditorValidatorSubsystem.md#__tid_subsystem__)
- [bAllowBlueprintValidators](ue_ue.EditorValidatorSubsystem.md#ballowblueprintvalidators)
- [bValidateAssetsWhileSavingForCook](ue_ue.EditorValidatorSubsystem.md#bvalidateassetswhilesavingforcook)
- [bValidateOnSave](ue_ue.EditorValidatorSubsystem.md#bvalidateonsave)

### Methods

- [AddValidator](ue_ue.EditorValidatorSubsystem.md#addvalidator)
- [CreateDefaultSubobject](ue_ue.EditorValidatorSubsystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorValidatorSubsystem.md#executeubergraph)
- [GetClass](ue_ue.EditorValidatorSubsystem.md#getclass)
- [GetName](ue_ue.EditorValidatorSubsystem.md#getname)
- [GetOuter](ue_ue.EditorValidatorSubsystem.md#getouter)
- [GetWorld](ue_ue.EditorValidatorSubsystem.md#getworld)
- [IsAssetValid](ue_ue.EditorValidatorSubsystem.md#isassetvalid)
- [IsObjectValid](ue_ue.EditorValidatorSubsystem.md#isobjectvalid)
- [ValidateAssets](ue_ue.EditorValidatorSubsystem.md#validateassets)
- [Find](ue_ue.EditorValidatorSubsystem.md#find)
- [Load](ue_ue.EditorValidatorSubsystem.md#load)
- [StaticClass](ue_ue.EditorValidatorSubsystem.md#staticclass)

## Constructors

### constructor

• **new EditorValidatorSubsystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[constructor](ue_ue.EditorSubsystem.md#constructor)

## Properties

### ExcludedDirectories

• **ExcludedDirectories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### Validators

• **Validators**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Class`](ue_ue.Class.md), [`EditorValidatorBase`](ue_ue.EditorValidatorBase.md)\>

___

### \_\_tid\_DynamicSubsystem\_\_

• **\_\_tid\_DynamicSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_DynamicSubsystem__](ue_ue.EditorSubsystem.md#__tid_dynamicsubsystem__)

___

### \_\_tid\_EditorSubsystem\_\_

• **\_\_tid\_EditorSubsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_EditorSubsystem__](ue_ue.EditorSubsystem.md#__tid_editorsubsystem__)

___

### \_\_tid\_EditorValidatorSubsystem\_\_

• **\_\_tid\_EditorValidatorSubsystem\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Object__](ue_ue.EditorSubsystem.md#__tid_object__)

___

### \_\_tid\_Subsystem\_\_

• **\_\_tid\_Subsystem\_\_**: `boolean`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[__tid_Subsystem__](ue_ue.EditorSubsystem.md#__tid_subsystem__)

___

### bAllowBlueprintValidators

• **bAllowBlueprintValidators**: `boolean`

___

### bValidateAssetsWhileSavingForCook

• **bValidateAssetsWhileSavingForCook**: `boolean`

___

### bValidateOnSave

• **bValidateOnSave**: `boolean`

## Methods

### AddValidator

▸ **AddValidator**(`InValidator`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValidator` | [`$Nullable`](../modules/puerts.md#$nullable)<[`EditorValidatorBase`](ue_ue.EditorValidatorBase.md)\> |

#### Returns

`void`

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

[EditorSubsystem](ue_ue.EditorSubsystem.md).[CreateDefaultSubobject](ue_ue.EditorSubsystem.md#createdefaultsubobject)

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

[EditorSubsystem](ue_ue.EditorSubsystem.md).[ExecuteUbergraph](ue_ue.EditorSubsystem.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetClass](ue_ue.EditorSubsystem.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetName](ue_ue.EditorSubsystem.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetOuter](ue_ue.EditorSubsystem.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorSubsystem](ue_ue.EditorSubsystem.md).[GetWorld](ue_ue.EditorSubsystem.md#getworld)

___

### IsAssetValid

▸ **IsAssetValid**(`AssetData`, `ValidationErrors`): [`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`AssetData`](ue_ue.AssetData.md)\> |
| `ValidationErrors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

[`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

___

### IsObjectValid

▸ **IsObjectValid**(`InObject`, `ValidationErrors`): [`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ValidationErrors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

[`EDataValidationResult`](../enums/ue_ue.EDataValidationResult.md)

___

### ValidateAssets

▸ **ValidateAssets**(`AssetDataList`, `bSkipExcludedDirectories?`, `bShowIfNoFailures?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AssetDataList` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\> |
| `bSkipExcludedDirectories?` | `boolean` |
| `bShowIfNoFailures?` | `boolean` |

#### Returns

`number`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorValidatorSubsystem`](ue_ue.EditorValidatorSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorValidatorSubsystem`](ue_ue.EditorValidatorSubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Find](ue_ue.EditorSubsystem.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorValidatorSubsystem`](ue_ue.EditorValidatorSubsystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorValidatorSubsystem`](ue_ue.EditorValidatorSubsystem.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[Load](ue_ue.EditorSubsystem.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorSubsystem](ue_ue.EditorSubsystem.md).[StaticClass](ue_ue.EditorSubsystem.md#staticclass)
