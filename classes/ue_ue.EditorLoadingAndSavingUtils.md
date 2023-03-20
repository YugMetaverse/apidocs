[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorLoadingAndSavingUtils

# Class: EditorLoadingAndSavingUtils

[ue/ue](../modules/ue_ue.md).EditorLoadingAndSavingUtils

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditorLoadingAndSavingUtils`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorLoadingAndSavingUtils.md#constructor)

### Properties

- [\_\_tid\_EditorLoadingAndSavingUtils\_\_](ue_ue.EditorLoadingAndSavingUtils.md#__tid_editorloadingandsavingutils__)
- [\_\_tid\_Object\_\_](ue_ue.EditorLoadingAndSavingUtils.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorLoadingAndSavingUtils.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorLoadingAndSavingUtils.md#executeubergraph)
- [GetClass](ue_ue.EditorLoadingAndSavingUtils.md#getclass)
- [GetName](ue_ue.EditorLoadingAndSavingUtils.md#getname)
- [GetOuter](ue_ue.EditorLoadingAndSavingUtils.md#getouter)
- [GetWorld](ue_ue.EditorLoadingAndSavingUtils.md#getworld)
- [ExportScene](ue_ue.EditorLoadingAndSavingUtils.md#exportscene)
- [Find](ue_ue.EditorLoadingAndSavingUtils.md#find)
- [GetDirtyContentPackages](ue_ue.EditorLoadingAndSavingUtils.md#getdirtycontentpackages)
- [GetDirtyMapPackages](ue_ue.EditorLoadingAndSavingUtils.md#getdirtymappackages)
- [ImportScene](ue_ue.EditorLoadingAndSavingUtils.md#importscene)
- [Load](ue_ue.EditorLoadingAndSavingUtils.md#load)
- [LoadMap](ue_ue.EditorLoadingAndSavingUtils.md#loadmap)
- [LoadMapWithDialog](ue_ue.EditorLoadingAndSavingUtils.md#loadmapwithdialog)
- [NewBlankMap](ue_ue.EditorLoadingAndSavingUtils.md#newblankmap)
- [NewMapFromTemplate](ue_ue.EditorLoadingAndSavingUtils.md#newmapfromtemplate)
- [SaveCurrentLevel](ue_ue.EditorLoadingAndSavingUtils.md#savecurrentlevel)
- [SaveDirtyPackages](ue_ue.EditorLoadingAndSavingUtils.md#savedirtypackages)
- [SaveDirtyPackagesWithDialog](ue_ue.EditorLoadingAndSavingUtils.md#savedirtypackageswithdialog)
- [SaveMap](ue_ue.EditorLoadingAndSavingUtils.md#savemap)
- [SavePackages](ue_ue.EditorLoadingAndSavingUtils.md#savepackages)
- [SavePackagesWithDialog](ue_ue.EditorLoadingAndSavingUtils.md#savepackageswithdialog)
- [StaticClass](ue_ue.EditorLoadingAndSavingUtils.md#staticclass)
- [UnloadPackages](ue_ue.EditorLoadingAndSavingUtils.md#unloadpackages)

## Constructors

### constructor

• **new EditorLoadingAndSavingUtils**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:33061](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33061)

## Properties

### \_\_tid\_EditorLoadingAndSavingUtils\_\_

• **\_\_tid\_EditorLoadingAndSavingUtils\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33081)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### ExportScene

▸ `Static` **ExportScene**(`bExportSelectedActorsOnly`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bExportSelectedActorsOnly` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33062)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorLoadingAndSavingUtils`](ue_ue.EditorLoadingAndSavingUtils.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorLoadingAndSavingUtils`](ue_ue.EditorLoadingAndSavingUtils.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:33078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33078)

___

### GetDirtyContentPackages

▸ `Static` **GetDirtyContentPackages**(`OutDirtyPackages`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutDirtyPackages` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Package`](ue_ue.Package.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33063)

___

### GetDirtyMapPackages

▸ `Static` **GetDirtyMapPackages**(`OutDirtyPackages`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutDirtyPackages` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Package`](ue_ue.Package.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33064)

___

### ImportScene

▸ `Static` **ImportScene**(`Filename`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Filename` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33065)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorLoadingAndSavingUtils`](ue_ue.EditorLoadingAndSavingUtils.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorLoadingAndSavingUtils`](ue_ue.EditorLoadingAndSavingUtils.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:33079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33079)

___

### LoadMap

▸ `Static` **LoadMap**(`Filename`): [`World`](ue_ue.World.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Filename` | `string` |

#### Returns

[`World`](ue_ue.World.md)

#### Defined in

[ue/ue.d.ts:33066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33066)

___

### LoadMapWithDialog

▸ `Static` **LoadMapWithDialog**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Defined in

[ue/ue.d.ts:33067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33067)

___

### NewBlankMap

▸ `Static` **NewBlankMap**(`bSaveExistingMap`): [`World`](ue_ue.World.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSaveExistingMap` | `boolean` |

#### Returns

[`World`](ue_ue.World.md)

#### Defined in

[ue/ue.d.ts:33068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33068)

___

### NewMapFromTemplate

▸ `Static` **NewMapFromTemplate**(`PathToTemplateLevel`, `bSaveExistingMap`): [`World`](ue_ue.World.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PathToTemplateLevel` | `string` |
| `bSaveExistingMap` | `boolean` |

#### Returns

[`World`](ue_ue.World.md)

#### Defined in

[ue/ue.d.ts:33069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33069)

___

### SaveCurrentLevel

▸ `Static` **SaveCurrentLevel**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:33070](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33070)

___

### SaveDirtyPackages

▸ `Static` **SaveDirtyPackages**(`bSaveMapPackages`, `bSaveContentPackages`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSaveMapPackages` | `boolean` |
| `bSaveContentPackages` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:33071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33071)

___

### SaveDirtyPackagesWithDialog

▸ `Static` **SaveDirtyPackagesWithDialog**(`bSaveMapPackages`, `bSaveContentPackages`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSaveMapPackages` | `boolean` |
| `bSaveContentPackages` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:33072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33072)

___

### SaveMap

▸ `Static` **SaveMap**(`World`, `AssetPath`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `World` | [`$Nullable`](../modules/puerts.md#$nullable)<[`World`](ue_ue.World.md)\> |
| `AssetPath` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:33073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33073)

___

### SavePackages

▸ `Static` **SavePackages**(`PackagesToSave`, `bOnlyDirty`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackagesToSave` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Package`](ue_ue.Package.md)\> |
| `bOnlyDirty` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:33074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33074)

___

### SavePackagesWithDialog

▸ `Static` **SavePackagesWithDialog**(`PackagesToSave`, `bOnlyDirty`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackagesToSave` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Package`](ue_ue.Package.md)\> |
| `bOnlyDirty` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:33075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33075)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:33077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33077)

___

### UnloadPackages

▸ `Static` **UnloadPackages**(`PackagesToUnload`, `bOutAnyPackagesUnloaded`, `OutErrorMessage`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PackagesToUnload` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Package`](ue_ue.Package.md)\> |
| `bOutAnyPackagesUnloaded` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `OutErrorMessage` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:33076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33076)
