[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UnitTest

# Class: UnitTest

[ue/ue](../modules/ue_ue.md).UnitTest

## Hierarchy

- [`UnitTestBase`](ue_ue.UnitTestBase.md)

  ↳ **`UnitTest`**

  ↳↳ [`ProcessUnitTest`](ue_ue.ProcessUnitTest.md)

  ↳↳ [`NetBitsTest`](ue_ue.NetBitsTest.md)

  ↳↳ [`PackedVectorTest`](ue_ue.PackedVectorTest.md)

  ↳↳ [`VMReflection`](ue_ue.VMReflection.md)

## Table of contents

### Constructors

- [constructor](ue_ue.UnitTest.md#constructor)

### Properties

- [LastExecutionTime](ue_ue.UnitTest.md#lastexecutiontime)
- [PeakMemoryUsage](ue_ue.UnitTest.md#peakmemoryusage)
- [TimeToPeakMem](ue_ue.UnitTest.md#timetopeakmem)
- [UnitTasks](ue_ue.UnitTest.md#unittasks)
- [VerificationState](ue_ue.UnitTest.md#verificationstate)
- [\_\_tid\_Object\_\_](ue_ue.UnitTest.md#__tid_object__)
- [\_\_tid\_UnitTestBase\_\_](ue_ue.UnitTest.md#__tid_unittestbase__)
- [\_\_tid\_UnitTest\_\_](ue_ue.UnitTest.md#__tid_unittest__)

### Methods

- [CreateDefaultSubobject](ue_ue.UnitTest.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UnitTest.md#executeubergraph)
- [GetClass](ue_ue.UnitTest.md#getclass)
- [GetName](ue_ue.UnitTest.md#getname)
- [GetOuter](ue_ue.UnitTest.md#getouter)
- [GetWorld](ue_ue.UnitTest.md#getworld)
- [Find](ue_ue.UnitTest.md#find)
- [Load](ue_ue.UnitTest.md#load)
- [StaticClass](ue_ue.UnitTest.md#staticclass)

## Constructors

### constructor

• **new UnitTest**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[UnitTestBase](ue_ue.UnitTestBase.md).[constructor](ue_ue.UnitTestBase.md#constructor)

#### Defined in

[ue/ue.d.ts:27537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27537)

## Properties

### LastExecutionTime

• **LastExecutionTime**: `number`

#### Defined in

[ue/ue.d.ts:27540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27540)

___

### PeakMemoryUsage

• **PeakMemoryUsage**: `bigint`

#### Defined in

[ue/ue.d.ts:27538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27538)

___

### TimeToPeakMem

• **TimeToPeakMem**: `number`

#### Defined in

[ue/ue.d.ts:27539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27539)

___

### UnitTasks

• **UnitTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTask`](ue_ue.UnitTask.md)\>

#### Defined in

[ue/ue.d.ts:27541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27541)

___

### VerificationState

• **VerificationState**: [`EUnitTestVerification`](../enums/ue_ue.EUnitTestVerification.md)

#### Defined in

[ue/ue.d.ts:27542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27542)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[__tid_Object__](ue_ue.UnitTestBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_UnitTestBase\_\_

• **\_\_tid\_UnitTestBase\_\_**: `boolean`

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[__tid_UnitTestBase__](ue_ue.UnitTestBase.md#__tid_unittestbase__)

#### Defined in

[ue/ue.d.ts:27523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27523)

___

### \_\_tid\_UnitTest\_\_

• **\_\_tid\_UnitTest\_\_**: `boolean`

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

[UnitTestBase](ue_ue.UnitTestBase.md).[CreateDefaultSubobject](ue_ue.UnitTestBase.md#createdefaultsubobject)

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

[UnitTestBase](ue_ue.UnitTestBase.md).[ExecuteUbergraph](ue_ue.UnitTestBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[GetClass](ue_ue.UnitTestBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[GetName](ue_ue.UnitTestBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[GetOuter](ue_ue.UnitTestBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[GetWorld](ue_ue.UnitTestBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UnitTest`](ue_ue.UnitTest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UnitTest`](ue_ue.UnitTest.md)

#### Overrides

[UnitTestBase](ue_ue.UnitTestBase.md).[Find](ue_ue.UnitTestBase.md#find)

#### Defined in

[ue/ue.d.ts:27544](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27544)

___

### Load

▸ `Static` **Load**(`InName`): [`UnitTest`](ue_ue.UnitTest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UnitTest`](ue_ue.UnitTest.md)

#### Overrides

[UnitTestBase](ue_ue.UnitTestBase.md).[Load](ue_ue.UnitTestBase.md#load)

#### Defined in

[ue/ue.d.ts:27545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27545)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[UnitTestBase](ue_ue.UnitTestBase.md).[StaticClass](ue_ue.UnitTestBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:27543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27543)
