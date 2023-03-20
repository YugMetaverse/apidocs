[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetRegUtilCommandlet

# Class: AssetRegUtilCommandlet

[ue/ue](../modules/ue_ue.md).AssetRegUtilCommandlet

## Hierarchy

- [`Commandlet`](ue_ue.Commandlet.md)

  ↳ **`AssetRegUtilCommandlet`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetRegUtilCommandlet.md#constructor)

### Properties

- [HelpDescription](ue_ue.AssetRegUtilCommandlet.md#helpdescription)
- [HelpParamDescriptions](ue_ue.AssetRegUtilCommandlet.md#helpparamdescriptions)
- [HelpParamNames](ue_ue.AssetRegUtilCommandlet.md#helpparamnames)
- [HelpUsage](ue_ue.AssetRegUtilCommandlet.md#helpusage)
- [HelpWebLink](ue_ue.AssetRegUtilCommandlet.md#helpweblink)
- [IsClient](ue_ue.AssetRegUtilCommandlet.md#isclient)
- [IsEditor](ue_ue.AssetRegUtilCommandlet.md#iseditor)
- [IsServer](ue_ue.AssetRegUtilCommandlet.md#isserver)
- [LogToConsole](ue_ue.AssetRegUtilCommandlet.md#logtoconsole)
- [ShowErrorCount](ue_ue.AssetRegUtilCommandlet.md#showerrorcount)
- [ShowProgress](ue_ue.AssetRegUtilCommandlet.md#showprogress)
- [\_\_tid\_AssetRegUtilCommandlet\_\_](ue_ue.AssetRegUtilCommandlet.md#__tid_assetregutilcommandlet__)
- [\_\_tid\_Commandlet\_\_](ue_ue.AssetRegUtilCommandlet.md#__tid_commandlet__)
- [\_\_tid\_Object\_\_](ue_ue.AssetRegUtilCommandlet.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetRegUtilCommandlet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetRegUtilCommandlet.md#executeubergraph)
- [GetClass](ue_ue.AssetRegUtilCommandlet.md#getclass)
- [GetName](ue_ue.AssetRegUtilCommandlet.md#getname)
- [GetOuter](ue_ue.AssetRegUtilCommandlet.md#getouter)
- [GetWorld](ue_ue.AssetRegUtilCommandlet.md#getworld)
- [Find](ue_ue.AssetRegUtilCommandlet.md#find)
- [Load](ue_ue.AssetRegUtilCommandlet.md#load)
- [StaticClass](ue_ue.AssetRegUtilCommandlet.md#staticclass)

## Constructors

### constructor

• **new AssetRegUtilCommandlet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[constructor](ue_ue.Commandlet.md#constructor)

#### Defined in

[ue/ue.d.ts:21876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21876)

## Properties

### HelpDescription

• **HelpDescription**: `string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpDescription](ue_ue.Commandlet.md#helpdescription)

#### Defined in

[ue/ue.d.ts:16167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16167)

___

### HelpParamDescriptions

• **HelpParamDescriptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpParamDescriptions](ue_ue.Commandlet.md#helpparamdescriptions)

#### Defined in

[ue/ue.d.ts:16171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16171)

___

### HelpParamNames

• **HelpParamNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpParamNames](ue_ue.Commandlet.md#helpparamnames)

#### Defined in

[ue/ue.d.ts:16170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16170)

___

### HelpUsage

• **HelpUsage**: `string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpUsage](ue_ue.Commandlet.md#helpusage)

#### Defined in

[ue/ue.d.ts:16168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16168)

___

### HelpWebLink

• **HelpWebLink**: `string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[HelpWebLink](ue_ue.Commandlet.md#helpweblink)

#### Defined in

[ue/ue.d.ts:16169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16169)

___

### IsClient

• **IsClient**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[IsClient](ue_ue.Commandlet.md#isclient)

#### Defined in

[ue/ue.d.ts:16173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16173)

___

### IsEditor

• **IsEditor**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[IsEditor](ue_ue.Commandlet.md#iseditor)

#### Defined in

[ue/ue.d.ts:16174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16174)

___

### IsServer

• **IsServer**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[IsServer](ue_ue.Commandlet.md#isserver)

#### Defined in

[ue/ue.d.ts:16172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16172)

___

### LogToConsole

• **LogToConsole**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[LogToConsole](ue_ue.Commandlet.md#logtoconsole)

#### Defined in

[ue/ue.d.ts:16175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16175)

___

### ShowErrorCount

• **ShowErrorCount**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[ShowErrorCount](ue_ue.Commandlet.md#showerrorcount)

#### Defined in

[ue/ue.d.ts:16176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16176)

___

### ShowProgress

• **ShowProgress**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[ShowProgress](ue_ue.Commandlet.md#showprogress)

#### Defined in

[ue/ue.d.ts:16177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16177)

___

### \_\_tid\_AssetRegUtilCommandlet\_\_

• **\_\_tid\_AssetRegUtilCommandlet\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21881)

___

### \_\_tid\_Commandlet\_\_

• **\_\_tid\_Commandlet\_\_**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[__tid_Commandlet__](ue_ue.Commandlet.md#__tid_commandlet__)

#### Defined in

[ue/ue.d.ts:16182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16182)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[__tid_Object__](ue_ue.Commandlet.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Commandlet](ue_ue.Commandlet.md).[ExecuteUbergraph](ue_ue.Commandlet.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetClass](ue_ue.Commandlet.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetName](ue_ue.Commandlet.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetOuter](ue_ue.Commandlet.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[GetWorld](ue_ue.Commandlet.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetRegUtilCommandlet`](ue_ue.AssetRegUtilCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetRegUtilCommandlet`](ue_ue.AssetRegUtilCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Find](ue_ue.Commandlet.md#find)

#### Defined in

[ue/ue.d.ts:21878](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21878)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetRegUtilCommandlet`](ue_ue.AssetRegUtilCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetRegUtilCommandlet`](ue_ue.AssetRegUtilCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Load](ue_ue.Commandlet.md#load)

#### Defined in

[ue/ue.d.ts:21879](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21879)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[StaticClass](ue_ue.Commandlet.md#staticclass)

#### Defined in

[ue/ue.d.ts:21877](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21877)