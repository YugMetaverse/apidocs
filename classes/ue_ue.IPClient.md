[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / IPClient

# Class: IPClient

[ue/ue](../modules/ue_ue.md).IPClient

## Hierarchy

- [`ClientUnitTest`](ue_ue.ClientUnitTest.md)

  ↳ **`IPClient`**

  ↳↳ [`SteamClient`](ue_ue.SteamClient.md)

  ↳↳ [`WebSocketClient`](ue_ue.WebSocketClient.md)

## Table of contents

### Constructors

- [constructor](ue_ue.IPClient.md#constructor)

### Properties

- [LastExecutionTime](ue_ue.IPClient.md#lastexecutiontime)
- [MinClient](ue_ue.IPClient.md#minclient)
- [PeakMemoryUsage](ue_ue.IPClient.md#peakmemoryusage)
- [TimeToPeakMem](ue_ue.IPClient.md#timetopeakmem)
- [UnitTasks](ue_ue.IPClient.md#unittasks)
- [VerificationState](ue_ue.IPClient.md#verificationstate)
- [\_\_tid\_ClientUnitTest\_\_](ue_ue.IPClient.md#__tid_clientunittest__)
- [\_\_tid\_IPClient\_\_](ue_ue.IPClient.md#__tid_ipclient__)
- [\_\_tid\_Object\_\_](ue_ue.IPClient.md#__tid_object__)
- [\_\_tid\_ProcessUnitTest\_\_](ue_ue.IPClient.md#__tid_processunittest__)
- [\_\_tid\_UnitTestBase\_\_](ue_ue.IPClient.md#__tid_unittestbase__)
- [\_\_tid\_UnitTest\_\_](ue_ue.IPClient.md#__tid_unittest__)

### Methods

- [CreateDefaultSubobject](ue_ue.IPClient.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.IPClient.md#executeubergraph)
- [GetClass](ue_ue.IPClient.md#getclass)
- [GetName](ue_ue.IPClient.md#getname)
- [GetOuter](ue_ue.IPClient.md#getouter)
- [GetWorld](ue_ue.IPClient.md#getworld)
- [Find](ue_ue.IPClient.md#find)
- [Load](ue_ue.IPClient.md#load)
- [StaticClass](ue_ue.IPClient.md#staticclass)

## Constructors

### constructor

• **new IPClient**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ClientUnitTest](ue_ue.ClientUnitTest.md).[constructor](ue_ue.ClientUnitTest.md#constructor)

## Properties

### LastExecutionTime

• **LastExecutionTime**: `number`

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[LastExecutionTime](ue_ue.ClientUnitTest.md#lastexecutiontime)

___

### MinClient

• **MinClient**: [`MinimalClient`](ue_ue.MinimalClient.md)

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[MinClient](ue_ue.ClientUnitTest.md#minclient)

___

### PeakMemoryUsage

• **PeakMemoryUsage**: `bigint`

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[PeakMemoryUsage](ue_ue.ClientUnitTest.md#peakmemoryusage)

___

### TimeToPeakMem

• **TimeToPeakMem**: `number`

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[TimeToPeakMem](ue_ue.ClientUnitTest.md#timetopeakmem)

___

### UnitTasks

• **UnitTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTask`](ue_ue.UnitTask.md)\>

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[UnitTasks](ue_ue.ClientUnitTest.md#unittasks)

___

### VerificationState

• **VerificationState**: [`EUnitTestVerification`](../enums/ue_ue.EUnitTestVerification.md)

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[VerificationState](ue_ue.ClientUnitTest.md#verificationstate)

___

### \_\_tid\_ClientUnitTest\_\_

• **\_\_tid\_ClientUnitTest\_\_**: `boolean`

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[__tid_ClientUnitTest__](ue_ue.ClientUnitTest.md#__tid_clientunittest__)

___

### \_\_tid\_IPClient\_\_

• **\_\_tid\_IPClient\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[__tid_Object__](ue_ue.ClientUnitTest.md#__tid_object__)

___

### \_\_tid\_ProcessUnitTest\_\_

• **\_\_tid\_ProcessUnitTest\_\_**: `boolean`

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[__tid_ProcessUnitTest__](ue_ue.ClientUnitTest.md#__tid_processunittest__)

___

### \_\_tid\_UnitTestBase\_\_

• **\_\_tid\_UnitTestBase\_\_**: `boolean`

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[__tid_UnitTestBase__](ue_ue.ClientUnitTest.md#__tid_unittestbase__)

___

### \_\_tid\_UnitTest\_\_

• **\_\_tid\_UnitTest\_\_**: `boolean`

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[__tid_UnitTest__](ue_ue.ClientUnitTest.md#__tid_unittest__)

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

[ClientUnitTest](ue_ue.ClientUnitTest.md).[CreateDefaultSubobject](ue_ue.ClientUnitTest.md#createdefaultsubobject)

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

[ClientUnitTest](ue_ue.ClientUnitTest.md).[ExecuteUbergraph](ue_ue.ClientUnitTest.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[GetClass](ue_ue.ClientUnitTest.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[GetName](ue_ue.ClientUnitTest.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[GetOuter](ue_ue.ClientUnitTest.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ClientUnitTest](ue_ue.ClientUnitTest.md).[GetWorld](ue_ue.ClientUnitTest.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`IPClient`](ue_ue.IPClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`IPClient`](ue_ue.IPClient.md)

#### Overrides

[ClientUnitTest](ue_ue.ClientUnitTest.md).[Find](ue_ue.ClientUnitTest.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`IPClient`](ue_ue.IPClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`IPClient`](ue_ue.IPClient.md)

#### Overrides

[ClientUnitTest](ue_ue.ClientUnitTest.md).[Load](ue_ue.ClientUnitTest.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ClientUnitTest](ue_ue.ClientUnitTest.md).[StaticClass](ue_ue.ClientUnitTest.md#staticclass)
