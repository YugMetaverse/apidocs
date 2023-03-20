[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIBlueprintHelperLibrary

# Class: AIBlueprintHelperLibrary

[ue/ue](../modules/ue_ue.md).AIBlueprintHelperLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`AIBlueprintHelperLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.AIBlueprintHelperLibrary.md#constructor)

### Properties

- [\_\_tid\_AIBlueprintHelperLibrary\_\_](ue_ue.AIBlueprintHelperLibrary.md#__tid_aiblueprinthelperlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.AIBlueprintHelperLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.AIBlueprintHelperLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AIBlueprintHelperLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AIBlueprintHelperLibrary.md#executeubergraph)
- [GetClass](ue_ue.AIBlueprintHelperLibrary.md#getclass)
- [GetName](ue_ue.AIBlueprintHelperLibrary.md#getname)
- [GetOuter](ue_ue.AIBlueprintHelperLibrary.md#getouter)
- [GetWorld](ue_ue.AIBlueprintHelperLibrary.md#getworld)
- [CreateMoveToProxyObject](ue_ue.AIBlueprintHelperLibrary.md#createmovetoproxyobject)
- [Find](ue_ue.AIBlueprintHelperLibrary.md#find)
- [GetAIController](ue_ue.AIBlueprintHelperLibrary.md#getaicontroller)
- [GetBlackboard](ue_ue.AIBlueprintHelperLibrary.md#getblackboard)
- [GetCurrentPath](ue_ue.AIBlueprintHelperLibrary.md#getcurrentpath)
- [IsValidAIDirection](ue_ue.AIBlueprintHelperLibrary.md#isvalidaidirection)
- [IsValidAILocation](ue_ue.AIBlueprintHelperLibrary.md#isvalidailocation)
- [IsValidAIRotation](ue_ue.AIBlueprintHelperLibrary.md#isvalidairotation)
- [Load](ue_ue.AIBlueprintHelperLibrary.md#load)
- [LockAIResourcesWithAnimation](ue_ue.AIBlueprintHelperLibrary.md#lockairesourceswithanimation)
- [SendAIMessage](ue_ue.AIBlueprintHelperLibrary.md#sendaimessage)
- [SimpleMoveToActor](ue_ue.AIBlueprintHelperLibrary.md#simplemovetoactor)
- [SimpleMoveToLocation](ue_ue.AIBlueprintHelperLibrary.md#simplemovetolocation)
- [SpawnAIFromClass](ue_ue.AIBlueprintHelperLibrary.md#spawnaifromclass)
- [StaticClass](ue_ue.AIBlueprintHelperLibrary.md#staticclass)
- [UnlockAIResourcesWithAnimation](ue_ue.AIBlueprintHelperLibrary.md#unlockairesourceswithanimation)

## Constructors

### constructor

• **new AIBlueprintHelperLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:15035](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15035)

## Properties

### \_\_tid\_AIBlueprintHelperLibrary\_\_

• **\_\_tid\_AIBlueprintHelperLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15053](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15053)

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### CreateMoveToProxyObject

▸ `Static` **CreateMoveToProxyObject**(`WorldContextObject`, `Pawn`, `Destination`, `TargetActor?`, `AcceptanceRadius?`, `bStopOnOverlap?`): [`AIAsyncTaskBlueprintProxy`](ue_ue.AIAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Pawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |
| `Destination` | [`Vector`](ue_ue_s.Vector.md) |
| `TargetActor?` | [`Actor`](ue_ue.Actor.md) |
| `AcceptanceRadius?` | `number` |
| `bStopOnOverlap?` | `boolean` |

#### Returns

[`AIAsyncTaskBlueprintProxy`](ue_ue.AIAsyncTaskBlueprintProxy.md)

#### Defined in

[ue/ue.d.ts:15036](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15036)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AIBlueprintHelperLibrary`](ue_ue.AIBlueprintHelperLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AIBlueprintHelperLibrary`](ue_ue.AIBlueprintHelperLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:15050](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15050)

___

### GetAIController

▸ `Static` **GetAIController**(`ControlledActor`): [`AIController`](ue_ue.AIController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControlledActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

[`AIController`](ue_ue.AIController.md)

#### Defined in

[ue/ue.d.ts:15037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15037)

___

### GetBlackboard

▸ `Static` **GetBlackboard**(`Target`): [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

[`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Defined in

[ue/ue.d.ts:15038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15038)

___

### GetCurrentPath

▸ `Static` **GetCurrentPath**(`Controller`): [`NavigationPath`](ue_ue.NavigationPath.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Controller` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |

#### Returns

[`NavigationPath`](ue_ue.NavigationPath.md)

#### Defined in

[ue/ue.d.ts:15039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15039)

___

### IsValidAIDirection

▸ `Static` **IsValidAIDirection**(`DirectionVector`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DirectionVector` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:15040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15040)

___

### IsValidAILocation

▸ `Static` **IsValidAILocation**(`Location`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:15041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15041)

___

### IsValidAIRotation

▸ `Static` **IsValidAIRotation**(`Rotation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:15042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15042)

___

### Load

▸ `Static` **Load**(`InName`): [`AIBlueprintHelperLibrary`](ue_ue.AIBlueprintHelperLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AIBlueprintHelperLibrary`](ue_ue.AIBlueprintHelperLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:15051](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15051)

___

### LockAIResourcesWithAnimation

▸ `Static` **LockAIResourcesWithAnimation**(`AnimInstance`, `bLockMovement`, `LockAILogic`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimInstance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimInstance`](ue_ue.AnimInstance.md)\> |
| `bLockMovement` | `boolean` |
| `LockAILogic` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15043)

___

### SendAIMessage

▸ `Static` **SendAIMessage**(`Target`, `Message`, `MessageSource`, `bSuccess?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Target` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |
| `Message` | `string` |
| `MessageSource` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `bSuccess?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15044)

___

### SimpleMoveToActor

▸ `Static` **SimpleMoveToActor**(`Controller`, `Goal`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Controller` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `Goal` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15045)

___

### SimpleMoveToLocation

▸ `Static` **SimpleMoveToLocation**(`Controller`, `Goal`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Controller` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `Goal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15046](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15046)

___

### SpawnAIFromClass

▸ `Static` **SpawnAIFromClass**(`WorldContextObject`, `PawnClass`, `BehaviorTree`, `Location`, `Rotation?`, `bNoCollisionFail?`): [`Pawn`](ue_ue.Pawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PawnClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `BehaviorTree` | [`$Nullable`](../modules/puerts.md#$nullable)<[`BehaviorTree`](ue_ue.BehaviorTree.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bNoCollisionFail?` | `boolean` |

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Defined in

[ue/ue.d.ts:15047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15047)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:15049](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15049)

___

### UnlockAIResourcesWithAnimation

▸ `Static` **UnlockAIResourcesWithAnimation**(`AnimInstance`, `bUnlockMovement`, `UnlockAILogic`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimInstance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimInstance`](ue_ue.AnimInstance.md)\> |
| `bUnlockMovement` | `boolean` |
| `UnlockAILogic` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15048](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15048)
