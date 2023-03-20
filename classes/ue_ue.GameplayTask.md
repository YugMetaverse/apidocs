[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameplayTask

# Class: GameplayTask

[ue/ue](../modules/ue_ue.md).GameplayTask

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GameplayTask`**

  ↳↳ [`AITask`](ue_ue.AITask.md)

  ↳↳ [`GameplayTask_ClaimResource`](ue_ue.GameplayTask_ClaimResource.md)

  ↳↳ [`GameplayTask_SpawnActor`](ue_ue.GameplayTask_SpawnActor.md)

  ↳↳ [`GameplayTask_TimeLimitedExecution`](ue_ue.GameplayTask_TimeLimitedExecution.md)

  ↳↳ [`GameplayTask_WaitDelay`](ue_ue.GameplayTask_WaitDelay.md)

  ↳↳ [`MockTask_Log`](ue_ue.MockTask_Log.md)

## Table of contents

### Constructors

- [constructor](ue_ue.GameplayTask.md#constructor)

### Properties

- [ChildTask](ue_ue.GameplayTask.md#childtask)
- [InstanceName](ue_ue.GameplayTask.md#instancename)
- [ResourceOverlapPolicy](ue_ue.GameplayTask.md#resourceoverlappolicy)
- [\_\_tid\_GameplayTask\_\_](ue_ue.GameplayTask.md#__tid_gameplaytask__)
- [\_\_tid\_Object\_\_](ue_ue.GameplayTask.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GameplayTask.md#createdefaultsubobject)
- [EndTask](ue_ue.GameplayTask.md#endtask)
- [ExecuteUbergraph](ue_ue.GameplayTask.md#executeubergraph)
- [GenericGameplayTaskDelegate\_\_DelegateSignature](ue_ue.GameplayTask.md#genericgameplaytaskdelegate__delegatesignature)
- [GetClass](ue_ue.GameplayTask.md#getclass)
- [GetName](ue_ue.GameplayTask.md#getname)
- [GetOuter](ue_ue.GameplayTask.md#getouter)
- [GetWorld](ue_ue.GameplayTask.md#getworld)
- [ReadyForActivation](ue_ue.GameplayTask.md#readyforactivation)
- [Find](ue_ue.GameplayTask.md#find)
- [Load](ue_ue.GameplayTask.md#load)
- [StaticClass](ue_ue.GameplayTask.md#staticclass)

## Constructors

### constructor

• **new GameplayTask**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ChildTask

• **ChildTask**: [`GameplayTask`](ue_ue.GameplayTask.md)

___

### InstanceName

• **InstanceName**: `string`

___

### ResourceOverlapPolicy

• **ResourceOverlapPolicy**: [`ETaskResourceOverlapPolicy`](../enums/ue_ue.ETaskResourceOverlapPolicy.md)

___

### \_\_tid\_GameplayTask\_\_

• **\_\_tid\_GameplayTask\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### EndTask

▸ **EndTask**(): `void`

#### Returns

`void`

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

### GenericGameplayTaskDelegate\_\_DelegateSignature

▸ **GenericGameplayTaskDelegate__DelegateSignature**(): `void`

#### Returns

`void`

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

### ReadyForActivation

▸ **ReadyForActivation**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameplayTask`](ue_ue.GameplayTask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameplayTask`](ue_ue.GameplayTask.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameplayTask`](ue_ue.GameplayTask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameplayTask`](ue_ue.GameplayTask.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
