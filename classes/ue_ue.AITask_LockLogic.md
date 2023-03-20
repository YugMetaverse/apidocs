[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AITask\_LockLogic

# Class: AITask\_LockLogic

[ue/ue](../modules/ue_ue.md).AITask_LockLogic

## Hierarchy

- [`AITask`](ue_ue.AITask.md)

  ↳ **`AITask_LockLogic`**

## Table of contents

### Constructors

- [constructor](ue_ue.AITask_LockLogic.md#constructor)

### Properties

- [ChildTask](ue_ue.AITask_LockLogic.md#childtask)
- [InstanceName](ue_ue.AITask_LockLogic.md#instancename)
- [OwnerController](ue_ue.AITask_LockLogic.md#ownercontroller)
- [ResourceOverlapPolicy](ue_ue.AITask_LockLogic.md#resourceoverlappolicy)
- [\_\_tid\_AITask\_LockLogic\_\_](ue_ue.AITask_LockLogic.md#__tid_aitask_locklogic__)
- [\_\_tid\_AITask\_\_](ue_ue.AITask_LockLogic.md#__tid_aitask__)
- [\_\_tid\_GameplayTask\_\_](ue_ue.AITask_LockLogic.md#__tid_gameplaytask__)
- [\_\_tid\_Object\_\_](ue_ue.AITask_LockLogic.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AITask_LockLogic.md#createdefaultsubobject)
- [EndTask](ue_ue.AITask_LockLogic.md#endtask)
- [ExecuteUbergraph](ue_ue.AITask_LockLogic.md#executeubergraph)
- [GenericGameplayTaskDelegate\_\_DelegateSignature](ue_ue.AITask_LockLogic.md#genericgameplaytaskdelegate__delegatesignature)
- [GetClass](ue_ue.AITask_LockLogic.md#getclass)
- [GetName](ue_ue.AITask_LockLogic.md#getname)
- [GetOuter](ue_ue.AITask_LockLogic.md#getouter)
- [GetWorld](ue_ue.AITask_LockLogic.md#getworld)
- [ReadyForActivation](ue_ue.AITask_LockLogic.md#readyforactivation)
- [Find](ue_ue.AITask_LockLogic.md#find)
- [Load](ue_ue.AITask_LockLogic.md#load)
- [StaticClass](ue_ue.AITask_LockLogic.md#staticclass)

## Constructors

### constructor

• **new AITask_LockLogic**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AITask](ue_ue.AITask.md).[constructor](ue_ue.AITask.md#constructor)

#### Defined in

[ue/ue.d.ts:16110](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16110)

## Properties

### ChildTask

• **ChildTask**: [`GameplayTask`](ue_ue.GameplayTask.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[ChildTask](ue_ue.AITask.md#childtask)

#### Defined in

[ue/ue.d.ts:14889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14889)

___

### InstanceName

• **InstanceName**: `string`

#### Inherited from

[AITask](ue_ue.AITask.md).[InstanceName](ue_ue.AITask.md#instancename)

#### Defined in

[ue/ue.d.ts:14887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14887)

___

### OwnerController

• **OwnerController**: [`AIController`](ue_ue.AIController.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[OwnerController](ue_ue.AITask.md#ownercontroller)

#### Defined in

[ue/ue.d.ts:16101](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16101)

___

### ResourceOverlapPolicy

• **ResourceOverlapPolicy**: [`ETaskResourceOverlapPolicy`](../enums/ue_ue.ETaskResourceOverlapPolicy.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[ResourceOverlapPolicy](ue_ue.AITask.md#resourceoverlappolicy)

#### Defined in

[ue/ue.d.ts:14888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14888)

___

### \_\_tid\_AITask\_LockLogic\_\_

• **\_\_tid\_AITask\_LockLogic\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16115)

___

### \_\_tid\_AITask\_\_

• **\_\_tid\_AITask\_\_**: `boolean`

#### Inherited from

[AITask](ue_ue.AITask.md).[__tid_AITask__](ue_ue.AITask.md#__tid_aitask__)

#### Defined in

[ue/ue.d.ts:16106](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16106)

___

### \_\_tid\_GameplayTask\_\_

• **\_\_tid\_GameplayTask\_\_**: `boolean`

#### Inherited from

[AITask](ue_ue.AITask.md).[__tid_GameplayTask__](ue_ue.AITask.md#__tid_gameplaytask__)

#### Defined in

[ue/ue.d.ts:14897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14897)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AITask](ue_ue.AITask.md).[__tid_Object__](ue_ue.AITask.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[AITask](ue_ue.AITask.md).[CreateDefaultSubobject](ue_ue.AITask.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### EndTask

▸ **EndTask**(): `void`

#### Returns

`void`

#### Inherited from

[AITask](ue_ue.AITask.md).[EndTask](ue_ue.AITask.md#endtask)

#### Defined in

[ue/ue.d.ts:14890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14890)

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

[AITask](ue_ue.AITask.md).[ExecuteUbergraph](ue_ue.AITask.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GenericGameplayTaskDelegate\_\_DelegateSignature

▸ **GenericGameplayTaskDelegate__DelegateSignature**(): `void`

#### Returns

`void`

#### Inherited from

[AITask](ue_ue.AITask.md).[GenericGameplayTaskDelegate__DelegateSignature](ue_ue.AITask.md#genericgameplaytaskdelegate__delegatesignature)

#### Defined in

[ue/ue.d.ts:14891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14891)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[GetClass](ue_ue.AITask.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AITask](ue_ue.AITask.md).[GetName](ue_ue.AITask.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[GetOuter](ue_ue.AITask.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[GetWorld](ue_ue.AITask.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### ReadyForActivation

▸ **ReadyForActivation**(): `void`

#### Returns

`void`

#### Inherited from

[AITask](ue_ue.AITask.md).[ReadyForActivation](ue_ue.AITask.md#readyforactivation)

#### Defined in

[ue/ue.d.ts:14892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14892)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AITask_LockLogic`](ue_ue.AITask_LockLogic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AITask_LockLogic`](ue_ue.AITask_LockLogic.md)

#### Overrides

[AITask](ue_ue.AITask.md).[Find](ue_ue.AITask.md#find)

#### Defined in

[ue/ue.d.ts:16112](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16112)

___

### Load

▸ `Static` **Load**(`InName`): [`AITask_LockLogic`](ue_ue.AITask_LockLogic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AITask_LockLogic`](ue_ue.AITask_LockLogic.md)

#### Overrides

[AITask](ue_ue.AITask.md).[Load](ue_ue.AITask.md#load)

#### Defined in

[ue/ue.d.ts:16113](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16113)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AITask](ue_ue.AITask.md).[StaticClass](ue_ue.AITask.md#staticclass)

#### Defined in

[ue/ue.d.ts:16111](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16111)
