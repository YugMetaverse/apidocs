[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintMacroFactory

# Class: BlueprintMacroFactory

[ue/ue](../modules/ue_ue.md).BlueprintMacroFactory

## Hierarchy

- [`BlueprintFactory`](ue_ue.BlueprintFactory.md)

  ↳ **`BlueprintMacroFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintMacroFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.BlueprintMacroFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.BlueprintMacroFactory.md#automatedimportdata)
- [ContextClass](ue_ue.BlueprintMacroFactory.md#contextclass)
- [Formats](ue_ue.BlueprintMacroFactory.md#formats)
- [ImportPriority](ue_ue.BlueprintMacroFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.BlueprintMacroFactory.md#overwriteyesornotoallstate)
- [ParentClass](ue_ue.BlueprintMacroFactory.md#parentclass)
- [SupportedClass](ue_ue.BlueprintMacroFactory.md#supportedclass)
- [\_\_tid\_BlueprintFactory\_\_](ue_ue.BlueprintMacroFactory.md#__tid_blueprintfactory__)
- [\_\_tid\_BlueprintMacroFactory\_\_](ue_ue.BlueprintMacroFactory.md#__tid_blueprintmacrofactory__)
- [\_\_tid\_Factory\_\_](ue_ue.BlueprintMacroFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintMacroFactory.md#__tid_object__)
- [bCreateNew](ue_ue.BlueprintMacroFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.BlueprintMacroFactory.md#beditafternew)
- [bEditorImport](ue_ue.BlueprintMacroFactory.md#beditorimport)
- [bText](ue_ue.BlueprintMacroFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintMacroFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintMacroFactory.md#executeubergraph)
- [GetClass](ue_ue.BlueprintMacroFactory.md#getclass)
- [GetName](ue_ue.BlueprintMacroFactory.md#getname)
- [GetOuter](ue_ue.BlueprintMacroFactory.md#getouter)
- [GetWorld](ue_ue.BlueprintMacroFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.BlueprintMacroFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.BlueprintMacroFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.BlueprintMacroFactory.md#find)
- [Load](ue_ue.BlueprintMacroFactory.md#load)
- [StaticClass](ue_ue.BlueprintMacroFactory.md#staticclass)

## Constructors

### constructor

• **new BlueprintMacroFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFactory](ue_ue.BlueprintFactory.md).[constructor](ue_ue.BlueprintFactory.md#constructor)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[AssetImportTask](ue_ue.BlueprintFactory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[AutomatedImportData](ue_ue.BlueprintFactory.md#automatedimportdata)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ContextClass](ue_ue.BlueprintFactory.md#contextclass)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[Formats](ue_ue.BlueprintFactory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ImportPriority](ue_ue.BlueprintFactory.md#importpriority)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[OverwriteYesOrNoToAllState](ue_ue.BlueprintFactory.md#overwriteyesornotoallstate)

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ParentClass](ue_ue.BlueprintFactory.md#parentclass)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[SupportedClass](ue_ue.BlueprintFactory.md#supportedclass)

___

### \_\_tid\_BlueprintFactory\_\_

• **\_\_tid\_BlueprintFactory\_\_**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[__tid_BlueprintFactory__](ue_ue.BlueprintFactory.md#__tid_blueprintfactory__)

___

### \_\_tid\_BlueprintMacroFactory\_\_

• **\_\_tid\_BlueprintMacroFactory\_\_**: `boolean`

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[__tid_Factory__](ue_ue.BlueprintFactory.md#__tid_factory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[__tid_Object__](ue_ue.BlueprintFactory.md#__tid_object__)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bCreateNew](ue_ue.BlueprintFactory.md#bcreatenew)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bEditAfterNew](ue_ue.BlueprintFactory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bEditorImport](ue_ue.BlueprintFactory.md#beditorimport)

___

### bText

• **bText**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bText](ue_ue.BlueprintFactory.md#btext)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetClass](ue_ue.BlueprintFactory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetName](ue_ue.BlueprintFactory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetOuter](ue_ue.BlueprintFactory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetWorld](ue_ue.BlueprintFactory.md#getworld)

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

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintMacroFactory`](ue_ue.BlueprintMacroFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintMacroFactory`](ue_ue.BlueprintMacroFactory.md)

#### Overrides

[BlueprintFactory](ue_ue.BlueprintFactory.md).[Find](ue_ue.BlueprintFactory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintMacroFactory`](ue_ue.BlueprintMacroFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintMacroFactory`](ue_ue.BlueprintMacroFactory.md)

#### Overrides

[BlueprintFactory](ue_ue.BlueprintFactory.md).[Load](ue_ue.BlueprintFactory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFactory](ue_ue.BlueprintFactory.md).[StaticClass](ue_ue.BlueprintFactory.md#staticclass)
