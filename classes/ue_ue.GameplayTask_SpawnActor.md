[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameplayTask\_SpawnActor

# Class: GameplayTask\_SpawnActor

[ue/ue](../modules/ue_ue.md).GameplayTask_SpawnActor

## Hierarchy

- [`GameplayTask`](ue_ue.GameplayTask.md)

  ↳ **`GameplayTask_SpawnActor`**

## Table of contents

### Constructors

- [constructor](ue_ue.GameplayTask_SpawnActor.md#constructor)

### Properties

- [ChildTask](ue_ue.GameplayTask_SpawnActor.md#childtask)
- [ClassToSpawn](ue_ue.GameplayTask_SpawnActor.md#classtospawn)
- [DidNotSpawn](ue_ue.GameplayTask_SpawnActor.md#didnotspawn)
- [InstanceName](ue_ue.GameplayTask_SpawnActor.md#instancename)
- [ResourceOverlapPolicy](ue_ue.GameplayTask_SpawnActor.md#resourceoverlappolicy)
- [Success](ue_ue.GameplayTask_SpawnActor.md#success)
- [\_\_tid\_GameplayTask\_SpawnActor\_\_](ue_ue.GameplayTask_SpawnActor.md#__tid_gameplaytask_spawnactor__)
- [\_\_tid\_GameplayTask\_\_](ue_ue.GameplayTask_SpawnActor.md#__tid_gameplaytask__)
- [\_\_tid\_Object\_\_](ue_ue.GameplayTask_SpawnActor.md#__tid_object__)

### Methods

- [BeginSpawningActor](ue_ue.GameplayTask_SpawnActor.md#beginspawningactor)
- [CreateDefaultSubobject](ue_ue.GameplayTask_SpawnActor.md#createdefaultsubobject)
- [EndTask](ue_ue.GameplayTask_SpawnActor.md#endtask)
- [ExecuteUbergraph](ue_ue.GameplayTask_SpawnActor.md#executeubergraph)
- [FinishSpawningActor](ue_ue.GameplayTask_SpawnActor.md#finishspawningactor)
- [GenericGameplayTaskDelegate\_\_DelegateSignature](ue_ue.GameplayTask_SpawnActor.md#genericgameplaytaskdelegate__delegatesignature)
- [GetClass](ue_ue.GameplayTask_SpawnActor.md#getclass)
- [GetName](ue_ue.GameplayTask_SpawnActor.md#getname)
- [GetOuter](ue_ue.GameplayTask_SpawnActor.md#getouter)
- [GetWorld](ue_ue.GameplayTask_SpawnActor.md#getworld)
- [ReadyForActivation](ue_ue.GameplayTask_SpawnActor.md#readyforactivation)
- [Find](ue_ue.GameplayTask_SpawnActor.md#find)
- [Load](ue_ue.GameplayTask_SpawnActor.md#load)
- [SpawnActor](ue_ue.GameplayTask_SpawnActor.md#spawnactor)
- [StaticClass](ue_ue.GameplayTask_SpawnActor.md#staticclass)

## Constructors

### constructor

• **new GameplayTask_SpawnActor**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### ClassToSpawn

• **ClassToSpawn**: [`Class`](ue_ue.Class.md)

___

### DidNotSpawn

• **DidNotSpawn**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SpawnedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### InstanceName

• **InstanceName**: `string`

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[InstanceName](ue_ue.GameplayTask.md#instancename)

___

### ResourceOverlapPolicy

• **ResourceOverlapPolicy**: [`ETaskResourceOverlapPolicy`](../enums/ue_ue.ETaskResourceOverlapPolicy.md)

#### Inherited from

[GameplayTask](ue_ue.GameplayTask.md).[ResourceOverlapPolicy](ue_ue.GameplayTask.md#resourceoverlappolicy)

___

### Success

• **Success**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SpawnedActor`: [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\>) => `void`\>

___

### \_\_tid\_GameplayTask\_SpawnActor\_\_

• **\_\_tid\_GameplayTask\_SpawnActor\_\_**: `boolean`

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

### BeginSpawningActor

▸ **BeginSpawningActor**(`WorldContextObject`, `SpawnedActor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SpawnedActor` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

___

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

### FinishSpawningActor

▸ **FinishSpawningActor**(`WorldContextObject`, `SpawnedActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SpawnedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameplayTask_SpawnActor`](ue_ue.GameplayTask_SpawnActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameplayTask_SpawnActor`](ue_ue.GameplayTask_SpawnActor.md)

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[Find](ue_ue.GameplayTask.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameplayTask_SpawnActor`](ue_ue.GameplayTask_SpawnActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameplayTask_SpawnActor`](ue_ue.GameplayTask_SpawnActor.md)

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[Load](ue_ue.GameplayTask.md#load)

___

### SpawnActor

▸ `Static` **SpawnActor**(`TaskOwner`, `SpawnLocation`, `SpawnRotation`, `Class`, `bSpawnOnlyOnAuthority?`): [`GameplayTask_SpawnActor`](ue_ue.GameplayTask_SpawnActor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TaskOwner` | [`GameplayTaskOwnerInterface`](ue_ue.GameplayTaskOwnerInterface.md) |
| `SpawnLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `SpawnRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Class` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `bSpawnOnlyOnAuthority?` | `boolean` |

#### Returns

[`GameplayTask_SpawnActor`](ue_ue.GameplayTask_SpawnActor.md)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameplayTask](ue_ue.GameplayTask.md).[StaticClass](ue_ue.GameplayTask.md#staticclass)
