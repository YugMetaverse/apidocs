[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AITask\_MoveTo

# Class: AITask\_MoveTo

[ue/ue](../modules/ue_ue.md).AITask_MoveTo

## Hierarchy

- [`AITask`](ue_ue.AITask.md)

  ↳ **`AITask_MoveTo`**

## Table of contents

### Constructors

- [constructor](ue_ue.AITask_MoveTo.md#constructor)

### Properties

- [ChildTask](ue_ue.AITask_MoveTo.md#childtask)
- [InstanceName](ue_ue.AITask_MoveTo.md#instancename)
- [MoveRequest](ue_ue.AITask_MoveTo.md#moverequest)
- [OnMoveFinished](ue_ue.AITask_MoveTo.md#onmovefinished)
- [OnRequestFailed](ue_ue.AITask_MoveTo.md#onrequestfailed)
- [OwnerController](ue_ue.AITask_MoveTo.md#ownercontroller)
- [ResourceOverlapPolicy](ue_ue.AITask_MoveTo.md#resourceoverlappolicy)
- [\_\_tid\_AITask\_MoveTo\_\_](ue_ue.AITask_MoveTo.md#__tid_aitask_moveto__)
- [\_\_tid\_AITask\_\_](ue_ue.AITask_MoveTo.md#__tid_aitask__)
- [\_\_tid\_GameplayTask\_\_](ue_ue.AITask_MoveTo.md#__tid_gameplaytask__)
- [\_\_tid\_Object\_\_](ue_ue.AITask_MoveTo.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AITask_MoveTo.md#createdefaultsubobject)
- [EndTask](ue_ue.AITask_MoveTo.md#endtask)
- [ExecuteUbergraph](ue_ue.AITask_MoveTo.md#executeubergraph)
- [GenericGameplayTaskDelegate\_\_DelegateSignature](ue_ue.AITask_MoveTo.md#genericgameplaytaskdelegate__delegatesignature)
- [GetClass](ue_ue.AITask_MoveTo.md#getclass)
- [GetName](ue_ue.AITask_MoveTo.md#getname)
- [GetOuter](ue_ue.AITask_MoveTo.md#getouter)
- [GetWorld](ue_ue.AITask_MoveTo.md#getworld)
- [ReadyForActivation](ue_ue.AITask_MoveTo.md#readyforactivation)
- [AIMoveTo](ue_ue.AITask_MoveTo.md#aimoveto)
- [Find](ue_ue.AITask_MoveTo.md#find)
- [Load](ue_ue.AITask_MoveTo.md#load)
- [StaticClass](ue_ue.AITask_MoveTo.md#staticclass)

## Constructors

### constructor

• **new AITask_MoveTo**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AITask](ue_ue.AITask.md).[constructor](ue_ue.AITask.md#constructor)

#### Defined in

[ue/ue.d.ts:16132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16132)

## Properties

### ChildTask

• **ChildTask**: [`GameplayTask`](ue_ue.GameplayTask.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[ChildTask](ue_ue.AITask.md#childtask)

#### Defined in

[ue/ue.d.ts:14889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14889)

___

### InstanceName

• **InstanceName**: `string`

#### Inherited from

[AITask](ue_ue.AITask.md).[InstanceName](ue_ue.AITask.md#instancename)

#### Defined in

[ue/ue.d.ts:14887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14887)

___

### MoveRequest

• **MoveRequest**: [`AIMoveRequest`](ue_ue.AIMoveRequest.md)

#### Defined in

[ue/ue.d.ts:16135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16135)

___

### OnMoveFinished

• **OnMoveFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Result`: [`EPathFollowingResult`](../enums/ue_ue.EPathFollowingResult.md), `AIController`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:16134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16134)

___

### OnRequestFailed

• **OnRequestFailed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:16133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16133)

___

### OwnerController

• **OwnerController**: [`AIController`](ue_ue.AIController.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[OwnerController](ue_ue.AITask.md#ownercontroller)

#### Defined in

[ue/ue.d.ts:16101](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16101)

___

### ResourceOverlapPolicy

• **ResourceOverlapPolicy**: [`ETaskResourceOverlapPolicy`](../enums/ue_ue.ETaskResourceOverlapPolicy.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[ResourceOverlapPolicy](ue_ue.AITask.md#resourceoverlappolicy)

#### Defined in

[ue/ue.d.ts:14888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14888)

___

### \_\_tid\_AITask\_MoveTo\_\_

• **\_\_tid\_AITask\_MoveTo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16141)

___

### \_\_tid\_AITask\_\_

• **\_\_tid\_AITask\_\_**: `boolean`

#### Inherited from

[AITask](ue_ue.AITask.md).[__tid_AITask__](ue_ue.AITask.md#__tid_aitask__)

#### Defined in

[ue/ue.d.ts:16106](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16106)

___

### \_\_tid\_GameplayTask\_\_

• **\_\_tid\_GameplayTask\_\_**: `boolean`

#### Inherited from

[AITask](ue_ue.AITask.md).[__tid_GameplayTask__](ue_ue.AITask.md#__tid_gameplaytask__)

#### Defined in

[ue/ue.d.ts:14897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14897)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AITask](ue_ue.AITask.md).[__tid_Object__](ue_ue.AITask.md#__tid_object__)

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

[AITask](ue_ue.AITask.md).[CreateDefaultSubobject](ue_ue.AITask.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### EndTask

▸ **EndTask**(): `void`

#### Returns

`void`

#### Inherited from

[AITask](ue_ue.AITask.md).[EndTask](ue_ue.AITask.md#endtask)

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

[AITask](ue_ue.AITask.md).[ExecuteUbergraph](ue_ue.AITask.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GenericGameplayTaskDelegate\_\_DelegateSignature

▸ **GenericGameplayTaskDelegate__DelegateSignature**(): `void`

#### Returns

`void`

#### Inherited from

[AITask](ue_ue.AITask.md).[GenericGameplayTaskDelegate__DelegateSignature](ue_ue.AITask.md#genericgameplaytaskdelegate__delegatesignature)

#### Defined in

[ue/ue.d.ts:14891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14891)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[GetClass](ue_ue.AITask.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AITask](ue_ue.AITask.md).[GetName](ue_ue.AITask.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[GetOuter](ue_ue.AITask.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AITask](ue_ue.AITask.md).[GetWorld](ue_ue.AITask.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### ReadyForActivation

▸ **ReadyForActivation**(): `void`

#### Returns

`void`

#### Inherited from

[AITask](ue_ue.AITask.md).[ReadyForActivation](ue_ue.AITask.md#readyforactivation)

#### Defined in

[ue/ue.d.ts:14892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14892)

___

### AIMoveTo

▸ `Static` **AIMoveTo**(`Controller`, `GoalLocation`, `GoalActor?`, `AcceptanceRadius?`, `StopOnOverlap?`, `AcceptPartialPath?`, `bUsePathfinding?`, `bLockAILogic?`, `bUseContinuosGoalTracking?`, `ProjectGoalOnNavigation?`): [`AITask_MoveTo`](ue_ue.AITask_MoveTo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Controller` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `GoalLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `GoalActor?` | [`Actor`](ue_ue.Actor.md) |
| `AcceptanceRadius?` | `number` |
| `StopOnOverlap?` | [`EAIOptionFlag`](../enums/ue_ue.EAIOptionFlag.md) |
| `AcceptPartialPath?` | [`EAIOptionFlag`](../enums/ue_ue.EAIOptionFlag.md) |
| `bUsePathfinding?` | `boolean` |
| `bLockAILogic?` | `boolean` |
| `bUseContinuosGoalTracking?` | `boolean` |
| `ProjectGoalOnNavigation?` | [`EAIOptionFlag`](../enums/ue_ue.EAIOptionFlag.md) |

#### Returns

[`AITask_MoveTo`](ue_ue.AITask_MoveTo.md)

#### Defined in

[ue/ue.d.ts:16136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16136)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AITask_MoveTo`](ue_ue.AITask_MoveTo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AITask_MoveTo`](ue_ue.AITask_MoveTo.md)

#### Overrides

[AITask](ue_ue.AITask.md).[Find](ue_ue.AITask.md#find)

#### Defined in

[ue/ue.d.ts:16138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16138)

___

### Load

▸ `Static` **Load**(`InName`): [`AITask_MoveTo`](ue_ue.AITask_MoveTo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AITask_MoveTo`](ue_ue.AITask_MoveTo.md)

#### Overrides

[AITask](ue_ue.AITask.md).[Load](ue_ue.AITask.md#load)

#### Defined in

[ue/ue.d.ts:16139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16139)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AITask](ue_ue.AITask.md).[StaticClass](ue_ue.AITask.md#staticclass)

#### Defined in

[ue/ue.d.ts:16137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16137)
