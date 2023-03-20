[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AITask

# Class: AITask

[ue/ue](../modules/ue_ue.md).AITask

## Hierarchy

- [`GameplayTask`](ue_ue.GameplayTask.md)

  ↳ **`AITask`**

  ↳↳ [`AITask_LockLogic`](ue_ue.AITask_LockLogic.md)

  ↳↳ [`AITask_MoveTo`](ue_ue.AITask_MoveTo.md)

  ↳↳ [`AITask_RunEQS`](ue_ue.AITask_RunEQS.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AITask.md#constructor)

### Properties

- [ChildTask](ue_ue.AITask.md#childtask)
- [InstanceName](ue_ue.AITask.md#instancename)
- [OwnerController](ue_ue.AITask.md#ownercontroller)
- [ResourceOverlapPolicy](ue_ue.AITask.md#resourceoverlappolicy)
- [\_\_tid\_AITask\_\_](ue_ue.AITask.md#__tid_aitask__)
- [\_\_tid\_GameplayTask\_\_](ue_ue.AITask.md#__tid_gameplaytask__)
- [\_\_tid\_Object\_\_](ue_ue.AITask.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AITask.md#createdefaultsubobject)
- [EndTask](ue_ue.AITask.md#endtask)
- [ExecuteUbergraph](ue_ue.AITask.md#executeubergraph)
- [GenericGameplayTaskDelegate\_\_DelegateSignature](ue_ue.AITask.md#genericgameplaytaskdelegate__delegatesignature)
- [GetClass](ue_ue.AITask.md#getclass)
- [GetName](ue_ue.AITask.md#getname)
- [GetOuter](ue_ue.AITask.md#getouter)
- [GetWorld](ue_ue.AITask.md#getworld)
- [ReadyForActivation](ue_ue.AITask.md#readyforactivation)
- [Find](ue_ue.AITask.md#find)
- [Load](ue_ue.AITask.md#load)
- [StaticClass](ue_ue.AITask.md#staticclass)

## Constructors

### constructor

• **new AITask**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[constructor](ue_ue.GameplayTask.md#constructor)

#### Defined in

[ue/ue.d.ts:16100](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16100)

## Properties

### ChildTask

• **ChildTask**: [`GameplayTask`](ue_ue.GameplayTask.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[ChildTask](ue_ue.GameplayTask.md#childtask)

#### Defined in

[ue/ue.d.ts:14889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14889)

___

### InstanceName

• **InstanceName**: `string`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[InstanceName](ue_ue.GameplayTask.md#instancename)

#### Defined in

[ue/ue.d.ts:14887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14887)

___

### OwnerController

• **OwnerController**: [`AIController`](ue_ue.AIController.md)

#### Defined in

[ue/ue.d.ts:16101](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16101)

___

### ResourceOverlapPolicy

• **ResourceOverlapPolicy**: [`ETaskResourceOverlapPolicy`](../enums/ue_ue.ETaskResourceOverlapPolicy.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[ResourceOverlapPolicy](ue_ue.GameplayTask.md#resourceoverlappolicy)

#### Defined in

[ue/ue.d.ts:14888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14888)

___

### \_\_tid\_AITask\_\_

• **\_\_tid\_AITask\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16106](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16106)

___

### \_\_tid\_GameplayTask\_\_

• **\_\_tid\_GameplayTask\_\_**: `boolean`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[__tid_GameplayTask__](ue_ue.GameplayTask.md#__tid_gameplaytask__)

#### Defined in

[ue/ue.d.ts:14897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14897)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[__tid_Object__](ue_ue.GameplayTask.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[GameplayTask](ue_ue.GameplayTask.md).[CreateDefaultSubobject](ue_ue.GameplayTask.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### EndTask

▸ **EndTask**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[EndTask](ue_ue.GameplayTask.md#endtask)

#### Defined in

[ue/ue.d.ts:14890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14890)

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

[GameplayTask](ue_ue.GameplayTask.md).[ExecuteUbergraph](ue_ue.GameplayTask.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GenericGameplayTaskDelegate\_\_DelegateSignature

▸ **GenericGameplayTaskDelegate__DelegateSignature**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GenericGameplayTaskDelegate__DelegateSignature](ue_ue.GameplayTask.md#genericgameplaytaskdelegate__delegatesignature)

#### Defined in

[ue/ue.d.ts:14891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14891)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GetClass](ue_ue.GameplayTask.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GetName](ue_ue.GameplayTask.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GetOuter](ue_ue.GameplayTask.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GetWorld](ue_ue.GameplayTask.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### ReadyForActivation

▸ **ReadyForActivation**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[ReadyForActivation](ue_ue.GameplayTask.md#readyforactivation)

#### Defined in

[ue/ue.d.ts:14892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14892)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AITask`](ue_ue.AITask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AITask`](ue_ue.AITask.md)

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[Find](ue_ue.GameplayTask.md#find)

#### Defined in

[ue/ue.d.ts:16103](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16103)

___

### Load

▸ `Static` **Load**(`InName`): [`AITask`](ue_ue.AITask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AITask`](ue_ue.AITask.md)

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[Load](ue_ue.GameplayTask.md#load)

#### Defined in

[ue/ue.d.ts:16104](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16104)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[StaticClass](ue_ue.GameplayTask.md#staticclass)

#### Defined in

[ue/ue.d.ts:16102](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16102)
