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

#### Defined in

[ue/ue.d.ts:24169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24169)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[AssetImportTask](ue_ue.BlueprintFactory.md#assetimporttask)

#### Defined in

[ue/ue.d.ts:15338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15338)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[AutomatedImportData](ue_ue.BlueprintFactory.md#automatedimportdata)

#### Defined in

[ue/ue.d.ts:15337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15337)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ContextClass](ue_ue.BlueprintFactory.md#contextclass)

#### Defined in

[ue/ue.d.ts:15331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15331)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[Formats](ue_ue.BlueprintFactory.md#formats)

#### Defined in

[ue/ue.d.ts:15332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15332)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ImportPriority](ue_ue.BlueprintFactory.md#importpriority)

#### Defined in

[ue/ue.d.ts:15336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15336)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[OverwriteYesOrNoToAllState](ue_ue.BlueprintFactory.md#overwriteyesornotoallstate)

#### Defined in

[ue/ue.d.ts:15339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15339)

___

### ParentClass

• **ParentClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ParentClass](ue_ue.BlueprintFactory.md#parentclass)

#### Defined in

[ue/ue.d.ts:24052](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24052)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[SupportedClass](ue_ue.BlueprintFactory.md#supportedclass)

#### Defined in

[ue/ue.d.ts:15330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15330)

___

### \_\_tid\_BlueprintFactory\_\_

• **\_\_tid\_BlueprintFactory\_\_**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[__tid_BlueprintFactory__](ue_ue.BlueprintFactory.md#__tid_blueprintfactory__)

#### Defined in

[ue/ue.d.ts:24057](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24057)

___

### \_\_tid\_BlueprintMacroFactory\_\_

• **\_\_tid\_BlueprintMacroFactory\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:24174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24174)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[__tid_Factory__](ue_ue.BlueprintFactory.md#__tid_factory__)

#### Defined in

[ue/ue.d.ts:15346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15346)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[__tid_Object__](ue_ue.BlueprintFactory.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bCreateNew](ue_ue.BlueprintFactory.md#bcreatenew)

#### Defined in

[ue/ue.d.ts:15329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15329)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bEditAfterNew](ue_ue.BlueprintFactory.md#beditafternew)

#### Defined in

[ue/ue.d.ts:15333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15333)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bEditorImport](ue_ue.BlueprintFactory.md#beditorimport)

#### Defined in

[ue/ue.d.ts:15334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15334)

___

### bText

• **bText**: `boolean`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[bText](ue_ue.BlueprintFactory.md#btext)

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

[BlueprintFactory](ue_ue.BlueprintFactory.md).[CreateDefaultSubobject](ue_ue.BlueprintFactory.md#createdefaultsubobject)

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

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ExecuteUbergraph](ue_ue.BlueprintFactory.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetClass](ue_ue.BlueprintFactory.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetName](ue_ue.BlueprintFactory.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetOuter](ue_ue.BlueprintFactory.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFactory](ue_ue.BlueprintFactory.md).[GetWorld](ue_ue.BlueprintFactory.md#getworld)

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

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ScriptFactoryCanImport](ue_ue.BlueprintFactory.md#scriptfactorycanimport)

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

[BlueprintFactory](ue_ue.BlueprintFactory.md).[ScriptFactoryCreateFile](ue_ue.BlueprintFactory.md#scriptfactorycreatefile)

#### Defined in

[ue/ue.d.ts:15341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15341)

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

#### Defined in

[ue/ue.d.ts:24171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24171)

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

#### Defined in

[ue/ue.d.ts:24172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24172)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFactory](ue_ue.BlueprintFactory.md).[StaticClass](ue_ue.BlueprintFactory.md#staticclass)

#### Defined in

[ue/ue.d.ts:24170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24170)
