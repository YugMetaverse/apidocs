[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintFunctionLibraryFactory

# Class: BlueprintFunctionLibraryFactory

[ue/ue](../modules/ue_ue.md).BlueprintFunctionLibraryFactory

## Hierarchy

- [`BlueprintFactory`](ue_ue.BlueprintFactory.md)

  ↳ **`BlueprintFunctionLibraryFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintFunctionLibraryFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.BlueprintFunctionLibraryFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.BlueprintFunctionLibraryFactory.md#automatedimportdata)
- [ContextClass](ue_ue.BlueprintFunctionLibraryFactory.md#contextclass)
- [Formats](ue_ue.BlueprintFunctionLibraryFactory.md#formats)
- [ImportPriority](ue_ue.BlueprintFunctionLibraryFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.BlueprintFunctionLibraryFactory.md#overwriteyesornotoallstate)
- [ParentClass](ue_ue.BlueprintFunctionLibraryFactory.md#parentclass)
- [SupportedClass](ue_ue.BlueprintFunctionLibraryFactory.md#supportedclass)
- [\_\_tid\_BlueprintFactory\_\_](ue_ue.BlueprintFunctionLibraryFactory.md#__tid_blueprintfactory__)
- [\_\_tid\_BlueprintFunctionLibraryFactory\_\_](ue_ue.BlueprintFunctionLibraryFactory.md#__tid_blueprintfunctionlibraryfactory__)
- [\_\_tid\_Factory\_\_](ue_ue.BlueprintFunctionLibraryFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintFunctionLibraryFactory.md#__tid_object__)
- [bCreateNew](ue_ue.BlueprintFunctionLibraryFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.BlueprintFunctionLibraryFactory.md#beditafternew)
- [bEditorImport](ue_ue.BlueprintFunctionLibraryFactory.md#beditorimport)
- [bText](ue_ue.BlueprintFunctionLibraryFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintFunctionLibraryFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintFunctionLibraryFactory.md#executeubergraph)
- [GetClass](ue_ue.BlueprintFunctionLibraryFactory.md#getclass)
- [GetName](ue_ue.BlueprintFunctionLibraryFactory.md#getname)
- [GetOuter](ue_ue.BlueprintFunctionLibraryFactory.md#getouter)
- [GetWorld](ue_ue.BlueprintFunctionLibraryFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.BlueprintFunctionLibraryFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.BlueprintFunctionLibraryFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.BlueprintFunctionLibraryFactory.md#find)
- [Load](ue_ue.BlueprintFunctionLibraryFactory.md#load)
- [StaticClass](ue_ue.BlueprintFunctionLibraryFactory.md#staticclass)

## Constructors

### constructor

• **new BlueprintFunctionLibraryFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFactory](ue_ue.BlueprintFactory.md).[constructor](ue_ue.BlueprintFactory.md#constructor)

#### Defined in

[ue/ue.d.ts:24061](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24061)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[AssetImportTask](ue_ue.BlueprintFactory.md#assetimporttask)

#### Defined in

[ue/ue.d.ts:15338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15338)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[AutomatedImportData](ue_ue.BlueprintFactory.md#automatedimportdata)

#### Defined in

[ue/ue.d.ts:15337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15337)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ContextClass](ue_ue.BlueprintFactory.md#contextclass)

#### Defined in

[ue/ue.d.ts:15331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15331)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[Formats](ue_ue.BlueprintFactory.md#formats)

#### Defined in

[ue/ue.d.ts:15332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15332)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ImportPriority](ue_ue.BlueprintFactory.md#importpriority)

#### Defined in

[ue/ue.d.ts:15336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15336)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[OverwriteYesOrNoToAllState](ue_ue.BlueprintFactory.md#overwriteyesornotoallstate)

#### Defined in

[ue/ue.d.ts:15339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15339)

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ParentClass](ue_ue.BlueprintFactory.md#parentclass)

#### Defined in

[ue/ue.d.ts:24052](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24052)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[SupportedClass](ue_ue.BlueprintFactory.md#supportedclass)

#### Defined in

[ue/ue.d.ts:15330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15330)

___

### \_\_tid\_BlueprintFactory\_\_

• **\_\_tid\_BlueprintFactory\_\_**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[__tid_BlueprintFactory__](ue_ue.BlueprintFactory.md#__tid_blueprintfactory__)

#### Defined in

[ue/ue.d.ts:24057](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24057)

___

### \_\_tid\_BlueprintFunctionLibraryFactory\_\_

• **\_\_tid\_BlueprintFunctionLibraryFactory\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:24066](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24066)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[__tid_Factory__](ue_ue.BlueprintFactory.md#__tid_factory__)

#### Defined in

[ue/ue.d.ts:15346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15346)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[__tid_Object__](ue_ue.BlueprintFactory.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bCreateNew](ue_ue.BlueprintFactory.md#bcreatenew)

#### Defined in

[ue/ue.d.ts:15329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15329)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bEditAfterNew](ue_ue.BlueprintFactory.md#beditafternew)

#### Defined in

[ue/ue.d.ts:15333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15333)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bEditorImport](ue_ue.BlueprintFactory.md#beditorimport)

#### Defined in

[ue/ue.d.ts:15334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15334)

___

### bText

• **bText**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bText](ue_ue.BlueprintFactory.md#btext)

#### Defined in

[ue/ue.d.ts:15335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15335)

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

[BlueprintFactory](ue_ue.BlueprintFactory.md).[CreateDefaultSubobject](ue_ue.BlueprintFactory.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ExecuteUbergraph](ue_ue.BlueprintFactory.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetClass](ue_ue.BlueprintFactory.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetName](ue_ue.BlueprintFactory.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetOuter](ue_ue.BlueprintFactory.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetWorld](ue_ue.BlueprintFactory.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### ScriptFactoryCanImport

▸ **ScriptFactoryCanImport**(`Filename`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Filename` | `string` |

#### Returns

`boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ScriptFactoryCanImport](ue_ue.BlueprintFactory.md#scriptfactorycanimport)

#### Defined in

[ue/ue.d.ts:15340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15340)

___

### ScriptFactoryCreateFile

▸ **ScriptFactoryCreateFile**(`InTask`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTask` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AssetImportTask`](ue_ue.AssetImportTask.md)\> |

#### Returns

`boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ScriptFactoryCreateFile](ue_ue.BlueprintFactory.md#scriptfactorycreatefile)

#### Defined in

[ue/ue.d.ts:15341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15341)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintFunctionLibraryFactory`](ue_ue.BlueprintFunctionLibraryFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintFunctionLibraryFactory`](ue_ue.BlueprintFunctionLibraryFactory.md)

#### Overrides

[BlueprintFactory](ue_ue.BlueprintFactory.md).[Find](ue_ue.BlueprintFactory.md#find)

#### Defined in

[ue/ue.d.ts:24063](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24063)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintFunctionLibraryFactory`](ue_ue.BlueprintFunctionLibraryFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintFunctionLibraryFactory`](ue_ue.BlueprintFunctionLibraryFactory.md)

#### Overrides

[BlueprintFactory](ue_ue.BlueprintFactory.md).[Load](ue_ue.BlueprintFactory.md#load)

#### Defined in

[ue/ue.d.ts:24064](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24064)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFactory](ue_ue.BlueprintFactory.md).[StaticClass](ue_ue.BlueprintFactory.md#staticclass)

#### Defined in

[ue/ue.d.ts:24062](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24062)
