[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClientUnitTest

# Class: ClientUnitTest

[ue/ue](../modules/ue_ue.md).ClientUnitTest

## Hierarchy

- [`ProcessUnitTest`](ue_ue.ProcessUnitTest.md)

  ↳ **`ClientUnitTest`**

  ↳↳ [`FTextCrash`](ue_ue.FTextCrash.md)

  ↳↳ [`IPClient`](ue_ue.IPClient.md)

  ↳↳ [`UTT61_DebugReplicateData`](ue_ue.UTT61_DebugReplicateData.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ClientUnitTest.md#constructor)

### Properties

- [LastExecutionTime](ue_ue.ClientUnitTest.md#lastexecutiontime)
- [MinClient](ue_ue.ClientUnitTest.md#minclient)
- [PeakMemoryUsage](ue_ue.ClientUnitTest.md#peakmemoryusage)
- [TimeToPeakMem](ue_ue.ClientUnitTest.md#timetopeakmem)
- [UnitTasks](ue_ue.ClientUnitTest.md#unittasks)
- [VerificationState](ue_ue.ClientUnitTest.md#verificationstate)
- [\_\_tid\_ClientUnitTest\_\_](ue_ue.ClientUnitTest.md#__tid_clientunittest__)
- [\_\_tid\_Object\_\_](ue_ue.ClientUnitTest.md#__tid_object__)
- [\_\_tid\_ProcessUnitTest\_\_](ue_ue.ClientUnitTest.md#__tid_processunittest__)
- [\_\_tid\_UnitTestBase\_\_](ue_ue.ClientUnitTest.md#__tid_unittestbase__)
- [\_\_tid\_UnitTest\_\_](ue_ue.ClientUnitTest.md#__tid_unittest__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClientUnitTest.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClientUnitTest.md#executeubergraph)
- [GetClass](ue_ue.ClientUnitTest.md#getclass)
- [GetName](ue_ue.ClientUnitTest.md#getname)
- [GetOuter](ue_ue.ClientUnitTest.md#getouter)
- [GetWorld](ue_ue.ClientUnitTest.md#getworld)
- [Find](ue_ue.ClientUnitTest.md#find)
- [Load](ue_ue.ClientUnitTest.md#load)
- [StaticClass](ue_ue.ClientUnitTest.md#staticclass)

## Constructors

### constructor

• **new ClientUnitTest**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[constructor](ue_ue.ProcessUnitTest.md#constructor)

#### Defined in

[ue/ue.d.ts:27569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27569)

## Properties

### LastExecutionTime

• **LastExecutionTime**: `number`

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[LastExecutionTime](ue_ue.ProcessUnitTest.md#lastexecutiontime)

#### Defined in

[ue/ue.d.ts:27540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27540)

___

### MinClient

• **MinClient**: [`MinimalClient`](ue_ue.MinimalClient.md)

#### Defined in

[ue/ue.d.ts:27570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27570)

___

### PeakMemoryUsage

• **PeakMemoryUsage**: `bigint`

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[PeakMemoryUsage](ue_ue.ProcessUnitTest.md#peakmemoryusage)

#### Defined in

[ue/ue.d.ts:27538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27538)

___

### TimeToPeakMem

• **TimeToPeakMem**: `number`

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[TimeToPeakMem](ue_ue.ProcessUnitTest.md#timetopeakmem)

#### Defined in

[ue/ue.d.ts:27539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27539)

___

### UnitTasks

• **UnitTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTask`](ue_ue.UnitTask.md)\>

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[UnitTasks](ue_ue.ProcessUnitTest.md#unittasks)

#### Defined in

[ue/ue.d.ts:27541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27541)

___

### VerificationState

• **VerificationState**: [`EUnitTestVerification`](../enums/ue_ue.EUnitTestVerification.md)

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[VerificationState](ue_ue.ProcessUnitTest.md#verificationstate)

#### Defined in

[ue/ue.d.ts:27542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27542)

___

### \_\_tid\_ClientUnitTest\_\_

• **\_\_tid\_ClientUnitTest\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27575)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[__tid_Object__](ue_ue.ProcessUnitTest.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ProcessUnitTest\_\_

• **\_\_tid\_ProcessUnitTest\_\_**: `boolean`

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[__tid_ProcessUnitTest__](ue_ue.ProcessUnitTest.md#__tid_processunittest__)

#### Defined in

[ue/ue.d.ts:27556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27556)

___

### \_\_tid\_UnitTestBase\_\_

• **\_\_tid\_UnitTestBase\_\_**: `boolean`

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[__tid_UnitTestBase__](ue_ue.ProcessUnitTest.md#__tid_unittestbase__)

#### Defined in

[ue/ue.d.ts:27523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27523)

___

### \_\_tid\_UnitTest\_\_

• **\_\_tid\_UnitTest\_\_**: `boolean`

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[__tid_UnitTest__](ue_ue.ProcessUnitTest.md#__tid_unittest__)

#### Defined in

[ue/ue.d.ts:27547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27547)

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

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[CreateDefaultSubobject](ue_ue.ProcessUnitTest.md#createdefaultsubobject)

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

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[ExecuteUbergraph](ue_ue.ProcessUnitTest.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[GetClass](ue_ue.ProcessUnitTest.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[GetName](ue_ue.ProcessUnitTest.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[GetOuter](ue_ue.ProcessUnitTest.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[GetWorld](ue_ue.ProcessUnitTest.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClientUnitTest`](ue_ue.ClientUnitTest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClientUnitTest`](ue_ue.ClientUnitTest.md)

#### Overrides

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[Find](ue_ue.ProcessUnitTest.md#find)

#### Defined in

[ue/ue.d.ts:27572](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27572)

___

### Load

▸ `Static` **Load**(`InName`): [`ClientUnitTest`](ue_ue.ClientUnitTest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClientUnitTest`](ue_ue.ClientUnitTest.md)

#### Overrides

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[Load](ue_ue.ProcessUnitTest.md#load)

#### Defined in

[ue/ue.d.ts:27573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27573)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ProcessUnitTest](ue_ue.ProcessUnitTest.md).[StaticClass](ue_ue.ProcessUnitTest.md#staticclass)

#### Defined in

[ue/ue.d.ts:27571](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27571)
