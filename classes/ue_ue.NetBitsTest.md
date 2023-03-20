[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NetBitsTest

# Class: NetBitsTest

[ue/ue](../modules/ue_ue.md).NetBitsTest

## Hierarchy

- [`UnitTest`](ue_ue.UnitTest.md)

  ↳ **`NetBitsTest`**

## Table of contents

### Constructors

- [constructor](ue_ue.NetBitsTest.md#constructor)

### Properties

- [LastExecutionTime](ue_ue.NetBitsTest.md#lastexecutiontime)
- [PeakMemoryUsage](ue_ue.NetBitsTest.md#peakmemoryusage)
- [TimeToPeakMem](ue_ue.NetBitsTest.md#timetopeakmem)
- [UnitTasks](ue_ue.NetBitsTest.md#unittasks)
- [VerificationState](ue_ue.NetBitsTest.md#verificationstate)
- [\_\_tid\_NetBitsTest\_\_](ue_ue.NetBitsTest.md#__tid_netbitstest__)
- [\_\_tid\_Object\_\_](ue_ue.NetBitsTest.md#__tid_object__)
- [\_\_tid\_UnitTestBase\_\_](ue_ue.NetBitsTest.md#__tid_unittestbase__)
- [\_\_tid\_UnitTest\_\_](ue_ue.NetBitsTest.md#__tid_unittest__)

### Methods

- [CreateDefaultSubobject](ue_ue.NetBitsTest.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NetBitsTest.md#executeubergraph)
- [GetClass](ue_ue.NetBitsTest.md#getclass)
- [GetName](ue_ue.NetBitsTest.md#getname)
- [GetOuter](ue_ue.NetBitsTest.md#getouter)
- [GetWorld](ue_ue.NetBitsTest.md#getworld)
- [Find](ue_ue.NetBitsTest.md#find)
- [Load](ue_ue.NetBitsTest.md#load)
- [StaticClass](ue_ue.NetBitsTest.md#staticclass)

## Constructors

### constructor

• **new NetBitsTest**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[UnitTest](ue_ue.UnitTest.md).[constructor](ue_ue.UnitTest.md#constructor)

## Properties

### LastExecutionTime

• **LastExecutionTime**: `number`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[LastExecutionTime](ue_ue.UnitTest.md#lastexecutiontime)

___

### PeakMemoryUsage

• **PeakMemoryUsage**: `bigint`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[PeakMemoryUsage](ue_ue.UnitTest.md#peakmemoryusage)

___

### TimeToPeakMem

• **TimeToPeakMem**: `number`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[TimeToPeakMem](ue_ue.UnitTest.md#timetopeakmem)

___

### UnitTasks

• **UnitTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTask`](ue_ue.UnitTask.md)\>

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[UnitTasks](ue_ue.UnitTest.md#unittasks)

___

### VerificationState

• **VerificationState**: [`EUnitTestVerification`](../enums/ue_ue.EUnitTestVerification.md)

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[VerificationState](ue_ue.UnitTest.md#verificationstate)

___

### \_\_tid\_NetBitsTest\_\_

• **\_\_tid\_NetBitsTest\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[__tid_Object__](ue_ue.UnitTest.md#__tid_object__)

___

### \_\_tid\_UnitTestBase\_\_

• **\_\_tid\_UnitTestBase\_\_**: `boolean`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[__tid_UnitTestBase__](ue_ue.UnitTest.md#__tid_unittestbase__)

___

### \_\_tid\_UnitTest\_\_

• **\_\_tid\_UnitTest\_\_**: `boolean`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[__tid_UnitTest__](ue_ue.UnitTest.md#__tid_unittest__)

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

[UnitTest](ue_ue.UnitTest.md).[CreateDefaultSubobject](ue_ue.UnitTest.md#createdefaultsubobject)

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

[UnitTest](ue_ue.UnitTest.md).[ExecuteUbergraph](ue_ue.UnitTest.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[GetClass](ue_ue.UnitTest.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[GetName](ue_ue.UnitTest.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[GetOuter](ue_ue.UnitTest.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[GetWorld](ue_ue.UnitTest.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NetBitsTest`](ue_ue.NetBitsTest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NetBitsTest`](ue_ue.NetBitsTest.md)

#### Overrides

[UnitTest](ue_ue.UnitTest.md).[Find](ue_ue.UnitTest.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`NetBitsTest`](ue_ue.NetBitsTest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NetBitsTest`](ue_ue.NetBitsTest.md)

#### Overrides

[UnitTest](ue_ue.UnitTest.md).[Load](ue_ue.UnitTest.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[UnitTest](ue_ue.UnitTest.md).[StaticClass](ue_ue.UnitTest.md#staticclass)
