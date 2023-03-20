[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorUtilityWidgetBlueprintFactory

# Class: EditorUtilityWidgetBlueprintFactory

[ue/ue](../modules/ue_ue.md).EditorUtilityWidgetBlueprintFactory

## Hierarchy

- [`Factory`](ue_ue.Factory.md)

  ↳ **`EditorUtilityWidgetBlueprintFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorUtilityWidgetBlueprintFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.EditorUtilityWidgetBlueprintFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.EditorUtilityWidgetBlueprintFactory.md#automatedimportdata)
- [BlueprintType](ue_ue.EditorUtilityWidgetBlueprintFactory.md#blueprinttype)
- [ContextClass](ue_ue.EditorUtilityWidgetBlueprintFactory.md#contextclass)
- [Formats](ue_ue.EditorUtilityWidgetBlueprintFactory.md#formats)
- [ImportPriority](ue_ue.EditorUtilityWidgetBlueprintFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.EditorUtilityWidgetBlueprintFactory.md#overwriteyesornotoallstate)
- [ParentClass](ue_ue.EditorUtilityWidgetBlueprintFactory.md#parentclass)
- [SupportedClass](ue_ue.EditorUtilityWidgetBlueprintFactory.md#supportedclass)
- [\_\_tid\_EditorUtilityWidgetBlueprintFactory\_\_](ue_ue.EditorUtilityWidgetBlueprintFactory.md#__tid_editorutilitywidgetblueprintfactory__)
- [\_\_tid\_Factory\_\_](ue_ue.EditorUtilityWidgetBlueprintFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.EditorUtilityWidgetBlueprintFactory.md#__tid_object__)
- [bCreateNew](ue_ue.EditorUtilityWidgetBlueprintFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.EditorUtilityWidgetBlueprintFactory.md#beditafternew)
- [bEditorImport](ue_ue.EditorUtilityWidgetBlueprintFactory.md#beditorimport)
- [bText](ue_ue.EditorUtilityWidgetBlueprintFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorUtilityWidgetBlueprintFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorUtilityWidgetBlueprintFactory.md#executeubergraph)
- [GetClass](ue_ue.EditorUtilityWidgetBlueprintFactory.md#getclass)
- [GetName](ue_ue.EditorUtilityWidgetBlueprintFactory.md#getname)
- [GetOuter](ue_ue.EditorUtilityWidgetBlueprintFactory.md#getouter)
- [GetWorld](ue_ue.EditorUtilityWidgetBlueprintFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.EditorUtilityWidgetBlueprintFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.EditorUtilityWidgetBlueprintFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.EditorUtilityWidgetBlueprintFactory.md#find)
- [Load](ue_ue.EditorUtilityWidgetBlueprintFactory.md#load)
- [StaticClass](ue_ue.EditorUtilityWidgetBlueprintFactory.md#staticclass)

## Constructors

### constructor

• **new EditorUtilityWidgetBlueprintFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Factory](ue_ue.Factory.md).[constructor](ue_ue.Factory.md#constructor)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[AssetImportTask](ue_ue.Factory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[AutomatedImportData](ue_ue.Factory.md#automatedimportdata)

___

### BlueprintType

• **BlueprintType**: [`EBlueprintType`](../enums/ue_ue.EBlueprintType.md)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[ContextClass](ue_ue.Factory.md#contextclass)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Factory](ue_ue.Factory.md).[Formats](ue_ue.Factory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[Factory](ue_ue.Factory.md).[ImportPriority](ue_ue.Factory.md#importpriority)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[Factory](ue_ue.Factory.md).[OverwriteYesOrNoToAllState](ue_ue.Factory.md#overwriteyesornotoallstate)

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[SupportedClass](ue_ue.Factory.md#supportedclass)

___

### \_\_tid\_EditorUtilityWidgetBlueprintFactory\_\_

• **\_\_tid\_EditorUtilityWidgetBlueprintFactory\_\_**: `boolean`

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[__tid_Factory__](ue_ue.Factory.md#__tid_factory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[__tid_Object__](ue_ue.Factory.md#__tid_object__)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bCreateNew](ue_ue.Factory.md#bcreatenew)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bEditAfterNew](ue_ue.Factory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bEditorImport](ue_ue.Factory.md#beditorimport)

___

### bText

• **bText**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bText](ue_ue.Factory.md#btext)

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

[Factory](ue_ue.Factory.md).[CreateDefaultSubobject](ue_ue.Factory.md#createdefaultsubobject)

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

[Factory](ue_ue.Factory.md).[ExecuteUbergraph](ue_ue.Factory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetClass](ue_ue.Factory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Factory](ue_ue.Factory.md).[GetName](ue_ue.Factory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetOuter](ue_ue.Factory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetWorld](ue_ue.Factory.md#getworld)

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

[Factory](ue_ue.Factory.md).[ScriptFactoryCanImport](ue_ue.Factory.md#scriptfactorycanimport)

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

[Factory](ue_ue.Factory.md).[ScriptFactoryCreateFile](ue_ue.Factory.md#scriptfactorycreatefile)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorUtilityWidgetBlueprintFactory`](ue_ue.EditorUtilityWidgetBlueprintFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorUtilityWidgetBlueprintFactory`](ue_ue.EditorUtilityWidgetBlueprintFactory.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Find](ue_ue.Factory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorUtilityWidgetBlueprintFactory`](ue_ue.EditorUtilityWidgetBlueprintFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorUtilityWidgetBlueprintFactory`](ue_ue.EditorUtilityWidgetBlueprintFactory.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Load](ue_ue.Factory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Factory](ue_ue.Factory.md).[StaticClass](ue_ue.Factory.md#staticclass)
