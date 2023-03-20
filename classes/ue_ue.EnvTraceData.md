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

## Properties

### ExtentX

• **ExtentX**: `number`

___

### ExtentY

• **ExtentY**: `number`

___

### ExtentZ

• **ExtentZ**: `number`

___

### NavigationFilter

• **NavigationFilter**: [`Class`](ue_ue.Class.md)

___

### PostProjectionVerticalOffset

• **PostProjectionVerticalOffset**: `number`

___

### ProjectDown

• **ProjectDown**: `number`

___

### ProjectUp

• **ProjectUp**: `number`

___

### SerializedChannel

• **SerializedChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

___

### TraceChannel

• **TraceChannel**: [`ETraceTypeQuery`](../enums/ue_ue.ETraceTypeQuery.md)

___

### TraceMode

• **TraceMode**: [`EEnvQueryTrace`](../enums/ue_ue.EEnvQueryTrace.md)

___

### TraceShape

• **TraceShape**: [`EEnvTraceShape`](../enums/ue_ue.EEnvTraceShape.md)

___

### VersionNum

• **VersionNum**: `number`

___

### \_\_tid\_EnvTraceData\_\_

• `Private` **\_\_tid\_EnvTraceData\_\_**: `boolean`

___

### bCanDisableTrace

• **bCanDisableTrace**: `boolean`

___

### bCanProjectDown

• **bCanProjectDown**: `boolean`

___

### bCanTraceOnGeometry

• **bCanTraceOnGeometry**: `boolean`

___

### bCanTraceOnNavMesh

• **bCanTraceOnNavMesh**: `boolean`

___

### bOnlyBlockingHits

• **bOnlyBlockingHits**: `boolean`

___

### bTraceComplex

• **bTraceComplex**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
