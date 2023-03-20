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

## Properties

### LastExecutionTime

• **LastExecutionTime**: `number`

___

### PeakMemoryUsage

• **PeakMemoryUsage**: `bigint`

___

### TimeToPeakMem

• **TimeToPeakMem**: `number`

___

### UnitTasks

• **UnitTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTask`](ue_ue.UnitTask.md)\>

___

### VerificationState

• **VerificationState**: [`EUnitTestVerification`](../enums/ue_ue.EUnitTestVerification.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[__tid_Object__](ue_ue.UnitTestBase.md#__tid_object__)

___

### \_\_tid\_UnitTestBase\_\_

• **\_\_tid\_UnitTestBase\_\_**: `boolean`

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[__tid_UnitTestBase__](ue_ue.UnitTestBase.md#__tid_unittestbase__)

___

### \_\_tid\_UnitTest\_\_

• **\_\_tid\_UnitTest\_\_**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[GetClass](ue_ue.UnitTestBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[GetName](ue_ue.UnitTestBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[GetOuter](ue_ue.UnitTestBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[UnitTestBase](ue_ue.UnitTestBase.md).[GetWorld](ue_ue.UnitTestBase.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[UnitTestBase](ue_ue.UnitTestBase.md).[StaticClass](ue_ue.UnitTestBase.md#staticclass)
