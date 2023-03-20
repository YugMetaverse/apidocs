[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UnrealPakCommandlet

# Class: UnrealPakCommandlet

[ue/ue](../modules/ue_ue.md).UnrealPakCommandlet

## Hierarchy

- [`Commandlet`](ue_ue.Commandlet.md)

  ↳ **`UnrealPakCommandlet`**

## Table of contents

### Constructors

- [constructor](ue_ue.UnrealPakCommandlet.md#constructor)

### Properties

- [HelpDescription](ue_ue.UnrealPakCommandlet.md#helpdescription)
- [HelpParamDescriptions](ue_ue.UnrealPakCommandlet.md#helpparamdescriptions)
- [HelpParamNames](ue_ue.UnrealPakCommandlet.md#helpparamnames)
- [HelpUsage](ue_ue.UnrealPakCommandlet.md#helpusage)
- [HelpWebLink](ue_ue.UnrealPakCommandlet.md#helpweblink)
- [IsClient](ue_ue.UnrealPakCommandlet.md#isclient)
- [IsEditor](ue_ue.UnrealPakCommandlet.md#iseditor)
- [IsServer](ue_ue.UnrealPakCommandlet.md#isserver)
- [LogToConsole](ue_ue.UnrealPakCommandlet.md#logtoconsole)
- [ShowErrorCount](ue_ue.UnrealPakCommandlet.md#showerrorcount)
- [ShowProgress](ue_ue.UnrealPakCommandlet.md#showprogress)
- [\_\_tid\_Commandlet\_\_](ue_ue.UnrealPakCommandlet.md#__tid_commandlet__)
- [\_\_tid\_Object\_\_](ue_ue.UnrealPakCommandlet.md#__tid_object__)
- [\_\_tid\_UnrealPakCommandlet\_\_](ue_ue.UnrealPakCommandlet.md#__tid_unrealpakcommandlet__)

### Methods

- [CreateDefaultSubobject](ue_ue.UnrealPakCommandlet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UnrealPakCommandlet.md#executeubergraph)
- [GetClass](ue_ue.UnrealPakCommandlet.md#getclass)
- [GetName](ue_ue.UnrealPakCommandlet.md#getname)
- [GetOuter](ue_ue.UnrealPakCommandlet.md#getouter)
- [GetWorld](ue_ue.UnrealPakCommandlet.md#getworld)
- [Find](ue_ue.UnrealPakCommandlet.md#find)
- [Load](ue_ue.UnrealPakCommandlet.md#load)
- [StaticClass](ue_ue.UnrealPakCommandlet.md#staticclass)

## Constructors

### constructor

• **new UnrealPakCommandlet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[constructor](ue_ue.Commandlet.md#constructor)

#### Defined in

[ue/ue.d.ts:64775](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64775)

## Properties

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

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[__tid_Object__](ue_ue.Commandlet.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_UnrealPakCommandlet\_\_

• **\_\_tid\_UnrealPakCommandlet\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64780](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64780)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UnrealPakCommandlet`](ue_ue.UnrealPakCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UnrealPakCommandlet`](ue_ue.UnrealPakCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Find](ue_ue.Commandlet.md#find)

#### Defined in

[ue/ue.d.ts:64777](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64777)

___

### Load

▸ `Static` **Load**(`InName`): [`UnrealPakCommandlet`](ue_ue.UnrealPakCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UnrealPakCommandlet`](ue_ue.UnrealPakCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Load](ue_ue.Commandlet.md#load)

#### Defined in

[ue/ue.d.ts:64778](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64778)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[StaticClass](ue_ue.Commandlet.md#staticclass)

#### Defined in

[ue/ue.d.ts:64776](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64776)
