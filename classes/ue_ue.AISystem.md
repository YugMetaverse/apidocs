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

#### Defined in

[ue/ue.d.ts:15670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15670)

## Properties

### AISystemClassName

• **AISystemClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[AISystemClassName](ue_ue.AISystemBase.md#aisystemclassname)

#### Defined in

[ue/ue.d.ts:10065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10065)

___

### AISystemModuleName

• **AISystemModuleName**: `string`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[AISystemModuleName](ue_ue.AISystemBase.md#aisystemmodulename)

#### Defined in

[ue/ue.d.ts:10066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10066)

___

### AcceptanceRadius

• **AcceptanceRadius**: `number`

#### Defined in

[ue/ue.d.ts:15673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15673)

___

### AllProxyObjects

• **AllProxyObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIAsyncTaskBlueprintProxy`](ue_ue.AIAsyncTaskBlueprintProxy.md)\>

#### Defined in

[ue/ue.d.ts:15686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15686)

___

### BehaviorTreeManager

• **BehaviorTreeManager**: [`BehaviorTreeManager`](ue_ue.BehaviorTreeManager.md)

#### Defined in

[ue/ue.d.ts:15683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15683)

___

### DefaultSightCollisionChannel

• **DefaultSightCollisionChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Defined in

[ue/ue.d.ts:15682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15682)

___

### EnvironmentQueryManager

• **EnvironmentQueryManager**: [`EnvQueryManager`](ue_ue.EnvQueryManager.md)

#### Defined in

[ue/ue.d.ts:15684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15684)

___

### HotSpotManager

• **HotSpotManager**: [`AIHotSpotManager`](ue_ue.AIHotSpotManager.md)

#### Defined in

[ue/ue.d.ts:15687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15687)

___

### HotSpotManagerClassName

• **HotSpotManagerClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:15672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15672)

___

### NavLocalGrids

• **NavLocalGrids**: [`NavLocalGridManager`](ue_ue.NavLocalGridManager.md)

#### Defined in

[ue/ue.d.ts:15688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15688)

___

### PathfollowingNavLinkAcceptanceRadius

• **PathfollowingNavLinkAcceptanceRadius**: `number`

#### Defined in

[ue/ue.d.ts:15675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15675)

___

### PathfollowingRegularPathPointAcceptanceRadius

• **PathfollowingRegularPathPointAcceptanceRadius**: `number`

#### Defined in

[ue/ue.d.ts:15674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15674)

___

### PerceptionSystem

• **PerceptionSystem**: [`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

#### Defined in

[ue/ue.d.ts:15685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15685)

___

### PerceptionSystemClassName

• **PerceptionSystemClassName**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Defined in

[ue/ue.d.ts:15671](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15671)

___

### \_\_tid\_AISystemBase\_\_

• **\_\_tid\_AISystemBase\_\_**: `boolean`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[__tid_AISystemBase__](ue_ue.AISystemBase.md#__tid_aisystembase__)

#### Defined in

[ue/ue.d.ts:10072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10072)

___

### \_\_tid\_AISystem\_\_

• **\_\_tid\_AISystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15695](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15695)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[__tid_Object__](ue_ue.AISystemBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAcceptPartialPaths

• **bAcceptPartialPaths**: `boolean`

#### Defined in

[ue/ue.d.ts:15677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15677)

___

### bAllowControllersAsEQSQuerier

• **bAllowControllersAsEQSQuerier**: `boolean`

#### Defined in

[ue/ue.d.ts:15680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15680)

___

### bAllowStrafing

• **bAllowStrafing**: `boolean`

#### Defined in

[ue/ue.d.ts:15678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15678)

___

### bEnableBTAITasks

• **bEnableBTAITasks**: `boolean`

#### Defined in

[ue/ue.d.ts:15679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15679)

___

### bEnableDebuggerPlugin

• **bEnableDebuggerPlugin**: `boolean`

#### Defined in

[ue/ue.d.ts:15681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15681)

___

### bFinishMoveOnGoalOverlap

• **bFinishMoveOnGoalOverlap**: `boolean`

#### Defined in

[ue/ue.d.ts:15676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15676)

___

### bInstantiateAISystemOnClient

• **bInstantiateAISystemOnClient**: `boolean`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[bInstantiateAISystemOnClient](ue_ue.AISystemBase.md#binstantiateaisystemonclient)

#### Defined in

[ue/ue.d.ts:10067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10067)

## Methods

### AIIgnorePlayers

▸ **AIIgnorePlayers**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15689)

___

### AILoggingVerbose

▸ **AILoggingVerbose**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15690)

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

[AISystemBase](ue_ue.AISystemBase.md).[ExecuteUbergraph](ue_ue.AISystemBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[GetClass](ue_ue.AISystemBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[GetName](ue_ue.AISystemBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[GetOuter](ue_ue.AISystemBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AISystemBase](ue_ue.AISystemBase.md).[GetWorld](ue_ue.AISystemBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:15692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15692)

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

#### Defined in

[ue/ue.d.ts:15693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15693)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISystemBase](ue_ue.AISystemBase.md).[StaticClass](ue_ue.AISystemBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:15691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15691)
