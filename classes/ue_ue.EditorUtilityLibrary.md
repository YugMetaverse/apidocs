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

#### Defined in

[ue/ue.d.ts:33571](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33571)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_EditorUtilityLibrary\_\_

• **\_\_tid\_EditorUtilityLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33583)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetActorReference

▸ **GetActorReference**(`PathToActor`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToActor` | `string` |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:33572](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33572)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:33580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33580)

___

### GetSelectedAssetData

▸ `Static` **GetSelectedAssetData**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetData`](ue_ue.AssetData.md)\>

#### Defined in

[ue/ue.d.ts:33573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33573)

___

### GetSelectedAssets

▸ `Static` **GetSelectedAssets**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:33574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33574)

___

### GetSelectedBlueprintClasses

▸ `Static` **GetSelectedBlueprintClasses**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\>

#### Defined in

[ue/ue.d.ts:33575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33575)

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

#### Defined in

[ue/ue.d.ts:33576](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33576)

___

### GetSelectionSet

▸ `Static` **GetSelectionSet**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:33577](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33577)

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

#### Defined in

[ue/ue.d.ts:33581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33581)

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

#### Defined in

[ue/ue.d.ts:33578](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33578)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:33579](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33579)
