[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvTraceData

# Class: EnvTraceData

[ue/ue](../modules/ue_ue.md).EnvTraceData

## Table of contents

### Constructors

- [constructor](ue_ue.EnvTraceData.md#constructor)

### Properties

- [ExtentX](ue_ue.EnvTraceData.md#extentx)
- [ExtentY](ue_ue.EnvTraceData.md#extenty)
- [ExtentZ](ue_ue.EnvTraceData.md#extentz)
- [NavigationFilter](ue_ue.EnvTraceData.md#navigationfilter)
- [PostProjectionVerticalOffset](ue_ue.EnvTraceData.md#postprojectionverticaloffset)
- [ProjectDown](ue_ue.EnvTraceData.md#projectdown)
- [ProjectUp](ue_ue.EnvTraceData.md#projectup)
- [SerializedChannel](ue_ue.EnvTraceData.md#serializedchannel)
- [TraceChannel](ue_ue.EnvTraceData.md#tracechannel)
- [TraceMode](ue_ue.EnvTraceData.md#tracemode)
- [TraceShape](ue_ue.EnvTraceData.md#traceshape)
- [VersionNum](ue_ue.EnvTraceData.md#versionnum)
- [\_\_tid\_EnvTraceData\_\_](ue_ue.EnvTraceData.md#__tid_envtracedata__)
- [bCanDisableTrace](ue_ue.EnvTraceData.md#bcandisabletrace)
- [bCanProjectDown](ue_ue.EnvTraceData.md#bcanprojectdown)
- [bCanTraceOnGeometry](ue_ue.EnvTraceData.md#bcantraceongeometry)
- [bCanTraceOnNavMesh](ue_ue.EnvTraceData.md#bcantraceonnavmesh)
- [bOnlyBlockingHits](ue_ue.EnvTraceData.md#bonlyblockinghits)
- [bTraceComplex](ue_ue.EnvTraceData.md#btracecomplex)

### Methods

- [StaticClass](ue_ue.EnvTraceData.md#staticclass)
- [StaticStruct](ue_ue.EnvTraceData.md#staticstruct)

## Constructors

### constructor

• **new EnvTraceData**()

#### Defined in

[ue/ue.d.ts:34284](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34284)

• **new EnvTraceData**(`VersionNum`, `NavigationFilter`, `ProjectDown`, `ProjectUp`, `ExtentX`, `ExtentY`, `ExtentZ`, `PostProjectionVerticalOffset`, `TraceChannel`, `SerializedChannel`, `TraceShape`, `TraceMode`, `bTraceComplex`, `bOnlyBlockingHits`, `bCanTraceOnNavMesh`, `bCanTraceOnGeometry`, `bCanDisableTrace`, `bCanProjectDown`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VersionNum` | `number` |
| `NavigationFilter` | [`Class`](ue_ue.Class.md) |
| `ProjectDown` | `number` |
| `ProjectUp` | `number` |
| `ExtentX` | `number` |
| `ExtentY` | `number` |
| `ExtentZ` | `number` |
| `PostProjectionVerticalOffset` | `number` |
| `TraceChannel` | [`ETraceTypeQuery`](../enums/ue_ue.ETraceTypeQuery.md) |
| `SerializedChannel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |
| `TraceShape` | [`EEnvTraceShape`](../enums/ue_ue.EEnvTraceShape.md) |
| `TraceMode` | [`EEnvQueryTrace`](../enums/ue_ue.EEnvQueryTrace.md) |
| `bTraceComplex` | `boolean` |
| `bOnlyBlockingHits` | `boolean` |
| `bCanTraceOnNavMesh` | `boolean` |
| `bCanTraceOnGeometry` | `boolean` |
| `bCanDisableTrace` | `boolean` |
| `bCanProjectDown` | `boolean` |

#### Defined in

[ue/ue.d.ts:34285](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34285)

## Properties

### ExtentX

• **ExtentX**: `number`

#### Defined in

[ue/ue.d.ts:34290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34290)

___

### ExtentY

• **ExtentY**: `number`

#### Defined in

[ue/ue.d.ts:34291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34291)

___

### ExtentZ

• **ExtentZ**: `number`

#### Defined in

[ue/ue.d.ts:34292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34292)

___

### NavigationFilter

• **NavigationFilter**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:34287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34287)

___

### PostProjectionVerticalOffset

• **PostProjectionVerticalOffset**: `number`

#### Defined in

[ue/ue.d.ts:34293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34293)

___

### ProjectDown

• **ProjectDown**: `number`

#### Defined in

[ue/ue.d.ts:34288](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34288)

___

### ProjectUp

• **ProjectUp**: `number`

#### Defined in

[ue/ue.d.ts:34289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34289)

___

### SerializedChannel

• **SerializedChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Defined in

[ue/ue.d.ts:34295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34295)

___

### TraceChannel

• **TraceChannel**: [`ETraceTypeQuery`](../enums/ue_ue.ETraceTypeQuery.md)

#### Defined in

[ue/ue.d.ts:34294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34294)

___

### TraceMode

• **TraceMode**: [`EEnvQueryTrace`](../enums/ue_ue.EEnvQueryTrace.md)

#### Defined in

[ue/ue.d.ts:34297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34297)

___

### TraceShape

• **TraceShape**: [`EEnvTraceShape`](../enums/ue_ue.EEnvTraceShape.md)

#### Defined in

[ue/ue.d.ts:34296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34296)

___

### VersionNum

• **VersionNum**: `number`

#### Defined in

[ue/ue.d.ts:34286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34286)

___

### \_\_tid\_EnvTraceData\_\_

• `Private` **\_\_tid\_EnvTraceData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:34309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34309)

___

### bCanDisableTrace

• **bCanDisableTrace**: `boolean`

#### Defined in

[ue/ue.d.ts:34302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34302)

___

### bCanProjectDown

• **bCanProjectDown**: `boolean`

#### Defined in

[ue/ue.d.ts:34303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34303)

___

### bCanTraceOnGeometry

• **bCanTraceOnGeometry**: `boolean`

#### Defined in

[ue/ue.d.ts:34301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34301)

___

### bCanTraceOnNavMesh

• **bCanTraceOnNavMesh**: `boolean`

#### Defined in

[ue/ue.d.ts:34300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34300)

___

### bOnlyBlockingHits

• **bOnlyBlockingHits**: `boolean`

#### Defined in

[ue/ue.d.ts:34299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34299)

___

### bTraceComplex

• **bTraceComplex**: `boolean`

#### Defined in

[ue/ue.d.ts:34298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34298)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:34307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34307)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:34308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34308)
