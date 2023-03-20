[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundSurroundFactory

# Class: SoundSurroundFactory

[ue/ue](../modules/ue_ue.md).SoundSurroundFactory

## Hierarchy

- [`Factory`](ue_ue.Factory.md)

  ↳ **`SoundSurroundFactory`**

  ↳↳ [`ReimportSoundSurroundFactory`](ue_ue.ReimportSoundSurroundFactory.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SoundSurroundFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.SoundSurroundFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.SoundSurroundFactory.md#automatedimportdata)
- [ContextClass](ue_ue.SoundSurroundFactory.md#contextclass)
- [CueVolume](ue_ue.SoundSurroundFactory.md#cuevolume)
- [Formats](ue_ue.SoundSurroundFactory.md#formats)
- [ImportPriority](ue_ue.SoundSurroundFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.SoundSurroundFactory.md#overwriteyesornotoallstate)
- [SupportedClass](ue_ue.SoundSurroundFactory.md#supportedclass)
- [\_\_tid\_Factory\_\_](ue_ue.SoundSurroundFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.SoundSurroundFactory.md#__tid_object__)
- [\_\_tid\_SoundSurroundFactory\_\_](ue_ue.SoundSurroundFactory.md#__tid_soundsurroundfactory__)
- [bCreateNew](ue_ue.SoundSurroundFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.SoundSurroundFactory.md#beditafternew)
- [bEditorImport](ue_ue.SoundSurroundFactory.md#beditorimport)
- [bText](ue_ue.SoundSurroundFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundSurroundFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundSurroundFactory.md#executeubergraph)
- [GetClass](ue_ue.SoundSurroundFactory.md#getclass)
- [GetName](ue_ue.SoundSurroundFactory.md#getname)
- [GetOuter](ue_ue.SoundSurroundFactory.md#getouter)
- [GetWorld](ue_ue.SoundSurroundFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.SoundSurroundFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.SoundSurroundFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.SoundSurroundFactory.md#find)
- [Load](ue_ue.SoundSurroundFactory.md#load)
- [StaticClass](ue_ue.SoundSurroundFactory.md#staticclass)

## Constructors

### constructor

• **new SoundSurroundFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[ContextClass](ue_ue.Factory.md#contextclass)

___

### CueVolume

• **CueVolume**: `number`

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

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[SupportedClass](ue_ue.Factory.md#supportedclass)

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

### \_\_tid\_SoundSurroundFactory\_\_

• **\_\_tid\_SoundSurroundFactory\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundSurroundFactory`](ue_ue.SoundSurroundFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundSurroundFactory`](ue_ue.SoundSurroundFactory.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Find](ue_ue.Factory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundSurroundFactory`](ue_ue.SoundSurroundFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundSurroundFactory`](ue_ue.SoundSurroundFactory.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Load](ue_ue.Factory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Factory](ue_ue.Factory.md).[StaticClass](ue_ue.Factory.md#staticclass)
