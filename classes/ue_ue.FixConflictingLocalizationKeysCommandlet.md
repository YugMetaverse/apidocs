[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FixConflictingLocalizationKeysCommandlet

# Class: FixConflictingLocalizationKeysCommandlet

[ue/ue](../modules/ue_ue.md).FixConflictingLocalizationKeysCommandlet

## Hierarchy

- [`Commandlet`](ue_ue.Commandlet.md)

  ↳ **`FixConflictingLocalizationKeysCommandlet`**

## Table of contents

### Constructors

- [constructor](ue_ue.FixConflictingLocalizationKeysCommandlet.md#constructor)

### Properties

- [HelpDescription](ue_ue.FixConflictingLocalizationKeysCommandlet.md#helpdescription)
- [HelpParamDescriptions](ue_ue.FixConflictingLocalizationKeysCommandlet.md#helpparamdescriptions)
- [HelpParamNames](ue_ue.FixConflictingLocalizationKeysCommandlet.md#helpparamnames)
- [HelpUsage](ue_ue.FixConflictingLocalizationKeysCommandlet.md#helpusage)
- [HelpWebLink](ue_ue.FixConflictingLocalizationKeysCommandlet.md#helpweblink)
- [IsClient](ue_ue.FixConflictingLocalizationKeysCommandlet.md#isclient)
- [IsEditor](ue_ue.FixConflictingLocalizationKeysCommandlet.md#iseditor)
- [IsServer](ue_ue.FixConflictingLocalizationKeysCommandlet.md#isserver)
- [LogToConsole](ue_ue.FixConflictingLocalizationKeysCommandlet.md#logtoconsole)
- [ShowErrorCount](ue_ue.FixConflictingLocalizationKeysCommandlet.md#showerrorcount)
- [ShowProgress](ue_ue.FixConflictingLocalizationKeysCommandlet.md#showprogress)
- [\_\_tid\_Commandlet\_\_](ue_ue.FixConflictingLocalizationKeysCommandlet.md#__tid_commandlet__)
- [\_\_tid\_FixConflictingLocalizationKeysCommandlet\_\_](ue_ue.FixConflictingLocalizationKeysCommandlet.md#__tid_fixconflictinglocalizationkeyscommandlet__)
- [\_\_tid\_Object\_\_](ue_ue.FixConflictingLocalizationKeysCommandlet.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.FixConflictingLocalizationKeysCommandlet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FixConflictingLocalizationKeysCommandlet.md#executeubergraph)
- [GetClass](ue_ue.FixConflictingLocalizationKeysCommandlet.md#getclass)
- [GetName](ue_ue.FixConflictingLocalizationKeysCommandlet.md#getname)
- [GetOuter](ue_ue.FixConflictingLocalizationKeysCommandlet.md#getouter)
- [GetWorld](ue_ue.FixConflictingLocalizationKeysCommandlet.md#getworld)
- [Find](ue_ue.FixConflictingLocalizationKeysCommandlet.md#find)
- [Load](ue_ue.FixConflictingLocalizationKeysCommandlet.md#load)
- [StaticClass](ue_ue.FixConflictingLocalizationKeysCommandlet.md#staticclass)

## Constructors

### constructor

• **new FixConflictingLocalizationKeysCommandlet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[constructor](ue_ue.Commandlet.md#constructor)

#### Defined in

[ue/ue.d.ts:35605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35605)

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

### \_\_tid\_Commandlet\_\_

• **\_\_tid\_Commandlet\_\_**: `boolean`

#### Inherited from

[Commandlet](ue_ue.Commandlet.md).[__tid_Commandlet__](ue_ue.Commandlet.md#__tid_commandlet__)

#### Defined in

[ue/ue.d.ts:16182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16182)

___

### \_\_tid\_FixConflictingLocalizationKeysCommandlet\_\_

• **\_\_tid\_FixConflictingLocalizationKeysCommandlet\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35610)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FixConflictingLocalizationKeysCommandlet`](ue_ue.FixConflictingLocalizationKeysCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FixConflictingLocalizationKeysCommandlet`](ue_ue.FixConflictingLocalizationKeysCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Find](ue_ue.Commandlet.md#find)

#### Defined in

[ue/ue.d.ts:35607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35607)

___

### Load

▸ `Static` **Load**(`InName`): [`FixConflictingLocalizationKeysCommandlet`](ue_ue.FixConflictingLocalizationKeysCommandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FixConflictingLocalizationKeysCommandlet`](ue_ue.FixConflictingLocalizationKeysCommandlet.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[Load](ue_ue.Commandlet.md#load)

#### Defined in

[ue/ue.d.ts:35608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35608)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Commandlet](ue_ue.Commandlet.md).[StaticClass](ue_ue.Commandlet.md#staticclass)

#### Defined in

[ue/ue.d.ts:35606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35606)
