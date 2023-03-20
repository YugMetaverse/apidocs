[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DiffAssetRegistriesCommandlet

# Class: DiffAssetRegistriesCommandlet

[ue/ue](../modules/ue_ue.md).DiffAssetRegistriesCommandlet

## Hierarchy

- [`Commandlet`](ue_ue.Commandlet.md)

  ↳ **`DiffAssetRegistriesCommandlet`**

## Table of contents

### Constructors

- [constructor](ue_ue.DiffAssetRegistriesCommandlet.md#constructor)

### Properties

- [AssetRegistrySearchPath](ue_ue.DiffAssetRegistriesCommandlet.md#assetregistrysearchpath)
- [HelpDescription](ue_ue.DiffAssetRegistriesCommandlet.md#helpdescription)
- [HelpParamDescriptions](ue_ue.DiffAssetRegistriesCommandlet.md#helpparamdescriptions)
- [HelpParamNames](ue_ue.DiffAssetRegistriesCommandlet.md#helpparamnames)
- [HelpUsage](ue_ue.DiffAssetRegistriesCommandlet.md#helpusage)
- [HelpWebLink](ue_ue.DiffAssetRegistriesCommandlet.md#helpweblink)
- [IsClient](ue_ue.DiffAssetRegistriesCommandlet.md#isclient)
- [IsEditor](ue_ue.DiffAssetRegistriesCommandlet.md#iseditor)
- [IsServer](ue_ue.DiffAssetRegistriesCommandlet.md#isserver)
- [LogToConsole](ue_ue.DiffAssetRegistriesCommandlet.md#logtoconsole)
- [P4EngineAssetPath](ue_ue.DiffAssetRegistriesCommandlet.md#p4engineassetpath)
- [P4EngineBasePath](ue_ue.DiffAssetRegistriesCommandlet.md#p4enginebasepath)
- [P4GameAssetPath](ue_ue.DiffAssetRegistriesCommandlet.md#p4gameassetpath)
- [P4GameBasePath](ue_ue.DiffAssetRegistriesCommandlet.md#p4gamebasepath)
- [P4Repository](ue_ue.DiffAssetRegistriesCommandlet.md#p4repository)
- [RegexBranchCL](ue_ue.DiffAssetRegistriesCommandlet.md#regexbranchcl)
- [ShowErrorCount](ue_ue.DiffAssetRegistriesCommandlet.md#showerrorcount)
- [ShowProgress](ue_ue.DiffAssetRegistriesCommandlet.md#showprogress)
- [\_\_tid\_Commandlet\_\_](ue_ue.DiffAssetRegistriesCommandlet.md#__tid_commandlet__)
- [\_\_tid\_DiffAssetRegistriesCommandlet\_\_](ue_ue.DiffAssetRegistriesCommandlet.md#__tid_diffassetregistriescommandlet__)
- [\_\_tid\_Object\_\_](ue_ue.DiffAssetRegistriesCommandlet.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DiffAssetRegistriesCommandlet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DiffAssetRegistriesCommandlet.md#executeubergraph)
- [GetClass](ue_ue.DiffAssetRegistriesCommandlet.md#getclass)
- [GetName](ue_ue.DiffAssetRegistriesCommandlet.md#getname)
- [GetOuter](ue_ue.DiffAssetRegistriesCommandlet.md#getouter)
- [GetWorld](ue_ue.DiffAssetRegistriesCommandlet.md#getworld)
- [Find](ue_ue.DiffAssetRegistriesCommandlet.md#find)
- [Load](ue_ue.DiffAssetRegistriesCommandlet.md#load)
- [StaticClass](ue_ue.DiffAssetRegistriesCommandlet.md#staticclass)

## Constructors

### constructor

• **new DiffAssetRegistriesCommandlet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[constructor](ue_ue.Commandlet.md#constructor)

#### Defined in

[ue/ue.d.ts:30910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30910)

## Properties

### AssetRegistrySearchPath

• **AssetRegistrySearchPath**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:30911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30911)

___

### HelpDescription

• **HelpDescription**: `string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpDescription](ue_ue.Commandlet.md#helpdescription)

#### Defined in

[ue/ue.d.ts:16167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16167)

___

### HelpParamDescriptions

• **HelpParamDescriptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpParamDescriptions](ue_ue.Commandlet.md#helpparamdescriptions)

#### Defined in

[ue/ue.d.ts:16171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16171)

___

### HelpParamNames

• **HelpParamNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpParamNames](ue_ue.Commandlet.md#helpparamnames)

#### Defined in

[ue/ue.d.ts:16170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16170)

___

### HelpUsage

• **HelpUsage**: `string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpUsage](ue_ue.Commandlet.md#helpusage)

#### Defined in

[ue/ue.d.ts:16168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16168)

___

### HelpWebLink

• **HelpWebLink**: `string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpWebLink](ue_ue.Commandlet.md#helpweblink)

#### Defined in

[ue/ue.d.ts:16169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16169)

___

### IsClient

• **IsClient**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[IsClient](ue_ue.Commandlet.md#isclient)

#### Defined in

[ue/ue.d.ts:16173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16173)

___

### IsEditor

• **IsEditor**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[IsEditor](ue_ue.Commandlet.md#iseditor)

#### Defined in

[ue/ue.d.ts:16174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16174)

___

### IsServer

• **IsServer**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[IsServer](ue_ue.Commandlet.md#isserver)

#### Defined in

[ue/ue.d.ts:16172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16172)

___

### LogToConsole

• **LogToConsole**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[LogToConsole](ue_ue.Commandlet.md#logtoconsole)

#### Defined in

[ue/ue.d.ts:16175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16175)

___

### P4EngineAssetPath

• **P4EngineAssetPath**: `string`

#### Defined in

[ue/ue.d.ts:30914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30914)

___

### P4EngineBasePath

• **P4EngineBasePath**: `string`

#### Defined in

[ue/ue.d.ts:30913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30913)

___

### P4GameAssetPath

• **P4GameAssetPath**: `string`

#### Defined in

[ue/ue.d.ts:30916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30916)

___

### P4GameBasePath

• **P4GameBasePath**: `string`

#### Defined in

[ue/ue.d.ts:30915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30915)

___

### P4Repository

• **P4Repository**: `string`

#### Defined in

[ue/ue.d.ts:30912](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30912)

___

### RegexBranchCL

• **RegexBranchCL**: `string`

#### Defined in

[ue/ue.d.ts:30917](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30917)

___

### ShowErrorCount

• **ShowErrorCount**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[ShowErrorCount](ue_ue.Commandlet.md#showerrorcount)

#### Defined in

[ue/ue.d.ts:16176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16176)

___

### ShowProgress

• **ShowProgress**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[ShowProgress](ue_ue.Commandlet.md#showprogress)

#### Defined in

[ue/ue.d.ts:16177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16177)

___

### \_\_tid\_Commandlet\_\_

• **\_\_tid\_Commandlet\_\_**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[__tid_Commandlet__](ue_ue.Commandlet.md#__tid_commandlet__)

#### Defined in

[ue/ue.d.ts:16182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16182)

___

### \_\_tid\_DiffAssetRegistriesCommandlet\_\_

• **\_\_tid\_DiffAssetRegistriesCommandlet\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30922](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30922)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[__tid_Object__](ue_ue.Commandlet.md#__tid_object__)

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

[Commandlet](ue_ue.Commandlet.md).[CreateDefaultSubobject](ue_ue.Commandlet.md#createdefaultsubobject)

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

[Commandlet](ue_ue.Commandlet.md).[ExecuteUbergraph](ue_ue.Commandlet.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetClass](ue_ue.Commandlet.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetName](ue_ue.Commandlet.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetOuter](ue_ue.Commandlet.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetWorld](ue_ue.Commandlet.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DiffAssetRegistriesCommandlet`](ue_ue.DiffAssetRegistriesCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DiffAssetRegistriesCommandlet`](ue_ue.DiffAssetRegistriesCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Find](ue_ue.Commandlet.md#find)

#### Defined in

[ue/ue.d.ts:30919](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30919)

___

### Load

▸ `Static` **Load**(`InName`): [`DiffAssetRegistriesCommandlet`](ue_ue.DiffAssetRegistriesCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DiffAssetRegistriesCommandlet`](ue_ue.DiffAssetRegistriesCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Load](ue_ue.Commandlet.md#load)

#### Defined in

[ue/ue.d.ts:30920](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30920)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[StaticClass](ue_ue.Commandlet.md#staticclass)

#### Defined in

[ue/ue.d.ts:30918](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30918)
