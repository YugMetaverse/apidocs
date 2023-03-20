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

## Properties

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

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[__tid_Object__](ue_ue.Commandlet.md#__tid_object__)

___

### \_\_tid\_UnrealPakCommandlet\_\_

• **\_\_tid\_UnrealPakCommandlet\_\_**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[StaticClass](ue_ue.Commandlet.md#staticclass)
