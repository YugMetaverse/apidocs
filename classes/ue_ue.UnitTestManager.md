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

#### Defined in

[ue/ue.d.ts:64622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64622)

## Properties

### ActiveUnitTests

• **ActiveUnitTests**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTest`](ue_ue.UnitTest.md)\>

#### Defined in

[ue/ue.d.ts:64631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64631)

___

### AutoCloseMemoryPercent

• **AutoCloseMemoryPercent**: `number`

#### Defined in

[ue/ue.d.ts:64627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64627)

___

### FinishedUnitTests

• **FinishedUnitTests**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`UnitTest`](ue_ue.UnitTest.md)\>

#### Defined in

[ue/ue.d.ts:64632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64632)

___

### MaxAutoCloseCount

• **MaxAutoCloseCount**: `number`

#### Defined in

[ue/ue.d.ts:64628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64628)

___

### MaxMemoryPercent

• **MaxMemoryPercent**: `number`

#### Defined in

[ue/ue.d.ts:64626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64626)

___

### MaxUnitTestCount

• **MaxUnitTestCount**: `number`

#### Defined in

[ue/ue.d.ts:64624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64624)

___

### PendingUnitTests

• **PendingUnitTests**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Class`](ue_ue.Class.md)\>

#### Defined in

[ue/ue.d.ts:64630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64630)

___

### UnitTestSessionCount

• **UnitTestSessionCount**: `number`

#### Defined in

[ue/ue.d.ts:64629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64629)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_UnitTestManager\_\_

• **\_\_tid\_UnitTestManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64637)

___

### bCapUnitTestCount

• **bCapUnitTestCount**: `boolean`

#### Defined in

[ue/ue.d.ts:64623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64623)

___

### bCapUnitTestMemory

• **bCapUnitTestMemory**: `boolean`

#### Defined in

[ue/ue.d.ts:64625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64625)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:64634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64634)

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

#### Defined in

[ue/ue.d.ts:64635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64635)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:64633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64633)
