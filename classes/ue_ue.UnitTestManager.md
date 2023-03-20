[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UnitTestManager

# Class: UnitTestManager

[ue/ue](../modules/ue_ue.md).UnitTestManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`UnitTestManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.UnitTestManager.md#constructor)

### Properties

- [ActiveUnitTests](ue_ue.UnitTestManager.md#activeunittests)
- [AutoCloseMemoryPercent](ue_ue.UnitTestManager.md#autoclosememorypercent)
- [FinishedUnitTests](ue_ue.UnitTestManager.md#finishedunittests)
- [MaxAutoCloseCount](ue_ue.UnitTestManager.md#maxautoclosecount)
- [MaxMemoryPercent](ue_ue.UnitTestManager.md#maxmemorypercent)
- [MaxUnitTestCount](ue_ue.UnitTestManager.md#maxunittestcount)
- [PendingUnitTests](ue_ue.UnitTestManager.md#pendingunittests)
- [UnitTestSessionCount](ue_ue.UnitTestManager.md#unittestsessioncount)
- [\_\_tid\_Object\_\_](ue_ue.UnitTestManager.md#__tid_object__)
- [\_\_tid\_UnitTestManager\_\_](ue_ue.UnitTestManager.md#__tid_unittestmanager__)
- [bCapUnitTestCount](ue_ue.UnitTestManager.md#bcapunittestcount)
- [bCapUnitTestMemory](ue_ue.UnitTestManager.md#bcapunittestmemory)

### Methods

- [CreateDefaultSubobject](ue_ue.UnitTestManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UnitTestManager.md#executeubergraph)
- [GetClass](ue_ue.UnitTestManager.md#getclass)
- [GetName](ue_ue.UnitTestManager.md#getname)
- [GetOuter](ue_ue.UnitTestManager.md#getouter)
- [GetWorld](ue_ue.UnitTestManager.md#getworld)
- [Find](ue_ue.UnitTestManager.md#find)
- [Load](ue_ue.UnitTestManager.md#load)
- [StaticClass](ue_ue.UnitTestManager.md#staticclass)

## Constructors

### constructor

• **new UnitTestManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ActiveUnitTests

• **ActiveUnitTests**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTest`](ue_ue.UnitTest.md)\>

___

### AutoCloseMemoryPercent

• **AutoCloseMemoryPercent**: `number`

___

### FinishedUnitTests

• **FinishedUnitTests**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTest`](ue_ue.UnitTest.md)\>

___

### MaxAutoCloseCount

• **MaxAutoCloseCount**: `number`

___

### MaxMemoryPercent

• **MaxMemoryPercent**: `number`

___

### MaxUnitTestCount

• **MaxUnitTestCount**: `number`

___

### PendingUnitTests

• **PendingUnitTests**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\>

___

### UnitTestSessionCount

• **UnitTestSessionCount**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_UnitTestManager\_\_

• **\_\_tid\_UnitTestManager\_\_**: `boolean`

___

### bCapUnitTestCount

• **bCapUnitTestCount**: `boolean`

___

### bCapUnitTestMemory

• **bCapUnitTestMemory**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UnitTestManager`](ue_ue.UnitTestManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UnitTestManager`](ue_ue.UnitTestManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UnitTestManager`](ue_ue.UnitTestManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UnitTestManager`](ue_ue.UnitTestManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
