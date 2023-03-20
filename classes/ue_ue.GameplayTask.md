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

#### Defined in

[ue/ue.d.ts:14886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14886)

## Properties

### ChildTask

• **ChildTask**: [`GameplayTask`](ue_ue.GameplayTask.md)

#### Defined in

[ue/ue.d.ts:14889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14889)

___

### InstanceName

• **InstanceName**: `string`

#### Defined in

[ue/ue.d.ts:14887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14887)

___

### ResourceOverlapPolicy

• **ResourceOverlapPolicy**: [`ETaskResourceOverlapPolicy`](../enums/ue_ue.ETaskResourceOverlapPolicy.md)

#### Defined in

[ue/ue.d.ts:14888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14888)

___

### \_\_tid\_GameplayTask\_\_

• **\_\_tid\_GameplayTask\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14897)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### EndTask

▸ **EndTask**(): `void`

#### Returns

`void`

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GenericGameplayTaskDelegate\_\_DelegateSignature

▸ **GenericGameplayTaskDelegate__DelegateSignature**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14891)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### ReadyForActivation

▸ **ReadyForActivation**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14892)

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

#### Defined in

[ue/ue.d.ts:14894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14894)

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

#### Defined in

[ue/ue.d.ts:14895](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14895)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:14893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14893)
