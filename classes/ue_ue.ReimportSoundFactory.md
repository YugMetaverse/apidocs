[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReimportSoundFactory

# Class: ReimportSoundFactory

[ue/ue](../modules/ue_ue.md).ReimportSoundFactory

## Hierarchy

- [`SoundFactory`](ue_ue.SoundFactory.md)

  ↳ **`ReimportSoundFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReimportSoundFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.ReimportSoundFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.ReimportSoundFactory.md#automatedimportdata)
- [ContextClass](ue_ue.ReimportSoundFactory.md#contextclass)
- [CuePackageSuffix](ue_ue.ReimportSoundFactory.md#cuepackagesuffix)
- [CueVolume](ue_ue.ReimportSoundFactory.md#cuevolume)
- [Formats](ue_ue.ReimportSoundFactory.md#formats)
- [ImportPriority](ue_ue.ReimportSoundFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.ReimportSoundFactory.md#overwriteyesornotoallstate)
- [SupportedClass](ue_ue.ReimportSoundFactory.md#supportedclass)
- [\_\_tid\_Factory\_\_](ue_ue.ReimportSoundFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.ReimportSoundFactory.md#__tid_object__)
- [\_\_tid\_ReimportSoundFactory\_\_](ue_ue.ReimportSoundFactory.md#__tid_reimportsoundfactory__)
- [\_\_tid\_SoundFactory\_\_](ue_ue.ReimportSoundFactory.md#__tid_soundfactory__)
- [bAutoCreateCue](ue_ue.ReimportSoundFactory.md#bautocreatecue)
- [bCreateNew](ue_ue.ReimportSoundFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.ReimportSoundFactory.md#beditafternew)
- [bEditorImport](ue_ue.ReimportSoundFactory.md#beditorimport)
- [bIncludeAttenuationNode](ue_ue.ReimportSoundFactory.md#bincludeattenuationnode)
- [bIncludeLoopingNode](ue_ue.ReimportSoundFactory.md#bincludeloopingnode)
- [bIncludeModulatorNode](ue_ue.ReimportSoundFactory.md#bincludemodulatornode)
- [bText](ue_ue.ReimportSoundFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.ReimportSoundFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReimportSoundFactory.md#executeubergraph)
- [GetClass](ue_ue.ReimportSoundFactory.md#getclass)
- [GetName](ue_ue.ReimportSoundFactory.md#getname)
- [GetOuter](ue_ue.ReimportSoundFactory.md#getouter)
- [GetWorld](ue_ue.ReimportSoundFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.ReimportSoundFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.ReimportSoundFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.ReimportSoundFactory.md#find)
- [Load](ue_ue.ReimportSoundFactory.md#load)
- [StaticClass](ue_ue.ReimportSoundFactory.md#staticclass)

## Constructors

### constructor

• **new ReimportSoundFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundFactory](ue_ue.SoundFactory.md).[constructor](ue_ue.SoundFactory.md#constructor)

#### Defined in

[ue/ue.d.ts:59328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59328)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[AssetImportTask](ue_ue.SoundFactory.md#assetimporttask)

#### Defined in

[ue/ue.d.ts:15338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15338)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[AutomatedImportData](ue_ue.SoundFactory.md#automatedimportdata)

#### Defined in

[ue/ue.d.ts:15337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15337)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[ContextClass](ue_ue.SoundFactory.md#contextclass)

#### Defined in

[ue/ue.d.ts:15331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15331)

___

### CuePackageSuffix

• **CuePackageSuffix**: `string`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[CuePackageSuffix](ue_ue.SoundFactory.md#cuepackagesuffix)

#### Defined in

[ue/ue.d.ts:59319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59319)

___

### CueVolume

• **CueVolume**: `number`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[CueVolume](ue_ue.SoundFactory.md#cuevolume)

#### Defined in

[ue/ue.d.ts:59318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59318)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[Formats](ue_ue.SoundFactory.md#formats)

#### Defined in

[ue/ue.d.ts:15332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15332)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[ImportPriority](ue_ue.SoundFactory.md#importpriority)

#### Defined in

[ue/ue.d.ts:15336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15336)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[OverwriteYesOrNoToAllState](ue_ue.SoundFactory.md#overwriteyesornotoallstate)

#### Defined in

[ue/ue.d.ts:15339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15339)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[SupportedClass](ue_ue.SoundFactory.md#supportedclass)

#### Defined in

[ue/ue.d.ts:15330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15330)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[__tid_Factory__](ue_ue.SoundFactory.md#__tid_factory__)

#### Defined in

[ue/ue.d.ts:15346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15346)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[__tid_Object__](ue_ue.SoundFactory.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ReimportSoundFactory\_\_

• **\_\_tid\_ReimportSoundFactory\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59333)

___

### \_\_tid\_SoundFactory\_\_

• **\_\_tid\_SoundFactory\_\_**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[__tid_SoundFactory__](ue_ue.SoundFactory.md#__tid_soundfactory__)

#### Defined in

[ue/ue.d.ts:59324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59324)

___

### bAutoCreateCue

• **bAutoCreateCue**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[bAutoCreateCue](ue_ue.SoundFactory.md#bautocreatecue)

#### Defined in

[ue/ue.d.ts:59314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59314)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[bCreateNew](ue_ue.SoundFactory.md#bcreatenew)

#### Defined in

[ue/ue.d.ts:15329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15329)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[bEditAfterNew](ue_ue.SoundFactory.md#beditafternew)

#### Defined in

[ue/ue.d.ts:15333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15333)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[bEditorImport](ue_ue.SoundFactory.md#beditorimport)

#### Defined in

[ue/ue.d.ts:15334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15334)

___

### bIncludeAttenuationNode

• **bIncludeAttenuationNode**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[bIncludeAttenuationNode](ue_ue.SoundFactory.md#bincludeattenuationnode)

#### Defined in

[ue/ue.d.ts:59315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59315)

___

### bIncludeLoopingNode

• **bIncludeLoopingNode**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[bIncludeLoopingNode](ue_ue.SoundFactory.md#bincludeloopingnode)

#### Defined in

[ue/ue.d.ts:59316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59316)

___

### bIncludeModulatorNode

• **bIncludeModulatorNode**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[bIncludeModulatorNode](ue_ue.SoundFactory.md#bincludemodulatornode)

#### Defined in

[ue/ue.d.ts:59317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59317)

___

### bText

• **bText**: `boolean`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[bText](ue_ue.SoundFactory.md#btext)

#### Defined in

[ue/ue.d.ts:15335](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15335)

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

[SoundFactory](ue_ue.SoundFactory.md).[CreateDefaultSubobject](ue_ue.SoundFactory.md#createdefaultsubobject)

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

[SoundFactory](ue_ue.SoundFactory.md).[ExecuteUbergraph](ue_ue.SoundFactory.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[GetClass](ue_ue.SoundFactory.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[GetName](ue_ue.SoundFactory.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[GetOuter](ue_ue.SoundFactory.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundFactory](ue_ue.SoundFactory.md).[GetWorld](ue_ue.SoundFactory.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

[SoundFactory](ue_ue.SoundFactory.md).[ScriptFactoryCanImport](ue_ue.SoundFactory.md#scriptfactorycanimport)

#### Defined in

[ue/ue.d.ts:15340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15340)

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

[SoundFactory](ue_ue.SoundFactory.md).[ScriptFactoryCreateFile](ue_ue.SoundFactory.md#scriptfactorycreatefile)

#### Defined in

[ue/ue.d.ts:15341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15341)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReimportSoundFactory`](ue_ue.ReimportSoundFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReimportSoundFactory`](ue_ue.ReimportSoundFactory.md)

#### Overrides

[SoundFactory](ue_ue.SoundFactory.md).[Find](ue_ue.SoundFactory.md#find)

#### Defined in

[ue/ue.d.ts:59330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59330)

___

### Load

▸ `Static` **Load**(`InName`): [`ReimportSoundFactory`](ue_ue.ReimportSoundFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReimportSoundFactory`](ue_ue.ReimportSoundFactory.md)

#### Overrides

[SoundFactory](ue_ue.SoundFactory.md).[Load](ue_ue.SoundFactory.md#load)

#### Defined in

[ue/ue.d.ts:59331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59331)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundFactory](ue_ue.SoundFactory.md).[StaticClass](ue_ue.SoundFactory.md#staticclass)

#### Defined in

[ue/ue.d.ts:59329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59329)
