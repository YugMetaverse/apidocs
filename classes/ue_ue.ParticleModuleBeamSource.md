[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleBeamSource

# Class: ParticleModuleBeamSource

[ue/ue](../modules/ue_ue.md).ParticleModuleBeamSource

## Hierarchy

- [`ParticleModuleBeamBase`](ue_ue.ParticleModuleBeamBase.md)

  ↳ **`ParticleModuleBeamSource`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleBeamSource.md#constructor)

### Properties

- [LODDuplicate](ue_ue.ParticleModuleBeamSource.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleBeamSource.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleBeamSource.md#moduleeditorcolor)
- [Source](ue_ue.ParticleModuleBeamSource.md#source)
- [SourceMethod](ue_ue.ParticleModuleBeamSource.md#sourcemethod)
- [SourceName](ue_ue.ParticleModuleBeamSource.md#sourcename)
- [SourceStrength](ue_ue.ParticleModuleBeamSource.md#sourcestrength)
- [SourceTangent](ue_ue.ParticleModuleBeamSource.md#sourcetangent)
- [SourceTangentMethod](ue_ue.ParticleModuleBeamSource.md#sourcetangentmethod)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleBeamSource.md#__tid_object__)
- [\_\_tid\_ParticleModuleBeamBase\_\_](ue_ue.ParticleModuleBeamSource.md#__tid_particlemodulebeambase__)
- [\_\_tid\_ParticleModuleBeamSource\_\_](ue_ue.ParticleModuleBeamSource.md#__tid_particlemodulebeamsource__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleBeamSource.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleBeamSource.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleBeamSource.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleBeamSource.md#beditable)
- [bEnabled](ue_ue.ParticleModuleBeamSource.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleBeamSource.md#bfinalupdatemodule)
- [bLockSource](ue_ue.ParticleModuleBeamSource.md#blocksource)
- [bLockSourceStength](ue_ue.ParticleModuleBeamSource.md#blocksourcestength)
- [bLockSourceTangent](ue_ue.ParticleModuleBeamSource.md#blocksourcetangent)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleBeamSource.md#brequiresloopingnotification)
- [bSourceAbsolute](ue_ue.ParticleModuleBeamSource.md#bsourceabsolute)
- [bSpawnModule](ue_ue.ParticleModuleBeamSource.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleBeamSource.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleBeamSource.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleBeamSource.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleBeamSource.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleBeamSource.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleBeamSource.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleBeamSource.md#getclass)
- [GetName](ue_ue.ParticleModuleBeamSource.md#getname)
- [GetOuter](ue_ue.ParticleModuleBeamSource.md#getouter)
- [GetWorld](ue_ue.ParticleModuleBeamSource.md#getworld)
- [Find](ue_ue.ParticleModuleBeamSource.md#find)
- [Load](ue_ue.ParticleModuleBeamSource.md#load)
- [StaticClass](ue_ue.ParticleModuleBeamSource.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleBeamSource**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[constructor](ue_ue.ParticleModuleBeamBase.md#constructor)

#### Defined in

[ue/ue.d.ts:55446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55446)

## Properties

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[LODDuplicate](ue_ue.ParticleModuleBeamBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[LODValidity](ue_ue.ParticleModuleBeamBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6748)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[ModuleEditorColor](ue_ue.ParticleModuleBeamBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6749)

___

### Source

• **Source**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:55450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55450)

___

### SourceMethod

• **SourceMethod**: [`Beam2SourceTargetMethod`](../enums/ue_ue.Beam2SourceTargetMethod.md)

#### Defined in

[ue/ue.d.ts:55447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55447)

___

### SourceName

• **SourceName**: `string`

#### Defined in

[ue/ue.d.ts:55448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55448)

___

### SourceStrength

• **SourceStrength**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55455)

___

### SourceTangent

• **SourceTangent**: [`RawDistributionVector`](ue_ue.RawDistributionVector.md)

#### Defined in

[ue/ue.d.ts:55453](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55453)

___

### SourceTangentMethod

• **SourceTangentMethod**: [`Beam2SourceTargetTangentMethod`](../enums/ue_ue.Beam2SourceTargetTangentMethod.md)

#### Defined in

[ue/ue.d.ts:55452](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55452)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_Object__](ue_ue.ParticleModuleBeamBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleBeamBase\_\_

• **\_\_tid\_ParticleModuleBeamBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_ParticleModuleBeamBase__](ue_ue.ParticleModuleBeamBase.md#__tid_particlemodulebeambase__)

#### Defined in

[ue/ue.d.ts:55382](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55382)

___

### \_\_tid\_ParticleModuleBeamSource\_\_

• **\_\_tid\_ParticleModuleBeamSource\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:55461](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55461)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleBeamBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[b3DDrawMode](ue_ue.ParticleModuleBeamBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6741)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bCurvesAsColor](ue_ue.ParticleModuleBeamBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bEditable](ue_ue.ParticleModuleBeamBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bEnabled](ue_ue.ParticleModuleBeamBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleBeamBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6738)

___

### bLockSource

• **bLockSource**: `boolean`

#### Defined in

[ue/ue.d.ts:55451](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55451)

___

### bLockSourceStength

• **bLockSourceStength**: `boolean`

#### Defined in

[ue/ue.d.ts:55456](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55456)

___

### bLockSourceTangent

• **bLockSourceTangent**: `boolean`

#### Defined in

[ue/ue.d.ts:55454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55454)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleBeamBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6747)

___

### bSourceAbsolute

• **bSourceAbsolute**: `boolean`

#### Defined in

[ue/ue.d.ts:55449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55449)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSpawnModule](ue_ue.ParticleModuleBeamBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleBeamBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleBeamBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleBeamBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[bUpdateModule](ue_ue.ParticleModuleBeamBase.md#bupdatemodule)

#### Defined in

[ue/ue.d.ts:6737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6737)

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

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleBeamBase.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleBeamBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetClass](ue_ue.ParticleModuleBeamBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetName](ue_ue.ParticleModuleBeamBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetOuter](ue_ue.ParticleModuleBeamBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[GetWorld](ue_ue.ParticleModuleBeamBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleBeamSource`](ue_ue.ParticleModuleBeamSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleBeamSource`](ue_ue.ParticleModuleBeamSource.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[Find](ue_ue.ParticleModuleBeamBase.md#find)

#### Defined in

[ue/ue.d.ts:55458](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55458)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleBeamSource`](ue_ue.ParticleModuleBeamSource.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleBeamSource`](ue_ue.ParticleModuleBeamSource.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[Load](ue_ue.ParticleModuleBeamBase.md#load)

#### Defined in

[ue/ue.d.ts:55459](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55459)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleBeamBase](ue_ue.ParticleModuleBeamBase.md).[StaticClass](ue_ue.ParticleModuleBeamBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:55457](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55457)
