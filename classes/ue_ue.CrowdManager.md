[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CrowdManager

# Class: CrowdManager

[ue/ue](../modules/ue_ue.md).CrowdManager

## Hierarchy

- [`CrowdManagerBase`](ue_ue.CrowdManagerBase.md)

  ↳ **`CrowdManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.CrowdManager.md#constructor)

### Properties

- [AvoidanceConfig](ue_ue.CrowdManager.md#avoidanceconfig)
- [MaxAgentRadius](ue_ue.CrowdManager.md#maxagentradius)
- [MaxAgents](ue_ue.CrowdManager.md#maxagents)
- [MaxAvoidedAgents](ue_ue.CrowdManager.md#maxavoidedagents)
- [MaxAvoidedWalls](ue_ue.CrowdManager.md#maxavoidedwalls)
- [MyNavData](ue_ue.CrowdManager.md#mynavdata)
- [NavmeshCheckInterval](ue_ue.CrowdManager.md#navmeshcheckinterval)
- [PathOffsetRadiusMultiplier](ue_ue.CrowdManager.md#pathoffsetradiusmultiplier)
- [PathOptimizationInterval](ue_ue.CrowdManager.md#pathoptimizationinterval)
- [SamplingPatterns](ue_ue.CrowdManager.md#samplingpatterns)
- [SeparationDirClamp](ue_ue.CrowdManager.md#separationdirclamp)
- [\_\_tid\_CrowdManagerBase\_\_](ue_ue.CrowdManager.md#__tid_crowdmanagerbase__)
- [\_\_tid\_CrowdManager\_\_](ue_ue.CrowdManager.md#__tid_crowdmanager__)
- [\_\_tid\_Object\_\_](ue_ue.CrowdManager.md#__tid_object__)
- [bResolveCollisions](ue_ue.CrowdManager.md#bresolvecollisions)

### Methods

- [CreateDefaultSubobject](ue_ue.CrowdManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CrowdManager.md#executeubergraph)
- [GetClass](ue_ue.CrowdManager.md#getclass)
- [GetName](ue_ue.CrowdManager.md#getname)
- [GetOuter](ue_ue.CrowdManager.md#getouter)
- [GetWorld](ue_ue.CrowdManager.md#getworld)
- [Find](ue_ue.CrowdManager.md#find)
- [Load](ue_ue.CrowdManager.md#load)
- [StaticClass](ue_ue.CrowdManager.md#staticclass)

## Constructors

### constructor

• **new CrowdManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[constructor](ue_ue.CrowdManagerBase.md#constructor)

#### Defined in

[ue/ue.d.ts:28906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28906)

## Properties

### AvoidanceConfig

• **AvoidanceConfig**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CrowdAvoidanceConfig`](ue_ue.CrowdAvoidanceConfig.md)\>

#### Defined in

[ue/ue.d.ts:28908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28908)

___

### MaxAgentRadius

• **MaxAgentRadius**: `number`

#### Defined in

[ue/ue.d.ts:28911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28911)

___

### MaxAgents

• **MaxAgents**: `number`

#### Defined in

[ue/ue.d.ts:28910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28910)

___

### MaxAvoidedAgents

• **MaxAvoidedAgents**: `number`

#### Defined in

[ue/ue.d.ts:28912](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28912)

___

### MaxAvoidedWalls

• **MaxAvoidedWalls**: `number`

#### Defined in

[ue/ue.d.ts:28913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28913)

___

### MyNavData

• **MyNavData**: [`NavigationData`](ue_ue.NavigationData.md)

#### Defined in

[ue/ue.d.ts:28907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28907)

___

### NavmeshCheckInterval

• **NavmeshCheckInterval**: `number`

#### Defined in

[ue/ue.d.ts:28914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28914)

___

### PathOffsetRadiusMultiplier

• **PathOffsetRadiusMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:28917](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28917)

___

### PathOptimizationInterval

• **PathOptimizationInterval**: `number`

#### Defined in

[ue/ue.d.ts:28915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28915)

___

### SamplingPatterns

• **SamplingPatterns**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CrowdAvoidanceSamplingPattern`](ue_ue.CrowdAvoidanceSamplingPattern.md)\>

#### Defined in

[ue/ue.d.ts:28909](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28909)

___

### SeparationDirClamp

• **SeparationDirClamp**: `number`

#### Defined in

[ue/ue.d.ts:28916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28916)

___

### \_\_tid\_CrowdManagerBase\_\_

• **\_\_tid\_CrowdManagerBase\_\_**: `boolean`

#### Inherited from

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[__tid_CrowdManagerBase__](ue_ue.CrowdManagerBase.md#__tid_crowdmanagerbase__)

#### Defined in

[ue/ue.d.ts:28868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28868)

___

### \_\_tid\_CrowdManager\_\_

• **\_\_tid\_CrowdManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28923](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28923)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[__tid_Object__](ue_ue.CrowdManagerBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bResolveCollisions

• **bResolveCollisions**: `boolean`

#### Defined in

[ue/ue.d.ts:28918](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28918)

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

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[CreateDefaultSubobject](ue_ue.CrowdManagerBase.md#createdefaultsubobject)

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

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[ExecuteUbergraph](ue_ue.CrowdManagerBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[GetClass](ue_ue.CrowdManagerBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[GetName](ue_ue.CrowdManagerBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[GetOuter](ue_ue.CrowdManagerBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[GetWorld](ue_ue.CrowdManagerBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CrowdManager`](ue_ue.CrowdManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CrowdManager`](ue_ue.CrowdManager.md)

#### Overrides

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[Find](ue_ue.CrowdManagerBase.md#find)

#### Defined in

[ue/ue.d.ts:28920](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28920)

___

### Load

▸ `Static` **Load**(`InName`): [`CrowdManager`](ue_ue.CrowdManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CrowdManager`](ue_ue.CrowdManager.md)

#### Overrides

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[Load](ue_ue.CrowdManagerBase.md#load)

#### Defined in

[ue/ue.d.ts:28921](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28921)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CrowdManagerBase](ue_ue.CrowdManagerBase.md).[StaticClass](ue_ue.CrowdManagerBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:28919](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28919)
