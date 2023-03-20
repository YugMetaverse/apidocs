[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ImportAssetsCommandlet

# Class: ImportAssetsCommandlet

[ue/ue](../modules/ue_ue.md).ImportAssetsCommandlet

## Hierarchy

- [`Commandlet`](ue_ue.Commandlet.md)

  ↳ **`ImportAssetsCommandlet`**

## Table of contents

### Constructors

- [constructor](ue_ue.ImportAssetsCommandlet.md#constructor)

### Properties

- [GlobalImportData](ue_ue.ImportAssetsCommandlet.md#globalimportdata)
- [HelpDescription](ue_ue.ImportAssetsCommandlet.md#helpdescription)
- [HelpParamDescriptions](ue_ue.ImportAssetsCommandlet.md#helpparamdescriptions)
- [HelpParamNames](ue_ue.ImportAssetsCommandlet.md#helpparamnames)
- [HelpUsage](ue_ue.ImportAssetsCommandlet.md#helpusage)
- [HelpWebLink](ue_ue.ImportAssetsCommandlet.md#helpweblink)
- [ImportDataList](ue_ue.ImportAssetsCommandlet.md#importdatalist)
- [IsClient](ue_ue.ImportAssetsCommandlet.md#isclient)
- [IsEditor](ue_ue.ImportAssetsCommandlet.md#iseditor)
- [IsServer](ue_ue.ImportAssetsCommandlet.md#isserver)
- [LogToConsole](ue_ue.ImportAssetsCommandlet.md#logtoconsole)
- [ShowErrorCount](ue_ue.ImportAssetsCommandlet.md#showerrorcount)
- [ShowProgress](ue_ue.ImportAssetsCommandlet.md#showprogress)
- [\_\_tid\_Commandlet\_\_](ue_ue.ImportAssetsCommandlet.md#__tid_commandlet__)
- [\_\_tid\_ImportAssetsCommandlet\_\_](ue_ue.ImportAssetsCommandlet.md#__tid_importassetscommandlet__)
- [\_\_tid\_Object\_\_](ue_ue.ImportAssetsCommandlet.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ImportAssetsCommandlet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ImportAssetsCommandlet.md#executeubergraph)
- [GetClass](ue_ue.ImportAssetsCommandlet.md#getclass)
- [GetName](ue_ue.ImportAssetsCommandlet.md#getname)
- [GetOuter](ue_ue.ImportAssetsCommandlet.md#getouter)
- [GetWorld](ue_ue.ImportAssetsCommandlet.md#getworld)
- [Find](ue_ue.ImportAssetsCommandlet.md#find)
- [Load](ue_ue.ImportAssetsCommandlet.md#load)
- [StaticClass](ue_ue.ImportAssetsCommandlet.md#staticclass)

## Constructors

### constructor

• **new ImportAssetsCommandlet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[constructor](ue_ue.Commandlet.md#constructor)

## Properties

### GlobalImportData

• **GlobalImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

___

### HelpDescription

• **HelpDescription**: `string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpDescription](ue_ue.Commandlet.md#helpdescription)

___

### HelpParamDescriptions

• **HelpParamDescriptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpParamDescriptions](ue_ue.Commandlet.md#helpparamdescriptions)

___

### HelpParamNames

• **HelpParamNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpParamNames](ue_ue.Commandlet.md#helpparamnames)

___

### HelpUsage

• **HelpUsage**: `string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpUsage](ue_ue.Commandlet.md#helpusage)

___

### HelpWebLink

• **HelpWebLink**: `string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpWebLink](ue_ue.Commandlet.md#helpweblink)

___

### ImportDataList

• **ImportDataList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)\>

___

### IsClient

• **IsClient**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[IsClient](ue_ue.Commandlet.md#isclient)

___

### IsEditor

• **IsEditor**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[IsEditor](ue_ue.Commandlet.md#iseditor)

___

### IsServer

• **IsServer**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[IsServer](ue_ue.Commandlet.md#isserver)

___

### LogToConsole

• **LogToConsole**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[LogToConsole](ue_ue.Commandlet.md#logtoconsole)

___

### ShowErrorCount

• **ShowErrorCount**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[ShowErrorCount](ue_ue.Commandlet.md#showerrorcount)

___

### ShowProgress

• **ShowProgress**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[ShowProgress](ue_ue.Commandlet.md#showprogress)

___

### \_\_tid\_Commandlet\_\_

• **\_\_tid\_Commandlet\_\_**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[__tid_Commandlet__](ue_ue.Commandlet.md#__tid_commandlet__)

___

### \_\_tid\_ImportAssetsCommandlet\_\_

• **\_\_tid\_ImportAssetsCommandlet\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[__tid_Object__](ue_ue.Commandlet.md#__tid_object__)

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

[Commandlet](ue_ue.Commandlet.md).[CreateDefaultSubobject](ue_ue.Commandlet.md#createdefaultsubobject)

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

[Commandlet](ue_ue.Commandlet.md).[ExecuteUbergraph](ue_ue.Commandlet.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetClass](ue_ue.Commandlet.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetName](ue_ue.Commandlet.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetOuter](ue_ue.Commandlet.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetWorld](ue_ue.Commandlet.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ImportAssetsCommandlet`](ue_ue.ImportAssetsCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ImportAssetsCommandlet`](ue_ue.ImportAssetsCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Find](ue_ue.Commandlet.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ImportAssetsCommandlet`](ue_ue.ImportAssetsCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ImportAssetsCommandlet`](ue_ue.ImportAssetsCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Load](ue_ue.Commandlet.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[StaticClass](ue_ue.Commandlet.md#staticclass)
