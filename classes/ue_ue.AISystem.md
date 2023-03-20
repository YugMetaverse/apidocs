[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AISystem

# Class: AISystem

[ue/ue](../modules/ue_ue.md).AISystem

## Hierarchy

- [`AISystemBase`](ue_ue.AISystemBase.md)

  ↳ **`AISystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.AISystem.md#constructor)

### Properties

- [AISystemClassName](ue_ue.AISystem.md#aisystemclassname)
- [AISystemModuleName](ue_ue.AISystem.md#aisystemmodulename)
- [AcceptanceRadius](ue_ue.AISystem.md#acceptanceradius)
- [AllProxyObjects](ue_ue.AISystem.md#allproxyobjects)
- [BehaviorTreeManager](ue_ue.AISystem.md#behaviortreemanager)
- [DefaultSightCollisionChannel](ue_ue.AISystem.md#defaultsightcollisionchannel)
- [EnvironmentQueryManager](ue_ue.AISystem.md#environmentquerymanager)
- [HotSpotManager](ue_ue.AISystem.md#hotspotmanager)
- [HotSpotManagerClassName](ue_ue.AISystem.md#hotspotmanagerclassname)
- [NavLocalGrids](ue_ue.AISystem.md#navlocalgrids)
- [PathfollowingNavLinkAcceptanceRadius](ue_ue.AISystem.md#pathfollowingnavlinkacceptanceradius)
- [PathfollowingRegularPathPointAcceptanceRadius](ue_ue.AISystem.md#pathfollowingregularpathpointacceptanceradius)
- [PerceptionSystem](ue_ue.AISystem.md#perceptionsystem)
- [PerceptionSystemClassName](ue_ue.AISystem.md#perceptionsystemclassname)
- [\_\_tid\_AISystemBase\_\_](ue_ue.AISystem.md#__tid_aisystembase__)
- [\_\_tid\_AISystem\_\_](ue_ue.AISystem.md#__tid_aisystem__)
- [\_\_tid\_Object\_\_](ue_ue.AISystem.md#__tid_object__)
- [bAcceptPartialPaths](ue_ue.AISystem.md#bacceptpartialpaths)
- [bAllowControllersAsEQSQuerier](ue_ue.AISystem.md#ballowcontrollersaseqsquerier)
- [bAllowStrafing](ue_ue.AISystem.md#ballowstrafing)
- [bEnableBTAITasks](ue_ue.AISystem.md#benablebtaitasks)
- [bEnableDebuggerPlugin](ue_ue.AISystem.md#benabledebuggerplugin)
- [bFinishMoveOnGoalOverlap](ue_ue.AISystem.md#bfinishmoveongoaloverlap)
- [bInstantiateAISystemOnClient](ue_ue.AISystem.md#binstantiateaisystemonclient)

### Methods

- [AIIgnorePlayers](ue_ue.AISystem.md#aiignoreplayers)
- [AILoggingVerbose](ue_ue.AISystem.md#ailoggingverbose)
- [CreateDefaultSubobject](ue_ue.AISystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AISystem.md#executeubergraph)
- [GetClass](ue_ue.AISystem.md#getclass)
- [GetName](ue_ue.AISystem.md#getname)
- [GetOuter](ue_ue.AISystem.md#getouter)
- [GetWorld](ue_ue.AISystem.md#getworld)
- [Find](ue_ue.AISystem.md#find)
- [Load](ue_ue.AISystem.md#load)
- [StaticClass](ue_ue.AISystem.md#staticclass)

## Constructors

### constructor

• **new AISystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AISystemBase](ue_ue.AISystemBase.md).[constructor](ue_ue.AISystemBase.md#constructor)

## Properties

### AISystemClassName

• **AISystemClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[AISystemClassName](ue_ue.AISystemBase.md#aisystemclassname)

___

### AISystemModuleName

• **AISystemModuleName**: `string`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[AISystemModuleName](ue_ue.AISystemBase.md#aisystemmodulename)

___

### AcceptanceRadius

• **AcceptanceRadius**: `number`

___

### AllProxyObjects

• **AllProxyObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIAsyncTaskBlueprintProxy`](ue_ue.AIAsyncTaskBlueprintProxy.md)\>

___

### BehaviorTreeManager

• **BehaviorTreeManager**: [`BehaviorTreeManager`](ue_ue.BehaviorTreeManager.md)

___

### DefaultSightCollisionChannel

• **DefaultSightCollisionChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

___

### EnvironmentQueryManager

• **EnvironmentQueryManager**: [`EnvQueryManager`](ue_ue.EnvQueryManager.md)

___

### HotSpotManager

• **HotSpotManager**: [`AIHotSpotManager`](ue_ue.AIHotSpotManager.md)

___

### HotSpotManagerClassName

• **HotSpotManagerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### NavLocalGrids

• **NavLocalGrids**: [`NavLocalGridManager`](ue_ue.NavLocalGridManager.md)

___

### PathfollowingNavLinkAcceptanceRadius

• **PathfollowingNavLinkAcceptanceRadius**: `number`

___

### PathfollowingRegularPathPointAcceptanceRadius

• **PathfollowingRegularPathPointAcceptanceRadius**: `number`

___

### PerceptionSystem

• **PerceptionSystem**: [`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

___

### PerceptionSystemClassName

• **PerceptionSystemClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### \_\_tid\_AISystemBase\_\_

• **\_\_tid\_AISystemBase\_\_**: `boolean`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[__tid_AISystemBase__](ue_ue.AISystemBase.md#__tid_aisystembase__)

___

### \_\_tid\_AISystem\_\_

• **\_\_tid\_AISystem\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[__tid_Object__](ue_ue.AISystemBase.md#__tid_object__)

___

### bAcceptPartialPaths

• **bAcceptPartialPaths**: `boolean`

___

### bAllowControllersAsEQSQuerier

• **bAllowControllersAsEQSQuerier**: `boolean`

___

### bAllowStrafing

• **bAllowStrafing**: `boolean`

___

### bEnableBTAITasks

• **bEnableBTAITasks**: `boolean`

___

### bEnableDebuggerPlugin

• **bEnableDebuggerPlugin**: `boolean`

___

### bFinishMoveOnGoalOverlap

• **bFinishMoveOnGoalOverlap**: `boolean`

___

### bInstantiateAISystemOnClient

• **bInstantiateAISystemOnClient**: `boolean`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[bInstantiateAISystemOnClient](ue_ue.AISystemBase.md#binstantiateaisystemonclient)

## Methods

### AIIgnorePlayers

▸ **AIIgnorePlayers**(): `void`

#### Returns

`void`

___

### AILoggingVerbose

▸ **AILoggingVerbose**(): `void`

#### Returns

`void`

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

[AISystemBase](ue_ue.AISystemBase.md).[CreateDefaultSubobject](ue_ue.AISystemBase.md#createdefaultsubobject)

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

[AISystemBase](ue_ue.AISystemBase.md).[ExecuteUbergraph](ue_ue.AISystemBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[GetClass](ue_ue.AISystemBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[GetName](ue_ue.AISystemBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[GetOuter](ue_ue.AISystemBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[GetWorld](ue_ue.AISystemBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AISystem`](ue_ue.AISystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AISystem`](ue_ue.AISystem.md)

#### Overrides

[AISystemBase](ue_ue.AISystemBase.md).[Find](ue_ue.AISystemBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AISystem`](ue_ue.AISystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AISystem`](ue_ue.AISystem.md)

#### Overrides

[AISystemBase](ue_ue.AISystemBase.md).[Load](ue_ue.AISystemBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISystemBase](ue_ue.AISystemBase.md).[StaticClass](ue_ue.AISystemBase.md#staticclass)
