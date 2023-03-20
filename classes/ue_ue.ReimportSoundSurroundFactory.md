[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReimportSoundSurroundFactory

# Class: ReimportSoundSurroundFactory

[ue/ue](../modules/ue_ue.md).ReimportSoundSurroundFactory

## Hierarchy

- [`SoundSurroundFactory`](ue_ue.SoundSurroundFactory.md)

  ↳ **`ReimportSoundSurroundFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReimportSoundSurroundFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.ReimportSoundSurroundFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.ReimportSoundSurroundFactory.md#automatedimportdata)
- [ContextClass](ue_ue.ReimportSoundSurroundFactory.md#contextclass)
- [CueVolume](ue_ue.ReimportSoundSurroundFactory.md#cuevolume)
- [Formats](ue_ue.ReimportSoundSurroundFactory.md#formats)
- [ImportPriority](ue_ue.ReimportSoundSurroundFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.ReimportSoundSurroundFactory.md#overwriteyesornotoallstate)
- [ReimportPaths](ue_ue.ReimportSoundSurroundFactory.md#reimportpaths)
- [SupportedClass](ue_ue.ReimportSoundSurroundFactory.md#supportedclass)
- [\_\_tid\_Factory\_\_](ue_ue.ReimportSoundSurroundFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.ReimportSoundSurroundFactory.md#__tid_object__)
- [\_\_tid\_ReimportSoundSurroundFactory\_\_](ue_ue.ReimportSoundSurroundFactory.md#__tid_reimportsoundsurroundfactory__)
- [\_\_tid\_SoundSurroundFactory\_\_](ue_ue.ReimportSoundSurroundFactory.md#__tid_soundsurroundfactory__)
- [bCreateNew](ue_ue.ReimportSoundSurroundFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.ReimportSoundSurroundFactory.md#beditafternew)
- [bEditorImport](ue_ue.ReimportSoundSurroundFactory.md#beditorimport)
- [bText](ue_ue.ReimportSoundSurroundFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.ReimportSoundSurroundFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReimportSoundSurroundFactory.md#executeubergraph)
- [GetClass](ue_ue.ReimportSoundSurroundFactory.md#getclass)
- [GetName](ue_ue.ReimportSoundSurroundFactory.md#getname)
- [GetOuter](ue_ue.ReimportSoundSurroundFactory.md#getouter)
- [GetWorld](ue_ue.ReimportSoundSurroundFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.ReimportSoundSurroundFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.ReimportSoundSurroundFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.ReimportSoundSurroundFactory.md#find)
- [Load](ue_ue.ReimportSoundSurroundFactory.md#load)
- [StaticClass](ue_ue.ReimportSoundSurroundFactory.md#staticclass)

## Constructors

### constructor

• **new ReimportSoundSurroundFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[constructor](ue_ue.SoundSurroundFactory.md#constructor)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[AssetImportTask](ue_ue.SoundSurroundFactory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[AutomatedImportData](ue_ue.SoundSurroundFactory.md#automatedimportdata)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ContextClass](ue_ue.SoundSurroundFactory.md#contextclass)

___

### CueVolume

• **CueVolume**: `number`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[CueVolume](ue_ue.SoundSurroundFactory.md#cuevolume)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[Formats](ue_ue.SoundSurroundFactory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ImportPriority](ue_ue.SoundSurroundFactory.md#importpriority)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[OverwriteYesOrNoToAllState](ue_ue.SoundSurroundFactory.md#overwriteyesornotoallstate)

___

### ReimportPaths

• **ReimportPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[SupportedClass](ue_ue.SoundSurroundFactory.md#supportedclass)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[__tid_Factory__](ue_ue.SoundSurroundFactory.md#__tid_factory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[__tid_Object__](ue_ue.SoundSurroundFactory.md#__tid_object__)

___

### \_\_tid\_ReimportSoundSurroundFactory\_\_

• **\_\_tid\_ReimportSoundSurroundFactory\_\_**: `boolean`

___

### \_\_tid\_SoundSurroundFactory\_\_

• **\_\_tid\_SoundSurroundFactory\_\_**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[__tid_SoundSurroundFactory__](ue_ue.SoundSurroundFactory.md#__tid_soundsurroundfactory__)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[bCreateNew](ue_ue.SoundSurroundFactory.md#bcreatenew)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[bEditAfterNew](ue_ue.SoundSurroundFactory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[bEditorImport](ue_ue.SoundSurroundFactory.md#beditorimport)

___

### bText

• **bText**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[bText](ue_ue.SoundSurroundFactory.md#btext)

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

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[CreateDefaultSubobject](ue_ue.SoundSurroundFactory.md#createdefaultsubobject)

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

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ExecuteUbergraph](ue_ue.SoundSurroundFactory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[GetClass](ue_ue.SoundSurroundFactory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[GetName](ue_ue.SoundSurroundFactory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[GetOuter](ue_ue.SoundSurroundFactory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[GetWorld](ue_ue.SoundSurroundFactory.md#getworld)

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

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ScriptFactoryCanImport](ue_ue.SoundSurroundFactory.md#scriptfactorycanimport)

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

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ScriptFactoryCreateFile](ue_ue.SoundSurroundFactory.md#scriptfactorycreatefile)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReimportSoundSurroundFactory`](ue_ue.ReimportSoundSurroundFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReimportSoundSurroundFactory`](ue_ue.ReimportSoundSurroundFactory.md)

#### Overrides

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[Find](ue_ue.SoundSurroundFactory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ReimportSoundSurroundFactory`](ue_ue.ReimportSoundSurroundFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReimportSoundSurroundFactory`](ue_ue.ReimportSoundSurroundFactory.md)

#### Overrides

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[Load](ue_ue.SoundSurroundFactory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[StaticClass](ue_ue.SoundSurroundFactory.md#staticclass)
