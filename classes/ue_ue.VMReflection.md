[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VMReflection

# Class: VMReflection

[ue/ue](../modules/ue_ue.md).VMReflection

## Hierarchy

- [`UnitTest`](ue_ue.UnitTest.md)

  ↳ **`VMReflection`**

## Table of contents

### Constructors

- [constructor](ue_ue.VMReflection.md#constructor)

### Properties

- [LastExecutionTime](ue_ue.VMReflection.md#lastexecutiontime)
- [PeakMemoryUsage](ue_ue.VMReflection.md#peakmemoryusage)
- [TimeToPeakMem](ue_ue.VMReflection.md#timetopeakmem)
- [UnitTasks](ue_ue.VMReflection.md#unittasks)
- [VerificationState](ue_ue.VMReflection.md#verificationstate)
- [\_\_tid\_Object\_\_](ue_ue.VMReflection.md#__tid_object__)
- [\_\_tid\_UnitTestBase\_\_](ue_ue.VMReflection.md#__tid_unittestbase__)
- [\_\_tid\_UnitTest\_\_](ue_ue.VMReflection.md#__tid_unittest__)
- [\_\_tid\_VMReflection\_\_](ue_ue.VMReflection.md#__tid_vmreflection__)

### Methods

- [CreateDefaultSubobject](ue_ue.VMReflection.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VMReflection.md#executeubergraph)
- [GetClass](ue_ue.VMReflection.md#getclass)
- [GetName](ue_ue.VMReflection.md#getname)
- [GetOuter](ue_ue.VMReflection.md#getouter)
- [GetWorld](ue_ue.VMReflection.md#getworld)
- [Find](ue_ue.VMReflection.md#find)
- [Load](ue_ue.VMReflection.md#load)
- [StaticClass](ue_ue.VMReflection.md#staticclass)

## Constructors

### constructor

• **new VMReflection**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[UnitTest](ue_ue.UnitTest.md).[constructor](ue_ue.UnitTest.md#constructor)

#### Defined in

[ue/ue.d.ts:65362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65362)

## Properties

### LastExecutionTime

• **LastExecutionTime**: `number`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[LastExecutionTime](ue_ue.UnitTest.md#lastexecutiontime)

#### Defined in

[ue/ue.d.ts:27540](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27540)

___

### PeakMemoryUsage

• **PeakMemoryUsage**: `bigint`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[PeakMemoryUsage](ue_ue.UnitTest.md#peakmemoryusage)

#### Defined in

[ue/ue.d.ts:27538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27538)

___

### TimeToPeakMem

• **TimeToPeakMem**: `number`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[TimeToPeakMem](ue_ue.UnitTest.md#timetopeakmem)

#### Defined in

[ue/ue.d.ts:27539](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27539)

___

### UnitTasks

• **UnitTasks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTask`](ue_ue.UnitTask.md)\>

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[UnitTasks](ue_ue.UnitTest.md#unittasks)

#### Defined in

[ue/ue.d.ts:27541](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27541)

___

### VerificationState

• **VerificationState**: [`EUnitTestVerification`](../enums/ue_ue.EUnitTestVerification.md)

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[VerificationState](ue_ue.UnitTest.md#verificationstate)

#### Defined in

[ue/ue.d.ts:27542](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27542)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[__tid_Object__](ue_ue.UnitTest.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_UnitTestBase\_\_

• **\_\_tid\_UnitTestBase\_\_**: `boolean`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[__tid_UnitTestBase__](ue_ue.UnitTest.md#__tid_unittestbase__)

#### Defined in

[ue/ue.d.ts:27523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27523)

___

### \_\_tid\_UnitTest\_\_

• **\_\_tid\_UnitTest\_\_**: `boolean`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[__tid_UnitTest__](ue_ue.UnitTest.md#__tid_unittest__)

#### Defined in

[ue/ue.d.ts:27547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27547)

___

### \_\_tid\_VMReflection\_\_

• **\_\_tid\_VMReflection\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65367)

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

[UnitTest](ue_ue.UnitTest.md).[ExecuteUbergraph](ue_ue.UnitTest.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[GetClass](ue_ue.UnitTest.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[GetName](ue_ue.UnitTest.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[GetOuter](ue_ue.UnitTest.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[UnitTest](ue_ue.UnitTest.md).[GetWorld](ue_ue.UnitTest.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VMReflection`](ue_ue.VMReflection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VMReflection`](ue_ue.VMReflection.md)

#### Overrides

[UnitTest](ue_ue.UnitTest.md).[Find](ue_ue.UnitTest.md#find)

#### Defined in

[ue/ue.d.ts:65364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65364)

___

### Load

▸ `Static` **Load**(`InName`): [`VMReflection`](ue_ue.VMReflection.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VMReflection`](ue_ue.VMReflection.md)

#### Overrides

[UnitTest](ue_ue.UnitTest.md).[Load](ue_ue.UnitTest.md#load)

#### Defined in

[ue/ue.d.ts:65365](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65365)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[UnitTest](ue_ue.UnitTest.md).[StaticClass](ue_ue.UnitTest.md#staticclass)

#### Defined in

[ue/ue.d.ts:65363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65363)
