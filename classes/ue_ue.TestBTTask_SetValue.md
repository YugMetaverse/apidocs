[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TestBTTask\_SetValue

# Class: TestBTTask\_SetValue

[ue/ue](../modules/ue_ue.md).TestBTTask_SetValue

## Hierarchy

- [`BTTaskNode`](ue_ue.BTTaskNode.md)

  ↳ **`TestBTTask_SetValue`**

## Table of contents

### Constructors

- [constructor](ue_ue.TestBTTask_SetValue.md#constructor)

### Properties

- [KeyName](ue_ue.TestBTTask_SetValue.md#keyname)
- [NodeName](ue_ue.TestBTTask_SetValue.md#nodename)
- [ParentNode](ue_ue.TestBTTask_SetValue.md#parentnode)
- [Services](ue_ue.TestBTTask_SetValue.md#services)
- [TaskResult](ue_ue.TestBTTask_SetValue.md#taskresult)
- [TreeAsset](ue_ue.TestBTTask_SetValue.md#treeasset)
- [Value](ue_ue.TestBTTask_SetValue.md#value)
- [\_\_tid\_BTNode\_\_](ue_ue.TestBTTask_SetValue.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.TestBTTask_SetValue.md#__tid_bttasknode__)
- [\_\_tid\_Object\_\_](ue_ue.TestBTTask_SetValue.md#__tid_object__)
- [\_\_tid\_TestBTTask\_SetValue\_\_](ue_ue.TestBTTask_SetValue.md#__tid_testbttask_setvalue__)
- [bIgnoreRestartSelf](ue_ue.TestBTTask_SetValue.md#bignorerestartself)

### Methods

- [CreateDefaultSubobject](ue_ue.TestBTTask_SetValue.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TestBTTask_SetValue.md#executeubergraph)
- [GetClass](ue_ue.TestBTTask_SetValue.md#getclass)
- [GetName](ue_ue.TestBTTask_SetValue.md#getname)
- [GetOuter](ue_ue.TestBTTask_SetValue.md#getouter)
- [GetWorld](ue_ue.TestBTTask_SetValue.md#getworld)
- [Find](ue_ue.TestBTTask_SetValue.md#find)
- [Load](ue_ue.TestBTTask_SetValue.md#load)
- [StaticClass](ue_ue.TestBTTask_SetValue.md#staticclass)

## Constructors

### constructor

• **new TestBTTask_SetValue**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[constructor](ue_ue.BTTaskNode.md#constructor)

## Properties

### KeyName

• **KeyName**: `string`

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[NodeName](ue_ue.BTTaskNode.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[ParentNode](ue_ue.BTTaskNode.md#parentnode)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[Services](ue_ue.BTTaskNode.md#services)

___

### TaskResult

• **TaskResult**: [`EBTNodeResult`](../enums/ue_ue.EBTNodeResult.md)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[TreeAsset](ue_ue.BTTaskNode.md#treeasset)

___

### Value

• **Value**: `number`

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTNode__](ue_ue.BTTaskNode.md#__tid_btnode__)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTTaskNode__](ue_ue.BTTaskNode.md#__tid_bttasknode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_Object__](ue_ue.BTTaskNode.md#__tid_object__)

___

### \_\_tid\_TestBTTask\_SetValue\_\_

• **\_\_tid\_TestBTTask\_SetValue\_\_**: `boolean`

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[bIgnoreRestartSelf](ue_ue.BTTaskNode.md#bignorerestartself)

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

[BTTaskNode](ue_ue.BTTaskNode.md).[CreateDefaultSubobject](ue_ue.BTTaskNode.md#createdefaultsubobject)

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

[BTTaskNode](ue_ue.BTTaskNode.md).[ExecuteUbergraph](ue_ue.BTTaskNode.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetClass](ue_ue.BTTaskNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetName](ue_ue.BTTaskNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetOuter](ue_ue.BTTaskNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetWorld](ue_ue.BTTaskNode.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TestBTTask_SetValue`](ue_ue.TestBTTask_SetValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TestBTTask_SetValue`](ue_ue.TestBTTask_SetValue.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Find](ue_ue.BTTaskNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TestBTTask_SetValue`](ue_ue.TestBTTask_SetValue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TestBTTask_SetValue`](ue_ue.TestBTTask_SetValue.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Load](ue_ue.BTTaskNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[StaticClass](ue_ue.BTTaskNode.md#staticclass)
