[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleAccelerationDrag

# Class: ParticleModuleAccelerationDrag

[ue/ue](../modules/ue_ue.md).ParticleModuleAccelerationDrag

## Hierarchy

- [`ParticleModuleAccelerationBase`](ue_ue.ParticleModuleAccelerationBase.md)

  ↳ **`ParticleModuleAccelerationDrag`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleAccelerationDrag.md#constructor)

### Properties

- [DragCoefficient](ue_ue.ParticleModuleAccelerationDrag.md#dragcoefficient)
- [DragCoefficientRaw](ue_ue.ParticleModuleAccelerationDrag.md#dragcoefficientraw)
- [LODDuplicate](ue_ue.ParticleModuleAccelerationDrag.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleAccelerationDrag.md#lodvalidity)
- [ModuleEditorColor](ue_ue.ParticleModuleAccelerationDrag.md#moduleeditorcolor)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleAccelerationDrag.md#__tid_object__)
- [\_\_tid\_ParticleModuleAccelerationBase\_\_](ue_ue.ParticleModuleAccelerationDrag.md#__tid_particlemoduleaccelerationbase__)
- [\_\_tid\_ParticleModuleAccelerationDrag\_\_](ue_ue.ParticleModuleAccelerationDrag.md#__tid_particlemoduleaccelerationdrag__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleAccelerationDrag.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleAccelerationDrag.md#b3ddrawmode)
- [bAlwaysInWorldSpace](ue_ue.ParticleModuleAccelerationDrag.md#balwaysinworldspace)
- [bCurvesAsColor](ue_ue.ParticleModuleAccelerationDrag.md#bcurvesascolor)
- [bEditable](ue_ue.ParticleModuleAccelerationDrag.md#beditable)
- [bEnabled](ue_ue.ParticleModuleAccelerationDrag.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleAccelerationDrag.md#bfinalupdatemodule)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleAccelerationDrag.md#brequiresloopingnotification)
- [bSpawnModule](ue_ue.ParticleModuleAccelerationDrag.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleAccelerationDrag.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleAccelerationDrag.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleAccelerationDrag.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleAccelerationDrag.md#bupdatemodule)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleAccelerationDrag.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleAccelerationDrag.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleAccelerationDrag.md#getclass)
- [GetName](ue_ue.ParticleModuleAccelerationDrag.md#getname)
- [GetOuter](ue_ue.ParticleModuleAccelerationDrag.md#getouter)
- [GetWorld](ue_ue.ParticleModuleAccelerationDrag.md#getworld)
- [Find](ue_ue.ParticleModuleAccelerationDrag.md#find)
- [Load](ue_ue.ParticleModuleAccelerationDrag.md#load)
- [StaticClass](ue_ue.ParticleModuleAccelerationDrag.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleAccelerationDrag**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[constructor](ue_ue.ParticleModuleAccelerationBase.md#constructor)

#### Defined in

[ue/ue.d.ts:55270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55270)

## Properties

### DragCoefficient

• **DragCoefficient**: [`DistributionFloat`](ue_ue.DistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55271)

___

### DragCoefficientRaw

• **DragCoefficientRaw**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:55272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55272)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[LODDuplicate](ue_ue.ParticleModuleAccelerationBase.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[LODValidity](ue_ue.ParticleModuleAccelerationBase.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6748)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[ModuleEditorColor](ue_ue.ParticleModuleAccelerationBase.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6749)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[__tid_Object__](ue_ue.ParticleModuleAccelerationBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleAccelerationBase\_\_

• **\_\_tid\_ParticleModuleAccelerationBase\_\_**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[__tid_ParticleModuleAccelerationBase__](ue_ue.ParticleModuleAccelerationBase.md#__tid_particlemoduleaccelerationbase__)

#### Defined in

[ue/ue.d.ts:55245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55245)

___

### \_\_tid\_ParticleModuleAccelerationDrag\_\_

• **\_\_tid\_ParticleModuleAccelerationDrag\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:55277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55277)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[__tid_ParticleModule__](ue_ue.ParticleModuleAccelerationBase.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[b3DDrawMode](ue_ue.ParticleModuleAccelerationBase.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6741)

___

### bAlwaysInWorldSpace

• **bAlwaysInWorldSpace**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bAlwaysInWorldSpace](ue_ue.ParticleModuleAccelerationBase.md#balwaysinworldspace)

#### Defined in

[ue/ue.d.ts:55240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55240)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bCurvesAsColor](ue_ue.ParticleModuleAccelerationBase.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6740)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bEditable](ue_ue.ParticleModuleAccelerationBase.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6744)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bEnabled](ue_ue.ParticleModuleAccelerationBase.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bFinalUpdateModule](ue_ue.ParticleModuleAccelerationBase.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6738)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bRequiresLoopingNotification](ue_ue.ParticleModuleAccelerationBase.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6747)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bSpawnModule](ue_ue.ParticleModuleAccelerationBase.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bSupported3DDrawMode](ue_ue.ParticleModuleAccelerationBase.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bSupportsRandomSeed](ue_ue.ParticleModuleAccelerationBase.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bUpdateForGPUEmitter](ue_ue.ParticleModuleAccelerationBase.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[bUpdateModule](ue_ue.ParticleModuleAccelerationBase.md#bupdatemodule)

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

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[CreateDefaultSubobject](ue_ue.ParticleModuleAccelerationBase.md#createdefaultsubobject)

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

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[ExecuteUbergraph](ue_ue.ParticleModuleAccelerationBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[GetClass](ue_ue.ParticleModuleAccelerationBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[GetName](ue_ue.ParticleModuleAccelerationBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[GetOuter](ue_ue.ParticleModuleAccelerationBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[GetWorld](ue_ue.ParticleModuleAccelerationBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleAccelerationDrag`](ue_ue.ParticleModuleAccelerationDrag.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleAccelerationDrag`](ue_ue.ParticleModuleAccelerationDrag.md)

#### Overrides

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[Find](ue_ue.ParticleModuleAccelerationBase.md#find)

#### Defined in

[ue/ue.d.ts:55274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55274)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleAccelerationDrag`](ue_ue.ParticleModuleAccelerationDrag.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleAccelerationDrag`](ue_ue.ParticleModuleAccelerationDrag.md)

#### Overrides

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[Load](ue_ue.ParticleModuleAccelerationBase.md#load)

#### Defined in

[ue/ue.d.ts:55275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55275)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModuleAccelerationBase](ue_ue.ParticleModuleAccelerationBase.md).[StaticClass](ue_ue.ParticleModuleAccelerationBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:55273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L55273)
