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

#### Defined in

[ue/ue.d.ts:59347](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59347)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[AssetImportTask](ue_ue.SoundSurroundFactory.md#assetimporttask)

#### Defined in

[ue/ue.d.ts:15338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15338)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[AutomatedImportData](ue_ue.SoundSurroundFactory.md#automatedimportdata)

#### Defined in

[ue/ue.d.ts:15337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15337)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ContextClass](ue_ue.SoundSurroundFactory.md#contextclass)

#### Defined in

[ue/ue.d.ts:15331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15331)

___

### CueVolume

• **CueVolume**: `number`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[CueVolume](ue_ue.SoundSurroundFactory.md#cuevolume)

#### Defined in

[ue/ue.d.ts:59338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59338)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[Formats](ue_ue.SoundSurroundFactory.md#formats)

#### Defined in

[ue/ue.d.ts:15332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15332)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ImportPriority](ue_ue.SoundSurroundFactory.md#importpriority)

#### Defined in

[ue/ue.d.ts:15336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15336)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[OverwriteYesOrNoToAllState](ue_ue.SoundSurroundFactory.md#overwriteyesornotoallstate)

#### Defined in

[ue/ue.d.ts:15339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15339)

___

### ReimportPaths

• **ReimportPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:59348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59348)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[SupportedClass](ue_ue.SoundSurroundFactory.md#supportedclass)

#### Defined in

[ue/ue.d.ts:15330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15330)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[__tid_Factory__](ue_ue.SoundSurroundFactory.md#__tid_factory__)

#### Defined in

[ue/ue.d.ts:15346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15346)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[__tid_Object__](ue_ue.SoundSurroundFactory.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ReimportSoundSurroundFactory\_\_

• **\_\_tid\_ReimportSoundSurroundFactory\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59353](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59353)

___

### \_\_tid\_SoundSurroundFactory\_\_

• **\_\_tid\_SoundSurroundFactory\_\_**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[__tid_SoundSurroundFactory__](ue_ue.SoundSurroundFactory.md#__tid_soundsurroundfactory__)

#### Defined in

[ue/ue.d.ts:59343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59343)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[bCreateNew](ue_ue.SoundSurroundFactory.md#bcreatenew)

#### Defined in

[ue/ue.d.ts:15329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15329)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[bEditAfterNew](ue_ue.SoundSurroundFactory.md#beditafternew)

#### Defined in

[ue/ue.d.ts:15333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15333)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[bEditorImport](ue_ue.SoundSurroundFactory.md#beditorimport)

#### Defined in

[ue/ue.d.ts:15334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15334)

___

### bText

• **bText**: `boolean`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[bText](ue_ue.SoundSurroundFactory.md#btext)

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

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[CreateDefaultSubobject](ue_ue.SoundSurroundFactory.md#createdefaultsubobject)

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

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ExecuteUbergraph](ue_ue.SoundSurroundFactory.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[GetClass](ue_ue.SoundSurroundFactory.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[GetName](ue_ue.SoundSurroundFactory.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[GetOuter](ue_ue.SoundSurroundFactory.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[GetWorld](ue_ue.SoundSurroundFactory.md#getworld)

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

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ScriptFactoryCanImport](ue_ue.SoundSurroundFactory.md#scriptfactorycanimport)

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

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[ScriptFactoryCreateFile](ue_ue.SoundSurroundFactory.md#scriptfactorycreatefile)

#### Defined in

[ue/ue.d.ts:15341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15341)

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

#### Defined in

[ue/ue.d.ts:59350](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59350)

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

#### Defined in

[ue/ue.d.ts:59351](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59351)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundSurroundFactory](ue_ue.SoundSurroundFactory.md).[StaticClass](ue_ue.SoundSurroundFactory.md#staticclass)

#### Defined in

[ue/ue.d.ts:59349](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59349)
