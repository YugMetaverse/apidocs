[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameplayTask\_WaitDelay

# Class: GameplayTask\_WaitDelay

[ue/ue](../modules/ue_ue.md).GameplayTask_WaitDelay

## Hierarchy

- [`GameplayTask`](ue_ue.GameplayTask.md)

  ↳ **`GameplayTask_WaitDelay`**

## Table of contents

### Constructors

- [constructor](ue_ue.GameplayTask_WaitDelay.md#constructor)

### Properties

- [ChildTask](ue_ue.GameplayTask_WaitDelay.md#childtask)
- [InstanceName](ue_ue.GameplayTask_WaitDelay.md#instancename)
- [OnFinish](ue_ue.GameplayTask_WaitDelay.md#onfinish)
- [ResourceOverlapPolicy](ue_ue.GameplayTask_WaitDelay.md#resourceoverlappolicy)
- [\_\_tid\_GameplayTask\_WaitDelay\_\_](ue_ue.GameplayTask_WaitDelay.md#__tid_gameplaytask_waitdelay__)
- [\_\_tid\_GameplayTask\_\_](ue_ue.GameplayTask_WaitDelay.md#__tid_gameplaytask__)
- [\_\_tid\_Object\_\_](ue_ue.GameplayTask_WaitDelay.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GameplayTask_WaitDelay.md#createdefaultsubobject)
- [EndTask](ue_ue.GameplayTask_WaitDelay.md#endtask)
- [ExecuteUbergraph](ue_ue.GameplayTask_WaitDelay.md#executeubergraph)
- [GenericGameplayTaskDelegate\_\_DelegateSignature](ue_ue.GameplayTask_WaitDelay.md#genericgameplaytaskdelegate__delegatesignature)
- [GetClass](ue_ue.GameplayTask_WaitDelay.md#getclass)
- [GetName](ue_ue.GameplayTask_WaitDelay.md#getname)
- [GetOuter](ue_ue.GameplayTask_WaitDelay.md#getouter)
- [GetWorld](ue_ue.GameplayTask_WaitDelay.md#getworld)
- [ReadyForActivation](ue_ue.GameplayTask_WaitDelay.md#readyforactivation)
- [TaskDelayDelegate\_\_DelegateSignature](ue_ue.GameplayTask_WaitDelay.md#taskdelaydelegate__delegatesignature)
- [Find](ue_ue.GameplayTask_WaitDelay.md#find)
- [Load](ue_ue.GameplayTask_WaitDelay.md#load)
- [StaticClass](ue_ue.GameplayTask_WaitDelay.md#staticclass)
- [TaskWaitDelay](ue_ue.GameplayTask_WaitDelay.md#taskwaitdelay)

## Constructors

### constructor

• **new GameplayTask_WaitDelay**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[constructor](ue_ue.GameplayTask.md#constructor)

## Properties

### ChildTask

• **ChildTask**: [`GameplayTask`](ue_ue.GameplayTask.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[ChildTask](ue_ue.GameplayTask.md#childtask)

___

### InstanceName

• **InstanceName**: `string`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[InstanceName](ue_ue.GameplayTask.md#instancename)

___

### OnFinish

• **OnFinish**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### ResourceOverlapPolicy

• **ResourceOverlapPolicy**: [`ETaskResourceOverlapPolicy`](../enums/ue_ue.ETaskResourceOverlapPolicy.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[ResourceOverlapPolicy](ue_ue.GameplayTask.md#resourceoverlappolicy)

___

### \_\_tid\_GameplayTask\_WaitDelay\_\_

• **\_\_tid\_GameplayTask\_WaitDelay\_\_**: `boolean`

___

### \_\_tid\_GameplayTask\_\_

• **\_\_tid\_GameplayTask\_\_**: `boolean`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[__tid_GameplayTask__](ue_ue.GameplayTask.md#__tid_gameplaytask__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[__tid_Object__](ue_ue.GameplayTask.md#__tid_object__)

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

___

### EndTask

▸ **EndTask**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[EndTask](ue_ue.GameplayTask.md#endtask)

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

___

### GenericGameplayTaskDelegate\_\_DelegateSignature

▸ **GenericGameplayTaskDelegate__DelegateSignature**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GenericGameplayTaskDelegate__DelegateSignature](ue_ue.GameplayTask.md#genericgameplaytaskdelegate__delegatesignature)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GetClass](ue_ue.GameplayTask.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GetName](ue_ue.GameplayTask.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GetOuter](ue_ue.GameplayTask.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[GetWorld](ue_ue.GameplayTask.md#getworld)

___

### ReadyForActivation

▸ **ReadyForActivation**(): `void`

#### Returns

`void`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[ReadyForActivation](ue_ue.GameplayTask.md#readyforactivation)

___

### TaskDelayDelegate\_\_DelegateSignature

▸ **TaskDelayDelegate__DelegateSignature**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameplayTask_WaitDelay`](ue_ue.GameplayTask_WaitDelay.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameplayTask_WaitDelay`](ue_ue.GameplayTask_WaitDelay.md)

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[Find](ue_ue.GameplayTask.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameplayTask_WaitDelay`](ue_ue.GameplayTask_WaitDelay.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameplayTask_WaitDelay`](ue_ue.GameplayTask_WaitDelay.md)

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[Load](ue_ue.GameplayTask.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[StaticClass](ue_ue.GameplayTask.md#staticclass)

___

### TaskWaitDelay

▸ `Static` **TaskWaitDelay**(`TaskOwner`, `Time`, `Priority?`): [`GameplayTask_WaitDelay`](ue_ue.GameplayTask_WaitDelay.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TaskOwner` | [`GameplayTaskOwnerInterface`](ue_ue.GameplayTaskOwnerInterface.md) |
| `Time` | `number` |
| `Priority?` | `number` |

#### Returns

[`GameplayTask_WaitDelay`](ue_ue.GameplayTask_WaitDelay.md)
