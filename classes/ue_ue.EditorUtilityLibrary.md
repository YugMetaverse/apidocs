[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorUtilityLibrary

# Class: EditorUtilityLibrary

[ue/ue](../modules/ue_ue.md).EditorUtilityLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`EditorUtilityLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorUtilityLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.EditorUtilityLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_EditorUtilityLibrary\_\_](ue_ue.EditorUtilityLibrary.md#__tid_editorutilitylibrary__)
- [\_\_tid\_Object\_\_](ue_ue.EditorUtilityLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorUtilityLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorUtilityLibrary.md#executeubergraph)
- [GetActorReference](ue_ue.EditorUtilityLibrary.md#getactorreference)
- [GetClass](ue_ue.EditorUtilityLibrary.md#getclass)
- [GetName](ue_ue.EditorUtilityLibrary.md#getname)
- [GetOuter](ue_ue.EditorUtilityLibrary.md#getouter)
- [GetWorld](ue_ue.EditorUtilityLibrary.md#getworld)
- [Find](ue_ue.EditorUtilityLibrary.md#find)
- [GetSelectedAssetData](ue_ue.EditorUtilityLibrary.md#getselectedassetdata)
- [GetSelectedAssets](ue_ue.EditorUtilityLibrary.md#getselectedassets)
- [GetSelectedBlueprintClasses](ue_ue.EditorUtilityLibrary.md#getselectedblueprintclasses)
- [GetSelectionBounds](ue_ue.EditorUtilityLibrary.md#getselectionbounds)
- [GetSelectionSet](ue_ue.EditorUtilityLibrary.md#getselectionset)
- [Load](ue_ue.EditorUtilityLibrary.md#load)
- [RenameAsset](ue_ue.EditorUtilityLibrary.md#renameasset)
- [StaticClass](ue_ue.EditorUtilityLibrary.md#staticclass)

## Constructors

### constructor

• **new EditorUtilityLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_EditorUtilityLibrary\_\_

• **\_\_tid\_EditorUtilityLibrary\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetActorReference

▸ **GetActorReference**(`PathToActor`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToActor` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorUtilityLibrary`](ue_ue.EditorUtilityLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorUtilityLibrary`](ue_ue.EditorUtilityLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetSelectedAssetData

▸ `Static` **GetSelectedAssetData**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>

___

### GetSelectedAssets

▸ `Static` **GetSelectedAssets**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### GetSelectedBlueprintClasses

▸ `Static` **GetSelectedBlueprintClasses**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\>

___

### GetSelectionBounds

▸ `Static` **GetSelectionBounds**(`Origin`, `BoxExtent`, `SphereRadius`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Origin` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `BoxExtent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `SphereRadius` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### GetSelectionSet

▸ `Static` **GetSelectionSet**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### Load

▸ `Static` **Load**(`InName`): [`EditorUtilityLibrary`](ue_ue.EditorUtilityLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorUtilityLibrary`](ue_ue.EditorUtilityLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### RenameAsset

▸ `Static` **RenameAsset**(`Asset`, `NewName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Asset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `NewName` | `string` |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
